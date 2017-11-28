# ServiceWorker Cookbook

[![Build Status](https://travis-ci.org/mozilla/serviceworker-cookbook.svg?branch=master)](https://travis-ci.org/mozilla/serviceworker-cookbook)
[![dependencies](https://david-dm.org/mozilla/serviceworker-cookbook.svg)](https://david-dm.org/mozilla/serviceworker-cookbook)
[![devdependencies](https://david-dm.org/mozilla/serviceworker-cookbook/dev-status.svg)](https://david-dm.org/mozilla/serviceworker-cookbook#info=devDependencies)

It's online. It's offline. It's a Service Worker!

Service workers are a new technology to aid developers in:

	- creating realistic, reliable offline experiences
	- vastly improving performance when online
	- logically and dynamically caching files for any purpose

The ServiceWorker API, which has recently made its way into Firefox Developer Edition, will change the way web and mobile app developers make their websites fast and functional!

## What is in this cookbook?

This cookbook contains dozens of practical, detailed, and working examples of service worker usage.  These examples are for developers from beginner to expert and illustrate a number of APIs:

- [navigator.serviceWorker](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)
- [fetch](https://developer.mozilla.org/en-US/docs/Web/API/GlobalFetch/fetch)
- [cache](https://developer.mozilla.org/en-US/docs/Web/API/Cache)
- [push](https://developer.mozilla.org/en-US/docs/Web/API/Simple_Push_API)
- [notifications](https://developer.mozilla.org/en-US/docs/Web/API/notification)
- [BackgroundSync](https://developer.mozilla.org/en-US/docs/Web/API/ServiceWorkerRegistration/sync)

## How to contribute

We are always happy to accept contributions!  You can follow the process below to start creating a new recipe:

1.  Clone this repository
2.  Execute `cd serviceworker-cookbook && npm install`
3.  Copy the `_recipe_template` directory, rename it, and add all recipe code and resources within that new directory
4.  export GCM_API_KEY='<Your key>'
5.  Execute `gulp watch` to start the server
6.  Navigate to http://localhost:3000 to develop and test your recipe

When it's all done, please submit a pull request to the [ServiceWorker Cookbook](https://github.com/mozilla/serviceworker-cookbook).

## Similar projects & prior art

- [Google Chrome Service Worker Samples](https://github.com/GoogleChrome/samples/tree/gh-pages/service-worker)
- [Is ServiceWorker Ready?](https://github.com/jakearchibald/isserviceworkerready/tree/gh-pages/demos)
- [Embrace The Network](https://github.com/phamann/embrace-the-network)
- [The Offline Cookbook](https://jakearchibald.com/2014/offline-cookbook/)

# Attributions

[MealKeeper Icon](https://www.iconfinder.com/icons/51445/cook_book_recipe_group_icon) by [Shlyapnikova](http://shlyapnikova.deviantart.com/), [Creative Commons (Attribution 3.0 Unported)](http://creativecommons.org/licenses/by/3.0/)

Attribution of pictures in Caching strategies category can be found at [lorempixel.com](http://lorempixel.com).
