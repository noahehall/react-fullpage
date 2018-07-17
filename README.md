# @ap.cx/react-fullpage

https://thierryc.github.io/react-fullpage/

0.0.8 Alpha Version. **Not for production**.

This project is still in a very **early stage**.
You shouldn't use this for production unless you really know what you're doing. 🖖

Try "features/variableHeight" branch.

https://github.com/thierryc/react-fullpage/tree/features/variableHeight

## Features

- Simple
- Mobile ready
- Hide safari's header on Scroll on iphone and ipad
- Hide Google Chrome's header on Scroll on iOS and Android
- Drived by the scroll
- CSS animation
- GPU/CPU swtich
- Very Small

> Create Fullscreen Scrolling Websites

[![NPM](https://img.shields.io/npm/v/@ap.cx/react-fullpage.svg)](https://www.npmjs.com/package/react-fullpage)
[![MIT](https://img.shields.io/packagist/l/doctrine/orm.svg)](https://github.com/thierryc/react-fullpage/blob/master/LICENSE)

## Install

```bash
npm install --save @ap.cx/react-fullpage
```

## Usage

```jsx
import React, { Component } from 'react'
import Fullpage, { FullpageSection } from '@ap.cx/react-fullpage'

export default class App extends Component {
  render () {
    return (
      <Fullpage>
        <FullpageSection style={{
          backgroundColor: 'lime',
          height: '80vh',
          padding: '1em',
        }}>1</FullpageSection>
        <FullpageSection style={{
          backgroundColor: 'coral',
          padding: '1em',
        }}>2</FullpageSection>
        <FullpageSection style={{
          backgroundColor: 'firebrick',
          padding: '1em',
        }}>3</FullpageSection>
      </Fullpage>
    )
  }
}

```

### For IE

```

npm i babel-polyfill

```

```
import "babel-polyfill";

```


## Mobile First

![Android Phone](https://raw.githubusercontent.com/thierryc/react-fullpage/master/static/images/android-phone.jpg)

## Thanks

Special thanks to [BrowserStack](https://www.browserstack.com/users/sign_up) for sponsoring this plugin. 👍

[![Browserstack](https://raw.githubusercontent.com/thierryc/react-fullpage/master/static/images/browserstack@2x.png)](https://www.browserstack.com/users/sign_up)

## License (MIT)

```
WWWWWW||WWWWWW
 W W W||W W W
      ||
    ( OO )__________
     /  |           \
    /o o|    MIT     \
    \___/||_||__||_|| *
         || ||  || ||
        _||_|| _||_||
       (__|__|(__|__|
```

MIT © [thierryc](https://github.com/thierryc)
Copyright (c) 2018-present anotherplanet.io, hello@anotherplanet.io

## Hit me up on Twitter

[@Autre_planete](https://twitter.com/Autre_planete?ref=github)
