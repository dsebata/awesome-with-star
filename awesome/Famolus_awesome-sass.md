# Information comes from [Famolus/awesome-sass](https://github.com/Famolus/awesome-sass)
![Awesome Sass](https://raw.githubusercontent.com/Famolus/awesome-sass/master/awesome-sass-logo-github.png)

# Awesome Sass [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Curated list of awesome [Sass](http://sass-lang.com/) and [SCSS](http://sass-lang.com/) frameworks, libraries, style guides, articles, and resources.

- Use <kbd>command</kbd> + <kbd>F</kbd> or <kbd>ctrl</kbd> + <kbd>F</kbd> to search for a keyword.
- Contributions welcome, please see [contribution guide](contributing.md).

## Contents
- [About](#about)
- [Getting Started](#getting-started)
- [Sass vs SCSS](#sass-vs-scss)
- [Frameworks](#frameworks)
- [Libraries and Mixins](#libraries-and-mixins)
  - [Grid](#grid)
  - [Media Queries](#media-queries)
  - [Color](#color)
  - [Typography](#typography)
  - [Animation](#animation)
  - [Miscellaneous](#miscellaneous)
- [Style Guides](#style-guides)
- [Articles](#articles)
- [Tools](#tools)
- [Books](#books)
- [Videos](#videos)
- [Community](#community)

## About
[Sass](http://sass-lang.com/) is an extension of CSS that adds power and elegance to the basic language. It allows you to use variables, nested rules, mixins, inline imports, and more, all with a fully CSS-compatible syntax. Sass helps keep large stylesheets well-organized, and get small stylesheets up and running quickly.

Sass has two syntaxes. The new main syntax (as of Sass 3) is known as "SCSS" (for "Sassy CSS"), and is a superset of CSS's syntax. This means that every valid CSS stylesheet is valid SCSS as well. SCSS files use the extension `.scss`.

The second, older syntax is known as the indented syntax (or just "Sass"). Inspired by Haml's terseness, it's intended for people who prefer conciseness over similarity to CSS. Instead of brackets and semicolons, it uses the indentation of lines to specify blocks. Although no longer the primary syntax, the indented syntax will continue to be supported. Files in the indented syntax use the extension `.sass`.

## Getting Started
- [Official Sass and SCSS Guide](http://sass-lang.com/guide) - Official Sass and SCSS guide.
- [Tutorialzine](http://tutorialzine.com/2016/01/learn-sass-in-15-minutes/) - Learn SASS in 15 minutes tutorial.
- [Codecademy](https://www.codecademy.com/learn/learn-sass) - Learn Sass with Codecademy.
- [Lynda](https://www.lynda.com/SASS-training-tutorials/1435-0.html) - Learn how to use Sass, from beginner basics to advanced techniques, with online video tutorials taught by industry experts.
- [Official Sass and SCSS Reference](http://sass-lang.com/documentation/file.SASS_REFERENCE.html) - Official Sass and SCSS Documentation Reference.
- [SitePoint Sass and SCSS Reference](https://www.sitepoint.com/sass-reference/) - SitePoint Sass and SCSS reference.

## Sass vs SCSS
- [SitePoint](https://www.sitepoint.com/whats-difference-sass-scss/) - What’s the difference between Sass and SCSS?
- [The Sass Way](http://thesassway.com/editorial/sass-vs-scss-which-syntax-is-better) - Which syntax is better?
- [Stack Overflow](http://stackoverflow.com/questions/5654447/whats-the-difference-between-scss-and-sass) - What's the difference between SCSS and Sass?

## Frameworks
- [avalanche](https://avalanche.oberlehner.net) - Framework for building the foundation for a package based CSS workflow.
- [Bootstrap 4](https://github.com/twbs/bootstrap) - Bootstrap version 4, the most popular HTML, CSS, and JS framework for developing responsive, mobile first projects on the web. :star:135123
- [Bootstrap-sass](https://github.com/twbs/bootstrap-sass) - Official Sass port of Bootstrap 2 and 3. :star:12776
- [Bulma](https://github.com/jgthms/bulma) - Modern CSS framework based on Flexbox. :star:36044
- [Foundation for Sites](https://github.com/zurb/foundation-sites) - The most advanced responsive front-end framework in the world. Quickly create prototypes and production code for sites that work on any kind of device. :star:28223
- [Hocus-Pocus](https://bkzl.github.io/hocus-pocus/) - Universal and lightweight stylesheet starter kit that focuses on base html elements and typography.
- [iotaCSS](https://www.iotacss.com) - Open source Sass-based OOCSS framework built for scale.
- [Kickoff](http://trykickoff.com) - Kickoff is a lightweight front-end framework for creating scalable, performant and responsive sites.
- [Materialize](http://materializecss.com) - Modern responsive front-end framework based on Material Design.
- [mini.css](http://minicss.org/) - Minimal, responsive, style-agnostic CSS framework.
- [Scooter](http://dropbox.github.io/scooter/) - SCSS framework built to provide base styles, CSS components, and rapid static prototyping for Dropbox.
- [Sierra](http://sierra-library.github.io/) - Micro SCSS library to help you build websites, without all the arbitrary selectors.

## Libraries and Mixins

### Grid
- [Avalanche](http://colourgarden.net/avalanche) - Lightweight, responsive, Sass-based, BEM-syntax grid system.
- [csswizardry-grids](http://csswizardry.com/csswizardry-grids/) - Simple, fluid, nestable, flexible, Sass-based, responsive grid system.
- [Griddle](http://necolas.github.io/griddle/) - Extremely flexable CSS grid constructor.
- [Gridlex](http://gridlex.devlint.fr/) - Flexbox grid system.
- [Jeet](https://github.com/mojotech/jeet) - Simple fractional grid system for Sass and Stylus. :star:3066
- [Neat](http://neat.bourbon.io/) - Lightweight semantic grid framework built with Sass.
- [Sass Flexible Grid System](https://dnomak.com/flexiblegs/install/sass/) - Sass flexible grid system.
- [SCSS Flexible Grid System](https://dnomak.com/flexiblegs/install/scss/) - SCSS flexible grid system.
- [Susy](https://github.com/oddbird/susy) - Responsive layout toolkit for Sass. :star:3949
- [Toast](http://daneden.github.io/Toast/) - Flexible and lightweight grid framework from the creator of [animate.css](https://daneden.github.io/animate.css/).
- [Waffle Grid](https://lucasgruwez.github.io/waffle-grid/) - Easy to use flexbox grid system.

### Media Queries
- [Breakpoint](https://github.com/at-import/breakpoint) - Breakpoint makes writing media queries in Sass super simple. :star:2054
- [include-media](http://include-media.com/) - Simple, elegant and maintainable media queries.
- [mq-scss](https://github.com/Dan503/mq-scss) - An extreamly powerful but easy to use Sass media query mixin. :star:118
- [Sass MediaQueries](http://rafalbromirski.github.io/sass-mediaqueries/) - Collection of useful media queries mixins for Sass (including iOS devices, TVs and more).
- [Sass MQ](https://github.com/sass-mq/sass-mq) - Sass mixin that helps you compose media queries in an elegant way. :star:1637

### Color
- [brand-colors](http://brand-colors.com/) - 1100+ collection of popular brand colors available in Sass, Less, Stylus and CSS.
- [Open color](https://github.com/yeun/open-color) - Open color is a color scheme for UI design. Available in CSS, SCSS, LESS, Stylus, Adobe library, Photoshop/Illustrator swatches and Sketch palette. :star:3656
- [sass-planifolia](https://github.com/xi/sass-planifolia) - Advanced color manipulation and contrast calculation in vanilla Sass. :star:26
- [scss-blend-modes](https://github.com/heygrady/scss-blend-modes) - Using standard color blending functions in Sass. :star:830

### Typography
- [Sassline](https://sassline.com/) - Set text on the web to a baseline grid with Sass & rems using a responsive modular-scale.
- [Sassy-Gridlover](https://github.com/hiulit/Sassy-Gridlover) - Super easy to use Sass mixins to establish a typographic system with modular scale and vertical rhythm. Based on the Gridlover app. :star:220
- [Shevy](http://kyleshevlin.github.io/shevy/) - Typography made easy. A vertical rhythm library.
- [Typi](https://github.com/zellwk/typi) - Sass mixin to make responsive typography easy. :star:839

### Animation
- [Animate.scss](https://github.com/geoffgraham/animate.scss) -  Port of Dan Eden's [Animate.css](https://daneden.github.io/animate.css/) for SASS. :star:596
- [Hover](http://ianlunn.github.io/Hover/) - Collection of CSS3 powered hover animated effects to be applied to links, buttons, logos, SVG, featured images and so on. Available in CSS, Sass, and LESS.
- [Kf](https://kf-sass.com) - Sass mixin library for creating keyframe-based animations from maps.
- [Sass Burger](https://github.com/jorenvanhee/sass-burger) - Sass mixin for creating animated hamburger icon. :star:669
- [SpinThatShit](https://matejkustec.github.io/SpinThatShit/) - Set of SCSS mixins for single element loaders and spinners.

### Miscellaneous
- [Angled Edges](https://github.com/josephfusco/angled-edges) - Sass mixin for creating angled edges on sections by dynamically encoding SVGs. :star:944
- [Bourbon](http://bourbon.io/) - Simple and lightweight mixin library for Sass.
- [Buttons](https://github.com/alexwolfe/Buttons) - CSS button library built using Sass and Compass. :star:5142
- [csstyle](https://csstyle.io) - A SCSS library to help you build modular CSS that generates your selectors for you and deals with specificity automatically.
- [Family.scss](http://lukyvj.github.io/family.scss/) - Set of 26 smart Sass mixins which will help you to manage the style of :nth-child’ified elements, in an easy and classy way.
- [Juice](http://kylebrumm.com/juice/) - Collection of Sass mixins and functions.
- [Modular Scale](https://github.com/modularscale/modularscale-sass) - Modular scale calculator built into your Sass. :star:1913
- [normalize-scss](https://github.com/JohnAlbin/normalize-scss) -  Sass/Compass version of Normalize.css, a collection of HTML element and attribute rulesets to normalize styles across all browsers. :star:1371
- [Pretty checkbox](https://github.com/lokesh-coder/pretty-checkbox) -  SCSS/CSS library to beautify checkbox and radio buttons. :star:1267
- [retina.js](https://github.com/imulus/retinajs) - JavaScript, SCSS, Sass, Less, and Stylus helpers for rendering high-resolution image variants. :star:4440
- [Sass Accoutrement](http://oddbird.net/open-source/accoutrement/) - Accoutrement modules are Sass toolkits that work together to form the central configuration of a project. The tools can be used individually, or integrated for extra power.
- [Sass Deprecate](https://github.com/salesforce-ux/sass-deprecate) - Sass mixin that helps managing code deprecation. :star:257
- [Sass flexbox mixin](https://github.com/mastastealth/sass-flex-mixin) - Set of mixins for those who want to mess around with flexbox using the native support of current browsers. :star:1147
- [Sassdash](https://github.com/davidkpiano/sassdash) - The Sass implementation of lodash ([API documentation](http://davidkpiano.github.io/sassdash)). :star:346
- [Scut](https://github.com/davidtheclark/scut) - Collection of Sass utilities to ease and improve the implementations of common style-code patterns. :star:769

## Style Guides
- [Hugo Giraudel's Sass Guidelines](https://sass-guidelin.es/) - Guidelines for writing sane, maintainable and scalable Sass.
- [BigCommerce Sass Coding Guidelines](https://github.com/bigcommerce/sass-style-guide) - Guidelines in use at BigCommerce. :star:247
- [Airbnb Sass and CSS Style Guide](https://github.com/airbnb/css) - Sass and CSS style guide by Airbnb. :star:4904
- [Dropbox (S)CSS Style Guide](https://github.com/dropbox/css-style-guide) - Dropbox’s (S)CSS authoring style guide. :star:708

## Articles
- [Hugo Giraudel Personal Awesome Sass List](https://github.com/HugoGiraudel/awesome-sass) - Records of Hugo Giraudel's works on Sass. :star:704
- [Cubic Bézier Representation in Sass](http://thesassway.com/advanced/cubic-bezier-representation-in-sass)
- [Faster Sass builds with Webpack](http://eng.localytics.com/faster-sass-builds-with-webpack/)
- [Transitioning to SCSS at Scale](https://codeascraft.com/2015/02/02/transitioning-to-scss-at-scale/)
- [Sass Maps to UI Components](https://blog.prototypr.io/sass-maps-to-ui-components-f14e1f34412e#.9zt0s0rxt)
- [Inverse trigonometric functions with Sass](http://thesassway.com/advanced/inverse-trigonometric-functions-with-sass)
- [Stop Arguing So Much with Your Mixins](http://sassbreak.com/stop-arguing-with-your-mixins)
- [Styling React Components in Sass](http://hugogiraudel.com/2015/06/18/styling-react-components-in-sass/)
- [A Sass !default use case](https://robots.thoughtbot.com/sass-default)
- [Aesthetic Sass 3: Typography and Vertical Rhythm](https://scotch.io/tutorials/aesthetic-sass-3-typography-and-vertical-rhythm)
- [A Tale of CSS and Sass Precision](https://www.sitepoint.com/a-tale-of-css-and-sass-precision/)
- [Build a Style Guide Straight from Sass](https://css-tricks.com/build-style-guide-straight-sass/)
- [Advanced SCSS, or, 16 cool things you may not have known your stylesheets could do](https://gist.github.com/jareware/4738651)
- [The 80-20 Approach to Sustainable SCSS](https://zendev.com/2018/05/30/the-80-20-approach-to-sustainable-scss.html)
- [Advanced Use of Sass Maps](https://itnext.io/advanced-use-of-sass-maps-bd5a47ca0d1a)

## Tools
- [dart-sass](https://github.com/sass/dart-sass) - Dart implementation of Sass. :star:1123
- [diamond](https://diamond.js.org) - Dependency management built for Sass, Less, and CSS.
- [libsass-python](https://github.com/dahlia/libsass-python) - Binding of libsass for Python. :star:421
- [libsass](https://github.com/sass/libsass) - C/C++ implementation of a Sass compiler. :star:4018
- [node-sass-magic-importer](https://github.com/maoberlehner/node-sass-magic-importer) - Custom node-sass importer for selector specific imports, node importing, module importing, globbing support and importing files only once. :star:211
- [node-sass](https://github.com/sass/node-sass) - Node.js bindings to libsass. :star:6496
- [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through *.scss and *.sass files efficiently with the OctoLinker browser extension for GitHub. :star:3799
- [sass-extract](https://github.com/jgranstrom/sass-extract) - Extract variables from scss files. Use scss to describe styles for use in javascript by extracting computed styles into js objects. Supports imports and advanced language features. :star:152
- [sass-loader](https://github.com/jtangelder/sass-loader) - Sass loader for webpack. :star:3104
- [sass-rails](https://github.com/rails/sass-rails) - Ruby on Rails stylesheet engine for Sass. :star:782
- [SassDoc](http://sassdoc.com/) - Documentation system (like JSDoc for JavaScript) to build pretty and powerful docs in the blink of an eye.
- [Scout-App](http://scout-app.io/) - Process your Sass and SCSS files into CSS without needing any knowledge of the command line.
- [scss-lint](https://github.com/brigade/scss-lint) - Configurable tool for writing clean and consistent SCSS. [(deprecated)](https://github.com/brigade/scss-lint#notice-consider-other-tools-before-adopting-scss-lint) :star:3358
- [SharpScss](https://github.com/xoofx/SharpScss) - P/Invoke .NET wrapper around libsass to convert SCSS to CSS supporting NET2.0/NET3.5/NET4.x+ and CoreCLR platform. :star:27
- [stylelint](https://stylelint.io/) - A mighty, modern CSS linter that helps you enforce consistent conventions and avoid errors in your stylesheets. Supports CSS-like syntaxes, including SCSS.

## Books
- [Sass in the Real World: Book I of IV](https://anotheruiguy.gitbooks.io/sassintherealworld_book-i/content/)
- [Sass in the Real World: Book II of IV](https://anotheruiguy.gitbooks.io/sass-in-the-real-world-book-2-of-4/content/)
- [Jump Start Sass: Get Up to Speed With Sass in a Weekend](https://www.amazon.com/Jump-Start-Sass-Speed-Weekend/dp/0994182678)
- [Sass and Compass for Designers](https://www.amazon.com/Sass-Compass-Designers-Ben-Frain/dp/1849694540)

## Videos
- [Sass Tutorial](https://www.youtube.com/watch?v=wz3kElLbEHE)
- [Series of Sass tutorials showing the installing of, the basics, and using key features](https://www.youtube.com/playlist?list=PL2CB1F80266E986EA)
- [Sass or LESS? What should you use?](https://www.youtube.com/watch?v=lJclQekSfSM)
- [Learn Sass in this Free Crash Course - Give your CSS Superpowers!](https://www.youtube.com/watch?v=roywYSEPSvc)
- [The Net Ninja Sass playlist](https://www.youtube.com/watch?v=St5B7hnMLjg&list=PL4cUxeGkcC9iEwigam3gTjU_7IA3W2WZA)

## Community
- [Reddit](https://www.reddit.com/r/Sass/)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/sass)
- [@SassCSS on Twitter](https://twitter.com/SassCSS)

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

