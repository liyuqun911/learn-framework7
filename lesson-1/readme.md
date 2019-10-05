# F7AppWeb

## Framework7 CLI Options

Framework7 app created with following options:

```
{
  "cwd": "D:\\MyProjects\\framework7\\f7\\lesson-1",
  "type": [
    "web"
  ],
  "name": "F7AppWeb",
  "framework": "core",
  "template": "single-view",
  "bundler": "webpack",
  "cssPreProcessor": "less",
  "theming": {
    "customColor": true,
    "color": "#007aff",
    "darkTheme": false,
    "iconFonts": true,
    "fillBars": false
  },
  "customBuild": true,
  "customBuildConfig": {
    "rtl": false,
    "themes": [
      "ios",
      "md",
      "aurora"
    ],
    "components": [
      "appbar",
      "dialog",
      "popup",
      "login-screen",
      "popover",
      "actions",
      "sheet",
      "toast",
      "preloader",
      "progressbar",
      "sortable",
      "swipeout",
      "accordion",
      "contacts-list",
      "virtual-list",
      "list-index",
      "timeline",
      "tabs",
      "panel",
      "card",
      "chip",
      "form",
      "input",
      "checkbox",
      "radio",
      "toggle",
      "range",
      "stepper",
      "smart-select",
      "grid",
      "calendar",
      "picker",
      "infinite-scroll",
      "pull-to-refresh",
      "lazy",
      "data-table",
      "fab",
      "searchbar",
      "messages",
      "messagebar",
      "swiper",
      "photo-browser",
      "notification",
      "autocomplete",
      "tooltip",
      "gauge",
      "skeleton",
      "menu",
      "color-picker",
      "treeview",
      "elevation",
      "typography"
    ]
  },
  "webpack": {
    "developmentSourceMap": true,
    "productionSourceMap": true,
    "hashAssets": false,
    "preserveAssetsPaths": false,
    "inlineAssets": true
  }
}
```

## NPM Scripts

* `npm start` - run development server
* `npm run build-prod` - build web app for production
* `npm run build-dev` - build web app using development mode (faster build without minification and optimization)

## WebPack

There is a webpack bundler setup. It compiles and bundles all "front-end" resources. You should work only with files located in `/src` folder. Webpack config located in `build/webpack.config.js`.

Webpack has specific way of handling static assets (CSS files, images, audios). You can learn more about correct way of doing things on [official webpack documentation](https://webpack.js.org/guides/asset-management/).
## Assets

Assets (icons, splash screens) source images located in `assets-src` folder. To generate your own icons and splash screen images, you will need to replace all assets in this directory with your own images (pay attention to image size and format), and run the following command in the project directory:

```
framework7 generate-assets
```

Or launch UI where you will be able to change icons and splash screens:

```
framework7 generate-assets --ui
```

## Documentation & Resources

* [Framework7 Core Documentation](https://framework7.io/docs/)


* [Framework7 Icons Reference](https://framework7.io/icons/)
* [Community Forum](https://forum.framework7.io)

## Support Framework7

Love Framework7? Support project by donating or pledging on patreon:
https://patreon.com/vladimirkharlampidi