# 社区门诊系统

### 介绍 📖

本项目是一款专为社区门诊设计的轻量级管理系统，基于 Vue 3、TypeScript、Pinia、Element Plus 和 ECharts 实现。系统提供了病患信息管理、日程提醒、健康数据可视化等功能，能够满足日常的社区门诊工作需求，并通过简洁的界面和高效的数据管理提升医护人员的工作效率。项目采用本地存储技术，保证数据的持久化与快速响应，适合轻量化的前端应用场景。

### 项目功能 🔨

- 使用 **Vue 3** 和 **TypeScript** 构建现代化前端架构
- 集成 **Pinia** 作为状态管理，确保数据同步与管理
- 使用 **Element Plus** 提供简洁、高效的 UI 组件
- 使用 **ECharts** 实现健康数据的可视化，支持心率、血压、体温等数据的展示
- 支持病患信息的增删改查（CRUD）功能
- 提供日程提醒功能，帮助医生及时跟进病患预约
- 实现了本地存储（localStorage）功能，确保数据持久化管理
- 使用 **Vue Router** 实现动态路由，支持根据病患 ID 生成个性化数据展示页面
- 系统设计轻量、易用，便于后续扩展和功能迭代

### 项目技术栈 📚

- **Vue 3**：前端框架，用于构建用户界面
- **TypeScript**：增强代码的类型安全
- **Pinia**：Vue 3 的状态管理库，用于管理全局数据状态
- **Element Plus**：Vue 3 的 UI 组件库，提供丰富的表单和交互组件
- **ECharts**：用于绘制数据可视化图表，展示健康数据
- **Vue Router**：用于管理前端路由，实现动态路由和页面跳转

### 安装使用步骤 📔

- **Clone：**

```text

# GitHub
git clone https://github.com/HalseySpicy/Geeker-Admin.git
```

- **Install：**

```text
pnpm install
```

- **Run：**

```text
pnpm dev
pnpm serve
```

- **Build：**

```text
# 开发环境
pnpm build:dev

# 测试环境
pnpm build:test

# 生产环境
pnpm build:pro
```

- **Lint：**

```text
# eslint 检测代码
pnpm lint:eslint

# prettier 格式化代码
pnpm lint:prettier

# stylelint 格式化样式
pnpm lint:stylelint
```

- **commit：**

```text
# 提交代码（提交前会自动执行 lint:lint-staged 命令）
pnpm commit
```

### 文件资源目录 📚

```text
Geeker-Admin
├─ .husky                  # husky 配置文件
├─ .vscode                 # VSCode 推荐配置
├─ build                   # Vite 配置项
├─ public                  # 静态资源文件（该文件夹不会被打包）
├─ src
│  ├─ api                  # API 接口管理
│  ├─ assets               # 静态资源文件
│  ├─ components           # 全局组件
│  ├─ config               # 全局配置项
│  ├─ directives           # 全局指令文件
│  ├─ enums                # 项目常用枚举
│  ├─ hooks                # 常用 Hooks 封装
│  ├─ languages            # 语言国际化 i18n
│  ├─ layouts              # 框架布局模块
│  ├─ routers              # 路由管理
│  ├─ stores               # pinia store
│  ├─ styles               # 全局样式文件
│  ├─ typings              # 全局 ts 声明
│  ├─ utils                # 常用工具库
│  ├─ views                # 项目所有页面
│  ├─ App.vue              # 项目主组件
│  ├─ main.ts              # 项目入口文件
│  └─ vite-env.d.ts        # 指定 ts 识别 vue
├─ .editorconfig           # 统一不同编辑器的编码风格
├─ .env                    # vite 常用配置
├─ .env.development        # 开发环境配置
├─ .env.production         # 生产环境配置
├─ .env.test               # 测试环境配置
├─ .eslintignore           # 忽略 Eslint 校验
├─ .eslintrc.cjs           # Eslint 校验配置文件
├─ .gitignore              # 忽略 git 提交
├─ .prettierignore         # 忽略 Prettier 格式化
├─ .prettierrc.cjs         # Prettier 格式化配置
├─ .stylelintignore        # 忽略 stylelint 格式化
├─ .stylelintrc.cjs        # stylelint 样式格式化配置
├─ CHANGELOG.md            # 项目更新日志
├─ commitlint.config.cjs   # git 提交规范配置
├─ index.html              # 入口 html
├─ LICENSE                 # 开源协议文件
├─ lint-staged.config.cjs  # lint-staged 配置文件
├─ package-lock.json       # 依赖包包版本锁
├─ package.json            # 依赖包管理
├─ postcss.config.cjs      # postcss 配置
├─ README.md               # README 介绍
├─ tsconfig.json           # typescript 全局配置
└─ vite.config.ts          # vite 全局配置文件
```

           |                   last 2 versions                   |

### 项目后台接口 🧩

项目后台接口完全采用 Mock 数据，感谢以下 Mock 平台支持：

- FastMock： https://www.fastmock.site
- EasyMock：https://mock.mengxuegu.com
#   c l i n i c  
 