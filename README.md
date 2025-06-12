# For Learning Codex

This repository contains a minimal TypeScript setup. It includes Jest for tests, ESLint for linting, and Prettier for code formatting.

## Installation

Make sure you have Node.js installed. Then install project dependencies:

```bash
npm install
```

## Scripts

- **Build**: compile the TypeScript source

  ```bash
  npm run build
  ```

- **Start**: run the compiled application

  ```bash
  npm start
  ```

- **Development**: run directly from TypeScript

  ```bash
  npm run dev
  ```

- **Watch Build**: continuously compile on changes

  ```bash
  npm run watch
  ```

- **Test**: execute the test suite

  ```bash
  npm test
  ```

  Additional options:
  - `npm run test:watch` – run tests in watch mode.
  - `npm run test:coverage` – generate a coverage report.

- **Lint**: check code style using ESLint

  ```bash
  npm run lint
  ```
  - `npm run lint:fix` – automatically fix lint errors.

- **Format**: format files with Prettier

  ```bash
  npm run format
  ```
  - `npm run format:check` – verify formatting without writing changes.

## Testing and Formatting

Run the tests with `npm test` or the other test commands listed above. Formatting is handled by Prettier; run `npm run format` before committing changes to keep the codebase consistent.
