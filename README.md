react-jazzicon
==============
[![NPM version][npm-image]][npm-url] [![dependencies Status][david-dep-image]][david-dep-url] [![devDependencies Status][david-devDep-image]][david-devDep-url]

This is a react component for [Dan Finlay's](https://github.com/danfinlay)
[jazzicon](https://github.com/danfinlay/jazzicon).

# usage

```js
import Jazzicon from 'react-jazzicon'

export default class App extends React.Component {

  …

  render() {
    return (
      <Jazzicon diameter={100} seed={Math.random(100).toString()} />
    )
  }
}
```

# setup

```sh
$ https://github.com/marcusmolchany/react-jazzicon
$ cd react-jazzicon
$ yarn # or npm i
```

## demo page

the demo page is on the `gh-pages` branch in the `demo` folder.

```sh
# first install dependencies in the top level package
$ yarn # or npm i

# then checkout the gh-pages branch and install dependencies in the "demo" folder
$ git checkout gh-pages
$ cd demo && yarn # or npm i
$ yarn start # or npm run start
```

[david-dep-image]: https://david-dm.org/marcusmolchany/react-jazzicon/status.svg
[david-dep-url]: https://david-dm.org/marcusmolchany/react-jazzicon
[david-devDep-image]: https://david-dm.org/marcusmolchany/react-jazzicon/dev-status.svg
[david-devDep-url]: https://david-dm.org/marcusmolchany/react-jazzicon?type=dev
[npm-image]: https://badge.fury.io/js/react-jazzicon.svg
[npm-url]: https://npmjs.org/package/react-jazzicon
