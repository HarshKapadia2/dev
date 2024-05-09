# My Dev Resources

-   The crash course in each section is the bare minimum that should be done.
-   The resources have been aligned in a logical manner that should be followed.

## Table of Contents

-   [Prerequisites](#prerequisites)
-   [Front End](#front-end)
    -   [HTML](#html)
    -   [CSS](#css)
    -   [JS](#js)
-   [Misc #1](#misc-1)
    -   [Git and GitHub](#git-and-github)
    -   [Web Design](#web-design)
    -   [Browser DevTools](#browser-devtools)
    -   [Accessibility](#accessibility)
    -   [Documentation](#documentation)
    -   [Rendering Patterns](#rendering-patterns)
    -   [PWA (+ Service Worker API)](#pwa--service-worker-api)
    -   [Networking](#networking)
    -   [RegEx](#regex)
    -   [SVG](#svg)
    -   [Intersection Observer API](#intersection-observer-api)
    -   [InedxedDB](#indexeddb)
    -   [Web Components API](#web-components-api)
    -   [Misc Libraries](#misc-libraries)
    -   [TWA](#twa)
-   [General Back End Prerequisites](#general-back-end-prerequisites)
    -   [HTTP](#http)
    -   [JSON](#json)
    -   [APIs](#apis)
    -   [Async JS](#async-js)
    -   [Caching](#caching)
    -   [CORS](#cors)
    -   [Cookies](#cookies)
    -   [AJAX and its libraries](#ajax-and-its-libraries)
    -   [JWT](#jwt)
-   [Databases](#databases)
    -   [SQL](#sql)
    -   [NoSQL](#nosql)
-   [JS Back End](#js-back-end)
    -   [Node.js](#nodejs)
    -   [Express.js](#expressjs)
    -   [JS REST API](#js-rest-api)
-   [Python Back End](#python-back-end)
    -   [Prerequisite](#prerequisite)
    -   [Flask](#flask)
-   [PHP](#php)
    -   [Prerequisites](#prerequisites-1)
    -   [PHP REST API](#php-rest-api)
-   [Front End JS Frameworks/Libraries](#front-end-js-frameworkslibraries)
    -   [Prerequisites](#prerequisites-2)
        -   [Misc](#misc)
        -   [JavaScript](#javascript)
        -   [State](#state)
        -   [XML](#xml)
    -   [React.js](#reactjs)
-   [Misc #2](#misc-2)
    -   [Web Performance](#web-performance)
    -   [SEO](#seo)
        -   [`robots.txt`](#robotstxt)
    -   [Firebase](#firebase)
    -   [DevOps](#devops)
        -   [Git](#git)
        -   [Scripting](#shell-scripting)
        -   [Build Systems](#build-systems)
        -   [Deployment/Hosting](#deploymenthosting)
        -   [YAML](#yaml)
        -   [CI/CD](#cicd)
        -   [Docker](#docker)
        -   [Cloud](#cloud)
    -   [The Missing Semester of CS Education](#the-missing-semester-of-cs-education)
    -   [Character Sets and Encoding](#character-sets-and-encoding)
        -   [Unicode](#unicode)
        -   [New Lines/Line Endings](#new-linesline-endings)
-   [C](#c)
-   [Linux](#linux)

## My Resources

### Prerequisites

-   Browser (Google Chrome, Microsoft Edge, Brave or Firefox are preferred.)
-   [Set up VS Code](https://www.youtube.com/watch?v=fnPhJHN0jTE) (Code Editor)
-   [How To Setup Prettier](https://www.youtube.com/watch?v=DqfQ4DPnRqI) (Code Formatter)

### Front End

#### HTML

-   [Crash course](https://www.youtube.com/watch?v=UB1O30fR-EE)
-   [Validator](https://validator.w3.org) to check correctness of HTML.
-   [Best practices](https://github.com/hail2u/html-best-practices)
-   [When to use `target="_blank"`](https://css-tricks.com/use-target_blank)
-   [Absolute vs relative links](https://stackoverflow.com/a/14278020/11958552)
    -   Difference between `href="css/style.css"` (relative link) and `href="/css/style.css"` (absolute link).
-   The `<head>` of a HTML doc
    -   [Get Your Head Straight](https://www.youtube.com/watch?v=MHyAOZ45vnU)
        -   [ct.css](https://csswizardry.com/ct) - A diagnostic CSS snippet that exposes potential performance issues in a HTML document’s `<head>` tag.
    -   [HEAD](https://github.com/joshbuchea/HEAD) - A list of a lot of things that could go in the head of a HTML document.
-   The Open Graph Protocol (OGP)
    -   [ogp.me](https://ogp.me)
    -   Articles
        -   [What is Open Graph and how can I use it for my website?](https://www.freecodecamp.org/news/what-is-open-graph-and-how-can-i-use-it-for-my-website)
        -   [The-Open-Graph-protocol](https://indieweb.org/The-Open-Graph-protocol)
    -   [For Twitter cards](https://developer.twitter.com/en/docs/twitter-for-websites/cards/overview/abouts-cards)
    -   NOTE:
        -   For the image in the card, SVGs are not supported. Use a PNG or JPG image.
        -   The image/video/audio value has to be a URL _to a file_ (Eg: `https://harshkapadia.me/static/img/og-img.png`) and NOT a relative link (Eg: `static/img/og-img.png`) to a file in the project.
        -   The image size should be less than 300 kb for certain services.
        -   The `itemprop` attribute might be required. ([Source](https://stackoverflow.com/a/20429551/11958552), [Source](https://stackoverflow.com/questions/25100917/showing-thumbnail-for-link-in-whatsapp-ogimage-meta-tag-doesnt-work/64743183#64743183))
        -   [WhatsApp instructions](https://newbedev.com/provide-an-image-for-whatsapp-link-sharing)
        -   Audio and video are also supported, as mentioned on [ogp.me](https://ogp.me).
        -   [2020 standards](https://stackoverflow.com/questions/19778620/provide-an-image-for-whatsapp-link-sharing/43154489#43154489)
-   [Lazy loading attribute for images](https://css-tricks.com/native-lazy-loading)
-   [Maximally optimizing image loading for the web in 2021](https://www.industrialempathy.com/posts/image-optimizations)
-   Resource hints
    -   [`prefetch`, `preload` and `preconnect`](https://www.keycdn.com/blog/resource-hints)
    -   [`preconnect` and `dns-prefetch`](https://web.dev/preconnect-and-dns-prefetch)
    -   [`preconnect` resource hint and the `crossorigin` attribute](https://crenshaw.dev/preconnect-resource-hint-crossorigin-attribute)
-   [`async` and `defer` scripts](https://javascript.info/script-async-defer)
-   [URL Text Fragments](https://web.dev/text-fragments/#text-fragments)

#### CSS

-   [Crash course](https://www.youtube.com/watch?v=yfoY53QXEnI)
-   [Margin vs padding](https://www.differencebetween.com/difference-between-margin-and-vs-padding)
-   [`box-sizing` property](https://www.w3schools.com/css/css3_box-sizing.asp)
-   [Website layout](https://www.w3schools.com/css/css_website_layout.asp)
-   Selectors [PDF](https://webdevsimplified.com/specificity-cheat-sheet.html) or [article](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors)
-   [Pseudo-elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)
-   Specificity
    -   Order: `!important` > `inline` > `id selectors` > `class selectors + attribute selectors + pseudo-classes` > `element selectors (tags) + pseudo-elements`
    -   The number of ids, classes and tags for a particular element matter in the specifity as well. More of each implies an increase in specificity.
    -   `!important` trumps all, irrespective of the number of ids, classes and tags. Should be avoided as far as possible.
    -   Inline CSS trumps all but `!important`, irrespective of the number of ids, classes and tags. Should be avoided as far as possible.
    -   [Specificity illustrated](https://specifishity.com) (Format: `(<no_of_ids>, <no_of_classes+attribute_selectors+pseudo-classes>, <no_of_tags+pseudo-elements>)`)
        -   Most pseudo classes have the same specificity as a class. `is` and `where` are exceptions, with `where` having zero specificity and `is` using the highest value from its list.
    -   [`id` vs `class` specificity](https://css-tricks.com/the-difference-between-id-and-class/#comment-27579)
-   [Always maintaining round borders using `border-radius: 50%;`.](https://www.codecademy.com/forum_questions/559fe347e39efe4cf40005a9)
-   Positioning
    -   [`position` property](https://www.w3schools.com/Css/css_positioning.asp)
    -   [CSS Position Ultimate Guide](https://blog.webdevsimplified.com/2022-01/css-position)
-   [`display` property](https://alligator.io/css/display-inline-vs-inline-block)
-   CSS Flexbox
    -   [Livestream by Madhav Bahl](https://www.youtube.com/watch?v=LKmsQCUb0oE)
    -   [MadhavBahlMD/flex](https://github.com/MadhavBahlMD/flex)
    -   [Visualizer](https://lokeshdhakar.com/projects/flexitem)
    -   [Crash course by Brad Traversy](https://www.youtube.com/watch?v=JJSoEo8JSnc) (Haven't watched this.)
-   CSS Grid
    -   [Crash course](https://www.youtube.com/watch?v=EFafSYg-PkI)
    -   [Browser extension _Gridman_ for Grid lines](https://chrome.google.com/webstore/detail/gridman-css-grid-inspecto/cmplbmppmfboedgkkelpkfgaakabpicn) (Incase the DevTools don't support CSS Grid.)
-   [Media queries](https://www.w3schools.com/css/css3_mediaqueries.asp)
-   Units
    -   [`px`, `%`, `vh`, `vw`, `em` and `rem` (Part 1 of 2)](https://www.youtube.com/watch?v=gSL0hUPBgQA) (Hindi)
    -   [`rem` vs `em` (Part 2 of 2)](https://www.youtube.com/watch?v=W862VHnZ6Sw) (Hindi)
    -   [W3Schools](https://www.w3schools.com/CSSref/css_units.asp)
    -   [Viewport units](https://www.youtube.com/watch?v=5m6JOJLy5B0) (`vh`, `vw`, `vmin`, `vmax`, `vi`, `vb`, `lvh`, `dvh`, `svh`...)
-   [`clamp()` function](https://blog.webdevsimplified.com/2020-11/css-clamp) (view [MDN](<https://developer.mozilla.org/en-US/docs/Web/CSS/clamp()>) for more)
-   [Responsive web site tutorial](https://www.youtube.com/watch?v=ZeDP-rzOnAA&list=WL&index=155&t=0s)
-   Check responsiveness on various devices
    -   In the browser DevTools (best option)
    -   On [springload.responsinator.com](https://springload.responsinator.com)
-   [Why you should never use `px` to set font-size in CSS](https://joshcollinsworth.com/blog/never-use-px-for-font-size)
-   [Avoiding `<img>` layout shifts: `aspect-ratio` vs `width` & `height` attributes](https://jakearchibald.com/2022/img-aspect-ratio)
-   [2D Transforms](https://www.w3schools.com/Css/css3_2dtransforms.asp)
-   [Animations](https://www.w3schools.com/css/css3_animations.asp) ([High performance aimations](https://www.html5rocks.com/en/tutorials/speed/high-performance-animations))
-   [Transitions](https://www.w3schools.com/css/css3_transitions.asp)
-   [Custom properties (variables)](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)
-   [Bootstrap crash course](https://www.youtube.com/watch?v=5GcQtLDGXy8)
-   [`:is()`, `:where()`, `:has()` and `:not()` pseudo classes](https://www.youtube.com/watch?v=7matgtwNx4I)
    -   Most pseudo classes have the same specificity as a class. `is` and `where` are exceptions, with `where` having zero specificity and `is` using the highest value from its list.
-   `:last-child` vs `:last-of-type` pseudo-classes
    -   [The Difference Between `:nth-child` and `:nth-of-type`](https://css-tricks.com/the-difference-between-nth-child-and-nth-of-type)
    -   [CSS Gotchas: last-child vs. last-of-type and other bizarre conundrums](https://g-liu.com/blog/2014/12/css-last-child-vs-last-of-type-and-other-bizarre-conundrums)
    -   [The `last-child` vs `last-of-type` selector in CSS](http://www.js-craft.io/blog/the-last-child-vs-last-of-type-selector-in-css)
    -   [Difference Between `:last-child` and `:last-of-type` Selector in CSS](https://www.webdevelopmentinstitute.com/blog/difference-between-last-child-and-last-of-type-selector-in-css)
-   [Sub-string matching selectors](https://blog.teamtreehouse.com/css3-substring-matching-attribute-selectors) (Eg: `[class*="col-"] { width: 100%; }`)
-   [Scrollbar styling](https://css-tricks.com/almanac/properties/s/scrollbar)
-   [`scroll-padding`](https://css-tricks.com/almanac/properties/s/scroll-padding)
    -   Add the property to the `html` element for it to work.
-   [Only load required characters in Google Fonts](https://www.youtube.com/watch?v=Ez1huZ-kfY4) (Saves bandwidth)
-   CSS basics
    -   [Redo Your CSS](https://learn.redoyourcss.com) ([Main site](https://www.redoyourcss.com))
-   [Some design resources](https://github.com/bradtraversy/design-resources-for-developers)

#### JS

-   [Crash course](https://www.youtube.com/watch?v=hdI2bqOjy3c)
-   [`var` vs `let` vs `const`](https://blog.webdevsimplified.com/2020-01/var-vs-let-vs-const)
-   [Reference vs value](https://blog.webdevsimplified.com/2021-03/js-reference-vs-value)
-   [Document Object Model](https://medium.com/@EdidiongAsikpo/getting-started-with-the-dom-d27907f17be0) (DOM)
-   [`window` vs `document`](https://stackoverflow.com/questions/9895202/what-is-the-difference-between-window-screen-and-document-in-javascript)
-   [`element.classList`](https://blog.webdevsimplified.com/2020-11/class-list)
-   Callbacks
    -   [The Art of Node: Callbacks](https://github.com/maxogden/art-of-node#callbacks)
    -   [How (not) to get a value "out of" a callback.](https://felix-kling.de/blog/2019/javascript-callbacks-misconceptions.html)
    -   Promises can be one way to get data 'out' of a callback. ([Example](https://github.com/HarshKapadia2/git-graph/blob/main/src/util/generateObjects.js#L161))
-   [HTML Element vs HTML Node and HTMLCollection vs NodeList](https://www.youtube.com/watch?v=rhvec8cXLlo) ([PDF](https://webdevsimplified.com/js-dom-traversal-cheat-sheet.html))
-   [Data attributes](https://blog.webdevsimplified.com/2020-10/javascript-data-attributes) (`element.dataset` property - view [MDN](https://developer.mozilla.org/en-US/docs/Web/API/HTMLOrForeignElement/dataset) for more.)
-   [`localStorage` vs `sessionStorage`](https://blog.webdevsimplified.com/2020-08/cookies-localStorage-sessionStorage) (view [javascript.info](https://javascript.info/localstorage) for more differences)
-   Events
    -   [Event reference](https://developer.mozilla.org/en-US/docs/Web/Events) (`load`, `click`, `change`, `submit`, etc)
    -   [Page: DOMContentLoaded, load, beforeunload, unload](https://javascript.info/onload-ondomcontentloaded)
-   [Rounding off](https://medium.com/swlh/how-to-round-to-a-certain-number-of-decimal-places-in-javascript-ed74c471c1b8)
-   [Handling `NaN`](https://blog.webdevsimplified.com/2020-10/javascript-nan)
-   [Some cases of file handling](https://developer.mozilla.org/en-US/docs/Web/API/File/Using_files_from_web_applications)
-   [Responsive nav bar tutorial](https://www.youtube.com/watch?v=gXkqy0b4M5g)
-   [HTML Drag and Drop API](https://www.youtube.com/watch?v=Wtrin7C4b7w)
-   [`navigator.sendBeacon()`](https://benborgers.com/posts/navigator-sendbeacon)
-   Modules
    -   [Intro](https://www.youtube.com/watch?v=cRHQNNcYf6s)
    -   [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules)
    -   [`import` statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import)
    -   [`export` statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/export)
    -   [JS modules and build tools](https://www.youtube.com/watch?v=U4ja6HeBm6s)
-   Internals
    -   [Namaste :pray: JavaScript](https://www.youtube.com/watch?v=pN6jk0uUrD8&list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP&index=1)
    -   [JS modules and build tools](https://www.youtube.com/watch?v=U4ja6HeBm6s)
    -   [Closures](https://dmitripavlutin.com/simple-explanation-of-javascript-closures)
    -   [Event loop](https://www.youtube.com/watch?v=8aGhZQkoFbQ&feature=youtu.be)
    -   [Concept Visualise - JavaScript Internals](https://www.youtube.com/watch?v=R4jZ_Mylqaw)
    -   [JS Internals Visualizer](https://www.jsv9000.app)
    -   [Scheduling in JS and browsers](https://www.youtube.com/watch?v=z96oKTUSQjE) ([Tweet](https://twitter.com/reactify_in/status/1309843620179054592))

### Misc #1

#### Git and GitHub

-   Sessions by me
    -   [Git Basics - The Basics of Git and GitHub](https://talks.harshkapadia.me/git_basics)
    -   [The basics of Branching, Issues and Pull Requests](https://youtu.be/LfgDc7BbhaY?t=946)
    -   [Git Internals - How does Git work!?](https://talks.harshkapadia.me/git_internals)
    -   [Hacktoberfest, Open Source and Pull Requests](https://talks.harshkapadia.me/otc_open_source_hacktoberfest_2020)
    -   [More talks](https://talks.harshkapadia.me)
-   [git_basics PWA](https://harshkapadia2.github.io/git_basics)
-   [Git Internals PWA](https://git.harshkapadia.me)
-   [Crash course by Brad Traversy](https://www.youtube.com/watch?v=SWYqp7iY_Tc)
-   [Git Server](https://github.com/HarshKapadia2/git-server)

#### Web Design

-   [Typography 101](https://www.youtube.com/watch?v=HnpsOtIcfbo)
-   [Color theory 101](https://www.youtube.com/watch?v=e_kdWMmD3z0)
-   [Layout design](https://www.youtube.com/watch?v=S4viQ_Ejptc)
-   [Top Design Resources and Apps](https://www.youtube.com/watch?v=GUOgv4PcHIQ)
-   [Making text stand out in front of images](https://graphicdesign.stackexchange.com/questions/57472/making-text-stand-out-in-front-of-images)
-   [Figma crash course](https://www.youtube.com/watch?v=4W4LvJnNegA)
-   [Image compression deep-dive](https://www.youtube.com/watch?v=F1kYBnY6mwg)

#### Browser DevTools

-   [Guide to Chrome's performance profiler](https://www.youtube.com/watch?v=KWM5wxlDuis)
-   [Chrome DevTools documentation](https://developers.google.com/web/tools/chrome-devtools)
-   [Crash course (Brad Traversy)](https://www.youtube.com/watch?v=x4q86IjJFag)
-   [Crash course (FreeCodeCamp)](https://www.youtube.com/watch?v=gTVpBbFWry8)

> NOTE: The DevTools are similar in almost all browsers, so the above resources are fine.

-   [Check the support of a front end web technology on desktop and mobile web browsers.](https://caniuse.com/ciu/about)

#### Accessibility

-   [Exploring Web Accessibility](https://explore-a11y.netlify.app)

#### Documentation

-   [Presentation and Documentation](https://undirected-graph.netlify.app/posts/presentation#:~:text=LinkedIn%20Post.-,Documentation,the%20next%20best%20thing%20after%20the%20presentation%20is%20passive%20presentation%20%E2%80%94%20Documentation.,-What%20even%20is)
-   [Hack the Project Onboarding Process: Learning by Writing Tutorials as a New Contributor](https://www.youtube.com/watch?v=_BqI1o7sbkw)
    -   Slightly unrelated: [A Guide for Contributing to Any Open Source JavaScript Project Ever](https://dev.to/saurabhdaware/a-guide-for-contributing-to-any-open-source-javascript-project-ever-hi)

#### Rendering Patterns

-   [10 Rendering Patterns for Web Apps](https://www.youtube.com/watch?v=Dkx5ydvtpCA)
-   [Rendering Patterns](https://www.lydiahallie.io/blog/rendering-patterns)

#### PWA (+ Service Worker API)

-   Prerequisite: [Caching](#caching)
-   [Crash course](https://www.youtube.com/watch?v=ksXwaWHCW6k) (Intro to Service Workers and Caching)
-   [Progressive Web Apps in 100 seconds](https://www.youtube.com/watch?v=sFsRylCQblw)
-   [Extra PWA features](https://www.youtube.com/watch?v=ppwagkhrZJs)
-   [Offline-first PWAs](https://www.youtube.com/watch?v=cmGr0RszHc8) (A good overview)
-   [Demistifying Web Workers and Service Workers](https://www.youtube.com/watch?v=OgLemdR65pE) (Some content of the talk is outdated.)
-   [The Modern PWA Cheat Sheet](https://www.youtube.com/watch?v=cybhV88KLfI)
-   [Service Workers MDN](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API/Using_Service_Workers)
-   [The offline cookbook](https://jakearchibald.com/2014/offline-cookbook) (Caching and network strategies.)
-   [Application Cache is a Douchebag](https://alistapart.com/article/application-cache-is-a-douchebag) (Caching gotchas.)
-   [Creating a PWA with JS](https://dev.to/devpato/how-to-create-a-pwa-with-javascript-4jlh)
-   PWA Manifest
    -   [Important manifest options](https://web.dev/add-manifest)
    -   [All manifest options](https://w3c.github.io/manifest)
    -   The manifest file can have a `.json` or a `.webmanifest` extension. [The spec suggests `.webmanifest`.](https://w3c.github.io/manifest/#:~:text=File%20extension%3A%20.webmanifest%20or%20.json%3F)
    -   [`id` property](https://developer.chrome.com/blog/pwa-manifest-id)
-   [Icon generator](https://www.pwabuilder.com/imageGenerator)
-   [Customizing the install experience](https://web.dev/customize-install)
-   The Application tab in the Dev Tools can be used to check the service worker status and the manifest.
-   Use LightHouse for debugging and checking.
-   Service Workers are not just used for PWAs. They are used just for caching as well.
-   Caching is an important concept for PWAs. Please go through [Caching section](#caching) below.
-   In a PWA, static files need to be manually cached during the install event, because the Service Worker is not active by then to cache the initial response. Also, every file has to be listed individually, as directories are not recognized.
-   Once a PWA is installed, the icons cannot be changed. The change is reflected on re-installing the PWA. (I think TWAs can change their icons. Check the [TWA section](#twa) below for more info.)
-   An offline PWA does not have access to Local Storage. (The service worker does not allow it.) IndexedDB can be used in place. ([IndexedDB section](#indexeddb) below.)
-   [Some problems with Service Workers](https://www.youtube.com/watch?v=JJSloXLTyNg)

#### Networking

-   [My notes and resources](https://networking.harshkapadia.me)

#### RegEx

-   [My RegEx notes and resources](https://harshkapadia2.github.io/regex)

#### SVG

-   [Get started](https://webdesign.tutsplus.com/tutorials/how-to-hand-code-svg--cms-30368)

#### Intersection Observer API

-   [15 minute crash course](https://www.youtube.com/watch?v=2IbRtjez6ag)
-   [MDN](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API)
-   [Scroll to top button](https://css-tricks.com/how-to-make-an-unobtrusive-scroll-to-top-button/#option-3-intersection-observer)

#### IndexedDB

-   [Crash course](https://www.youtube.com/watch?v=vb7fkBeblcw)

#### Web Components API

-   [Crash course](https://www.youtube.com/watch?v=PCWaFLy3VUo)
-   [HTML with Superpowers](https://www.youtube.com/watch?v=fEhBkSZ15qM)

#### Misc Libraries

-   [Color Thief](https://lokeshdhakar.com/projects/color-thief) - Grab the color palette from an image using JS. Works in the browser and in Node.js.

#### TWA

-   Prerequisites
    -   [PWA](#pwa--service-worker-api)
    -   Google Play Console Developer Account ($25 fee)
-   [What is a Trusted Web Activity?](https://www.youtube.com/watch?v=7JDFjeMvxos)
-   [TWA overview](https://developer.chrome.com/docs/android/trusted-web-activity/overview)
-   [Build a TWA from an existing PWA](https://www.pwabuilder.com) ([Steps after downlaoding](https://github.com/pwa-builder/CloudAPK/blob/master/Next-steps.md) and [Asset Link file instructions](https://github.com/pwa-builder/CloudAPK/blob/master/Asset-links.md))
-   Hosting a TWA using GitHub Pages
    -   NOTE: The PWA can be hosted from any of **your** repos. The instructions below have to be followed nonetheless.
    -   Create a repo with the name `<github_username>.github.io`.
    -   The `.well-known/assetlinks.json` file should be in the root directory of the newly created repo. ([More info](https://www.mydatahack.com/releasing-multiple-pwas-to-googleplay-by-using-a-single-github-page-root))
    -   If you're not using [Jekyll](https://jekyllrb.com), add an empty `.nojekyll` file to the root directory of the newly created repo. ([Reason](https://github.community/t/unable-to-access-resources-in-folder-with-name-starting-with/10505))
    -   If you're using [Jekyll](https://jekyllrb.com), change your `_config.yml` file to include the `.well-known` folder.

### General Back End Prerequisites

#### HTTP

-   [What is HTTP?](https://www.youtube.com/watch?v=0OrmKCB0UrQ)
-   [Crash course](https://www.youtube.com/watch?v=iYM2zFP3Zn0)
-   [HTTP methods, status codes and versions](https://harshkapadia2.github.io/networking/http.html)

#### JSON

-   [Crash course](https://www.youtube.com/watch?v=iiADhChRriM)
-   [Schema templates](https://www.schemastore.org/json) (for JSON, JavaScript and CSS)
-   [`JSON.stringify`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify) and its [optional parameters](https://www.youtube.com/watch?v=0k4NwimfszA).
-   [`JSON.parse`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/parse)

#### APIs

-   [Everything about APIs](https://blogs.omkaragrawal.dev/everything-about-apis)
-   [REST (RESTful) API introduction](https://www.youtube.com/watch?v=Q-BpqyOT3a8)
-   [REST in short](https://www.youtube.com/watch?v=6sUbt-Qp6Pg)
-   [REST Web Service](https://www.youtube.com/watch?v=lyxJQWUymV4&list=PLhW3qG5bs-L9E2KV6vVdB-YTk-sRxmRAB&index=5)
-   [Designing an API](https://www.youtube.com/watch?v=_YlYuNMTCc8)
-   [Some public APIs](https://github.com/public-apis/public-apis)
-   [Google Translate API](https://www.w3schools.com/howto/howto_google_translate.asp)

#### Async JS

-   [Crash course](https://www.youtube.com/watch?v=_8gHHBlbziw)
-   [`async`/`await` article](https://www.freecodecamp.org/news/async-await-javascript-tutorial)

#### Caching

-   [CacheStorage API](https://developer.mozilla.org/en-US/docs/Web/API/CacheStorage)
-   [Cache API](https://developer.mozilla.org/en-US/docs/Web/API/Cache)
-   [Cache-Control header](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Cache-Control)
-   Difference between the Cache API and CacheStorage API
    -   [Tweet](https://twitter.com/harshgkapadia/status/1355100023705493507)
    -   A Cache is an object (file) and Cache Storage is a file system.
-   [Cache Busting](https://medium.com/javascript-in-plain-english/what-is-cache-busting-55366b3ac022) ([CSS-Tricks article](https://css-tricks.com/strategies-for-cache-busting-css))
-   [Application Cache is a Douchebag](https://alistapart.com/article/application-cache-is-a-douchebag) (Caching gotchas.) (Refer to [PWA section](#pwa--service-worker-api) above.)

#### CORS

-   Prerequisite
    -   [Fetch API](#ajax-and-its-libraries)
-   Session by me
    -   [Working with CORS](https://talks.harshkapadia.me/cors)
-   [Tackling CORS quickly](https://www.youtube.com/watch?v=PNtFSVU-YTI)
-   [MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS) (Pretty extensive.)
-   [CORS explained by example](https://www.youtube.com/watch?v=Ka8vG5miErk)
-   [How to win at CORS](https://jakearchibald.com/2021/cors)
-   CORS proxies
    -   [What are they and why are they required?](https://httptoolkit.tech/blog/cors-proxies) (Primer article.)
    -   [CORS Anywhere](https://github.com/Rob--W/cors-anywhere)
    -   [CORS Bridged](https://app.cors.bridged.cc) ([Usage guide](https://blog.grida.co/cors-anywhere-for-everyone-free-reliable-cors-proxy-service-73507192714e))
    -   [List of proxies and more](https://gist.github.com/jimmywarting/ac1be6ea0297c16c477e17f8fbe51347) (Some are dead.)
-   Credentialed requests through the [`Authorization` header](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Authorization) using the [Fetch API](#ajax-and-its-libraries)
    -   Demos by me
        -   [HarshKapadia2/cors](https://github.com/HarshKapadia2/cors)
        -   [HarshKapadia2/flask-jwt-cors](https://github.com/HarshKapadia2/flask-jwt-cors)
    -   The [`Access-Control-Allow-Headers` header](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Access-Control-Allow-Headers) can't be wildcarded (`*`) and the `Authorization` header always needs to be listed explicitly.
        -   Side note: If the `Content-Type` request header's value is `application/json`, add it to the value of the `Access-Control-Allow-Headers` response header. ([Source](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS#:~:text=The%20only%20type/subtype%20combinations%20allowed%20for%20the%20media%20type%20specified%20in%20the%20Content%2DType%20header%20are%3A))
    -   The [`Access-Control-Allow-Methods` header](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Access-Control-Allow-Methods) can't be wildcarded (`*`) and all the allowed [HTTP request methods](https://networking.harshkapadia.me/http#http-request-methodsverbs) need to be listed explicitly.
    -   The [`Access-Control-Allow-Origin` header](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Access-Control-Allow-Origin) can't be wildcarded (`*`) and the origin always needs to be listed explicitly. ([Source](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS#:~:text=Note%3A%20When%20responding%20to%20a%20credentialed%20requests%20request%2C%20the%20server%20must%20specify%20an%20origin%20in%20the%20value%20of%20the%20Access%2DControl%2DAllow%2DOrigin%20header%2C%20instead%20of%20specifying%20the%20%22*%22%20wildcard.))
        -   This header needs to not only be sent in the response to the preflight request, but in the response to the the actual request as well.
    -   The [`Access-Control-Allow-Credentials` header](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Access-Control-Allow-Credentials) needs to be sent
        -   [In response to the preflight request](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS#requests_with_credentials) and in response to the actual request after the preflight request as well.
        -   [In response to the simple (non-preflighted) requests that require authorization.](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS#:~:text=Line%207%20shows,invoking%20web%20content.)
    -   In Fetch, the [`credentials: "include"` option](https://developer.mozilla.org/en-US/docs/Web/API/fetch#credentials) has to be added.
        -   This option is what adds the strictness of adding non-wildcarded values to each of the response headers.
        -   [Fetch does not send any Cookies by default](https://medium.com/cameron-nokes/4-common-mistakes-front-end-developers-make-when-using-fetch-1f974f9d1aa1#:~:text=Unlike%20XHR%2C%20fetch%20does%20not%20include%20any%20cookies%20in%20the%20request%20by%20default.) and [this option makes the browser send 1st and 3rd party Cookies to the server](https://zellwk.com/blog/handling-cookies-with-fetchs-credentials/#:~:text=domains%20or%20subdomains.-,If%20you%20set,3rd%20party%20cookies%20set%20by%20a%20specific%20domain%20that%20domain%E2%80%99s%20server.,-Access%2DControl%2DAllow).
    -   When using Fetch, remember to return appropriate CORS headers with the error response as well, otherwise the Fetch call itself will fail and the actual error will not be caught.
        -   A CORS error will pop up for errors returned without appropriate CORS headers, instead of returning the actual error and that can get very confusing.

#### Cookies

-   [Crash course](https://www.youtube.com/watch?v=sovAIX4doOE)
-   [`SameSite` Cookie Attribute](https://www.youtube.com/watch?v=aUF2QCEudPo)

#### AJAX and its libraries

-   [Crash course](https://www.youtube.com/watch?v=82hnvUYY6QA) (with `XMLHttpRequest`, i.e., `XHR`)
-   Fetch API
    -   [Hands on introduction](https://www.youtube.com/watch?v=Oive66jrwBs)
    -   [Fetch API error handling](https://www.youtube.com/watch?v=cuEtnrL9-H0)
    -   [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) (MDN)
    -   [Common `no-cors` misconceptions](https://evertpot.com/no-cors)
        -   The response body, status or headers cannot be read.
    -   [Handling cookies with Fetch’s credentials](https://zellwk.com/blog/handling-cookies-with-fetchs-credentials)
    -   [Common mistakes](https://medium.com/cameron-nokes/4-common-mistakes-front-end-developers-make-when-using-fetch-1f974f9d1aa1)
-   [Playlist: Async JS, AJAX, XHR, Fetch, Cookies, CORS, Headers, Auth, etc.](https://www.youtube.com/watch?v=7EKebb4VUYQ&list=PLyuRouwmQCjkWu63mHksI9EA4fN-vwGs7&index=1)

#### JWT

-   [Crash course](https://www.youtube.com/watch?v=T0k-3Ze4NLo)
-   [Session vs Token Authentication in 100 Seconds](https://www.youtube.com/watch?v=UBUNrFtufWo)
-   [What Is JWT and Why Should You Use JWT?](https://www.youtube.com/watch?v=7Q17ubqLfaM)
-   [Why I haven't been using JWT tokens for Authentication](https://www.youtube.com/watch?v=dgg1dvs0Bn4) (Ben Awad)
-   [A JWT demo using the `flask-jwt-extended` package.](https://github.com/HarshKapadia2/flask-jwt-cors)
-   JWTs are for authorization and not authentication. (Username and password provide authentication.)
-   Refresh Tokens
    -   [What Are Refresh Tokens and How to Use Them Securely](https://auth0.com/blog/refresh-tokens-what-are-they-and-when-to-use-them)
    -   [How to Handle Refresh Tokens](https://security.stackexchange.com/questions/194774/how-to-handle-refresh-tokens)
    -   Refresh Tokens are tokens with a longer expiry duration than Access Tokens.
    -   If the Refresh Token is expired, then the user has to manually log in.
    -   They are used to
        -   Reduce the number of explicit logins that the client has to make.
        -   Reduce the load of querying/storing authorization details in the database every time a user needs access.
    -   There is a tradeoff between security and database storage/querying.
        -   If better security is required, the Refresh Tokens need to be stored in the database and marked as expired once a new one is issued. This increases database querying, but improves security and still maintains the convenience of less number of logins for the client.
        -   Another way to provide security would be to issue a new Refresh Token every time a new Access Token is issued, but this increases the number of Refresh Tokens that have to be stored in the database (to expire them later as discussed in the previous point). So database storage is increased, but this improves security and still maintains the convenience of less number of logins for the client.
            -   Storing Refresh Tokens is still better than storing a Session Token, because a Session Token is checked every time an API call is made. Now if there are too many Refresh Tokens, database storage increases and querying takes time, but that is a trade off that has to be decided upon.
            -   A hybrid approach can be taken, where a Session Token (as a short-lived JWT) can be issued and stored in the database along with a Refresh Token and so the Session Token does not have to be checked with the DB on every request. A new Session Token can be issued whenever it expires, using the Refresh Token.

### Databases

-   [A database of Databases](https://dbdb.io)
-   [Database Engineering by Hussein Nasser](https://www.youtube.com/watch?v=pomxJOFVcQs&list=PLQnljOFTspQXjD0HOzN7P2tgzu7scWpl2)
-   [CMU 445/645 Introduction to Database Systems](https://www.youtube.com/watch?v=oeYBdghaIjc&list=PLSE8ODhjZXjbohkNBWQs_otTrBTrjyohi&index=2)
-   [CMU 721 Advanced Database Systems](https://www.youtube.com/watch?v=SdW5RKUboKc&list=PLSE8ODhjZXjasmrEd2_Yi1deeE360zv5O&index=2)

#### SQL

-   Relational DBs
-   [MySQL crash course](https://www.youtube.com/watch?v=HXV3zeQKqGY)
-   MySQL [fragmentation](https://www.youtube.com/watch?v=sICmP7bJrvo) and [partitioning](https://www.youtube.com/watch?v=iUjoPB27-iA)
-   Eg: MySQL, PostgreSQL, MariaDB, SQLite, etc...

#### NoSQL

-   Non-relational DBs
-   [NoSQL DB introduction](https://www.youtube.com/watch?v=uD3p_rZPBUQ)
-   [MongoDB crash course](https://www.youtube.com/watch?v=-56x56UppqQ)
-   Cloud Firestore and Realtime DB (Covered in the [Firebase section](#firebase) below.)

### JS Back End

#### Node.js

-   [Crash course](https://www.youtube.com/watch?v=fBNz5xF-Kx4)
-   [The Art of Node](https://github.com/maxogden/art-of-node)
-   [Middleware](https://thenextbigwriter.tech/middlewares-in-express-js-ck8d87su900w3xes1ny80u28q)
-   ['Callbacks' in JS section above](https://dev.harshkapadia.me/resources.html#js:~:text=Callbacks)
-   Modules
    -   Refer to the 'Modules' point in the [JS section](#js) above.
    -   [How to Export and Require Modules in Node.js](https://www.youtube.com/watch?v=pP4kjXykbio)
-   [Creating and publishing a NPM package](https://iq.opengenus.org/creating-node-modules)

#### Express.js

-   [Crash course](https://www.youtube.com/watch?v=L72fhGm1tfE)
-   [Body parser](https://stackoverflow.com/a/43626891/11958552)

#### JS REST API

-   [Node.js (Express.js) and MongoDB REST API](https://www.youtube.com/watch?v=vjf774RKrLc)

### Python Back End

#### Prerequisite

-   [Python basics](https://www.youtube.com/watch?v=JJmcL1N2KQs)

#### Flask

-   [Crash course](https://www.youtube.com/watch?v=Z1RJmh_OqeA)
-   [_Tech With Tim_'s series](https://www.youtube.com/watch?v=mqhxxeeTbu0&list=PLzMcBGfZo4-n4vJJybUVV3Un_NFS5EOgX)
-   [Documentation](https://flask.palletsprojects.com/en/1.1.x)
-   [How to enable CORS in Flask?](https://stackoverflow.com/a/52875875/11958552)

### PHP

#### Prerequisites

-   [PHP basics](https://www.youtube.com/watch?v=oJbfyzaA2QA&list=PLillGF-Rfqbap2IB6ZS4BBBcYPagAjpjn&index=1)
-   [PHP Data Objects](https://www.youtube.com/watch?v=kEW6f7Pilc4) (PDO)

#### PHP REST API

-   [Crash course](https://www.youtube.com/watch?v=OEWXbpUMODk&list=PLillGF-RfqbZ3_Xr8do7Q2R752xYrDRAo&index=1)

### Front End JS Frameworks/Libraries

#### Prerequisites

##### Misc

-   [General front end framework advice](https://threadreaderapp.com/thread/1394898131926458371.html)
-   [How To Handle Large Amounts of Data in React-based Applications](https://betterprogramming.pub/how-to-handle-large-amounts-of-data-in-react-based-applications-8d97dd80a9f1)

##### JavaScript

-   [JavaScript requirements](https://www.youtube.com/watch?v=JR9wsVYp8RQ)
-   [JS section](#js)
-   [Async JS](#async-js)
-   [AJAX and its libraries](#ajax-and-its-libraries)

##### State

-   ['State' in 30 seconds](https://twitter.com/technoidic_ash/status/1305638862631260160)
-   [What is 'state'?](https://egghead.io/articles/what-is-state-why-do-i-need-to-manage-it)

##### XML

-   [Very basics of XML](https://www.youtube.com/watch?v=KeLiQXqVgMI)

#### React.js

-   [React in 100 Seconds](https://www.youtube.com/watch?v=Tn6-PIqc4UM)
-   [Crash course](https://www.youtube.com/watch?v=w7ejDZ8SWv8)
-   Hooks
    -   [`useState` array pass by reference gotcha](https://stackoverflow.com/a/67354136/11958552)
    -   [10 React Hooks Explained](https://www.youtube.com/watch?v=TNhaISOUy6Q)
    -   [Hooks API reference](https://reactjs.org/docs/hooks-reference.html)
    -   [The `useRef` hook](https://www.youtube.com/watch?v=t2ypzz6gJm0)
    -   [Be Aware of Stale Closures when Using React Hooks](https://dmitripavlutin.com/react-hooks-stale-closures)
-   Memoization
    -   [Understanding re-rendering and memoization in React](https://engineering.udacity.com/understanding-re-rendering-and-memoization-in-react-13e8c024c2b4)
    -   [Use `React.memo()` wisely](https://dmitripavlutin.com/use-react-memo-wisely)
-   [30-Days-Of-React](https://github.com/Asabeneh/30-Days-Of-React)
-   Internals
    -   [How a React App Works Under the Hood](https://www.youtube.com/watch?v=TjnyFNxQ67Y) (High level stuff in 14 mins.)
    -   [Is React a Library or a Framework? Here's Why it Matters](https://www.freecodecamp.org/news/is-react-a-library-or-a-framework)
    -   [Why does React.js need keys?](https://twitter.com/dan_abramov/status/1415279090446204929)
    -   [Calling functional components as functions](https://dev.to/igor_bykov/react-calling-functional-components-as-functions-1d3l)
    -   [Deconstructing React](https://www.youtube.com/watch?v=f2mMOiCSj5c)
    -   [Building a Custom React Renderer](https://www.youtube.com/watch?v=CGpMlWVcHok)
    -   [Destructuring React](https://www.youtube.com/watch?v=zmO51Dn5DPI)
    -   [Understanding React's UI Rendering Process](https://www.youtube.com/watch?v=i793Qm6kv3U)

### Misc #2

#### Web Performance

-   [Site-Speed Topography](https://csswizardry.com/2020/11/site-speed-topography)
-   [Lighthouse](https://developers.google.com/web/tools/lighthouse) (available in Chrome and Edge DevTools and as an add-on in Firefox)
-   [web.dev](https://web.dev)

#### SEO

##### `robots.txt`

-   [robotstxt.org](https://www.robotstxt.org)
-   [Google Site Verification](https://developers.google.com/search/docs/advanced/robots/submit-updated-robots-txt)
-   Example
    -   [google.com/robots.txt](https://www.google.com/robots.txt)
    -   [catchup.ourtech.community/robots.txt](https://catchup.ourtech.community/robots.txt)
    -   [harshkapadia2.github.io/git_basics/robots.txt](https://harshkapadia2.github.io/git_basics/robots.txt)

#### Firebase

-   BaaS
-   [Documentation](https://firebase.google.com/docs) (More than sufficient. Also, do watch the videos linked in the docs.)

#### DevOps

##### Git

-   Covered in the [Git and GitHub section](#git-and-github) above.

##### Shell Scripting

-   [Shell and Shell scripting](https://harshkapadia2.github.io/cli)
-   [Advanced Bash-Scripting Guide](https://tldp.org/LDP/abs/html/index.html)
-   [Dotfiles](https://github.com/HarshKapadia2/dotfiles)

##### Build Systems

-   Make
    -   [Make basics](https://www.youtube.com/watch?v=a8mPKBxQ9No)
    -   [Makefiles: 95% of what you need to know](https://www.youtube.com/watch?v=DtGrdB8wQ_8)
    -   [Sample Makefile from a project](https://github.com/HarshKapadia2/parse-elf/blob/main/Makefile)
    -   [What do the makefile symbols `$@` and `$<` mean?](https://stackoverflow.com/questions/3220277/what-do-the-makefile-symbols-and-mean)
    -   [What's the difference between `:=` and `=` in Makefile?](https://stackoverflow.com/questions/4879592/whats-the-difference-between-and-in-makefile)
    -   [What is the purpose of `.PHONY` in a Makefile?](https://stackoverflow.com/questions/2145590/what-is-the-purpose-of-phony-in-a-makefile)

##### Deployment/Hosting

-   For web sites only
    -   [GitHub Pages](https://pages.github.com)
    -   [Netlify](https://www.netlify.com)
-   For web sites and web apps
    -   [Heroku](https://heroku.com)
    -   [Vercel](https://vercel.com)
    -   [Deta](https://deta.sh)
    -   [Python Anywhere](https://www.pythonanywhere.com) (Only for Python web sites and web apps.)
    -   [Firebase Hosting](https://firebase.google.com/docs/hosting) (Dynamic: Only Node.js supported through Cloud Functions)
    -   [Digital Ocean](https://www.digitalocean.com/solutions/website-hosting)
-   Domain names
    -   [.js.org](https://js.org) (For users, organizations, projects, etc.) (free)
    -   [.is-a.dev](https://www.is-a.dev) (For portfolio web sites.) (free)
    -   [.ml](http://www.dot.ml/en/index.html) (free)

##### YAML

-   [Crash course](https://www.youtube.com/watch?v=1uFVr15xDGg)
-   [Different string quotes and their meanings](https://stackoverflow.com/a/69850618/11958552)

##### CI/CD

-   GitHub Actions
-   GitLab Actions
-   Jenkins
-   TravisCI
-   Circle CI

##### Docker

-   [Getting Started](https://www.youtube.com/watch?v=Kyx2PsuwomE) (part one of two)
-   [Docker Compose](https://www.youtube.com/watch?v=hP77Rua1E0c) (part two of two)
-   [My Docker repo](https://harshkapadia2.github.io/docker)

##### Cloud

-   [My notes and resources](https://harshkapadia2.github.io/cloud)

#### The Missing Semester of CS Education

-   [The Missing Semester of Your CS Education](https://missing.csail.mit.edu)

#### Character Sets and Encoding

##### Unicode

-   [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets (No Excuses!)](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses)
-   [What are Unicode, UTF-8, and UTF-16?](https://stackoverflow.com/questions/2241348/what-are-unicode-utf-8-and-utf-16)

##### New Lines/Line Endings

-   Also called 'Newline' and 'line break'.
-   Types
    -   Carriage Return
        -   Unicode and ASCII: `CR`
        -   Programming languages: `\r`
        -   Hexadecimal: `0D`, `0x0D`
        -   [More details](https://www.asciihex.com/character/control/13/0x0D/cr-carriage-return)
    -   Line Feed
        -   Unicode and ASCII: `LF`
        -   Programming languages: `\n`
        -   Hexadecimal: `0A`, `0x0A`
        -   [More details](https://www.asciihex.com/character/control/10/0x0A/lf-line-feed)
    -   Carriage Return and Line Feed
        -   Unicode and ASCII: `CRLF`, `CR+LF`
        -   Programming languages: `\r\n`
        -   Hexadecimal: `0D 0A`, `0x0D 0x0A`
    -   End of Line
        -   Unicode: `EOL`
    -   Next Line
        -   Unicode: `NEL`
    -   New Line
        -   EBCDIC: `NL`
-   > ...different system uses different line break. Carriage Return is used on old Macintosh operating systems. UNIX based systems including Linux and Mac OS X use Line Feed, while most of non-Unix operating systems use End of Line (`\r\n`). Therefore, good code should handle all kind of line breaks. ([Source](https://www.woolha.com/tutorials/dart-split-string-by-newline-using-linesplitter#:~:text=Sometimes%20we%20may,CR%20%2B%20LF.))
-   [What's a Carriage and Who's Feeding it Lines? CRLF](https://www.youtube.com/watch?v=TtiBhktB4Qg)
-   [Newline](https://en.wikipedia.org/wiki/Newline)
-   [`\r\n` vs `\n\r` what is the difference in their behavior?](https://stackoverflow.com/questions/43607389/r-n-vs-n-r-what-is-the-difference-in-their-behavior)
-   [Why Windows uses `\r\n` newlines instead of `\n`](https://dev.to/pieter/why-windows-uses-rn-newlines-instead-of-n-126l)
-   [What Are Teletypes, and Why Were They Used with Computers?](https://www.howtogeek.com/727213/what-are-teletypes-and-why-were-they-used-with-computers)
    -   [Video with `CR` and `LF` keys on a Teletype Model 33 ASR!](https://youtu.be/ObgXrIYKQjc)

##### Misc Characters

-   [Deleting a single character involves three characters (`\b \b`).](https://stackoverflow.com/a/24404619/11958552)

### C

-   [C in 100 Seconds](https://www.youtube.com/watch?v=U3aXWizDbQ4)
-   [You Can Write Your First C Program In 10 Minutes](https://www.youtube.com/watch?v=BuiX6vsiEfo)
-   [The Descent to C](https://www.chiark.greenend.org.uk/~sgtatham/cdescent)
-   [Is C programming language low level or high level?](https://softwareengineering.stackexchange.com/questions/303117/is-c-programming-language-low-level-or-high-level)
-   [C introduction notes](./files/c/c-intro-notes-manjrekar.pdf)
-   [`int main()` vs `void main()` vs `int main(void)` in C](https://www.codesdope.com/blog/article/int-main-vs-void-main-vs-int-mainvoid-in-c-c)
-   [C warning: 'Function declaration isn't a prototype'](https://stackoverflow.com/a/20843829/11958552)
    -   Why `int foo() { /* ... */ }` gives a warning and `int foo(void) { /* ... */}` resolves it.
-   Header files
    -   [Header files](https://www.tutorialspoint.com/cprogramming/c_header_files.htm)
    -   [why do header files even exist?](https://www.youtube.com/watch?v=tOQZlD-0Scc)
    -   [Should I use `#include` in headers?](https://stackoverflow.com/questions/1804486/should-i-use-include-in-headers)
    -   Header file locations in Linux
        -   [Where is the `stdio.h` file located in Linux while using the gcc.7.2 compiler?](https://stackoverflow.com/questions/46043225/where-is-the-stdio-h-file-located-in-linux-while-using-the-gcc-7-2-compiler)
        -   [Where is `stdbool.h`?](https://stackoverflow.com/questions/1656874/where-is-stdbool-h)
-   Include Guards
    -   [Why are `#ifndef` and `#define` used in C++ header files?](https://stackoverflow.com/questions/1653958/why-are-ifndef-and-define-used-in-c-header-files)
    -   [What exactly do C include guards do?](https://stackoverflow.com/questions/27810115/what-exactly-do-c-include-guards-do)
    -   [What is the conventional way of writing include guards?](https://stackoverflow.com/questions/17307540/what-is-the-conventional-way-of-writing-include-guards)
-   Pointers
    -   [you will never ask about pointers again after watching this video](https://www.youtube.com/watch?v=2ybLD6_2gKM)
    -   [What is `char **` in C?](https://stackoverflow.com/questions/13353807/what-is-char-in-c)
    -   [why do void pointers even exist?](https://www.youtube.com/watch?v=t7CUti_7d7c)
    -   [Pointer arithmetic cannot be performed on void pointers](https://stackoverflow.com/questions/6449935/increment-void-pointer-by-one-byte-by-two)
    -   [How does incrementing memory address affects pointer](https://stackoverflow.com/questions/56608384/how-does-incrementing-memory-address-affects-pointer) (excellent example)
-   Characters and strings
    -   [Char Comparison in C](https://stackoverflow.com/questions/22736348/char-comparison-in-c)
    -   [Why do strings in C need to be null terminated?](https://stackoverflow.com/questions/2221304/why-do-strings-in-c-need-to-be-null-terminated)
    -   [Why/when to include terminating `\0` character for C Strings?](https://stackoverflow.com/questions/46261028/why-when-to-include-terminating-0-character-for-c-strings)
    -   [Single quotes vs. double quotes in C or C++](https://stackoverflow.com/questions/3683602/single-quotes-vs-double-quotes-in-c-or-c)
-   Compilers
    -   [GCC vs Clang](https://stackoverflow.com/questions/24836183/what-is-the-difference-between-clang-and-llvm-and-gcc-g)
    -   [Why is C Compiler So Smart?](https://www.youtube.com/watch?v=juWM6saNCZk)
    -   [what's the Secret Sauce that makes code work?](https://www.youtube.com/watch?v=2y1IgW2T8bo)
    -   [Writing a compiler with LLVM](https://www.youtube.com/watch?v=vrRXIQDCCEk)
-   `libc` and `libm`
    -   [what is `libc`?](https://stackoverflow.com/questions/20396471/what-is-libc-what-are-the-functions-it-includes-how-can-we-get-the-source-code)
        -   [`libc` vs `glibc`](https://stackoverflow.com/a/54053221/11958552)
    -   [Why do you need an explicit `-lm` compiler option?](https://stackoverflow.com/questions/10371647/why-do-you-need-an-explicit-lm-compiler-option)
    -   [Why do you have to link the math library in C?](https://stackoverflow.com/questions/1033898/why-do-you-have-to-link-the-math-library-in-c)
-   [What is the difference between C, C99, ANSI C and GNU C?](https://stackoverflow.com/questions/17206568/what-is-the-difference-between-c-c99-ansi-c-and-gnu-c)
-   Data types and variables
    -   [What is the use of typedef?](https://stackoverflow.com/questions/2566027/what-is-the-use-of-typedef)
    -   `_t` data types
        -   [All Those `_t` Data Types](https://c-for-dummies.com/blog/?p=5059)
        -   [What Is The `_t` In `Uint8_t`](https://techexplorations.com/guides/arduino/programming/_t-in-uint8_t/#:~:text=So%2C%20in%20the%20C99%20standard,platform%20the%20program%20runs%20on.)
        -   [What does a type followed by `_t` (underscore-t) represent?](https://stackoverflow.com/questions/231760/what-does-a-type-followed-by-t-underscore-t-represent)
    -   Using the `L` suffix for `long` data types
        -   [what is the reason for explicitly declaring `L` or `UL` for `long` values](https://stackoverflow.com/a/13139304/11958552)
        -   [What's the point of adding an "l" at the end of an int or long int when you define it?](https://www.reddit.com/r/C_Programming/comments/kcvhhs/comment/gftgaa7)
            -   [Overflow demo](https://gist.github.com/HarshKapadia2/eaf501d241b2798d5672ed102b780b82)
        -   [Using the letter L in long variable declaration](https://stackoverflow.com/questions/17738232/using-the-letter-l-in-long-variable-declaration)
        -   [From Java: Integer Literals](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html#:~:text=Values%20of%20the%20integral%20types%20byte%2C%20short%2C%20int%2C%20and%20long%20can%20be%20created%20from%20int%20literals.%20Values%20of%20type%20long%20that%20exceed%20the%20range%20of%20int%20can%20be%20created%20from%20long%20literals.)
    -   [What are the rules about using an underscore in a C identifier?](https://stackoverflow.com/questions/69084726/what-are-the-rules-about-using-an-underscore-in-a-c-identifier)
-   [What is POSIX? Why Does it Matter to Linux/UNIX Users?](https://itsfoss.com/posix)
-   Buffer Overflow Attack
    -   [why do hackers love strings?](https://www.youtube.com/watch?v=fjMrDDj47E8)
    -   [how do hackers exploit buffers that are too small?](https://www.youtube.com/watch?v=qpyRz5lkRjE)
    -   [Does buffer-overflow causes segfault only when an important pointer is overwritten?](https://stackoverflow.com/questions/45740014/does-buffer-overflow-causes-segfault-only-when-an-important-pointer-is-overwritt)
    -   [Buffer Overflow Attack](https://owasp.org/www-community/attacks/Buffer_overflow_attack)
    -   [`fgets()` and `gets_s()`](https://www.cisa.gov/uscert/bsi/articles/knowledge/coding-practices/fgets-and-gets_s)
    -   [Common vulnerabilities guide for C programmers](https://security.web.cern.ch/recommendations/en/codetools/c.shtml)
    -   [Heartbleed bug](https://networking.harshkapadia.me/tls#heartbleed-bug)
    -   [how can memory safe code STOP HACKERS?](https://www.youtube.com/watch?v=lxUYZVX_FjQ)
-   [everything is open source if you can reverse engineer](https://www.youtube.com/watch?v=gh2RXE9BIN8)
-   Arrays
    -   [Passing arrays as `int arr[2]`, `int *arr[2]`, `int (*arr)[2]`, etc.](https://stackoverflow.com/a/51527502/11958552)
        -   [Tool to translate C expressions like `int *arr[2]` vs `int (*arr)[2]` into English](https://cdecl.org)
-   Memory layout
    -   [Memory Layout of C Programs](https://www.geeksforgeeks.org/memory-layout-of-c-program)
    -   [The Origins of Process Memory - Exploring the Use of Various Memory Allocators in Linux C](https://www.youtube.com/watch?v=c7xf5dvUb_Q)
    -   [demystifying the secret structure you've been using all along (stack)](https://www.youtube.com/watch?v=CRTR5ljBjPM)
    -   [Smashing the Stack for Fun and Profit](https://networking.harshkapadia.me/files/tls/smashing-the-stack-for-fun-and-profit.pdf) ([UCB hosted](https://inst.eecs.berkeley.edu/~cs161/fa08/papers/stack_smashing.pdf))
    -   [do you understand how "return" works?](https://www.youtube.com/watch?v=e46wHUjNDjE)
-   Bitwise operations
    -   [Basics of Bit Manipulation](https://www.hackerearth.com/practice/basic-programming/bit-manipulation/basics-of-bit-manipulation/tutorial)
    -   [What does tilde(`~`) operator do?](https://stackoverflow.com/questions/3952122/what-does-tilde-operator-do)
    -   [C/C++ check if one bit is set in, i.e. int variable](https://stackoverflow.com/questions/523724/c-c-check-if-one-bit-is-set-in-i-e-int-variable)
    -   [Modify a bit at a given position](https://www.geeksforgeeks.org/modify-bit-given-position)
    -   [How do I change bits in specific positions to specific values?](https://stackoverflow.com/questions/53478679/c-how-do-i-change-bits-in-specific-positions-to-specific-values)
    -   [Set, Clear and Toggle a given bit of a number in C](https://www.geeksforgeeks.org/set-clear-and-toggle-a-given-bit-of-a-number-in-c)
-   Structures (`struct`s)
    -   [Difference between `->` and `.` in a struct?](https://stackoverflow.com/questions/5998599/difference-between-and-in-a-struct)
    -   Structure Packing
        -   [The forgotten art of Struct Packing in C/C++.](https://www.joshcaratelli.com/blog/struct-packing)
        -   [What is the meaning of `__attribute__((packed, aligned(4)))`?](https://stackoverflow.com/questions/11770451/what-is-the-meaning-of-attribute-packed-aligned4)
-   [How can I check my byte flag, verifying that a specific bit is at 1 or 0?](https://stackoverflow.com/questions/127027/how-can-i-check-my-byte-flag-verifying-that-a-specific-bit-is-at-1-or-0)
-   Docs
    -   [Docs](https://devdocs.io/c)
    -   [Docs](https://www.mkssoftware.com/docs/man3/memcpy.3.asp) (Modify links)
-   [Phone Book project](https://github.com/HarshKapadia2/phone-book)

### Linux

-   [linux.harshkapadia.me](https://linux.harshkapadia.me)
