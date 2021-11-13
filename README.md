# Typescript Starter Default

Fully Configured environment for Typescript projects, still not opinionated.

Best choice for building libraries or small components not related to specific frameworks.

## 💎 Batteries included:

- Typescript
- Eslint with airbnb guidelines
- Prettier
- VScode configured for extensions ( *do yourself a favour* : get them) :
  - prettier : esbenp.prettier-vscode
  - eslint : dbaeumer.vscode-eslint
- Husky : blocks committing code with lint errors
- Go Fast with ts-node-dev

## Installation

```sh
npm i
```

It will install the packages and setup husky.
You're ready to go!

## Scripts

**Linting**

```sh
npm run lint
```

**Run ts code directly**

Does not need to build, for faster development

```sh
npm run dev
```

**Build your code**

```sh
npm run build
```

**Run your buildcode**

```sh
npm run js
```


Made with ❤ by Tancrède Simonin
