# currency-flags
This package outputs two CSS files (minified and unminified) with classes for currency codes using base64 background images inlined.

## How to use

**1. Install**

`bower install --save https://github.com/transferwise/currency-flags.git`

or

`npm install --save https://github.com/transferwise/currency-flags.git`

**2. Add CSS to page**

**3. Use**

```html
<div class="currency-flag currency-flag-gbp" style="width: 24px; height: 16px; background-size: cover;"></div>
```

<img src="http://i.imgur.com/Fdd5VLp.png">

The dimensions are specified on the element due to this package only outputting `background-image` values, this should actually happen in your CSS.

## How to add flags

1. Clone repo

2. Add correctly sized (`48x32`) `png` files to `src/flags`

3. Run `npm start`

4. Update version in `package.json`

5. Commit and open a pull request
