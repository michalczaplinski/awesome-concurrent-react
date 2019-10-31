<div align="center">
	<a href="react_concurrent_logo.png"><img src="react_concurrent_logo.png" alt="react-concurrent-logo"></a>
	<br>
	<br>
	<br>
</div>

# Awesome Concurrent React [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> List of resources about the React Concurrent Mode (previously called React Suspense). 

React Concurrent is the set of new, experimental React features that allow for:
- React rendering to run concurrently to other browser processes which allows for e.g. `native` input to "interrupt" rendering.
- "Suspend" the rendering until all of component's dependencies (data or code) are available and show a fallback until then.

## Contents
- [Documentation](#documentation)
- [Talks](#talks)
- [Data Fetching](#data-fetching)
- [Demos](#demos)

## Documentation

- [Official React Docs](https://reactjs.org/docs/concurrent-mode-intro.html)
- [concurrent-react-notes](https://github.com/sw-yx/concurrent-react-notes) - Unofficial notes by [@swyx](https://github.com/sw-yx). Useful for a historical perspective.

## Talks

- [Dan Abramov - Suspense! - ReactFest 2018](https://www.youtube.com/watch?v=6g3g0Q_XVb4&feature=youtu.be) - The talk that introduced the idea of Suspense and React Concurrent in 2018.
- [Yuzhi Zheng - Keynote - ReactConf 2019](https://www.youtube.com/watch?v=uXEEL9mrkAQ) - Discussing Selective Hydration, Suspense, Concurrent Mode, and more.
- [Joe Savona - Data Fetching With Suspense In Relay - ReactConf 2019](https://www.youtube.com/watch?v=Tl0S7QkxFE4) - Fetching data using Concurrent React at Facebook.

## Data Fetching

- [relay](https://relay.dev/docs/en/experimental/a-guided-tour-of-relay#loading-states-with-suspense) - Official bindings for facebook relay library.
- [swr](https://github.com/zeit/swr) - React Hooks library for remote data fetching.
- [react-async](https://github.com/async-library/react-async) - Flexible promise-based React data loader.
- [react-fetching-library](https://github.com/marcin-piela/react-fetching-library) - API client for react with Suspense support.
- [fetch-suspense](https://github.com/CharlesStover/fetch-suspense) - A React fetch hook compatible with React 16.6's Suspense component.
- [rest-hooks](https://github.com/coinbase/rest-hooks) - Data fetching for React by Coinbase.
- [react-hooks-fetch](https://github.com/dai-shi/react-hooks-fetch) - A React custom hook for data fetching with Suspense.

## Demos

- [Fetching data](https://codesandbox.io/s/frosty-hermann-bztrp) - Basic data fetching example.

## License

[CC0](https://github.com/michalczaplinski/awesome-concurrent-react)
