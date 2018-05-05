[![Build Status](https://travis-ci.org/o10n-x/wordpress-css-optimization.svg?branch=master)](https://travis-ci.org/o10n-x/wordpress-css-optimization) ![Version](https://img.shields.io/github/release/o10n-x/wordpress-css-optimization.svg)

# WordPress CSS Optimization

Advanced CSS optimization toolkit. Critical CSS, minification, concatenation, async loading, advanced editor, CSS Lint, Clean CSS (professional), beautifier and more.

* [Documentation](https://github.com/o10n-x/wordpress-css-optimization/tree/master/docs)
* [Description](https://github.com/o10n-x/wordpress-css-optimization#description)

**This plugin is removed from WordPress.org. Read the story [here](https://github.com/o10n-x/wordpress-css-optimization/issues/4).**

## Installation

![Github Updater](https://github.com/afragen/github-updater/raw/develop/assets/GitHub_Updater_logo_small.png)

This plugin can be installed and updated using [Github Updater](https://github.com/afragen/github-updater) ([installation instructions](https://github.com/afragen/github-updater/wiki/Installation))

## WordPress WPO Collection

This plugin is part of a Website Performance Optimization collection that include [Javascript](https://github.com/o10n-x/wordpress-javascript-optimization), [HTML](https://github.com/o10n-x/wordpress-html-optimization), [Web Font](https://github.com/o10n-x/wordpress-font-optimization), [HTTP/2](https://github.com/o10n-x/wordpress-http2-optimization), [Progressive Web App (Service Worker)](https://github.com/o10n-x/wordpress-pwa-optimization) and [Security Header](https://github.com/o10n-x/wordpress-security-header-optimization) optimization. 

The WPO optimization plugins provide in all essential tools that enable to achieve perfect [Google Lighthouse Test](https://developers.google.com/web/tools/lighthouse/) scores and to validate a website as [Google PWA](https://developers.google.com/web/progressive-web-apps/), an important ranking factor for Google's [Speed Update](https://searchengineland.com/google-speed-update-page-speed-will-become-ranking-factor-mobile-search-289904) (July 2018).

![Google Lighthouse Perfect Performance Scores](https://github.com/o10n-x/wordpress-css-optimization/blob/master/docs/images/google-lighthouse-pwa-validation.jpg)

The WPO optimization plugins are designed to work together with single plugin performance. The plugins provide the latest optimization technologies and many unique innovations.

### JSON shema configuration

The WPO optimization plugins are based on JSON schema based configuration that enables full control of the optimization using JSON. This provides several great advantages for website performance optimization.

Read more about [JSON schemas](https://github.com/o10n-x/wordpress-o10n-core/tree/master/schemas).

## Google PageSpeed vs Google Lighthouse Scores

While a Google PageSpeed 100 score is still of value, websites with a high Google PageSpeed score may score very bad in Google's new [Lighthouse performance test](https://developers.google.com/web/tools/lighthouse/). 

The following scores are for the same site. It shows that a perfect Google PageSpeed score does not correlate to a high Google Lighthouse performance score.

![Perfect Google PageSpeed 100 Score](https://github.com/o10n-x/wordpress-css-optimization/blob/master/docs/images/google-pagespeed-100.png) ![Google Lighthouse Critical Performance Score](https://github.com/o10n-x/wordpress-css-optimization/blob/master/docs/images/lighthouse-performance-15.png)

### Google PageSpeed score is outdated

For the open web to have a chance of survival in a mobile era it needs to compete with and win from native mobile apps. Google is dependent on the open web for it's advertising revenue. Google therefor seeks a way to secure the open web and the main objective is to rapidly enhance the quality of the open web to meet the standards of native mobile apps.

For SEO it is therefor simple: websites will need to meet the standards set by the [Google Lighthouse Test](https://developers.google.com/web/tools/lighthouse/) (or Google's future new tests). A website with perfect scores will be preferred in search over low performance websites. The officially announced [Google Speed Update](https://searchengineland.com/google-speed-update-page-speed-will-become-ranking-factor-mobile-search-289904) (July 2018) shows that Google is going as far as it can to drive people to enhance the quality to ultra high levels, to meet the quality of, and hopefully beat native mobile apps.

A perfect Google Lighthouse Score includes validation of a website as a [Progressive Web App (PWA)](https://developers.google.com/web/progressive-web-apps/).

Google offers another new website performance test that is much tougher than the Google PageSpeed score. It is based on a AI neural network and it can be accessed on https://testmysite.thinkwithgoogle.com

## Description

This plugin is a toolkit for professional CSS optimization.

The plugin provides in a complete solution for CSS code optimization, CSS delivery optimization (async CSS loading) and Critical CSS management.

The plugin provides the option to minify CSS code using multiple CSS minifiers including [CSSMin](https://github.com/natxet/CssMin) (PHP), Yahoo's [YUI Compressor PHP Port](https://github.com/tubalmartin/YUI-CSS-compressor-PHP-port), a fast regular expression based CSS minifier and the option to use a custom minifier using a WordPress filter that enables to use any solution, including a Amazon Lambda or Google Cloud function with Node.js based CSS optimization software. 

The plugin provides many unique innovations including conditional Critical CSS, timed CSS loading and/or rendering based on `requestAnimationFrame` with frame target, `requestIdleCallback`, element scrolled into view or a Media Query.

The plugin enables to render and unrender stylesheets based on a Media Query or element scrolled in and out of viewport enabling to optimize the CSS for individual devices (e.g. save +100kb of CSS on mobile devices). The plugin makes it possible to enable and disable stylesheets based on the viewport orientation change or element scrolled in or out of view event, making it possible (and easy to manage) to dynamically redesign a website based on events.

With debug modus enabled, the browser console will show detailed information about the CSS loading and rendering process including a [Performance API](https://developer.mozilla.org/nl/docs/Web/API/Performance) result for an insight in the CSS loading performance of any given configuration.

The plugin contains an advanced CSS editor with CSS Lint, Clean-CSS code optimization and CSS Beautifier. The editor can be personalized with more than 30 themes.

![Advanced CSS Editor](https://github.com/o10n-x/wordpress-css-optimization/blob/master/docs/images/css-editor.png)

Additional features can be requested on the [Github forum](https://github.com/o10n-x/wordpress-css-optimization/issues).