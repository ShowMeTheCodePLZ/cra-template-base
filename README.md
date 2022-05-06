# cra-template-basis



## React Template⚡️

⚡️A base React starter template with CRA



## Dependencies

- react 18
- typescript
- react-router-dom v6
- axios
- vite
- eslint
- prettier
- commitizen

## Getting Started

```shell
npm install degit -g

# yarn
yarn create react-app my-app --template typescript
cd myapp
npx husky install

# npm
npx create-react-app my-app --template typescript
cd myapp
npx husky install
```



### Prerequisites

- `npm` should be installed.
- `git` should be installed (recommended v2.4.11 or higher)



## File directory

### src:

- api —— 请求接口
- assets/static —— 存放一些静态资源、如 icon、图片
- components —— 存放通用组件
- styles/design —— 存放全局样式
- enums —— 存放全局 ts 字典
- hooks —— 存放封装的自定义 hook
- layouts —— 存放布局方案
- lib/vendor —— 存放第三方库
- pages/views —— 存放项目的页面
- router —— 存放布局方案
- settings —— 存放一些全局的设置
- store —— 存放状态管理相关
- utils —— 存放通用的工具类函数
