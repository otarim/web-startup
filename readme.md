## web-startup

自用的web应用脚手架，只是想解决模块化开发的问题，基于 `systemjs` 加载器，样式预处理器选择 `less`, 因为 `sass` 开发体验很糟糕（基于 `webworker`，加载一大堆依赖，而且我也用不到很多 `sass` 的特性）

### 使用

**初始化**

依赖 `yarn`, 不想装的把 `npm script` 里面的 `yarn` 改成 `npm` 就行了

    npm run init

**开发**

依赖 `live-server` 实现本地开发服务器功能，也可以用 `http-server` 之类的替换

    npm run dev

**发布**

    npm run build

然后把html的 `dev` 注释注释掉，取消 `build` 的注释即可，打包目录是 `./dist`
