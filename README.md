### 简介

[Vue Naive Admin],一个基于 Vue3.0、Vite、Naive UI 的后台管理模板，此项目简洁、轻量，学习成本非常低，对新手极其友好。权限、Mock、菜单、axios 封装、pinia、项目配置、样式配置、环境配置，以及一些经常用的基础组件封装等等,非常适用于中小型项目或者个人项目

### 为什么要开发这个模板

- Vue3 和 Vite 已经趋于成熟，学习 vite 和 vue3 非常有必要，通过开发模板进行学习是一个很好的方式，事实也证明我确实从中获益良多

### 功能

- 🍒 集成 Naive UI，尤大推荐的 UI 组件库，[https://www.naiveui.com](https://www.naiveui.com)
- 🍑 集成登陆、注销及权限验证
- 🍐 集成多环境配置，dev、测试、生产和github pages环境
- 🍎 集成 Eslint + Prettier，代码约束和格式化统一
- 🍉 集成 Mock 接口服务，dev 环境和发布环境都支持，可动态配置是否启用 mock 服务，不启用时不会加载 mock 包，减少打包体积
- 🍇 集成 unocss，antfu 大神开源的原子化 css 解决方案，非常轻量，目前我是自己写 scss 样式搭配着 unocss 使用的
- 🍍 集成 Pinia，Vuex 的替代方案，轻量、简单、易用（尤大已表示不会有Vuex5，或者说pinia就是Vuex5）
- 📦 集成 Vite 自动导入插件unplugin-vue-components，解放双手，开发效率直接起飞
- 🤹 集成 unplugin-icons插件，优雅使用iconify图标
- 🍏 二次封装 Axios，支持多 axios 实例
- 🍌 二次封装全局 Dialog、Message、LoadingBar 组件
- 🍋 二次封装 localStorage 和 sessionStorage，支持设置过期时间


### 构建

# 安装依赖(建议使用pnpm: https://pnpm.io/zh/installation)
pnpm i 

# 启动
pnpm run dev
```

### 发布

```shell
# 构建测试环境
npm run build:test

# 构建生产环境
npm run build
```

### 其他指令

```shell
# eslint代码格式检查
npm run lint

# 代码检查并修复
npm run lint:fix

# 预览发布包效果（需先执行构建指令）
npm run preview
```

### 规范

#### git commit 规范

- `feat` 增加新功能
- `fix` 修复问题/BUG
- `style` 代码风格相关无影响运行结果的
- `perf` 优化/性能提升
- `refactor` 重构
- `revert` 撤销修改
- `test` 测试相关
- `docs` 文档/注释
- `chore` 依赖更新/脚手架配置修改等
- `workflow` 工作流改进
- `ci` 持续集成
- `types` 类型定义文件更改
- `wip` 开发中
- `mod` 不确定分类的修改
- `release` 发布


