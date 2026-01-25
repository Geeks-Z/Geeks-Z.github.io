# Hongwei Zhao's Academic Homepage

个人学术主页，使用纯静态HTML构建，托管于GitHub Pages。

## 🌐 Website

**在线访问**: [https://geeks-z.github.io](https://geeks-z.github.io)

- 🇺🇸 English: [https://geeks-z.github.io](https://geeks-z.github.io)
- 🇨🇳 中文版: [https://geeks-z.github.io/index-zh.html](https://geeks-z.github.io/index-zh.html)

## 📋 Features

- 🌍 **中英双语** - 完整的中英文版本支持
- 📐 **两栏布局** - 左侧固定边栏 + 右侧主内容区
- 📄 **学术论文** - 展示发表的论文和专利
- 🔬 **项目经历** - 详细的项目描述和成果
- 🎓 **教育背景** - 学术履历展示
- 📰 **博客系统** - 支持Markdown的简易博客
- 📱 **响应式设计** - 适配各种设备屏幕

## 📁 Project Structure

```
├── index.html           # 英文主页
├── index-zh.html        # 中文主页
├── .nojekyll            # 禁用Jekyll（使用纯静态HTML）
├── blog/                # 博客目录
│   ├── index.html       # 博客列表页
│   └── hello-world.md   # 博客文章（Markdown格式）
├── images/              # 图片资源
│   ├── profile.jpg      # 个人照片
│   ├── TALON.png        # 论文图片
│   ├── DLEPEM.png
│   ├── HyPro.png
│   └── MPE.png
├── files/               # 文件资源（CV等）
└── README.md            # 项目说明
```

## 🚀 Quick Start

### 部署到GitHub Pages

1. Fork 本仓库
2. 重命名为 `your-username.github.io`
3. 修改 `index.html` 和 `index-zh.html` 中的个人信息
4. 替换 `images/profile.jpg` 为你的照片
5. 推送更改，访问 `https://your-username.github.io`

### 本地预览

```bash
# 使用Python简易服务器
python -m http.server 8000

# 或使用VS Code Live Server插件
# 访问 http://localhost:8000
```

## ✏️ Customization

### 修改个人信息
编辑 `index.html` 和 `index-zh.html` 中的 `.sidebar` 部分

### 添加论文
在 `#publications` section 中添加新的 `.pub-item`

### 添加项目
在 `#projects` section 中添加新的 `.project-item`

### 添加博客
在 `blog/` 目录下创建新的 `.md` 文件

## 🛠️ Tech Stack

- **HTML5 + CSS3** - 纯静态页面，无需构建
- **Google Fonts** - Inter + Noto Sans SC 字体
- **Font Awesome 6.4** - 图标库
- **Academicons** - 学术图标（arXiv、Google Scholar等）
- **Marked.js** - Markdown博客渲染

## 📞 Contact

- **Email**: izhw1024@163.com
- **GitHub**: [Geeks-Z](https://github.com/Geeks-Z)
- **Google Scholar**: [Profile](https://scholar.google.com/citations?user=YOUR_ID)

## 📜 License

MIT License
