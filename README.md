
<h1 align="center">
  Spellbook of Modern Web Dev
</h1>

<div align="center">
  <em>A Big Picture, Thesaurus, and Taxonomy of Modern JavaScript Web Development</em>
</div>

<br>
<br>
<br>
<br>

<div align="center">
  <img src="assets/cover.png" alt="Spellbook of Modern Web Dev" width="256">
</div>

<br>
<br>
<br>
<br>

* This document originated from a bunch of most commonly used links and learning resources I sent to every new web developer on our full-stack web development team.
* What I'm doing in this document now is trying to provide the __complete view angle__ of __modern web (app or page) development ruled by JavaScript__, reflect __technological advance__ and help developers to __acquire APIs, libraries, tools, services, best practices and learning resource__ which are __not outdated__ and __most commonly used__.
* I hope this document can __help one developer to have more power to do much more and much better__, just __like a spellbook does in fantasy worlds__.
* The JS/web technology is like [an ocean of stuff you don’t know](https://medium.com/javascript-scene/why-im-thankful-for-js-fatigue-i-know-you-re-sick-of-those-words-but-this-is-different-296fae0c888f). Simply collecting more stuff or composing dozens of "awesome lists" into a single one will only exacerbate the [Javascript Fatigue](https://medium.com/@ericclemmons/javascript-fatigue-48d4011b6fc4). So this document must __stay lean__ and focus on __the most frequent problems__ and __the most commonly used stuff__.
* So for each problem domain and each technology, I try my best to pick only __one or a few__ links.
* Which link belongs to "not outdated and most commonly used stuff" is not only decided by __clear trends__, __empirical observation__, and __working experience__, also by __public data__ and __web scraping scripts__.
* __The npm package statistics (like download count) are given more weight than Github repo statistics (like starring data)__ because npm statistics can better reflect the actual usage and popularity.
* Prefer __fine-grained classifications and deep hierarchies__ over __featureless descriptions and distractive comments__.
* Ideally, __each line is a unique category__. The __" / "__ symbol between the links means they are replaceable. The __", "__ symbol between the links means they are complementary.
* I wish this document could be closer to a kind of __knowledge graph__ or __skill tree__ than a list or a collection.
* It currently contains __2000+__<!-- \[[^\]]+\] --> links (projects, tools, plugins, services, articles, books, sites, etc.)
* Feel free to submit the __missing__ or __better__ links in your opinion. Also, please provide the __reason__.
* [Why not add a Europe (or other regions) section](https://github.com/dexteryy/spellbook-of-modern-webdev/pull/4#issuecomment-308073026)? [Why not add your project](https://github.com/dexteryy/spellbook-of-modern-webdev/pull/5)? [Why so many React-based projects? Why not Angular/Vue.js/XXX](http://www.npmtrends.com/rxjs-vs-mobx-vs-redux-vs-vue-vs-react-vs-@angular/core-vs-@cycle/dom-vs-backbone-vs-jquery-vs-vuex)?

#### Understanding Modern Web Development

* In English: coming soon...
* In Chinese: [slides](https://speakerdeck.com/dexteryy/understanding-modern-web-development-at-jsconf-china-2017-zhong-wen) @ [JSConf CN 2017](http://2017.jsconf.cn/#schedule)

<br>
<br>

<div align="center">
  <img src="assets/showme.jpg" width="">
</div>

<br>
<br>

---

## Table of Contents


- [Platforms and Languages](#platforms-and-languages)
  - [Open Web Platform](#open-web-platform)
    - Learning, Reference, Visual Tools
    - Performance, Security, Semantics / SEO / Accessibility
  - [HTML5 / Web APIs](#html5--web-apis)
    - HTML/DOM, Appearance, Interaction, Access, Network, Media, Graphics, Computing...
  - [CSS Features](#css-features)
    - RWD, Layout, Typography, Text, Animation, Effects...
  - [Modern CSS / Next-Gen CSS](#modern-css--next-gen-css)
    - CSS Module, PostCSS, CSS in JS
    - Best Practices (Skeleton, Methodology, Code Style...)
    - Know More about Web Design / UI Design / UX Design (RWD, Atomic Design, Motion Design, Grid System, Typography, Style Guide...)
  - [Modern JS / Next-Gen JS](#modern-js--next-gen-js)
    - ES6+ Features, Intro to ES6+, Re-intro to JS, Important Proposals, Functional Programming, FRP, Static Typing, Code Style...
  - [WebAssembly](#webassembly)
    - Concepts, Features, Rust, ...
  - [Node.js](#nodejs)
    - Intro, Workshop, Best Practices...
  - [Platform Compatibility and Proposal Status](#platform-compatibility-and-proposal-status)
    - Platform Status / Releases / Updates, ECMAScript Compatibility
    - Proposal Status (W3C WG, WICG, WHATWG, ECMA TC39, Node.js CTC)
    - JS Engine (V8, JSC, Chakra), Web/JS Runtime (Electron, Cordova, React Native...), Device...
  - [Cross-browser / Polyfill Libraries](#cross-browser--polyfill-libraries)
    - Appearance, Interaction, Access, Network, Performance, Offline, Media...
  - [npm Ecosystem](#npm-ecosystem)
    - Finding Packages (Search, Stats, Rank)
    - Dependency Management / Release / Maintenance (npm, yarn, lerna, ncp...)
    - Convention (Open Source, SemVer, package.json, Small modules, Isomorphic JS / Universal JS...)
  - [Universal Utility Libraries](#universal-utility-libraries)
    - Standard Library Extensions (FP, OOP, Async...)
    - Hashing / Generating
    - Parsing / Manipulating (URL, Validator, i18n, Date, Numbers, Color, Text, Buffer / Blob...)
    - Logic, Network, Storage, NLP, ML...
- [Universal Web Apps / Web Pages](#universal-web-apps--web-pages)
  - [GUI Framework](#gui-framework)
    - View / ViewModel / ViewController (React)
    - Model / App State (Redux)
    - API (GraphQL)
    - GUI Architectures (MVC, MVP, PM, MVVM, Flux, Redux, Elm, MVI, SAM...)
  - [UI Toolkits](#ui-toolkits)
    - CSS, React...
  - [Standalone UI Components](#standalone-ui-components)
    - Layout, Icon, Button, Form, Overlay, Picker, Content, Editor...
- [Client Side](#client-side)
  - [UX Libraries](#ux-libraries)
    - Drag & Drop, Gesture, Scrolling, Zoom, Tooltip, Tour...
  - [Graphic Libraries](#graphic-libraries)
    - Animation (Effects, Loading, Scrolling, Parallax, Transition, Timeline, Motion / Curved Path...)
    - 2D (Canvas, SVG, Physics...), 3D (WebGL, Physics...)
    - Data Visualization, Game...
  - [Hybrid Libraries](#hybrid-libraries)
    - Electron, React Native
- [Server Side](#server-side)
  - [Network](#network)
    - HTTP (Intro, Same-origin policy, Performance, HTTPS, HTTP/2, gRPC...)
    - TCP, UDP...
  - [Server-side Best Practices](#server-side-best-practices)
    - Restful API, SaaS, Microservices (API Gateway, Serverless)
    - Cloud / Distributed, Web Hosting / Non-distributed
    - Authentication / Authorization, Security, Logging / Monitoring, DevOps...
  - [Microservices / API Services (Node.js)](#microservices--api-services-nodejs)
    - Frameworks (RESTful API, Microservices, Serverless, Bots...), GraphQL, DocGen + CodeGen...
  - [Server-side Libraries (Node.js)](#server-side-libraries-nodejs)
    - Configuration, Debugging, Protocols, Network, Crypto, Auth, Storage, Jobs, Scraping, Images, Parsing / Generating, NLP...
  - [Cloud Services (Global)](#cloud-services-global)
    - Compute (FaaS / Serverless / WebHook, PaaS, CaaS)
    - Storage (Object Storage, DBaaS)
    - BaaS (CRUD, Auth, Search, Email, SMS...)
    - AIaaS / BDaaS (Natural Language, Computer Vision...)
  - [Cloud Services (China)](#cloud-services-china)
    - The evil twins inside [the Great Firewall of China](https://github.com/dexteryy/spellbook-of-modern-webdev/pull/4)
- [Tooling](#tooling)
  - [Testing](#testing)
    - Unit Testing / Test Runner, Test Doubles
    - Web Testing (Integration Testing, Functional/E2E Testing, Visual testing, Monkey Testing, Headless Browsers)
    - Server-side Testing (Functional Testing, Load Testing)
    - Benchmark Testing
    - Analysis (Code Coverage, Node.js Security...)
  - [Documentation](#documentation)
    - JS, API, CLI, CSS / Style Guide, Writing
  - [Toolchain](#toolchain)
    - Compiler / Transpiler / Preprocessor (Babel, PostCSS...)
    - Loader / Builder / Bundler (Webpack, Rollup...)
    - Minifier / Compressor / Optimizer (Prepack, Babili / Uglify, imagemin, cssnano / clean-css...)
    - Formatter (Prettier, Stylefmt...)
    - Static Analysis (ESLint, Flow, StyleLint...)
    - Task Automation (npm scripts, Gulp...)
  - [Workflow](#workflow)
    - Development (Micro Generator, Live Reload / Watch / Preview, Dev Tools, HTTP Inspector, Debugging Proxy...)
    - Deployment (Process Supervisor, Containers, Container Clusters, PaaS)
    - Monitoring (Error Tracking, Logging, APM...)
  - [Command-line Environment (Mac)](#command-line-environment-mac)
    - Terminal, Homebrew, Zsh, Vim, Git, Docker, dotfiles, Utilities...
  - [Command-line Libraries (Node.js)](#command-line-libraries-nodejs)
    - Input (Options/Arguments Parser, Interactive, Configuration...)
    - Output (Color / Style, Icon, Updating Log, Notice, Columns, Curses, Drawing...)
    - Delivery, OS, API, Parser...
  - [IDE / Editors](#ide--editors)
    - VSCode Plugins (UI, Formatting, Operating, Static Analysis, Docs, Assistant, Integration...)
    - Atom Plugins (UI, Formatting, Operating, Static Analysis, Docs, Assistant, Integration...)
    - Out-of-the-box Atom IDE, Other Electron-based IDE, Programming Fonts...
  - [Useful Apps](#useful-apps)
    - Playground, Visual Tools, Viewer, Docs, Automation...
  - [Collaboration](#collaboration)
    - Version Control, ChatOps, Kanban, Markdown, Design...

A Subset as a __Learning Path__

1. [Open Web Platform](#open-web-platform)
2. [HTML5 / Web APIs](#html5--web-apis)
3. [CSS Features](#css-features)
4. [Modern CSS / Next-Gen CSS](#modern-css--next-gen-css)
5. [Modern JS / Next-Gen JS](#modern-js--next-gen-js)
6. [Platform Compatibility and Proposal Status](#platform-compatibility-and-proposal-status)
7. [Network](#network)
8. [Node.js](#nodejs)
9. [npm Ecosystem](#npm-ecosystem)
10. [Command-line Environment (Mac)](#command-line-environment-mac)
11. [IDE / Editors](#ide--editors)
12. [GUI Framework](#gui-framework)
13. [Microservices / API Services (Node.js)](#microservices--api-services-nodejs)
15. [Testing](#testing)

A Subset for __Finding Libraries__

- [Cross-browser / Polyfill Libraries](#cross-browser--polyfill-libraries)
- [Hybrid Libraries](#hybrid-libraries)
- [GUI Framework](#gui-framework)
- [UI Toolkits](#ui-toolkits)
- [Standalone UI Components](#standalone-ui-components)
- [UX Libraries](#ux-libraries)
- [Graphic Libraries](#graphic-libraries)
- [Universal Utility Libraries](#universal-utility-libraries)
- [Microservices / API Services (Node.js)](#microservices--api-services-nodejs)
- [Server-side Libraries (Node.js)](#server-side-libraries-nodejs)
- [Command-line Libraries (Node.js)](#command-line-libraries-nodejs)

A Subset for __Architecture and Infrastructure__

- [GUI Framework](#gui-framework)
- [Toolchain](#toolchain)
- [Workflow](#workflow)
- [Microservices / API Services (Node.js)](#microservices--api-services-nodejs)
- [Server-side Best Practices](#server-side-best-practices)
- [Cloud Services (Global)](#cloud-services-global) / [Cloud Services (China)](#cloud-services-china)
- [Documentation](#documentation)

---

<br>
<br>

<div align="center">
  <img src="assets/merlins_spell_book.jpg" width="">
</div>

<br>
<br>

## Platforms and Languages

### Open Web Platform

* Learning
  * [What is the Internet](http://www.20thingsilearned.com/en-US/what-is-the-internet/), [How does the Internet work](https://www.w3.org/wiki/How_does_the_Internet_work)
    * HTTP - see _[Server Side > Network](#network)_
  * [Evolution of the Web](http://www.evolutionoftheweb.com/)
    * [Timeline of web browsers](https://en.wikipedia.org/wiki/Timeline_of_web_browsers)
    * [Dive Into HTML5 - A Quite Biased History of HTML5](http://diveintohtml5.info/past.html)
    * [20 Things I Learned About Browsers and the Web](http://www.20thingsilearned.com/)
  * MDN's [Learn Web Development](https://developer.mozilla.org/en-US/docs/Learn)
* Reference
  * [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web)
    * [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference), [SVG](https://developer.mozilla.org/en-US/docs/Web/SVG), [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference), [DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model), [DOM Events](https://developer.mozilla.org/en-US/docs/Web/Events), [Web APIs](https://developer.mozilla.org/en-US/docs/Web/API)
    * [MDN content Roadmap](https://trello.com/b/LFl3umOX/mdn-content-roadmap)
  * [Google Developers](https://developers.google.com/web/)
    * [Web Fundamentals](https://developers.google.com/web/fundamentals/), [Update](https://developers.google.com/web/updates/), [HTML5Rocks Archived Tutorials](https://www.html5rocks.com/en/tutorials/)
  * Apple
    * [WebKit JS](https://developer.apple.com/reference/webkitjs/)
  * [CSSDB](https://cssdb.org/)
  * CSS-Tricks's [CSS Almanac](https://css-tricks.com/almanac/), [Codrops' CSS Reference](https://tympanus.net/codrops/css_reference/)
  * [Mastering CSS Principles: A Comprehensive Guide](https://www.smashingmagazine.com/mastering-css-principles-comprehensive-reference-guide/)
  * [HTML: The Living Standard (Web Developer Edition)](https://developers.whatwg.org/)
    * [The Web platform: Browser technologies](https://platform.html5.org/)
  * [W3Fools](http://www.w3fools.com/)
    * [W3Schools Responds to W3Fools](https://readwrite.com/2011/01/17/w3schools-responds-to-w3fools/)
    * [Why shouldn't I use W3Schools?](https://codereview.meta.stackexchange.com/questions/4975/why-shouldnt-i-use-w3schools-as-reference), [Why do people hate W3schools?](https://www.quora.com/Why-do-people-hate-W3schools-com), [Does W3Schools really suck?](https://www.quora.com/Does-W3Schools-really-suck)
  * Visual Tools
    * see _[Tooling > Useful Apps](#useful-apps) > Visual Tools_
* Performance
  * Rendering
    * [How Browsers Work: Behind the scenes of modern web browsers](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/), \
      [How Browsers Lay Out Web Pages](https://dbaron.org/talks/2012-03-11-sxsw/master.xhtml)
    * [Rendering Performance](https://developers.google.com/web/fundamentals/performance/rendering/)
    * [GPU Animation: Doing It Right](https://www.smashingmagazine.com/2016/12/gpu-animation-doing-it-right/) / [An Introduction to Hardware Acceleration with CSS Animations](https://www.sitepoint.com/introduction-to-hardware-acceleration-css-animations/)
    * [CSS will-change](https://developer.mozilla.org/en-US/docs/Web/CSS/will-change)
      * [Everything You Need to Know About the CSS will-change Property](https://dev.opera.com/articles/css-will-change-property/)
    * [CSS Containment in Chrome 52](https://developers.google.com/web/updates/2016/06/css-containment)
  * Loading
    * [How DNS works](https://howdns.works/)
    * [Network resilience](https://web.dev/reliable)
    * [Evolution of Script Loading](https://www.stevesouders.com/blog/2010/12/06/evolution-of-script-loading/), [Browser script loading roundup](https://www.stevesouders.com/blog/2010/02/07/browser-script-loading-roundup/)
    * [JavaScript Start-up Performance](https://medium.com/reloading/javascript-start-up-performance-69200f43b201)
    * [Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/),
       [CSS and the critical path](http://www.phpied.com/css-and-the-critical-path/)
  * Offline
    * see _[HTML5 / Web APIs](#html5--web-apis) > Offline_
  * Measure
    * [Performance budgets 101](https://web.dev/performance-budgets-101/)
    * [Measure Performance with the RAIL Model](https://developers.google.com/web/fundamentals/performance/rail)
    * [Measuring Page Load Speed with Navigation Timing](https://www.html5rocks.com/en/tutorials/webperformance/basics/)
    * [Measuring network performance with Resource Timing API](https://developers.googleblog.com/2013/12/measuring-network-performance-with.html)
    * [User Timing API](https://www.html5rocks.com/en/tutorials/webperformance/usertiming/)
    * [Why Web Developers Need to Care about Interactivity](https://philipwalton.com/articles/why-web-developers-need-to-care-about-interactivity/)
      * [requestIdleCallback](https://developers.google.com/web/updates/2015/08/using-requestidlecallback)
      * [PerformanceObserver](https://developer.mozilla.org/en-US/docs/Web/API/PerformanceObserver)
  * Optimization
    * [Fast load times](https://web.dev/fast)
    * [Why Performance Matters](https://developers.google.com/web/fundamentals/performance/why-performance-matters/)
    * [Performance audits](https://web.dev/lighthouse-performance)
    * [Lighthouse Audit References](https://developers.google.com/web/tools/lighthouse/audits/critical-request-chains)
* Security
  * [Safe and secure](https://web.dev/secure)
  * [The Tangled Web: A Guide to Securing Modern Web Applications](http://lcamtuf.coredump.cx/tangled/)
  * [HTML5 Security Cheatsheet](https://html5sec.org/)
* Semantics
  * SEO
    * [Let’s Talk about Semantics](http://html5doctor.com/lets-talk-about-semantics/)
    * [Easily discoverable](https://web.dev/discoverable)
    * [SEO audits](https://web.dev/lighthouse-seo)
    * [SEO Tutorial For Beginners](https://www.hobo-web.co.uk/seo-tutorial/), \
      Google's [Search Engine Optimization Starter Guide](http://www.google.com/webmasters/docs/search-engine-optimization-starter-guide.pdf)
  * Accessibility
    * [Accessible to all](https://web.dev/accessible)
    * [The A11Y Project](http://a11yproject.com/), [Using ARIA](https://w3c.github.io/using-aria/)

\>\> Return to [Table of Contents](#table-of-contents)

### HTML5 / Web APIs

* HTML / DOM
  * [You Might Not Need jQuery](http://youmightnotneedjquery.com/), \
    [You Don't Need jQuery](https://github.com/oneuijs/You-Dont-Need-jQuery), \
    [(Now More Than Ever) You Might Not Need jQuery](https://css-tricks.com/now-ever-might-not-need-jquery/)
  * [HEAD](https://github.com/joshbuchea/HEAD/)
  * [favicon](https://github.com/audreyr/favicon-cheat-sheet)
  * [Form pseudo-element](https://gist.github.com/webtobesocial/aefd6e25064c08e0cc9a)
  * [Native form elements](http://nativeformelements.com/)
  * [Detect DOM changes with Mutation Observers](https://developers.google.com/web/updates/2012/02/Detect-DOM-changes-with-Mutation-Observers)
* Appearance
  * [Web Components](https://developers.google.com/web/updates/2017/01/webcomponents-org)
    * [Shadow DOM v1](https://developers.google.com/web/fundamentals/getting-started/primers/shadowdom), [Custom Elements v1](https://developers.google.com/web/fundamentals/getting-started/primers/customelements)
  * [Web Animations](https://developer.mozilla.org/en-US/docs/Web/API/Web_Animations_API)
    * [Web Animation Past, Present, and Future](https://alistapart.com/article/web-animation-past-present-and-future)
    * [Let's talk about the Web Animations API](http://danielcwilson.com/blog/2015/07/animations-intro/)
    * Status - [Are we animated yet?](https://birtles.github.io/areweanimatedyet/)
* Interaction
  * Desktop
    * [MouseEvent](https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent), [WheelEvent](https://developer.mozilla.org/en-US/docs/Web/API/WheelEvent), [KeyboardEvent](https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent)
    * [Drag and Drop](https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API), [Pointer Lock](https://developer.mozilla.org/en-US/docs/Web/API/Pointer_Lock_API)
  * Mobile
    * [TouchEvent](https://developer.mozilla.org/en-US/docs/Web/API/TouchEvent)
      * [300ms tap delay, gone away](https://developers.google.com/web/updates/2013/12/300ms-tap-delay-gone-away), [More Responsive Tapping on iOS](https://webkit.org/blog/5610/more-responsive-tapping-on-ios/)
    * [DeviceOrientationEvent + DeviceMotionEvent](https://developer.mozilla.org/en-US/docs/Web/API/Detecting_device_orientation)
  * Hardware Agnostic
    * [PointerEvent](https://developer.mozilla.org/en-US/docs/Web/API/PointerEvent), [Selection](https://developer.mozilla.org/en-US/docs/Web/API/Selection)
    * [Intersection Observer API](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API) ([Intro](https://developers.google.com/web/updates/2016/04/intersectionobserver))
    * [Resize Observer API](https://developers.google.com/web/updates/2016/10/resizeobserver)
  * [Gamepad](https://developer.mozilla.org/en-US/docs/Web/API/Gamepad_API), [Web Speech](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API)
* Access
  * [URL](https://developer.mozilla.org/en-US/docs/Web/API/URL), [History](https://developer.mozilla.org/en-US/docs/Web/API/History), [Navigator](https://developer.mozilla.org/en-US/docs/Web/API/Navigator), [Screen](https://developer.mozilla.org/en-US/docs/Web/API/Screen), [Page Visibility](https://developer.mozilla.org/en-US/docs/Web/API/Page_Visibility_API), [Clipboard](https://developer.mozilla.org/en-US/docs/tag/Clipboard%20API), [Performance](https://developer.mozilla.org/en-US/docs/Web/API/Performance), [Console](https://developer.mozilla.org/en-US/docs/Web/API/Console)
  * [Permissions](https://developer.mozilla.org/en-US/docs/Web/API/Permissions_API), [Geolocation](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation)
  * [Web Notifications](https://developer.mozilla.org/en-US/docs/Web/API/Notifications_API) , [Vibration](https://developer.mozilla.org/en-US/docs/Web/API/Vibration_API)
* Network
  * [XMLHttpRequest2](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest)
  * [Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
    * [Abortable Fetch](https://developers.google.com/web/updates/2017/09/abortable-fetch)
    * [Why I won’t be using Fetch API in my apps](https://medium.com/@shahata/why-i-wont-be-using-fetch-api-in-my-apps-6900e6c6fe78)
  * [WebSocket](https://developer.mozilla.org/en-US/docs/Web/API/WebSocket), [Server-sent Event](https://developer.mozilla.org/en-US/docs/Web/API/EventSource)
  * [WebRTC](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API)
    * [Getting Started with WebRTC](https://www.html5rocks.com/en/tutorials/webrtc/basics/)
    * [WebRTC in the real world: STUN, TURN and signaling](https://www.html5rocks.com/en/tutorials/webrtc/infrastructure/)
    * [WebRTC data channels](https://www.html5rocks.com/en/tutorials/webrtc/datachannels/)
    * Workshop - [Codelabs - Real time communication with WebRTC](https://codelabs.developers.google.com/codelabs/webrtc-web/)
* Offline
  * Overview
    * [Offline UX Considerations](https://developers.google.com/web/fundamentals/instant-and-offline/offline-ux)
    * [The offline cookbook](https://jakearchibald.com/2014/offline-cookbook/)
    * [Offline First - HTML5 technologies for a faster, smarter, more engaging web](http://www.webdirections.org/offlineworkshop/ibooksDraft.pdf)
  * [Web Storage](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API), [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API#database_connection)
  * [FileReader](https://developer.mozilla.org/en-US/docs/Web/API/FileReader), [File](https://developer.mozilla.org/en-US/docs/Web/API/File), [Blob](https://developer.mozilla.org/en-US/docs/Web/API/Blob)
  * [Service Worker](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)
    * [Service Workers Explained](https://github.com/w3c/ServiceWorker/blob/master/explainer.md)
    * [Service Workers: an Introduction](https://developers.google.com/web/fundamentals/getting-started/primers/service-workers), [The Service Worker Lifecycle](https://developers.google.com/web/fundamentals/instant-and-offline/service-worker/lifecycle)
    * [Instant Loading Web Apps with an Application Shell Architecture](https://developers.google.com/web/updates/2015/11/app-shell)
    * [Service Worker Cookbook](https://serviceworke.rs/)
    * Status - [Is ServiceWorker Ready?](https://jakearchibald.github.io/isserviceworkerready/)
  * [Progressive Web Apps](https://developers.google.com/web/progressive-web-apps/)
    * [Progressive Web App Checklist](https://developers.google.com/web/progressive-web-apps/checklist), [PWA audits](https://web.dev/lighthouse-pwa)
    * [Offline Storage for Progressive Web Apps](https://developers.google.com/web/fundamentals/instant-and-offline/web-storage/offline-for-pwa)
    * [The PRPL pattern](https://developers.google.com/web/fundamentals/performance/prpl-pattern/)
    * Workshop - [Codelabs - Your First Progressive Web App](https://codelabs.developers.google.com/codelabs/your-first-pwapp/)
* Media
  * [\<video\>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video), [\<audio\>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio)
  * [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
    * [Web Audio API Book](http://chimera.labs.oreilly.com/books/1234000001552/index.html)
    * Workshop - [Web Audio School](https://github.com/mmckegg/web-audio-school)
  * [Media Streams](https://developer.mozilla.org/en-US/docs/Web/API/Media_Streams_API)
    * [Capturing Audio & Video in HTML5](https://www.html5rocks.com/en/tutorials/getusermedia/intro/)
* Graphics
  * [SVG](https://developer.mozilla.org/en-US/docs/Web/SVG)
    * [Styling And Animating SVGs With CSS](https://www.smashingmagazine.com/2014/11/styling-and-animating-svgs-with-css/)
  * [Canvas](https://developer.mozilla.org/en-US/docs/HTML/Canvas)
    * [HTML5 Canvas](http://chimera.labs.oreilly.com/books/1234000001654/index.html)
  * [WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API)
    * [WebGL by example](https://developer.mozilla.org/en-US/docs/Learn/WebGL/By_example), [WebGL tutorial](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/Tutorial), [Learning WebGL](http://learningwebgl.com/blog/?page_id=1217)
    * [Primer: Shaders](https://notes.underscorediscovery.com/shaders-a-primer/), [An Introduction to Shaders](https://aerotwist.com/tutorials/an-introduction-to-shaders-part-1/)
    * [The Book of Shaders](http://thebookofshaders.com/)
    * Workshop -[Shader School](https://github.com/stackgl/shader-school), [WebGL Workshop](https://github.com/stackgl/webgl-workshop), [WebGL Academy](http://www.webglacademy.com/)
    * [Learning Modern 3D Graphics Programming](https://paroj.github.io/gltut/)
  * [WebXR / Immersive Web](https://github.com/immersive-web/webxr)
    * [Welcome to the immersive web](https://developers.google.com/web/updates/2018/05/welcome-to-immersive)
    * [Progressive WebXR](https://blog.mozvr.com/progressive-webxr-ar-store/)
* Computing
  * [Web Cryptography](https://developer.mozilla.org/en-US/docs/Web/API/Crypto)
  * [Web Workers](https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API)
  * WebAssembly
    * see _[WebAssembly](#webassembly)_

\>\> Return to [Table of Contents](#table-of-contents)

### CSS Features

* Basics
  * [You Don't Need JavaScript](https://github.com/you-dont-need/You-Dont-Need-JavaScript)
  * [CSS Selectors from CSS4 till CSS1](http://css4-selectors.com/selectors/)
    * [CSS Diner - Where we feast on CSS Selectors!](http://flukeout.github.io/)
  * [An Ultimate Guide To CSS Pseudo-Classes And Pseudo-Elements](https://www.smashingmagazine.com/2016/05/an-ultimate-guide-to-css-pseudo-classes-and-pseudo-elements/)
  * [@supports Rule (Feature Queries)](https://www.sitepoint.com/an-introduction-to-css-supports-rule-feature-queries/)
  * [Houdini](https://github.com/w3c/css-houdini-drafts/wiki)
    * [Houdini: Demystifying CSS](https://developers.google.com/web/updates/2016/05/houdini), [Houdini: Maybe The Most Exciting Development In CSS You've Never Heard Of](https://www.smashingmagazine.com/2016/03/houdini-maybe-the-most-exciting-development-in-css-youve-never-heard-of/)
* Responsive Web Design
  * Media Queries
    * [Media Queries for Standard Devices](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/)
  * Images
    * [Responsive Images](https://developers.google.com/web/fundamentals/design-and-ui/responsive/images), [Responsive Images in CSS](https://css-tricks.com/responsive-images-css/)
  * Units
    * [Font Size Idea: px at the Root, rem for Components, em for Text Elements](https://css-tricks.com/rems-ems/), \
      [Understanding and Using rem Units in CSS](https://www.sitepoint.com/understanding-and-using-rem-units-in-css/)
    * [Truly Fluid Typography With vh And vw Units](https://www.smashingmagazine.com/2016/05/fluid-typography/)
* [Layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)
  * Flexbox, CSS Grid Layout
    * [CSS Grid, Flexbox And Box Alignment: Our New System For Web Layout](https://www.smashingmagazine.com/2016/11/css-grids-flexbox-and-box-alignment-our-new-system-for-web-layout/)
    * [A Complete Guide to Flexbox (CSS-Tricks)](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) / [Flexbox (Codrops)](https://tympanus.net/codrops/css_reference/flexbox/)
      * [Using Flexbox today](https://chriswrightdesign.com/experiments/using-flexbox-today/)
      * [Solved by Flexbox](https://philipwalton.github.io/solved-by-flexbox/), [Flexbox Patterns](http://www.flexboxpatterns.com/home)
        * [Centering Elements with Flexbox](https://www.smashingmagazine.com/2013/05/centering-elements-with-flexbox/)
        * [Quantity Queries with Flexbox](https://www.smashingmagazine.com/2015/07/quantity-ordering-with-css/)
    * [A Complete Guide to Grid (CSS-Tricks)](https://css-tricks.com/snippets/css/complete-guide-grid/) / [A Complete Guide to CSS Grid (Codrops)](https://tympanus.net/codrops/css_reference/grid/)
  * Traditional
    * [Learn CSS Layout](http://learnlayout.com/)
      * [Learn CSS Layout - the pedantic way](http://book.mixu.net/css/)
    * [CSS Floats 101](https://alistapart.com/article/css-floats-101), [All About Floats](https://css-tricks.com/all-about-floats/), [CSS Float Theory: Things You Should Know](https://www.smashingmagazine.com/2007/05/css-float-theory-things-you-should-know/)
    * [CSS Positioning 101](https://alistapart.com/article/css-positioning-101)
      * [CSS “position: sticky” – Introduction and Polyfills](https://www.sitepoint.com/css-position-sticky-introduction-polyfills/)
    * [The Z-Index CSS Property: A Comprehensive Look](https://www.smashingmagazine.com/2009/09/the-z-index-css-property-a-comprehensive-look/)
    * [Centering in CSS: A Complete Guide](https://css-tricks.com/centering-css-complete-guide/), [Absolute Center an Image](https://css-tricks.com/snippets/css/absolute-center-vertical-horizontal-an-image/), [How To Center in CSS](http://howtocenterincss.com/)
* Web Typography
  * [Using @font-face](https://css-tricks.com/snippets/css/using-font-face/)
  * [A Comprehensive Guide to Font Loading Strategies](https://www.zachleat.com/web/comprehensive-webfonts/)
* Text
  * [Handling Long Words and URLs](https://css-tricks.com/snippets/css/prevent-long-urls-from-breaking-out-of-container/)
  * [writing-mode](https://developer.mozilla.org/en-US/docs/Web/CSS/writing-mode) + [text-orientation](https://developer.mozilla.org/en-US/docs/Web/CSS/text-orientation)
* Animation
  * CSS Transition
    * [Using CSS transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions)
    * [Intro to CSS 3D transforms](http://desandro.github.io/3dtransforms/)
  * CSS Animation
    * [The Guide To CSS Animation: Principles and Examples](https://www.smashingmagazine.com/2011/09/the-guide-to-css-animation-principles-and-examples/)
    * [Upgrading CSS Animation With Motion Curves](https://www.smashingmagazine.com/2016/08/css-animations-motion-curves/)
  * Motion Path
    * [Animating Clipped Elements In SVG](https://www.smashingmagazine.com/2015/12/animating-clipped-elements-svg/)
    * [Moving along a curved path in CSS with layered animation](http://tobiasahlin.com/blog/curved-path-animations-in-css/)
    * [Future Use: CSS Motion Paths](https://codepen.io/danwilson/post/css-motion-paths)
* Effects
  * [CSS Image Effects](https://una.im/vintage-washout/)
  * [Web Image Effects Performance Showdown](https://www.smashingmagazine.com/2016/05/web-image-effects-performance-showdown/)
    * [Basics of CSS Blend Modes](https://css-tricks.com/basics-css-blend-modes/)
    * [CSS Blend Modes could be the next big thing in Web Design](https://medium.com/@bennettfeely/css-blend-modes-could-be-the-next-big-thing-in-web-design-6b51bf53743a)
    * [Understanding CSS Filter Effects](https://www.html5rocks.com/en/tutorials/filters/understanding-css/)
  * [Clipping and Masking in CSS](https://css-tricks.com/clipping-masking-css/)
  * [The State of CSS Reflections](https://css-tricks.com/state-css-reflections/)
  * [CSS Shapes 101](https://alistapart.com/article/css-shapes-101)

\>\> Return to [Table of Contents](#table-of-contents)

### Modern CSS / Next-Gen CSS

* Component-based CSS
  * Utility Class / Functional CSS / Utility-first CSS / Atomic CSS
    * [The Case for Atomic / Utility-First CSS](https://johnpolacek.github.io/the-case-for-atomic-css/)
      * [CSS Utility Classes and "Separation of Concerns"](https://adamwathan.me/css-utility-classes-and-separation-of-concerns/)
    * [A Year of Utility Classes](https://css-irl.info/a-year-of-utility-classes/)
    * [So you need a CSS utility library?](https://css-tricks.com/need-css-utility-library/)
    * see _[UI Toolkits](#ui-toolkits)_
  * [CSS Modules](https://github.com/css-modules/css-modules)
    * [The End of Global CSS](https://medium.com/seek-blog/the-end-of-global-css-90d2a4a06284)
    * Tools - see _[Tooling > Toolchain](#toolchain) > Builder / Bundler > Webpack_
  * [Styled-Components](https://github.com/styled-components/styled-components) / [Emotion](https://emotion.sh/)
    * [CSS in JS](https://speakerdeck.com/vjeux/react-css-in-js)
      * [A Unified Styling Language](https://medium.com/seek-blog/a-unified-styling-language-d0c208de2660)
      * [A Brief History of CSS-in-JS: How We Got Here and Where We’re Going](https://levelup.gitconnected.com/a-brief-history-of-css-in-js-how-we-got-here-and-where-were-going-ea6261c19f04), [The State of CSS](http://ryanogles.by/css/javascript/2017/05/25/the-state-of-css.html)
      * [Comparison of CSS-in-JS solutions](http://michelebertoli.github.io/css-in-js/)
    * [Styled Components: Enforcing Best Practices In Component-Based Systems](https://www.smashingmagazine.com/2017/01/styled-components-enforcing-best-practices-component-based-systems/)
    * [Writing your styles in JS ≠ writing inline styles](http://mxstbr.blog/2016/11/inline-styles-vs-css-in-js/)
    * Libraries
      * [styled-system](https://github.com/jxnblk/styled-system), [system-components](https://github.com/jxnblk/styled-system/tree/master/system-components), [grid-styled](https://jxnblk.com/grid-styled/)
      * [styled-normalize](https://github.com/sergeysova/styled-normalize) / [styled-sanitize](https://www.npmjs.com/package/styled-sanitize)
      * [styled-components-breakpoint](https://github.com/jameslnewell/styled-components-breakpoint)
      * [styled-tools](https://github.com/diegohaz/styled-tools)
* Preprocessor-based CSS
  * [PostCSS](http://postcss.org/)
    * Intro
      * [Meet PostCSS](http://www.meetpostcss.com/)
      * [PostCSS – A Comprehensive Introduction](https://www.smashingmagazine.com/2015/12/introduction-to-postcss/)
      * [PostCSS – Sass Killer or Preprocessing Pretender?](https://ashleynolan.co.uk/blog/postcss-a-review)
      * [PostCSS Playground](https://sneakertack.github.io/postcss-playground/)
    * [Preset Env](https://preset-env.cssdb.org/features)
      * [It’s Time To Start Using CSS Custom Properties](https://www.smashingmagazine.com/2017/04/start-using-css-custom-properties/)
      * [Getting Started With CSS calc()](https://www.smashingmagazine.com/2015/12/getting-started-css-calc-techniques/)
    * More Plugins - see _[Tooling > Toolchain](#toolchain) > Compiler / Transpiler / Preprocessor > PostCSS_
* Best Practices
  * [Sanitize.css](https://github.com/csstools/sanitize.css) / [Normalize.css](http://nicolasgallagher.com/about-normalize-css/) / [Reset.css](http://meyerweb.com/eric/tools/css/reset/)
  * Methodology
    * [BEM](https://en.bem.info/methodology/)
      * [BEM 101](https://css-tricks.com/bem-101/) / [MindBEMding](https://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/)
    * [OOCSS](https://github.com/stubbornella/oocss/wiki)
      * [An Introduction To Object Oriented CSS (OOCSS)](https://www.smashingmagazine.com/2011/12/an-introduction-to-object-oriented-css-oocss/)
    * [SMACSS](https://smacss.com/)
    * [ITCSS](https://www.xfive.co/blog/itcss-scalable-maintainable-css-architecture/), [RSCSS](http://rscss.io/), [SOLID CSS](http://blog.millermedeiros.com/solid-css/)
    * [CSS Guidelines](https://cssguidelin.es/), [MaintainableCSS](https://maintainablecss.com/)
  * Code Style
    * [Idiomatic CSS](https://github.com/necolas/idiomatic-css)
    * [Airbnb CSS / Sass Styleguide](https://github.com/airbnb/css)
    * [Airbnb CSS-in-JavaScript Style Guide](https://github.com/airbnb/javascript/tree/master/css-in-javascript)
    * CSS + HTML
      * [Isobar Front-end Code Standards](http://isobar-idev.github.io/code-standards/)
      * [Code Guide by @mdo](http://codeguide.co/)
* Know More about Web Design / [UI Design / UX Design](https://medium.com/@Mockplus/ux-vs-ui-vs-ia-vs-ixd-4-confusing-digital-design-terms-defined-ebd679f53f2)
  * Responsive/Adaptive Web Design
    * [Responsive Web Design Basics](https://developers.google.com/web/fundamentals/design-and-ui/responsive/) /\
      [Responsive Web Design: What It Is And How To Use It](https://www.smashingmagazine.com/2011/01/guidelines-for-responsive-web-design/)
    * [The Difference Between Responsive and Adaptive Design](https://css-tricks.com/the-difference-between-responsive-and-adaptive-design/)
    * [The Current State of Adaptive Design](https://medium.com/swlh/the-current-state-of-adaptive-design-6b2b89b258c4)
    * Responsivedesign.is - [Design](https://responsivedesign.is/design/), [Develop](https://responsivedesign.is/develop/)
    * Patterns
      * [Responsive Web Design Patterns](https://developers.google.com/web/fundamentals/design-and-ui/responsive/patterns), \
        [Responsive Patterns](http://bradfrost.github.io/this-is-responsive/patterns.html), \
        [ResponsiveDesign.is Patterns](https://responsivedesign.is/patterns/)
      * [Responsive Data Table Roundup](https://css-tricks.com/responsive-data-table-roundup/)
  * Motion Design
    * [Creating Usability with Motion: The UX in Motion Manifesto](https://medium.com/ux-in-motion/creating-usability-with-motion-the-ux-in-motion-manifesto-a87a4584ddc)
    * [10 principles for smooth web animations](https://blog.gyrosco.pe/smooth-css-animations-7d8ffc2c1d29)
  * Grid System - [A Comprehensive Introduction to Grids in Web Design](https://webdesign.tutsplus.com/articles/a-comprehensive-introduction-to-grids-in-web-design--cms-26521)
    * calc() grid system - [Lost Grid](http://lostgrid.org/)
    * flexbox grid system - [Flexbox Grid](http://flexboxgrid.com/)
    * [The 8-Point Grid](https://spec.fm/specifics/8-pt-grid)
  * Typography
    * [Typography.js](https://www.npmjs.com/package/typography)
    * [Gutenberg](http://matejlatin.github.io/Gutenberg/)
    * [The Equilateral Triangle of a Perfect Paragraph](https://betterwebtype.com/triangle)
    * [The Elements of Typographic Style Applied to the Web](http://webtypography.net/toc/)
    * [Why is Vertical Rhythm an Important Typography Practice?](https://zellwk.com/blog/why-vertical-rhythms/)
      * [CSS with vertical rhythm](https://drewish.com/tools/vertical-rhythm/)
    * [More Meaningful Typography](https://alistapart.com/article/more-meaningful-typography)
      * [Modular Scale](http://www.modularscale.com/)
  * [Atomic Design](http://bradfrost.com/blog/post/atomic-web-design/) ([Book](http://atomicdesign.bradfrost.com/table-of-contents/))
    * [The Atomic Workflow — People, Process, And Making Design Systems Happen](https://www.smashingmagazine.com/atomic-design-workflow/)
    * [The “Other” Interface: Atomic Design With Sass](https://www.smashingmagazine.com/2013/08/other-interface-atomic-design-sass/)
    * [Atomic Design – Your Ultimate Guide to Scalable & Modular CSS (Sass)](https://blog.alexdevero.com/atomic-design-scalable-modular-css-sass/)
  * Design System
    * [A comprehensive guide to design systems](https://www.invisionapp.com/blog/guide-to-design-systems/), [Design Systems Handbook](https://www.designbetter.co/design-systems-handbook/introducing-design-systems)
    * Design Tokens
      * [Tokens in Design Systems](https://medium.com/eightshapes-llc/tokens-in-design-systems-25dd82d58421)
      * [How to manage your Design Tokens with Style Dictionary](https://medium.com/@didoo/how-to-manage-your-design-tokens-with-style-dictionary-98c795b938aa)
      * [What Are Design Tokens?](https://css-tricks.com/what-are-design-tokens/)
    * Style Guide
      * [Style Guide Driven Development / Living Style Guides](http://styleguides.io/)
      * Tools - see _[Tooling > Documentation](#documentation) > Style Guide_
      * Examples
        * Apple's [Human Interface Guidelines](https://developer.apple.com/design/)
        * Google's [Material Design](https://material.io/)
        * Microsoft's [Fluent Design System](http://fluent.microsoft.com/)
        * Airbnb's [new design system](https://airbnb.design/building-a-visual-language/)
        * Github's [Primer](http://primercss.io/)
        * Atlassian's [Design Guidelines](https://atlassian.design/guidelines/product/overview)
        * Salesforce's [Lightning Design System](https://www.lightningdesignsystem.com/)
        * Yelp's [Styleguide](https://www.yelp.com/styleguide)
        * IBM's [Living Language](https://www.ibm.com/design/language/)
        * BBC's [GEL Guidelines](http://www.bbc.co.uk/gel/guidelines/)
        * A List Apart's [pattern library](http://patterns.alistapart.com/)
        * <span>USA</span>.gov's [Web Design Standards](https://standards.usa.gov/)
        * MailChimp's [Email Design Guide](https://mailchimp.com/email-design-guide/)

\>\> Return to [Table of Contents](#table-of-contents)

### Modern JS / Next-Gen JS

* ES6+ Features
  * [Overview of ECMAScript 6 features](https://github.com/lukehoban/es6features)
  * [Babel REPL](http://babeljs.io/repl/) / [ES6 New Features Comparison](http://es6-features.org/)
* Intro to ES6+
  * [Dr. Axel Rauschmayer's blog](http://2ality.com/)
    * [Exploring ES6](http://exploringjs.com/es6/)
    * [Exploring ES2016 and ES2017](http://exploringjs.com/es2016-es2017/)
  * [ES6 In Depth](https://hacks.mozilla.org/category/es6-in-depth/)
  * Nicholas C. Zakas's [Understanding ECMAScript 6](https://leanpub.com/understandinges6)
* Re-intro to JS
  * Articles
    * MDN
      * [A re-introduction to JavaScript (JS tutorial)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript)
      * [Equality comparisons and sameness](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness), [Data types and data structures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures), [Closures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures), [Inheritance and the prototype chain](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)
      * [Concurrency model and Event Loop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/EventLoop), [Memory Management](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Memory_Management)
    * Dmitry Soshnikov
      * [JavaScript. The Core](http://dmitrysoshnikov.com/ecmascript/javascript-the-core/)
      * ECMA-262-3 in detail
        * [Execution Contexts](http://dmitrysoshnikov.com/ecmascript/chapter-1-execution-contexts/), [Variable object](http://dmitrysoshnikov.com/ecmascript/chapter-2-variable-object/), [This](http://dmitrysoshnikov.com/ecmascript/chapter-3-this/), [Scope chain](http://dmitrysoshnikov.com/ecmascript/chapter-4-scope-chain/), [Functions](http://dmitrysoshnikov.com/ecmascript/chapter-5-functions/), [Closures](http://dmitrysoshnikov.com/ecmascript/chapter-6-closures/), [Evaluation strategy](http://dmitrysoshnikov.com/ecmascript/chapter-8-evaluation-strategy/)
        * OOP: [The general theory](http://dmitrysoshnikov.com/ecmascript/chapter-7-1-oop-general-theory/), [ECMAScript implementation](http://dmitrysoshnikov.com/ecmascript/chapter-7-2-oop-ecmascript-implementation/),
      * ECMA-262-5 in detail
        * [Properties and Property Descriptors](http://dmitrysoshnikov.com/ecmascript/es5-chapter-1-properties-and-property-descriptors/), [Strict Mode](http://dmitrysoshnikov.com/ecmascript/es5-chapter-2-strict-mode/)
        * Lexical environments: [Common Theory](http://dmitrysoshnikov.com/ecmascript/es5-chapter-3-1-lexical-environments-common-theory/), [ECMAScript implementation](http://dmitrysoshnikov.com/ecmascript/es5-chapter-3-2-lexical-environments-ecmascript-implementation/)
      * Notes
        * [Equality operators](http://dmitrysoshnikov.com/notes/note-2-ecmascript-equality-operators/), [Default values of parameters](http://dmitrysoshnikov.com/ecmascript/es6-notes-default-values-of-parameters/)
    * Dmitri Pavlutin
      * [equality operator](https://dmitripavlutin.com/the-legend-of-javascript-equality-operator/), [undefined](https://dmitripavlutin.com/7-tips-to-handle-undefined-in-javascript/)
      * [variables hoisting](https://dmitripavlutin.com/javascript-hoisting-in-details/), [variables lifecycle](https://dmitripavlutin.com/variables-lifecycle-and-why-let-is-not-hoisted/)
      * [declare functions](https://dmitripavlutin.com/6-ways-to-declare-javascript-functions/), ['this' keyword](https://dmitripavlutin.com/gentle-explanation-of-this-in-javascript/)
      * [three dots](https://dmitripavlutin.com/how-three-dots-changed-javascript/)
      * [array creation](https://dmitripavlutin.com/power-up-the-array-creation-in-javascript/), [object literals](https://dmitripavlutin.com/why-object-literals-in-javascript-are-cool/)
      * [well-known symbols](https://dmitripavlutin.com/detailed-overview-of-well-known-symbols/)
      * [small and plain functions](https://dmitripavlutin.com/the-art-of-writing-small-and-plain-functions/)
      * [unicode](https://dmitripavlutin.com/what-every-javascript-developer-should-know-about-unicode/)
    * Other
      * [The Evolution of JavaScript Modularity](https://github.com/myshov/history-of-javascript/tree/master/4_evolution_of_js_modularity)
      * [About object-oriented design and the “class” & “extends” keywords in ES6](http://blog.wolksoftware.com/about-classes-inheritance-and-object-oriented-design-in-typescript-and-es6)
      * [JavaScript Regular Expression Enlightenment](http://codylindley.com/techpro/2013_05_14__javascript-regular-expression-/)
  * Books
    * [Eloquent JavaScript](http://eloquentjavascript.net/)
    * [Speaking JavaScript](http://speakingjs.com/es5/)
    * [You Don't Know JS (book series)](https://github.com/getify/You-Dont-Know-JS)
* Reference
  * [JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
  * [JavaScript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)
* Important Proposals
  * ESM (ECMAScript Modules)
    * Intro
      * [The state of JavaScript modules](https://medium.com/webpack/the-state-of-javascript-modules-4636d1774358)
      * [ECMAScript 6 modules: the final syntax](http://2ality.com/2014/09/es6-modules-final.html)
      * [ES6 Modules in Depth](https://ponyfoo.com/articles/es6-modules-in-depth#the-es6-module-system)
    * Browsers
      * [ECMAScript modules in browsers](https://jakearchibald.com/2017/es-modules-in-browsers/)
    * Node.js
      * [Node.js, TC-39, and Modules](https://hackernoon.com/node-js-tc-39-and-modules-a1118aecf95e)
      * [.mjs](https://nodejs.org/api/esm.html)
        * [Using ES modules natively in Node.js](http://2ality.com/2017/09/native-esm-node.html)
      * [esm](https://www.npmjs.com/package/esm)
        * [ES Modules in Node Today!](https://medium.com/web-on-the-edge/es-modules-in-node-today-32cff914e4b)
  * [Dynamic Import (`import()`)](https://github.com/tc39/proposal-dynamic-import)
  * [Class Fields & Static Properties](https://github.com/tc39/proposal-class-public-fields/issues/46#issuecomment-239031422)
  * [Decorators](https://github.com/wycats/javascript-decorators)
  * [async/await](https://github.com/yortus/asyncawait), [Promise](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Promise), [Promise Promote](https://www.promisejs.org/), [Promises/A+](https://promisesaplus.com/implementations)
  * [Observables](https://github.com/tc39/proposal-observable)
  * [Static Typing](https://ecmascript-daily.github.io/pages/status-of-static-typing-in-ecmascript/)
  * Concurrent JS / Parallel JavaScript
    * [Concurrent JavaScript: It can work!](https://webkit.org/blog/7846/concurrent-javascript-it-can-work/)
    * [The Path to Parallel JavaScript](https://blog.mozilla.org/javascript/2015/02/26/the-path-to-parallel-javascript/)
      * [A Taste of JavaScript’s New Parallel Primitives](https://hacks.mozilla.org/2016/05/a-taste-of-javascripts-new-parallel-primitives/)
      * [A cartoon intro to ArrayBuffers and SharedArrayBuffers](https://hacks.mozilla.org/2017/06/a-cartoon-intro-to-arraybuffers-and-sharedarraybuffers/)
* Functional Programming
  * [Functional Programming for JavaScript People](https://medium.com/@chetcorcos/functional-programming-for-javascript-people-1915d8775504)
  * [Functional Programming Jargon](https://github.com/hemanth/functional-programming-jargon)
  * [Composing Software](https://medium.com/javascript-scene/the-rise-and-fall-and-rise-of-functional-programming-composable-software-c2d91b424c8c)
  * Books
    * [Professor Frisby's Mostly Adequate Guide to Functional Programming](https://drboolean.gitbooks.io/mostly-adequate-guide)
    * [Functional-Light JavaScript](https://github.com/getify/functional-light-js)
  * [Lodash's FP Guide](https://github.com/lodash/lodash/wiki/FP-Guide)
  * [Introduction to Immutable.js and Functional Programming Concepts](https://auth0.com/blog/intro-to-immutable-js/)
  * [Why Ramda?](http://fr.umio.us/why-ramda/)
    * [The Philosophy of Ramda](http://fr.umio.us/the-philosophy-of-ramda/)
    * [Favoring Curry](http://fr.umio.us/favoring-curry/)
    * [Thinking in Ramda](http://randycoulman.com/blog/2016/05/24/thinking-in-ramda-getting-started/)
  * [Fantasy Land](https://github.com/fantasyland/fantasy-land)
    * [From Callback to Future -> Functor -> Monad](https://hackernoon.com/from-callback-to-future-functor-monad-6c86d9c16cb5)
    * [ADT (Algebraic Data Types)](http://blog.jenkster.com/2016/06/functional-mumbo-jumbo-adts.html)
    * [JavaScript and Type Thinking](https://medium.com/@yelouafi/javascript-and-type-thinking-735edddc388d)
    * [Functors, Applicatives, And Monads In Pictures](http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html)
* FRP (Functional Reactive Programming)
  * [The introduction to Reactive Programming you've been missing](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754)
  * [How Is Reactive Different From Procedural Programming?](http://insights.dice.com/2014/01/13/how-is-reactive-different-from-procedural-programming/)
  * [A General Theory of Reactivity](https://github.com/kriskowal/gtor)
  * [Learn RxJS](https://www.learnrxjs.io/)
    * [Rx Book](http://xgrommx.github.io/rx-book/index.html)
    * [Functional Programming in JavaScript](http://reactivex.io/learnrx/)
    * [RxMarbles](http://rxmarbles.com/)
* Static Typing
  * Intro
    * [Why use static types in JavaScript?](https://medium.freecodecamp.com/why-use-static-types-in-javascript-part-1-8382da1e0adb)
    * [You Might Not Need TypeScript (or Static Types)](https://medium.com/javascript-scene/you-might-not-need-typescript-or-static-types-aa7cb670a77b)
  * [Flow](https://flow.org/en/docs/)
    * [Flow Runtime](https://codemix.github.io/flow-runtime/)
    * [Flow Comments](https://flow.org/blog/2015/02/20/Flow-Comments/)
  * [TypeScript](http://www.typescriptlang.org/)
    * [TypeScript Playground](https://www.typescriptlang.org/play/)
    * [DefinitelyTyped](http://definitelytyped.org/), [TypeSearch](http://microsoft.github.io/TypeSearch/)
  * [tcomb](https://www.npmjs.com/package/tcomb)
  * [JSDoc Tags](https://github.com/google/closure-compiler/wiki/Annotating-JavaScript-for-the-Closure-Compiler)
    * [jsdoc-to-assert](https://github.com/azu/jsdoc-to-assert)
* Concurrent JS / Parallel JavaScript
  * [Napa.js](https://github.com/Microsoft/napajs/)
* Code Style
  * [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
  * [Node.js Style Guide](https://github.com/felixge/node-style-guide)
  * [Clean Code JavaScript](https://github.com/ryanmcdermott/clean-code-javascript)
  * [JavaScript Clean Coding Best Practices](https://blog.risingstack.com/javascript-clean-coding-best-practices-node-js-at-scale/)

\>\> Return to [Table of Contents](#table-of-contents)

### WebAssembly

* References
  * [WebAssembly.org](http://webassembly.org/)
  * [MDN docs](https://developer.mozilla.org/en-US/docs/WebAssembly)
* Concepts
  * [WebAssembly High-Level Goals](https://github.com/WebAssembly/design/blob/master/HighLevelGoals.md)
  * [Minimum Viable Product](https://github.com/WebAssembly/design/blob/master/MVP.md)
  * [WebAssembly concepts](https://developer.mozilla.org/en-US/docs/WebAssembly/Concepts)
  * [An Abridged Cartoon Introduction To WebAssembly](https://www.smashingmagazine.com/2017/05/abridged-cartoon-introduction-webassembly/)
* Features
  * [Features to add after the MVP](https://github.com/WebAssembly/design/blob/master/FutureFeatures.md)
  * [WebAssembly proposals](https://github.com/WebAssembly/proposals)
* Workshop
  * [Codelabs - An Introduction to Web Assembly](https://codelabs.developers.google.com/codelabs/web-assembly-intro/)
* Languages
  * [Rust](https://www.rust-lang.org)
    * [Rust and WebAssembly](https://rustwasm.github.io/docs.html)
      * [The Rust Wasm Book](https://rustwasm.github.io/docs/book/)

### Node.js

* Intro
  * [The Art of Node](https://github.com/maxogden/art-of-node)
  * [You Don’t Know Node](https://webapplog.com/you-dont-know-node/)
  * [RisingStack's](https://blog.risingstack.com/node-js-at-scale-understanding-node-js-event-loop/) / [NodeSource's](https://nodesource.com/blog/understanding-the-nodejs-event-loop/) Understanding the Node.js Event Loop
  * [Node.js Garbage Collection Explained](https://blog.risingstack.com/node-js-at-scale-node-js-garbage-collection/)
  * [Stream Handbook](https://github.com/substack/stream-handbook)
    * [A Brief History of Node Streams](https://medium.com/the-node-js-collection/a-brief-history-of-node-streams-pt-1-3401db451f21)
    * [Understanding Object Streams](https://nodesource.com/blog/understanding-object-streams/)
  * [Keeping the Node.js core small](https://developer.ibm.com/node/2017/04/20/keeping-node-js-core-small/)
  * [Debugging Node.js with Google Chrome](https://medium.com/the-node-js-collection/debugging-node-js-with-google-chrome-4965b5f910f4)
    * [Add v8_inspector supports](https://medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27)
    * [How to Debug Node.js with the Best Tools Available](https://blog.risingstack.com/how-to-debug-nodej-js-with-the-best-tools-available/)
* Workshop
  * [NodeSchool](https://nodeschool.io/)
    * [learnyounode](https://www.npmjs.com/package/learnyounode)
* Best Practices
  * [The Node Way](http://thenodeway.io/introduction/)
  * [Joyent's Production Practices - Design](https://www.joyent.com/node-js/production/design/), [Error Handling](https://www.joyent.com/node-js/production/design/errors)
  * [Best Practices for Node.js Development](https://devcenter.heroku.com/articles/node-best-practices)
  * [Node.js Best Practices](https://github.com/alanjames1987/Node.js-Best-Practices)

\>\> Return to [Table of Contents](#table-of-contents)

### Platform Compatibility and Proposal Status

* Web
  * Platform Status
    * [Can I Use](http://caniuse.com/)
    * [Chrome](https://www.chromestatus.com/features), [WebKit](https://webkit.org/status/), [Firefox](https://platform-status.mozilla.org/), [Edge](https://developer.microsoft.com/en-us/microsoft-edge/platform/status/), [TBS (China)](http://x5.tencent.com/tbs/guide/w3c.html)
  * Platform Releases
    * [Chrome](https://chromereleases.googleblog.com/), [Safari](https://developer.apple.com/safari/whats-new/) ([Webkit](https://trac.webkit.org/)), [Firefox](https://www.mozilla.org/en-US/firefox/releases/), [Edge](https://developer.microsoft.com/en-us/microsoft-edge/platform/changelog/)
  * Platform Updates
    * [Mozilla Hacks](https://hacks.mozilla.org/)
    * [Web Updates](https://developers.google.com/web/updates/), [Chromium Blog](https://blog.chromium.org/)
    * [Webkit Blog](https://webkit.org/blog/)
    * [Microsoft Edge Dev Blog](https://developer.microsoft.com/en-us/microsoft-edge/community/)
  * [Writing forward-compatible websites](https://developer.mozilla.org/en-US/docs/Web/Guide/Writing_forward-compatible_websites)
    * Polyfill - [What is a Polyfill?](https://remysharp.com/2010/10/08/what-is-a-polyfill)
    * Feature Detection - [Modernizr/feature-detects](https://github.com/Modernizr/Modernizr/tree/master/feature-detects), [feature.js](https://github.com/viljamis/feature.js/blob/master/feature.js)
    * Browser/Device/Runtime Detection - see _[Platforms and Languages > Universal Utility Libraries](#universal-utility-libraries) > Parsing / Manipulating_
    * [Graded Browser Support](https://github.com/yui/yui3/wiki/Graded-Browser-Support) - [Grade components, not browsers](https://www.filamentgroup.com/lab/grade-the-components.html)
  * Email
    * [CSS Support Guide for Email Clients](https://www.campaignmonitor.com/css/) / [Email Client CSS Support](https://templates.mailchimp.com/resources/email-client-css-support/)
    * [Email Design Reference](https://templates.mailchimp.com/) + [HTML Email Templates](https://github.com/mailchimp/Email-Blueprints)
* Node.js
  * Platform Releases
    * [Node.js Release Working Group](https://github.com/nodejs/Release)
* ECMAScript Support
  * [ECMAScript compatibility table](http://kangax.github.io/compat-table/es6/)
  * [Node.js ES2015+ Support](http://node.green/)
    * Node 10.x LTS - Supports ES modules natively (without `--experimental-modules`)
    * [Node.8.5](https://nodejs.org/en/blog/release/v8.5.0/) - Supports ES modules natively (`.mjs` + `--experimental-modules`)
    * [Node 8.3](https://nodejs.org/en/blog/release/v8.3.0/) - [V8 6.0](https://v8project.blogspot.hk/2017/04/v8-release-59.html), [Ignition + Turbofan launched](https://v8project.blogspot.hk/2017/05/launching-ignition-and-turbofan.html)
    * [Node 8.0 LTS](https://nodejs.org/en/blog/release/v8.0.0/) - [V8 5.8](https://v8project.blogspot.hk/2017/03/v8-release-58.html), [Five New Features You Need To Know](http://codingsans.com/blog/node-8)
    * [Node 7.6](https://nodejs.org/en/blog/release/v7.6.0/) - [V8 5.5](https://v8project.blogspot.hk/2016/10/v8-release-55.html), Async functions
    * [Node 6.0 LTS](https://nodejs.org/en/blog/release/v6.0.0/) - [V8 5.0](https://v8project.blogspot.hk/2016/03/v8-release-50.html), 93% of ES6 language features
  * Performance - [Six Speed](https://kpdecker.github.io/six-speed/)
* Proposal Status
  * [W3C WG](https://www.w3.org/Consortium/activities#Working) (World Wide Web Consortium Working Groups)
    * [Web Platform Publication Status](https://www.w3.org/WebPlatform/WG/PubStatus)
      * [JavaScript APIs](https://www.w3.org/standards/techs/js), [Mobile Web Applications](https://www.w3.org/standards/techs/mobileapp), [CSS](https://www.w3.org/standards/techs/css)
    * [CSS current work](https://www.w3.org/Style/CSS/current-work)
    * [Current HTML5 Specifications](http://html5-overview.net/current)
    * Inside
      * [W3C TR (Technical Reports)](https://www.w3.org/2014/Process-20140801/#rec-advance)
      * [An Inside View of the CSS Working Group at W3C](http://fantasai.inkedblade.net/weblog/2011/inside-csswg/)
  * [WICG](https://wicg.github.io/admin/charter.html) (Web Incubator Community Group)
    * [Proposals](https://github.com/WICG)
  * [WHATWG](https://whatwg.org/faq) (Web Hypertext Application Technology Working Group)
    * [WHATWG Live Standards](https://spec.whatwg.org/)
    * Inside
      * [W3C vs. WHATWG HTML5 Specs – The Differences Documented](http://developer.telerik.com/featured/w3c-vs-whatwg-html5-specs-differences-documented/)
  * [ECMA TC39](http://ecma-international.org/memento/TC39.htm) (Ecma International Technical Committee 39)
    * [Status, process, and documents for ECMA262](https://github.com/tc39/ecma262)
      * [ECMAScript Proposals](https://github.com/tc39/proposals) / [TC39 Proposals](https://prop-tc39.now.sh/)
    * Inside
      * [The TC39 Process](http://tc39.github.io/process-document/) / [The TC39 process for ECMAScript features](http://2ality.com/2015/11/tc39-process.html)
  * [Node.js TSC](https://github.com/nodejs/TSC) (Node.js Foundation Technical Steering Committee)
    * [Meeting Notes](https://github.com/nodejs/TSC/tree/master/meetings)
    * Inside
      * [How Node.js created a model open source community](https://readwrite.com/2016/04/15/how-node-js-model-open-source-community-pl1/)
      * [Healthy Open Source](https://medium.com/the-node-js-collection/healthy-open-source-967fa8be7951)
* JS Engine
  * [A Guide to JavaScript Engines for Idiots](http://developer.telerik.com/featured/a-guide-to-javascript-engines-for-idiots/)
  * [V8](https://developers.google.com/v8/)
    * [How the V8 engine works?](http://thibaultlaurens.github.io/javascript/2013/04/29/how-the-v8-engine-works/)
    * Internal
      * [v8: a tale of two compilers](https://wingolog.org/archives/2011/07/05/v8-a-tale-of-two-compilers), \
        [A tour of V8: full compiler](http://jayconrod.com/posts/51/a-tour-of-v8-full-compiler)
      * [A tour of V8: Garbage Collection](http://jayconrod.com/posts/55/a-tour-of-v8-garbage-collection)
    * Next Generation
      * [Ignition + TurboFan launch and Declarative JavaScript](http://benediktmeurer.de/2017/04/03/v8-behind-the-scenes-march-edition/)
        * [Launching Ignition and TurboFan](https://v8project.blogspot.hk/2017/05/launching-ignition-and-turbofan.html)
        * [A tale of TurboFan](http://benediktmeurer.de/2017/03/01/v8-behind-the-scenes-february-edition/)
      * [Ignition + TurboFan and ES2015](http://benediktmeurer.de/2016/11/25/v8-behind-the-scenes-november-edition/)
  * [JSC](https://trac.webkit.org/wiki/JavaScriptCore)
    * [JavaScriptCore, the WebKit JS implementation](https://wingolog.org/archives/2011/10/28/javascriptcore-the-webkit-js-implementation)
    * Internal
      * [Introducing the WebKit FTL JIT](https://webkit.org/blog/3362/introducing-the-webkit-ftl-jit/)
    * Next Generation
      * [JSC Love ES6](https://webkit.org/blog/7536/jsc-loves-es6/)
      * [Introducing the B3 JIT Compiler](https://webkit.org/blog/5852/introducing-the-b3-jit-compiler/)
  * [Chakra](https://github.com/Microsoft/ChakraCore)
    * [Microsoft Edge’s JavaScript engine to go open-source](https://blogs.windows.com/msedgedev/2015/12/05/open-source-chakra-core/)
    * [Architecture Overview](https://github.com/Microsoft/ChakraCore/wiki/Architecture-Overview)
    * [Node-ChakraCore and VM Neutrality in Node.js](https://blogs.windows.com/msedgedev/2016/11/29/node-chakracore-vm-neutrality/)
    * Internal
      * JavaScript performance updates - [2015](https://blogs.windows.com/msedgedev/2015/05/20/delivering-fast-javascript-performance-in-microsoft-edge), [2016](https://blogs.windows.com/msedgedev/2016/06/22/javascript-performance-updates-anniversary-update/), [2017](https://blogs.windows.com/msedgedev/2017/04/20/improved-javascript-performance-webassembly-shared-memory/)
    * Next Generation
      * [Roadmap](https://github.com/Microsoft/ChakraCore/wiki/Roadmap)
  * [SpiderMonkey](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey)
    * [The monkeys in 2013](https://blog.mozilla.org/javascript/2014/01/23/the-monkeys-in-2013/)
  * Benchmarks
    * [The truth about traditional JavaScript benchmarks](http://benediktmeurer.de/2016/12/16/the-truth-about-traditional-javascript-benchmarks/)
    * [Browser Benchmarks](http://browserbench.org/)
* Web Runtime / JS Runtime
  * [Electron](https://electron.atom.io/)
    * Tutorials - [Essential Electron](http://jlord.us/essential-electron/)
  * [Cordova](https://cordova.apache.org/)
    * [Platform Support](https://cordova.apache.org/docs/en/latest/guide/support/index.html)
    * [Top Mistakes by Developers new to Cordova/Phonegap](https://github.com/jessemonroy650/top-phonegap-mistakes/blob/master/new-to-Phonegap.md)
    * Curated Plugins - [Awesome Cordova Plugins](https://github.com/rdn87/awesome-cordova-plugins#list-plugins)
    * Finding Plugins - [plugreg](http://www.plugreg.com/) / [Plugin Search](https://cordova.apache.org/plugins/)
  * [React Native](http://facebook.github.io/react-native/) / [NativeScript](https://www.nativescript.org/) / [Weex](https://weex-project.io/)
    * [React Native Styling Cheat Sheet](https://github.com/vhpoet/react-native-styling-cheat-sheet)
    * [Bridging in React Native - An in-depth look into React Native's core](https://tadeuzagallo.com/blog/react-native-bridge/)
    * Tutorials - [React Native Express](http://www.reactnativeexpress.com/), [React Native Workshop](https://rangle-io.gitbooks.io/react-native-workshop/), [React Native Training](https://unbug.gitbooks.io/react-native-training/content/)
    * Examples - [30 Days of React Native](https://github.com/fangwei716/30-days-of-react-native)
* Device
  * [The Ultimate Guide To iPhone Resolutions](https://www.paintcodeapp.com/news/ultimate-guide-to-iphone-resolutions)
  * [Device Metrics](https://material.io/devices/) / [Screen Sizes](http://screensiz.es/monitor)

\>\> Return to [Table of Contents](#table-of-contents)

### Cross-browser / Polyfill Libraries

* Appearance
  * Responsive Web Design
    * Media Queries - [Enquire.js](https://www.npmjs.com/package/enquire.js)
    * Responsive Image - [Picturefill](https://www.npmjs.com/package/picturefill)
    * [Viewport Units Buggyfill](https://www.npmjs.com/package/viewport-units-buggyfill)
  * Web Typography
    * `@font-face` - [Font Face Observer](https://www.npmjs.com/package/fontfaceobserver)
  * Web Animation API
    * [Web Animations Polyfill](https://www.npmjs.com/package/web-animations-js)
  * Web Components
    * [webcomponents.js (v1 spec polyfills)](https://github.com/webcomponents/webcomponentsjs) / [Polymer](https://www.polymer-project.org/)
* Interaction
  * Keyboard - [Mousetrap](https://craig.is/killing/mice)
  * `scroll-behavior: smooth;` - [Smoothscroll Polyfill](https://www.npmjs.com/package/smoothscroll-polyfill)
  * PointerEvent - [PEP](https://www.npmjs.com/package/pepjs) / [React Pointable](https://www.npmjs.com/package/react-pointable)
  * [ResizeObserver Polyfill](https://github.com/que-etc/resize-observer-polyfill)
* Access
  * Web Notifications API - [Push.js](https://www.npmjs.com/package/push.js) / [Notify.js](https://www.npmjs.com/package/notifyjs)
  * Clipboard API - [Clipboard.js](https://www.npmjs.com/package/clipboard) / [copy-to-clipboard](https://www.npmjs.com/package/copy-to-clipboard)
  * Fullscreen API - [Screenfull](https://www.npmjs.com/package/screenfull)
  * Page Visibility API - [Visibility.js](https://www.npmjs.com/package/visibilityjs)
  * `<iframe>` - [iframe-resizer](https://www.npmjs.com/package/iframe-resizer)
* Network
  * XHR - [window.fetch Polyfill](https://github.com/github/fetch)
  * Server-Sent Events - [EventSource Polyfill](https://github.com/amvtek/EventSource)
  * WebSocket - [Socket.IO-client](https://www.npmjs.com/package/socket.io-client) / [Engine.IO-client](https://www.npmjs.com/package/engine.io-client) / [SockJS-client](https://www.npmjs.com/package/sockjs-client)
* Performance
  * Web Worker - [Greenlet](https://github.com/developit/greenlet) / [Workerize](https://github.com/developit/workerize)
  * `document-write` - [PostScribe](https://www.npmjs.com/package/postscribe)
  * User Timing API - [marky](https://www.npmjs.com/package/marky)
* Offline
  * Service Work - [Workbox](https://developers.google.com/web/tools/workbox/)
  * File / FileReader API
    * [FileSaver.js](https://www.npmjs.com/package/file-saver) / [StreamSaver.js](https://github.com/jimmywarting/StreamSaver.js)
    * [blob-util](https://www.npmjs.com/package/blob-util)
  * IndexedDB
    * LocalStorage API - [localForage](https://www.npmjs.com/package/localforage)
* Media
  * `<video>` - [Video.js](http://videojs.com/)
  * `<audio>` - [Howler.js](https://howlerjs.com/)
  * Web Audio API - [Waud.js](http://www.waudjs.com/), [Tone.js](https://tonejs.github.io/)

\>\> Return to [Table of Contents](#table-of-contents)

### npm Ecosystem

* [npm](https://www.npmjs.com/)
  * [how many npm users are there?](http://blog.npmjs.org/post/143451680695/how-many-npm-users-are-there), [Module Counts](http://www.modulecounts.com/)
  * [Why not to use version control hosting for packages](http://blog.npmjs.org/post/154387331670/the-right-tool-for-the-job-why-not-to-use-version)
  * [npm and front-end packaging](http://blog.npmjs.org/post/101775448305/npm-and-front-end-packaging)
  * [changes to npm’s unpublish policy](http://blog.npmjs.org/post/141905368000/changes-to-npms-unpublish-policy), [kik, left-pad, and npm](http://blog.npmjs.org/post/141577284765/kik-left-pad-and-npm)
  * [Hello, Yarn!](http://blog.npmjs.org/post/151660845210/hello-yarn)
* Finding Packages
  * Search
    * [npms.io](https://npms.io/) / [node-modules.com](http://node-modules.com/) / [npmsearch.com](http://npmsearch.com/)
      * [improved search in the npm CLI (and how we got here)](http://blog.npmjs.org/post/156076312840/search-update), \
        [Better search is here!](http://blog.npmjs.org/post/154912817335/better-search-is-here)
    * [Github Search (sort by stars, for JS)](https://github.com/search?l=JavaScript&q=stars%3A%3E1&s=stars&type=Repositories)
  * Stats
    * [npm trends](http://www.npmtrends.com/)
    * [NPMCompare](https://npmcompare.com/)
    * [npm-stat](https://npm-stat.com/)
  * Rank
    * [The State Of JavaScript](http://stateofjs.com/), \
      [Stack Overflow Annual Developer Survey](https://insights.stackoverflow.com/survey)
    * npm's [most depended-upon packages](https://www.npmjs.com/browse/depended)
* Dependency Management / Release / Maintenance
  * [npm Developer Guide](https://docs.npmjs.com/misc/developers)
    * [npm's CLI](https://docs.npmjs.com/#cli)
    * [v5.0.0](http://blog.npmjs.org/post/161081169345/v500)
    * [npm’s lockfiles](http://blog.npmjs.org/post/161627993435/learn-more-about-npms-lockfiles)
  * [Yarn](https://yarnpkg.com/)
    * [yarn's CLI](https://yarnpkg.com/en/docs/cli/)
    * [yarn.lock](https://yarnpkg.com/en/docs/yarn-lock)
  * [Lerna](https://lernajs.io/)
  * [semantic-release](https://www.npmjs.com/package/semantic-release) / [np](https://www.npmjs.com/package/np), [gh-release](https://www.npmjs.com/package/gh-release)
  * [npm-check-updates](https://www.npmjs.com/package/npm-check-updates)
  * [check-dependencies](https://www.npmjs.com/package/check-dependencies)
  * [changed-log](https://www.npmjs.com/package/changed-log)
  * [license-checker](https://www.npmjs.com/package/license-checker)
* Convention
  * Open Source
    * README
      * [Art of README](https://github.com/noffle/art-of-readme), [How To Write A Readme](http://jfhbrook.github.io/2011/11/09/readmes.html)
      * [Top ten reasons why I won't use your open source project](https://changelog.com/posts/top-ten-reasons-why-i-wont-use-your-open-source-project)
      * [Readme Driven Development](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html)
      * Template - [Common Readme](https://github.com/noffle/common-readme) / [Standard Readme](https://github.com/RichardLitt/standard-readme) / [Zalando's README Template](https://github.com/zalando/zalando-howto-open-source/blob/master/READMEtemplate.md)
    * Changelog
      * [Conventional Commits](https://conventionalcommits.org/)
      * [Conventional Changelog](https://github.com/conventional-changelog/conventional-changelog)
      * [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/)
    * License
      * [Choose an open source license](https://choosealicense.com/)
  * SemVer
    * [SemVer (Semantic Versioning)](http://semver.org/) / [The semantic versioner for npm](https://docs.npmjs.com/misc/semver) / [Semver: A Primer](https://nodesource.com/blog/semver-a-primer/)
    * [npm semver calculator](https://semver.npmjs.com/)
  * package.json
    * [Specifics of npm's package.json](https://docs.npmjs.com/files/package.json)
    * [Specifics of yarn's package.json](https://yarnpkg.com/en/docs/package-json)
    * [What's the difference between dependencies, devDependencies and peerDependencies](http://stackoverflow.com/questions/18875674/whats-the-difference-between-dependencies-devdependencies-and-peerdependencies)
  * Small Modules
    * [Unix Philosophy and Node.js](http://blog.izs.me/post/48281998870/unix-philosophy-and-nodejs)
    * [module best practices](https://github.com/mattdesl/module-best-practices)
    * [how I write modules](http://substack.net/how_I_write_modules)
    * Hyper Modular / One-line Modules
      * [Small focused modules](https://github.com/sindresorhus/ama/issues/10#issuecomment-117766328)
      * [Hyper Modular Packages: A Crazy Cult or a Reasonable Practice?](http://thefullstack.xyz/hyper-modular-packages-a-crazy-cult-or-a-reasonable-practice/)
      * [In Defense of Hyper Modular JavaScript](https://medium.freecodecamp.com/in-defense-of-hyper-modular-javascript-33934c79e113)
  * Isomorphic JS / Universal JS
    * [Isomorphic JavaScript: The Future of Web Apps](https://medium.com/airbnb-engineering/isomorphic-javascript-the-future-of-web-apps-10882b7a2ebc)
    * [Universal JavaScript](https://medium.com/@mjackson/universal-javascript-4761051b7ae9)

\>\> Return to [Table of Contents](#table-of-contents)

### Universal Utility Libraries

* Standard Library Extensions
  * Utilities
    * [Lodash](https://lodash.com)
    * [is.js](http://is.js.org/)
  * FP
    * [Ramda](http://ramdajs.com/)
      * [ramda-fantasy](https://www.npmjs.com/package/ramda-fantasy)
    * Immutable
      * [immutability-helper](https://www.npmjs.com/package/immutability-helper) + [redux-immutable-state-invariant](https://www.npmjs.com/package/redux-immutable-state-invariant) / [redux-freeze](https://www.npmjs.com/package/redux-freeze)
      * [icepick](https://www.npmjs.com/package/icepick) / [seamless-immutable](https://www.npmjs.com/package/seamless-immutable) / [dot-prop-immutable](https://www.npmjs.com/package/dot-prop-immutable) / [object-path-immutable](https://www.npmjs.com/package/object-path-immutable) / [timm](https://www.npmjs.com/package/timm) / [updeep](https://www.npmjs.com/package/updeep)
      * [ImmutableJS](http://facebook.github.io/immutable-js/)
  * OOP
    * [lodash-decorators](https://www.npmjs.com/package/lodash-decorators)
    * [Stampit](https://www.npmjs.com/package/stampit)
  * Async
    * Observable - [RxJS](https://www.npmjs.com/package/rxjs)
    * Promise - [es6-promisify](https://www.npmjs.com/package/es6-promisify), [Bluebird](http://bluebirdjs.com/docs/features.html)
    * Generator - [Co](https://www.npmjs.com/package/co)
    * Callback - [Async](http://caolan.github.io/async/)
  <!-- * Concurrent / Parallel -->
  * Syntax
    * [XRegExp](https://www.npmjs.com/package/xregexp)
  * Node.js API
    * [node-libs-browser](https://www.npmjs.com/package/node-libs-browser)
    * [EventEmitter3](https://www.npmjs.com/package/eventemitter3)
  * Debugging
    * [debug](https://www.npmjs.com/package/debug) / [pino](https://www.npmjs.com/package/pino)
* Hashing / Generating
  * [uuid](https://www.npmjs.com/package/uuid) / [cuid](http://usecuid.org)
  * [shortid](https://www.npmjs.com/package/shortid) / [punycode](https://www.npmjs.com/package/punycode) / [string-hash](https://www.npmjs.com/package/string-hash)
  * [base64-js](https://www.npmjs.com/package/base64-js) / [sha.js](https://www.npmjs.com/package/sha.js) / [spark-md5](https://www.npmjs.com/package/spark-md5) / [crypto-js](https://www.npmjs.com/package/crypto-js) / [jsrsasign](https://www.npmjs.com/package/jsrsasign)
* Parsing / Manipulating
  * URL
    * URL Parsing - [qs](https://www.npmjs.com/package/qs), [URI.js](https://github.com/medialize/URI.js)
    * IP Address Manipulation - [ip](https://www.npmjs.com/package/ip)
  * Environment
    * UA Sniffing - [UAParser.js](https://github.com/faisalman/ua-parser-js) / [useragent](https://www.npmjs.com/package/useragent)
    * Information - [platform.js](https://www.npmjs.com/package/platform)
    * Runtime Detection - [is-electron-renderer](https://www.npmjs.com/package/is-electron-renderer) / [electron-is](https://www.npmjs.com/package/electron-is)
  * Validator
    * String Validation - [validator.js](https://github.com/chriso/validator.js)
    * Schema Validation - [joi](https://www.npmjs.com/package/joi) / [Ajv](http://epoberezkin.github.io/ajv/)
  * i18n
    * [Intl.js](https://www.npmjs.com/package/intl) + [FormatJS](https://formatjs.io/guides/) / [i18next](https://www.i18next.com/)
  * Date
    * Date Manipulation - [Moment.js](http://momentjs.com)
  * Numbers
    * Number Manipulation - [Numeral.js](http://numeraljs.com/)
    * Money - [accounting.js](http://openexchangerates.github.io/accounting.js/)
  * Color
    * Color Manipulation - [Chroma.js](http://gka.github.io/chroma.js/), [Chromatism](https://www.npmjs.com/package/chromatism), [randomColor](https://www.npmjs.com/package/randomcolor)
    * Color Extraction - [node-vibrant](https://www.npmjs.com/package/node-vibrant) / [Colorify.js](http://colorify.rocks/)
  * Text
    * Text Manipulation - [Voca.js](https://vocajs.com) / [string.js](https://github.com/jprichardson/string.js)
    * Characters - [string-width](https://www.npmjs.com/package/string-width), [string-length](https://www.npmjs.com/package/string-length)
    * HTML Entities - [he](https://www.npmjs.com/package/he)
    * Human-readable Slug - [speakingurl](https://www.npmjs.com/package/speakingurl)
    * XSS Sanitizer - [DOMPurify](https://www.npmjs.com/package/dompurify) / [xss](https://www.npmjs.com/package/xss)
    * HTTP - [mime-types](https://www.npmjs.com/package/mime-types), [content-type](https://www.npmjs.com/package/content-type)
    * JSON Superset - [serialize-javascript](https://www.npmjs.com/package/serialize-javascript), [JSON5](https://www.npmjs.com/package/json5)
    * Markdown - [marked](https://www.npmjs.com/package/marked) / [markdown-it](https://www.npmjs.com/package/markdown-it)
      * [CommonMark](http://commonmark.org/), [A formal spec for GitHub Flavored Markdown](https://githubengineering.com/a-formal-spec-for-github-markdown/)
    * Links Recognition - [linkify-it](https://www.npmjs.com/package/linkify-it)
    * Language Detection - [franc](https://www.npmjs.com/package/franc)
    * Text Differencing - [diff](https://www.npmjs.com/package/diff)
    * JSON Differencing - [deep-diff](https://www.npmjs.com/package/deep-diff)
    * Search - [Fuse.js](http://fusejs.io/) / [fuzzysearch](https://www.npmjs.com/package/fuzzysearch) / [Lunr.js](https://lunrjs.com) / [js-worker-search](https://www.npmjs.com/package/js-worker-search), [regexgen](https://www.npmjs.com/package/regexgen) / [escape-string-regexp](https://www.npmjs.com/package/escape-string-regexp)
    * DSL Parser - [PEG.js](https://pegjs.org/) / [nearley](http://nearley.js.org/)
  * Buffer / Blob
    * Type Detection - [file-type](https://www.npmjs.com/package/file-type), [image-type](https://www.npmjs.com/package/image-type)
    * Size Detection - [probe-image-size](https://www.npmjs.com/package/probe-image-size)
    * Image Manipulation - [jimp](https://www.npmjs.com/package/jimp)
      * Image Crop - [Smartcrop.js](https://www.npmjs.com/package/smartcrop)
    * QR Code / Barcode - [qrcode](https://www.npmjs.com/package/qrcode) / [jsbarcode](https://www.npmjs.com/package/jsbarcode)
* Logic
  * Rate Limiter - [Bottleneck](https://www.npmjs.com/package/bottleneck) / [Limiter](https://www.npmjs.com/package/limiter)
* Network
  * HTTP / XHR
    * Low-level - [Isomorphic Fetch](https://github.com/matthew-andrews/isomorphic-fetch)
    * High-level
      * Based on XHR - [Axios](https://www.npmjs.com/package/axios)
      * Based on Fetch API - [hifetch](https://github.com/dexteryy/Project-WebCube/blob/master/packages/hifetch)
    * GraphQL - [lokka](https://github.com/kadirahq/lokka)
  * TCP
    * [MQTT](https://www.npmjs.com/package/mqtt)
  * UDP / P2P
    * [Simple Peer](https://www.npmjs.com/package/simple-peer) / [JS SIP](https://www.npmjs.com/package/jssip)
    * [WebTorrent](https://www.npmjs.com/package/webtorrent)
* Storage
  * File Database
    * JSON - [Lowdb](https://www.npmjs.com/package/lowdb)
  * IndexedDB / WebSQL / localStorage / Memory
    * MongoDB API - [NeDB](https://www.npmjs.com/package/nedb)
    * CouchDB API - [PouchDB](https://pouchdb.com)
  * Realtime / P2P - [Gun](https://www.npmjs.com/package/gun), [ShareDB](https://www.npmjs.com/package/sharedb)
* Computation
  * [Math.js](http://mathjs.org/), [Simple Statistics](https://simplestatistics.org/), [ndarray](https://www.npmjs.com/package/ndarray), [bignumber.js](http://mikemcl.github.io/bignumber.js/)
* NLP
  * [compromise](https://github.com/nlp-compromise/compromise) / [talisman](http://yomguithereal.github.io/talisman/)
* ML/DL
  * [TensorFlow.js](https://js.tensorflow.org/)
  * [MLJS](https://www.npmjs.com/package/ml), [Synaptic](https://www.npmjs.com/package/synaptic)

\>\> Return to [Table of Contents](#table-of-contents)

## Universal Web Apps / Web Pages

### GUI Framework

* View / ViewModel / ViewController
  * [React](https://facebook.github.io/react/)
    * Learning
      * Pete Hunt's [react-howto](https://github.com/petehunt/react-howto)
      * [React - Basic Theoretical Concepts](https://github.com/reactjs/react-basic)
      * [Under the hood: ReactJS](https://bogdan-lyashenko.github.io/Under-the-hood-ReactJS/)
      * [SurviveJS React](https://survivejs.com/react/introduction/) / [React Express](http://www.react.express/)
      * [React Cheat Sheet](https://reactcheatsheet.com/)
      * Best Practices
        * [React Bits](https://github.com/vasanthk/react-bits), [React in patterns](https://github.com/krasimir/react-in-patterns)
        * [Functional UI and Components as Higher Order Functions](https://blog.risingstack.com/functional-ui-and-components-as-higher-order-functions/)
      * Next Gen - [What is React Fiber?](https://gist.github.com/duivvv/2ba00d413b8ff7bc1fa5a2e51c61ba43), [React 16](https://github.com/facebook/react/issues/10294)
    * Component Utilities
      * [Recompose](https://github.com/acdlite/recompose)
      * [React Display Name](https://www.npmjs.com/package/react-display-name)
      * [React Side Effect](https://www.npmjs.com/package/react-side-effect)
      * [React Komposer](https://www.npmjs.com/package/react-komposer)
      * [React Loadable](https://www.npmjs.com/package/react-loadable)
      * [React CSS Themr](https://www.npmjs.com/package/react-css-themr)
    * Browser Utilities
      * [React Event Listener](https://www.npmjs.com/package/react-event-listener)
      * [React onClickOutside](https://www.npmjs.com/package/react-onclickoutside)
      * [React Responsive](https://www.npmjs.com/package/react-responsive)
      * [React Sizeme](https://www.npmjs.com/package/react-sizeme) / [React Dimensions](https://www.npmjs.com/package/react-dimensions)
      * [React Portal](https://www.npmjs.com/package/react-portal) / [React Gateway](https://www.npmjs.com/package/react-gateway)
      * [React Measure](https://www.npmjs.com/package/react-measure)
      * [React Copy to clipboard](https://www.npmjs.com/package/react-copy-to-clipboard)
      * [React Cookie](https://www.npmjs.com/package/react-cookie)
    * Use React Alone
      * [Redial](https://www.npmjs.com/package/redial) / [React Refetch](https://www.npmjs.com/package/react-refetch)
      * [formik](https://www.npmjs.com/package/formik) / [Formsy React](https://www.npmjs.com/package/formsy-react)
    * Lightweight Alternative
      * [Preact](https://preactjs.com/) / [Inferno](https://infernojs.org/)
  * [Angular](https://angular.io/)
  * [Vue.js](https://vuejs.org/)
  * Cross-framework
    * [vuera](https://github.com/akxcv/vuera)
* Model / App State
  * [Redux](http://redux.js.org/)
    * Learning
      * [Notes of Dan Abramov's Redux course videos](https://github.com/tayiorbeii/egghead.io_redux_course_notes)
      * [A cartoon intro to Redux](https://code-cartoons.com/a-cartoon-intro-to-redux-3afb775501a6)
      * [Tic-Tac-Toe.js: redux pattern in plain JavaScript](http://ramonvictor.github.io/tic-tac-toe-js/)
    * Reduce Boilerplate
      * [redux-cube](https://github.com/dexteryy/Project-WebCube/tree/master/packages/redux-cube) (Author's own project)
    * Connect
      * [react-redux](https://www.npmjs.com/package/react-redux)
      * [reselect](https://www.npmjs.com/package/reselect)
    * Action Types, Action Creators, Reducer Switch
      * [redux-actions](https://www.npmjs.com/package/redux-actions)
      * [flux-standard-action](https://www.npmjs.com/package/flux-standard-action)
      * [topologically-combine-reducers](https://www.npmjs.com/package/topologically-combine-reducers)
    * Asnyc Actions
      * [redux-thunk](https://www.npmjs.com/package/redux-thunk) + [redux-promise-middleware](https://www.npmjs.com/package/redux-promise-middleware) + [redux-debounced](https://www.npmjs.com/package/redux-debounced)
      * [redux-observable](https://www.npmjs.com/package/redux-observable)
      * [redux-saga](https://github.com/redux-saga/redux-saga)
      * [redux-api-middleware](https://www.npmjs.com/package/redux-api-middleware) / [redux-axios-middleware](https://www.npmjs.com/package/redux-axios-middleware) / [redux-socket.io](http://npmjs.com/redux-socket.io)
      * [redux-rest-resource](https://www.npmjs.com/package/redux-rest-resource)  / [redux-json-api](https://www.npmjs.com/package/redux-json-api) / [redux-api](https://www.npmjs.com/package/redux-api)
    * State
      * [normalizr](https://www.npmjs.com/package/normalizr)
      * Immutalbe - see _[Universal Utility Libraries](#universal-utility-libraries) > Standard Library Extensions > FP > Immutable_
      * [redux-immutable](https://www.npmjs.com/package/redux-immutable)
      * [redux-persist](https://www.npmjs.com/package/redux-persist)
      * [redux-undo](https://www.npmjs.com/package/redux-undo)
      * [redux-reset](https://www.npmjs.com/package/redux-reset)
    * UI Patterns
      * [redux-form](https://redux-form.com/)
      * [react-block-ui](https://www.npmjs.com/package/react-block-ui) / [react-redux-loading-bar](https://www.npmjs.com/package/react-redux-loading-bar)
      * [react-notification-system-redux](https://www.npmjs.com/package/react-notification-system-redux) / [react-redux-toastr](https://www.npmjs.com/package/react-redux-toastr)
      * [redux-optimistic-ui](https://www.npmjs.com/package/redux-optimistic-ui)
    * App Behaviours
      * [redux-auth-wrapper](https://www.npmjs.com/package/redux-auth-wrapper)
      * [react-intl-redux](https://www.npmjs.com/package/react-intl-redux)
      * [Redux Search](https://www.npmjs.com/package/redux-search)
    * Development
      * [redux-devtools-extension](https://www.npmjs.com/package/redux-devtools-extension)
      * [redux-logger](https://www.npmjs.com/package/redux-logger)
      * Testing - see _[Testing](#testing) > Web Testing > Integration Testing_
  * [MobX](https://mobx.js.org)
  * [Baobab](https://www.npmjs.com/package/baobab) / [Freezer](https://www.npmjs.com/package/freezer-js)
* API / Data Source
  * [GraphQL](http://graphql.org/)
    * Learning
      * [Queries and Mutations](http://graphql.org/learn/queries/)
      * Playground - [GraphQLHub](https://www.graphqlhub.com/), [Explore GraphQL](https://www.graphql.com/tutorials/)
    * State Management
      * [Apollo Client](https://www.apollographql.com/client/)
      * [redux-source](https://github.com/dexteryy/Project-WebCube/tree/master/packages/redux-source) (Author's own project)
    * [graphql-anywhere](https://www.npmjs.com/package/graphql-anywhere)
    * [graphql-tools](http://dev.apollodata.com/tools/graphql-tools/index.html)
* Offline First
  * Learning
    * [Designing Offline-First Web Apps](https://alistapart.com/article/offline-first)
    * [Say Hello to Offline First](http://hood.ie/blog/say-hello-to-offline-first.html), \
      [Offline First and the Circle Of Web](http://hood.ie/blog/offline-first-and-the-circle-of-web.html), [Part II: Breaking the Circle](http://hood.ie/blog/offline-first-and-the-circle-of-web-part-ii-breaking-the-circle.html)
* Routing
  * [React Router](https://reacttraining.com/react-router/)
  * [Connected React Router](https://github.com/supasate/connected-react-router)
  * [React Helmet](https://www.npmjs.com/package/react-helmet)
* i18n
  * [React Intl](https://github.com/yahoo/react-intl) / [React i18next](https://react.i18next.com)
  * [React Intl Redux](https://www.npmjs.com/package/react-intl-redux)
* Monitoring / Error Capture
  * [react-ga](https://www.npmjs.com/package/react-ga)
  * [redux-segment](https://www.npmjs.com/package/redux-segment)
  * [redux-raven-middleware](https://www.npmjs.com/package/redux-raven-middleware) / [raven-for-redux](https://www.npmjs.com/package/raven-for-redux)
  * [redux-catch](https://www.npmjs.com/package/redux-catch)
  * [redux-beacon](https://www.npmjs.com/package/redux-beacon)
  * Services - see _[Tooling > Workflow](#workflow) > Monitoring_
* Debugging
  * [why-did-you-update](https://www.npmjs.com/package/why-did-you-update)
* Server-side Rendering
  * see _[Tooling > Workflow](#workflow) > Deployment > Publishing App_
* Static Web
  * [JAMstack](https://jamstack.org/)
  * see _[Tooling > Workflow](#workflow) > Deployment > Publishing App_
* Scaffold / Boilerplate / Generator
  * [create-react-app](https://github.com/facebookincubator/create-react-app) / [angular-cli](https://cli.angular.io/) / [vue-cli](https://www.npmjs.com/package/vue-cli)
  * [Next.js](https://github.com/zeit/next.js)
  * [webcube](https://github.com/dexteryy/Project-WebCube) (Author's own project)
  * [Starter Kits Recommended by the React Team](https://reactjs.org/community/starter-kits.html)
  * [JavaScript Stack from Scratch](https://github.com/verekia/js-stack-from-scratch)
  * Static Site Generator - [Gatsby](https://www.gatsbyjs.org/) / [Metalsmith](http://www.metalsmith.io/) / [Hexo](https://hexo.io/) / [Assemble](http://assemble.io/)
* GUI Architectures
  * Comparison
    * [Scaling Isomorphic JavaScript Code](https://blog.nodejitsu.com/scaling-isomorphic-javascript-code/)
    * [Comparison of Architecture presentation patterns MVP(SC),MVP(PV),PM,MVVM and MVC](https://www.codeproject.com/Articles/66585/Comparison-of-Architecture-presentation-patterns-M)
    * [Unidirectional User Interface Architectures](https://staltz.com/unidirectional-user-interface-architectures.html)
    * [Change And Its Detection In JavaScript Frameworks](http://teropa.info/blog/2015/03/02/change-and-its-detection-in-javascript-frameworks.html)
    * [Martin Fowler's eaaDev](https://martinfowler.com/eaaDev/)
  * [Patterns For Large-Scale JavaScript Application Architecture](https://addyosmani.com/largescalejavascript/)
  * MVC - [A](https://alexatnet.com/model-view-controller-mvc-in-javascript/), [B](https://developer.mozilla.org/en-US/Apps/Fundamentals/Modern_web_app_architecture/MVC_architecture), [C](https://developer.chrome.com/apps/app_frameworks)
  * [Understanding MVC And MVP (For JavaScript And Backbone Developers)](https://addyosmani.com/blog/understanding-mvc-and-mvp-for-javascript-and-backbone-developers/)
  * [Understanding MVVM - A Guide For JavaScript Developers](https://addyosmani.com/blog/understanding-mvvm-a-guide-for-javascript-developers/)
  * [Flux Concepts](https://github.com/facebook/flux/tree/master/examples/flux-concepts)
    * [Flux - In Depth Overview](http://facebook.github.io/flux/docs/in-depth-overview.html)
  * [Redux - Reinventing Flux - Interview with Dan Abramov](https://survivejs.com/blog/redux-interview/)
  * [The Elm Architecture](https://guide.elm-lang.org/architecture/)
  * [MVI (Model-View-Intent) in Cycle.js](https://cycle.js.org/model-view-intent.html)
    * [What Developers Need to Know about MVI (Model-View-Intent)](https://thenewstack.io/developers-need-know-mvi-model-view-intent/)
  * [SAM (State-Action-Model)](http://sam.js.org/)

\>\> Return to [Table of Contents](#table-of-contents)

### UI Toolkits

* CSS
  * [Skeleton.css](http://getskeleton.com/)
  * [Tachyons](http://tachyons.io/)
  * [Bulma](http://bulma.io/)
  * [Material Components for the web](https://github.com/material-components/material-components-web)
  * [WeUI](https://github.com/weui/weui)
  * [MJML](https://mjml.io/) / [Foundation for Emails 2](http://foundation.zurb.com/emails.html)
* React
  * [Reactstrap](https://reactstrap.github.io/) / [React Bootstrap](https://www.npmjs.com/package/react-bootstrap)
  * [Material-UI](http://www.material-ui.com) / [React Toolbox](http://react-toolbox.com/)
  * [Ant Design](https://ant.design/) / [Ant Design Mobile](https://mobile.ant.design/)
  * [Rebass](http://jxnblk.com/rebass/)
  * [Blueprint](http://blueprintjs.com/)
  * [Semantic UI React](https://react.semantic-ui.com)
  * [React Foundation](https://react.foundation/)
  * [React WeUI](https://weui.github.io/react-weui/docs/)
  * [React Desktop](http://reactdesktop.js.org/)
  * [React Native Web](https://www.npmjs.com/package/react-native-web)

\>\> Return to [Table of Contents](#table-of-contents)

### Standalone UI Components

* Layout
  * Grid - [React FlexBox Grid](http://roylee0704.github.io/react-flexbox-grid/)
  * Masonry - [React Masonry Component](https://www.npmjs.com/package/react-masonry-component) / [masonry-layout](https://www.npmjs.com/package/masonry-layout) / [bricks.js](https://www.npmjs.com/package/bricks.js) / [Justified Layout](http://flickr.github.io/justified-layout/)
  * Split - [React Split Pane](https://www.npmjs.com/package/react-split-pane) / [Split.js](http://nathancahill.github.io/Split.js/)
  * Dashboard - [React Grid Layout](https://www.npmjs.com/package/react-grid-layout)
* Icon
  * [React Icons](https://www.npmjs.com/package/react-icons) / [Material Design Icons](http://google.github.io/material-design-icons/) / [Bytesize Icons](https://www.npmjs.com/package/bytesize-icons)
* Progress
  * [React Redux Loading Bar](https://www.npmjs.com/package/react-redux-loading-bar) / [NProgress](https://www.npmjs.com/package/nprogress)
* Button
  * [Buttons](http://unicorn-ui.com/buttons/)
  * Indicators - [React Ladda](https://www.npmjs.com/package/react-ladda) / [Ladda](http://lab.hakim.se/ladda/) / [React Progress Button](https://www.npmjs.com/package/react-progress-button)
* Accordion
  * [React Collapse](https://www.npmjs.com/package/react-collapse) / [React Sanfona](https://www.npmjs.com/package/react-sanfona)
* Picker
  * [React Tabs](https://www.npmjs.com/package/react-tabs)
  * [React Select](http://jedwatson.github.io/react-select/)
  * [React Radio Group](https://www.npmjs.com/package/react-radio-group)
  * [RC Slider](https://www.npmjs.com/package/rc-slider) / [React Slider](https://www.npmjs.com/package/react-slider) / [React Input Range](https://www.npmjs.com/package/react-input-range)
  * [React Color](http://casesandberg.github.io/react-color/)
  * [React Dates](https://www.npmjs.com/package/react-dates) / [React Datepicker](https://hacker0x01.github.io/react-datepicker/) / [React Day Picker](http://react-day-picker.js.org/) / [Pikaday](https://www.npmjs.com/package/pikaday) / [React Datetime](https://www.npmjs.com/package/react-datetime)
* Input
  * [React Toggle](https://www.npmjs.com/package/react-toggle)
  * [React Input Autosize](https://www.npmjs.com/package/react-input-autosize), [React Textarea Autosize](https://www.npmjs.com/package/react-textarea-autosize)
  * [React Tag Input](https://www.npmjs.com/package/react-tagsinput)
  * [React Autosuggest](https://www.npmjs.com/package/react-autosuggest)
  * Auto-formatting - [React MaskedInput](https://www.npmjs.com/package/react-maskedinput) / [React Text Mask](https://www.npmjs.com/package/react-text-mask) / [Cleave.js](https://www.npmjs.com/package/cleave.js)
* Form
  * [React JSON Schema Form](https://www.npmjs.com/package/react-jsonschema-form)
* Overlay
  * [React Modal](https://www.npmjs.com/package/react-modal) / [SweetAlert2](https://www.npmjs.com/package/sweetalert2) / [vex](https://www.npmjs.com/package/vex-js)
  * [React Overlays](https://www.npmjs.com/package/react-overlays)
  * [React Notification System](https://github.com/igorprado/react-notification-system) / [react-notification-system-redux](https://www.npmjs.com/package/react-notification-system-redux) /\
    [React Redux Toastr](https://www.npmjs.com/package/react-redux-toastr) / [React Notification](https://www.npmjs.com/package/react-notification) / [React sAlert](https://www.npmjs.com/package/react-s-alert) / [Notie](https://www.npmjs.com/package/notie)
  * Drawer - [React Burger Menu](http://negomi.github.io/react-burger-menu/) / [React Sidebar](https://www.npmjs.com/package/react-sidebar) / [React Dock](https://www.npmjs.com/package/react-dock)
  * [React ContextMenu](https://www.npmjs.com/package/react-contextmenu)
  * [React Block UI](https://availity.github.io/react-block-ui/)
* Content
  * Carousel - [React Slick](https://www.npmjs.com/package/react-slick) / [Nuka Carousel](https://www.npmjs.com/package/nuka-carousel)
  * [React Paginate](https://www.npmjs.com/package/react-paginate)
  * [React Rating](https://www.npmjs.com/package/react-rating)
  * List / Table - [React Virtualized](https://www.npmjs.com/package/react-virtualized) / [React Table](https://www.npmjs.com/package/react-table) / [React List](https://www.npmjs.com/package/react-list)
  * Spreadsheet - [React Data Grid](http://adazzle.github.io/react-data-grid/) / [React Handsontable](https://www.npmjs.com/package/react-handsontable) / [React Datasheet](https://nadbm.github.io/react-datasheet/)
  * TreeView - [React Treebeard](https://www.npmjs.com/package/react-treebeard) / [React TreeView](https://www.npmjs.com/package/react-treeview)
  * JSON Viewer - [React JSON Tree](https://www.npmjs.com/package/react-json-tree)
  * [React QR Code](https://www.npmjs.com/package/qrcode.react)
  * Email Table - [Oy Vey](https://www.npmjs.com/package/oy-vey)
* Editor
  * [Draft.js](https://draftjs.org/)
    * [Awesome Draft.js](https://github.com/nikgraf/awesome-draft-js)
  * [Slate](https://github.com/ianstormtaylor/slate)
  * [React Quill](https://www.npmjs.com/package/react-quill) / [Quill](https://quilljs.com/)
  * [React Monaco Editor](https://www.npmjs.com/package/react-monaco-editor) / [React Ace](https://www.npmjs.com/package/react-ace) / [React Codemirror](https://www.npmjs.com/package/react-codemirror)
    * [Monaco Editor](https://microsoft.github.io/monaco-editor/) / [Ace](https://ace.c9.io/) / [CodeMirror](https://codemirror.net/)
  * [React Markdown](https://www.npmjs.com/package/react-markdown)
  * [React Syntax Highlighter](https://www.npmjs.com/package/react-syntax-highlighter) / [Highlight.js](https://www.npmjs.com/package/highlight.js)
* Widget
  * [React Music](https://github.com/FormidableLabs/react-music)
  * [React Big Calendar](https://www.npmjs.com/package/react-big-calendar)
  * [React Image Gallery](https://www.npmjs.com/package/react-image-gallery)
  * [React Google Maps](https://www.npmjs.com/package/react-google-maps) / [Google Map React](https://www.npmjs.com/package/google-map-react) / [React Map GL](https://www.npmjs.com/package/react-map-gl)
  * [React Youtube](https://www.npmjs.com/package/react-youtube) / [React Player](https://www.npmjs.com/package/react-player)
  * [Searchkit](http://www.searchkit.co/)
  * [Redux Auth](https://github.com/lynndylanhurley/redux-auth)
  * [SurveyJS](http://surveyjs.org/)

\>\> Return to [Table of Contents](#table-of-contents)

## Client Side

### UX Libraries

* Drag & Drop
  * [React DnD](https://react-dnd.github.io/react-dnd) / [React Draggable](https://www.npmjs.com/package/react-draggable)
  * [React Sortable HOC ](https://www.npmjs.com/package/react-sortable-hoc) / [Sortable](https://github.com/RubaXa/Sortable)
  * [React Dropzone](https://www.npmjs.com/package/react-dropzone) / [DropzoneJS](http://www.dropzonejs.com/)
  * [GSAP - Draggable](https://greensock.com/draggable)
* Gesture
  * [Hammer.js](http://hammerjs.github.io/) / [Interact.js](http://interactjs.io/) / [ZingTouch](https://zingchart.github.io/zingtouch/) / [AlloyFinger](https://github.com/AlloyTeam/AlloyFinger)
    * [Gestures Patterns](https://material.io/guidelines/patterns/gestures.html)
    * [React HammerJS](https://www.npmjs.com/package/react-hammerjs)
  * [React Swipeable Views](https://github.com/oliviertassinari/react-swipeable-views) / [React Swipeable](https://www.npmjs.com/package/react-swipeable) / [Swiper](http://idangero.us/swiper)
* Scrolling
  * Viewport and Elements
    * [React Waypoint](https://www.npmjs.com/package/react-waypoint) / [Waypoints](https://www.npmjs.com/package/waypoints), \
      [React ScrollMonitor](https://www.npmjs.com/package/scrollmonitor-react) / [ScrollMonitor](https://www.npmjs.com/package/scrollmonitor), \
      [React Visibility Sensor](https://www.npmjs.com/package/react-visibility-sensor)
    * [React Sticky](https://www.npmjs.com/package/react-sticky)
    * [React Headroom](https://www.npmjs.com/package/react-headroom) / [Headroom.js](https://www.npmjs.com/package/headroom.js)
    * [React Infinite Scroller](https://www.npmjs.com/package/react-infinite-scroller) / [React Infinite](https://www.npmjs.com/package/react-infinite)
    * [React Lazyload](https://www.npmjs.com/package/react-lazyload)
  * [React Pull to Refresh](https://www.npmjs.com/package/react-pull-to-refresh)
  * Smooth Scrolling - [React Scroll](https://www.npmjs.com/package/react-scroll)
  * Scrollable - [React iScroll](https://www.npmjs.com/package/react-iscroll) / [iScroll](http://iscrolljs.com/) / [Zynga Scroller](http://zynga.github.io/scroller/)
  * Scrollable Container - [React Custom Scrollbars](https://www.npmjs.com/package/react-custom-scrollbars) / [React Scroll Box](https://www.npmjs.com/package/react-scroll-box) / [React Scrollbar](https://www.npmjs.com/package/react-scrollbar) / [Overthrow](https://www.npmjs.com/package/fg-overthrow)
* Zoom
  * Image Loupe - [Drift](https://www.npmjs.com/package/drift-zoom) / [React Image Magnify](https://www.npmjs.com/package/react-image-magnify)
  * Image Viewer - [React Images](https://www.npmjs.com/package/react-images) / [React Image Lightbox](https://www.npmjs.com/package/react-image-lightbox) / [LightGallery](https://www.npmjs.com/package/lightgallery.js) / [SmartPhoto](https://www.npmjs.com/package/smartphoto)
* Crop
  * [React Avatar Editor](https://www.npmjs.com/package/react-avatar-editor) / [React Image Crop](https://www.npmjs.com/package/react-image-crop) / [React Cropper](https://www.npmjs.com/package/react-cropper)
* Resize
  * [React Resizable](https://www.npmjs.com/package/react-resizable)
  * [React RnD](https://www.npmjs.com/package/react-rnd)
* Tooltip
  * [Hint.css](http://kushagragour.in/lab/hint/)
  * [React Tether](https://www.npmjs.com/package/react-tether) / [Tether.js](http://tether.io/) / [Popper.js](https://popper.js.org/), \
    [React Tooltip](https://www.npmjs.com/package/react-tooltip) / [Tether Tooltip](http://github.hubspot.com/tooltip/docs/welcome/) / [Tippy.js](https://atomiks.github.io/tippyjs/)
* Tour
  * [React Joyride](https://www.npmjs.com/package/react-joyride) / [Intro.js](http://introjs.com/) / [tether-shepherd](https://www.npmjs.com/package/tether-shepherd) / [Chardin.js](https://www.npmjs.com/package/chardin.js)
* Accessiblity
  * [React HotKeys](https://www.npmjs.com/package/react-hotkeys)
  * [React A11y](https://www.npmjs.com/package/react-a11y)

\>\> Return to [Table of Contents](#table-of-contents)

### Graphic Libraries

* Animation
  * Effects
    * [Animate.css](https://daneden.github.io/animate.css/) / [Magic Animations](https://minimamente.com/example/magic_animations/) / [All Animation CSS3](http://all-animation.github.io/) / [Motion CSS](http://pavlyukpetr.com/awesome/) / [Effeckt.css](http://h5bp.github.io/Effeckt.css/) / [CSS3 Animation Cheat Sheet](http://justinaguilar.com/animations/index.html)
      * [React Animations](https://www.npmjs.com/package/react-animations) / [Animate Components](https://www.npmjs.com/package/animate-components) / [rc-animate](https://www.npmjs.com/package/rc-animate)
    * [Hover.css](http://ianlunn.github.io/Hover/)
    * [Transformicons](http://www.transformicons.com/) / [Hamburgers](https://www.npmjs.com/package/hamburgers)
    * Loading
      * [Loaders.css](https://connoratherton.com/loaders) / [SpinKit](https://github.com/tobiasahlin/SpinKit) / [Spin.js](http://spin.js.org/)
      * [React Spinkit](https://www.npmjs.com/package/react-spinkit) / [React Loaders](https://www.npmjs.com/package/react-loaders) / [Halogen](http://madscript.com/halogen/) / [React Spinjs](https://www.npmjs.com/package/react-spinjs)
    * Queue
      * [React FLIP Move](https://www.npmjs.com/package/react-flip-move) / [rc-queue-anim](https://www.npmjs.com/package/rc-queue-anim)
    * Characters
      * [React Typist](https://www.npmjs.com/package/react-typist) / [rc-texty](https://www.npmjs.com/package/rc-texty)
      * [React CountUp](https://www.npmjs.com/package/react-countup) / [CountUp.js](https://www.npmjs.com/package/countup.js)
  * Parallax / Scrolling
    * [ScrollReveal.js](https://www.npmjs.com/package/scrollreveal) / [ScrollMagic](http://scrollmagic.io/) / [Rellax](https://www.npmjs.com/package/rellax)
    * [rc-scroll-anim](https://www.npmjs.com/package/rc-scroll-anim) / [React Springy Parallax](https://www.npmjs.com/package/react-springy-parallax)
    * Orientation - [Parallax](https://www.npmjs.com/package/parallax-js)
  * Easing
    * [d3-ease](https://www.npmjs.com/package/d3-ease) / [tween-functions](https://www.npmjs.com/package/tween-functions)
    * [bezier-easing](https://www.npmjs.com/package/bezier-easing)
  * Keyframe / Transition
    * Style
      * [Velocity.js](http://velocityjs.org/) / [Velocity React](https://www.npmjs.com/package/velocity-react) / [Dynamics.js](http://dynamicsjs.com/)
      * [React Overdrive](https://www.npmjs.com/package/react-overdrive)
    * Anything
      * [Anime.js](http://anime-js.com/documentation/)  /  [React Anime](https://www.npmjs.com/package/react-anime)
      * Between Shapes - [flubber](https://www.npmjs.com/package/flubber)
      * Lightweight Tweening Engine - [shifty](https://www.npmjs.com/package/shifty) / [tween.js](https://github.com/tweenjs/tween.js/)
      * [GSAP - TweenLite](https://greensock.com/tweenlite), [GSAP - TweenMax](https://greensock.com/tweenmax)
  * Keyframe + Timeline
    * Style
      * [React Motion](https://www.npmjs.com/package/react-motion)
        * [React Motion UI Pack](https://www.npmjs.com/package/react-motion-ui-pack)
        * [React Router Transition](https://www.npmjs.com/package/react-router-transition)
    * Anything
      * [React Move](https://react-move.js.org)
      * [GSAP - TimelineLite](https://greensock.com/timelinelite), [GSAP - TimelineMax](https://greensock.com/timelinemax)
        * [React GSAP Enhancer](https://www.npmjs.com/package/react-gsap-enhancer)
  * Motion / Curved Path
    * SVG - [Vivus](http://maxwellito.github.io/vivus/)
    * Shape - [mo-js](http://mojs.io/)
    * [rc-tween-one](https://www.npmjs.com/package/rc-tween-one)
* 2D
  * Canvas
    * [Pixi.js](http://www.pixijs.com/) / [Fabric.js](https://github.com/kangax/fabric.js)
    * [React Pixi](https://reactpixi.org/) / [ReactPixiFiber](https://github.com/michalochman/react-pixi-fiber) / [React Konva](https://www.npmjs.com/package/react-konva)
    * Isometric - [obelisk.js](https://www.npmjs.com/package/obelisk.js)
    * Creative - [p5.js](https://www.npmjs.com/package/p5)
    * Fonts - [opentype.js](https://opentype.js.org/)
  * SVG
    * [Snap.svg](http://snapsvg.io/) / [Raphaël](http://dmitrybaranovskiy.github.io/raphael/)
  * Physics
    * [Matter.js](http://brm.io/matter-js/)
* 3D
  * WebGL
    * [Three.js](https://threejs.org/) / [React Three](https://github.com/Izzimach/react-three) / [React Three Renderer](https://github.com/toxicFork/react-three-renderer)
    * [Babylon.js](http://www.babylonjs.com/)
    * [stackgl](https://github.com/stackgl)
    * [aframe-react](https://www.npmjs.com/package/aframe-react) / [A-Frame](https://aframe.io/)
    * [React 360](https://facebook.github.io/react-360/)
  * Physics
    * [cannon.js](https://github.com/schteppe/cannon.js) / [ammo.js](https://github.com/kripken/ammo.js) / [oimo.js](https://github.com/lo-th/Oimo.js/)
* Data Visualization
  * [React Sparklines](https://borisyankov.github.io/react-sparklines/) / [React Trend](https://www.npmjs.com/package/react-trend) / [vx](https://vx-demo.now.sh/)
  * [Recharts](http://recharts.org/) / [Victory](http://formidable.com/open-source/victory/)
  * [ECharts](http://echarts.baidu.com) / [Highcharts (Commercial)](https://www.highcharts.com) / [React Highcharts](https://www.npmjs.com/package/react-highcharts) / [Google Charts](https://developers.google.com/chart/) / [React Google Charts](https://www.npmjs.com/package/react-google-charts)
  * [Plotly.js](https://plot.ly/javascript/)
  * [AntV G2](https://antv.alipay.com)
  * [Chart.js](http://www.chartjs.org/) / [React ChartJS](https://www.npmjs.com/package/react-chartjs) / [Chartist.js](http://gionkunz.github.io/chartist-js)
  * Graph - [Cytoscape.js](http://js.cytoscape.org/), [AntV G6](https://antv.alipay.com/g6/doc/index.html)
  * [Timesheet.js](https://sbstjn.com/timesheet.js/), [Canvas Gauges](https://canvas-gauges.com)
  * GIS - [Leaflet](http://leafletjs.com/), [Turf.js](http://turfjs.org/), [OpenLayers](https://openlayers.org/), [Cesium](https://www.npmjs.com/package/cesium)
  * [D3.js](https://d3js.org/)
    * Word Cloud - [d3-cloud](https://www.npmjs.com/package/d3-cloud)
    * Constraint - [d3-force](https://www.npmjs.com/package/d3-force) / [cola.js](https://www.npmjs.com/package/webcola)
    * [Awesome D3](https://github.com/wbkd/awesome-d3)
* Game
  * [React GameKit](https://www.npmjs.com/package/react-game-kit)
  * [Phaser](https://www.npmjs.com/package/phaser)
  * [voxel.js](http://voxeljs.com/)

\>\> Return to [Table of Contents](#table-of-contents)

### Hybrid Libraries

* Electron
  * Persistence
    * [Electron Settings](https://www.npmjs.com/package/electron-settings)
    * [Auto Launch](https://www.npmjs.com/package/auto-launch)
    * [Electron Window State](https://www.npmjs.com/package/electron-window-state)
    * [Electron LetsMove](https://www.npmjs.com/package/electron-lets-move)
  * UI
    * [Electron Window](https://www.npmjs.com/package/electron-window)
    * [About Window](https://www.npmjs.com/package/about-window)
    * [Electron Context Menu](https://www.npmjs.com/package/electron-context-menu)
    * [Menubar](https://www.npmjs.com/package/menubar)
  * Interaction
    * [Electron Localshortcut](https://www.npmjs.com/package/electron-localshortcut)
  * Debug
    * [Electron Log](https://www.npmjs.com/package/electron-log)
    * [Electron Debug](https://www.npmjs.com/package/electron-debug)
* React Native
  * UI Toolkits
    * [NativeBase](https://www.npmjs.com/package/native-base)
    * [React Native Elements](https://www.npmjs.com/package/react-native-elements)
  * Standalone UI Components
    * [Vector Icons](https://www.npmjs.com/package/react-native-vector-icons)
    * [Loading Spinner Overlay](https://www.npmjs.com/package/react-native-loading-spinner-overlay) / [SpinKit](https://www.npmjs.com/package/react-native-spinkit)
    * [Progress](https://www.npmjs.com/package/react-native-progress)
    * [Button](https://www.npmjs.com/package/react-native-button)
    * [Tabs](https://www.npmjs.com/package/react-native-tabs)
    * [Drawer](https://www.npmjs.com/package/react-native-drawer)
    * [Modalbox](https://www.npmjs.com/package/react-native-modalbox)
    * [DatePicker](https://www.npmjs.com/package/react-native-datepicker)
    * [Maps](https://www.npmjs.com/package/react-native-maps)
  * UX
    * [React Navigation](https://www.npmjs.com/package/react-navigation) / [Navigation](https://www.npmjs.com/package/react-native-navigation)
    * [Push Notification](https://www.npmjs.com/package/react-native-push-notification) / [OneSignal](https://www.npmjs.com/package/react-native-onesignal)
    * [Parsed Text](https://www.npmjs.com/package/react-native-parsed-text)
    * [Swiper](https://www.npmjs.com/package/react-native-swiper)
    * [TabView](https://www.npmjs.com/package/react-native-tab-view) / [Scrollable TabView](https://www.npmjs.com/package/react-native-scrollable-tab-view)
    * [Invertible Scroll View](https://www.npmjs.com/package/react-native-invertible-scroll-view), [Gifted Chat](https://www.npmjs.com/package/react-native-gifted-chat)
    * [Keyboard Spacer](https://www.npmjs.com/package/react-native-keyboard-spacer)
  * Access
    * [Device Info](https://www.npmjs.com/package/react-native-device-info)
    * [Permissions](https://www.npmjs.com/package/react-native-permissions)
    * [Keychain](https://www.npmjs.com/package/react-native-keychain)
    * [Config](https://www.npmjs.com/package/react-native-config)
    * [Image Picker](https://www.npmjs.com/package/react-native-image-picker) / [Image Crop Picker](https://www.npmjs.com/package/react-native-image-crop-picker)
    * [Filesystem](http://npmjs.com/react-native-fs)
    * [Communications](https://www.npmjs.com/package/react-native-communications)
  * Graphic
    * [SVG](https://www.npmjs.com/package/react-native-svg)
    * [Blur](https://www.npmjs.com/package/react-native-blur)
    * [Animatable](https://www.npmjs.com/package/react-native-animatable)
    * [Lottie](https://www.npmjs.com/package/lottie-react-native)
  * Media
    * [Video](https://www.npmjs.com/package/react-native-video)
    * [Camera](https://www.npmjs.com/package/react-native-camera)
    * [Sound](http://npmjs.com/react-native-sound)
  * Storage
    * [Realm](https://www.npmjs.com/package/realm)
    * [Simple Store](https://www.npmjs.com/package/react-native-simple-store)

\>\> Return to [Table of Contents](#table-of-contents)

## Server Side

### Network

* HTTP
  * Intro
    * [An overview of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview), \
      [Introduction to HTTP](https://launchschool.com/books/http)
    * [Evolution of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/Evolution_of_HTTP)
    * [Identifying resources on the Web](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/Identifying_resources_on_the_Web) / \
      [Understanding URIs](http://medialize.github.io/URI.js/about-uris.html)
    * [Architecture of the World Wide Web: Identification](https://www.w3.org/TR/webarch/#identification)
    * [MIME types](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_Types)
    * [HTTP Messages](https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages)
    * [Connection management in HTTP/1.x](https://developer.mozilla.org/en-US/docs/Web/HTTP/Connection_management_in_HTTP_1.x)
    * [Redirections in HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Redirections)
  * Reference
    * [HTTP headers](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers)
    * [HTTP response status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status) / [httpstatuses.com](https://httpstatuses.com/)
  * [Same-origin policy](https://developer.mozilla.org/en-US/docs/Web/Security/Same-origin_policy)
    * [HTTP access control (CORS)](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS) / [Using CORS](https://www.html5rocks.com/en/tutorials/cors/)
    * Content Security Policy (CSP) - [Google](https://developers.google.com/web/fundamentals/security/csp/) / [Mozilla](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP)
  * Performance
    * [High Performance Browser Networking](https://hpbn.co/), \
      [Ideal HTTP Performance](https://www.mnot.net/blog/2016/04/22/ideal-http)
    * HTTP Caching - [Google](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching), [Mozilla](https://developer.mozilla.org/en-US/docs/Web/HTTP/Caching)
    * [Compression in HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Compression)
  * HTTPS
    * [Why HTTPS Matters](https://developers.google.com/web/fundamentals/security/encrypt-in-transit/why-https)
    * [Is TLS Fast Yet?](https://istlsfastyet.com/) / [HTTP vs HTTPS Test](https://www.httpvshttps.com/)
    * [HTTP Strict-Transport-Security (HSTS)](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Strict-Transport-Security)
    * [What Is Mixed Content?](https://developers.google.com/web/fundamentals/security/prevent-mixed-content/what-is-mixed-content), [Preventing Mixed Content](https://developers.google.com/web/fundamentals/security/prevent-mixed-content/fixing-mixed-content)
  * HTTP/2
    * [http2 explained](https://www.gitbook.com/book/bagder/http2-explained/details) / \
      [Introduction to HTTP/2](https://developers.google.com/web/fundamentals/performance/http2/)
    * [HTTP/2 FAQ](https://http2.github.io/faq/)
    * [A Comprehensive Guide To HTTP/2 Server Push](https://www.smashingmagazine.com/2017/04/guide-http2-server-push/)
  * [gRPC](http://www.grpc.io/docs/quickstart/node.html)
    * [What is gRPC?](http://www.grpc.io/docs/guides/)
    * [Protocol Buffers](https://developers.google.com/protocol-buffers/)
* TCP
  * [Writing WebSocket servers](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API/Writing_WebSocket_servers)
* UDP
  * [QUIC](https://www.chromium.org/quic)

\>\> Return to [Table of Contents](#table-of-contents)

### Server-side Best Practices

* SaaS
  * [The Twelve-Factor App](https://12factor.net/)
* Restful API
  * Heroku's [HTTP API Design Guide](https://geemus.gitbooks.io/http-api-design/content/en/), \
    Microsoft's [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design), [REST API Guidelines](https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md), \
    [Best Practices for Designing a Pragmatic RESTful API](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api), \
    [Principles of good RESTful API Design](https://codeplanet.io/principles-good-restful-api-design/)
  * [REST API Error Codes 101](http://blog.restcase.com/rest-api-error-codes-101/)
  * [Introducing JSON](http://json.org/)
* Microservices
  * [A pattern language for microservices](http://microservices.io/patterns/index.html)
    * [Microservice Architecture](http://microservices.io/patterns/microservices.html), [Monolithic Architecture](http://microservices.io/patterns/monolithic.html)
    * Decompose by [business capability](http://microservices.io/patterns/decomposition/decompose-by-business-capability.html), [subdomain](http://microservices.io/patterns/decomposition/decompose-by-subdomain.html)
    * [Service instance per container](http://microservices.io/patterns/deployment/service-per-container.html), [Service deployment platform](http://microservices.io/patterns/deployment/service-deployment-platform.html)
    * [Externalized configuration](http://microservices.io/patterns/externalized-configuration.html), [Microservice chassis](http://microservices.io/patterns/microservice-chassis.html)
    * Service discovery ([Server-side](http://microservices.io/patterns/server-side-discovery.html), [Client-side](http://microservices.io/patterns/client-side-discovery.html)), [Service registry](http://microservices.io/patterns/service-registry.html), [Remote Procedure Invocation](http://microservices.io/patterns/communication-style/rpi.html)
    * [Database per service](http://microservices.io/patterns/data/database-per-service.html), [Shared database](http://microservices.io/patterns/data/shared-database.html)
  * [Microservices: From Design to Deployment](https://www.nginx.com/blog/introduction-to-microservices/)
  * [Microservices Resource Guide](https://martinfowler.com/microservices/)
  * API Gateway
    * [Pattern: API Gateway / Backend for Front-End](http://microservices.io/patterns/apigateway.html)
    * [Why an API Gateway?](https://www.nginx.com/blog/microservices-api-gateways-part-1-why-an-api-gateway/)
    * [Moving from REST to GraphQL](https://medium.com/@frikille/moving-from-rest-to-graphql-e3650b6f5247) / [From REST to GraphQL](https://0x2a.sh/from-rest-to-graphql-b4e95e94c26b) / [GraphQL vs. REST](https://dev-blog.apollodata.com/graphql-vs-rest-5d425123e34b)
    * [Serverless and GraphQL: A Perfect Match for the New Cloud Paradigm](https://thenewstack.io/serverless-graphql-perfect-match-new-cloud-paradigm/)
  * Serverless
    * [Pattern: Serverless deployment](http://microservices.io/patterns/deployment/serverless-deployment.html)
    * [Microservices without the Servers](https://aws.amazon.com/blogs/compute/microservices-without-the-servers/)
    * [The Next Layer of Abstraction in Cloud Computing is Serverless](https://read.acloud.guru/iaas-paas-serverless-the-next-big-deal-in-cloud-computing-34b8198c98a2)
    * [The essential guide to serverless technologies and architectures](https://techbeacon.com/essential-guide-serverless-technologies-architectures), \
      [An essential guide to the serverless ecosystem](https://techbeacon.com/essential-guide-serverless-ecosystem)
    * [Serverless Architecture: Five Design Patterns](https://thenewstack.io/serverless-architecture-five-design-patterns/), \
      [Serverless Code Patterns](https://serverless.com/blog/serverless-architecture-code-patterns/)
* Cloud / Distributed
  * Architecture
    * [AWS Well-Architected](https://aws.amazon.com/architecture/well-architected/)
    * Azure's Cloud Fundamentals - [Architecture styles](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/), [Pillars of software quality](https://docs.microsoft.com/en-us/azure/architecture/guide/pillars), [Design principles](https://docs.microsoft.com/en-us/azure/architecture/guide/design-principles/index)
  * Static
    * [Static Content Hosting](https://docs.microsoft.com/en-us/azure/architecture/patterns/static-content-hosting), [Valet Key](https://docs.microsoft.com/en-us/azure/architecture/patterns/valet-key), [Content Delivery Network](https://docs.microsoft.com/en-us/azure/architecture/best-practices/cdn)
  * Queue / Jobs
    * [Queue-Based Load Leveling](https://docs.microsoft.com/en-us/azure/architecture/patterns/queue-based-load-leveling), [Competing Consumers](https://docs.microsoft.com/en-us/azure/architecture/patterns/competing-consumers), [Priority Queue](https://docs.microsoft.com/en-us/azure/architecture/patterns/priority-queue)
    * [Background jobs](https://docs.microsoft.com/en-us/azure/architecture/best-practices/background-jobs)
  * Decompose
    * [Federated Identity](https://docs.microsoft.com/en-us/azure/architecture/patterns/federated-identity)
    * [Pipes and Filters](https://docs.microsoft.com/en-us/azure/architecture/patterns/pipes-and-filters)
    * [Compute Resource Consolidation](https://docs.microsoft.com/en-us/azure/architecture/patterns/compute-resource-consolidation)
  * Configuration
    * [External Configuration Store](https://docs.microsoft.com/en-us/azure/architecture/patterns/external-configuration-store), [Runtime Reconfiguration](https://docs.microsoft.com/en-us/azure/architecture/patterns/runtime-reconfiguration)
  * Storage / Querying
    * [Cache-Aside](https://docs.microsoft.com/en-us/azure/architecture/patterns/cache-aside), [Caching](https://docs.microsoft.com/en-us/azure/architecture/best-practices/caching)
    * [CQRS](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs), [Event Sourcing](https://docs.microsoft.com/en-us/azure/architecture/patterns/event-sourcing)
    * [Index Table](https://docs.microsoft.com/en-us/azure/architecture/patterns/index-table), [Materialized View](https://docs.microsoft.com/en-us/azure/architecture/patterns/materialized-view)
    * [Data partitioning](https://docs.microsoft.com/en-us/azure/architecture/best-practices/data-partitioning), [Sharding](https://docs.microsoft.com/en-us/azure/architecture/patterns/sharding)
  * [Resiliency](https://docs.microsoft.com/en-us/azure/architecture/resiliency/) / [Availability](https://docs.microsoft.com/en-us/azure/architecture/checklist/availability)
    * [Retry](https://docs.microsoft.com/en-us/azure/architecture/patterns/retry), [Circuit Breaker](https://docs.microsoft.com/en-us/azure/architecture/patterns/circuit-breaker), [Transient fault handling](https://docs.microsoft.com/en-us/azure/architecture/best-practices/transient-faults)
    * [Compensating Transaction](https://docs.microsoft.com/en-us/azure/architecture/patterns/compensating-transaction)
    * [Health Endpoint Monitoring](https://docs.microsoft.com/en-us/azure/architecture/patterns/health-endpoint-monitoring), [Leader Election](https://docs.microsoft.com/en-us/azure/architecture/patterns/leader-election), [Scheduler Agent Supervisor](https://docs.microsoft.com/en-us/azure/architecture/patterns/scheduler-agent-supervisor)
    * [The Reactive Manifesto](http://www.reactivemanifesto.org/)
  * Multitenant
    * [Manage Identity in Multitenant Applications](https://docs.microsoft.com/en-us/azure/architecture/multitenant-identity/)
* Old-fashioned Web Hosting / Non-distributed
  * [Ultimate Guide to Web Hosting](http://www.whoishostingthis.com/resources/web-hosting/) / [Web Hosting Beginner Guide](http://www.webhostingsecretrevealed.net/web-hosting-beginner-guide/)
* Authentication / Authorization
  * [Cookies vs Tokens: The Definitive Guide](https://auth0.com/blog/cookies-vs-tokens-definitive-guide/), \
    [The Ins and Outs of Token Based Authentication](https://scotch.io/tutorials/the-ins-and-outs-of-token-based-authentication)
  * [Introduction to JSON Web Tokens](https://jwt.io/introduction/)
  * [An Introduction to OAuth 2](https://www.digitalocean.com/community/tutorials/an-introduction-to-oauth-2), [Understanding OAuth2](http://www.bubblecode.net/en/2016/01/22/understanding-oauth2/)
    * [The OAuth Bible](http://oauthbible.com/)
  * [Tokens used by Auth0](https://auth0.com/docs/tokens)
    * [Understanding Refresh Tokens](https://auth0.com/learn/refresh-tokens/)
  * [How To Safely Store A Password](https://codahale.com/how-to-safely-store-a-password/), \
    [You Wouldn't Base64 a Password - Cryptography Decoded](https://paragonie.com/blog/2015/08/you-wouldnt-base64-a-password-cryptography-decoded), \
    [How to securely hash passwords?](https://security.stackexchange.com/a/31846)
  * [Weak Signature Algorithm](https://developer.mozilla.org/en-US/docs/Web/Security/Weak_Signature_Algorithm)
* Security
  * [Security Guide for Developers](https://github.com/FallibleInc/security-guide-for-developers)
    * [Understanding CSRF](https://github.com/pillarjs/understanding-csrf), [CSRF Demystified](http://www.gnucitizen.org/blog/csrf-demystified/)
    * [Cross-site Scripting (XSS) Attack](https://www.acunetix.com/websitesecurity/cross-site-scripting/)
  * [OWASP Top Ten Cheat Sheet](https://www.owasp.org/index.php/OWASP_Top_Ten_Cheat_Sheet)
  * [WebAppSec/Secure Coding Guidelines](https://wiki.mozilla.org/WebAppSec/Secure_Coding_Guidelines)
  * [Node.js Security Checklist](https://blog.risingstack.com/node-js-security-checklist/)
  * Tools - see _[Tooling > Testing](#testing) > Analysis_
* Logging / Monitoring
  * [Logging The Ultimate Guide](https://www.loggly.com/ultimate-guide/category/node/)
  * [The Definitive Guide for Monitoring Node.js Applications](https://blog.risingstack.com/monitoring-nodejs-applications-nodejs-at-scale/)
  * [Monitoring and diagnostics](https://docs.microsoft.com/en-us/azure/architecture/best-practices/monitoring)
  * Tools - see _[Tooling > Workflow](#workflow) > Monitoring_
* DevOps
  * [Deployments Best Practices](http://guides.beanstalkapp.com/deployments/best-practices.html)
  * [Start your DevOps journey](https://www.atlassian.com/devops/start-your-journey)
  * [The Practical DevOps Playbook](https://www.shippable.com/devops-playbook.html)
  * Tools - see _[Tooling > Workflow](#workflow) > Deployment > DevOps_

\>\> Return to [Table of Contents](#table-of-contents)

### Microservices / API Services (Node.js)

* Frameworks
  * RESTful API
    * Middleware Framework
      * [Express](http://expressjs.com/) / [Koa](http://koajs.com/)
      * Express Middlewares
        * Logger
          * [morgan](https://www.npmjs.com/package/morgan), [express-winston](https://www.npmjs.com/package/express-winston), [errorhandler](https://www.npmjs.com/package/errorhandler), [response-time](https://www.npmjs.com/package/response-time)
        * HTTP Parser
          * [body-parser](https://www.npmjs.com/package/body-parser), [multer](https://www.npmjs.com/package/multer), [raw-body](https://www.npmjs.com/package/raw-body), [cookie-parser](https://www.npmjs.com/package/cookie-parser)
        * HTTP Headers and Verbs
          * [cors](https://www.npmjs.com/package/cors), [method-override](https://www.npmjs.com/package/method-override)
        * Performance
          * [compression](https://www.npmjs.com/package/compression) , [connect-timeout](https://www.npmjs.com/package/connect-timeout)
        * Security
          * [helmet](https://www.npmjs.com/package/helmet), [express-validator](https://www.npmjs.com/package/express-validator)
        * Auth
          * [express-jwt](https://www.npmjs.com/package/express-jwt) / [passport.js](http://passportjs.org/)
        * Proxy
          * [http-proxy-middleware](https://www.npmjs.com/package/http-proxy-middleware) / [rocky](https://www.npmjs.com/package/rocky)
        * GraphQL
          * [apollo-server-express](https://www.apollographql.com/docs/apollo-server/servers/express.html) / [express-graphql](https://www.npmjs.com/package/express-graphql)
    * Rich Framework
      * Configuration - [Hapi](https://hapijs.com/)
      * Realtime - [Feathers](https://feathersjs.com/)
  * Microservices
    * [Micro](https://www.npmjs.com/package/micro) / [Seneca](http://senecajs.org/) / [StdLib](https://stdlib.com/)
  * Serverless
    * [Serverless Framework](https://github.com/serverless/serverless)
    * [IronFunctions](https://github.com/iron-io/functions)
  * Bots
    * [Botkit](https://www.npmjs.com/package/botkit)
* GraphQL
  * [Schemas and Types](http://graphql.org/learn/schema/)
    * [GraphQL Schema Language Cheat Sheet](https://wehavefaces.net/graphql-shorthand-notation-cheatsheet-17cd715861b6)
  * [The Fullstack Tutorial for GraphQL](https://www.howtographql.com/)
  * Server
    * [Apollo Server](https://www.apollographql.com/docs/apollo-server/)
    * [graphql-tools](http://dev.apollodata.com/tools/graphql-tools/index.html)
  * Resolvers
    * [graphql-resolvers](https://github.com/lucasconstantino/graphql-resolvers)
* DocGen + CodeGen
  * [API Blueprint](https://apiblueprint.org/) / [Swagger](http://swagger.io/) / [RAML](http://raml.org/)
    * Parser - [Protagonist](https://www.npmjs.com/package/protagonist) / [Drafter](https://www.npmjs.com/package/drafter)
      * Renderer - [Aglio](https://www.npmjs.com/package/aglio)
    * Validator - [Dredd](https://www.npmjs.com/package/dredd)
  * [JSON Schema](http://json-schema.org/)
    * [Understanding JSON Schema](https://spacetelescope.github.io/understanding-json-schema/)
    * [JSON Schema Based Editor](https://github.com/jdorn/json-editor)
  * See _[Tooling > Documentation](#documentation)_
* Scaffold / Boilerplate / Generator
  * [Nodal](https://github.com/keithwhor/nodal)
  * [Fuge](http://fuge.io/)
  * [Botpress](https://github.com/botpress/botpress)
  * [nodecube](https://github.com/dexteryy/Project-WebCube) (Author's own project)

\>\> Return to [Table of Contents](#table-of-contents)

### Server-side Libraries (Node.js)

* Configuration
  * [dotenv](https://www.npmjs.com/package/dotenv)
  * [jsonfile](https://www.npmjs.com/package/jsonfile)
* Debugging
  * [winston](https://www.npmjs.com/package/winston)
  * [verror](https://www.npmjs.com/package/verror)
  * [longjohn](https://www.npmjs.com/package/longjohn), [stackman](https://www.npmjs.com/package/stackman)
  * [why-is-node-running](https://www.npmjs.com/package/why-is-node-running)
* Protocols
  * [form-data](https://www.npmjs.com/package/form-data), [formidable](https://www.npmjs.com/package/formidable)
  * [iconv-lite](https://www.npmjs.com/package/iconv-lite)
* Network
  * WebSocket - [ws](https://www.npmjs.com/package/ws) / [Socket.IO](https://www.npmjs.com/package/socket.io) / [Engine.IO](https://www.npmjs.com/package/engine.io) / [SockJS-node](https://www.npmjs.com/package/sockjs)
  * Server-Sent Event - [faye-websocket](https://www.npmjs.com/package/faye-websocket)
  * HTTP/2 - [spdy](https://www.npmjs.com/package/spdy)
  * gRPC - [grpc](https://www.npmjs.com/package/grpc)
  * AMQP - [amqplib](https://www.npmjs.com/package/amqplib)
  * [download](https://www.npmjs.com/package/download)
  * Email - [Nodemailer](https://nodemailer.com/)
    * Email HTML - [mailgen](https://www.npmjs.com/package/mailgen)
* Crypto
  * [hasha](https://www.npmjs.com/package/hasha)
  * [md5](https://www.npmjs.com/package/md5)
  * [bcrypt](https://www.npmjs.com/package/bcrypt)
* Auth
  * JWT - [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)
  * [passwordless](https://passwordless.net/)
  * [oauth](https://www.npmjs.com/package/oauth)
  * OAuth Providers - [hello.js](http://adodson.com/hello.js/) / [grant](https://www.npmjs.com/package/grant)
  * [svg-captcha](https://github.com/lemonce/svg-captcha)
* Storage
  * NOSQL
    * Redis Client - [ioredis](https://github.com/luin/ioredis)
    * MongoDB ORM - [Mongooose](http://mongoosejs.com/)
    * DynamoDB ORM - [vogels](https://www.npmjs.com/package/vogels)
    * HBase Client - [hbase](https://www.npmjs.com/package/hbase)
  * RDS
    * RDS ORM - [Sequelize](http://docs.sequelizejs.com/)
    * SQL Builder - [Knex.js](http://knexjs.org/)
* Jobs
  * Parallel - [webworker-threads](https://www.npmjs.com/package/webworker-threads)
  * Queue - [kue](https://www.npmjs.com/package/kue) / [bull](https://www.npmjs.com/package/bull)
  * Scheduler - [node-schedule](https://www.npmjs.com/package/node-schedule)
* Scraping
  * HTML Traversing - [cheerio](https://www.npmjs.com/package/cheerio), [jsdom](https://www.npmjs.com/package/jsdom)
  * HTML Parsing - [parse5](http://inikulin.github.io/parse5/index.html) / [htmlparser2](https://www.npmjs.com/package/htmlparser2)
  * Extract Article - [read-art](https://www.npmjs.com/package/read-art) / [node-readability](https://www.npmjs.com/package/node-readability)
  * Extract Metadata - [url-unshort](https://www.npmjs.com/package/url-unshort) / [embedza](https://www.npmjs.com/package/embedza)
  * Web Crawler - [simplecrawler](https://www.npmjs.com/package/simplecrawler) / [x-ray](https://www.npmjs.com/package/x-ray) / [scrape-it](https://www.npmjs.com/package/scrape-it) / [Headless Chrome Crawler](https://github.com/yujiosaka/headless-chrome-crawler)
  * Headless Browsers Automation - see _[Tooling > Testing](#testing) > Web Testing > Functional Testing > Headless Browser Automation_
* Images
  * Canvas / WebGL API - [node-canvas](https://www.npmjs.com/package/canvas) / [gl](https://www.npmjs.com/package/gl)
  * Image Manipulation - [gm](https://www.npmjs.com/package/gm) / [sharp](http://sharp.dimens.io/)
  * Capture Screenshots - [pageres](https://github.com/sindresorhus/pageres)
  * QR Code / Barcode - [qr-image](https://www.npmjs.com/package/qr-image)
  * Computer Vision - [tracking.js](https://trackingjs.com) / [opencv](https://www.npmjs.com/package/opencv)
* Parsing / Generating
  * Text - [unified](https://www.npmjs.com/package/unified)
    * Markdown - [remark](http://remark.js.org/)
  * [PDFKit](https://www.npmjs.com/package/pdfkit)
  * [csv](https://www.npmjs.com/package/csv)
  * [xml2js](https://www.npmjs.com/package/xml2js)
* NLP
  * [natural](https://github.com/NaturalNode/natural) / [retext](https://github.com/wooorm/retext) / [NodeJieba](https://github.com/yanyiwu/nodejieba)

\>\> Return to [Table of Contents](#table-of-contents)

### Cloud Services (Global)

* Compute
  * FaaS / Serverless / WebHook
    * [AWS Lambda](https://aws.amazon.com/lambda/) / [Google Cloud Functions](https://cloud.google.com/functions/)
    * [webtask](https://webtask.io/) / [hook.io](https://hook.io/)
    * [Graphcool Functions](https://www.graph.cool/docs/reference/functions/overview-boo6uteemo/)
    * [Amazon API Gateway](https://aws.amazon.com/api-gateway/)
  * PaaS
    * See _[Tooling > Workflow](#workflow) > Deployment > DevOps > PaaS_
  * CaaS
    * [Amazon ECS](https://aws.amazon.com/ecs/) / [Google Container Engine](https://cloud.google.com/container-engine/)
* Storage
  * Object Storage
    * [Amazon S3](https://aws.amazon.com/s3/) / [Google Cloud Storage](https://cloud.google.com/storage/)
    * [imgix](https://www.imgix.com)
  * DBaaS
    * In-Memory Key-Value NoSQL - [Amazon ElastiCache](https://aws.amazon.com/elasticache/)
      * Redis - [Compose](https://www.compose.com/redis) / [Redise Cloud](https://redislabs.com/products/redis-cloud/) / [Heroku Redis](https://www.heroku.com/redis)
    * Document NoSQL - [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) / [Google Cloud Datastore](https://cloud.google.com/datastore/)
      * MongoDB - [Compose](https://www.compose.com/mongodb) / [mLab](https://mlab.com/) / [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
      * CouchDB - [Couchbase](https://www.couchbase.com/products/server) / [Cloudant](https://www.ibm.com/analytics/us/en/technology/cloud-data-services/cloudant/)
    * Wide Column NoSQL - [Google Bigtable](https://cloud.google.com/bigtable/)
    * SQL - [Amazon RDS](https://aws.amazon.com/rds/) / [Google Cloud SQL](https://cloud.google.com/sql/)
      * PostgreSQL - [Compose](https://www.compose.com/postgresql) / [Heroku Postgres](https://www.heroku.com/postgres)
      * MySQL - [Compose](https://www.compose.com/mysql)
    * NewSQL - [Google Cloud Spanner](https://cloud.google.com/spanner/)
    * Queue - [Amazon SQS](https://aws.amazon.com/sqs/) / [Amazon Kinesis](https://aws.amazon.com/kinesis/) / [Google Cloud Pub/Sub](https://cloud.google.com/pubsub/)
      * Kafka - [Heroku Kafka](https://www.heroku.com/kafka)
      * RabbitMQ - [Compose](https://www.compose.com/rabbitmq)
    * Analytics - [Amazon CloudSearch](https://aws.amazon.com/cloudsearch/)
      * Elasticsearch - [Amazon Elasticsearch Service](https://aws.amazon.com/elasticsearch-service/) / [Elastic Cloud](https://www.elastic.co/cloud) / [Bonsai](https://bonsai.io/)
    * Warehouse - [Amazon Redshift](https://aws.amazon.com/redshift/) / [Google BigQuery](https://cloud.google.com/bigquery/)
* BaaS
  * CRUD
    * Realtime
      * [Firebase Realtime Database](https://firebase.google.com/products/database/)
    * GraphQL
      * [Graphcool](https://www.graph.cool/) / [Scaphold](https://scaphold.io/)
    * CMS
      * [WordPress.com REST API](https://developer.wordpress.com/docs/api/) / [Contentful](https://www.contentful.com/) / [DatoCMS](https://www.datocms.com/) / [GraphCMS](https://graphcms.com/) / [Baasic](http://www.baasic.com/)
  * Auth
    * [Auth0](https://auth0.com/) / [Amazon Cognito](https://aws.amazon.com/cognito/) / [Firebase Authentication](https://firebase.google.com/products/auth/)
    * [OAuth.io](https://oauth.io/)
    * CAPTCHA
      * [reCAPTCHA](https://www.google.com/recaptcha/)
  * Search - [Algolia](https://www.algolia.com/)
  * Email - [SendGrid](https://sendgrid.com/) / [Mailgun](https://www.mailgun.com/) / [Mandrill](http://www.mandrill.com/) / [Amazon SES](https://aws.amazon.com/ses/)
  * SMS - [Nexmo](https://www.nexmo.com/) / [Twilio](https://www.twilio.com/) / [Amazon SNS](https://aws.amazon.com/sns/)
  * Payment - [Stripe](https://stripe.com/)
  * Maps - [Mapbox](https://www.mapbox.com/)
  * Customer Support - [Intercom](https://developers.intercom.com/) / [Zendesk](https://developer.zendesk.com/)
  * IM - [Discord](https://discordapp.com/developers/)
  * Form - [Typeform.io](http://docs.typeform.io/) / [Form.io](https://form.io/)
* AIaaS / BDaaS
  * Natural Language
    * NLP - [Google Natural Language API](https://cloud.google.com/natural-language/)
    * Speech Recognition / Speech Synthesis
      * [Amazon Lex](https://aws.amazon.com/lex/) / [Google Cloud Speech API](https://cloud.google.com/speech/)
      * [Amazon Polly](https://aws.amazon.com/polly/)
    * Translation - [Google Cloud Translation API](https://cloud.google.com/translate/)
  * Computer Vision
    * [Amazon Rekognition](https://aws.amazon.com/rekognition/) / [Google Cloud Vision API](https://cloud.google.com/vision/)
    * [Google Cloud Video Intelligence API](https://cloud.google.com/video-intelligence/)

\>\> Return to [Table of Contents](#table-of-contents)

### Cloud Services (China)

> The evil twins inside [the Great Firewall of China](https://github.com/dexteryy/spellbook-of-modern-webdev/pull/4)

* Compute
  * FaaS / Serverless / WebHook
    * [阿里云-函数计算](https://www.aliyun.com/product/fc) / [腾讯云-无服务器云函数 SCF](https://www.qcloud.com/product/scf)
    * [阿里云-API 网关](https://www.aliyun.com/product/apigateway)
  * PaaS
    * See _[Tooling > Workflow](#workflow) > Deployment > DevOps > PaaS_
  * CaaS
    * [阿里云-容器服务](https://www.aliyun.com/product/containerservice) / [腾讯云-容器服务 CCS](https://www.qcloud.com/product/ccs) / [DaoCloud](https://www.daocloud.io/dcs)
* Storage
  * Object Storage
    * [阿里云-对象存储 OSS](https://www.aliyun.com/product/oss) / [腾讯云-对象存储 COS](https://www.qcloud.com/product/cos)
  * DBaaS
    * In-Memory Key-Value NoSQL
      * Redis - [阿里云-云数据库 Redis 版](https://www.aliyun.com/product/kvstore) / [腾讯云-云存储 Redis](https://www.qcloud.com/product/crs)
    * Document NoSQL
      * MongoDB - [阿里云-云数据库 MongoDB版](https://www.aliyun.com/product/mongodb) / [腾讯云-文档数据库 MongoDB](https://www.qcloud.com/product/mongodb)
    * Wide Column NoSQL - [阿里云-表格存储 OTS](https://www.aliyun.com/product/ots)
      * HBase - [阿里云-云数据库 HBase 版](https://cn.aliyun.com/product/hbase) / [腾讯云-列式数据库 HBase](https://www.qcloud.com/product/HBase)
    * SQL
      * PostgreSQL - [阿里云-云数据库 PostgreSQL 版](https://www.aliyun.com/product/rds/postgresql) / [腾讯云-云数据库 CDB for PostgreSQL](https://www.qcloud.com/product/postgresql)
      * MySQL - [阿里云-云数据库 MySQL 版](https://www.aliyun.com/product/rds/mysql) / [腾讯云-云数据库 CDB for MySQL](https://www.qcloud.com/product/cdb)
    * Queue - [阿里云-消息服务 MNS](https://www.aliyun.com/product/mns) / [腾讯云-消息服务 CMQ](https://www.qcloud.com/product/cmq)
      * Kafka - [腾讯云-消息服务 CKAFKA](https://www.qcloud.com/product/CKafka)
    * Analytics - [阿里云-开放搜索 OpenSearch](https://www.aliyun.com/product/opensearch) / [腾讯云搜 TCS](https://www.qcloud.com/product/tcs)
    * Warehouse - [阿里云-MaxCompute (ODPS)](https://www.aliyun.com/product/odps) / [腾讯云-大数据处理套件TBDS](https://www.qcloud.com/product/tbds)
* BaaS
  * CRUD
    * [LeanCloud-数据存储](https://leancloud.cn/docs/storage_overview.html)
    * Realtime
      * [野狗-实时通信引擎](https://www.wilddog.com/product/sync-overview) / [LeanCloud-实时通信](https://leancloud.cn/docs/realtime_v2.html)
  * Auth
    * [野狗-身份认证](https://www.wilddog.com/product/auth-overview)
    * CAPTCHA
      * [极验](http://www.geetest.com/) / [腾讯云-验证码服务 YY](https://www.qcloud.com/product/yy)
  * Search -
  * Email - [阿里云-邮件推送](https://www.aliyun.com/product/directmail) / [SendCloud](http://sendcloud.sohu.com/)
  * SMS - [阿里云-短信服务](https://www.aliyun.com/product/sms) / [腾讯云-短信 SMS](https://www.qcloud.com/product/sms) / [云片](https://www.yunpian.com/) / [野狗-短信](https://www.wilddog.com/product/message-overview)
  * Payment - [Ping++](https://www.pingxx.com/products)
  * Maps - [高德开放平台](https://lbs.amap.com/getting-started/map/) / [百度地图开放平台](http://lbsyun.baidu.com/)
  * Customer Support - [美洽](https://meiqia.com/) / [微金小云客服](https://www.qcloud.com/product/ICS)
  * IM - [野狗-即时通讯](https://www.wilddog.com/product/im-overview) / [腾讯云-云通信 IM](https://www.qcloud.com/product/im)
  * Form - [金数据](https://help.jinshuju.net/articles/api-intro)
* AIaaS / BDaaS
  * Natural Language
    * NLP
      * [腾讯云-文智自然语言处理 NLP](https://www.qcloud.com/product/nlp)
      * [阿里云-机器学习PAI-文本分析](https://help.aliyun.com/document_detail/42747.html)
    * Speech Recognition / Speech Synthesis
      * [阿里云-智能语音交互](https://data.aliyun.com/product/nls) / [腾讯云-智能语音服务 AAI](https://www.qcloud.com/product/aai)
    * Translation - [腾讯云-机器翻译](https://www.qcloud.com/product/tmt)
  * Computer Vision
    * [腾讯云-万象优图 CI](https://www.qcloud.com/product/ci)
    * [阿里云-印刷文字识别](https://data.aliyun.com/product/ocr)
  * Graphs / Networks / Clusters
    * [阿里云-推荐引擎](https://data.aliyun.com/product/re) / [腾讯云-云推荐引擎 CRE](https://www.qcloud.com/product/cre)
    * [阿里云-关系网络分析](https://data.aliyun.com/product/graphanalytics)
    * [阿里云-机器学习PAI-网络分析](https://help.aliyun.com/document_detail/42750.html)
  * Persona
    * [阿里云-画像分析](https://data.aliyun.com/product/porana) / [腾讯云-智能推荐 IR](https://www.qcloud.com/product/ir)

\>\> Return to [Table of Contents](#table-of-contents)

## Tooling

### Testing

* Unit Testing / Test Runner
  * [Jest](https://facebook.github.io/jest/)
  * [AVA](https://github.com/avajs/ava)
  * [Mocha](https://mochajs.org/) + [Chai](http://chaijs.com/)
  * [Cypress](https://www.cypress.io/)
  * [Karma](https://karma-runner.github.io)
* Web Testing
  * Integration Testing
    * Components - [Enzyme](http://airbnb.io/enzyme/)
    * Reducers
      * [redux-test-utils](https://www.npmjs.com/package/redux-test-utils) + [enzyme-redux](https://www.npmjs.com/package/enzyme-redux)
      * [redux-testkit](https://www.npmjs.com/package/redux-testkit)
  * Functional Testing / E2E Testing
    * Headless Browser Automation
      * DevTools API
        * Headless Chrome - [Puppeteer](https://github.com/GoogleChrome/puppeteer) / [Chromy](https://www.npmjs.com/package/chromy)
          * [End-to-end Tests that Don’t Suck with Puppeteer](https://ropig.com/blog/end-end-tests-dont-suck-puppeteer/)
          * AWS Lambda - [Chromeless](https://www.npmjs.com/package/chromeless)
        * electron-prebuilt - [Nightmare](https://github.com/segmentio/nightmare)
      * WebDriver API - [Selenium WebDriverJS](https://github.com/SeleniumHQ/selenium/wiki/WebDriverJs) / [WebDriverIO](http://webdriver.io/) / [Nightwatch.js](http://nightwatchjs.org/) / [CasperJS](http://casperjs.org/) / [Protractor](http://www.protractortest.org/)
          * AWS Lambda - [Lambdium](https://github.com/smithclay/lambdium)
    * Cloud - [BrowserStack Automate](https://www.browserstack.com/automate) / [Sauce Labs](https://saucelabs.com/open-source#automated-testing-platform)
  * Visual Testing
    * [React Storybook](https://storybooks.js.org/) / [React Cosmos](https://github.com/react-cosmos/react-cosmos)
    * [BrowserStack](https://www.browserstack.com/)
  * Monkey Testing
    * [gremlins.js](https://www.npmjs.com/package/gremlins.js)
  * Headless Browsers
    * Browsers
      * Chromium - [Headless Chrome/Chromium](https://developers.google.com/web/updates/2017/04/headless-chrome)
      * Chromium + Node.js - [electron-prebuilt](https://www.npmjs.com/package/electron)
      * WebKit - [PhantomJS](http://phantomjs.org/)
        * [Why you should stop using PhantomJS](https://blog.phantombuster.com/why-you-should-stop-using-phantomjs-f5c5f2717209)
      * Gecko - [SlimerJS](https://slimerjs.org/)
    * In-memory X11 Display Server
      * [xvfb](https://en.wikipedia.org/wiki/Xvfb) - [xvfb-run](http://manpages.ubuntu.com/manpages/trusty/man1/xvfb-run.1.html) / [headless](https://www.npmjs.com/package/headless)
    * Docker
      * [lighthouse-ci/builder/Dockerfile.headless](https://github.com/ebidel/lighthouse-ci/blob/master/builder/Dockerfile.headless#L16)
      * [electron-headless](https://hub.docker.com/r/dannysu/electron-headless/~/dockerfile/)
* Server-side Testing
  * Functional Testing
    * [supertest](https://www.npmjs.com/package/supertest)
  * Load Testing
    * [k6](https://k6.io/)
    * [loadtest](https://www.npmjs.com/package/loadtest)
* Benchmark Testing
  * JS
    * [Benchmark.js](https://benchmarkjs.com/)
    * [Speedracer](https://github.com/ngryman/speedracer)
    * [stats.js](https://github.com/mrdoob/stats.js)
  * Network
    * [wrk](https://github.com/wg/wrk) / [httpstat](https://github.com/reorx/httpstat)
* [Test Doubles](https://martinfowler.com/bliki/TestDouble.html) ([Fakes, Mocks, Stubs](https://dev.to/milipski/test-doubles---fakes-mocks-and-stubs) and Spies)
  * Fake Data
    * [Faker.js](https://github.com/Marak/Faker.js) / [Chance.js](http://chancejs.com/)
    * [JSON Schema Faker](https://www.npmjs.com/package/json-schema-faker)
    * [placeholder.com](https://placeholder.com/)
  * HTTP Mocking - [Nock](https://www.npmjs.com/package/nock)
  * Monkey Patching - [Mockery](https://www.npmjs.com/package/mockery), [babel-plugin-rewire](https://www.npmjs.com/package/babel-plugin-rewire)
  * [SinonJS](http://sinonjs.org/) / [testdouble.js](https://www.npmjs.com/package/testdouble)
    * [Best Practices for Spies, Stubs and Mocks in Sinon.js](https://semaphoreci.com/community/tutorials/best-practices-for-spies-stubs-and-mocks-in-sinon-js)
    * [testdouble.js vs. sinon.js](http://blog.testdouble.com/posts/2016-03-13-testdouble-vs-sinon.html)
* Analysis
  * Code Coverage
    * [Istanbul](https://istanbul.js.org/)
  * Software Complexity
    * [escomplex](https://www.npmjs.com/package/escomplex) / [complexity-report](https://www.npmjs.com/package/complexity-report)
  * Node.js Security
    * [nsp](https://www.npmjs.com/package/nsp) / [snyk](https://www.npmjs.com/package/snyk)
      * [NSP Advisories](https://nodesecurity.io/advisories/) / [Snyk - Vulnerability DB](https://snyk.io/vuln/)
  * Web Page
    * [Lighthouse](https://developers.google.com/web/tools/lighthouse/) / [pwmetrics](https://github.com/paulirish/pwmetrics)
    * [PageSpeed Insights](https://developers.google.com/speed/pagespeed/)
    * [Varvy SEO tool](https://varvy.com/)

\>\> Return to [Table of Contents](#table-of-contents)

### Documentation

* JS
  * [JSDoc3](http://usejsdoc.org/) + [documentation.js](http://documentation.js.org/) / [jsdox](http://jsdox.org/) / [dox](https://www.npmjs.com/package/dox)
  * [ESDoc](https://esdoc.org/)
  * [React DocGen](https://www.npmjs.com/package/react-docgen)
* API
  * [apiDoc](http://apidocjs.com/)
  * [GraphQL Voyager](https://github.com/APIs-guru/graphql-voyager)
* CLI
  * [Ronn](http://rtomayko.github.io/ronn/)
  * [Docopt](http://docopt.org/)
* Style Guide
  * Markdown + JSX - [docz](https://www.docz.site/)
  * JS - [Storybook](https://storybook.js.org/)
  * JS comments - [React Styleguidist](https://react-styleguidist.js.org/)
  * CSS comments - [KSS (Knyle Style Sheets)](http://warpspire.com/kss/)
    * [kss-node](http://kss-node.github.io/kss-node/)
    * [SC5 Style Guide Generator](http://styleguide.sc5.io/)
* Writing
  * Static Web Generator - [GitBook](https://www.npmjs.com/package/gitbook) / [ReadMe](https://readme.io/)
  * Client-side Rendering - [Docute](https://docute.js.org) / [Docsify](https://docsify.js.org)

\>\> Return to [Table of Contents](#table-of-contents)

### Toolchain

* Compiler / Transpiler / Preprocessor
  * [Babel](https://babeljs.io)
    * [Setting up ES6](https://leanpub.com/setting-up-es6/read)
    * [Babel User Handbook](https://github.com/thejameskyle/babel-handbook/blob/master/translations/en/user-handbook.md), [Babel Plugin Handbook](https://github.com/thejameskyle/babel-handbook/blob/master/translations/en/plugin-handbook.md)
    * Presets
      * [Preset Env](https://babeljs.io/docs/en/next/babel-preset-env.html)
        * [Browserslist](https://github.com/ai/browserslist)
      * [Preset React](http://babeljs.io/docs/plugins/preset-react/)
      * [React Optimize](https://github.com/thejameskyle/babel-react-optimize)
    * Plugins
      * Proposals
        * [Babel progress on ECMAScript proposals](https://github.com/babel/proposals)
        * Shims - [@babel/polyfill](https://github.com/babel/babel/tree/master/packages/babel-polyfill) ([useBuiltIns](https://babeljs.io/docs/en/next/babel-preset-env.html#usebuiltins)) / [core-js](https://github.com/zloirock/core-js)
          * async/await - [fast-async](https://github.com/MatAtBread/fast-async) ([NoDent](https://www.npmjs.com/package/nodent))
        * [Stage 3](http://babeljs.io/docs/plugins/preset-stage-3/), [Stage 2](http://babeljs.io/docs/plugins/preset-stage-2/), [Stage 1](http://babeljs.io/docs/plugins/preset-stage-1/), [Stage 0](http://babeljs.io/docs/plugins/preset-stage-0/)
          * [Class properties](http://babeljs.io/docs/plugins/transform-class-properties/)
          * [Object rest spread](http://babeljs.io/docs/plugins/transform-object-rest-spread/)
          * [Legacy Decorator](https://www.npmjs.com/package/babel-plugin-transform-decorators-legacy) / [Stage 2 Decorators](http://babeljs.io/docs/plugins/transform-decorators/)
          * Dynamic Import- [Syntax](https://www.npmjs.com/package/babel-plugin-syntax-dynamic-import),  [For Node.js](https://www.npmjs.com/package/babel-plugin-dynamic-import-node)
          * [Optional Chaining Operator](https://www.npmjs.com/package/babel-plugin-transform-optional-chaining)
      * Node.js
        * [add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports)
        * [Root Import](https://github.com/entwicklerstube/babel-plugin-root-import) / [Webpack Alias](https://www.npmjs.com/package/babel-plugin-webpack-alias)
      * React
        * [JSX Control Statements](https://www.npmjs.com/package/jsx-control-statements)
        * [React CSS Modules](https://github.com/gajus/babel-plugin-react-css-modules)
      * Libraries
        * [lodash](https://www.npmjs.com/package/babel-plugin-lodash), [ramda](https://www.npmjs.com/package/babel-plugin-ramda)
      * Optimization
        * [transform-remove-console](https://www.npmjs.com/package/babel-plugin-transform-remove-console)
  * [TypeScript](http://www.typescriptlang.org/)
    * [TypeScript: the missing introduction](https://jameshenry.blog/typescript-the-missing-introduction/)
  * [PostCSS](https://github.com/postcss/postcss)
    * Standards
      * [Autoprefixer](https://github.com/postcss/autoprefixer)
      * [CSSNext](http://cssnext.io/) / [postcss-preset-env](https://preset-env.cssdb.org/)
      * [Will Change](https://www.npmjs.com/package/postcss-will-change)
      * [Normalize](https://www.npmjs.com/package/postcss-normalize)
    * Utilities
      * [Utility Library](https://www.npmjs.com/package/postcss-utilities), [Rucksack](http://simplaio.github.io/)
      * [LostGrid](http://lostgrid.org/)
      * [Quantity Queries](https://github.com/pascalduez/postcss-quantity-queries)
      * [Easing Gradients](https://www.npmjs.com/package/postcss-easing-gradients)
      * [Pxtorem](https://www.npmjs.com/package/postcss-pxtorem)
      * [Brand Colors](https://www.npmjs.com/package/postcss-brand-colors) / [Nippon Color](https://www.npmjs.com/package/postcss-nippon-color) / [Google Color](https://www.npmjs.com/package/postcss-google-color)
      * [Contrast](https://www.npmjs.com/package/postcss-contrast) / [Get Color](https://www.npmjs.com/package/postcss-get-color)
    * Assets
      * [Assets](https://www.npmjs.com/package/postcss-assets)
      * [Inline SVG](https://www.npmjs.com/package/postcss-inline-svg), [SVGO](https://www.npmjs.com/package/postcss-svgo)
      * [Font Magician](https://www.npmjs.com/package/postcss-font-magician)
    * Syntax
      * [PreCSS](https://www.npmjs.com/package/precss)
      * [SCSS Parser](https://www.npmjs.com/package/postcss-scss)
      * [JS](https://www.npmjs.com/package/postcss-js)
  * [node-sass](https://www.npmjs.com/package/node-sass)
  * [PostHTML](https://www.npmjs.com/package/posthtml)
* Loader / Builder / Bundler
  * [Webpack](https://webpack.js.org/concepts/)
    * [webpack-howto](https://github.com/petehunt/webpack-howto)
      * [SurviveJS Webpack](https://survivejs.com/webpack/what-is-webpack/)
      * [webpack-blocks](https://github.com/andywer/webpack-blocks)
    * Loaders
      * [babel-loader](https://www.npmjs.com/package/babel-loader), [ts-loader](https://www.npmjs.com/package/ts-loader) / [awesome-typescript-loader](https://www.npmjs.com/package/awesome-typescript-loader), [vue-loader](https://www.npmjs.com/package/vue-loader)
        * [imports-loader](https://www.npmjs.com/package/imports-loader)
          * [Granular Shimming](https://webpack.js.org/guides/shimming/#granular-shimming)
        * [exports-loader](https://webpack.js.org/loaders/exports-loader/)
          * [Global Exports](https://webpack.js.org/guides/shimming/#global-exports)
      * [css-loader](https://www.npmjs.com/package/css-loader), [style-loader](https://www.npmjs.com/package/style-loader) / [isomorphic-style-loader](https://www.npmjs.com/package/isomorphic-style-loader)
        * [postcss-loader](https://www.npmjs.com/package/postcss-loader), [scss-loader](https://www.npmjs.com/package/sass-loader), [less-loader](https://www.npmjs.com/package/less-loader)
        * [resolve-url-loader](https://www.npmjs.com/package/resolve-url-loader)
      * [workerize-loader](https://www.npmjs.com/package/workerize-loader) / [worker-loader](https://www.npmjs.com/package/worker-loader)
      * [raw-loader](https://www.npmjs.com/package/raw-loader)
        * [html-loader](https://www.npmjs.com/package/html-loader)
          * [markdown-loader](https://www.npmjs.com/package/markdown-loader) / [handlebars-loader](https://www.npmjs.com/package/handlebars-loader)
        * [shader-loader](https://www.npmjs.com/package/shader-loader) / [glslify-loader](https://www.npmjs.com/package/glslify-loader)
      * [image-webpack-loader](https://www.npmjs.com/package/image-webpack-loader) / [img-loader](https://www.npmjs.com/package/img-loader)
      * [svg-react-loader](https://www.npmjs.com/package/svg-react-loader), [react-markdown-loader](https://www.npmjs.com/package/react-markdown-loader)
      * [url-loader](https://www.npmjs.com/package/url-loader), [svg-url-loader](https://www.npmjs.com/package/svg-url-loader)
      * [file-loader](https://www.npmjs.com/package/file-loader)
      * [thread-loader](https://www.npmjs.com/package/thread-loader), [cache-loader](https://www.npmjs.com/package/cache-loader), [val-loader](https://www.npmjs.com/package/val-loader)
    * Plugins
      * [Extract Text Plugin](https://www.npmjs.com/package/extract-text-webpack-plugin), [Webpack Manifest Plugin](https://www.npmjs.com/package/webpack-manifest-plugin)
      * [Copy Webpack Plugin](https://github.com/kevlened/copy-webpack-plugin), [Clean Webpack Plugin](https://www.npmjs.com/package/clean-webpack-plugin)
      * [HTML Webpack Plugin](https://www.npmjs.com/package/html-webpack-plugin)
        * [HTML Webpack Template](https://github.com/jaketrent/html-webpack-template)
        * Plugins
          * [Favicons](https://www.npmjs.com/package/favicons-webpack-plugin)
          * [Harddisk](https://www.npmjs.com/package/html-webpack-harddisk-plugin)
          * [Inline Source](https://www.npmjs.com/package/html-webpack-inline-source-plugin), [Preload](https://www.npmjs.com/package/preload-webpack-plugin)
          * [Include Assets](https://www.npmjs.com/package/html-webpack-include-assets-plugin) + [Exclude Assets](https://www.npmjs.com/package/html-webpack-exclude-assets-plugin)
          * [Inline Chunk Manifest](https://www.npmjs.com/package/inline-chunk-manifest-html-webpack-plugin)
      * [Define Plugin](https://webpack.js.org/plugins/define-plugin/) / [Environment Plugin](https://webpack.js.org/plugins/environment-plugin/)
      * [Provide Plugin](https://webpack.js.org/plugins/provide-plugin/)
        * [Shimming Global](https://webpack.js.org/guides/shimming/)
      * [Ignore Plugin](https://webpack.js.org/plugins/ignore-plugin/), [Watch Ignore Plugin](https://webpack.js.org/plugins/watch-ignore-plugin/)
      * [Module Concatenation Plugin](https://webpack.js.org/plugins/module-concatenation-plugin/), [Lodash Plugin](https://www.npmjs.com/package/lodash-webpack-plugin)
      * [UglifyJS Webpack Plugin](https://www.npmjs.com/package/uglifyjs-webpack-plugin) / [Babel Minify Webpack Plugin](https://www.npmjs.com/package/babel-minify-webpack-plugin)
      * [Workbox Webpack Plugins](https://developers.google.com/web/tools/workbox/modules/workbox-webpack-plugin), [Offline Plugin](https://www.npmjs.com/package/offline-plugin)
      * [Bundle Analyzer](https://www.npmjs.com/package/webpack-bundle-analyzer)
      * [Fork TS Checker Webpack Plugin](https://www.npmjs.com/package/fork-ts-checker-webpack-plugin), [HappyPack](https://www.npmjs.com/package/happypack)
  * [Rollup](https://rollupjs.org/)
    * [Webpack and Rollup: the same but different](https://medium.com/webpack/webpack-and-rollup-the-same-but-different-a41ad427058c)
* Formatter
  * ESLint with autofix feature - see Static Analysis
  * [Prettier](https://www.npmjs.com/package/prettier)
    * [prettier-eslint](https://www.npmjs.com/package/prettier-eslint)
  * Codemod - [Effective JavaScript Codemods](https://medium.com/@cpojer/effective-javascript-codemods-5a6686bb46fb)
    * [jscodeshift](https://www.npmjs.com/package/jscodeshift)
    * [react-codemod](https://www.npmjs.com/package/react-codemod)
    * [Recast](https://www.npmjs.com/package/recast)
  * [stylefmt](https://www.npmjs.com/package/stylefmt)
* Static Analysis
  * [ESLint](http://eslint.org/)
    * [ESLint Rules](http://eslint.org/docs/rules/)
      * [eslint-index](https://www.npmjs.com/package/eslint-index), [eslint-find-rules](https://www.npmjs.com/package/eslint-find-rules)
    * Plugins
      * [prettier](https://www.npmjs.com/package/eslint-plugin-prettier)
      * [babel](https://www.npmjs.com/package/babel-eslint), [import](https://www.npmjs.com/package/eslint-plugin-import), [eslint-comments](https://www.npmjs.com/package/eslint-plugin-eslint-comments), [unicorn](https://www.npmjs.com/package/eslint-plugin-unicorn), [no-use-extend-native](https://www.npmjs.com/package/eslint-plugin-no-use-extend-native)
      * [filenames](https://www.npmjs.com/package/eslint-plugin-filenames)
        * [eslint-import-resolver-webpack](https://www.npmjs.com/package/eslint-import-resolver-webpack)
      * [compat](https://www.npmjs.com/package/eslint-plugin-compat)
      * [node](https://www.npmjs.com/package/eslint-plugin-node), [security](https://www.npmjs.com/package/eslint-plugin-security)
      * [react](https://www.npmjs.com/package/eslint-plugin-react), [jsx-a11y](https://www.npmjs.com/package/eslint-plugin-jsx-a11y), [graphql](https://www.npmjs.com/package/eslint-plugin-graphql), [mongodb](https://www.npmjs.com/package/eslint-plugin-mongodb)
      * [jsdoc](https://www.npmjs.com/package/eslint-plugin-jsdoc), [flowtype](https://github.com/gajus/eslint-plugin-flowtype)
      * [jest](https://www.npmjs.com/package/eslint-plugin-jest), [ava](https://www.npmjs.com/package/eslint-plugin-ava), [mocha](https://www.npmjs.com/package/eslint-plugin-mocha), [chai-expect](https://www.npmjs.com/package/eslint-plugin-chai-expect)
      * [fp](https://www.npmjs.com/package/eslint-plugin-fp), [lodash](https://www.npmjs.com/package/eslint-plugin-lodash), [lodash-fp](https://www.npmjs.com/package/eslint-plugin-lodash-fp), [immutable](https://www.npmjs.com/package/eslint-plugin-immutable)
      * [promise](https://www.npmjs.com/package/eslint-plugin-promise), [optimize-regex](https://www.npmjs.com/package/eslint-plugin-optimize-regex)
    * Presets
      * [eslint-config-webcube](./packages/eslint-config-webcube/) (Author's own project)
      * [eslint-config-airbnb](https://www.npmjs.com/package/eslint-config-airbnb)
      * [eslint-config-react-app](https://github.com/facebookincubator/create-react-app/tree/master/packages/eslint-config-react-app)
  * [Flow](https://flow.org)
    * [flow-typed](https://github.com/flowtype/flow-typed)
    * [Flow Runtime](https://www.npmjs.com/package/babel-plugin-flow-runtime)
  * [StyleLint](http://stylelint.io/)
    * [doiuse](https://www.npmjs.com/package/doiuse)
    * [Colorguard](https://www.npmjs.com/package/colorguard)
    * [postcss-bem-linter](https://www.npmjs.com/package/postcss-bem-linter)
  * [HTMLHint](https://github.com/yaniswang/HTMLHint)
* Minifier / Compressor / Optimizer
  * [Prepack](https://prepack.io/)
  * [babel-minify](https://github.com/babel/minify) / [uglify-es](https://github.com/mishoo/UglifyJS2/tree/harmony) / [UglifyJS 3](https://github.com/mishoo/UglifyJS2) / [UglifyJS 2](https://github.com/mishoo/UglifyJS2/tree/v2.x)
  * [cssnano](http://cssnano.co/) / [clean-css](https://www.npmjs.com/package/clean-css) / [CSSO](https://www.npmjs.com/package/csso)
  * [HTMLMinifier](https://github.com/kangax/html-minifier)
  * [Critical](https://www.npmjs.com/package/critical) / [Penthouse](https://www.npmjs.com/package/penthouse)
  * [imagemin](https://www.npmjs.com/package/imagemin)
    * [gifsicle](https://github.com/kevva/imagemin-gifsicle)
    * [jpegtran](https://www.npmjs.com/package/imagemin-jpegtran) / [mozjpeg](https://github.com/imagemin/imagemin-mozjpeg)
    * [optipng](https://github.com/kevva/imagemin-optipng) / [pngquant](https://www.npmjs.com/package/imagemin-pngquant)
    * [svgo](https://github.com/kevva/imagemin-svgo)
    * [webp](https://www.npmjs.com/package/imagemin-webp)
  * [fontmin](https://www.npmjs.com/package/fontmin), [font-spider](https://www.npmjs.com/package/font-spider)
* Task Automation
  * [npm-run-script](https://docs.npmjs.com/cli/run-script), [npm-scripts](https://docs.npmjs.com/misc/scripts)
    * [task automation with npm run](http://substack.net/task_automation_with_npm_run), \
      [How to Use npm as a Build Tool](https://www.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/)
      * [Why I Left Gulp and Grunt for npm Scripts](https://medium.freecodecamp.com/why-i-left-gulp-and-grunt-for-npm-scripts-3d6853dd22b8)
    * Git Hooks
      * [Husky](https://github.com/typicode/husky)
      * [lint-staged](https://www.npmjs.com/package/lint-staged)
        * [Make linting great again!](https://medium.com/@okonetchnikov/make-linting-great-again-f3890e1ad6b8)
    * Environment Variables - [env-cmd](https://www.npmjs.com/package/env-cmd), [cross-env](https://www.npmjs.com/package/cross-env)
    * [get-port](https://www.npmjs.com/package/get-port), [public-ip](https://www.npmjs.com/package/public-ip)
  * [Gulp](http://gulpjs.com/)
    * [gulp - The vision, history, and future of the project](https://medium.com/@contrahacks/gulp-3828e8126466)
    * [Why you shouldn’t create a gulp plugin](http://blog.overzealous.com/post/74121048393/why-you-shouldnt-create-a-gulp-plugin-or-how-to)
    * [Gulpfile API](https://github.com/gulpjs/gulp/blob/master/docs/API.md)
    * Utilities
      * [The Problem with gulp-util](https://medium.com/gulpjs/gulp-util-ca3b1f9f9ac5)
      * [through2](https://www.npmjs.com/package/through2), [gulp-load-plugins](https://www.npmjs.com/package/gulp-load-plugins)
      * [gulp-size](https://www.npmjs.com/package/gulp-size), [gulp-count](https://www.npmjs.com/package/gulp-count), [gulp-notify](https://www.npmjs.com/package/gulp-notify)
      * [gulp-debug](https://www.npmjs.com/package/gulp-debug)
      * [gulp-if](https://www.npmjs.com/package/gulp-if), [gulp-filter](https://www.npmjs.com/package/gulp-filter), [merge-stream](https://www.npmjs.com/package/merge-stream)
      * [gulp-changed](https://www.npmjs.com/package/gulp-changed) / [gulp-cached](https://www.npmjs.com/package/gulp-cached)
      * [gulp-exec](https://www.npmjs.com/package/gulp-exec), [gulp-git](https://www.npmjs.com/package/gulp-git)
      * [gulp-rename](https://www.npmjs.com/package/gulp-rename)
      * [gulp-replace](https://www.npmjs.com/package/gulp-replace/) / [gulp-inject](https://www.npmjs.com/package/gulp-inject) / [gulp-useref](https://www.npmjs.com/package/gulp-useref), [gulp-inline-source](https://www.npmjs.com/package/gulp-inline-source/)
      * [gulp-sourcemaps](https://www.npmjs.com/package/gulp-sourcemaps)

\>\> Return to [Table of Contents](#table-of-contents)

### Workflow

* Development
  * Micro Generator
    * [Plop](https://plopjs.com)
  * Live Reload / Watch / Preview
    * [webpack-serve](https://github.com/webpack-contrib/webpack-serve)
    * [webpack-dev-server](https://www.npmjs.com/package/webpack-dev-server)
      * [webpack-dashboard](https://www.npmjs.com/package/webpack-dashboard)
      * [webpack-dev-middleware](https://www.npmjs.com/package/webpack-dev-middleware)
    * [Hot Module Replacement](https://webpack.js.org/guides/hot-module-replacement/) / [React Hot Loader](http://gaearon.github.io/react-hot-loader/)
    * [Browsersync](https://www.npmjs.com/package/browser-sync)
    * Electron - [Electron Connect](https://www.npmjs.com/package/electron-connect)
    * React Native - [Expo](https://expo.io/)
    * Node.js - [nodemon](https://www.npmjs.com/package/nodemon)
  * Dev Tools
    * [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/) / [Firefox Developer Tools](https://developer.mozilla.org/en-US/docs/Tools) / [Safari Web Inspector](https://developer.apple.com/library/content/documentation/AppleApplications/Conceptual/Safari_Developer_Guide/) / [Microsoft Edge F12 Dev Tools](https://docs.microsoft.com/en-us/microsoft-edge/f12-devtools-guide)
      * Console - [Console API](https://developers.google.com/web/tools/chrome-devtools/console/console-reference), [Command Line API](https://developers.google.com/web/tools/chrome-devtools/console/command-line-reference)
    * Third-party Panels
      * [React DevTools](https://github.com/facebook/react-devtools) / [AngularJS Batarang](https://chrome.google.com/webstore/detail/angularjs-batarang/ighdmehidhipcmcojjgiloacoafjmpfk) / [Augury](https://chrome.google.com/webstore/detail/augury/elgalmkoelokbchhkhacckoklkejnhcd) / [Vue.js DevTools](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd)
      * [React Perf](https://chrome.google.com/webstore/detail/react-perf/hacmcodfllhbnekmghgdlplbdnahmhmm)
      * [Redux DevTools](https://github.com/gaearon/redux-devtools)
      * [Immutable DevTools](https://github.com/andrewdavey/immutable-devtools), [Immutable.js Object Formatter](https://chrome.google.com/webstore/detail/immutablejs-object-format/hgldghadipiblonfkkicmgcbbijnpeog)
      * [Apollo Client Devtools](https://github.com/apollographql/apollo-client-devtools), [GraphQL Network](https://github.com/Ghirro/graphql-network)
      * [JWT Inspector](https://jwtinspector.io/)
      * [WebGL Insight](https://github.com/3Dparallax/insight/), [Three.js Editor Extension](https://chrome.google.com/webstore/detail/threejs-editor-extension/fbgbekpggeldiacgjkacbkkcbjhmakea)
    * [Reactotron](https://github.com/infinitered/reactotron)
    * Electron - [Devtron](https://github.com/electron/devtron)
    * [React Native Debugger](https://github.com/jhen0409/react-native-debugger)
  * HTTP Inspector
    * [Paw](https://paw.cloud/) / [Postman](https://www.getpostman.com/) / [HTTPie](https://github.com/jakubroztocil/httpie)
  * Debugging Proxy
    * [AnyProxy](http://anyproxy.io/en.html) / [Fiddler](http://www.telerik.com/fiddler)
    * [Tamper Chrome](https://github.com/google/tamperchrome)
* Deployment
  * Publishing App
    * Server-side Rendering
      * [Hypernova](https://github.com/airbnb/hypernova)
      * [React Isomorphic Render](https://www.npmjs.com/package/react-isomorphic-render)
      * [React Engine](https://www.npmjs.com/package/react-engine)
      * [Express React Views](https://www.npmjs.com/package/express-react-views)
    * Static Web
      * Dynamic Routing + CDN
        * [Superstatic](https://www.npmjs.com/package/superstatic)
      * Object Storage + CDN
        * Global
          * [Amazon S3 + CloudFront](http://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html) - [aws-sdk](https://www.npmjs.com/package/aws-sdk) / [awscli](https://github.com/aws/aws-cli)
          * [Google Cloud Storage + Cloud CDN](https://cloud.google.com/storage/docs/hosting-static-website) - [google-cloud](https://www.npmjs.com/package/google-cloud) / [gcloud](https://cloud.google.com/sdk/gcloud/)
          * [Firebase Hosting](https://firebase.google.com/products/hosting/) - [firebase-tools](https://www.npmjs.com/package/firebase-tools)
          * [Netlify](https://www.netlify.com/) - [netlify-cli](https://www.npmjs.com/package/netlify-cli)
          * [Surge](https://surge.sh/) - [surge cli client](https://www.npmjs.com/package/surge)
        * China
          * [阿里云 OSS + CDN](https://help.aliyun.com/document_detail/31872.html) - [aliyun-sdk](https://www.npmjs.com/package/aliyun-sdk) / [oss-nodejs-sdk](https://www.npmjs.com/package/ali-oss)
          * [腾讯云 COS + CDN](https://www.qcloud.com/document/product/436/9512) - [cos-nodejs-sdk-v5](https://www.npmjs.com/package/cos-nodejs-sdk-v5)
    * Packaged App
      * [Electron Builder](https://www.npmjs.com/package/electron-builder)
        * [Auto Update](https://github.com/electron-userland/electron-builder/wiki/Auto-Update)
      * [CodePush](https://www.npmjs.com/package/react-native-code-push)
  * DevOps
    * Process Supervisor
      * [pm2](http://pm2.keymetrics.io/)
        * [pm2-docker](http://pm2.keymetrics.io/docs/usage/docker-pm2-nodejs/)
        * [Process File](http://pm2.keymetrics.io/docs/usage/application-declaration/)
    * Containers
      * [Docker](https://docs.docker.com/engine/reference/builder/)
        * Learning
          * [Play with docker classroom](http://training.play-with-docker.com/)
          * [Docker Curriculum](https://github.com/prakhar1989/docker-curriculum)
          * [Docker Cheat Sheet](https://github.com/wsargent/docker-cheat-sheet) / [Docker Cheat Sheet](http://docker.jens-piegsa.com/)
        * [Dockerfile reference](https://docs.docker.com/engine/reference/builder/)
        * [Docker run reference](https://docs.docker.com/engine/reference/run/)
        * [Docker Compose](https://docs.docker.com/compose/overview/)
      * Docker Images
        * [node](https://github.com/nodejs/docker-node) / [risingstack/alpine](https://hub.docker.com/r/risingstack/alpine/) / [keymetrics/pm2-docker-alpine](https://hub.docker.com/r/keymetrics/pm2-docker-alpine/)
        * [docker-lambda](https://github.com/lambci/docker-lambda)
    * Container Clusters
      * [Docker Engine in Swarm Mode](https://docs.docker.com/engine/swarm/)
        * [Compose file reference](https://docs.docker.com/compose/compose-file/)
        * [wait-for-it.sh](https://github.com/vishnubob/wait-for-it) / [dockerize](https://github.com/jwilder/dockerize)
      * [Kubernetes](https://kubernetes.io/)
        * [Kubernetes Cheat Sheet](http://k8s.info/cs.html)
    * PaaS
      * Global
        * [now](https://zeit.co/now)
        * [heroku](heroku.com) - [heroku-cli](https://devcenter.heroku.com/articles/heroku-cli#getting-started)
      * China
        * [LeanCloud-云引擎](https://leancloud.cn/docs/leanengine_overview.html) ([云函数](https://leancloud.cn/docs/leanengine_cloudfunction_guide-node.html), [网站托管](https://leancloud.cn/docs/leanengine_webhosting_guide-node.html)) - [lean-cli](https://leancloud.cn/docs/leanengine_cli.html)
* Monitoring
  * Error Tracking
    * [Capturing client-side JavaScript errors](https://www.thoughtworks.com/radar/techniques/capturing-client-side-javascript-errors), [Front-End Error Handling](https://staticapps.org/articles/front-end-error-handling/)
      * [A Guide to Proper Error Handling in JavaScript](https://www.sitepoint.com/proper-error-handling-javascript/)
    * Services
      * [TrackJS](https://trackjs.com/) / [Errorception](https://errorception.com/)
      * [Sentry](https://sentry.io/for/javascript/) / [Rollbar](https://rollbar.com/docs/notifier/rollbar.js/) / [Bugsnag](https://docs.bugsnag.com/platforms/browsers/) / [Airbrake](https://airbrake.io/languages/javascript_exception_handler) / [Raygun](https://raygun.com/)
  * Logging
    * Global
      * [Amazon CloudWatch](https://aws.amazon.com/cloudwatch/) / [Google Stackdriver](https://cloud.google.com/stackdriver/)
      * [PM2 Plus](https://pm2.io/plus/)
    * China
      * [阿里云-云监控](https://www.aliyun.com/product/jiankong) / [腾讯云-基础监控 BCM](https://www.qcloud.com/product/bcm)
  * APM (Application Performance Management)
    * Global
      * [New Relic](https://newrelic.com/) / [AppDynamics](https://www.appdynamics.com/) / [Datadog APM](https://www.datadoghq.com/apm/)
      * [Pingdom](https://www.pingdom.com/) / [SpeedCurve](https://speedcurve.com/) / [AppNeta](https://www.appneta.com/)
      * [Trace](https://trace.risingstack.com)
    * China
      * [OneAPM](https://www.oneapm.com/) / [听云](http://www.tingyun.com/)
      * [监控宝](https://www.jiankongbao.com/) / [百度云观测](http://ce.baidu.com/) / [360网站服务监控](http://jk.cloud.360.cn/) / [腾讯云-云拨测 CAT](https://www.qcloud.com/product/cat)
      * [阿里云 Node.js 性能平台](https://www.aliyun.com/product/nodejs)

\>\> Return to [Table of Contents](#table-of-contents)

### Command-line Environment (Mac)

* Intro
  * [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)
  * [The Bash Guide](http://guide.bash.academy/)
  * [Linux Shell Scripting Tutorial (LSST)](https://bash.cyberciti.biz/guide/Main_Page)
* Terminal
  * [iTerm2](https://www.iterm2.com/)
    * [iTerm Color Schemes](https://github.com/mbadolato/iTerm2-Color-Schemes)
  * [Hyper](https://hyper.is/)
    * [Awesome Hyper](https://github.com/bnb/awesome-hyper)
* Package Manager
  * [Homebrew](https://brew.sh/)
* Shell
  * [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh)
  * [Spaceship ZSH Theme](https://github.com/denysdovhan/spaceship-zsh-theme)
  * Zsh Plugins
    * [zsh-better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion)
    * [Awesome Zsh Plugins](https://github.com/unixorn/awesome-zsh-plugins)
* Vim
  * [Vimtutor](http://linuxcommand.org/man_pages/vimtutor1.html)
  * [spf13-vim](https://github.com/spf13/spf13-vim) / [YVim](https://github.com/dexteryy/YVim)
* Git
  * [Git-it](https://github.com/jlord/git-it-electron), [TryGit Simulator](https://try.github.io/)
  * [Become a git guru](https://www.atlassian.com/git/tutorials), [Git Glossary](https://www.atlassian.com/git/glossary)
  * [Pro Git - Index of Commands](https://git-scm.com/book/commands)
  * [commitizen](https://github.com/commitizen/cz-cli)
* [Docker for Mac](https://docs.docker.com/docker-for-mac/)
* [dotfiles](https://dotfiles.github.io/)
* Utilities
  * Analysis - [cloc](https://github.com/AlDanial/cloc/)
  * Finding - [rg (ripgrep)](https://github.com/BurntSushi/ripgrep) / [ag (The Silver Searcher)](https://github.com/ggreer/the_silver_searcher), [peco](https://github.com/peco/peco), [jq](https://stedolan.github.io/jq), [fzf](https://github.com/junegunn/fzf)
  * Processes - [glances](https://github.com/nicolargo/glances) / [vtop](https://www.npmjs.com/package/vtop), [fkill](https://www.npmjs.com/package/fkill-cli)
  * Help - [tldr](https://github.com/tldr-pages/tldr) / [howdoi](https://github.com/gleitz/howdoi)

\>\> Return to [Table of Contents](#table-of-contents)

### Command-line Libraries (Node.js)

* Input
  * Options/Arguments Parser - [minimist](https://www.npmjs.com/package/minimist) / [commander](https://www.npmjs.com/package/commander) / [yargs](https://www.npmjs.com/package/yargs)
  * Interactive - [inquirer](https://www.npmjs.com/package/inquirer)
  * Rapidly Building - [vorpal](https://www.npmjs.com/package/vorpal) / [cli](https://www.npmjs.com/package/cli)
  * Configuration - [Liftoff](https://www.npmjs.com/package/liftoff)
* Output
  * Color / Style - [Chalk](https://www.npmjs.com/package/chalk)
  * Icon - [log-symbols](https://www.npmjs.com/package/log-symbols) / [figures](https://www.npmjs.com/package/figures)
  * Updating Log
    * Low-level - [log-update](https://www.npmjs.com/package/log-update)
    * Indicator - [ora](https://www.npmjs.com/package/ora) / [progress](https://www.npmjs.com/package/progress) / [pace](https://www.npmjs.com/package/pace)
    * Pretty Log - [DraftLogs](https://www.npmjs.com/package/draftlog) / [listr](https://www.npmjs.com/package/listr)
  * Notice - [boxen](https://www.npmjs.com/package/boxen), [cfonts](https://www.npmjs.com/package/cfonts)
  * Columns - [cli-table](https://www.npmjs.com/package/cli-table) / [columnify](https://www.npmjs.com/package/columnify)
  * Curses-like - [blessed](https://www.npmjs.com/package/blessed)
  * Drawing - [drawille-canvas](https://www.npmjs.com/package/drawille-canvas)
  * Image - [term-img](https://www.npmjs.com/package/term-img)
* Delivery
  * [update-notifier](https://www.npmjs.com/package/update-notifier)
  * Reporting Usage - [insight](https://www.npmjs.com/package/insight)
  * Self-contained Executable - [pkg](https://www.npmjs.com/package/pkg)
* Framework
  * Generator - [Yeoman](http://yeoman.io/authoring/)
* OS
  * Shell Commands - [ShellJS](https://www.npmjs.com/package/shelljs)
  * Filesystem
    * Filesystem API - [fs-extra](https://www.npmjs.com/package/fs-extra) / [fs-jetpack](https://www.npmjs.com/package/fs-jetpack)
    * Wildcard Matching - [glob](https://www.npmjs.com/package/glob) / [globby](https://www.npmjs.com/package/globby), [matcher](https://www.npmjs.com/package/matcher)
    * Virtual Filesystem - [vinyl](https://www.npmjs.com/package/vinyl-fs)
    * Temporary File - [tmp](https://www.npmjs.com/package/tmp)
    * File Locking - [proper-lockfile](https://www.npmjs.com/package/proper-lockfile)
    * Finding - [find-up](https://www.npmjs.com/package/find-up), [readdirp](https://www.npmjs.com/package/readdirp)
    * Watch - [chokidar](https://www.npmjs.com/package/chokidar) / [gaze](https://www.npmjs.com/package/gaze)
  * Local
    * [network-address](https://www.npmjs.com/package/network-address)
    * [clipboardy](https://www.npmjs.com/package/clipboardy)
* API
  * Git - [simple-git](https://www.npmjs.com/package/simple-git) / [nodegit](https://www.npmjs.com/package/nodegit)
  * Docker - [dockerode](https://www.npmjs.com/package/dockerode)
  * SSH - [ssh2](https://www.npmjs.com/package/ssh2)
* Parser
  * JS - [Acorn](https://www.npmjs.com/package/acorn) / [Babylon](https://www.npmjs.com/package/babylon) / [Espree](https://www.npmjs.com/package/espree) / [Esprima](https://www.npmjs.com/package/esprima)

\>\> Return to [Table of Contents](#table-of-contents)

### IDE / Editors

* [VS Code](https://code.visualstudio.com/) Plugins
  * UI
    * [vscode-icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons)
    * [Indenticator](https://marketplace.visualstudio.com/items?itemName=SirTori.indenticator)
  * Operating
    * [VSCodeVim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)
    * [Search node_modules](https://marketplace.visualstudio.com/items?itemName=jasonnutter.search-node-modules)
    * [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
    * [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
    * [Lorem ipsum](https://marketplace.visualstudio.com/items?itemName=Tyriar.lorem-ipsum) / [Chinese Lorem Ipsum](https://marketplace.visualstudio.com/items?itemName=galend.vsc-lorem-cn)
    * Snippets
      * [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
      * [JavaScript Snippet Pack](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-javascript-snippet-pack)
      * [Reactjs code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.ReactSnippets)
      * [React Redux ES6 Snippets](https://marketplace.visualstudio.com/items?itemName=timothymclane.react-redux-es6-snippets)
      * [eslint-disable-snippets](https://marketplace.visualstudio.com/items?itemName=drKnoxy.eslint-disable-snippets)
      * [HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets)
      * [SVG Icons](https://marketplace.visualstudio.com/items?itemName=idleberg.svg-icons)
      * [Icon Fonts](https://marketplace.visualstudio.com/items?itemName=idleberg.icon-fonts)
  * Formatting
    * [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
    * [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) / [stylefmt](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-stylefmt)
    * [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
    * [change-case](https://marketplace.visualstudio.com/items?itemName=wmaurer.change-case)
    * [Align](https://marketplace.visualstudio.com/items?itemName=steve8708.Align)
  * Static Analysis
    * [Flow Language Support](https://marketplace.visualstudio.com/items?itemName=flowtype.flow-for-vscode)
    * [Stylelint](https://marketplace.visualstudio.com/items?itemName=shinnn.stylelint)
    * [HTMLHint](https://marketplace.visualstudio.com/items?itemName=mkaufman.HTMLHint)
    * Syntax
      * [CSS Modules](https://marketplace.visualstudio.com/items?itemName=clinyong.vscode-css-modules)
      * [vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=jpoissonnier.vscode-styled-components)
      * [GraphQL for VSCode](https://marketplace.visualstudio.com/items?itemName=kumar-harsh.graphql-for-vscode)
      * [Docker](https://marketplace.visualstudio.com/items?itemName=PeterJausovec.vscode-docker)
  * Docs
    * [Dash](https://marketplace.visualstudio.com/items?itemName=deerawan.vscode-dash)
    * [Regex Previewer](https://marketplace.visualstudio.com/items?itemName=chrmarti.regex)
    * [Color Picker](https://marketplace.visualstudio.com/items?itemName=anseki.vscode-color)
    * [Swagger Viewer](https://marketplace.visualstudio.com/items?itemName=Arjun.swagger-viewer)
    * [API Elements extension](https://marketplace.visualstudio.com/items?itemName=vncz.vscode-apielements)
  * Assistant
    * [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)
    * [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)
    * [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)
    * [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
    * [Quokka.js - Live Scratchpad for JavaScript](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
  * Integration
    * VCS
      * [Git Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
      * [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
      * [Open in GitHub](https://marketplace.visualstudio.com/items?itemName=ziyasal.vscode-open-in-github)
    * [Share Code](https://marketplace.visualstudio.com/items?itemName=RolandGreim.sharecode)
    * Debug
      * [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)
      * [Node Debug 2](https://marketplace.visualstudio.com/items?itemName=ms-vscode.node-debug2)
      * [Jest](https://marketplace.visualstudio.com/items?itemName=Orta.vscode-jest)
    * [React Native Tools](https://marketplace.visualstudio.com/items?itemName=vsmobile.vscode-react-native)
    * [Cordova Tools](https://marketplace.visualstudio.com/items?itemName=vsmobile.cordova-tools)
    * Write
      * [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
      * [Mermaid Preview](https://marketplace.visualstudio.com/items?itemName=vstirbu.vscode-mermaid-preview)
* [Atom](https://atom.io/) Plugins
  * UI
    * [fonts](https://atom.io/packages/fonts)
    * [file-icons](https://atom.io/packages/file-icons)
    * [highlight-line](https://atom.io/packages/highlight-line), [highlight-selected](https://atom.io/packages/highlight-selected)
    * [indent-guide-improved](https://atom.io/packages/indent-guide-improved), [trailing-spaces](https://atom.io/packages/trailing-spaces)
  * Operating
    * [vim-mode-plus](https://atom.io/packages/vim-mode-plus), [jumpy](https://atom.io/packages/jumpy)
    * [Sublime-Style-Column-Selection](https://atom.io/packages/Sublime-Style-Column-Selection)
    * [Emmet](https://atom.io/packages/emmet)
    * Snippets
      * [turbo-javascript](https://atom.io/packages/turbo-javascript)
  * Formatting
    * [auto-detect-indentation](https://atom.io/packages/auto-detect-indentation), [editorconfig](https://atom.io/packages/editorconfig)
    * [prettier-atom](https://atom.io/packages/prettier-atom)
    * [atom-stylefmt](https://atom.io/packages/stylefmt) / [postcss-sorting](https://atom.io/packages/postcss-sorting) / [atom-beautify](https://atom.io/packages/atom-beautify)
    * [aligner](https://atom.io/packages/aligner) / [atom-alignment](https://atom.io/packages/atom-alignment)
    * [toggle-quotes](https://atom.io/packages/toggle-quotes)
  * Static Analysis
    * [file-types](https://atom.io/packages/file-types)
    * [language-babel](https://atom.io/packages/language-babel), [atom-ternjs](https://atom.io/packages/atom-ternjs)
    * [language-postcss](https://atom.io/packages/language-postcss)
    * [language-mjml](https://atom.io/packages/language-mjml)
    * [linter-eslint](https://atom.io/packages/linter-eslint), [linter-flow](https://atom.io/packages/linter-flow), [linter-stylelint](https://atom.io/packages/linter-stylelint), [linter-htmlhint](https://atom.io/packages/linter-htmlhint), [linter-mjml](https://atom.io/packages/linter-mjml), [linter-jsonlint](https://atom.io/packages/linter-jsonlint), [linter-js-yaml](https://atom.io/packages/linter-js-yaml)
  * Docs
    * [dash](https://atom.io/packages/dash)
    * [Hyperclick](https://atom.io/packages/hyperclick), [js-hyperclick](https://atom.io/packages/js-hyperclick)
    * [keybinding-cheatsheet](https://atom.io/packages/keybinding-cheatsheet)
  * Assistant
    * [Project Manager](https://atom.io/packages/project-manager)
    * [todo-show](https://atom.io/packages/todo-show) / [imdone-atom](https://atom.io/packages/imdone-atom)
  * Integration
    * [GitHub for Atom](https://github.atom.io/)
    * [Build](https://atom.io/packages/build)
      * [AtomBuild](https://atombuild.github.io/)
    * [Markdown Preview Plus](https://atom.io/packages/markdown-preview-plus)
* Out-of-the-box Atom IDE
  * [YAtom](https://github.com/dexteryy/YAtom) (author's own project)
  * [Nuclide](https://nuclide.io/)
  * [Reactide](http://reactide.io/)
* Other Electron-based IDE
  * [Deco](https://www.decoide.org/)
* [WebStorm](https://www.jetbrains.com/webstorm/)
* Programming Fonts
  * [Hack](http://sourcefoundry.org/hack/)
  * [Anonymous Pro](https://www.marksimonson.com/fonts/view/anonymous-pro)
  * [Source Code Pro](http://adobe-fonts.github.io/source-code-pro/)
  * [Fira Mono](http://mozilla.github.io/Fira/)
  * [Google Noto Mono](https://www.google.com/get/noto/)
  * [Droid Sans Mono](https://fonts.google.com/specimen/Droid+Sans+Mono)
  * [Space Mono](https://fonts.google.com/specimen/Space%20Mono)
  * [M+](http://mplus-fonts.osdn.jp/about-en.html)
  * [Mononoki](http://madmalik.github.io/mononoki/)
  * [Profont](http://tobiasjung.name/profont/)

\>\> Return to [Table of Contents](#table-of-contents)

### Useful Apps

* Playground
  * [CodePen](http://codepen.io/) / [CodeSandbox](https://codesandbox.io/)
    * CDN for npm - [unpkg](https://unpkg.com/)
  * [RunKit](https://runkit.com)
  * [RequestBin](https://requestbin.com/)
  * [jsPerf](https://jsperf.com/)
  * [CSS in JS Playground](https://css-in-js-playground.com/)
  * [GraphQL Playground](https://github.com/graphcool/graphql-playground), [Apollo Launchpad](https://launchpad.graphql.com)
  * [GLSL Sandbox](http://glslsandbox.com/)
  * [ImmutableJS REPL](http://neilff.github.io/immutable-repl/?)
* Visual Tools
  * Performance
    * [Cuzillion](http://stevesouders.com/cuzillion/)
    * [Critical Path CSS Generator](https://jonassebastianohlsson.com/criticalpathcssgenerator/)
  * CSS
    * [cssreference.io](http://cssreference.io/)
    * [EnjoyCSS](http://enjoycss.com/)
    * Easing - [cubic-bezier](http://cubic-bezier.com/) / [Ceaser CSS Easing Animation Tool](https://matthewlein.com/ceaser/) / [Custom easing functions](http://www.joelambert.co.uk/morf/) / [Easing functions](http://easings.net/)
    * Flexbox - [Fibonacci Flexbox Composer](http://maxsteenbergen.com/fibonacci/) / [CSS Flexbox Please!](https://demo.agektmr.com/flexbox/) / [Flexy Boxes](http://the-echoplex.net/flexyboxes/) / [Flexbox Playground](https://demos.scotch.io/visual-guide-to-css3-flexbox-flexbox-playground/demos/) / [flexplorer](http://bennettfeely.com/flexplorer/)
    * Animation - [CSS3 Keyframes Animation Generator](http://cssanimate.com/) / [Mantra](http://jeremyckahn.github.io/mantra/) / [Bounce.js](http://bouncejs.com/)
    * Gradient - [Ultimate CSS Gradient Generator](http://www.colorzilla.com/gradient-editor/)
    * [Quantity Queries Builder](http://quantityqueries.com/)
    * Shapes - [CSS triangle generator](http://apps.eky.hk/css-triangle-generator/),  [Tridiv CSS 3D Editor](http://tridiv.com/)
    * [HTML Table Generator](http://www.tablesgenerator.com/html_tables)
  * JS
    * [Keyboard Event Viewer](https://w3c.github.io/uievents/tools/key-event-viewer.html)
    * [Web Audio Playground](http://webaudioplayground.appspot.com/)
    * [Regex101](https://regex101.com/) / [Debuggex](https://www.debuggex.com/)
* Viewer
  * [JSON Viewer](https://github.com/tulios/json-viewer), [XML Tree](https://chrome.google.com/webstore/detail/xml-tree/gbammbheopgpmaagmckhpjbfgdfkpadb)
  * [JS Nice](http://www.jsnice.org/) / [JS Beautifier](http://jsbeautifier.org/)
  * [GraphQL Voyager](https://apis.guru/graphql-voyager/), [GraphQL Docs](https://graphql-docs.com/), [GraphQL Visualizer / graphqlviz](http://nathanrandal.com/graphql-visualizer/) / [graphqlviz](https://github.com/sheerun/graphqlviz)
  * [AST Explorer](http://astexplorer.net/)
  * [DevTools Timeline Viewer](https://chromedevtools.github.io/timeline-viewer/)
  * [Text Escaping and Unescaping in JavaScript](http://0xcc.net/jsescape/)
  * [HTML Entity Lookup](http://entity-lookup.leftlogic.com/) / [HTML Arrows](https://www.toptal.com/designers/htmlarrows/)
* Docs
  * [Dash](https://kapeli.com/dash) / [DevDocs](http://devdocs.io/) / [Velocity](https://velocity.silverlakesoftware.com/) / [Zeal](https://zealdocs.org/)
* Automation
  * [RobotJS](https://robotjs.io/)

\>\> Return to [Table of Contents](#table-of-contents)

### Collaboration

* Version Control
  * Workflow
    * [Comparing Workflows](https://www.atlassian.com/git/tutorials/comparing-workflows)
    * [Understanding the GitHub Flow](https://guides.github.com/introduction/flow/)
    * [A successful Git branching model](http://nvie.com/posts/a-successful-git-branching-model/)
  * GUI
    * [SourceTree](https://www.sourcetreeapp.com/)
  * Github
    * [GitHub Cheat Sheet](https://github.com/tiimgreen/github-cheat-sheet)
    * [Github Help](https://help.github.com/)
    * [How we organize GitHub issues: A simple styleguide for tagging](https://robinpowered.com/blog/best-practice-system-for-organizing-and-tagging-github-issues/)
    * Chrome Extensions
      * [OctoLinker](https://octolinker.github.io/), [Octotree](https://github.com/buunguyen/octotree), [Code Climate](https://codeclimate.com/browser-extension/)
      * [Awesome browser extensions for GitHub](https://github.com/stefanbuck/awesome-browser-extensions-for-github)
* ChatOps
  * [What is ChatOps? And How do I Get Started?](https://www.pagerduty.com/blog/what-is-chatops/), \
    [What is ChatOps? A guide to its evolution, adoption, and significance](https://www.atlassian.com/blog/software-teams/what-is-chatops-adoption-guide)
  * [Hubot](https://hubot.github.com/)
    * Adapters - [Slack](https://github.com/slackapi/hubot-slack) / [Discord](http://npmjs.com/package/hubot-discord) / [IRC](https://www.npmjs.com/package/hubot-irc) / [Wechat](https://www.npmjs.com/package/hubot-weixin) / [QQ](https://www.npmjs.com/package/hubot-qq)
* Kanban
  * What is Kanban? - [A](https://leankit.com/learn/kanban/what-is-kanban/), [B](http://kanbanblog.com/explained/)
  * [Getting Started With Trello](https://trello.com/guide)
  * [Github Project Boards](https://help.github.com/articles/tracking-the-progress-of-your-work-with-project-boards/)
* Presentation
  * Markdown
    * [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
    * [Markdown: Syntax](https://daringfireball.net/projects/markdown/syntax)
  * Diagram
    * [Mermaid](https://mermaidjs.github.io/)
      * [Mermaid Live Editor](https://mermaidjs.github.io/mermaid-live-editor/)
  * Slides
    * [Remark](https://github.com/gnab/remark)
      * [remarker](https://github.com/kt3k/remarker)
* Design
  * [Sketch](https://www.sketchapp.com/learn/) / [Figma](https://www.figma.com/)
  * [InVision](https://www.invisionapp.com/) / [Atomic](https://atomic.io/) / [Proto.io](https://proto.io/)
  * [Zeplin](https://zeplin.io/) / [Sympli](https://sympli.io/) / [Avocode](https://avocode.com/)
  * [After Effects](http://www.adobe.com/products/aftereffects.html) + [Lottie](https://airbnb.design/lottie/) / [bodymovin](https://github.com/bodymovin/bodymovin) / [Inspector Spacetime](https://google.github.io/inspectorspacetime/) + [Sketch2AE](https://google.github.io/sketch2ae/)

\>\> Return to [Table of Contents](#table-of-contents)
