# react-todolist


## Summary
return [Summary](#summary)

<!-- TOC -->

- [react-todolist](#react-todolist)
  - [Summary](#summary)
- [Getting Started with Create React App](#getting-started-with-create-react-app)
  - [Available Scripts](#available-scripts)
    - [`npm start`](#npm-start)
    - [`npm test`](#npm-test)
    - [`npm run build`](#npm-run-build)
    - [`npm run eject`](#npm-run-eject)
  - [Learn More](#learn-more)
    - [Code Splitting](#code-splitting)
    - [Analyzing the Bundle Size](#analyzing-the-bundle-size)
    - [Making a Progressive Web App](#making-a-progressive-web-app)
    - [Advanced Configuration](#advanced-configuration)
    - [Deployment](#deployment)
    - [`npm run build` fails to minify](#npm-run-build-fails-to-minify)
  - [Setup](#setup)
    - [install nodejs](#install-nodejs)
    - [version verification](#version-verification)
    - [install json-server](#install-json-server)
  - [Reference](#reference)

<!-- /TOC -->

-----


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)


-----





## Setup
return [Summary](#summary)

### install nodejs

```shell
nvm install 16.15.0
nvm use 16.15.0
```

> nvm use 版本報錯，出現exit status 1後面跟一堆亂碼<br>
> 此時是因為無權限，以管理員身份打開，再次使用nvm use，問題解決



### version verification

```shell
# nvm version
1.1.8

# node -v
v16.15.0


```



### install json-server
```
# 首先全域安裝 json-server
npm install -g json-server

# 開啟 json server，並且指定使用哪個檔案
json-server db.json
```



使用 React 建立一個全新的 single-page 應用程式
Node >= 14.0.0 and npm >= 5.6

```
npx create-react-app react-todolist
cd react-todolist
npm start
```




出現 `'React' must be in scope when using JSX  react/react-in-jsx-scope` 錯誤
最上面加入下面這行就解決了
```
import React from 'react';
```






## Reference

React 官網
<https://zh-hant.reactjs.org/>


【前端速成】React 快速入門｜Tiktok工程師帶你入門前端｜布魯斯前端
<https://github.com/scps960740/React-crash-course-2021-bruceFE>


用 JSON Server 模擬 RESTful API
<https://medium.com/@debbyji/%E7%94%A8-json-server-%E6%A8%A1%E6%93%AC-restful-api-f07abda3927c>
