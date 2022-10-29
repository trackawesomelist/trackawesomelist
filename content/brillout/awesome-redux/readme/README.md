# Awesome Redux Overview

Catalog of Redux Libraries & Learning Material

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/brillout/awesome-redux/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 brillout/awesome-redux](https://github.com/brillout/awesome-redux) · ⭐ 363 · 🏷️ Front-End Development

[ [Daily](/content/brillout/awesome-redux/README.md) / [Weekly](/content/brillout/awesome-redux/week/README.md) / Overview ]

---

# Redux Libraries & Learning Material [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://rawgit.com/brillout/awesome-redux/master/redux-logo.svg" align="right" width="110">](http://redux.js.org/)

> Redux is a state container for JavaScript apps.

*   Official website: [`devarchy.com/redux`](https://devarchy.com/redux)
*   Use devarchy to add a library to the catalog

 <br/>

#### Contents

*   [Code Architecture](#code-architecture)
*   [Utilities](#utilities)
*   [Code Style](#code-style)
*   [Dev tools / Inspection tools](#dev-tools--inspection-tools)
*   [React Integration](#react-integration)
*   [Other Integrations](#other-integrations)
*   [Boilerplate](#boilerplate)
*   [Miscellaneous](#miscellaneous)
*   [Learning Material](#learning-material)
*   [Community](#community)

<br/>

## Code Architecture

*Aims to improve the overall structure of the source code. Makes reasoning about the code easier.*

*   [redux-schema](https://github.com/ddsol/redux-schema) - Automatic actions, reducers and validation for Redux.
*   [redux-tcomb](https://github.com/gcanti/redux-tcomb) - Immutable and type-checked state and actions for Redux.
*   [redux-action-tree](https://github.com/cerebral/redux-action-tree) - The Cerebral signals running with Redux.
*   [redux-elm](https://github.com/salsita/redux-elm) - The Elm Architecture in JavaScript.

## Utilities

*   [redux-orm](https://github.com/tommikaikkonen/redux-orm) - Small, simple and immutable ORM to manage relational data in your Redux store.
*   [redux-api-middleware](https://github.com/agraboso/redux-api-middleware) - Redux middleware for calling an API.
*   [redux-ignore](https://github.com/omnidan/redux-ignore) - Higher-order reducer to ignore Redux actions.
*   [redux-modifiers](https://github.com/calvinfroedge/redux-modifiers) - Collection of generic functions for writing Redux reducers to operate on various data structures.
*   [rereduce](https://github.com/slorber/rereduce) - Reducer library for Redux.
*   [redux-search](https://github.com/treasure-data/redux-search) - Redux bindings for client-side search.
*   [redux-logger](https://github.com/evgenyrodionov/redux-logger) - Logger middleware for Redux.
*   [redux-immutable](https://github.com/gajus/redux-immutable) - Redux-immutable is used to create an equivalent function of Redux combineReducers that works with Immutable.js state.
*   [reselect](https://github.com/reactjs/reselect) - Selector library for Redux.
*   [redux-requests](https://github.com/idolize/redux-requests) - Manages in-flight requests with a Redux reducer to avoid issuing duplicate requests.
*   [redux-undo](https://github.com/omnidan/redux-undo) - Higher order reducer to add undo/redo functionality to Redux state containers.
*   [redux-bug-reporter](https://github.com/dtschust/redux-bug-reporter) - Bug reporter and bug playback tool for Redux.
*   [redux-transducers](https://github.com/acdlite/redux-transducers) - Transducer utilities for Redux.

### Store Persistence

*   [redux-storage](https://github.com/michaelcontento/redux-storage) - Persistence layer for Redux with flexible backends.
*   [redux-persist](https://github.com/rt2zz/redux-persist) - Persist and rehydrate a Redux store.

### Side Effects

*Side Effects / Asynchronous Actions*

*   [redux-saga](https://github.com/yelouafi/redux-saga) - Alternative side effect model for Redux apps.
*   [redux-promise-middleware](https://github.com/pburtchaell/redux-promise-middleware) - Redux middleware for resolving and rejecting promises with conditional optimistic updates.
*   [redux-effects](https://github.com/redux-effects/redux-effects) - You write pure functions, redux-effects handles the rest.
*   [redux-thunk](https://github.com/gaearon/redux-thunk) - Thunk middleware for Redux.
*   [redux-connect](https://github.com/makeomatic/redux-connect) - Provides decorator for resolving async props in react-router, extremely useful for handling server-side rendering in React.
*   [redux-loop](https://github.com/redux-loop/redux-loop) - Port of elm-effects and the Elm Architecture to Redux that allows you to sequence your effects naturally and purely by returning them from your reducers.
*   [redux-side-effects](https://github.com/salsita/redux-side-effects) - Redux toolset for keeping all the side effects inside your reducers while maintaining their purity.
*   [redux-logic](https://github.com/jeffbski/redux-logic) - Redux middleware for organizing business logic and action side effects.
*   [redux-observable](https://github.com/redux-observable/redux-observable) - RxJS middleware for action side effects in Redux using "Epics".
*   [redux-ship](https://github.com/clarus/redux-ship) - Composable, testable and typable side effects.

## Code Style

*Aims to make parts of the source code easier to read/write.*

*   [redux-act](https://github.com/pauldijou/redux-act) - Opinionated lib to create actions and reducers for Redux.
*   [redux-crud](https://github.com/Versent/redux-crud) - Set of standard actions and reducers for Redux CRUD Applications.

## Dev tools / Inspection tools

*   [redux-devtools-inspector](https://github.com/alexkuz/redux-devtools-inspector) - Another Redux DevTools Monitor.
*   [redux-diff-logger](https://github.com/fcomb/redux-diff-logger) - Diff logger between states for Redux.
*   [redux-devtools-chart-monitor](https://github.com/romseguy/redux-devtools-chart-monitor) - Chart monitor for Redux DevTools.
*   [redux-devtools](https://github.com/gaearon/redux-devtools) - DevTools for Redux with hot reloading, action replay, and customizable UI.
*   [redux-devtools-dispatch](https://github.com/YoruNoHikage/redux-devtools-dispatch) - Dispatch your actions manually to test if your app Reacts well.
*   [redux-devtools-dock-monitor](https://github.com/gaearon/redux-devtools-dock-monitor) - Resizable and movable dock for Redux DevTools monitors.
*   [redux-devtools-filterable-log-monitor](https://github.com/bvaughn/redux-devtools-filterable-log-monitor) - Filterable tree view monitor for Redux DevTools.
*   [redux-devtools-log-monitor](https://github.com/gaearon/redux-devtools-log-monitor) - The default monitor for Redux DevTools with a tree view.
*   [remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) - Redux DevTools remotely.

## React Integration

*   [redux-test-recorder](https://github.com/conorhastings/redux-test-recorder) - Redux middleware to automatically generate tests for reducers through ui interaction.
*   [react-redux](https://github.com/reactjs/react-redux) - Official React bindings for Redux.
*   [react-easy-universal](https://github.com/keystonejs/react-easy-universal) - Universal Routing & Rendering with React & Redux was too hard. Now it's easy.
*   [redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) - Set of wrapper components to facilitate using Material UI with Redux Form.

### Routing

*   [redux-async-connect](https://github.com/Rezonans/redux-async-connect) - It allows you to request async data, store them in Redux state and connect them to your React component.
*   [redux-tiny-router](https://github.com/Agamennon/redux-tiny-router) - Router made for Redux and made for universal apps. Stop using the router as a controller, it's just state.
*   [redux-router](https://github.com/acdlite/redux-router) - Redux bindings for React Router – keep your router state inside your Redux store.
*   [react-router-redux](https://github.com/reactjs/react-router-redux) - Ruthlessly simple bindings to keep react-router and Redux in sync.
*   [ground-control](https://github.com/raisemarketplace/ground-control) - Scalable reducer management & powerful data fetching for React Router & Redux.

### Forms

*   [redux-form](https://github.com/erikras/redux-form) - Higher Order Component using react-redux to keep form state in a Redux store.
*   [react-redux-form](https://github.com/davidkpiano/react-redux-form) - Create forms easily in React with Redux.

### Component State

*   [redux-react-local](https://github.com/threepointone/redux-react-local) - Local component state via Redux.
*   [redux-ui](https://github.com/tonyhb/redux-ui) - Easy UI state management for React Redux.

## Other Integrations

### Flux

*   [redux-actions](https://github.com/acdlite/redux-actions) - Flux Standard Action utilities for Redux.
*   [redux-promise](https://github.com/acdlite/redux-promise) - FSA-compliant promise middleware for Redux.

### Backbone

*   [backbone-redux](https://github.com/redbooth/backbone-redux) - Easy way to keep your backbone collections and Redux store in sync.

### Falcor

*   [redux-falcor](https://github.com/ekosz/redux-falcor) - Connect your Redux front-end to your falcor back-end.

### RxJS

*   [redux-observable](https://github.com/redux-observable/redux-observable) - RxJS middleware for action side effects in Redux using "Epics".
*   [rx-redux](https://github.com/jas-chen/rx-redux) - Reimplementation of Redux using RxJS.
*   [redux-rx](https://github.com/acdlite/redux-rx) - RxJS utilities for Redux.
*   [redurx](https://github.com/shiftyp/redurx) - Redux'ish Functional State Management using RxJS.

### Electron

*   [redux-electron-store](https://github.com/samiskin/redux-electron-store) - Redux store enhancer that allows automatic synchronization between electron processes.

### Deku

*   [deku-redux](https://github.com/troch/deku-redux) - Bindings for Redux in deku < v2.

### Other

*   [redux-rollbar-middleware](https://github.com/netguru/redux-rollbar-middleware) - Redux middleware that wraps exceptions in actions and sends them to Rollbar with current state.
*   [kasia](https://github.com/outlandishideas/kasia) - React Redux toolset for the WordPress API.

## Boilerplate

*Boilerplates /  Scaffolds / Starter Kits / Generators / Stack Ensembles*

*   [redux-cli](https://github.com/SpencerCDixon/redux-cli) - Opinionated CLI for building Redux/React apps quicker.
*   [reactuate](https://github.com/reactuate/reactuate) - React/Redux stack (not a boilerplate kit).
*   [react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) - Boilerplate for Chrome Extension React.js project.
*   [universal-redux](https://github.com/bdefore/universal-redux) - Npm package that lets you jump right into coding React and Redux with universal (isomorphic) rendering. Only manage Express setups or Webpack configurations if you want to.
*   [generator-react-aspnet-boilerplate](https://github.com/pauldotknopf/react-aspnet-boilerplate) - Starting point for building isomorphic React applications with ASP.NET Core 1, leveraging existing techniques.
*   [generator-redux](https://github.com/banderson/generator-redux) - CLI tools for Redux: next-gen functional Flux/React with devtools.
*   [generator-react-webpack-redux](https://github.com/stylesuxx/generator-react-webpack-redux) - React Webpack Generator including Redux support.
*   [socrates](https://github.com/matthewmueller/socrates) - Small (8kb), batteries-included Redux store to reduce boilerplate and promote good habits.

## Miscellaneous

*   [redux-core](https://github.com/jas-chen/redux-core) - Minimal Redux.

## Learning Material

*   **Redux's concepts**

    [Redux official documentation](http://redux.js.org/) does a great job at explaining Redux's core principles.

*   **Why immutable data structures**

    The [guide on performance](https://facebook.github.io/react/docs/advanced-performance.html) of React's official documentation explains well what immutable data structures are and why they play an important role.

*   **Side Effects**

    [Redux Loop's readme](https://github.com/redux-loop/redux-loop) gives a good insight on Side Effects in the context of Redux.

Reading the aforementioned material will get you a good start for writing apps with Redux.
If you are curious for more, check out following resources.

*   **Functional Programming - Basics**

    This [post](http://jaysoo.ca/2016/01/13/functional-programming-little-ideas/) goes over basic concepts of functional programming while building a YouTube instant search demo app.

*   **Reactive Programming**

    This [introduction to Reactive Programming](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754) explains Reactive Programming with clarity.

*   **Functional Programming - Going beyond**

    Well written [article](https://medium.com/@chetcorcos/functional-programming-for-javascript-people-1915d8775504) that talks about interesting computer science concepts implemented in functional languages and how these apply to JavaScript.

*   **Monads**

    Curious about monads? Wikipedia gives a good [overview on monads](https://en.wikipedia.org/wiki/Monad_\(functional_programming\)) and [this article](http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html) explains monads in more details with graphics and simple examples.

## Community

*   [Reddit](https://www.reddit.com/r/reduxjs/)
*   [Stack Overflow](http://stackoverflow.com/questions/tagged/redux)
*   [Discord](https://discord.gg/0ZcbPKXt5bZ6au5t)
*   [Slack](http://slack.redux.io/)
*   [Gitter](https://gitter.im/reactjs/redux)
*   [`#rackt` on freenode](https://webchat.freenode.net/)

