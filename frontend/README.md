# 人力资源调度系统 - 前端

基于 Next.js 14 和 TypeScript 构建的现代化人力资源调度系统前端应用。

## 技术栈

- **框架**: Next.js 14 (App Router)
- **语言**: TypeScript
- **样式**: Tailwind CSS
- **UI组件**: Radix UI + shadcn/ui
- **状态管理**: TanStack Query
- **图标**: Lucide React
- **图表**: Recharts

## 功能模块

- 🏠 **仪表盘**: 数据概览和统计分析
- 👥 **用户管理**: 用户增删改查和权限管理
- 📋 **项目管理**: 项目创建、编辑和任务分配
- 📅 **智能调度**: 自动化排班和冲突解决
- 📊 **数据分析**: 可视化报表和性能指标
- 🔔 **通知系统**: 实时消息推送和提醒

## 开发环境

### 安装依赖

```bash
npm install
```

### 启动开发服务器

```bash
npm run dev
```

### 构建生产版本

```bash
npm run build
npm start
```

## 项目结构

```
frontend/
├── app/                    # Next.js App Router 页面
│   ├── dashboard/         # 仪表盘页面
│   ├── users/            # 用户管理页面
│   ├── projects/         # 项目管理页面
│   ├── scheduling/       # 调度管理页面
│   ├── analytics/        # 数据分析页面
│   └── notifications/    # 通知中心页面
├── components/            # 可复用组件
│   ├── dashboard/        # 仪表盘组件
│   ├── layout/          # 布局组件
│   ├── users/           # 用户管理组件
│   ├── projects/        # 项目管理组件
│   ├── scheduling/      # 调度管理组件
│   └── notifications/   # 通知组件
└── lib/                  # 工具库
    ├── api/             # API 客户端
    └── auth/            # 认证相关
```

## 开发规范

- 使用 TypeScript 进行类型安全开发
- 遵循 ESLint 代码规范
- 组件采用函数式组件 + Hooks
- 使用 Tailwind CSS 进行样式开发
- API 调用统一使用 TanStack Query