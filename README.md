# @ap.cx/react-fullpage

https://thierryc.github.io/react-fullpage/

0.0.0.1 Alpha Version. Not for production.

## Features

- Simple
- Mobile ready
- Drived by the scroll
- CSS animation
- Very Small

> Create Fullscreen Scrolling Websites

[![NPM](https://img.shields.io/npm/v/@ap.cx/react-fullpage.svg)](https://www.npmjs.com/package/react-fullpage) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

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

## License

MIT © [thierryc](https://github.com/thierryc)
