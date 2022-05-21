# use-viewport-sizes

![npm](https://img.shields.io/badge/npm-austral--ui%2Fuse--viewport--size-blue)
![GitHub issues](https://img.shields.io/github/issues-raw/oscarcornejo/use-viewport-size)
![NPM](https://img.shields.io/npm/dw/@austral-ui/use-viewport-size)

A tiny React hook which allows you to track visible window viewport size in your components.

## Installation

```
npm install @austral-ui/use-viewport-size
```

## Usage

### **See it in Action**

```
import React from 'react';
import { useViewportSize } from '@austral-ui/use-viewport-size';

export function App() {
  const { width, height } = useViewportSize();

  return (
    <div>
      <h2>Viewport Size</h2>
      <p>
        {width}px / {height}px
      </p>
    </div>
  );
}

export default App;
```

## Support

If you have read the examples and have any issues which you know are glitches, or would like to request something changed, please feel free to [post an issue on Github](https://github.com/oscarcornejo/use-viewport-size/issues/new).

Otherwise, if this was useful and you'd like to show your support, no donations necessary, but please consider [checking out the repo](https://github.com/oscarcornejo/use-viewport-size) and giving it a star (⭐).

## License

- Open Source **[MIT license](http://opensource.org/licenses/mit-license.php)**
