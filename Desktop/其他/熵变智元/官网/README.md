# YouMind 官网

YouMind 是一个现代化的官网项目，使用 React + Vite + Tailwind CSS 构建。

## 项目特性

- 🚀 基于 Vite 的快速开发体验
- ⚛️ React 18 最新特性
- 🎨 Tailwind CSS 现代化样式
- 📱 响应式设计
- 🔧 完整的开发工具链

## 技术栈

- **前端框架**: React 18
- **构建工具**: Vite
- **样式框架**: Tailwind CSS
- **图标库**: Lucide React
- **部署平台**: Vercel

## 项目结构

```
官网/
├── src/
│   ├── components/          # React 组件
│   │   ├── Features/       # 功能特性组件
│   │   ├── Footer/         # 页脚组件
│   │   ├── Header/         # 头部组件
│   │   ├── Hero/           # 主视觉组件
│   │   ├── ProductShowcase/# 产品展示组件
│   │   ├── Resources/      # 资源组件
│   │   └── Testimonials/   # 用户评价组件
│   ├── App.jsx            # 主应用组件
│   ├── main.jsx           # 应用入口
│   └── index.css          # 全局样式
├── index.html             # HTML 模板
├── package.json           # 项目配置
├── tailwind.config.js     # Tailwind 配置
├── vite.config.js         # Vite 配置
└── vercel.json           # Vercel 部署配置
```

## 快速开始

### 安装依赖

```bash
npm install
```

### 开发模式

```bash
npm run dev
```

### 构建生产版本

```bash
npm run build
```

### 预览生产版本

```bash
npm run preview
```

## 部署

本项目已配置 Vercel 部署，推送到 main 分支后会自动部署。

## 许可证

MIT License 