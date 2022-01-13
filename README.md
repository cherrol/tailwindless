# Tailwindcss Less Version

- 基于 [Tailwindcss@1.9.0](https://v1.tailwindcss.com/) 构建

- 因为项目需要兼容到 `less@2.5.3`，所以很多方法（`each`，`range` 等）暂时不使用。

## Install
- npm install
```bash
pnpm i @cherrol/tailwindless
# npm i @cherrol/tailwindless
# yarn add @cherrol/tailwindless
```
```js
// in js
import "@cherrol/tailwindless/dist/index.css";
```
```css
// in css
@import "@cherrol/tailwindless/dist/index.css";
```


- Custom import in less
```less
// variables
@import "~node_modules/@cherrol/tailwindless/src/variables/_export.less";
// mixins
@import "~node_modules/@cherrol/tailwindless/src/mixins/_export.less";
// classes
@import "~node_modules/@cherrol/tailwindless/src/classes/_export.less";
```
