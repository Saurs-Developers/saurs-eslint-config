# Saurs ESLint config

- Standard config;
- React config;
- Angular config (W.I.P);

##How to install

1. Install the dependencies
```
  npm i -D eslint @saurs/eslint-config
  //pnpm add -D @saurs/eslint-config
  //yarn add -D @saurs/eslint-config
  //bun add @saurs/eslint-config -d
```

2. Create a `eslintrc.json` or `eslintrc.js` file that extends the config:

```
{
  "extends": "@saurs/eslint-config/react
  //"extends": "@saurs/eslint-config/angular"
}
```
