# React TS 问卷系统

基于 React + TypeScript 的问卷调查系统，支持问卷的创建、编辑、管理和数据统计。

## 技术栈

- React 18 + TypeScript
- React Router v6（路由管理）
- Redux Toolkit（状态管理）
- Ant Design 5（UI 组件库）
- ahooks（React Hooks 工具库）
- CRACO（CRA 配置覆盖）
- Sass / CSS Modules（样式方案）
- Axios（HTTP 请求）
- Mock.js（数据模拟）

## 功能模块

- 首页展示
- 用户登录 / 注册
- 问卷管理（列表、收藏、回收站）
- 问卷编辑器（画布拖拽、组件库、属性面板、图层管理）
- 问卷统计
- 404 页面

## 问卷组件

| 分组     | 组件         |
| -------- | ------------ |
| 文本显示 | 问卷信息、标题、段落 |
| 用户输入 | 单行输入、多行输入   |
| 用户选择 | 单选、多选           |

## 项目结构

```
src/
├── components/        # 公共组件（Logo、Card、问卷组件等）
├── hooks/             # 自定义 Hooks
├── layouts/           # 页面布局
├── pages/             # 页面
│   ├── Home/          # 首页
│   ├── Login/         # 登录
│   ├── Register/      # 注册
│   ├── manage/        # 问卷管理（列表/收藏/回收站）
│   └── question/      # 问卷编辑 & 统计
├── router/            # 路由配置
├── store/             # Redux Store
│   └── modules/       # 组件、页面信息、用户 Reducer
├── _mock/             # Mock 数据
└── assets/            # 静态资源
```

## 快速开始

```bash
# 安装依赖
npm install

# 启动开发服务器
npm start

# 构建生产版本
npm run build

# 运行测试
npm test
```

开发服务器默认运行在 [http://localhost:3000](http://localhost:3000)。
