# For Learning Codex

此代码仓库包含一个精简的 TypeScript 项目设置。它包括用于测试的 Jest、用于代码检查的 ESLint 以及用于代码格式化的 Prettier。

## 安装

请确保你已安装 Node.js。然后安装项目依赖：

```bash
npm install
```

## 脚本命令

- **构建**：编译 TypeScript 源代码

  ```bash
  npm run build
  ```

- **启动**：运行已编译的应用程序

  ```bash
  npm start
  ```

- **开发模式**：直接运行 TypeScript 源文件

  ```bash
  npm run dev
  ```

- **监听构建**：文件变动时自动编译

  ```bash
  npm run watch
  ```

- **测试**：执行测试套件

  ```bash
  npm test
  ```

  其他可选命令：
  - `npm run test:watch` – 在监听模式下运行测试。
  - `npm run test:coverage` – 生成测试覆盖率报告。

- **代码检查**：使用 ESLint 检查代码风格

  ```bash
  npm run lint
  ```
  - `npm run lint:fix` – 自动修复代码风格错误。

- **代码格式化**：使用 Prettier 格式化文件

  ```bash
  npm run format
  ```
  - `npm run format:check` – 检查格式是否符合规范但不修改文件。

## 测试与格式化

可使用 `npm test` 或上方列出的其他测试命令运行测试。格式化由 Prettier 工具完成；在提交更改前请运行 `npm run format`，以保持代码库风格一致。
