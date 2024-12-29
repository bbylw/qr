# Long Text QR Code Tool
![](https://cdn.jsdelivr.net/gh/pusvsimg/img@main/Image/20241229100113929.png)

A powerful online QR code toolkit that includes both generator and decoder, supporting compressed long text content. This project is entirely frontend-based, requiring no backend service, and can be deployed on any static hosting platform. Developed with the assistance of Windsurf AI for efficient code writing and optimization.

## Key Features

- Long Text Support: Generate QR codes with large text content (3000+ characters) using compression algorithms
- Multiple Sizes: Supports various dimensions from 256x256 to 1024x1024
- Smart Decoding: Multi-size adaptive recognition for improved decode success rate
- Unique UI Design: Inspired by Pornhub's iconic black and orange color scheme
- Modern Interface: Dark theme design for excellent visual experience and usability
- Responsive Layout: Perfect support for both mobile and desktop devices
- No Backend Required: Pure frontend implementation, deployable on any static hosting service

## Design Philosophy

The interface design adopts the popular Pornhub style, featuring:

- Dark background (#1b1b1b) with vibrant orange (#ff9000)
- Clean and modern user interface
- Eye-catching buttons and interactive elements
- Clear visual hierarchy
- Ergonomic operation flow

## Tech Stack

- Development Tools:
  - Windsurf AI assisted development for improved efficiency

- Frontend Technologies:
  - HTML5 + CSS3 + JavaScript

- Core Dependencies:
  - qrcodejs: QR code generation with multiple sizes and error correction levels
  - pako: Text compression for long content
  - jsQR: QR code decoding with multi-size recognition
  - lz-string: String compression processing

## Functional Modules

### QR Code Generator

- Supports text and URL input
- Selectable QR code sizes (256x256 to 1024x1024)
- Multiple error correction levels (L/M/Q/H)
- Real-time preview
- One-click download of generated QR code
- Character count comparison before and after compression

### QR Code Decoder

- Supports file selection and drag-and-drop upload
- Smart multi-size recognition algorithm
- Automatic compressed content recognition and decompression
- Real-time decode result display
- Clear error messages

## Usage Guide

### Generate QR Code

1. Enter the text or URL in the input box
2. Select appropriate QR code size
   - Under 3000 characters: 256x256
   - 3000-5000 characters: 512x512
   - Over 5000 characters: 1024x1024
3. Choose error correction level
   - Low (L): Suitable for less content
   - Medium (M): Default option, suitable for most cases
   - Quarter (Q): Suitable for more content
   - High (H): Suitable for very large content
4. Click "Generate QR Code" button
5. Click "Download QR Code" to save the generated image

### Decode QR Code

1. Drag and drop QR code image to decode area, or click to select file
2. System will automatically recognize and display the QR code content
3. If content is compressed, system will automatically decompress and display

## Deployment Guide

This project is deployed on Cloudflare Pages, offering the following advantages:

- Global CDN acceleration
- Automatic HTTPS
- Zero-configuration deployment
- Continuous Integration/Continuous Deployment (CI/CD)

### Deployment Steps

1. Fork this repository to your GitHub account
2. Login to Cloudflare Dashboard
3. Go to Pages section
4. Click "Create a project"
5. Choose "Connect to Git"
6. Select your forked repository
7. Configure deployment options:
   - Framework preset: None
   - Build command: Leave empty
   - Build output directory: /
   - Root directory: /
8. Click "Save and Deploy"

After deployment, Cloudflare Pages will automatically assign a domain in the format `project-name.pages.dev`

## Notes

- Choose appropriate QR code size based on text length:
  - Recommend 256x256 for under 3000 characters
  - Recommend 512x512 for 3000-5000 characters
  - Recommend 1024x1024 for over 5000 characters
- For longer text, higher error correction levels (Q or H) are recommended
- If generation fails, try increasing QR code size or lowering error correction level
- Ensure QR code image is clear when decoding, system will automatically try multiple sizes for recognition
- If decoding fails, try rescanning or using a clearer image

---

## 超长文本二维码工具

一个功能强大的在线二维码工具集，包含生成器和解码器，支持超长文本内容的压缩处理。该项目完全基于前端实现，无需后端服务，可直接部署在静态托管平台上。项目使用 Windsurf AI 辅助开发，实现了高效的代码编写和优化。

## 主要特点

- 支持超长文本：通过压缩算法处理，可生成包含大量文本的二维码（支持3000字以上）
- 多种尺寸选择：支持256x256到1024x1024的不同尺寸
- 智能解码：支持多尺寸自适应识别，提高解码成功率
- 独特UI设计：灵感来自 Pornhub 的标志性黑橙配色方案
- 现代化界面：深色主题设计，提供出色的视觉体验和易用性
- 响应式布局：完美支持移动端和桌面端
- 无需后端：纯前端实现，可部署于任意静态托管服务

## 设计理念

项目的界面设计采用了广受欢迎的 Pornhub 风格，特点是：

- 深色背景 (#1b1b1b) 搭配鲜明的橙色 (#ff9000)
- 简约现代的用户界面
- 醒目的按钮和交互元素
- 清晰的视觉层次
- 符合人体工程学的操作流程

## 技术栈

- 开发工具：
  - Windsurf AI 辅助开发，提升开发效率

- 前端技术：
  - HTML5 + CSS3 + JavaScript

- 核心依赖：
  - qrcodejs：生成二维码，支持多种尺寸和纠错级别
  - pako：实现文本压缩，支持超长文本
  - jsQR：进行二维码解码，支持多尺寸识别
  - lz-string：处理字符串压缩

## 功能模块

### 二维码生成器

- 支持文本和URL输入
- 可选二维码尺寸（256x256到1024x1024）
- 提供多级别纠错选项（L/M/Q/H）
- 支持即时预览
- 一键下载生成的二维码
- 显示压缩前后的字符数对比

### 二维码解码器

- 支持文件选择和拖拽上传
- 智能多尺寸识别算法
- 自动识别压缩内容并解压
- 实时显示解码结果
- 清晰的错误提示

## 使用说明

### 生成二维码

1. 在文本框中输入需要转换的文本或网址
2. 选择合适的二维码大小
   - 3000字以下：256x256
   - 3000-5000字：512x512
   - 5000字以上：1024x1024
3. 选择适当的纠错级别
   - 低级别 (L)：适合内容较少的场景
   - 中级别 (M)：默认选项，适合大多数场景
   - 较高级别 (Q)：适合内容较多的场景
   - 高级别 (H)：适合内容特别多的场景
4. 点击"生成二维码"按钮
5. 可以点击"下载二维码"保存生成的图片

### 解码二维码

1. 将二维码图片拖拽到解码区域，或点击区域选择文件
2. 系统会自动识别并显示二维码中的内容
3. 如果内容经过压缩，系统会自动解压显示

## 部署说明

本项目使用 Cloudflare Pages 进行部署，具有以下优势：

- 全球 CDN 加速
- 自动 HTTPS
- 零配置部署
- 持续集成/持续部署 (CI/CD)

### 部署步骤

1. Fork 本仓库到你的 GitHub 账号
2. 登录 Cloudflare Dashboard
3. 进入 Pages 页面
4. 点击 "Create a project"
5. 选择 "Connect to Git"
6. 选择你 fork 的仓库
7. 配置部署选项：
   - Framework preset: None
   - Build command: 留空
   - Build output directory: /
   - Root directory: /
8. 点击 "Save and Deploy"

部署完成后，Cloudflare Pages 会自动为你的项目分配一个域名，格式为 `项目名.pages.dev`

## 注意事项

- 根据文本长度选择合适的二维码尺寸：
  - 3000字以下：256x256
  - 3000-5000字：512x512
  - 5000字以上：1024x1024
- 文本越长，建议选择更高的纠错级别（Q或H）
- 如果生成失败，可以尝试增加二维码尺寸或降低纠错级别
- 解码时请确保二维码图片清晰可见，系统会自动尝试多种尺寸进行识别
- 如果解码失败，可以尝试重新扫描或使用更清晰的图片
