## [1.3.4](https://github.com/wppconnect-team/wppconnect/compare/v1.3.3...v1.3.4) (2021-04-30)

### Bug Fixes

- Fixed deletion of tmp chrome user data dir on exit ([ce767b5](https://github.com/wppconnect-team/wppconnect/commit/ce767b54caae473db14e6be05c95133c4fb73c00))

## [1.3.3](https://github.com/wppconnect-team/wppconnect/compare/v1.3.2...v1.3.3) (2021-04-28)

## [1.3.2](https://github.com/wppconnect-team/wppconnect/compare/v1.3.1...v1.3.2) (2021-04-28)

### Bug Fixes

- Fixed message ID generator ([0da9a62](https://github.com/wppconnect-team/wppconnect/commit/0da9a62490073642aa00dc4f7052465de271f7f3))
- Fixed sendContact with custom name ([#152](https://github.com/wppconnect-team/wppconnect/issues/152)) ([47a51f0](https://github.com/wppconnect-team/wppconnect/commit/47a51f060814ab79704b160227c350092e2abe3f))

### Features

- Allow to define contact name in sendContactVcardList ([#152](https://github.com/wppconnect-team/wppconnect/issues/152)) ([474e5a0](https://github.com/wppconnect-team/wppconnect/commit/474e5a061496cd96ca4864b0d033813bc47c573a))

## [1.3.1](https://github.com/wppconnect-team/wppconnect/compare/v1.3.0...v1.3.1) (2021-04-20)

### Features

- Added function to enable and disable temporary messages ([5a9a289](https://github.com/wppconnect-team/wppconnect/commit/5a9a2891785e6b34e3bcb6a6cee3502101e36d7f))
- Added options to edit group description, subject and properties ([07d155f](https://github.com/wppconnect-team/wppconnect/commit/07d155fb5ca891223881100b28931c4fbbf37740))

# [1.3.0](https://github.com/wppconnect-team/wppconnect/compare/v1.2.6...v1.3.0) (2021-04-16)

### Bug Fixes

- corrects update instructions ([#124](https://github.com/wppconnect-team/wppconnect/issues/124)) ([8cbfb9b](https://github.com/wppconnect-team/wppconnect/commit/8cbfb9b2c48879d5c6709a40eb7e53188a1347f2))

### Features

- Created tokenStore interface for session data management ([a3a76c3](https://github.com/wppconnect-team/wppconnect/commit/a3a76c3e2e01581ff2ae4e40199eab5957bac0a3))

## [1.2.6](https://github.com/wppconnect-team/wppconnect/compare/v1.2.5...v1.2.6) (2021-04-12)

### Bug Fixes

- Fixed sendFile from URL ([ff63fed](https://github.com/wppconnect-team/wppconnect/commit/ff63fedd51793896169cc09097e13d99290ec031))

## [1.2.5](https://github.com/wppconnect-team/wppconnect/compare/v1.2.4...v1.2.5) (2021-04-07)

### Bug Fixes

- Fixed event dispose to stop listeners ([#103](https://github.com/wppconnect-team/wppconnect/issues/103)) ([0682c06](https://github.com/wppconnect-team/wppconnect/commit/0682c06122dc534789cea5721a515e4bdd96e4de))

### Features

- Added phoneWatchdog verification ([6616fa2](https://github.com/wppconnect-team/wppconnect/commit/6616fa22567fe0ea1f35fff32ec1f8b070e76695))

## [1.2.4](https://github.com/wppconnect-team/wppconnect/compare/v1.2.3...v1.2.4) (2021-03-30)

### Bug Fixes

- Fixed inject token for authentication ([c36466f](https://github.com/wppconnect-team/wppconnect/commit/c36466faddda75dcbfcc7f1e18d275917e41e707))

## [1.2.3](https://github.com/wppconnect-team/wppconnect/compare/v1.2.2...v1.2.3) (2021-03-29)

### Bug Fixes

- Fixed downloadMedia with new WhatsApp version (fix [#76](https://github.com/wppconnect-team/wppconnect/issues/76)) ([f61e118](https://github.com/wppconnect-team/wppconnect/commit/f61e1183937e8dd2989d892b6a8e7b8e117cd22e))

## [1.2.2](https://github.com/wppconnect-team/wppconnect/compare/v1.2.1...v1.2.2) (2021-03-29)

### Bug Fixes

- Fixed logged token delete on disconnect ([883d0d4](https://github.com/wppconnect-team/wppconnect/commit/883d0d415a6dd7d05625adcefaa0d3d397fc11ed))
- Fixed statusFind callback (#fix 57) ([cc0d3d6](https://github.com/wppconnect-team/wppconnect/commit/cc0d3d69855ae219699ea65a53e63379f72e3aa6))

## [1.2.1](https://github.com/wppconnect-team/wppconnect/compare/v1.2.0...v1.2.1) (2021-03-04)

### Bug Fixes

- Fixed send to status@broadcast ([a0c8d20](https://github.com/wppconnect-team/wppconnect/commit/a0c8d2053d15851dbde34b3a4f3ce03481f8ea09))

# [1.2.0](https://github.com/wppconnect-team/wppconnect/compare/v1.1.0...v1.2.0) (2021-03-02)

### Bug Fixes

- Increased timeout WhatsApp page load ([c1f8f03](https://github.com/wppconnect-team/wppconnect/commit/c1f8f03476038bceb9f62fd6648124b774794551))

### Features

- Improved module loader ([#27](https://github.com/wppconnect-team/wppconnect/issues/27)) ([0f44d20](https://github.com/wppconnect-team/wppconnect/commit/0f44d2030b34c0101b3f34d995d824f240aa5548))

# [1.1.0](https://github.com/wppconnect-team/wppconnect/compare/v1.0.3...v1.1.0) (2021-02-27)

### Bug Fixes

- Fixed decryptFile function ([c92597b](https://github.com/wppconnect-team/wppconnect/commit/c92597bb7bda03ee5b4905881894e13e0003e24b))

### Features

- Allow pass browser/page in create method ([#19](https://github.com/wppconnect-team/wppconnect/issues/19)) ([a2902e8](https://github.com/wppconnect-team/wppconnect/commit/a2902e8840046407b56da59ba5d2c1e5c16b5c0b))

## [1.0.3](https://github.com/wppconnect-team/wppconnect/compare/v1.0.2...v1.0.3) (2021-02-26)

### Bug Fixes

- Fixed "sender" field in message return ([ca5f6ef](https://github.com/wppconnect-team/wppconnect/commit/ca5f6efea3bfcb6b58acd949d2d9035d1088de4f))

### chore

- Deprecated create with argument option position based ([020e71c](https://github.com/wppconnect-team/wppconnect/commit/020e71c7e95eb20a0a623b6e7c218f52c32a172b))

### BREAKING CHANGES

- Deprecated create from argument in favor of CreateOptions

## [1.0.2](https://github.com/wppconnect-team/wppconnect/compare/v1.0.1...v1.0.2) (2021-02-25)

### Bug Fixes

- WhatsApp Web v2.2106.5 compatibility ([fa9d575](https://github.com/wppconnect-team/wppconnect/commit/fa9d575bff21d2a97dda59378e49740b15460a63))

## [1.0.1](https://github.com/wppconnect-team/wppconnect/compare/v1.0.0...v1.0.1) (2021-02-24)

### Bug Fixes

- Fixed sendPtt from audio with codecs ([2a8b476](https://github.com/wppconnect-team/wppconnect/commit/2a8b476de07366267bb1e683ac632f2e6b815a75))

### Features

- Added sendPtt from file ([ae38c8e](https://github.com/wppconnect-team/wppconnect/commit/ae38c8e38c6c8b731b0ceda008c9224b497f42fd))

# [1.0.0](https://github.com/wppconnect-team/wppconnect/compare/v0.0.2...v1.0.0) (2021-02-24)
