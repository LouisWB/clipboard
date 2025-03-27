<<<<<<< HEAD
# Clipboard Share

跨平台剪贴板共享应用，支持在不同设备间快速共享剪贴板内容（文本和图片）。

## 功能特点

- 支持局域网和互联网跨设备共享
- 支持多终端同步（电脑、手机）
- 支持会话机制，可以创建独立的共享组
- 支持图片和文本格式
- 电脑端支持直接粘贴
- 手机端支持图片保存到相册

## 技术栈

- 后端：Node.js + Express + Socket.IO + Redis
- Web端：React + Vite
- 移动端：React Native
- 桌面端：Electron

## 安装说明

1. 安装依赖
```bash
npm install
```

2. 启动Redis服务器
确保本地Redis服务器正在运行，或者在.env文件中配置远程Redis服务器地址。

3. 启动服务器
```bash
npm start
```

## 开发说明

- 启动开发服务器：`npm run dev`
- 启动Web客户端：`npm run web`
- 启动移动端：`npm run mobile`
- 启动桌面端：`npm run desktop`

## 使用说明

1. 创建或加入会话
2. 在任意设备上复制内容
3. 内容会自动同步到同一会话中的其他设备
4. 在电脑端可以直接粘贴使用
5. 在手机端可以查看或保存图片

## 许可证

MIT
=======
# clipboard
>>>>>>> e01693e (Initial commit)
