# GlassLib

> Front-end framework inspired on Glassmorphism. Based on [Halfmoon](https://www.gethalfmoon.com).

- **Built-in dark mode**—Halfmoon/GlassLib comes with a built-in, toggleable dark mode, which is one of its most important and defining features.
- **Great for building dashboards and tools**—The components have a very standard look and feel to them, making them suitable for dashboards and tools. Moreover, a lot of importance is placed on components such as forms, navbars, sidebars, dropdowns, toasts, shortcuts, etc. and there are also *tons of utilities* available.
- **Optional JS library**—Many of the components found in Halfmoon/GlassLib are built to work without JavaScript. However, the framework still comes with a powerful JavaScript library with no extra dependencies, such as jQuery.
- **Bootstrap like classes**—The class names should be instantly familiar to anyone who has used Bootstrap.
- **Cross-browser compatibility**—Fully supports almost all the browsers under the sun, including really old ones like Internet Explorer 11.

To learn more, go to [the documentation](https://www.gethalfmoon.com/docs/introduction/). This is the main branch of the repo, which contains the latest stable release. For the ongoing development, see the [develop branch](https://github.com/halfmoonui/halfmoon/tree/develop).

## Quickstart

The quickest way to get started with GlassLib is by using the CDN to include the following files:

```html
<!-- GlassLib CSS -->
<link href="https://cdn.jsdelivr.net/npm/halfmoon@1.2.1/css/glasslib.min.css" rel="stylesheet" />

<!-- GlassLib JS -->
<script src="https://cdn.jsdelivr.net/npm/halfmoon@1.2.1/js/glasslib.min.js"></script>
```

**Pleast note**, the JS file should be placed at the end of the `<body>` tag. Otherwise, some things may not work as expected. For example, using the `onclick="..."` event to call one of GlassLib's built-in methods will not work **unless** the JS file is placed at the end of the `<body>` tag.


## Starter template generator

You can use the [starter template generator](https://www.gethalfmoon.com/docs/page-building/#starter-template-generator) to generate boilerplates for your project. The generator takes your settings and adds the appropriate classes and defines the required containers and elements.

Once again, we recommend reading [the documentation](https://www.gethalfmoon.com/docs/introduction/), as it contains a lot of examples to help you quickly build websites.

## License

Halfmoon/GlassLib is licensed under the [MIT](https://www.gethalfmoon.com/license/) license.

## Copyright

Copyright 2020, Halfmoon UI
Copyright 2021, GlassLib
