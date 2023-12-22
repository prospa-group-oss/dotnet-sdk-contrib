# Changelog

## [0.2.0](https://github.com/prospa-group-oss/dotnet-sdk-contrib/compare/OpenFeature.Contrib.Providers.Flagd-v0.1.7...OpenFeature.Contrib.Providers.Flagd-v0.2.0) (2023-12-22)


### ⚠ BREAKING CHANGES

* rename namespace, add OpenFeature dependency and readmes.
* rename namespace, add OpenFeature dep ([#18](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/18))

### 🐛 Bug Fixes

* NET462 requires TLS for GRPC to work ([#72](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/72)) ([2322f43](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/2322f4319b4b44b66c6965e736551538b4ced9a1))
* Setup config correct when passing a Uri (fixes [#71](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/71)) ([#83](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/83)) ([e27d351](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/e27d351f7e3392102e2c7f840a0ab30e13198613))
* update flagd provider docs, publishing ([#39](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/39)) ([7abdf5e](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/7abdf5e979fe03b41ecf83e05c41ceb626941510))


### ✨ New Features

* flagd provider basic functionality ([#31](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/31)) ([5ed9336](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/5ed9336132a12c058f46beef5c861233270e975e))
* implement the flagd provider ([5ed9336](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/5ed9336132a12c058f46beef5c861233270e975e))
* implemented LRU caching for flagd provider  ([#47](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/47)) ([f4d2142](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/f4d21426e9ec079d62ecca4e8d1936cb8ad299b7))
* introduce FlagdProvider constructor accepting FlagdConfig as parameter ([#57](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/57)) ([2e4fda3](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/2e4fda3abc6ffd3c43d5ea42dcddb855f5298322))
* rename namespace, add OpenFeature dep ([#18](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/18)) ([3ca3172](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/3ca31722b83053d4edf2038889c78efa717a7cff))
* rename namespace, add OpenFeature dependency and readmes. ([3ca3172](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/3ca31722b83053d4edf2038889c78efa717a7cff))
* support TLS connection in flagd provider ([#48](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/48)) ([49e775a](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/49e775a425b043e5774fbae348cfa2c4af59f2cf))
* unix socket support for flagd provider ([#42](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/42)) ([9679fe4](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/9679fe40cb13b48fa2f34521ce6175d9b8a6874b))


### 🧹 Chore

* **deps:** update dependency google.protobuf to v3.22.1 ([#51](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/51)) ([f6834ed](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/f6834eddf125b3e1096473eb2f376b3588b62430))
* **deps:** update dependency google.protobuf to v3.22.3 ([#60](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/60)) ([f07d99b](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/f07d99b2358d8893a15a1c10d5070953d1fa8f4d))
* **deps:** update dependency google.protobuf to v3.22.4 ([#61](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/61)) ([2ea28ed](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/2ea28ed56b14566f1acd1b13f5fe1211b714c807))
* **deps:** update dependency google.protobuf to v3.23.4 ([#63](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/63)) ([7a20e82](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/7a20e82446e29934d50d6673bba5a3ed15b8d830))
* **deps:** update dependency grpc.net.client to v2.52.0 ([#52](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/52)) ([fb2a570](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/fb2a570701338fc3702af3ca2352150183af4b21))
* **deps:** update dependency grpc.net.client to v2.55.0 ([#62](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/62)) ([8aac8a8](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/8aac8a86582bdfd91f7f34dcd765052c81393845))
* **deps:** update dependency grpc.net.client to v2.57.0 ([#78](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/78)) ([b749549](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/b74954944c87dd708a0256a44fd7df8db911a66c))
* **deps:** update dependency grpc.net.client to v2.58.0 ([#92](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/92)) ([350d5ef](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/350d5efdfde51e1557e4f37b82c6baaccb05b2c9))
* **deps:** update dependency grpc.net.client to v2.59.0 ([#115](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/115)) ([f33c5ff](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/f33c5ff8ea9040ed61d7b36a2d4cf621a3a5c813))
* **deps:** update dependency grpc.tools to v2.54.0 ([#53](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/53)) ([db2f893](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/db2f893a2660060cefb5e8b41006981a21a0313e))
* **deps:** update dependency grpc.tools to v2.56.2 ([#67](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/67)) ([7f8144b](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/7f8144b93f04eed47be16381f881ee651f2ccb9c))
* **deps:** update dependency grpc.tools to v2.57.0 ([#77](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/77)) ([9690abc](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/9690abc3e3540cee3ec2a6c0cd29e81c8d4d39be))
* **deps:** update dependency grpc.tools to v2.58.0 ([#82](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/82)) ([9b017ff](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/9b017ff3a92499901c677e5cf9347ab387f91aaa))
* **deps:** update dependency grpc.tools to v2.59.0 ([#88](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/88)) ([fa1dccc](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/fa1dccc647da33b77a1509afe791b4fa83fab3e8))
* **deps:** update dependency grpc.tools to v2.60.0 ([#111](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/111)) ([500cfe4](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/500cfe49a4d12e4af199f9050cd89abeb06bcfe5))
* **deps:** update dependency system.net.http.winhttphandler to v7 ([#54](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/54)) ([04bdae0](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/04bdae038cbe3f8f631a5e3606cc7d8f6fa9f242))
* **deps:** update dotnet monorepo to v8 (major) ([#100](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/100)) ([13d3223](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/13d32231983e61ec9960cabfbf9a55fc5a6b32cb))
* **main:** release OpenFeature.Contrib.Providers.Flagd 0.1.7 ([#87](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/87)) ([d8cac7f](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/d8cac7fa6f757f6d62c9648eb249d80528f2b337))
* release main ([#17](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/17)) ([c5be031](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/c5be03129a42fd688fedb0b74ac35d340095b149))
* release main ([#38](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/38)) ([d7ed1f4](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/d7ed1f4a636c19231861367f5a82e3d67a462c8a))
* release main ([#40](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/40)) ([5227157](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/5227157f64c32cc25171c6a5ff22a45f4e62143a))
* release main ([#43](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/43)) ([e170817](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/e170817544b5c3642153fe02a8fe36a45eec017d))
* release main ([#55](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/55)) ([19447b3](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/19447b387c612d7b1cc1de335c60702f49281eae))
* release main ([#58](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/58)) ([a38c529](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/a38c5291765282202e6c3abedfc7f0cac735db92))
* release main ([#74](https://github.com/prospa-group-oss/dotnet-sdk-contrib/issues/74)) ([7d7ba0f](https://github.com/prospa-group-oss/dotnet-sdk-contrib/commit/7d7ba0f5817a8e5be0471d3503fc78d03397b0a0))

## [0.1.7](https://github.com/open-feature/dotnet-sdk-contrib/compare/OpenFeature.Contrib.Providers.Flagd-v0.1.6...OpenFeature.Contrib.Providers.Flagd-v0.1.7) (2023-09-13)


### 🐛 Bug Fixes

* Setup config correct when passing a Uri (fixes [#71](https://github.com/open-feature/dotnet-sdk-contrib/issues/71)) ([#83](https://github.com/open-feature/dotnet-sdk-contrib/issues/83)) ([e27d351](https://github.com/open-feature/dotnet-sdk-contrib/commit/e27d351f7e3392102e2c7f840a0ab30e13198613))


### 🧹 Chore

* **deps:** update dependency grpc.net.client to v2.57.0 ([#78](https://github.com/open-feature/dotnet-sdk-contrib/issues/78)) ([b749549](https://github.com/open-feature/dotnet-sdk-contrib/commit/b74954944c87dd708a0256a44fd7df8db911a66c))
* **deps:** update dependency grpc.tools to v2.57.0 ([#77](https://github.com/open-feature/dotnet-sdk-contrib/issues/77)) ([9690abc](https://github.com/open-feature/dotnet-sdk-contrib/commit/9690abc3e3540cee3ec2a6c0cd29e81c8d4d39be))
* **deps:** update dependency grpc.tools to v2.58.0 ([#82](https://github.com/open-feature/dotnet-sdk-contrib/issues/82)) ([9b017ff](https://github.com/open-feature/dotnet-sdk-contrib/commit/9b017ff3a92499901c677e5cf9347ab387f91aaa))

## [0.1.6](https://github.com/open-feature/dotnet-sdk-contrib/compare/OpenFeature.Contrib.Providers.Flagd-v0.1.5...OpenFeature.Contrib.Providers.Flagd-v0.1.6) (2023-08-08)


### Bug Fixes

* NET462 requires TLS for GRPC to work ([#72](https://github.com/open-feature/dotnet-sdk-contrib/issues/72)) ([2322f43](https://github.com/open-feature/dotnet-sdk-contrib/commit/2322f4319b4b44b66c6965e736551538b4ced9a1))

## [0.1.5](https://github.com/open-feature/dotnet-sdk-contrib/compare/OpenFeature.Contrib.Providers.Flagd-v0.1.4...OpenFeature.Contrib.Providers.Flagd-v0.1.5) (2023-04-07)


### Features

* introduce FlagdProvider constructor accepting FlagdConfig as parameter ([#57](https://github.com/open-feature/dotnet-sdk-contrib/issues/57)) ([2e4fda3](https://github.com/open-feature/dotnet-sdk-contrib/commit/2e4fda3abc6ffd3c43d5ea42dcddb855f5298322))

## [0.1.4](https://github.com/open-feature/dotnet-sdk-contrib/compare/OpenFeature.Contrib.Providers.Flagd-v0.1.3...OpenFeature.Contrib.Providers.Flagd-v0.1.4) (2023-04-04)


### Features

* implemented LRU caching for flagd provider  ([#47](https://github.com/open-feature/dotnet-sdk-contrib/issues/47)) ([f4d2142](https://github.com/open-feature/dotnet-sdk-contrib/commit/f4d21426e9ec079d62ecca4e8d1936cb8ad299b7))
* support TLS connection in flagd provider ([#48](https://github.com/open-feature/dotnet-sdk-contrib/issues/48)) ([49e775a](https://github.com/open-feature/dotnet-sdk-contrib/commit/49e775a425b043e5774fbae348cfa2c4af59f2cf))

## [0.1.3](https://github.com/open-feature/dotnet-sdk-contrib/compare/OpenFeature.Contrib.Providers.Flagd-v0.1.2...OpenFeature.Contrib.Providers.Flagd-v0.1.3) (2023-03-22)


### Features

* unix socket support for flagd provider ([#42](https://github.com/open-feature/dotnet-sdk-contrib/issues/42)) ([9679fe4](https://github.com/open-feature/dotnet-sdk-contrib/commit/9679fe40cb13b48fa2f34521ce6175d9b8a6874b))

## [0.1.2](https://github.com/open-feature/dotnet-sdk-contrib/compare/OpenFeature.Contrib.Providers.Flagd-v0.1.1...OpenFeature.Contrib.Providers.Flagd-v0.1.2) (2023-02-13)


### Bug Fixes

* update flagd provider docs, publishing ([#39](https://github.com/open-feature/dotnet-sdk-contrib/issues/39)) ([7abdf5e](https://github.com/open-feature/dotnet-sdk-contrib/commit/7abdf5e979fe03b41ecf83e05c41ceb626941510))

## [0.1.1](https://github.com/open-feature/dotnet-sdk-contrib/compare/OpenFeature.Contrib.Providers.Flagd-v0.1.0...OpenFeature.Contrib.Providers.Flagd-v0.1.1) (2023-02-13)


### Features

* flagd provider basic functionality ([#31](https://github.com/open-feature/dotnet-sdk-contrib/issues/31)) ([5ed9336](https://github.com/open-feature/dotnet-sdk-contrib/commit/5ed9336132a12c058f46beef5c861233270e975e))
* implement the flagd provider ([5ed9336](https://github.com/open-feature/dotnet-sdk-contrib/commit/5ed9336132a12c058f46beef5c861233270e975e))

## [0.1.0](https://github.com/open-feature/dotnet-sdk-contrib/compare/OpenFeature.Contrib.Providers.Flagd-v0.0.2...OpenFeature.Contrib.Providers.Flagd-v0.1.0) (2022-10-16)


### ⚠ BREAKING CHANGES

* rename namespace, add OpenFeature dependency and readmes.
* rename namespace, add OpenFeature dep (#18)

### Features

* rename namespace, add OpenFeature dep ([#18](https://github.com/open-feature/dotnet-sdk-contrib/issues/18)) ([3ca3172](https://github.com/open-feature/dotnet-sdk-contrib/commit/3ca31722b83053d4edf2038889c78efa717a7cff))
* rename namespace, add OpenFeature dependency and readmes. ([3ca3172](https://github.com/open-feature/dotnet-sdk-contrib/commit/3ca31722b83053d4edf2038889c78efa717a7cff))
