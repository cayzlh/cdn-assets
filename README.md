# CDN Assets - 静态资源库

## 仓库介绍

这是一个用于存放静态资源的仓库，包含图片、CSS、JS等文件。所有资源均通过 Cloudflare CDN 加速，确保全球访问速度。

## CDN 加速地址

- **主地址**：https://cdn-assets-2ch.pages.dev
- **备用地址**：https://cdn-cf.cayzlh.com

## 使用方法

### 1. 直接访问文件

格式：`CDN地址/文件路径`

示例：
```
https://cdn-assets-2ch.pages.dev/image/avatar.png
```

### 2. 在网页中引用

```html
<!-- 引用图片 -->
<img src="https://cdn-assets-2ch.pages.dev/image/avatar.png" alt="头像">

<!-- 引用CSS -->
<link rel="stylesheet" href="https://cdn-assets-2ch.pages.dev/css/style.css">

<!-- 引用JS -->
<script src="https://cdn-assets-2ch.pages.dev/js/tools_main.js"></script>
```

## 目录结构

```
/ (根目录)
├── 2021/          # 2021年的资源
├── 2022/          # 2022年的资源
├── blog/          # 博客相关资源
├── covers/        # 封面图片
├── css/           # CSS文件
├── font/          # 字体文件
├── image/         # 图片资源
├── images/        # 图片资源
├── js/            # JavaScript文件
├── logo/          # Logo文件
├── picgo/         # PicGo相关资源
├── uPic/          # uPic相关资源
├── README.md      # 说明文件
└── index.html     # 主页
```

## 常用文件示例

### 图片资源
- 头像：https://cdn-assets-2ch.pages.dev/image/avatar.png
- 背景图：https://cdn-assets-2ch.pages.dev/image/bg.jpg
- Logo：https://cdn-assets-2ch.pages.dev/logo/logo.png

### CSS 文件
- 样式文件：https://cdn-assets-2ch.pages.dev/css/style.css
- 字体样式：https://cdn-assets-2ch.pages.dev/css/cayzlh-zfont.css

### JS 文件
- 工具脚本：https://cdn-assets-2ch.pages.dev/js/tools_main.js
- 点击爱心效果：https://cdn-assets-2ch.pages.dev/js/clicklove.js

### 封面图片
- Java 封面：https://cdn-assets-2ch.pages.dev/covers/Java.png
- Linux 封面：https://cdn-assets-2ch.pages.dev/covers/Linux.jpg
- Spring 封面：https://cdn-assets-2ch.pages.dev/covers/Spring.png

## 使用提示

1. 所有资源均已通过 Cloudflare CDN 加速，全球访问速度快
2. 建议使用主地址，备用地址可在主地址不可用时使用
3. 文件路径区分大小写，请确保路径正确
4. 如果需要添加新资源，请直接上传到对应目录

## 访问主页

您可以通过以下地址访问仓库的主页，查看更详细的使用指南：
- https://cdn-assets-2ch.pages.dev
- https://cdn-cf.cayzlh.com
