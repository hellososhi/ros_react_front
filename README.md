# ros_react_front

## 環境

- Node.js v20.5.0

## セットアップ

```bash
git clone git@github.com:hellososhi/ros_react_front.git
cd ros_react_front
npm install
```

## 起動

### 開発時

```bash
npm run dev
```

### 本番

```bash
npm run build
npm run start
```

ブラウザで http://localhost:3000 にアクセスすると、画面が表示される

## ROS インターフェース

### 文字列表示

- Topic: /ros_react/string
- Type: std_msgs/String

### 画像表示

- Topic: /ros_react/image/compressed
- Type: sensor_msgs/CompressedImage
