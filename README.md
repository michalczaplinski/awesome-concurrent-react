<div align="center">
	<a href="react_concurrent_logo.png"><img src="react_concurrent_logo.png" alt="react-concurrent-logo"></a>
	<br>
	<br>
	<br>
</div>

# Awesome Concurrent React [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> List of resources about the React Concurrent Mode (previously called React Suspense). 

React Concurrent is the set of new, experimental React features that allow for:
- React rendering to run concurrently to other browser processes which allows for e.g. native `input` to "interrupt" rendering.
- "Suspend" the rendering until all of component's dependencies (data or code) are available and show a fallback until then.

## Contents
- [Documentation](#documentation)
- [Talks](#talks)
- [Data Fetching](#data-fetching)
- [Demos](#demos)
- [Blog posts / twitter threads](#blog-posts--twitter-threads)
- [Examples](#examples)

## Documentation

- [Official React Docs](https://reactjs.org/docs/concurrent-mode-intro.html)
- [concurrent-react-notes](https://github.com/sw-yx/concurrent-react-notes) - Unofficial notes by [@swyx](https://github.com/sw-yx). Useful for a historical perspective.

## Talks

- [Dan Abramov - Suspense! - ReactFest 2018](https://www.youtube.com/watch?v=6g3g0Q_XVb4&feature=youtu.be) - The talk that introduced the idea of Suspense and React Concurrent in 2018.
- [Yuzhi Zheng - Keynote - ReactConf 2019](https://www.youtube.com/watch?v=uXEEL9mrkAQ) - Discussing Selective Hydration, Suspense, Concurrent Mode, and more.
- [Joe Savona - Data Fetching With Suspense In Relay - ReactConf 2019](https://www.youtube.com/watch?v=Tl0S7QkxFE4) - Fetching data using Concurrent React at Facebook.
- [Ashley Watkins - Building The New Facebook With React and Relay - ReactConf 2019](https://www.youtube.com/watch?v=KT3XKDBZW7M) - Taking advantage of Relay and new Concurrent React features.


## Data Fetching Libraries

- [relay](https://relay.dev/docs/en/experimental/a-guided-tour-of-relay#loading-states-with-suspense) - Official bindings for facebook relay library.
- [swr](https://github.com/zeit/swr) - React Hooks library for remote data fetching.
- [react-async](https://github.com/async-library/react-async) - Flexible promise-based React data loader.
- [react-fetching-library](https://github.com/marcin-piela/react-fetching-library) - API client for react with Suspense support.
- [fetch-suspense](https://github.com/CharlesStover/fetch-suspense) - A React fetch hook compatible with React 16.6's Suspense component.
- [rest-hooks](https://github.com/coinbase/rest-hooks) - Data fetching for React by Coinbase.
- [react-hooks-fetch](https://github.com/dai-shi/react-hooks-fetch) - A React custom hook for data fetching with Suspense.

## Demos
- [Fetching data](https://codesandbox.io/s/frosty-hermann-bztrp) - Basic data fetching example (from react docs).
- [Relay Hooks Concurrent React Example](https://github.com/relayjs/relay-examples/blob/master/issue-tracker/README.md) - A (partial) clone of GitHub's issue feature using Concurrent Mode, Suspense, and Relay Hooks.
- [Suspense Demo for library authors](https://github.com/gaearon/suspense-experimental-github-demo) - Sample project built with Suspense to demonstrate render-as-you-fetch.

## Blog posts / twitter threads
- [Building Great User Experiences with Concurrent Mode and Suspense](https://reactjs.org/blog/2019/11/06/building-great-user-experiences-with-concurrent-mode-and-suspense.html) - From **official React blog**. Best practices for Suspense and Concurrent Mode learned while building the new facebook.com.
- [Is Concurrent Mode just a workaround for “virtual DOM diffing” overhead?](https://twitter.com/dan_abramov/status/1120971795425832961)
- [How to Enable React Concurrent Mode](https://kentcdodds.com/blog/how-to-enable-react-concurrent-mode) - Shows a simple DIY demo of concurrent React. by Kent C. Dodds.

## Podcasts
- [Andrew Clark (React team member) on Concurrent Mode](https://reactpodcast.com/70)
- [Joe Savona (React team member) on Relay and Data Fetching with Suspense](https://reactpodcast.com/71)

## License

[CC0](https://github.com/michalczaplinski/awesome-concurrent-react)
