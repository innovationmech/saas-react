# SaaS 平台登录系统

这是一个基于 React 和 TypeScript 构建的现代化 SaaS 平台登录系统。项目提供了美观的登录和注册界面，可作为 SaaS 应用的用户认证入口。

## 功能特点

- **登录页面**：包含邮箱、密码输入框以及"记住我"功能
- **注册页面**：包含姓名、邮箱、密码和确认密码字段，以及服务条款同意选项
- **表单验证**：支持基本的表单验证，如密码匹配检查
- **页面导航**：在登录和注册页面之间无缝切换
- **响应式设计**：适配各种屏幕尺寸的设备
- **现代化 UI**：使用 Tailwind CSS 实现的现代化界面设计

## 技术栈

- React 19
- TypeScript
- React Router v6
- Tailwind CSS
- Heroicons

## 开始使用

### 安装依赖

```bash
npm install
```

### 启动开发服务器

```bash
npm start
```

应用将在 [http://localhost:3000](http://localhost:3000) 运行。

### 构建生产版本

```bash
npm run build
```

## 项目结构

```
src/
  ├── components/        # 可复用组件
  │   ├── LoginForm.tsx  # 登录表单组件
  │   └── RegisterForm.tsx  # 注册表单组件
  ├── pages/            # 页面组件
  │   ├── LoginPage.tsx  # 登录页面
  │   └── RegisterPage.tsx  # 注册页面
  ├── App.tsx           # 应用主组件，包含路由配置
  └── index.tsx         # 应用入口点
```

## 自定义与扩展

### 添加实际的认证逻辑

登录和注册功能当前仅打印输入信息到控制台。要实现实际的认证，请修改：

- `LoginPage.tsx` 中的 `handleLogin` 函数
- `RegisterPage.tsx` 中的 `handleRegister` 函数

### 添加更多页面

要添加新页面，请在 `src/pages/` 创建页面组件，然后在 `App.tsx` 中添加新的路由。

## 许可

[MIT](LICENSE)
