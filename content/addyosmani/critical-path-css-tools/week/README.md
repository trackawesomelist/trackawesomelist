# Track Critical Path Css Tools Updates Weekly

Tools to prioritize above-the-fold (critical-path) CSS

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/addyosmani/critical-path-css-tools/week/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 addyosmani/critical-path-css-tools](https://github.com/addyosmani/critical-path-css-tools) · ⭐ 1.1K · 🏷️ Front-End Development

[ [Daily](/content/addyosmani/critical-path-css-tools/README.md) / Weekly / [Overview](/content/addyosmani/critical-path-css-tools/readme/README.md) ]

## [Jan 18 - Jan 24, 2016](/content/2016/3/README.md)

### Node modules

*   [Critical (⭐9.6k)](https://github.com/addyosmani/critical) - by Addy Osmani generates & inlines critical-path CSS (uses Penthouse, [Oust (⭐163)](https://github.com/addyosmani/oust) and inline-styles)

### Server-side modules

*   [mod\_pagespeed (⭐691)](https://github.com/pagespeed/mod_pagespeed) - Apache module for automatic PageSpeed optimization

### Online tools

*   [Penthouse online](https://jonassebastianohlsson.com/criticalpathcssgenerator/)

### Render-blocking issues detection

*   [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) - Online tool that measures the performance of a page for mobile devices and desktop devices. It fetches the url twice, once with a mobile user-agent, and once with a desktop-user agent.
*   [PSI (⭐3.1k)](https://github.com/addyosmani/psi) - Node module for PageSpeed Insights reporting as part of your build process. Use directly with Gulp or use [grunt-pagespeed (⭐464)](https://github.com/jrcryer/grunt-pagespeed) if a Grunt user. For local testing, a write-up using this task and [ngrok](http://www.jamescryer.com/2014/06/12/grunt-pagespeed-and-ngrok-locally-testing/) is available.

### Supplementary tools

*   [UnCSS (⭐9.3k)](https://github.com/giakki/uncss) removes unused CSS from pages, allowing you to reduce the global CSS you may need to load in for your site. Tasks are available for [Grunt (⭐3.9k)](https://github.com/addyosmani/grunt-uncss), [Gulp (⭐960)](https://github.com/ben-eb/gulp-uncss) and [other](https://addyosmani.com/blog/removing-unused-css/) build tools.

## [Jan 04 - Jan 10, 2016](/content/2016/1/README.md)

### Inline sources (styles, scripts)

*   [isomorphic-style-loader (⭐1.2k)](https://github.com/kriasoft/isomorphic-style-loader/) for Webpack - allows to extract critical CSS for any given page/screen in React apps and inline it into HTML during server-side rendering (SSR). See [React Starter Kit (⭐22k)](https://github.com/kriasoft/react-starter-kit) as an example.

## [Dec 07 - Dec 13, 2015](/content/2015/49/README.md)

### Grunt tasks

*   [grunt-critical (⭐149)](https://github.com/bezoerb/grunt-critical)

### Inline sources (styles, scripts)

*   [inline-critical (⭐106)](https://github.com/bezoerb/inline-critical) - by Ben Zörb, inline critical path CSS and load existing stylesheets with `loadCSS`

## [Aug 04 - Aug 10, 2014](/content/2014/31/README.md)

### PhantomJS

*   [dr-css-inliner (⭐81)](https://github.com/drdk/dr-css-inliner) - PhantomJS script to inline above-the-fold CSS on a page.

## [Jul 21 - Jul 27, 2014](/content/2014/29/README.md)

### Node modules

*   [Penthouse (⭐2.5k)](https://github.com/pocketjoso/penthouse) - by Jonas Ohlsson generates critical-path CSS
*   [CriticalCSS (⭐1.7k)](https://github.com/filamentgroup/criticalcss) - by FilamentGroup finds & outputs critical CSS

### Server-side modules

*   [ngx\_pagespeed (⭐4.4k)](https://github.com/pagespeed/ngx_pagespeed) - Nginx module for automatic PageSpeed optimization

### Grunt tasks

*   [grunt-penthouse (⭐68)](https://github.com/fatso83/grunt-penthouse)
*   [grunt-critical-css (⭐533)](https://github.com/filamentgroup/grunt-criticalcss)

### CasperJS

*   [critical-css-casperjs (⭐68)](https://github.com/ibrennan/critical-css-casperjs) - CasperJS script to pull critical CSS information from pages

### Inline sources (styles, scripts)

*   [inline-styles (⭐24)](https://github.com/maxogden/inline-styles) - by Max Ogden, replaces `<link>` tags with inline `<style>` tags + inlines CSS url() calls with data URIs
*   [gulp-inline-source (⭐211)](https://github.com/fmal/gulp-inline-source) - by Filip Malinowski, replaces `<link>` tags with inline `<style>` tags, and replaces `<script src="">` tags with their inline content

### Async load CSS

*   [loadCSS (⭐6.8k)](https://github.com/filamentgroup/loadCSS) - loads CSS asynchronously using JS. [Research](https://gist.github.com/scottjehl/87176715419617ae6994) that led to this is also available.
*   [async & conditional loading](https://gist.github.com/matt-bailey/602b40c77a5d3381ff26) - POC script for loading CSS files asynchronously and conditionally based on body tag classes
*   [asyncLoader (⭐0)](https://github.com/n0mad01/asyncLoader) - async script/stylesheet loader
*   [basket.js](http://addyosmani.github.io/basket.js/) - async script/resource loader with support for localStorage caching. Can be [extended (⭐19)](https://github.com/andrewwakeling/basket-css-example) to load stylesheets.

### Bookmarklets/Extensions

*   [Snippet](https://gist.github.com/PaulKinlan/6284142) by Paul Kinlan. Patrick Hamann has an [exercise](http://patrickhamann.com/workshops/performance/tasks/2_Critical_Path/2_2.html) using the snippet you can try out.
*   [Snippet](https://gist.github.com/scottjehl/b6129da04733e4e0f9a4) by Scott Jehl
*   [CSSVacuum (⭐45)](https://github.com/ndreckshage/CSSVacuum) by ndreckshage

### Render-blocking issues detection

*   [PageSpeed Insights DevTools extension](https://chrome.google.com/webstore/detail/pagespeed-insights-by-goo/gplegfbjlmmehdoakndmohflojccocli?hl=en) - Chrome extension for running PageSpeed tests from inside the browser.
*   [PageSpeed Insights Checker for mobile extension](https://chrome.google.com/webstore/detail/pagespeed-insights-checke/mkjmodmicmpjedhoekkmafdgpocdkbna?hl=en) - checks Mobile PageSpeed score for every page and gives you a handy preview.