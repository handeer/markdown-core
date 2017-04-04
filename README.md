# Markdown Core

An extensible markdown engine used in the [Markdown Plus](https://github.com/tylingsoft/markdown-plus) project.


## Installation

```
yarn add markdown-core
```


## Usage

### Node.js

`index.js`:

```javascript
import mdc from 'markdown-core' // OR const mdc = require('markdown-core').default
const html = mdc.render('# hello world')
console.log(html)
```

    node -r ignore-styles index.js

Demo project: https://github.com/tylingsoft/markdown-core-node-demo

### Browser

Please refer to [the example](./dist).


## Development

### Build

```
yarn build
```

### Verify

Host and open `dist/index.html` in browser


## License

MIT


## Todo

- PPT
- Create a website for this project
    - GitHub pages
- `mdc.xxx` => `xxx`
- setup Travis CI and coveralls.io, add badges
- add lots of plugins as peer dependencies
- markdown-mate possible bug
- webpack bundle node and web separately
