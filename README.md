# Long Text QR Code Tool

A powerful online QR code toolkit that includes both generator and decoder, supporting compressed long text content. Featuring a classic black and orange UI design inspired by Pornhub's iconic theme, this project is entirely frontend-based, requiring no backend service, and can be deployed on any static hosting platform.

## Key Features

 
- Long Text Support: Generate QR codes with large text content (3000+ characters) using compression algorithms
- Multi-segment Generation: Automatically split long text into segments (2000 characters limit per segment)
- Smart Decoding: Support sequential recognition of multiple QR codes, automatically merge and restore complete content
- Dark Theme: Dark background with bright text for excellent visual experience
- Responsive Layout: Perfect support for both mobile and desktop devices
- No Backend Required: Pure frontend implementation, deployable on any static hosting service
- **Classic Design**: UI and color scheme inspired by Pornhub's iconic black and orange theme
- **Frontend Only**: No backend required, can be deployed on any static hosting

## Tech Stack

### Frontend Technologies


- HTML5 + CSS3 + JavaScript

- Responsive Design

- Dark Theme UI


### Core Dependencies

- qrcodejs: QR code generation with multiple sizes and error correction levels
- lz-string: Text compression for long content support
- jsQR: QR code decoding with multi-segment recognition

- pako: Data compression processing

## Functional Modules

### QR Code Generator (index.html)
- Text Input: Support input of any length text content
- Auto Segmentation: Automatically segment text when exceeding length limit
- Compression: Use LZ-String for text compression
- Information Display:
  - Original text length
  - Compressed length
  - Compression ratio
  - Number of segments
- Download: Support downloading generated QR codes individually

### QR Code Decoder (decode.html)
- File Upload: Support drag-and-drop or file selection
- Multi-segment Processing: Support sequential processing of multiple QR codes
- Auto Decompression: Automatically recognize and decompress content
- Real-time Display: Instant display of decoded results
- Error Handling: Clear error messages

## Usage Guide

### Generate QR Code

1. Enter the text in the input box
2. System will automatically calculate and display:
   - Original text length
   - Compressed length
   - Compression ratio
   - Number of QR codes needed
3. Click "Generate QR Code" button
4. Download all generated QR codes in sequence

### Decode QR Code

1. Open the decoder tool page
2. Upload QR code images in the order they were generated
3. Wait for the system to process automatically
4. Complete content will be displayed after all QR codes are processed

## Important Notes

1. When generating QR codes:
   - Text will be automatically segmented, 2000 characters per segment
   - Save all generated QR codes in sequence
   - Use larger size to ensure scanning quality

2. When decoding QR codes:
   - Process QR codes in the exact order they were generated
   - Ensure QR code images are clear and complete
   - Wait for all QR codes to be processed before viewing complete content

## Deployment Guide

This is a static website that can be deployed on any static hosting platform:

1. Download project files:
   - index.html (Generator)
   - decode.html (Decoder)
   - README.md (Documentation)

2. Upload to static hosting service:
   - GitHub Pages
   - Vercel
   - Netlify
   - Or any web server that supports static websites

3. Access index.html to start using

## Browser Compatibility

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## License

MIT License

---

# 长文本二维码工具

一个功能强大的在线二维码工具包，包含生成器和解码器，支持压缩的长文本内容。采用经典的Pornhub黑橙配色设计风格，项目完全基于前端实现，无需后端服务，可以部署在任何静态托管平台上。

## 主要特点

 
- 支持长文本：通过压缩算法处理，可生成包含大量文本的二维码（支持3000字以上）
- 多段生成：自动将长文本分段处理，每段限制在2000字符以内
- 智能解码：支持多段二维码顺序识别，自动合并还原完整内容
- 深色主题：采用深色背景配合明亮的文字，提供出色的视觉体验
- 响应式布局：完美支持移动端和桌面端
- 无需后端：纯前端实现，可部署于任意静态托管服务
- **经典设计**：UI和配色方案源自Pornhub标志性的黑橙配色
- **纯前端实现**：无需后端，可部署于任意静态托管平台

## 技术栈

### 前端技术
- HTML5 + CSS3 + JavaScript

- Responsive Design

- Dark Theme UI


### 核心依赖

- qrcodejs：生成二维码，支持多种尺寸和纠错级别
- lz-string：实现文本压缩，支持长文本
- jsQR：进行二维码解码，支持多段识别

- pako：处理数据压缩

## 功能模块

### 二维码生成器（index.html）
- 文本输入：支持输入任意长度的文本内容
- 自动分段：超过限制长度自动分段处理
- 压缩处理：使用 LZ-String 进行文本压缩
- 信息显示：
  - 显示原始文本长度
  - 显示压缩后长度
  - 显示压缩率
  - 显示分段数量
- 下载功能：支持逐个下载生成的二维码图片

### 二维码解码器（decode.html）
- 文件上传：支持拖拽或选择文件上传
- 多段处理：支持按顺序处理多个二维码图片
- 自动解压：自动识别压缩内容并解压
- 实时显示：即时显示解码结果
- 错误处理：提供清晰的错误提示

## 使用说明

### 生成二维码

1. 在文本框中输入需要转换的文本
2. 系统会自动计算并显示：
   - 原始文本长度
   - 压缩后长度
   - 压缩率
   - 所需二维码数量
3. 点击"生成二维码"按钮
4. 按顺序下载生成的所有二维码图片

### 解码二维码

1. 打开解码工具页面
2. 按照生成顺序上传二维码图片
3. 等待系统自动处理并显示结果
4. 所有二维码处理完成后会自动显示完整内容

## 注意事项

1. 生成二维码时：
   - 文本会自动分段，每段限制在2000字符以内
   - 请按顺序保存所有生成的二维码图片
   - 建议使用较大尺寸以确保扫描质量

2. 解码二维码时：
   - 必须按照生成顺序处理二维码
   - 确保图片清晰完整
   - 等待所有二维码处理完成才能看到完整内容

## 部署说明

本项目为纯静态网页，可以部署在任何支持静态网站托管的平台上：

1. 下载项目文件：
   - index.html（生成器）
   - decode.html（解码器）
   - README.md（说明文档）

2. 上传到静态托管服务：
   - GitHub Pages
   - Vercel
   - Netlify
   - 或任何支持静态网站的服务器

3. 直接访问 index.html 即可开始使用

## 浏览器兼容性

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## 开源协议

MIT License
