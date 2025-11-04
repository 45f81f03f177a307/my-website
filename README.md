# SIP Tips - 个人技术分享网站

这是一个基于 [Docusaurus](https://docusaurus.io/) 构建的个人技术分享网站，专注于 SIP 协议和实时通信技术的学习笔记与开发经验分享。

## 📚 项目简介

SIP Tips 是一个现代化的技术博客和文档网站，旨在分享 SIP (Session Initiation Protocol) 相关的学习心得、开发经验和技术探索。

### ✨ 主要特色

- **📖 技术文档**：系统化的 SIP 学习笔记和技术文档
  - FreeSWITCH 相关内容
  - Kamailio 相关内容
  - SIP 客户端开发

- **✍️ 技术博客**：记录开发过程中的问题与解决方案

- **👤 关于我**：个人简历与联系方式

### 🛠️ 技术栈

- [Docusaurus](https://docusaurus.io/) - 现代化静态网站生成器
- React + TypeScript
- Markdown/MDX - 内容编写
- 支持深色/浅色主题切换

## 🚀 快速开始

### 安装依赖

```bash
yarn
```

或使用 npm：

```bash
npm install
```

### 本地开发

```bash
yarn start
```

此命令会启动本地开发服务器并自动打开浏览器窗口。大多数更改都会实时反映，无需重启服务器。

默认访问地址：`http://localhost:3000`

### 构建生产版本

```bash
yarn build
```

此命令会将静态内容生成到 `build` 目录，可以使用任何静态内容托管服务进行部署。

### 本地预览构建结果

```bash
yarn serve
```

## 📦 部署

### 使用 SSH 部署

```bash
USE_SSH=true yarn deploy
```

### 使用 HTTPS 部署

```bash
GIT_USER=<Your GitHub username> yarn deploy
```

如果使用 GitHub Pages 托管，此命令会自动构建网站并推送到 `gh-pages` 分支。

## 📝 内容管理

### 添加文档

在 `docs/` 目录下创建或编辑 Markdown 文件：

```bash
docs/
├── FreeSWITCH/
├── Kamailio/
├── SipClient/
└── intro.md
```

### 添加博客文章

在 `blog/` 目录下创建新的 Markdown 文件：

```bash
blog/
├── 2025-08-26-welcome/
└── authors.yml
```

### 更新个人信息

编辑 `src/pages/about.md` 文件更新个人简历和联系方式。

## 🎨 自定义

- **配置文件**：`docusaurus.config.ts` - 网站配置、导航栏、页脚等
- **样式文件**：`src/css/custom.css` - 自定义样式
- **静态资源**：`static/` - 图片、图标等静态文件

## 📄 许可证

本项目采用 MIT 许可证。

## 🤝 贡献

欢迎提出问题和建议！

---

Built with ❤️ using [Docusaurus](https://docusaurus.io/)
