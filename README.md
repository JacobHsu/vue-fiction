# vue-fiction

vue create projectName

? Use class-style component syntax? `Yes`
? Use Babel alongside TypeScript for auto-detected polyfills? `Yes`

## package.json

```js
  "eslintConfig": {
    "root": true,
    "env": {
      "node": true
    },
    "extends": [
      "plugin:vue/essential",
      "eslint:recommended",
      "@vue/typescript"
    ],
    "parserOptions": {
      "parser": "@typescript-eslint/parser"
    },
    "rules": {
      "generator-star-spacing": "off",
      "no-tabs": "off",
      "no-unused-vars": "off",
      "no-console": "off",
      "no-irregular-whitespace": "off",
      "no-debugger": "off"
    }
  },
```

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
