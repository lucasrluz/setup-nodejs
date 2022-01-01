# Setup Node.js
> Setup Node.js projects

Create project:

```
npm init -y
```
Copy [package.json](https://github.com/lucasrluz/setup-nodejs/blob/main/package.json) to the root directory of your project

TypeScript:

```
npm i -D typescript ts-node-dev
```

```
npm x -- tsc --init
```
Copy [tsconfig.json](https://github.com/lucasrluz/setup-nodejs/blob/main/tsconfig.json) to the root directory of your project

ESLint and Prettier:

```
npm i -D eslint prettier @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint-config-prettier eslint-plugin-prettier
```

Copy [.eslintrc.json](https://github.com/lucasrluz/setup-nodejs/blob/main/.eslintrc.json) and [.prettierrc.json](https://github.com/lucasrluz/setup-nodejs/blob/main/.prettierrc.json) to the root directory of your project

Jest:
```
npm i -D jest ts-jest @types/jest
```

Copy [jest.config.json](https://github.com/lucasrluz/setup-nodejs/blob/main/jest.config.json) to the root directory of your project
