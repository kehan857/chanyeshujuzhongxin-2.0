# 产业数据中心原型

基于Vue3 + Ant Design + TypeScript + Vite的现代化产业数据中心系统。

## ✨ 系统特色

### 🧠 智能产业大脑
- **多维度数据分析**: 企业画像、产业分析、供需匹配
- **实时数据看板**: 交互式图表展示产业发展趋势
- **智能决策支持**: 基于大数据的产业发展建议

### 🎨 现代化设计
- **双主题切换**: 明暗主题无缝切换，护眼体验
- **响应式布局**: 支持PC、平板、手机多端适配
- **毛玻璃效果**: 现代化视觉设计，提升用户体验
- **流畅动画**: CSS3动画效果，交互体验流畅

## 🚀 在线预览

- **GitHub Pages**: [https://kehan857.github.io/Industrial-Data-Center110/](https://kehan857.github.io/Industrial-Data-Center110/)
- **本地开发**: [http://localhost:3000/](http://localhost:3000/)

## 📋 核心功能

### 📊 数据看板 (Dashboard)
- 实时数据统计与可视化
- 多维度指标展示
- 趋势分析图表
- 关键指标监控

### 🔗 产业链图谱 (Industry Chain)
- 交互式产业链关系展示
- 上中下游企业分布
- 产业链强度分析
- 节点详情查看

### 🗺️ 产业地图 (Industry Map)
- 中国地图热力图展示
- 各省份产业分布
- 地理位置标记
- 区域发展对比

### 🏢 企业资源库
- **企业列表**: 详细企业信息展示
- **专家库**: 行业专家资源管理
- **产品库**: 产品信息与展示
- **需求库**: 技术需求发布与匹配
- **解决方案**: 成熟方案展示

### 🎯 商机洞察
- **供需地图**: 供需关系可视化
- **市场分析**: 市场机会识别
- **商机推荐**: 智能商机匹配

### 👥 系统管理
- **用户管理**: 用户权限控制
- **角色管理**: 角色权限配置
- **登录认证**: 安全登录体系

## 🛠️ 技术栈

### 前端框架
- **Vue 3.4+** - 渐进式JavaScript框架
- **TypeScript 5.0+** - 静态类型检查
- **Vite 5.0+** - 极速前端构建工具

### UI框架
- **Ant Design Vue 4.0+** - 企业级UI设计语言
- **Less** - CSS预处理器
- **Vue Router 4** - 官方路由管理器

### 构建部署
- **GitHub Actions** - 自动化CI/CD
- **GitHub Pages** - 静态网站托管
- **ESLint + Prettier** - 代码规范

## 🚀 快速开始

### 环境要求
- Node.js 18+
- npm 9+

### 安装依赖
```bash
npm install
```

### 本地开发
```bash
npm run dev
```

### 构建项目
```bash
npm run build
```

### 预览构建结果
```bash
npm run preview
```

## 📂 项目结构

```
产业数据中心原型/
├── public/                 # 静态资源
│   └── 404.html           # GitHub Pages 404页面
├── src/
│   ├── views/             # 页面组件
│   │   ├── Dashboard.vue        # 数据看板
│   │   ├── insights/            # 洞察分析
│   │   │   ├── IndustryChain.vue    # 产业链图谱
│   │   │   ├── IndustryMap.vue      # 产业地图
│   │   │   ├── IndustryOverview.vue # 产业概览
│   │   │   └── EnterpriseMap.vue    # 企业地图
│   │   ├── resources/           # 资源管理
│   │   │   ├── EnterpriseList.vue   # 企业列表
│   │   │   ├── ExpertList.vue       # 专家库
│   │   │   ├── ProductList.vue      # 产品库
│   │   │   ├── DemandList.vue       # 需求库
│   │   │   └── SolutionList.vue     # 解决方案
│   │   ├── opportunities/       # 商机洞察
│   │   │   └── SupplyDemandMap.vue  # 供需地图
│   │   ├── admin/              # 系统管理
│   │   │   ├── UserManagement.vue   # 用户管理
│   │   │   └── RoleManagement.vue   # 角色管理
│   │   └── auth/               # 认证相关
│   │       └── Login.vue            # 登录页面
│   ├── layouts/           # 布局组件
│   │   └── MainLayout.vue      # 主布局
│   ├── router/            # 路由配置
│   │   └── index.ts
│   ├── styles/            # 样式文件
│   │   ├── global.less         # 全局样式
│   │   └── themes/             # 主题样式
│   │       ├── light.less      # 明亮主题
│   │       └── dark.less       # 深色主题
│   ├── App.vue            # 根组件
│   └── main.ts            # 入口文件
├── .github/workflows/     # GitHub Actions
│   └── deploy.yml         # 自动部署配置
├── .gitignore            # Git忽略配置
├── .nojekyll             # 禁用Jekyll
├── vite.config.ts        # Vite配置
├── tsconfig.json         # TypeScript配置
└── package.json          # 项目配置
```

## 🎯 核心特性

### 🎨 主题系统
- **双主题支持**: 明亮/深色主题无缝切换
- **CSS变量**: 动态主题色彩系统
- **本地存储**: 主题偏好自动保存

### 📱 响应式设计
- **Flexbox布局**: 现代CSS布局方案
- **媒体查询**: 多设备适配
- **组件级响应**: 细粒度响应式控制

### 🔍 交互体验
- **动态路由**: 基于权限的路由控制
- **状态管理**: Vue3组合式API状态管理
- **加载状态**: 优雅的加载提示
- **错误处理**: 完善的错误边界

## 🚀 部署说明

### GitHub Pages自动部署
项目已配置GitHub Actions自动部署，推送到main分支即可自动构建并部署到GitHub Pages。

### 部署步骤
1. Fork或克隆仓库
2. 在GitHub仓库设置中启用Pages
3. 选择GitHub Actions作为部署源
4. 推送代码到main分支
5. 等待Actions完成部署

### 自定义域名
如需使用自定义域名，请在`public/`目录下添加`CNAME`文件。

## 🤝 贡献指南

1. Fork 项目
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开 Pull Request

## 📄 许可证

本项目采用 MIT 许可证。详情请见 [LICENSE](LICENSE) 文件。

## 📧 联系方式

如有问题或建议，请通过以下方式联系：

- GitHub Issues: [https://github.com/kehan857/Industrial-Data-Center110/issues](https://github.com/kehan857/Industrial-Data-Center110/issues)
- Email: kehan857@example.com

---

⭐ 如果这个项目对你有帮助，请给它一个星标！ 