# nest-starter

🚀 NestJS 模板

| 分类 | 技术栈               |
| ---- | -------------------- |
| 框架 | NestJS 12（Express） |
| 语言 | TypeScript（ESM）    |
| 检查 | oxlint               |
| 测试 | Vitest + Supertest   |

## 安装

```bash
npx degit tlyboy/nest-starter my-project
cd my-project
pnpm install
```

## 使用说明

### 开发

```bash
pnpm start:dev
```

服务监听 `http://localhost:3000`，设置 `PORT` 环境变量可以换端口。

### 构建

```bash
pnpm build
pnpm start:prod
```

### 生成资源

```bash
pnpm nest g resource users
pnpm format
```

生成器不会读取 Prettier 配置，生成后需要运行一次 `pnpm format`。

### 测试

```bash
pnpm test
pnpm test:e2e
pnpm test:cov
```

### 检查

```bash
pnpm lint
pnpm format
```

## 使用许可

[MIT](https://opensource.org/licenses/MIT) © tlyboy
