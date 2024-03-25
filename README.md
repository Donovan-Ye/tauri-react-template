# Tauri React Template

This is an opinionated template for building Tauri apps using React, Typescript, React-router, tailwindcss, i18n, ant-design-v5 and vite. It also includes a custom eslint-only configuration provided by [@antfu/eslint-config](https://github.com/antfu/eslint-config). Additionally, it utilizes Simple-git-hooks and lint-staged to lint and format code before committing.

## Features

- [React](https://reactjs.org/)
- [Typescript](https://www.typescriptlang.org/)
- [React-router](https://reactrouter.com/)
- [tailwindcss](https://tailwindcss.com/)
- [i18n](https://www.i18next.com/)
- [ant-design-v5](https://ant.design/)
- [vite](https://vitejs.dev/)
- [@antfu/eslint-config](https://github.com/antfu/eslint-config)
- [Simple-git-hooks](https://github.com/toplenboren/simple-git-hooks#readme)
- [lint-staged](https://github.com/okonet/lint-staged#readme)

## Usage

This project uses pnpm as the package manager. Begin by using the following command:

```bash
pnpm install
```

### Development

```bash
pnpm tauri dev
```

### Build

```bash
pnpm tauri build
```

### Lint

```bash
pnpm lint
pnpm lint:fix
```

## git-hooks and lint-staged

Please activate the git-hooks by running this command:

```bash
npx simple-git-hooks
```

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
