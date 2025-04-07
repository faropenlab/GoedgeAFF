# GoedgeAFF

这是一个前端基于 Next.js 14 构建的现代化 Web 应用程序,后端使用Nodejs开发的，可用于CDN系统GOEDGE的邀请系统。

## 前端技术栈

- **前端框架**：Next.js 14
- **UI 组件库**：Headless UI (@headlessui/react)
- **图标库**：Heroicons (@heroicons/react)
- **样式解决方案**：Tailwind CSS
- **动画效果**：Framer Motion
- **开发语言**：TypeScript
- **代码规范**：ESLint + Prettier

## 主要功能

1. **用户认证系统**
   - 登录功能
   - 注册功能
   - 服务条款页面

2. **应用功能**
   - 客户端邀请信息管理
   - 余额添加功能
   - 统计信息展示

## 开始使用

### 安装依赖

```bash
npm install
```

### 启动开发服务器

```bash
npm run dev
```

### 访问应用

打开浏览器访问 [http://localhost:3000](http://localhost:3000)

## 项目结构

```
src/
├── app/                # Next.js 应用路由
│   ├── api/           # API 路由
│   ├── login/         # 登录页面
│   ├── register/      # 注册页面
│   └── tos/           # 服务条款页面
├── components/         # 可复用组件
├── config/            # 配置文件
├── services/          # 服务层
└── styles/            # 全局样式
```

## 开发命令

- `npm run dev` - 启动开发服务器
- `npm run build` - 构建生产版本
- `npm run start` - 启动生产服务器
- `npm run lint` - 运行代码检查

## 项目特点

1. **类型安全**：使用 TypeScript 确保代码质量和可维护性
2. **现代化架构**：采用 Next.js 14 的 App Router 架构
3. **组件化开发**：使用 Headless UI 实现高度可定制的组件
4. **性能优化**：内置 Next.js 的性能优化特性
5. **代码质量**：集成 ESLint 和 Prettier 确保代码质量
