# css-styles

A set of my css styles used in different projects, including react-native, miniprogram(taro / uni-app) and web(react / vue).

English | [简体中文](README.CN.md)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Using nvm, node lts, npm lts and yarn is recommended.
  - Follow the links below and install nvm first
    - [nvm for Mac/Linux](https://github.com/nvm-sh/nvm)
    - [nvm-windows](https://github.com/coreybutler/nvm-windows)
    - Using [Homebrew](https://brew.sh/) to install nvm on Mac is **NOT** recommended
  - Then install node lts in terminal / command line

    ```sh
    # for now, lts version is 10.16.3
    # last updated: 2019.09.17
    nvm install 10.16.3
    ```

  - Globally update npm to lts and install yarn

    ```sh
    npm i -g npm@lts
    npm i -g yarn
    ```

  - If you are Chinese, maybe you should set mirrors
- Git is also required.
  - [git for Windows/Linux](https://git-scm.com/downloads)
  - Using [Homebrew](https://brew.sh/) to install git on Mac is recommended.

### Installing

```sh
yarn add @modyqyw/css-styles
# or
npm i @modyqyw/css-styles
```

### Usage

- taro / uni-app

Import `miniprogram/global.scss` as global styles.

```js
import '@modyqyw/css-styles/miniprogram/global.scss';
```

Import `miniprogram/vars.scss` to use preset colors.

```scss
@import '~@modyqyw/css-styles/miniprogram/vars'
```

- react / vue

Import `web/global.scss` as global styles.

```js
import '@modyqyw/css-styles/web/global.scss';
```

Import `web/vars.scss` to use preset colors.

```scss
@import '~@modyqyw/css-styles/web/vars'
```

- react native

Import `app/reactnative/global` to get preset colors, typography, layouts.

```js
import { colors, typography, layouts } from '@modyqyw/css-styles/app/reactnative/global'
// or
// import gStyles from '@modyqyw/css-styles/app/reactnative/global'
```

## Running the tests

No tests now. Pull requests are welcome.

## Features

- Preset layouts
- Preset typography
- Preset colors, two styles - Material Design and Ant Design

## Contributing

Please read [CONTRIBUTING.md](./CONTRIBUTING.md) for details on code of conduct, and the process for submitting pull requests.

## Versioning

Use [SemVer](http://semver.org/) for versioning. For the versions available, see the [releases on this repository](https://github.com/ModyQyW/css-styles/releases).

## Authors

- **Rui Wu** - *Initial work* - [ModyQyW](https://github.com/ModyQyW)

See also the list of [contributors](https://github.com/ModyQyW/css-styles/contributors) who participated in this project.

## License

[MIT](./LICENSE)

Copyright (c) 2019-present ModyQyW

## Acknowledgments

- [Material Design](https://material.io/)
- [Ant Design](https://ant.design/)
- [ElementUI](https://element.eleme.io/)
- [ColorUI](https://www.color-ui.com/)
- [ReactNativeElements](https://react-native-training.github.io/react-native-elements/)
- [NativeBase](https://nativebase.io/)
- [TaroUI](https://taro-ui.aotu.io/#/)
