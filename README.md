# vue-ts-boilerplate

A preconfigured Vue boilerplate ✌️

Features:
- TypeScript
- Vue Router
- Sass
- Jest (Unit Testing)
- ESLint + Airbnb Config
- Prettier

## IDE Settings

Install following extensions in VS Code:
- Vetur
- Prettier
- ESLint

Settings:

```
  "vetur.validation.template": false,
  "vetur.format.enable": false,
  "vetur.format.defaultFormatter.css": "none",
  "vetur.format.defaultFormatter.html": "none",
  "vetur.format.defaultFormatter.js": "none",
  "vetur.format.defaultFormatter.postcss": "none",
  "vetur.format.defaultFormatter.scss": "none",
  "vetur.format.defaultFormatter.ts": "none",
  "javascript.format.enable": false,
  "eslint.validate": ["javascript", "vue", "html"],
  "eslint.run": "onType",
  "eslint.enable": true,
  "eslint.format.enable": false,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
  },  
```

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your unit tests
```
npm run test:unit
```

### Lints and fixes files
```
npm run lint
```
