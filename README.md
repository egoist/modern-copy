# modern-copy

[![NPM version](https://img.shields.io/npm/v/modern-copy.svg?style=flat)](https://npmjs.com/package/modern-copy) [![NPM downloads](https://img.shields.io/npm/dm/modern-copy.svg?style=flat)](https://npmjs.com/package/modern-copy) [![donate](https://img.shields.io/badge/$-donate-ff69b4.svg?maxAge=2592000&style=flat)](https://github.com/egoist/donate)

> A precompiled version of [sindresorhus/copy-text-to-clipboard](https://github.com/sindresorhus/copy-text-to-clipboard), clipboard in modern browsers.

## Install

```bash
❯ npm install modern-copy
```

CDN: [UNPKG](https://unpkg.com/modern-copy/dist/) | [jsDelivr](https://cdn.jsdelivr.net/npm/modern-copy/dist/)

## Usage

Direct use it in your build process, without any extra config:

```js
import mcopy from 'modern-copy'

button.addEventListener('click', () => {
  mcopy('👌🙋')
  // Must be called in response to a user gesture event, like click or keyup.
})
```

Or CDN version, access it via `window.mcopy`:

```html
<script src="https://unpkg.com/modern-copy"></script>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


## Author

**modern-copy** © [egoist](https://github.com/egoist), Released under the [MIT](./LICENSE) License.<br>
Authored and maintained by egoist with help from contributors ([list](https://github.com/egoist/modern-copy/contributors)).

> [egoistian.com](https://egoistian.com) · GitHub [@egoist](https://github.com/egoist) · Twitter [@rem_rin_rin](https://twitter.com/rem_rin_rin)
