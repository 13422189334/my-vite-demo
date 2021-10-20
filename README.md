\*\*\* 技术选型

- 编程语言：TypeScript 4.x + JavaScript
- 构建工具：Vite 2.x
- 前端框架：Vue 3.x
- 路由工具：Vue Router 4.x
- 状态管理：Vuex 4.x
- UI 框架：Element Plus
- CSS 预编译：Stylus / Sass / Less
- HTTP 工具：Axios
- Git Hook 工具：husky + lint-staged
- 代码规范：EditorConfig + Prettier + ESLint + Airbnb JavaScript Style Guide
- 提交规范：Commitizen + Commitlint
- 单元测试：vue-test-utils + jest + vue-jest + ts-jest
- 自动部署：Gitee Actions

\*\*\* 目录结构

├── publish/
└── src/
├── assets/ // 静态资源目录
├── common/ // 通用类库目录
├── components/ // 公共组件目录
├── router/ // 路由配置目录
├── store/ // 状态管理目录
├── style/ // 通用 CSS 目录
├── utils/ // 工具函数目录
├── views/ // 页面组件目录
├── App.vue
├── main.ts
├── shims-vue.d.ts
├── tests/ // 单元测试目录
├── index.html
├── tsconfig.json // TypeScript 配置文件
├── vite.config.ts // Vite 配置文件
└── package.json

\*\*\* 部分命令

- 格式化所有文件（. 表示所有文件）

```shell script
npx prettier --write .
```

- 代码提交

```shell script
git cz
```
