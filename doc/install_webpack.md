/*
 * @Author: 大明冯 
 * @Date: 2019-07-05 15:47:27 
 * @Last Modified by: 大明冯
 * @Last Modified time: 2019-07-05 16:27:22
 */

两个选项

1、全局安装
```javascript
npm install webpack -g
```

全局安装webpack，就可以在 Command prompt/Terminal window 用 webpack 命令运行webpack.


2、在本地项目里安装
```javascript
npm install webpack -D
```

本地安装之后，就可以运行 webpack 或者 npm start


###运行 webpack

####1，用 webpack 命令
如果全局安装了webpack,就可以用webpack命令打包你的项目。

```javascript
webpack ./src/scripts/app.js ./dist/app.js
```