# My Web Dev Resources

- The crash course in each section is the bare minimum that should be done.
- The resources have been aligned in a logical manner that should be followed.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Front End](#front-end)
   - [HTML](#html)
   - [CSS](#css)
   - [JS](#js)
- [Misc #1](#misc-1)
   - [Git and GitHub](#git-and-github)
   - [Web Design](#web-design)
   - [Browser DevTools](#browser-devtools)
   - [PWA (+ Service Worker API)](#pwas--service-worker-api)
   - [Networking](#networking)
   - [RegEx](#regex)
   - [SVG](#svg)
   - [Intersection Observer API](#intersection-observer-api)
   - [InedxedDB](#indexeddb)
   - [Web Components API](#web-components-api)
   - [Misc Libraries](#misc-libraries)
   - [TWA](#twa)
- [General Back End Prerequisites](#general-back-end-prerequisites)
   - [HTTP](#http)
   - [JSON](#json)
   - [APIs](#apis)
   - [Async JS](#async-js)
   - [Caching](#caching)
- [Databases](#databases)
   - [SQL](#sql)
   - [NoSQL](#nosql)
- [JS Back End](#js-back-end)
   - [Node.js](#nodejs)
   - [Express.js](#expressjs)
   - [JS REST API](#js-rest-api)
- [Python Back End](#python-back-end)
   - [Prerequisite](#prerequisite-1)
   - [Flask](#flask)
- [PHP](#php)
   - [Prerequisites](#prerequisites-1)
   - [PHP REST API](#php-rest-api)
- [Front End JS Frameworks/Libraries](#front-end-js-frameworkslibraries)
   - [Prerequisite](#prerequisite)
      - [State](#state)
   - [React.js](#reactjs)
- [Misc #2](#misc-2)
   - [Web Performance](#web-performance)
   - [SEO](#seo)
      - [`robots.txt`](#robotstxt)
   - [Firebase](#firebase)
   - [DevOps](#devops)
      - [Git](#git)
      - [Deployment/Hosting](#deploymenthosting)
      - [CI/CD](#cicd)
      - [Docker](#docker)

## My resources

### Prerequisites

- Browser (Chrome, Edge, Brave or Firefox are preferred.)
- [Set up VS Code](https://www.youtube.com/watch?v=fnPhJHN0jTE)

### Front End

#### HTML

- [Crash course](https://www.youtube.com/watch?v=UB1O30fR-EE)
- [HEAD](https://github.com/joshbuchea/HEAD) - A list of a lot of things that *could* go in the head of a HTML document.
- The Open Graph Protocol (OGP)
   - [Official web site](https://ogp.me/)
   - Articles
      - https://www.freecodecamp.org/news/what-is-open-graph-and-how-can-i-use-it-for-my-website/#what-is-open-graph
      - https://indieweb.org/The-Open-Graph-protocol
   - [For Twitter cards](https://developer.twitter.com/en/docs/twitter-for-websites/cards/overview/abouts-cards)
   - NOTE:
      - For the image in the card, SVGs are not supported. Use a PNG or JPG image.
      - The image value has to be a URL and not a static file in the project.
      - The image size should be less than 300 kb.
- [Lazy loading attribute for images](https://css-tricks.com/native-lazy-loading/)
- [Maximally optimizing image loading for the web in 2021](https://www.industrialempathy.com/posts/image-optimizations/)
- [`prefetch`, `preload` and `preconnect` resource hints](https://www.keycdn.com/blog/resource-hints)
- [`async` and `defer` scripts](https://javascript.info/script-async-defer)
- [Validator](https://validator.w3.org/) to check correctness of HTML.

#### CSS

- [Crash course](https://www.youtube.com/watch?v=yfoY53QXEnI)
- [Margin vs padding](https://www.differencebetween.com/difference-between-margin-and-vs-padding/)
- [`box-sizing` property](https://www.w3schools.com/css/css3_box-sizing.asp)
- [Website layout](https://www.w3schools.com/css/css_website_layout.asp)
- Selectors [PDF](https://webdevsimplified.com/specificity-cheat-sheet.html) or [article](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors)
- [Pseudo-elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)
- Specificity
   - Order: `!important` > `inline` > `id selectors` > `class selectors + attribute selectors + pseudo-classes` > `element selectors (tags) + pseudo-elements`
   - The number of ids, classes and tags for a particular element matter in the specifity as well. More of each implies an increase in specificity.
   - `!important` trumps all, irrespective of the number of ids, classes and tags. Should be avoided as far as possible.
   - Inline CSS trumps all but `!important`, irrespective of the number of ids, classes and tags. Should be avoided as far as possible.
   - [Specificity illustrated](https://specifishity.com/) (Format: `(<no_of_ids>, <no_of_classes+attribute_selectors+pseudo-classes>, <no_of_tags+pseudo-elements>)`)
   - [`id` vs `class` specificity](https://css-tricks.com/the-difference-between-id-and-class/#comment-27579)
- [`display` property](https://alligator.io/css/display-inline-vs-inline-block/)
- [`position` property](https://www.w3schools.com/Css/css_positioning.asp)
- CSS Flexbox
   - [Livestream by Madhav Bahl](https://www.youtube.com/watch?v=LKmsQCUb0oE)
   - https://github.com/MadhavBahlMD/flex
   - [Visualizer](https://lokeshdhakar.com/projects/flexitem/)
   - [Crash course by Brad Traversy](https://www.youtube.com/watch?v=JJSoEo8JSnc) (Haven't watched this.)
- CSS Grid
   - [Crash course](https://www.youtube.com/watch?v=EFafSYg-PkI)
   - [Browser extension *Gridman* for Grid lines](https://chrome.google.com/webstore/detail/gridman-css-grid-inspecto/cmplbmppmfboedgkkelpkfgaakabpicn) (Incase the DevTools don't support CSS Grid.)
- [Media queries](https://www.w3schools.com/css/css3_mediaqueries.asp)
- Units
   - [`px`, `%`, `vh`, `vw`, `em` and `rem` (Part 1 of 2)](https://www.youtube.com/watch?v=gSL0hUPBgQA) (Hindi)
   - [`rem` vs `em` (Part 2 of 2)](https://www.youtube.com/watch?v=W862VHnZ6Sw) (Hindi)
   - [W3Schools](https://www.w3schools.com/CSSref/css_units.asp)
- [`clamp()` function](https://blog.webdevsimplified.com/2020-11/css-clamp/) (view [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/clamp()) for more)
- [2D Transforms](https://www.w3schools.com/Css/css3_2dtransforms.asp)
- [Animations](https://www.w3schools.com/css/css3_animations.asp) ([High performance aimations](https://www.html5rocks.com/en/tutorials/speed/high-performance-animations/))
- [Transitions](https://www.w3schools.com/css/css3_transitions.asp)
- [Responsive web site tutorial](https://www.youtube.com/watch?v=ZeDP-rzOnAA&list=WL&index=155&t=0s)
- Check responsiveness on various devices
   - In the browser DevTools (best option)
   - On https://springload.responsinator.com
- [Bootstrap crash course](https://www.youtube.com/watch?v=5GcQtLDGXy8)
- [Sub-string matching selectors](https://blog.teamtreehouse.com/css3-substring-matching-attribute-selectors) (Eg: `[class*="col-"] { width: 100%; }`)
- [Scrollbar styling](https://css-tricks.com/almanac/properties/s/scrollbar/)
- CSS basics
   - [Redo Your CSS](https://learn.redoyourcss.com/) ([Main site](https://www.redoyourcss.com/))
- [Some design resources](https://github.com/bradtraversy/design-resources-for-developers)

#### JS

- [Crash course](https://www.youtube.com/watch?v=hdI2bqOjy3c)
- [`var` vs `let` vs `const`](https://blog.webdevsimplified.com/2020-01/var-vs-let-vs-const/)
- [Reference vs value](https://blog.webdevsimplified.com/2021-03/js-reference-vs-value/)
- [Document Object Model](https://medium.com/@EdidiongAsikpo/getting-started-with-the-dom-d27907f17be0) (DOM)
- [`window` vs `document`](https://stackoverflow.com/questions/9895202/what-is-the-difference-between-window-screen-and-document-in-javascript)
- [`element.classList`](https://blog.webdevsimplified.com/2020-11/class-list/)
- [Data attributes](https://blog.webdevsimplified.com/2020-10/javascript-data-attributes/) (`element.dataset` property - view [MDN](https://developer.mozilla.org/en-US/docs/Web/API/HTMLOrForeignElement/dataset) for more.)
- [`localStorage` vs `sessionStorage`](https://blog.webdevsimplified.com/2020-08/cookies-localStorage-sessionStorage/) (view [javascript.info](https://javascript.info/localstorage) for more differences)
- [Event reference](https://developer.mozilla.org/en-US/docs/Web/Events) (`load`, `click`, `change`, `submit`, etc)
- [Rounding off](https://medium.com/swlh/how-to-round-to-a-certain-number-of-decimal-places-in-javascript-ed74c471c1b8)
- [Some cases of file handling](https://developer.mozilla.org/en-US/docs/Web/API/File/Using_files_from_web_applications)
- [Responsive nav bar tutorial](https://www.youtube.com/watch?v=gXkqy0b4M5g)
- [HTML Drag and Drop API](https://www.youtube.com/watch?v=Wtrin7C4b7w)
- JS internals
   - [Namaste :pray: JavaScript](https://www.youtube.com/watch?v=pN6jk0uUrD8&list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP&index=1)
   - [Event loop](https://www.youtube.com/watch?v=8aGhZQkoFbQ&feature=youtu.be)
   - [Scheduling in JS and browsers](https://www.youtube.com/watch?v=z96oKTUSQjE) | [Tweet](https://twitter.com/reactify_in/status/1309843620179054592)
   - [JS modules and build tools](https://www.youtube.com/watch?v=U4ja6HeBm6s&feature=youtu.be)

### Misc #1

#### Git and GitHub

- Sessions by me
   - [Crash course](https://www.youtube.com/watch?v=HF12-91iazM)
   - [Open Source, Hacktoberfest and Pull Requests](https://www.youtube.com/watch?v=uJdFNksgKJA)
- [git_basics web site](https://harshkapadia2.github.io/git_basics/)
- [Crash course by Brad Traversy](https://www.youtube.com/watch?v=SWYqp7iY_Tc)

#### Web Design

- [Typography 101](https://www.youtube.com/watch?v=HnpsOtIcfbo)
- [Color theory 101](https://www.youtube.com/watch?v=e_kdWMmD3z0)
- [Layout design](https://www.youtube.com/watch?v=S4viQ_Ejptc)
- [Top Design Resources and Apps](https://www.youtube.com/watch?v=GUOgv4PcHIQ)

#### Browser DevTools

- [Guide to Chrome's performance profiler](https://www.youtube.com/watch?v=KWM5wxlDuis)
- [Chrome DevTools documentation](https://developers.google.com/web/tools/chrome-devtools/)
- [Crash course (Brad Traversy)](https://www.youtube.com/watch?v=x4q86IjJFag)
- [Crash course (FreeCodeCamp)](https://www.youtube.com/watch?v=gTVpBbFWry8)

> NOTE: The DevTools are similar in almost all browsers, so the above resources are fine.

- [Check the support of a front end web technology on desktop and mobile web browsers.](https://caniuse.com/ciu/about)

#### PWAs (+ Service Worker API)

- Prerequisite: [Caching](#caching)
- [Crash course](https://www.youtube.com/watch?v=ksXwaWHCW6k) (Intro to Service Workers and Caching)
- [Progressive Web Apps in 100 seconds](https://www.youtube.com/watch?v=sFsRylCQblw)
- [Extra PWA features](https://www.youtube.com/watch?v=ppwagkhrZJs)
- [Offline-first PWAs](https://www.youtube.com/watch?v=cmGr0RszHc8) (A good overview)
- [Demistifying Web Workers and Service Workers](https://www.youtube.com/watch?v=OgLemdR65pE) (Some content of the talk is outdated.)
- [The Modern PWA Cheat Sheet](https://www.youtube.com/watch?v=cybhV88KLfI)
- [Service Workers MDN](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API/Using_Service_Workers)
- [The offline cookbook](https://jakearchibald.com/2014/offline-cookbook/) (Caching and network strategies.)
- [Application Cache is a Douchebag](https://alistapart.com/article/application-cache-is-a-douchebag/) (Caching gotchas.)
- [Creating a PWA with JS](https://dev.to/devpato/how-to-create-a-pwa-with-javascript-4jlh)
- [Important `manifest.json` options](https://web.dev/add-manifest/)
- [Icon generator](https://www.pwabuilder.com/imageGenerator)
- [Customizing the install experience](https://web.dev/customize-install/)
- Use LightHouse for debugging and checking.
- Service Workers are not just used for PWAs. They are used just for caching as well.
- Caching is an important concept for PWAs. Please go through [Caching section](#caching) below.
- In a PWA, static files need to be manually cached during the install event, because the Service Worker is not active by then to cache the initial response. Also, every file has to be listed individually, as directories are not recognized.
- Once a PWA is installed, the icons cannot be changed. The change is reflected on re-installing the PWA. (I think TWAs can change their icons. Check below for more info on TWAs.)
- An offline PWA does not have access to localStorage. (The service worker does not allow it.) IndexedDB can be used in place. (IndexedDB crash course below.)
- [Some problems with Service Workers](https://www.youtube.com/watch?v=JJSloXLTyNg)

#### Networking

- [My notes](https://github.com/HarshKapadia2/networking)

#### RegEx

- [Crash course](https://www.youtube.com/watch?v=rhzKDrUiJVk)
- [RegEx summarised in 100 seconds](https://www.youtube.com/watch?v=sXQxhojSdZM)

#### SVG

- [Get started](https://webdesign.tutsplus.com/tutorials/how-to-hand-code-svg--cms-30368)

#### Intersection Observer API

- [MDN](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API)
- [Scroll to top button](https://css-tricks.com/how-to-make-an-unobtrusive-scroll-to-top-button/#option-3-intersection-observer)

#### IndexedDB

- [Crash course](https://www.youtube.com/watch?v=vb7fkBeblcw)

#### Web Components API

- [Crash course](https://www.youtube.com/watch?v=PCWaFLy3VUo)

#### Misc Libraries

- [Color Thief](https://lokeshdhakar.com/projects/color-thief/) - Grab the color palette from an image using JS. Works in the browser and in Node.js.

#### TWA

- Prerequisite: PWA (covered a few points above) and a Google Play Console Developer Account ($25 fee)
- [What is a Trusted Web Activity?](https://www.youtube.com/watch?v=7JDFjeMvxos)
- [TWA overview](https://developer.chrome.com/docs/android/trusted-web-activity/overview/)
- [Build a TWA from an existing PWA](https://www.pwabuilder.com/) ([Steps after downlaoding](https://github.com/pwa-builder/CloudAPK/blob/master/Next-steps.md) and [Asset Link file instructions](https://github.com/pwa-builder/CloudAPK/blob/master/Asset-links.md))
- Hosting a TWA using GitHub Pages
   - NOTE: The PWA can be hosted from any of **your** repos. The instructions below have to be followed nonetheless.
   - Create a repo with the name `<github_username>.github.io`.
   - The `.well-known/assetlinks.json` file should be in the root directory of the newly created repo. ([More info](https://www.mydatahack.com/releasing-multiple-pwas-to-googleplay-by-using-a-single-github-page-root/))
   - If you're not using [Jekyll](https://jekyllrb.com/), add an empty `.nojekyll` file to the root directory of the newly created repo. ([Reason](https://github.community/t/unable-to-access-resources-in-folder-with-name-starting-with/10505))
   - If you're using [Jekyll](https://jekyllrb.com/), change your `_config.yml` file to include the `.well-known` folder.

### General Back End Prerequisites

#### HTTP

- [What is HTTP?](https://www.youtube.com/watch?v=0OrmKCB0UrQ)
- [Crash course](https://www.youtube.com/watch?v=iYM2zFP3Zn0)
- [HTTP methods, status codes and versions](https://github.com/HarshKapadia2/networking/blob/main/http.md)

#### JSON

- [Crash course](https://www.youtube.com/watch?v=iiADhChRriM)
- [Schema templates](https://www.schemastore.org/json/) (for JSON, JavaScript and CSS)
- [`JSON.stringify`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify) and its [optional parameters](https://www.youtube.com/watch?v=0k4NwimfszA).
- [`JSON.parse`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/parse)

#### APIs

- [REST (RESTful) API introduction](https://www.youtube.com/watch?v=Q-BpqyOT3a8)
- [REST in short](https://www.youtube.com/watch?v=6sUbt-Qp6Pg)
- [REST Web Service](https://www.youtube.com/watch?v=lyxJQWUymV4&list=PLhW3qG5bs-L9E2KV6vVdB-YTk-sRxmRAB&index=5)
- [Designing an API](https://www.youtube.com/watch?v=_YlYuNMTCc8)
- [Some public APIs](https://github.com/public-apis/public-apis)

#### Async JS

- [Crash course](https://www.youtube.com/watch?v=_8gHHBlbziw)
- [`async`/`await` article](https://www.freecodecamp.org/news/async-await-javascript-tutorial/)

#### Caching

- [CacheStorage API](https://developer.mozilla.org/en-US/docs/Web/API/CacheStorage)
- [Cache API](https://developer.mozilla.org/en-US/docs/Web/API/Cache)
- [Cache-Control header](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Cache-Control)
- Difference between the Cache API and CacheStorage API
   - [Tweet](https://twitter.com/harshgkapadia/status/1355100023705493507)
   - A Cache is an object (file) and Cache Storage is a file system.
- [Cache Busting](https://medium.com/javascript-in-plain-english/what-is-cache-busting-55366b3ac022) ([CSS-Tricks article](https://css-tricks.com/strategies-for-cache-busting-css/))
- [Application Cache is a Douchebag](https://alistapart.com/article/application-cache-is-a-douchebag/) (Caching gotchas.) (Refer to [PWA section](#pwa) above.)

- AJAX and its libraries
   - [Crash course](https://www.youtube.com/watch?v=82hnvUYY6QA) (with `XMLHttpRequest`)
   - Fetch API
      - [Hands on introduction](https://www.youtube.com/watch?v=Oive66jrwBs)
      - [Fetch API error handling](https://www.youtube.com/watch?v=cuEtnrL9-H0)
   - [Playlist: Async JS, AJAX, XHR, Fetch, Cookies, CORS, Headers, Auth, etc.](https://www.youtube.com/watch?v=7EKebb4VUYQ&list=PLyuRouwmQCjkWu63mHksI9EA4fN-vwGs7&index=1)

### Databases

- [A Database of Databases](https://dbdb.io/)

#### SQL

- Relational DBs
- [MySQL crash course](https://www.youtube.com/watch?v=HXV3zeQKqGY)
- MySQL [fragmentation](https://www.youtube.com/watch?v=sICmP7bJrvo) and [partitioning](https://www.youtube.com/watch?v=iUjoPB27-iA) (Beginners, please ignore.)
- Eg: MySQL, PostgreSQL, MariaDB, SQLite, etc...

#### NoSQL

- Non-relational DBs
- [NoSQL DB introduction](https://www.youtube.com/watch?v=uD3p_rZPBUQ)
- [MongoDB crash course](https://www.youtube.com/watch?v=-56x56UppqQ)
- Cloud Firestore and Realtime DB (Firebase) (covered below)

### JS Back End

#### Node.js

- [Crash course](https://www.youtube.com/watch?v=fBNz5xF-Kx4)
- [Middleware](https://thenextbigwriter.tech/middlewares-in-express-js-ck8d87su900w3xes1ny80u28q)
   
#### Express.js

- [Crash course](https://www.youtube.com/watch?v=L72fhGm1tfE)
- [Body parser](https://stackoverflow.com/a/43626891/11958552)

#### JS REST API

- [Node.js (Express.js) and MongoDB REST API](https://www.youtube.com/watch?v=vjf774RKrLc)

### Python Back End

#### Prerequisite

- [Python basics](https://www.youtube.com/watch?v=JJmcL1N2KQs)
   
#### Flask
   - [Crash course](https://www.youtube.com/watch?v=Z1RJmh_OqeA)
   - [*Tech With Tim*'s series](https://www.youtube.com/watch?v=mqhxxeeTbu0&list=PLzMcBGfZo4-n4vJJybUVV3Un_NFS5EOgX)
   - [Documentation](https://flask.palletsprojects.com/en/1.1.x/)

### PHP

#### Prerequisites

- [PHP basics](https://www.youtube.com/watch?v=oJbfyzaA2QA&list=PLillGF-Rfqbap2IB6ZS4BBBcYPagAjpjn&index=1)
- [PHP Data Objects](https://www.youtube.com/watch?v=kEW6f7Pilc4) (PDO)

#### PHP REST API

- [Crash course](https://www.youtube.com/watch?v=OEWXbpUMODk&list=PLillGF-RfqbZ3_Xr8do7Q2R752xYrDRAo&index=1)

### Front End JS Frameworks/Libraries

#### Prerequisite

##### State

- ['State' in 30 seconds](https://twitter.com/technoidic_ash/status/1305638862631260160?s=19)
- [What is 'state'?](https://egghead.io/articles/what-is-state-why-do-i-need-to-manage-it)

#### React.js

- [Crash course (2021)](https://www.youtube.com/watch?v=w7ejDZ8SWv8)
- React.js internals
   - [Deconstructing React](https://www.youtube.com/watch?v=f2mMOiCSj5c)
   - [Building a Custom React Renderer](https://www.youtube.com/watch?v=CGpMlWVcHok)
   - [Destructuring React](https://www.youtube.com/watch?v=zmO51Dn5DPI)

### Misc #2

#### Web Performance

- [Lighthouse](https://developers.google.com/web/tools/lighthouse/) (available in Chrome and Edge DevTools and as an add-on in Firefox)
- [web.dev](https://web.dev/)

#### SEO

##### `robots.txt`
   - https://www.robotstxt.org/
   - [Google Site Verification](https://developers.google.com/search/docs/advanced/robots/submit-updated-robots-txt)

#### Firebase

- BaaS
- [Documentation](https://firebase.google.com/docs) (More than sufficient. Also, do watch the videos linked in the docs.)

#### DevOps

##### Git

- Covered in the [Git and GitHub section](#git-and-github) above.

##### Deployment/Hosting

- For web sites only
   - [GitHub Pages](https://pages.github.com/)
   - [Netlify](https://www.netlify.com/)
- For web sites and web apps
   - [Heroku](https://heroku.com/)
   - [Python Anywhere](https://www.pythonanywhere.com/) (Only for Python web sites and web apps.)
   - [Firebase Hosting](https://firebase.google.com/docs/hosting/) (Dynamic: Only Node.js supported through Cloud Functions)
   - [Digital Ocean](https://www.digitalocean.com/solutions/website-hosting/)
- Domain names
   - [.js.org](https://js.org/) (For users, organizations, projects, etc.) (free)
   - [.is-a.dev](https://www.is-a.dev/) (For portfolio web sites.) (free)
   - [.ml](http://www.dot.ml/en/index.html?lang=en) (free)

##### CI/CD

- GitHub Actions
- Jenkins
- TravisCI
- Circle CI

##### Docker

- [Getting Started](https://www.youtube.com/watch?v=Kyx2PsuwomE) (part one of two)
- [Docker Compose](https://www.youtube.com/watch?v=hP77Rua1E0c) (part two of two)
- [My Docker repo](https://github.com/HarshKapadia2/docker)
