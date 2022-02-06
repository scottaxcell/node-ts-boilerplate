# Node.js TypeScript Application Boilerplate

Bare bones Node.js application template with Docker, TypeScript, Eslint, and Prettier configurations.

## Usage

Initialize your GitHub repository with the same directory structure and files using the ```Use this template``` feature.

## How this template was created

```
yarn init

# https://www.typescriptlang.org/download
yarn add --dev typescript
npx tsc --init

# https://typescript-eslint.io/docs/linting/
yarn add --dev eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin

# https://prettier.io/docs/en/install.html
yarn add --dev --exact prettier

# https://github.com/prettier/eslint-config-prettier
yarn add --dev eslint-config-prettier

yarn add --dev rimraf
```

## License

[MIT License](https://github.com/scottaxcell/winddcutil/blob/main/LICENSE)

## Issues

If you find a bug or have a feature request, please file an issue using [the issue tracker on GitHub](https://github.com/scottaxcell/node-ts-boilerplate/issues).
