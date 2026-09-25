# nest-starter

🚀 NestJS starter

| Category  | Stack               |
| --------- | ------------------- |
| Framework | NestJS 12 (Express) |
| Language  | TypeScript (ESM)    |
| Lint      | oxlint              |
| Test      | Vitest + Supertest  |

## Install

```bash
npx degit tlyboy/nest-starter my-project
cd my-project
pnpm install
```

## Usage

### Development

```bash
pnpm start:dev
```

The server listens on `http://localhost:3000`. Set `PORT` to use another port.

### Build

```bash
pnpm build
pnpm start:prod
```

### Generate resources

```bash
pnpm nest g resource users
pnpm format
```

The generator does not read the Prettier config, so run `pnpm format` after generating.

### Test

```bash
pnpm test
pnpm test:e2e
pnpm test:cov
```

### Check

```bash
pnpm typecheck
pnpm lint
pnpm check
```

## License

[MIT](https://opensource.org/licenses/MIT) © tlyboy
