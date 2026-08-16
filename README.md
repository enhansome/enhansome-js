# Awesome JS with stars

A curated collection of awesome **JavaScript** libraries, tools, runtimes, resources, and shiny things — across **browser**, **Node.js**, **Deno**, **Bun**, **edge/serverless**, **desktop**, and **mobile**.

> Scope: anything primarily built for JavaScript/TypeScript ecosystems (not just browser-side).

* [Awesome JS](#awesome-js)
  * [Runtimes](#runtimes)
  * [Package Managers](#package-managers)
  * [Monorepo & Workspace Tools](#monorepo--workspace-tools)
  * [Module Systems](#module-systems)
  * [Build Tools](#build-tools)
    * [Transpilers](#transpilers)
    * [Bundlers](#bundlers)
    * [Minimizers](#minimizers)
  * [Type Checking & Validation](#type-checking--validation)
  * [Testing](#testing)
    * [Test Runners](#test-runners)
    * [Assertion & Mocking](#assertion--mocking)
    * [E2E / Browser Automation](#e2e--browser-automation)
    * [Coverage](#coverage)
  * [Code Quality](#code-quality)
  * [Documentation](#documentation)
  * [Frontend](#frontend)
    * [UI Frameworks](#ui-frameworks)
    * [State Management](#state-management)
    * [Data Visualization](#data-visualization)
    * [Editors](#editors)
    * [Animations](#animations)
    * [Maps](#maps)
  * [Backend](#backend)
    * [Web Frameworks](#web-frameworks)
    * [API Clients & Data Fetching](#api-clients--data-fetching)
    * [Authentication](#authentication)
    * [ORM & Databases](#orm--databases)
    * [Queues & Jobs](#queues--jobs)
    * [WebSockets](#websockets)
    * [CMS](#cms)
  * [Utilities](#utilities)
    * [Files](#files)
    * [Functional Programming](#functional-programming)
    * [Reactive Programming](#reactive-programming)
    * [Data Structures](#data-structures)
    * [Date & Time](#date--time)
    * [String](#string)
    * [Number](#number)
    * [Storage](#storage)
    * [Color](#color)
    * [I18n & L10n](#i18n--l10n)
    * [Control Flow](#control-flow)
    * [Routing](#routing)
    * [RegExp](#regexp)
    * [Security](#security)
    * [Logging](#logging)
    * [Benchmarking](#benchmarking)
  * [Cross-Platform](#cross-platform)
    * [CLI](#cli)
    * [Desktop Apps](#desktop-apps)
    * [Mobile Apps](#mobile-apps)
  * [AI & ML](#ai--ml)
  * [Generative AI](#generative-ai)
  * [Articles & Posts](#articles--posts)
* [Worth Reading](#worth-reading)
* [Other Awesome Lists](#other-awesome-lists)
* [Contributing](#contributing)
* [License](#license)

***

## Runtimes

*Where JavaScript runs.*

* [Node.js](https://nodejs.org/) - Server-side JavaScript runtime.
* [Deno](https://deno.com/runtime) - Secure runtime with modern tooling built-in.
* [Bun](https://bun.sh/) - Fast runtime + bundler + package manager.
* [Cloudflare Workers](https://developers.cloudflare.com/workers/) - Edge/serverless JavaScript runtime.
* [Electron](https://www.electronjs.org/) - Build cross-platform desktop apps with JavaScript.
* [React Native](https://reactnative.dev/) - Build native mobile apps with JavaScript/TypeScript.

## Package Managers

*Host libraries and provide tools for fetching and packaging them.*

* [npm](https://www.npmjs.com/) - Package manager for JavaScript.
* [yarn](https://yarnpkg.com/) - Fast, reliable dependency management.
* [pnpm](https://pnpm.io/) - Fast, disk space efficient package manager.
* [bun](https://bun.sh/) - Runtime + package manager.
* [jspm](https://github.com/jspm/jspm-cli) ⭐ 3,871 | 🐛 68 | 🌐 TypeScript | 📅 2026-06-29 - Package management & import maps tooling.

<details>
<summary>Legacy / historical</summary>

* [Bower](https://github.com/bower/bower) ⭐ 14,914 | 🐛 15 | 🌐 JavaScript | 📅 2024-10-13 - Legacy front-end package manager.
* [component](https://github.com/componentjs/component) ⚠️ Archived - Client package management for building web apps.
* [Ender](https://github.com/ender-js/Ender) ⚠️ Archived - The no-library library.

</details>

## Monorepo & Workspace Tools

*Manage multiple packages/apps in one repo.*

* [Bit](https://github.com/teambit/bit) ⭐ 18,455 | 🐛 103 | 🌐 TypeScript | 📅 2026-08-16 - Create, find, and reuse components across apps.
* [Changesets](https://github.com/changesets/changesets) ⭐ 12,280 | 🐛 264 | 🌐 TypeScript | 📅 2026-08-16 - Versioning + changelogs for monorepos.
* [Nx](https://nx.dev/) - Smart, fast monorepos for JS/TS.
* [Turborepo](https://turbo.build/repo) - High-performance build system for monorepos.
* [Lerna](https://lerna.js.org/) - Monorepo tooling (often combined with npm/yarn/pnpm workspaces).

## Module Systems

*How code is loaded (ESM/CJS + loaders).*

* [browserify](https://github.com/substack/node-browserify) ⭐ 14,698 | 🐛 380 | 🌐 JavaScript | 📅 2024-12-21 - Bundle Node-style `require()` for browsers.
* [SystemJS](https://github.com/systemjs/systemjs) ⭐ 13,091 | 🐛 77 | 🌐 JavaScript | 📅 2026-06-14 - Dynamic module loader for browsers and Node.
* [RequireJS](https://github.com/requirejs/requirejs) ⭐ 12,913 | 🐛 289 | 🌐 JavaScript | 📅 2025-11-30 - AMD module loader.
* [ES Modules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules) - Standard module system for modern JS.

## Build Tools

### Transpilers

*Convert modern JS/TS syntax into target environments.*

* [SWC](https://swc.rs/) - Fast compiler platform (JS/TS).
* [Babel](https://github.com/babel/babel) ⭐ 43,983 | 🐛 769 | 🌐 TypeScript | 📅 2026-08-16 - JavaScript compiler.

### Bundlers

*Bundle modules and assets.*

* [webpack](https://github.com/webpack/webpack) ⭐ 65,973 | 🐛 142 | 🌐 JavaScript | 📅 2026-08-16 - Mature bundler for complex apps.
* [Parcel](https://github.com/parcel-bundler/parcel) ⭐ 44,023 | 🐛 600 | 🌐 JavaScript | 📅 2026-08-16 - Zero-config bundler.
* [esbuild](https://github.com/evanw/esbuild) ⭐ 40,012 | 🐛 601 | 🌐 Go | 📅 2026-08-09 - Extremely fast bundler/transpiler.
* [Rollup](https://github.com/rollup/rollup) ⭐ 26,303 | 🐛 603 | 🌐 JavaScript | 📅 2026-08-16 - Great for libraries (ESM-first).
* [Microbundle](https://github.com/developit/microbundle) ⭐ 8,130 | 🐛 102 | 🌐 JavaScript | 📅 2026-02-01 - Zero-config bundler for tiny modules.
* [FuseBox](https://github.com/fuse-box/fuse-box) ⚠️ Archived - A bundler that does it right.
* [Vite](https://vite.dev/) - Modern dev server + bundler.
* [Snowpack](https://www.snowpack.dev/) - Modern dev/build tool (historically popular).
* [bundlephobia](https://bundlephobia.com/) - Quick npm package size checker.

### Minimizers

*Minify JS for production.*

* [UglifyJS](https://github.com/mishoo/UglifyJS) ⭐ 13,381 | 🐛 45 | 🌐 JavaScript | 📅 2024-11-22 - Classic minifier (legacy for modern syntax).
* [Terser](https://github.com/terser/terser) ⭐ 9,320 | 🐛 350 | 🌐 JavaScript | 📅 2026-08-14 - Minifier for ES6+.

## Type Checking & Validation

* [Zod](https://github.com/colinhacks/zod) ⭐ 43,471 | 🐛 177 | 🌐 TypeScript | 📅 2026-08-16 - TypeScript-first schema validation.
* [Yup](https://github.com/jquense/yup) ⭐ 23,672 | 🐛 250 | 🌐 TypeScript | 📅 2026-08-12 - Schema builder and validator.
* [Ajv](https://github.com/ajv-validator/ajv) ⭐ 14,807 | 🐛 376 | 🌐 TypeScript | 📅 2026-05-12 - Fast JSON Schema validator.
* [io-ts](https://github.com/gcanti/io-ts) ⭐ 6,809 | 🐛 161 | 🌐 TypeScript | 📅 2024-12-10 - Runtime types + decoding.
* [TypeScript](https://www.typescriptlang.org/) - Typed superset of JavaScript.
* [Flow](https://flow.org/) - Static type checker for JavaScript.

## Testing

### Test Runners

* [Jest](https://github.com/facebook/jest) ⭐ 45,468 | 🐛 186 | 🌐 TypeScript | 📅 2026-08-16 - Painless JavaScript unit testing.
* [Mocha](https://github.com/mochajs/mocha) ⭐ 22,904 | 🐛 257 | 🌐 JavaScript | 📅 2026-08-15 - Flexible test framework for Node and browser.
* [AVA](https://github.com/avajs/ava) ⭐ 20,833 | 🐛 72 | 🌐 JavaScript | 📅 2026-06-17 - Futuristic JavaScript test runner.
* [Tape](https://github.com/substack/tape) ⭐ 5,798 | 🐛 40 | 🌐 JavaScript | 📅 2026-06-18 - Tap-producing test harness.
* [QUnit](https://github.com/qunitjs/qunit) ⭐ 4,035 | 🐛 52 | 🌐 JavaScript | 📅 2026-06-28 - Easy-to-use unit testing framework.
* [Vitest](https://vitest.dev/) - Fast unit test framework powered by Vite.

### Assertion & Mocking

* [Sinon](https://github.com/sinonjs/sinon) ⭐ 9,757 | 🐛 57 | 🌐 JavaScript | 📅 2026-08-05 - Spies, stubs, and mocks.
* [Chai](https://github.com/chaijs/chai) ⭐ 8,267 | 🐛 91 | 🌐 JavaScript | 📅 2026-08-10 - BDD/TDD assertion library.
* [Testing Library](https://testing-library.com/) - Test UI the way users interact.

### E2E / Browser Automation

* [Puppeteer](https://github.com/GoogleChrome/puppeteer) ⭐ 95,464 | 🐛 266 | 🌐 TypeScript | 📅 2026-08-16 - Headless Chrome/Chromium automation.
* [Playwright](https://github.com/microsoft/playwright) ⭐ 94,589 | 🐛 156 | 🌐 TypeScript | 📅 2026-08-16 - Automate Chromium/Firefox/WebKit.
* [TestCafe](https://github.com/DevExpress/testcafe) ⭐ 9,908 | 🐛 35 | 🌐 JavaScript | 📅 2026-08-12 - Automated browser testing.
* [Cypress](https://www.cypress.io/) - End-to-end testing framework.
* [WebdriverIO](https://webdriver.io/) - Node.js browser/mobile automation.

### Coverage

* [Istanbul / nyc](https://github.com/istanbuljs/nyc) ⭐ 5,766 | 🐛 207 | 🌐 JavaScript | 📅 2026-05-17 - Coverage reporting.
* [c8](https://github.com/bcoe/c8) ⭐ 2,118 | 🐛 116 | 🌐 JavaScript | 📅 2026-08-10 - Coverage using V8’s built-in coverage.

## Code Quality

*Format, lint, and keep code healthy.*

* [Prettier](https://github.com/prettier/prettier) ⭐ 52,203 | 🐛 1,428 | 🌐 JavaScript | 📅 2026-08-16 - Opinionated formatter.
* [Husky](https://github.com/typicode/husky) ⭐ 35,275 | 🐛 108 | 🌐 JavaScript | 📅 2026-03-19 - Git hooks made easy.
* [Standard](https://github.com/standard/standard) ⭐ 29,427 | 🐛 130 | 🌐 JavaScript | 📅 2025-07-11 - JavaScript Standard Style.
* [ESLint](https://github.com/eslint/eslint) ⭐ 27,457 | 🐛 130 | 🌐 JavaScript | 📅 2026-08-16 - Pluggable linting utility.
* [lint-staged](https://github.com/lint-staged/lint-staged) ⭐ 14,713 | 🐛 10 | 🌐 JavaScript | 📅 2026-08-08 - Run linters on staged files.
* [Biome](https://biomejs.dev/) - Fast formatter + linter (JS/TS).

## Documentation

*Write and publish docs, API refs, and guides.*

* [DevDocs](https://devdocs.io/) - Fast API documentation browser.
* [Docusaurus](https://docusaurus.io/) - Documentation site generator.
* [VitePress](https://vitepress.dev/) - Vite-powered docs.
* [Docsify](https://docsify.js.org/) - Docs site without a build step.
* [Storybook](https://storybook.js.org/) - UI component workshop + docs.
* [typedoc](https://typedoc.org/) - TypeScript API documentation.

## Frontend

### UI Frameworks

* [Preact](https://github.com/preactjs/preact) ⭐ 38,820 | 🐛 39 | 🌐 JavaScript | 📅 2026-08-13 - Fast, small React alternative.
* [Alpine.js](https://github.com/alpinejs/alpine) ⭐ 31,861 | 🐛 5 | 🌐 HTML | 📅 2026-08-14 - Minimal reactive framework.
* [React](https://react.dev/) - UI library.
* [Vue](https://vuejs.org/) - Progressive framework.
* [Svelte](https://svelte.dev/) - Compiler-based UI framework.
* [Angular](https://angular.dev/) - Full-featured framework (TypeScript).
* [Solid](https://www.solidjs.com/) - Fine-grained reactivity.

### State Management

* [Zustand](https://github.com/pmndrs/zustand) ⭐ 58,575 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-13 - Small, fast state management for React.
* [MobX](https://github.com/mobxjs/mobx) ⭐ 28,201 | 🐛 67 | 🌐 TypeScript | 📅 2026-08-02 - Simple, scalable state management.
* [Redux](https://redux.js.org/) - Predictable state container.
* [XState](https://xstate.js.org/) - State machines and statecharts.

### Data Visualization

* [Three.js](https://github.com/mrdoob/three.js) ⭐ 114,561 | 🐛 368 | 🌐 JavaScript | 📅 2026-08-16 - 3D library.
* [D3](https://github.com/d3/d3) ⭐ 113,480 | 🐛 20 | 🌐 Shell | 📅 2026-05-28 - Visualization library for HTML/SVG/Canvas.
* [Chart.js](https://github.com/chartjs/Chart.js) ⭐ 67,645 | 🐛 579 | 🌐 JavaScript | 📅 2026-05-27 - Simple canvas charts.
* [ECharts](https://github.com/apache/echarts) ⭐ 67,084 | 🐛 1,556 | 🌐 TypeScript | 📅 2026-08-04 - Powerful charting.
* [Vega](https://github.com/vega/vega) ⭐ 11,960 | 🐛 470 | 🌐 JavaScript | 📅 2026-08-14 - Visualization grammar.
* [Cytoscape.js](https://github.com/cytoscape/cytoscape.js) ⭐ 11,166 | 🐛 19 | 🌐 JavaScript | 📅 2026-08-14 - Graph theory visualizations.

### Editors

* [Quill](https://github.com/quilljs/quill) ⭐ 47,299 | 🐛 659 | 🌐 TypeScript | 📅 2025-07-25 - Rich text editor.
* [Ace](https://github.com/ajaxorg/ace) ⭐ 27,141 | 🐛 140 | 🌐 JavaScript | 📅 2026-08-13 - Browser code editor.
* [TinyMCE](https://github.com/tinymce/tinymce) ⭐ 16,271 | 🐛 418 | 🌐 TypeScript | 📅 2026-08-16 - Rich text editor.
* [CodeMirror](https://github.com/codemirror/dev) ⚠️ Archived - Code editor.
* [Monaco Editor](https://microsoft.github.io/monaco-editor/) - VS Code editor core.

### Animations

* [GSAP](https://gsap.com/) - High-performance animations.
* [anime.js](https://animejs.com/) - Animation engine.
* [motion](https://motion.dev/) - Modern animation library.
* [three.js](https://github.com/mrdoob/three.js) ⭐ 114,561 | 🐛 368 | 🌐 JavaScript | 📅 2026-08-16 - 3D animations and scenes.

### Maps

* [Leaflet](https://github.com/Leaflet/Leaflet) ⭐ 45,483 | 🐛 558 | 🌐 JavaScript | 📅 2026-08-10 - Interactive maps.
* [Cesium](https://github.com/CesiumGS/cesium) ⭐ 15,572 | 🐛 1,639 | 🌐 JavaScript | 📅 2026-08-15 - 3D globes and maps.
* [MapLibre GL JS](https://maplibre.org/maplibre-gl-js/docs/) - Open-source WebGL maps.
* [OpenLayers](https://openlayers.org/) - Feature-packed mapping library.

## Backend

### Web Frameworks

* [Express](https://expressjs.com/) - Minimal Node.js web framework.
* [Fastify](https://www.fastify.io/) - Fast, schema-based framework.
* [NestJS](https://nestjs.com/) - Opinionated framework (TypeScript-first).
* [Koa](https://koajs.com/) - Lightweight middleware framework.
* [Hono](https://hono.dev/) - Small, fast framework for edge runtimes (also Node).
* [SvelteKit](https://kit.svelte.dev/) - Full-stack Svelte framework.
* [Next.js](https://nextjs.org/) - Full-stack React framework.

### API Clients & Data Fetching

* [axios](https://github.com/axios/axios) ⭐ 109,205 | 🐛 65 | 🌐 JavaScript | 📅 2026-08-13 - HTTP client for Node and browser.
* [TanStack Query](https://github.com/TanStack/query) ⭐ 50,148 | 🐛 245 | 🌐 TypeScript | 📅 2026-08-16 - Async state + caching.
* [SWR](https://github.com/vercel/swr) ⭐ 32,457 | 🐛 213 | 🌐 TypeScript | 📅 2026-08-13 - React Hooks data fetching.
* [ky](https://github.com/sindresorhus/ky) ⭐ 17,026 | 🐛 2 | 🌐 TypeScript | 📅 2026-07-06 - Tiny Fetch-based HTTP client.

### Authentication

* [Passport](https://www.passportjs.org/) - Authentication middleware for Node.
* [Lucia](https://lucia-auth.com/) - Auth library (TypeScript-friendly).
* [NextAuth.js](https://authjs.dev/) - Authentication for Next.js and beyond.

### ORM & Databases

* [Prisma](https://github.com/prisma/prisma) ⭐ 47,577 | 🐛 2,537 | 🌐 TypeScript | 📅 2026-08-14 - Type-safe ORM.
* [TypeORM](https://github.com/typeorm/typeorm) ⭐ 36,632 | 🐛 614 | 🌐 TypeScript | 📅 2026-08-13 - ORM for TS/JS.
* [Drizzle ORM](https://github.com/drizzle-team/drizzle-orm) ⭐ 35,493 | 🐛 1,952 | 🌐 TypeScript | 📅 2026-08-12 - SQL-first TypeScript ORM.
* [Sequelize](https://github.com/sequelize/sequelize) ⭐ 30,375 | 🐛 1,074 | 🌐 TypeScript | 📅 2026-08-16 - Feature-rich ORM.
* [Mongoose](https://github.com/Automattic/mongoose) ⭐ 27,473 | 🐛 173 | 🌐 JavaScript | 📅 2026-08-14 - MongoDB object modeling.
* [Knex](https://github.com/knex/knex) ⭐ 20,341 | 🐛 735 | 🌐 JavaScript | 📅 2026-06-26 - SQL query builder.
* [Kysely](https://github.com/kysely-org/kysely) ⭐ 14,133 | 🐛 169 | 🌐 TypeScript | 📅 2026-08-14 - Type-safe SQL query builder.

### Queues & Jobs

* [Agenda](https://github.com/agenda/agenda) ⭐ 9,696 | 🐛 42 | 🌐 HTML | 📅 2026-07-21 - Job scheduling for Node.
* [BullMQ](https://github.com/taskforcesh/bullmq) ⭐ 9,301 | 🐛 365 | 🌐 TypeScript | 📅 2026-08-16 - Redis-backed queue.
* [Bree](https://github.com/breejs/bree) ⭐ 3,290 | 🐛 29 | 🌐 JavaScript | 📅 2026-02-17 - Job scheduler using worker threads.

### WebSockets

* [Socket.IO](https://github.com/socketio/socket.io) ⭐ 63,194 | 🐛 188 | 🌐 TypeScript | 📅 2026-07-24 - Realtime framework with fallbacks.
* [ws](https://github.com/websockets/ws) ⭐ 22,791 | 🐛 5 | 🌐 JavaScript | 📅 2026-08-13 - Fast WebSocket implementation.

### CMS

* [Strapi](https://github.com/strapi/strapi) ⭐ 72,940 | 🐛 543 | 🌐 TypeScript | 📅 2026-08-16 - Open-source headless CMS.
* [Ghost](https://github.com/tryghost/Ghost) ⭐ 54,788 | 🐛 130 | 🌐 JavaScript | 📅 2026-08-16 - Publishing platform.
* [KeystoneJS](https://github.com/keystonejs/keystone) ⭐ 9,942 | 🐛 144 | 🌐 TypeScript | 📅 2026-08-11 - CMS + app framework.

## Utilities

### Files

* [PDF.js](https://github.com/mozilla/pdf.js) ⭐ 53,738 | 🐛 416 | 🌐 JavaScript | 📅 2026-08-16 - PDF reader in JavaScript.
* [jsPDF](https://github.com/parallax/jsPDF) ⭐ 31,274 | 🐛 120 | 🌐 JavaScript | 📅 2026-08-09 - PDF generation.
* [Papa Parse](https://github.com/mholt/PapaParse) ⭐ 13,543 | 🐛 224 | 🌐 JavaScript | 📅 2026-08-13 - CSV parsing.
* [diff2html](https://github.com/rtfpessoa/diff2html) ⭐ 3,394 | 🐛 34 | 🌐 TypeScript | 📅 2026-05-08 - Git diff → pretty HTML.

### Functional Programming

* [lodash](https://github.com/lodash/lodash) ⭐ 61,286 | 🐛 106 | 🌐 JavaScript | 📅 2026-07-03 - Utility library.
* [underscore](https://github.com/jashkenas/underscore) ⭐ 27,337 | 🐛 52 | 🌐 JavaScript | 📅 2026-08-12 - Utility belt.
* [ramda](https://github.com/ramda/ramda) ⭐ 24,058 | 🐛 146 | 🌐 JavaScript | 📅 2026-07-26 - Practical FP library.
* [fxjs](https://github.com/marpple/FxTS) ⭐ 1,165 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-08 - Lazy evaluation + concurrency helpers.

### Reactive Programming

* [RxJS](https://github.com/ReactiveX/rxjs) ⭐ 31,706 | 🐛 179 | 🌐 TypeScript | 📅 2026-08-08 - Reactive programming library.
* [Bacon.js](https://github.com/baconjs/bacon.js) ⭐ 6,457 | 🐛 86 | 🌐 TypeScript | 📅 2025-04-18 - FRP library.
* [Most.js](https://github.com/cujojs/most) ⭐ 3,489 | 🐛 50 | 🌐 JavaScript | 📅 2022-12-06 - High-performance FRP library.

### Data Structures

* [immutable-js](https://github.com/immutable-js/immutable-js) ⭐ 33,039 | 🐛 128 | 🌐 TypeScript | 📅 2026-08-16 - Persistent data structures.
* [js-sdsl](https://github.com/zly201/js-sdsl) ⚠️ Archived - STL-like containers for JS.

### Date & Time

* [dayjs](https://github.com/iamkun/dayjs) ⭐ 48,665 | 🐛 1,297 | 🌐 JavaScript | 📅 2026-08-16 - Small Moment-like API.
* [date-fns](https://github.com/date-fns/date-fns) ⭐ 36,625 | 🐛 992 | 🌐 TypeScript | 📅 2026-08-10 - Modern date utility library.
* [luxon](https://github.com/moment/luxon) ⭐ 16,440 | 🐛 178 | 🌐 JavaScript | 📅 2026-08-09 - Dates and times with Intl.
* [ms](https://github.com/vercel/ms) ⭐ 5,544 | 🐛 35 | 🌐 TypeScript | 📅 2026-05-20 - Millisecond conversion utility.

### String

* [query-string](https://github.com/sindresorhus/query-string) ⭐ 6,904 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-06 - Parse/stringify URL query strings.
* [he](https://github.com/mathiasbynens/he) ⭐ 3,598 | 🐛 23 | 🌐 JavaScript | 📅 2021-12-29 - HTML entity encoder/decoder.
* [sprintf.js](https://github.com/alexei/sprintf.js) ⭐ 2,139 | 🐛 63 | 🌐 JavaScript | 📅 2024-04-05 - sprintf implementation.

### Number

* [Numeral.js](https://github.com/adamwdraper/Numeral-js) ⭐ 9,704 | 🐛 345 | 🌐 JavaScript | 📅 2026-02-15 - Number formatting.
* [chance](https://github.com/chancejs/chancejs) ⭐ 6,540 | 🐛 174 | 🌐 JavaScript | 📅 2025-05-18 - Random generator helpers.
* [Fraction.js](https://github.com/infusion/Fraction.js) ⭐ 691 | 🐛 5 | 🌐 JavaScript | 📅 2025-09-26 - Rational numbers.

### Storage

* [localForage](https://github.com/localForage/localForage) ⭐ 25,799 | 🐛 250 | 🌐 JavaScript | 📅 2024-07-30 - Offline storage wrapper.
* [js-cookie](https://github.com/js-cookie/js-cookie) ⭐ 22,595 | 🐛 11 | 🌐 JavaScript | 📅 2026-08-10 - Cookie API.
* [Dexie.js](https://github.com/dexie/Dexie.js) ⭐ 14,537 | 🐛 594 | 🌐 TypeScript | 📅 2026-08-14 - IndexedDB wrapper.

### Color

* [chroma.js](https://github.com/gka/chroma.js) ⭐ 10,575 | 🐛 76 | 🌐 JavaScript | 📅 2026-06-01 - Color manipulations.
* [randomColor](https://github.com/davidmerfield/randomColor) ⭐ 6,125 | 🐛 16 | 🌐 JavaScript | 📅 2025-12-03 - Color generator.
* [TinyColor](https://github.com/bgrins/TinyColor) ⭐ 5,247 | 🐛 105 | 🌐 JavaScript | 📅 2024-06-26 - Color manipulation/conversion.

### I18n & L10n

* [i18next](https://github.com/i18next/i18next) ⭐ 8,616 | 🐛 2 | 🌐 JavaScript | 📅 2026-07-09 - Internationalization framework.
* [ttag](https://github.com/ttag-org/ttag) ⭐ 354 | 🐛 51 | 🌐 TypeScript | 📅 2025-07-01 - Modern i18n using tagged templates.

### Control Flow

* [async](https://github.com/caolan/async) ⭐ 28,143 | 🐛 23 | 🌐 JavaScript | 📅 2026-08-07 - Async utilities.
* [p-limit](https://github.com/sindresorhus/p-limit) ⭐ 2,912 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-20 - Limit concurrent promises.
* [p-retry](https://github.com/sindresorhus/p-retry) ⭐ 1,025 | 🐛 1 | 🌐 JavaScript | 📅 2026-03-26 - Retry async functions.

### Routing

* [page.js](https://github.com/visionmedia/page.js) ⭐ 7,679 | 🐛 126 | 🌐 JavaScript | 📅 2023-06-27 - Micro client-side router.
* [director](https://github.com/flatiron/director) ⭐ 5,575 | 🐛 124 | 🌐 JavaScript | 📅 2020-12-26 - Isomorphic router.

### RegExp

* [Regex101](https://regex101.com/#javascript) - Online regex tester/debugger.
* [RegExr](https://regexr.com/) - Regex editor and learning tool.

### Security

* [DOMPurify](https://github.com/cure53/DOMPurify) ⭐ 17,307 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-16 - XSS sanitizer for HTML/SVG/MathML.
* [js-xss](https://github.com/leizongmin/js-xss) ⭐ 5,314 | 🐛 69 | 🌐 HTML | 📅 2026-05-06 - Sanitize untrusted HTML.
* [sanitize-html](https://github.com/apostrophecms/sanitize-html) ⚠️ Archived - HTML sanitizer.

### Logging

* [winston](https://github.com/winstonjs/winston) ⭐ 24,504 | 🐛 528 | 🌐 JavaScript | 📅 2026-07-20 - Multi-transport async logging.
* [pino](https://github.com/pinojs/pino) ⭐ 18,138 | 🐛 164 | 🌐 JavaScript | 📅 2026-08-13 - Very fast logger for Node.
* [loglevel](https://github.com/pimterry/loglevel) ⭐ 2,746 | 🐛 19 | 🌐 JavaScript | 📅 2025-03-20 - Minimal log level wrapper.

### Benchmarking

* [benchmark.js](https://github.com/bestiejs/benchmark.js) ⚠️ Archived - Benchmarking library.
* [matcha](https://github.com/logicalparadox/matcha) ⭐ 561 | 🐛 17 | 🌐 JavaScript | 📅 2020-09-04 - Simple benchmarking runner.

## Cross-Platform

### CLI

* [zx](https://github.com/google/zx) ⭐ 45,668 | 🐛 56 | 🌐 JavaScript | 📅 2026-08-14 - Write shell scripts in JavaScript.
* [commander](https://github.com/tj/commander.js) ⭐ 28,367 | 🐛 6 | 🌐 JavaScript | 📅 2026-08-11 - CLI framework.
* [yargs](https://github.com/yargs/yargs) ⭐ 11,511 | 🐛 215 | 🌐 JavaScript | 📅 2026-08-07 - CLI argument parsing.
* [oclif](https://github.com/oclif/oclif) ⭐ 9,576 | 🐛 22 | 🌐 TypeScript | 📅 2026-08-10 - Opinionated CLI framework.

### Desktop Apps

* [Electron](https://www.electronjs.org/) - Cross-platform desktop apps.
* [Tauri](https://tauri.app/) - Smaller desktop apps (JS frontend + Rust core).

### Mobile Apps

* [React Native](https://reactnative.dev/) - Native mobile apps with JS/TS.
* [Expo](https://expo.dev/) - Tooling + platform for React Native apps.
* [Ionic](https://ionicframework.com/) - Hybrid app framework.

## AI & ML

* [TensorFlow.js](https://www.tensorflow.org/js/) - Train/deploy ML models in JS.
* [Brain.js](https://github.com/BrainJS/brain.js) ⭐ 14,867 | 🐛 90 | 🌐 TypeScript | 📅 2024-09-26 - Neural networks in JavaScript.
* [ml5.js](https://ml5js.org/) - Friendly ML for the web.

## Generative AI

* [LangChain.js](https://github.com/langchain-ai/langchainjs) ⭐ 18,109 | 🐛 515 | 🌐 TypeScript | 📅 2026-08-14 - LLM application framework for JS/TS.
* [OpenAI SDK](https://github.com/openai/openai-node) ⭐ 11,119 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-15 - Official JavaScript/TypeScript library for the OpenAI API.
* [Vercel AI SDK](https://sdk.vercel.ai/docs) - Build AI features for web apps.

## Articles & Posts

* [javascript-algorithms](https://github.com/trekhleb/javascript-algorithms) ⭐ 196,495 | 🐛 404 | 🌐 JavaScript | 📅 2026-07-26 - Algorithms and data structures in JS.
* [Clean Code JavaScript](https://github.com/ryanmcdermott/clean-code-javascript) ⭐ 94,761 | 🐛 123 | 🌐 JavaScript | 📅 2024-07-29 - Clean Code ideas adapted for JS.
* [Roadmap.sh JavaScript Roadmap](https://roadmap.sh/javascript) - Community learning roadmap.

# Worth Reading

* [You Don’t Know JS Yet](https://github.com/getify/You-Dont-Know-JS) ⭐ 184,684 | 🐛 2 | 📅 2026-02-15 - Deep dive series on JS fundamentals and internals.
* [braziljs/js-the-right-way](https://github.com/braziljs/js-the-right-way/) ⭐ 8,677 | 🐛 0 | 🌐 HTML | 📅 2026-07-29 - Quick reference for JS best practices.
* [Superhero.js](http://superherojs.com) - Resources for creating and maintaining large JS codebases.

# Other Awesome Lists

* [sindresorhus/awesome](https://github.com/sindresorhus/awesome) ⭐ 496,563 | 🐛 100 | 📅 2026-06-30
* [enaqx/awesome-react](https://github.com/enaqx/awesome-react) ⭐ 74,294 | 🐛 74 | 📅 2026-07-20
* [denolib/awesome-deno](https://github.com/denolib/awesome-deno) ⭐ 4,411 | 🐛 2 | 📅 2026-08-14
* [apvarun/awesome-bun](https://github.com/apvarun/awesome-bun) ⭐ 3,641 | 🐛 89 | 📅 2025-07-20

# Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

# License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-16._
