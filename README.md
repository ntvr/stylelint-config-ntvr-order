# DEPRECATED stylelint-config-ntvr-order
⚠️ This package is deprecated in favour of [@ntvr/stylelint-config/order](https://github.com/ntvr/stylelint-config) config.


[![NPM version](http://img.shields.io/npm/v/@ntvr/stylelint-config-ntvr-order.svg)](https://www.npmjs.org/package/@ntvr/stylelint-config-ntvr-order)
[![Build Status](https://travis-ci.org/ntvr/stylelint-config-ntvr-order.svg?branch=master)](https://travis-ci.org/ntvr/stylelint-config-ntvr-order)
[![dependency Status](https://david-dm.org/ntvr/stylelint-config-ntvr-order/status.svg)](https://david-dm.org/ntvr/stylelint-config-ntvr-order)
[![peerDependency Status](https://david-dm.org/ntvr/stylelint-config-ntvr-order/peer-status.svg)](https://david-dm.org/ntvr/stylelint-config-ntvr-order?type=peer)
[![devDependency Status](https://david-dm.org/ntvr/stylelint-config-ntvr-order/dev-status.svg)](https://david-dm.org/ntvr/stylelint-config-ntvr-order?type=dev)

Ntvr' shareable config of properties order for
[Stylelint](https://github.com/stylelint/stylelint).

This config allows linting properties by defined [order](./index.js). It requires
[Stylelint](https://github.com/stylelint/stylelint) and its
[stylelint-order](https://github.com/hudochenkov/stylelint-order) plugin.

1. Install `stylelint`, `stylelint-order` and this config:

    ```sh
    $ yarn add --dev stylelint stylelint-order @ntvr/stylelint-config-ntvr-order
    ```

2. Add `"extends": "@ntvr/stylelint-config-ntvr-order"` to your `.stylelintrc` file.
