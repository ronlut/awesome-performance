# Awesome web **performance** list

A curated list of awesome web performance stuff

## How-To’s

- [Performance Checklist](https://www.smashingmagazine.com/2020/01/front-end-performance-checklist-2020-pdf-pages/) - Everything you need to know in 2020
- [perf.rocks](https://perf.rocks/) - Find resources that help you build lightning fast websites
- [Metrics](https://web.dev/metrics/) - Measure and optimize performance and user experience
- [Fast load times](https://web.dev/fast/) - Guarantee your site loads quickly to avoid user drop off
- [Network reliability](https://web.dev/reliable/) - See consistent, reliable performance regardless of network quality
- [Measuring Performance With Server Timing](https://www.smashingmagazine.com/2018/10/performance-server-timing/) - The Server Timing header provides a discrete and convenient way to communicate backend server performance timings to developer tools in the browser. Adding timing information to your application enables you to monitor back-end and front-end performance all in one place.

## Articles

- [The Impact of Web Performance](https://simplified.dev/performance/impact-of-web-performance) - I’m going to show that rendering performance is more important than any of the Lighthouse page load metrics
- [Move Fast & Don’t Break Things](https://www.filamentgroup.com/lab/dontbreakthings/) - It’s true, new web technology is exciting, but we already have the tools to build amazing things and deliver them efficiently today.
- [Smaller HTML Payloads with Service Workers](https://philipwalton.com/articles/smaller-html-payloads-with-service-workers/) - A service worker can request just the bare minimum of data it needs from the server (e.g. an HTML content partial, a Markdown file, JSON data, etc.), and then it can programmatically transform that data into a full HTML document.
- [Using Native JavaScript Modules in Production Today](https://philipwalton.com/articles/using-native-javascript-modules-in-production-today/) - The technique allows you to ship significantly less code to module-supporting browsers, and it’s now supported by most web frameworks and CLIs.
- [ECMAScript modules in browsers](https://jakearchibald.com/2017/es-modules-in-browsers/) - All you need is type=module on the script element, and the browser will treat the inline or external script as an ECMAScript module.
- [Loading Polyfills Only When Needed](https://philipwalton.com/articles/loading-polyfills-only-when-needed/) - The solution to this problem is to only load polyfills when they’re needed, but as it turns out, in practice that’s a lot harder than it sounds.
- [When CSS Blocks](https://timkadlec.com/remembers/2020-02-13-when-css-blocks/) - Preload is a bit of a blunt instrument—whatever you apply to it is gonna jump way up in line to be downloaded. The use of preload means that these stylesheets, which you’re presumably making asynchronous because they aren’t very critical to page display, are given a very high priority by browsers.

## Implementations

- [Youtube Embed Component](https://github.com/paulirish/lite-youtube-embed) - Provide videos with a supercharged focus on visual performance. This custom element renders just like the real thing but approximately 224X faster.

## Tools

- [sitespeed.io](https://www.sitespeed.io/) - Sitespeed.io is a set of Open Source tools that makes it easy to monitor and measure the performance of your web site.
- [Turbolinks](https://github.com/turbolinks/turbolinks) - Get the performance benefits of a single-page application without the added complexity of a client-side JavaScript framework.
- [Quicklink](https://getquick.link/) - Faster subsequent page-loads by prefetching in-viewport links during idle time ([Angular module](https://www.npmjs.com/package/ngx-quicklink)).
- [Instant.page](https://github.com/instantpage/instant.page) - instant.page uses *just-in-time preloading* — it preloads a page right before a user clicks on it.
- ["constant-locals-loader" for Webpack](https://www.npmjs.com/package/constant-locals-loader) - This loader optimizes the output of mini-css-extract-plugin and/or css-loader, entirely removing the potentially large CSS classname mappings normally inlined into your bundle when using CSS Modules.

## Converter

- [webp](https://developers.google.com/speed/webp) - WebP is a modern **image format** that provides superior **lossless and lossy** compression for images on the web. Using WebP, webmasters and web developers can create smaller, richer images that make the web faster.
- [FFmpeg](https://www.ffmpeg.org/) - Converting **video** and **audio** has never been so easy.
- [svgo](https://github.com/svg/svgo) - **SVG O**ptimizer is a Nodejs-based tool for optimizing SVG vector graphics files ([Web GUI](https://jakearchibald.github.io/svgomg/)).

## Other awesome lists

- https://github.com/davidsonfellipe/awesome-wpo#readme
- https://github.com/csabapalfi/awesome-web-performance-metrics#readme
- https://github.com/pajaydev/awesome-web-performance-budget#readme
