
[![NPM version][npm-img]][npm-url]
[![License][license-img]][license-url]
[![Dependency status][david-img]][david-url]

### react-flatpickr

[Flatpickr](https://github.com/chmln/flatpickr) for React.

### Usage

```jsx
import 'flatpickr/dist/flatpickr.material_green.min.css'

import Flatpickr from 'react-flatpickr'
import { Component } from 'react'

class App extends Component {
  render() {
    return (
      <Flatpickr data-enable-time
        onChange={v => console.info(v)} />
    )
  }
}
```

### License
MIT

[npm-img]: https://img.shields.io/npm/v/react-flatpickr.svg?style=flat-square
[npm-url]: https://npmjs.org/package/react-flatpickr
[travis-img]: https://img.shields.io/travis/coderhaoxin/react-flatpickr.svg?style=flat-square
[travis-url]: https://travis-ci.org/coderhaoxin/react-flatpickr
[codecov-img]: https://img.shields.io/codecov/c/github/coderhaoxin/react-flatpickr.svg?style=flat-square
[codecov-url]: https://codecov.io/github/coderhaoxin/react-flatpickr?branch=master
[license-img]: https://img.shields.io/badge/license-MIT-green.svg?style=flat-square
[license-url]: http://opensource.org/licenses/MIT
[david-img]: https://img.shields.io/david/coderhaoxin/react-flatpickr.svg?style=flat-square
[david-url]: https://david-dm.org/coderhaoxin/react-flatpickr
