# currency-flags
This package outputs two CSS files (minified and unminified) with classes for currency codes using a base64 sprite inlined in CSS.

## How to use

**1. Install**

`bower install --save https://github.com/transferwise/currency-flags.git`

or

`npm install --save https://github.com/transferwise/currency-flags.git`

**2. Add CSS to page**

**3. Use**

```html
<div class="currency-flag currency-flag-gbp"></div>
```

## How to add flags

1. Clone repo

2. Add correctly sized (`48x32`) `png` files to `src/flags`

3. Run `npm start`

4. Update version in `package.json`

5. Commit and open a pull request
