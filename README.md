# gatsby-starter-strict

A Gatsby starter with a set of strict linting and auto-formatting rules.

Features:

* A set of strict linting rules and scripts
  * `lint` runs every linter
  * `lint:es` lints `js` and `jsx` files (based on the [Airbnb JavaScript Style Guide][])
  * `lint:style` lints `scss` files (based on [stylelint-config-recommended-scss][] and [stylelint-config-idiomatic-order][])
* Encourage automatic code formatting
  * `format` script
* Prefer using [Yarn](https://yarnpkg.com) for package management
* Use [EditorConfig](http://editorconfig.org) to maintain consistent coding styles between different editors and IDEs
* Integration with [Visual Studio Code](https://code.visualstudio.com)
  * Pre-configured auto-formatting on file save
* Based on [gatsby-starter-default](https://github.com/gatsbyjs/gatsby-starter-default)

For an overview of the project structure please refer to the [Gatsby documentation - Building with Components](https://www.gatsbyjs.org/docs/building-with-components/)

Install this starter (assuming Gatsby is installed) by running from your CLI:

```
gatsby new gatsby-example-site https://github.com/kripod/gatsby-starter-strict
```

[airbnb javascript style guide]: https://github.com/airbnb/javascript
[stylelint-config-recommended-scss]: https://github.com/kristerkari/stylelint-config-recommended-scss
[stylelint-config-idiomatic-order]: https://github.com/ream88/stylelint-config-idiomatic-order

## Deploy

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/kripod/gatsby-starter-strict)
