## TypeScript 14
## Chapter 14: Learn useReducer with TypeScript and React Hooks
It is my coding practice with the TUTORIAL of Dave Gray. 

## Source
### Dave Gray 的 TypeScript 資源
https://github.com/gitdagray/typescript-course

### Dave Gray 的 TypeScript 課程
https://youtube.com/playlist?list=PL0Zuz27SZ-6NS8GXt5nPrcYpust89zq_b&si=8IJALfXOcur2OO_K

### Dave Gray 的 YouTube 頻道
https://www.youtube.com/@DaveGrayTeachesCode

## Quick Concept offline
###  1. Intro
        教學影片開頭和介紹

###  2. Welcome

###  3. Starter Code Review
        (1)在 terminal 輸入 npm create vite@latest
        (2)設定專案名稱
        (3)選取框架 React，變體選擇 TypeScript
        (4)開啟專案資料夾
        (5)在 terminal 輸入 npm i，安裝
        (6)在 terminal 輸入 npm run dev，執行
        (7)刪除 App.css
        (8)新增 counter.tsx
        (9)修改 App.tsx

###  4. What is useReducer?
        匯入 useReducer

###  5. Define initial state
        宣告 initState

###  6. Reducer Action Type: enum or object?
        宣告 enum

###  7. type ReducerAction
        設定 ReducerAction 類別

###  8. reducer function
        宣告 reducer，設定類型和 switch 描述式

###  9. Refactoring from useState to useReducer
        (1)使用 useReducer 宣告
        (2)使用 dispatch 宣告 increment 和 decrement 的類型
        (3)移除 useState 的匯入

### 10. Adding a Payload
        (1)在 initState 新增 text
        (2)在 enum 新增 text 的類型
        (3)在 ReducerAction 新增 payload 的類型
        (4)在 reducer 新增類型的條件
        (5)在 Counter，宣告 handelTextInput
        (6)加入 event 類型，並匯入類型
        (7)加入 input 元素
        (8)修改 REDUCER_ACTION_TYPE.NEW_INPUT，解決 text 可能為 undefined 的問題
        (9)加入 h2 元素

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list


# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
