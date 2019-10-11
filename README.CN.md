# css-styles

我在不同项目中使用的 css 样式集合，包括 react-native，小程序（taro / uni-app）和网页（react / vue）

[English](README.md) | 简体中文

## 起步

这些说明将让你得到能在本地启动、运行的项目副本以进行开发和测试。

### 准备

- 推荐使用 nvm，长期支持版 lts node，长期支持版 npm 和 yarn。
  - 参照以下链接，首先安装 nvm
    - [nvm for Mac/Linux](https://github.com/nvm-sh/nvm)
    - [nvm-windows](https://github.com/coreybutler/nvm-windows)
    - 使用 [Homebrew](https://brew.sh/) 在 Mac 安装 nvm 是**不**推荐的
  - 接着在终端/命令行安装长期支持版 node

    ```sh
    # for now, lts version is 10.16.3
    # last updated：2019.09.17
    nvm install 10.16.3
    ```

  - 全局升级 npm 到长期支持版，安装 yarn

    ```sh
    npm i -g npm@lts
    npm i -g yarn
    ```

  - 如果你是国人，或许你应该设置镜像
- Git 也是需要的
  - [git for Windows/Linux](https://git-scm.com/downloads)
  - 使用 [Homebrew](https://brew.sh/) 在 Mac 安装 git 是推荐的

### 安装

```sh
yarn add @modyqyw/css-styles
# or
npm i @modyqyw/css-styles
```

### 使用

- taro / uni-app

导入`miniprogram/global.scss`作为全局样式。

```js
import '@modyqyw/css-styles/miniprogram/global.scss';
```

导入`miniprogram/vars.scss`来使用预设颜色。

```scss
@import '~@modyqyw/css-styles/miniprogram/vars'
```

- react / vue

导入`web/global.scss`作为全局样式。

```js
import '@modyqyw/css-styles/web/global.scss';
```

Import `web/vars.scss`来使用预设颜色。

```scss
@import '~@modyqyw/css-styles/web/vars'
```

## 测试

目前没有测试。欢迎 PR。

## 特性

- 预设布局
- 预设排版
- 两种风格的预设颜色：Material Design 和 Ant Design

## 贡献

请阅读 [CONTRIBUTING.md](./CONTRIBUTING.md) 了解行为准则以及提交拉取请求的流程的详细信息。

## 版本命名

使用 [SemVer](http://semver.org/) 进行版本控制。有关可用版本，请参阅此仓库的 [releases](https://github.com/ModyQyW/css-styles/releases)。

## 作者

- **Rui Wu** - *最初工作* - [ModyQyW](https://github.com/ModyQyW)

另请参阅参与此项目的 [contributors](https://github.com/ModyQyW/css-styles/contributors) 列表。

## 协议

[MIT](./LICENSE)

Copyright (c) 2019-present ModyQyW

## 致谢

- [Material Design](https://material.io/)
- [Ant Design](https://ant.design/)
- [ElementUI](https://element.eleme.io/)
- [ColorUI](https://www.color-ui.com/)
- [ReactNativeElements](https://react-native-training.github.io/react-native-elements/)
- [NativeBase](https://nativebase.io/)
- [TaroUI](https://taro-ui.aotu.io/#/)
