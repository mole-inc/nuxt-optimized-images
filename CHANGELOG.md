# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [2.1.0](https://github.com/mole-inc/nuxt-optimized-images/compare/v2.0.0...v2.1.0) (2020-05-01)


### Features

* add jpegoptim plugin ([55d2b1b](https://github.com/mole-inc/nuxt-optimized-images/commit/55d2b1b0e1325e041e2447d549fc7da0a624dc6a))


### Bug Fixes

* fix detected loaders counts ([73a9c6f](https://github.com/mole-inc/nuxt-optimized-images/commit/73a9c6f7ff8733a1d1c648de98644209e1eb6f25))
* fix log message ([caa431c](https://github.com/mole-inc/nuxt-optimized-images/commit/caa431c7de13f40c4d980872e4e92b882a5148a7))

## [2.0.0](https://github.com/mole-inc/nuxt-optimized-images/compare/v1.0.0...v2.0.0) (2020-04-29)


### ⚠ BREAKING CHANGES

* rename package and changes

### Features

* rename package and changes ([c3c9074](https://github.com/mole-inc/nuxt-optimized-images/commit/c3c90741df255a80578c6997c64a2b46495a820c))

# [1.0.0](https://github.com/aceforth/nuxt-optimized-images/compare/v0.4.0...v1.0.0) (2020-04-12)


* refactor!: update parent company ([ad10855](https://github.com/aceforth/nuxt-optimized-images/commit/ad108557cb6880a9a28760750feb8ec51a80ccd5))


### BREAKING CHANGES

* **The package has been renamed from `@bazzite/nuxt-optimized-images` to `@aceforth/nuxt-optimized-images`.**



To upgrade

1. `npm install --save-dev @aceforth/nuxt-optimized-images` 

   or `yarn add --dev @aceforth/nuxt-optimized-images`

2. `npm uninstall @bazzite/nuxt-optimized-images` 

   or `yarn remove @bazzite/nuxt-optimized-images`

3. replace:

```js
{
  buildModules: [
    '@bazzite/nuxt-optimized-images',
  ],
}
```

with

```js
{
  buildModules: [
    '@aceforth/nuxt-optimized-images',
  ],
}
```


That’s it, there are no functional changes compared to `@bazzite/nuxt-optimized-images@0.4.0`.



# [0.4.0](https://github.com/aceforth/nuxt-optimized-images/compare/v0.3.0...v0.4.0) (2020-03-31)


### Bug Fixes

* **docs:** fix links in the Usage page and fix typos ([#159](https://github.com/aceforth/nuxt-optimized-images/issues/159)) ([c33702e](https://github.com/aceforth/nuxt-optimized-images/commit/c33702eed4b6cf53627089317a31043fca3d23aa))
* **docs:** fix typo ([#146](https://github.com/aceforth/nuxt-optimized-images/issues/146)) ([ff1489c](https://github.com/aceforth/nuxt-optimized-images/commit/ff1489cc3f18614624e845a7c81c0ff4bc7e0c5d))
* **docs:** update Installation instructions ([ef86870](https://github.com/aceforth/nuxt-optimized-images/commit/ef8687063565d58df362309867ee82ea30be9b33))
* **tests:** fix tests ([9bdf817](https://github.com/aceforth/nuxt-optimized-images/commit/9bdf8175406ac03cb08c570e5a9f82d0efe28b91))


* refactor!: drop support for Node.js 8 ([b747b41](https://github.com/aceforth/nuxt-optimized-images/commit/b747b41d2374b201097883b79a1d3eb074115087))


### BREAKING CHANGES

* minimum required Node.js version is 10.x



# [0.3.0](https://github.com/aceforth/nuxt-optimized-images/compare/v0.2.2...v0.3.0) (2019-12-19)


### Performance Improvements

* use `contenthash` for images name on production ([7ab94c0](https://github.com/aceforth/nuxt-optimized-images/commit/7ab94c06c1d0a092a9c93bcfc4481728017029c3))



## [0.2.2](https://github.com/aceforth/nuxt-optimized-images/compare/v0.2.1...v0.2.2) (2019-11-27)


### Bug Fixes

* **example:** print the nuxt debug messages when static generating the project ([4a3d69b](https://github.com/aceforth/nuxt-optimized-images/commit/4a3d69b34a4e4f24d3b979d24ca774730d75b3a3))
* fix the warning message when it's only used the LQIP loader ([27b920b](https://github.com/aceforth/nuxt-optimized-images/commit/27b920b44feac40560325326a7ea110ec3f627cd))
* **docs:** fix camel case in responsive-loader example ([#51](https://github.com/aceforth/nuxt-optimized-images/issues/51)) ([210ec85](https://github.com/aceforth/nuxt-optimized-images/commit/210ec85e248cfddc6834bf5c178b834d30201947))
* **docs:** fix typo on docs ([#99](https://github.com/aceforth/nuxt-optimized-images/issues/99)) ([5efce80](https://github.com/aceforth/nuxt-optimized-images/commit/5efce8082e93fc3ec34d429b0a6dea65cde9c244))


### Minor Changes

* **tests:** include the static generation of the example project in Travis CI ([d518ce9](https://github.com/aceforth/nuxt-optimized-images/commit/d518ce94a8317d73627cca3f571b4a8ee04e8c29))



## [0.2.1](https://github.com/aceforth/nuxt-optimized-images/compare/v0.2.0...v0.2.1) (2019-05-24)


### Bug Fixes

* **docs:** fix description of the page `/es/docs/contributing` ([1b65df6](https://github.com/aceforth/nuxt-optimized-images/commit/1b65df6))
* ignore the iteration of the webpack rules without a test attribute ([a73dc56](https://github.com/aceforth/nuxt-optimized-images/commit/a73dc56))



## [0.2.0](https://github.com/aceforth/nuxt-optimized-images/compare/v0.1.0...v0.2.0) (2019-05-17)


### Bug Fixes

* **package:** update raw-loader to version 2.0.0 ([e93b584](https://github.com/aceforth/nuxt-optimized-images/commit/e93b584))
* fix included svgs files with raw-loader@2.x ([4468716](https://github.com/aceforth/nuxt-optimized-images/commit/4468716))


### Features

* support `sqip-loader` ([098649](https://github.com/aceforth/nuxt-optimized-images/commit/098649))


## 0.1.0 (2019-03-14)

* first stable version
