# AI Navigation - 老舅AI导航

一个精心整理的AI工具导航网站，收集了最新的AI工具和资源。

## 🌟 特色功能

- **多语言支持**: 中文和英文两个版本
- **分类清晰**: 按功能分类的AI工具导航
- **响应式设计**: 支持桌面端和移动端
- **懒加载优化**: 图片懒加载，提升加载速度
- **搜索引擎**: 集成Google、Bing、百度搜索

## 📁 项目结构

```
ai-navigation/
├── cn/                 # 中文版本
│   └── index.html
├── en/                 # 英文版本
│   └── index.html
├── assets/             # 静态资源
│   ├── css/           # 样式文件
│   ├── js/            # JavaScript文件
│   └── images/        # 图片资源
│       └── logos/     # 工具logo
├── index.html          # 主页面
└── README.md          # 项目说明
```

## 🚀 部署方式

### Cloudflare Pages 部署

1. **Fork 或 Clone 此仓库**
   ```bash
   git clone https://github.com/yourusername/ai-navigation.git
   cd ai-navigation
   ```

2. **推送到 GitHub**
   ```bash
   git add .
   git commit -m "Initial commit: AI Navigation"
   git push origin main
   ```

3. **Cloudflare Pages 部署**
   - 访问 [Cloudflare Dashboard](https://dash.cloudflare.com/)
   - 进入 "Pages" 部分
   - 点击 "Create a project"
   - 选择 "Connect to Git"
   - 选择你的 GitHub 仓库
   - 配置部署设置：
     - Build command: 留空（静态网站）
     - Build output directory: 留空（根目录）
   - 点击 "Save and Deploy"

## 🛠️ 技术栈

- **前端**: HTML5, CSS3, JavaScript
- **框架**: Bootstrap (响应式设计)
- **图标**: Linecons, Font Awesome
- **懒加载**: Lozad.js
- **部署**: Cloudflare Pages

## 📋 AI工具分类

### 中文版本 (cn/index.html)
- 通用语言模型
- AI生图
- AI办公工具
- AI学习工具
- AI音频
- AI视频制作
- AI 3D建模
- AI编程
- AI游戏
- AI情感陪伴

### 英文版本 (en/index.html)
- General Language Models
- AI Image Generation
- AI Office Tools
- AI Learning Tools
- AI Audio
- AI Video Production
- AI 3D Modeling
- AI Coding
- AI Games
- AI Emotional Companion

## 🔧 本地开发

1. **克隆项目**
   ```bash
   git clone https://github.com/yourusername/ai-navigation.git
   cd ai-navigation
   ```

2. **启动本地服务器**
   ```bash
   # 使用 Python 3
   python3 -m http.server 8000
   
   # 或使用 Node.js
   npx serve .
   ```

3. **访问网站**
   - 打开浏览器访问 `http://localhost:8000`

## 📝 更新内容

### 2025年更新
- ✅ 同步中英文版本内容
- ✅ 修复图片懒加载问题
- ✅ 更新版权信息为 "@2025 老舅AI导航"
- ✅ 优化页面布局和响应式设计

## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来改进这个项目！

## 📄 许可证

MIT License

---

**© 2025 老舅AI导航** - 让AI工具触手可及


