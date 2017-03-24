## react-native 的eslint 简单配置
```
{
  "extends": "airbnb",
  "plugins": [
    "react",
    "jsx-a11y",
    "import"
  ],
  "env": {
    "browser": true,
    "node": true,
    "jest": true
  },
  "ecmaFeatures": {
    "forOf": true,
    "jsx": true,
    "es6": true
  },
  "rules": {
    "react/prop-types": 0,
    "no-use-before-define": 0,
    "radix": 0,
    "no-param-reassign": 0,
    "react/jsx-filename-extension": 0,
    "no-mixed-operators": 0,
    "import/prefer-default-export": 0,
    "import/no-extraneous-dependencies": 0,
    "no-plusplus": 0,
    "react/prefer-stateless-function": 0,
    "class-methods-use-this": 0,
    "react/require-default-props": 0
  }
}
```