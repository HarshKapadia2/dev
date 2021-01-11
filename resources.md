# My web dev resources

- The crash course in each section is the bare minimum that should be done.
- The resources have been aligned in a logical manner that should be followed.

## My resources

### Prerequisites

- Browser (Chrome, Edge, Brave or Firefox are preferred.)
- [Set up VSCode](https://www.youtube.com/watch?v=fnPhJHN0jTE)

### Front end

- HTML
   - [Crash course](https://www.youtube.com/watch?v=UB1O30fR-EE)
   - [The Open Graph Protocol](https://www.freecodecamp.org/news/what-is-open-graph-and-how-can-i-use-it-for-my-website/#what-is-open-graph)
   - [Validator](https://validator.w3.org/) to check correctness of HTML.

- CSS
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
   - [Bootstrap crash course](https://www.youtube.com/watch?v=5GcQtLDGXy8)
   - [Some design resources](https://github.com/bradtraversy/design-resources-for-developers)
   - [Sub-string matching selectors](https://blog.teamtreehouse.com/css3-substring-matching-attribute-selectors) (Eg: `[class*="col-"] { width: 100%; }`)
   - CSS internals
      - [Redo Your CSS](https://www.redoyourcss.com/)

- JS
   - [Crash course](https://www.youtube.com/watch?v=hdI2bqOjy3c)
   - [`var` vs `let` vs `const`](https://blog.webdevsimplified.com/2020-01/var-vs-let-vs-const/)
   - [Document Object Model](https://medium.com/@EdidiongAsikpo/getting-started-with-the-dom-d27907f17be0) (DOM)
   - [`window` vs `document`](https://stackoverflow.com/questions/9895202/what-is-the-difference-between-window-screen-and-document-in-javascript)
   - [`element.classList`](https://blog.webdevsimplified.com/2020-11/class-list/)
   - [Data attributes](https://blog.webdevsimplified.com/2020-10/javascript-data-attributes/) (`element.dataset` property - view [MDN](https://developer.mozilla.org/en-US/docs/Web/API/HTMLOrForeignElement/dataset) for more.)
   - [`localStorage` vs `sessionStorage`](https://blog.webdevsimplified.com/2020-08/cookies-localStorage-sessionStorage/) (view [javascript.info](https://javascript.info/localstorage) for more differences)
   - [Rounding off](https://medium.com/swlh/how-to-round-to-a-certain-number-of-decimal-places-in-javascript-ed74c471c1b8)
   - [Responsive nav bar tutorial](https://www.youtube.com/watch?v=gXkqy0b4M5g)
   - [HTML Drag and Drop API](https://www.youtube.com/watch?v=Wtrin7C4b7w)
   - JS internals (absolute beginners can skip)
      - [Namaste :pray: JavaScript](https://www.youtube.com/watch?v=pN6jk0uUrD8&list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP&index=1)
      - [Event loop](https://www.youtube.com/watch?v=8aGhZQkoFbQ&feature=youtu.be)
      - [Scheduling in JS and browsers](https://www.youtube.com/watch?v=z96oKTUSQjE) | [Tweet](https://twitter.com/reactify_in/status/1309843620179054592)
      - [JS modules and build tools](https://www.youtube.com/watch?v=U4ja6HeBm6s&feature=youtu.be)

### Misc

- Git and GitHub
   - Sessions by me
      - [Crash course](https://www.youtube.com/watch?v=HF12-91iazM)
      - [Open Source, Hacktoberfest and Pull Requests](https://www.youtube.com/watch?v=uJdFNksgKJA)
   - [git_basics web site](https://harshkapadia2.github.io/git_basics/)
   - [Crash course by Brad Traversy](https://www.youtube.com/watch?v=SWYqp7iY_Tc)

- Web design
   - [Typography 101](https://www.youtube.com/watch?v=HnpsOtIcfbo)
   - [Color theory 101](https://www.youtube.com/watch?v=e_kdWMmD3z0)
   - [Layout design](https://www.youtube.com/watch?v=S4viQ_Ejptc)
   - [Top Design Resources and Apps](https://www.youtube.com/watch?v=GUOgv4PcHIQ)

- Browser DevTools
   - [Guide to Chrome's performance profiler](https://www.youtube.com/watch?v=KWM5wxlDuis)
   - [Chrome DevTools documentation](https://developers.google.com/web/tools/chrome-devtools/)
   - [Crash course](https://www.youtube.com/watch?v=x4q86IjJFag)

> NOTE: The DevTools are similar in almost all browsers, so the above resources are fine.

- [Check the support of a front end web technology on desktop and mobile web browsers.](https://caniuse.com/ciu/about)

- [Networking](https://github.com/HarshKapadia2/networking)

- RegEx
   - [Crash course](https://www.youtube.com/watch?v=rhzKDrUiJVk)
   - [RegEx summarised in 100 seconds](https://www.youtube.com/watch?v=sXQxhojSdZM)

- Web Components API
   - [Crash course](https://www.youtube.com/watch?v=PCWaFLy3VUo)

- SVG
   - [Get started](https://webdesign.tutsplus.com/tutorials/how-to-hand-code-svg--cms-30368)

### General back end prerequisites

- HTTP
   - [What is HTTP?](https://www.youtube.com/watch?v=0OrmKCB0UrQ)
   - [Crash course](https://www.youtube.com/watch?v=iYM2zFP3Zn0)
   - [HTTP methods, status codes and versions](https://github.com/HarshKapadia2/networking/blob/main/http.md)

- JSON
   - [Crash course](https://www.youtube.com/watch?v=iiADhChRriM)
   - [Schema templates](https://www.schemastore.org/json/) (for JSON, JavaScript and CSS)
   - [`JSON.stringify`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify) and its [optional parameters](https://www.youtube.com/watch?v=0k4NwimfszA).
   - [`JSON.parse`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/parse)

- APIs
   - [REST (RESTful) API introduction](https://www.youtube.com/watch?v=Q-BpqyOT3a8)
   - [REST in short](https://www.youtube.com/watch?v=6sUbt-Qp6Pg)
   - [REST Web Service](https://www.youtube.com/watch?v=lyxJQWUymV4&list=PLhW3qG5bs-L9E2KV6vVdB-YTk-sRxmRAB&index=5)
   - [Some public APIs](https://github.com/public-apis/public-apis)

- Asynchronous (async) JS
   - [Crash course](https://www.youtube.com/watch?v=_8gHHBlbziw)
   - [`async`/`await` article](https://www.freecodecamp.org/news/async-await-javascript-tutorial/)

- AJAX and its libraries
   - [Crash course](https://www.youtube.com/watch?v=82hnvUYY6QA) (with `XMLHttpRequest`)
   - Fetch API
      - [Hands on introduction](https://www.youtube.com/watch?v=Oive66jrwBs)
      - [Fetch API error handling](https://www.youtube.com/watch?v=cuEtnrL9-H0)
   - [Playlist: Async JS, AJAX, XHR, Fetch, Cookies, CORS, Headers, Auth, etc.](https://www.youtube.com/watch?v=7EKebb4VUYQ&list=PLyuRouwmQCjkWu63mHksI9EA4fN-vwGs7&index=1)

### Databases

- [A Database of Databases](https://dbdb.io/)

- SQL (Relational DBs)
   - [MySQL crash course](https://www.youtube.com/watch?v=HXV3zeQKqGY)
   - MySQL [fragmentation](https://www.youtube.com/watch?v=sICmP7bJrvo) and [partitioning](https://www.youtube.com/watch?v=iUjoPB27-iA) (Beginners, please ignore.)
   - Eg: MySQL, PostgreSQL, MariaDB, SQLite, etc...

- NoSQL
   - [NoSQL DB introduction](https://www.youtube.com/watch?v=uD3p_rZPBUQ)
   - [MongoDB crash course](https://www.youtube.com/watch?v=-56x56UppqQ)
   - Cloud Firestore and Realtime DB (Firebase) (covered below)

### JS back end

- Node.js
   - [Crash course](https://www.youtube.com/watch?v=fBNz5xF-Kx4)
   - [Middleware](https://thenextbigwriter.tech/middlewares-in-express-js-ck8d87su900w3xes1ny80u28q)
   
- Express.js
   - [Crash course](https://www.youtube.com/watch?v=L72fhGm1tfE)
   - [Body parser](https://stackoverflow.com/a/43626891/11958552)

- JS REST API
   - [Node.js (Express.js) and MongoDB REST API](https://www.youtube.com/watch?v=vjf774RKrLc)

### JS front end frameworks/libraries

- Prerequisite
   - State
      - ['State' in 30 seconds](https://twitter.com/technoidic_ash/status/1305638862631260160?s=19)
      - [What is 'state'?](https://egghead.io/articles/what-is-state-why-do-i-need-to-manage-it)
   
- Vue.js (Still have to do this)
   - [Crash course](https://www.youtube.com/watch?v=Wy9q22isx3U)
   - [Vuex](https://www.youtube.com/watch?v=5lVQgZzLMHc) (state management library)

### Python back end

- Prerequisite
   - [Python basics](https://www.youtube.com/watch?v=JJmcL1N2KQs)
   
- Flask
   - [Crash course](https://www.youtube.com/watch?v=Z1RJmh_OqeA)
   - [*Tech With Tim*'s series](https://www.youtube.com/watch?v=mqhxxeeTbu0&list=PLzMcBGfZo4-n4vJJybUVV3Un_NFS5EOgX)
   - [Documentation](https://flask.palletsprojects.com/en/1.1.x/)

### PHP

- Prerequisites
   - [PHP basics](https://www.youtube.com/watch?v=oJbfyzaA2QA&list=PLillGF-Rfqbap2IB6ZS4BBBcYPagAjpjn&index=1)
   - [PHP Data Objects](https://www.youtube.com/watch?v=kEW6f7Pilc4) (PDO)
- PHP REST API
   - [Crash course](https://www.youtube.com/watch?v=OEWXbpUMODk&list=PLillGF-RfqbZ3_Xr8do7Q2R752xYrDRAo&index=1)

### Common path for everyone

- Web performance
   - [Lighthouse](https://developers.google.com/web/tools/lighthouse/) (available in Chrome and Edge DevTools and as an add-on in Firefox)
   - [web.dev](https://web.dev/)

- Firebase
   - [Documentation](https://firebase.google.com/docs) (More than sufficient. Also, do watch the videos linked in the docs.)

- DevOps
   - Git (Covered in the [Misc](#misc) section above.)
   - Deployment/hosting
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
   - CI/CD (Still have to do this)
      - GitHub Actions
      - Jenkins
      - TravisCI
      - Circle CI
   - Docker
      - [Getting Started](https://www.youtube.com/watch?v=Kyx2PsuwomE) (part one of two)
      - [Docker Compose](https://www.youtube.com/watch?v=hP77Rua1E0c) (part two of two)
      - [My Docker repo](https://github.com/HarshKapadia2/docker)
