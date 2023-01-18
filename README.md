# docusaurus-gtm

This docusaurus plugin Adds a Google Tag Manager script and noscript html tag to your docusaurus site.
This Plugin Adds the Google Tag Manager script to the headTags and the preBodyTags.

## Add Plugin

To add the plugin to your docusaurus v2 site, do this:

1. `yarn add docusaurus-gtm` (alternatively: `npm install --save docusaurus-gtm`)
2. Add the plugin to your `docusaurus.config.js` like this:

```js
module.exports = {
  plugins: [
    [
      require.resolve('docusaurus-gtm'),
      {
        id: 'GTM-XXXXXXX', // GTM Container ID
      }
    ]
  ],
  ...
};
```
