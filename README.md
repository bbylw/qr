# 长文本二维码工具
![](https://cdn.jsdelivr.net/gh/pusvsimg/img@main/Image/20241229100113929.png)
一个基于网页的二维码生成和解码工具，UI 设计灵感来自 Pornhub。这个项目完全基于前端实现，无需后端服务，可以部署在任何静态托管平台上。

## 主要特性

### 生成功能
- 支持生成单个或多个二维码
- 自动压缩长文本内容
- 支持显示和复制压缩后的内容
- 多种压缩格式支持 (v1/GZIP, v2/LZ-string, v3/分段)

### 解码功能
- 支持多种解码方式：
  - 上传图片解码
  - 直接输入压缩内容解码
- 支持批量图片解码
- 自动识别压缩格式
- 支持分段二维码合并

### UI 特性
- Pornhub 风格设计
- 响应式布局
- 直观的用户界面
- 复制功能一键完成

## 使用说明

### 生成二维码
1. 在输入框中输入要生成的内容
2. 点击"生成二维码"按钮
3. 如果内容较长，会自动分段生成多个二维码
4. 可以查看并复制压缩后的内容

### 解码二维码
两种解码方式：

1. 图片解码：
   - 上传或拖拽二维码图片
   - 支持同时上传多张图片
   - 自动识别分段并合并

2. 直接输入解码：
   - 粘贴压缩后的内容
   - 点击"解码"按钮

## 技术说明

### 压缩格式
- v1: GZIP 压缩
- v2: LZ-string 压缩
- v3: 分段 LZ-string 压缩

### 使用的库
- qrcode.js: 生成二维码
- jsQR: 解码二维码
- pako: GZIP 压缩
- lz-string: 字符串压缩

## 更新日志

### 2024-12-29
- 新增压缩内容显示和复制功能
- 改进解码功能，支持两种解码方式
- 修复多图片解码的问题
- 优化解压算法，确保内容完整性

## 开发者
- bbylw

## 许可证
MIT License

---

# Long Text QR Code Tool

A web-based QR code generator and decoder tool with UI design inspired by Pornhub. This project is entirely frontend-based, requiring no backend service, and can be deployed on any static hosting platform.

## Features

### Generation
- Support generating single or multiple QR codes
- Automatically compress long text content
- Support displaying and copying compressed content
- Multiple compression formats (v1/GZIP, v2/LZ-string, v3/Segmented)

### Decoding
- Multiple decoding methods:
  - Upload image to decode
  - Direct input of compressed content
- Support batch image decoding
- Automatic compression format detection
- Support merging segmented QR codes

### UI Features
- Pornhub-style design
- Responsive layout
- Intuitive user interface
- One-click copy functionality

## Usage

### Generate QR Code
1. Enter content in the input box
2. Click "Generate QR Code" button
3. For long content, multiple QR codes will be generated automatically
4. View and copy the compressed content

### Decode QR Code
Two decoding methods:

1. Image decoding:
   - Upload or drag & drop QR code image
   - Support uploading multiple images
   - Automatically recognize and merge segments

2. Direct input decoding:
   - Paste the compressed content
   - Click "Decode" button

## Technical Details

### Compression Formats
- v1: GZIP compression
- v2: LZ-string compression
- v3: Segmented LZ-string compression

### Libraries Used
- qrcode.js: Generate QR codes
- jsQR: Decode QR codes
- pako: GZIP compression
- lz-string: String compression

## Changelog

### 2024-12-29
- Added compressed content display and copy feature
- Improved decoding with two methods
- Fixed multi-image decoding issues
- Optimized decompression algorithm for content integrity

## Developer
- bbylw

## License
MIT License
