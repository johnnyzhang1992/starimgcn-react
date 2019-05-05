# starImgCn-React

## 项目介绍

此项目是 [starimg.cn](https://starimg.cm)网站的 react 版本。采用前后端分离的模式。当前项目正在开发阶段，会一直更新。。。

线上 demo 站点： [test.starimg.cn](http://test.starimg.cn)

## Dependencies

主要依赖：

- `react`
- `redux`
- `react-router`
- `react-redux`
- `redux-thunk`
- `gestalt` [Gestalt](https://github.com/pinterest/gestalt)
- `axios`
- ...

## `config` file

webpack 的 config 文件，在 `config` 目录下。

## Available Scripts

在项目根目录下，你可以运行一下命令:

### `npm start`

开发模式。在浏览器中打开 [http://localhost:3000](http://localhost:3000) 查看页面.

### `npm test`

测试模式。jest + emzyme + react-test-renderer

### `npm run build`

生产模式。生成的文件在 `bulid` 文件件下。

### `serve -s build`

在浏览器中打开 [http://localhost:5000/](http://localhost:5000/) 查看 `prod` 模式下的页面.

## 代理

package.json中配置如下代码

```js
 "proxy": "https://api.starimg.cn"
```