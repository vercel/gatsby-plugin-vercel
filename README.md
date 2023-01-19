# gatsby-plugin-vercel

> **Note:** This plugin has been deprecated and replaced by [`@vercel/gatsby-plugin-vercel-analytics`](https://www.npmjs.com/package/@vercel/gatsby-plugin-vercel-analytics).

This plugin sends [Core Web Vitals](https://web.dev/vitals/) to Vercel Analytics. This plugin is configured by default on Vercel. You **do not** need to install it manually. For more information, [read this post](https://vercel.com/blog/gatsby-analytics).

## Install

```bash
npm i gatsby-plugin-vercel
```

or

```bash
yarn add gatsby-plugin-vercel
```

## Usage

```js
// gatsby-config.js
module.exports = {
  plugins: [
    {
      resolve: "gatsby-plugin-vercel",
      options: {
        // (optional) Prints metrics in the console when true
        debug: false,
      },
    },
  ],
};
```

## Inspiration

- [gatsby-plugin-web-vitals](https://github.com/bejamas/gatsby-plugin-web-vitals)
