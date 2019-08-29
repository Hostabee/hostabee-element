# \<hostabee-element\>

[![Build Status](https://travis-ci.org/Hostabee/hostabee-element.svg?branch=master)](https://travis-ci.org/Hostabee/hostabee-element)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/) [![Greenkeeper badge](https://badges.greenkeeper.io/Hostabee/hostabee-element.svg)](https://greenkeeper.io/)

Polymer element which embeds internationalization.

```html
<script>
  class MyElement extends Hostabee.Element {
    static get is() {
      return 'my-element';
    }
  }
  window.customElements.define(MyElement.is, MyElement);
</script>
```

## Installation

Install `<hostabee-element>`:

```shell
bower install Hostabee/hostabee-element --save
```

Once installed, import it in your application:

```html
<link rel="import" href="bower_components/hostabee-element/hostabee-element.html">
```

## Running demos and tests in a browser

1. Fork the `hostabee-element` repository and clone it locally.

2. Make sure you have [npm](https://www.npmjs.com/) and [Bower](https://bower.io) installed.

3. When in the `hostabee-element` directory, run `npm install` and then `bower install` to install dependencies.

4. Run `npm start`, browser will automatically open the component API documentation.

5. You can also open demo or in-browser tests by adding **demo** or **test** to the URL, for example:

- http://127.0.0.1:3000/components/hostabee-element/demo
- http://127.0.0.1:3000/components/hostabee-element/test

## Running Tests

- When in the `hostabee-element` directory, run `polymer test`

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git cz` **OR** [follow this commit guide](https://conventionalcommits.org/) to write the commit messages.

4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request.

## License

Apache License 2.0

## Credits

Cross-browser Testing Platform and Open Source ❤️Provided by:
<!-- Yes, I know. HTML inside mardown file... The only way to change the SVG size without open Inkscape. It could be your first good contribution to fix it! -->
[<img src="./images/sauce_labs_badge.svg" width="120">](https://saucelabs.com)
