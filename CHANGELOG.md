# Changelog

## [2.0.0](https://github.com/palasthotel/wp-palasthotel-content-change-observer/compare/v1.2.4...v2.0.0) (2026-11-03)


### ⚠ BREAKING CHANGES

* the plugin folder is palasthotel-content-change-observer instead of content-observer. WordPress treats it as a new plugin: install it, deactivate and delete the old one, then activate the new one. Settings, connected sites and modifications stay, as options and tables keep their names.

### Features

* rename the plugin to Palasthotel Content Change Observer ([c40e088](https://github.com/palasthotel/wp-palasthotel-content-change-observer/commit/c40e088829f44a4d79a7e321a33440f3ea35f7fd))


### Bug Fixes

* show log notices only on the plugin's own admin pages ([5acb3b4](https://github.com/palasthotel/wp-palasthotel-content-change-observer/commit/5acb3b4ef5365fd787d383706c56377d97c9cbac))

## [1.2.4](https://github.com/palasthotel/wp-content-observer/compare/v1.2.3...v1.2.4) (2026-10-14)


### Bug Fixes

* connection test can no longer make the site request arbitrary URLs ([4f494f5](https://github.com/palasthotel/wp-content-observer/commit/4f494f53c26138146b17ca85bc5b741c64b49c69))
* escape admin notice logs and keep API keys out of them ([08b8c06](https://github.com/palasthotel/wp-content-observer/commit/08b8c06256f859d6933d9cda992cb68865d962c2))
* escape the API key field on the settings page ([8fc9ae1](https://github.com/palasthotel/wp-content-observer/commit/8fc9ae1300f16bd159036b7adb3ab53274505c12))
* modifications page disappears after applying modifications ([c3f6bb8](https://github.com/palasthotel/wp-content-observer/commit/c3f6bb81cd4911c1d91cdaed4f58e7c9bde158d3))
* protect Fetch, Notify and Apply against cross-site requests ([1ae6a34](https://github.com/palasthotel/wp-content-observer/commit/1ae6a34de2544fed18b52aeb7b70ee240b0bb558))
* reject requests to other sites' routes when no API key is set ([7775e3d](https://github.com/palasthotel/wp-content-observer/commit/7775e3d9c08d28c25307b29cc9dcaf5df11c2e05))

## 1.2.3

* Major library updates
* all js(x) files converted to typescript
* fix: use admin_url passed from php for ajax calls

## 1.2.1

* Feature: Admin notices logger

## 1.2.0

* New modifications page

## 1.1.0

* Library update
* all js api calls are cors independent

## 1.0.0

* First release
