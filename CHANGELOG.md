# Changelog

## [1.6.3](https://github.com/camptocamp/docker-odyssey/compare/v1.6.2...v1.6.3) (2024-07-03)


### Bug Fixes

* set id on release trigger ([b6ce1e9](https://github.com/camptocamp/docker-odyssey/commit/b6ce1e97cb4ba80b2a05495519c6404a3f958852))

## [1.6.2](https://github.com/camptocamp/docker-odyssey/compare/v1.6.1...v1.6.2) (2024-07-03)


### Bug Fixes

* trigger build on every github action run ([a5461f4](https://github.com/camptocamp/docker-odyssey/commit/a5461f449def73d1eaf4daecc15bf76b4306dcaf))

## [1.6.1](https://github.com/camptocamp/docker-odyssey/compare/v1.6.0...v1.6.1) (2024-07-03)


### Bug Fixes

* add output release manager for image tag ([564d564](https://github.com/camptocamp/docker-odyssey/commit/564d5640e96b7c61e1b0e63f6e3fa8b9040c8c0b))

## [1.6.0](https://github.com/camptocamp/docker-odyssey/compare/v1.5.2...v1.6.0) (2024-07-03)


### Features

* update pipeline automerge ([2602e96](https://github.com/camptocamp/docker-odyssey/commit/2602e96993d80ec7c7ec7d2274fa75f68bdee720))

## [1.5.2](https://github.com/camptocamp/docker-odyssey/compare/v1.5.1...v1.5.2) (2024-07-03)


### Bug Fixes

* trigger build on all tags ([329b1c6](https://github.com/camptocamp/docker-odyssey/commit/329b1c6ed84c45c7e4bd37b8ae987d98da9c1a3c))


### Miscellaneous Chores

* release 1.5.2 ([44a1d23](https://github.com/camptocamp/docker-odyssey/commit/44a1d230a52daefba4a2a879784e30a1064fbd81))

## [1.5.1](https://github.com/camptocamp/docker-odyssey/compare/v1.5.0...v1.5.1) (2024-07-03)


### Features

* add cert end date ([027e109](https://github.com/camptocamp/docker-odyssey/commit/027e109bc647f499966dbbb8737bbf174ed2ea5e))
* add prometheus logs ([e6f1b2c](https://github.com/camptocamp/docker-odyssey/commit/e6f1b2c7aa1aac7cd7fae9dd56e19f968cad2e81))
* add prometheus logs ([e8d1c06](https://github.com/camptocamp/docker-odyssey/commit/e8d1c06057213b776ffca2cd8a5acb515f3646b2))
* build image from tag ([feeae98](https://github.com/camptocamp/docker-odyssey/commit/feeae98a5dc410a5cc5997b39431a8b1e93ed484))
* fix postgresl root certificate ([97196aa](https://github.com/camptocamp/docker-odyssey/commit/97196aa514e7d14da2c39403075783be1833fe0b))
* Initial commit ([227d13f](https://github.com/camptocamp/docker-odyssey/commit/227d13fd91bd9c5a4aa94e394f74518bc35d566c))
* odyssey image 1.2 ([fad7422](https://github.com/camptocamp/docker-odyssey/commit/fad7422f2d11559031412b625c3962cf60deda9e))
* reanable build ([7acd3ba](https://github.com/camptocamp/docker-odyssey/commit/7acd3ba542530acd4aed7b5c378d6393bef29345))
* Release 1.4.0 ([c413a09](https://github.com/camptocamp/docker-odyssey/commit/c413a09fef0202d75c5ed0cea1d4d46014c0ba73))
* Release 1.5.0 ([b23d3cb](https://github.com/camptocamp/docker-odyssey/commit/b23d3cb105ecc5ab8d189fcfaa32414bfb5848f8))
* run add odyssey + deploy tag ([928cc34](https://github.com/camptocamp/docker-odyssey/commit/928cc3446c8e638b597d1766b78331d889a39031))


### Bug Fixes

* enable ca-certificate ([a93fd0f](https://github.com/camptocamp/docker-odyssey/commit/a93fd0f88772851da4ac64a812189e31956b3e87))


### Miscellaneous Chores

* release 1.5.1 ([193651b](https://github.com/camptocamp/docker-odyssey/commit/193651b11c492139c1f4003fb405ab90f82e9243))
1.5.0 (08-08-2023)
+++++++++++++++++++

* fix: Add Certificate end date storing, for external tests
* feat: switch from debian bulleye -> debian bookworm
* fix: remove deb file in /tmp
* feat: include sample odyssey config file 

1.4.0 (23-03-2023)
+++++++++++++++++++

* feat: add prometheus logs

1.3.0 (30-01-2023)
+++++++++++++++++++

* Deploy: Odyssey 1.3 + User odyssey
* New github workflow
