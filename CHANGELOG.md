# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [5.8.0](https://github.com/nuxt-community/axios-module/compare/v5.7.1...v5.8.0) (2019-10-23)


### Features

* add `CancelToken` and `isCancel` to axios instance ([#292](https://github.com/nuxt-community/axios-module/issues/292)) ([b9335b1](https://github.com/nuxt-community/axios-module/commit/b9335b1c55b3af34e2d6e5897fedb8372a620ce4))

### [5.7.1](https://github.com/nuxt-community/axios-module/compare/v5.7.0...v5.7.1) (2019-10-22)


### Bug Fixes

* use `Axios` for  `isCancel` (fixes [#301](https://github.com/nuxt-community/axios-module/issues/301)) ([82dfccc](https://github.com/nuxt-community/axios-module/commit/82dfccce409e918a91e498af1340408dc0892bf5))

## [5.7.0](https://github.com/nuxt-community/axios-module/compare/v5.6.0...v5.7.0) (2019-10-22)


### Features

* add function helper `setBaseURL` ([#296](https://github.com/nuxt-community/axios-module/issues/296)) ([1028bbc](https://github.com/nuxt-community/axios-module/commit/1028bbcaf2d1a29a33949f05aeb9d519c30b246e))
* allow adding custom headers with nuxt config ([#294](https://github.com/nuxt-community/axios-module/issues/294)) ([3e38906](https://github.com/nuxt-community/axios-module/commit/3e3890616a5ac3eb34b07ec476313bb648aca59a))


### Bug Fixes

* **headers:** don't proxy `content-md5` and `content-type` ([#300](https://github.com/nuxt-community/axios-module/issues/300)) ([f959c58](https://github.com/nuxt-community/axios-module/commit/f959c585254029ac8d623d1472b883022ab115e2))
* **progress:** handle canceled requests ([#301](https://github.com/nuxt-community/axios-module/issues/301)) ([5096060](https://github.com/nuxt-community/axios-module/commit/50960609d913d059758658aa88434bd28faa0c47))

## [5.6.0](https://github.com/nuxt-community/axios-module/compare/v5.5.4...v5.6.0) (2019-08-20)


### Features

* **types:** provide nuxt 2.9 compatible types ([#277](https://github.com/nuxt-community/axios-module/issues/277)) ([7aee77b](https://github.com/nuxt-community/axios-module/commit/7aee77b))
* https detection ([#260](https://github.com/nuxt-community/axios-module/issues/260)) ([953ab8c](https://github.com/nuxt-community/axios-module/commit/953ab8c))



### [5.5.4](https://github.com/nuxt-community/axios-module/compare/v5.5.3...v5.5.4) (2019-06-05)


### Bug Fixes

* ignore content-length header ([41ff27a](https://github.com/nuxt-community/axios-module/commit/41ff27a))



### [5.5.3](https://github.com/nuxt-community/axios-module/compare/v5.5.2...v5.5.3) (2019-05-30)


### Bug Fixes

* bump axios to ^0.19.0 ([ee8f999](https://github.com/nuxt-community/axios-module/commit/ee8f999))



## [5.5.2](https://github.com/nuxt-community/axios-module/compare/v5.5.1...v5.5.2) (2019-05-26)


### Bug Fixes

* vuex typescript type ([#253](https://github.com/nuxt-community/axios-module/issues/253)) ([9205fdf](https://github.com/nuxt-community/axios-module/commit/9205fdf))



## [5.5.1](https://github.com/nuxt-community/axios-module/compare/v5.5.0...v5.5.1) (2019-05-23)


### Bug Fixes

* don't toLowerCase headers for `setHeader` and `setToken` ([#250](https://github.com/nuxt-community/axios-module/issues/250)) ([93469f0](https://github.com/nuxt-community/axios-module/commit/93469f0))



# [5.5.0](https://github.com/nuxt-community/axios-module/compare/v5.4.2...v5.5.0) (2019-05-22)


### Bug Fixes

* lowercase `accept-encoding` header (nuxt/http[#43](https://github.com/nuxt-community/axios-module/issues/43)) ([c17fec2](https://github.com/nuxt-community/axios-module/commit/c17fec2))


### Features

* convert header names to lowercase (nuxt/http[#45](https://github.com/nuxt-community/axios-module/issues/45)) ([2e514a4](https://github.com/nuxt-community/axios-module/commit/2e514a4))
* use `server` of nuxt.config.js to set default baseURL ([#245](https://github.com/nuxt-community/axios-module/issues/245)) ([e1120a9](https://github.com/nuxt-community/axios-module/commit/e1120a9))



## [5.4.1](https://github.com/nuxt-community/axios-module/compare/v5.4.0...v5.4.1) (2019-03-05)


### Bug Fixes

* **types:** correct Vuex Store instance ([#227](https://github.com/nuxt-community/axios-module/issues/227)) ([1ed6e2f](https://github.com/nuxt-community/axios-module/commit/1ed6e2f))



# [5.4.0](https://github.com/nuxt-community/axios-module/compare/v5.3.6...v5.4.0) (2019-03-02)


### Bug Fixes

* **types:** `onResponseError` typo ([#203](https://github.com/nuxt-community/axios-module/issues/203)) ([5fc1441](https://github.com/nuxt-community/axios-module/commit/5fc1441))
* **types:** add AxiosError interface ([efb7191](https://github.com/nuxt-community/axios-module/commit/efb7191))
* **types:** move types in types folder ([deb2834](https://github.com/nuxt-community/axios-module/commit/deb2834))


### Features

* **types:** add Context interface ([7f8952a](https://github.com/nuxt-community/axios-module/commit/7f8952a))
* **types:** add types for helper functions ([#193](https://github.com/nuxt-community/axios-module/issues/193)) ([79909cc](https://github.com/nuxt-community/axios-module/commit/79909cc))



<a name="5.3.6"></a>
## [5.3.6](https://github.com/nuxt-community/axios-module/compare/v5.3.5...v5.3.6) (2018-11-08)


### Bug Fixes

* correctly ignore brotli encoding on server-side ([#180](https://github.com/nuxt-community/axios-module/issues/180)) ([4a52bfd](https://github.com/nuxt-community/axios-module/commit/4a52bfd))



<a name="5.3.5"></a>
## [5.3.5](https://github.com/nuxt-community/axios-module/compare/v5.3.4...v5.3.5) (2018-11-07)


### Bug Fixes

* **defaults:** ignore `cf-ray` and `cf-connecting-ip` headers on server side ([#20](https://github.com/nuxt-community/axios-module/issues/20)) ([#175](https://github.com/nuxt-community/axios-module/issues/175)) ([3ae5416](https://github.com/nuxt-community/axios-module/commit/3ae5416))
* **defaults:** set proper Accept-Encoding for server side ([#176](https://github.com/nuxt-community/axios-module/issues/176)) ([c84fb56](https://github.com/nuxt-community/axios-module/commit/c84fb56))



<a name="5.3.4"></a>
## [5.3.4](https://github.com/nuxt-community/axios-module/compare/v5.3.3...v5.3.4) (2018-10-30)



<a name="5.3.3"></a>
## [5.3.3](https://github.com/nuxt-community/axios-module/compare/v5.3.2...v5.3.3) (2018-09-28)


### Bug Fixes

* **package:** add missing types from index.d.ts ([3a06503](https://github.com/nuxt-community/axios-module/commit/3a06503))



<a name="5.3.2"></a>
## [5.3.2](https://github.com/nuxt-community/axios-module/compare/v5.3.1...v5.3.2) (2018-09-21)


### Bug Fixes

* **types:** replace AxiosPromise to Promise ([#162](https://github.com/nuxt-community/axios-module/issues/162)) ([5fd9214](https://github.com/nuxt-community/axios-module/commit/5fd9214))



<a name="5.3.1"></a>
## [5.3.1](https://github.com/nuxt-community/axios-module/compare/v5.3.0...v5.3.1) (2018-03-31)



<a name="5.3.0"></a>
# [5.3.0](https://github.com/nuxt-community/axios-module/compare/v5.2.0...v5.3.0) (2018-03-31)


### Features

* CLI improvements ([481e6da](https://github.com/nuxt-community/axios-module/commit/481e6da))



<a name="5.2.0"></a>
# [5.2.0](https://github.com/nuxt-community/axios-module/compare/v5.1.1...v5.2.0) (2018-03-31)


### Bug Fixes

* **progress:** onProgress when currentRequests is zero ([#118](https://github.com/nuxt-community/axios-module/issues/118)) ([a90236e](https://github.com/nuxt-community/axios-module/commit/a90236e))


### Features

* consola integration ([4ec3b5d](https://github.com/nuxt-community/axios-module/commit/4ec3b5d))



<a name="5.1.1"></a>
## [5.1.1](https://github.com/nuxt-community/axios-module/compare/v5.1.0...v5.1.1) (2018-03-06)


### Bug Fixes

* **progress:** handle division by zero ([#117](https://github.com/nuxt-community/axios-module/issues/117)) ([040eaf7](https://github.com/nuxt-community/axios-module/commit/040eaf7)), closes [#166](https://github.com/nuxt-community/axios-module/issues/166)



<a name="5.1.0"></a>
# [5.1.0](https://github.com/nuxt-community/axios-module/compare/v5.0.1...v5.1.0) (2018-03-05)


### Features

* allow disable progress per request. closes [#112](https://github.com/nuxt-community/axios-module/issues/112). ([1530bb6](https://github.com/nuxt-community/axios-module/commit/1530bb6))
* disable https for localhost url ([#93](https://github.com/nuxt-community/axios-module/issues/93)) ([dd67734](https://github.com/nuxt-community/axios-module/commit/dd67734))



<a name="5.0.1"></a>
## [5.0.1](https://github.com/nuxt-community/axios-module/compare/v5.0.0...v5.0.1) (2018-02-08)


### Bug Fixes

* don't mutate env.API_URL ([a8ea331](https://github.com/nuxt-community/axios-module/commit/a8ea331))



<a name="5.0.0"></a>
# [5.0.0](https://github.com/nuxt-community/axios-module/compare/v5.0.0-rc.2...v5.0.0) (2018-02-04)


### Bug Fixes

* **progress:** finish on fail ([ea7b569](https://github.com/nuxt-community/axios-module/commit/ea7b569))


### Features

* https option ([#57](https://github.com/nuxt-community/axios-module/issues/57)) ([9ecb547](https://github.com/nuxt-community/axios-module/commit/9ecb547))
* passing options via proxy option ([a923db3](https://github.com/nuxt-community/axios-module/commit/a923db3))
* support retry with axios-retry ([7221cac](https://github.com/nuxt-community/axios-module/commit/7221cac)), closes [#77](https://github.com/nuxt-community/axios-module/issues/77)



<a name="5.0.0-rc.2"></a>
# [5.0.0-rc.2](https://github.com/nuxt-community/axios-module/compare/v5.0.0-rc.1...v5.0.0-rc.2) (2018-01-29)


### Bug Fixes

* **package:** require [@nuxtjs](https://github.com/nuxtjs)/proxy as a peerDependency ([fd1ef47](https://github.com/nuxt-community/axios-module/commit/fd1ef47))
* support dynamic API_URL for SSR ([ea4882a](https://github.com/nuxt-community/axios-module/commit/ea4882a))



<a name="5.0.0-rc.1"></a>
# [5.0.0-rc.1](https://github.com/nuxt-community/axios-module/compare/v5.0.0-rc.0...v5.0.0-rc.1) (2018-01-28)


### Bug Fixes

* **progress:** ensure $loading is valid ([cbdc586](https://github.com/nuxt-community/axios-module/commit/cbdc586))



<a name="5.0.0-rc.0"></a>
# [5.0.0-rc.0](https://github.com/nuxt-community/axios-module/compare/v5.0.0-alpha.1...v5.0.0-rc.0) (2018-01-28)


### Features

* support proxy ([0d3be17](https://github.com/nuxt-community/axios-module/commit/0d3be17))



<a name="5.0.0-alpha.1"></a>
# [5.0.0-alpha.1](https://github.com/nuxt-community/axios-module/compare/v5.0.0-alpha.0...v5.0.0-alpha.1) (2018-01-28)


### Features

* integrate with nuxt progress bar ([41a0964](https://github.com/nuxt-community/axios-module/commit/41a0964))



<a name="5.0.0-alpha.0"></a>
# [5.0.0-alpha.0](https://github.com/nuxt-community/axios-module/compare/v4.5.2...v5.0.0-alpha.0) (2018-01-28)


### Code Refactoring

* a better and more stable way to specify baseURL and browserBaseURL options ([533cf4e](https://github.com/nuxt-community/axios-module/commit/533cf4e))


### Features

* interceptor helpers ([fa3eb47](https://github.com/nuxt-community/axios-module/commit/fa3eb47))
* rewrite plugin ([647b58f](https://github.com/nuxt-community/axios-module/commit/647b58f))


### BREAKING CHANGES

* prefix should be set to `/api` for backward compability. refer to new docs.



<a name="4.5.2"></a>
## [4.5.2](https://github.com/nuxt-community/axios-module/compare/v4.5.1...v4.5.2) (2017-12-29)



<a name="4.5.1"></a>
## [4.5.1](https://github.com/nuxt-community/axios-module/compare/v4.5.0...v4.5.1) (2017-12-29)



<a name="4.5.0"></a>
# [4.5.0](https://github.com/nuxt-community/axios-module/compare/v4.4.0...v4.5.0) (2017-11-16)


### Bug Fixes

* link to the proxy page ([5449939](https://github.com/nuxt-community/axios-module/commit/5449939))


### Features

* disable sefault error handler ([#44](https://github.com/nuxt-community/axios-module/issues/44)) ([f1e95ff](https://github.com/nuxt-community/axios-module/commit/f1e95ff))



<a name="4.4.0"></a>
# [4.4.0](https://github.com/nuxt-community/axios-module/compare/v4.3.1...v4.4.0) (2017-09-30)


### Features

* **proxyHeader:** proxyHeadersIgnore option ([7c13655](https://github.com/nuxt-community/axios-module/commit/7c13655))



<a name="4.3.1"></a>
## [4.3.1](https://github.com/nuxt-community/axios-module/compare/v4.3.0...v4.3.1) (2017-09-28)



<a name="4.3.0"></a>
# [4.3.0](https://github.com/nuxt-community/axios-module/compare/v4.2.1...v4.3.0) (2017-09-11)


### Features

* don't rely on hostname for default values ([dadd7d8](https://github.com/nuxt-community/axios-module/commit/dadd7d8))



<a name="4.2.1"></a>
## [4.2.1](https://github.com/nuxt-community/axios-module/compare/v4.2.0...v4.2.1) (2017-09-08)



<a name="4.2.0"></a>
# [4.2.0](https://github.com/nuxt-community/axios-module/compare/v4.1.1...v4.2.0) (2017-09-08)


### Features

* pass ctx to errorHandlers ([c70749a](https://github.com/nuxt-community/axios-module/commit/c70749a))



<a name="4.1.1"></a>
## [4.1.1](https://github.com/nuxt-community/axios-module/compare/v4.1.0...v4.1.1) (2017-09-06)


### Bug Fixes

* delete accept header ([2f04e30](https://github.com/nuxt-community/axios-module/commit/2f04e30)), closes [#12](https://github.com/nuxt-community/axios-module/issues/12)



<a name="4.1.0"></a>
# [4.1.0](https://github.com/nuxt-community/axios-module/compare/v4.0.1...v4.1.0) (2017-09-06)


### Bug Fixes

* inject $axios in current ctx ([356b31f](https://github.com/nuxt-community/axios-module/commit/356b31f))


### Features

* add options.init ([8e0c0e8](https://github.com/nuxt-community/axios-module/commit/8e0c0e8))


### Performance Improvements

* move init outside of plugin ([bcd4710](https://github.com/nuxt-community/axios-module/commit/bcd4710))



<a name="4.0.1"></a>
## [4.0.1](https://github.com/nuxt-community/axios-module/compare/v4.0.0...v4.0.1) (2017-09-04)


### Bug Fixes

* **package:** make nuxt devDependency ([a36a886](https://github.com/nuxt-community/axios-module/commit/a36a886))



<a name="4.0.0"></a>
# [4.0.0](https://github.com/nuxt-community/axios-module/compare/v3.1.4...v4.0.0) (2017-08-30)


### Features

* better baseURL message ([61432a1](https://github.com/nuxt-community/axios-module/commit/61432a1))
* responseInterceptor and errorHandler ([b16d6bf](https://github.com/nuxt-community/axios-module/commit/b16d6bf))
* upgrade for nuxt rc8 ([a341185](https://github.com/nuxt-community/axios-module/commit/a341185))


### BREAKING CHANGES

* app.axios is not available anymore (without $) should always use app.$axios



<a name="3.1.4"></a>
## [3.1.4](https://github.com/nuxt-community/axios-module/compare/v3.1.3...v3.1.4) (2017-08-13)


### Bug Fixes

* create fresh objects for all default header scopes ([7ba3ae8](https://github.com/nuxt-community/axios-module/commit/7ba3ae8))



<a name="3.1.3"></a>
## [3.1.3](https://github.com/nuxt-community/axios-module/compare/v3.1.1...v3.1.3) (2017-08-13)

### Bug Fixes

* **headers:** fix security bug with default request headers ([9355228](https://github.com/nuxt-community/axios-module/commit/9355228))



<a name="3.1.1"></a>
## 3.1.1 (2017-08-13)
 (repository moved from nuxt-community/modules)

### Features

* **axios:** fetch style requests

<a name="3.0.1"></a>
## [3.0.1](https://github.com/nuxt/modules/compare/@nuxtjs/axios@3.0.0...@nuxtjs/axios@3.0.1) (2017-07-25)


### Bug Fixes

* **axios:** typo in default headers ([9697559](https://github.com/nuxt/modules/commit/9697559))




<a name="3.0.0"></a>
# [3.0.0](https://github.com/nuxt/modules/compare/@nuxtjs/axios@2.3.0...@nuxtjs/axios@3.0.0) (2017-07-25)


### Code Refactoring

* **axios:** remove $ shortcut mixins ([1ab2bd6](https://github.com/nuxt/modules/commit/1ab2bd6))


### BREAKING CHANGES

* **axios:** You have to explicitly use `this.$axios.[method]` instead of `this.$[method]`




<a name="2.3.0"></a>
# [2.3.0](https://github.com/nuxt/modules/compare/@nuxtjs/axios@2.2.4...@nuxtjs/axios@2.3.0) (2017-07-24)


### Features

* **axios:** optionally disable error handling (#74) ([a195feb](https://github.com/nuxt/modules/commit/a195feb))
* **axios:** redirectError ([4ce1a1c](https://github.com/nuxt/modules/commit/4ce1a1c))




<a name="2.2.4"></a>
## [2.2.4](https://github.com/nuxt/modules/compare/@nuxtjs/axios@2.2.3...@nuxtjs/axios@2.2.4) (2017-07-20)


### Bug Fixes

* **axios:** temporary fix for nuxt/nuxt.js#1127 ([499b639](https://github.com/nuxt/modules/commit/499b639)), closes [nuxt/nuxt.js#1127](https://github.com/nuxt/nuxt.js/issues/1127)




<a name="2.2.3"></a>
## [2.2.3](https://github.com/nuxt/modules/compare/@nuxtjs/axios@2.2.1...@nuxtjs/axios@2.2.3) (2017-07-19)


### Bug Fixes

* **axios:** don't proxy Host header from request (#72, #39) ([61462ca](https://github.com/nuxt/modules/commit/61462ca))




<a name="2.2.2"></a>
## [2.2.2](https://github.com/nuxt/modules/compare/@nuxtjs/axios@2.2.1...@nuxtjs/axios@2.2.2) (2017-07-19)


### Bug Fixes

* **axios:** don't proxy Host header from request (#72, #39) ([61462ca](https://github.com/nuxt/modules/commit/61462ca))




<a name="2.2.1"></a>
## [2.2.1](https://github.com/nuxt/modules/compare/@nuxtjs/axios@2.2.0...@nuxtjs/axios@2.2.1) (2017-07-15)


### Bug Fixes

* **axios:** problems related to #65 ([4e7dd3f](https://github.com/nuxt/modules/commit/4e7dd3f))




<a name="2.0.3"></a>
## [2.0.3](https://github.com/nuxt/modules/compare/@nuxtjs/axios@2.0.2...@nuxtjs/axios@2.0.3) (2017-06-10)


### Bug Fixes

* **axios:** Handle relative baseURL ([19b8453](https://github.com/nuxt/modules/commit/19b8453))
* handle 0.0.0.0 host ([610e0f5](https://github.com/nuxt/modules/commit/610e0f5))




<a name="2.0.2"></a>
## [2.0.2](https://github.com/nuxt/modules/compare/@nuxtjs/axios@2.0.1...@nuxtjs/axios@2.0.2) (2017-06-09)


### Bug Fixes

* **axios:** Node 6.x support ([54deac0](https://github.com/nuxt/modules/commit/54deac0))




<a name="2.0.1"></a>
## [2.0.1](https://github.com/nuxt/modules/compare/@nuxtjs/axios@2.0.0...@nuxtjs/axios@2.0.1) (2017-06-09)


### Bug Fixes

* **axios:** ensure store exists before injecting ([23ad7b7](https://github.com/nuxt/modules/commit/23ad7b7))




<a name="2.0.0"></a>
# [2.0.0](https://github.com/nuxt/modules/compare/@nuxtjs/axios@1.0.2...@nuxtjs/axios@2.0.0) (2017-06-09)


### Bug Fixes

* **axios:** install using Vue.use ([184651b](https://github.com/nuxt/modules/commit/184651b))
* **axios:** req typo ([16f28b1](https://github.com/nuxt/modules/commit/16f28b1))
* **axios:** use relative `API_URL` if same host and port else `API_URL` ([3421d19](https://github.com/nuxt/modules/commit/3421d19))


### Features

* **axios:** AXIOS_CREDENTIALS, AXIOS_SSR_HEADERS ([4dfdc2d](https://github.com/nuxt/modules/commit/4dfdc2d))
* **axios:** don't append optional config into env ([fe189e8](https://github.com/nuxt/modules/commit/fe189e8))
* **axios:** Easier API ([f54a434](https://github.com/nuxt/modules/commit/f54a434))
* **axios:** New API ([0194226](https://github.com/nuxt/modules/commit/0194226))
* **axios:** nuxt friendly errors for SSR ([65bc50f](https://github.com/nuxt/modules/commit/65bc50f))


### BREAKING CHANGES

* **axios:** API_PREFIX is deprecated.




<a name="1.0.2"></a>
## [1.0.2](https://github.com/nuxt/modules/compare/@nuxtjs/axios@1.0.0...@nuxtjs/axios@1.0.2) (2017-05-29)


### Bug Fixes

* **axios:** remove extra function call on computed prop ([cd9da0b](https://github.com/nuxt/modules/commit/cd9da0b))




<a name="1.0.1"></a>
## [1.0.1](https://github.com/nuxt/modules/compare/@nuxtjs/axios@1.0.0...@nuxtjs/axios@1.0.1) (2017-05-26)


### Bug Fixes

* **axios:** remove extra function call on computed prop ([cd9da0b](https://github.com/nuxt/modules/commit/cd9da0b))




<a name="1.0.0"></a>
# 1.0.0 (2017-05-26)


### Features

* initial migration to 1.0.0-alpha1 ([05c1b7a](https://github.com/nuxt/modules/commit/05c1b7a))


### BREAKING CHANGES

* New modules system is backward incompatible with nuxt-helpers style modules




<a name="0.0.1"></a>
## 0.0.1 (2017-05-10)
