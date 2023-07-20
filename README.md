# RAC ESLint config

## Setup

1. Install the dependencies
```
npm i -D eslint @racsys/eslint-config
```

2. Create a `.eslintrc.json` file extending the config:
```
{
  "extends": "@racsys/eslint-config/react"
  // "extends": "@racsys/eslint-config/node"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.