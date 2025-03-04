# Changelog

## Version 0.2.4

### What's Changed

- Fix date format [#31](https://github.com/Barma-lej/landroid-card/issues/31)

### New Contributors

- @cm86 made their first contribution in https://github.com/Barma-lej/landroid-card/pull/19

**Full Changelog**: https://github.com/Barma-lej/landroid-card/compare/0.2.3...0.2.4

## Version 0.2.3

### What's Changed

- Add translation [#18](https://github.com/Barma-lej/landroid-card/issues/18)
- Fix animation [#30](https://github.com/Barma-lej/landroid-card/issues/18)
- Update README.md by @cm86 in https://github.com/Barma-lej/landroid-card/pull/19
- Bump actions/checkout from 2 to 3 by @dependabot in https://github.com/Barma-lej/landroid-card/pull/20
- Bump CupOfTea696/gh-action-auto-release from 1.0.0 to 1.0.2 by @dependabot in https://github.com/Barma-lej/landroid-card/pull/21
- Bump @babel/plugin-transform-runtime from 7.18.6 to 7.18.9 by @dependabot in https://github.com/Barma-lej/landroid-card/pull/22
- Bump core-js from 3.23.3 to 3.24.1 by @dependabot in https://github.com/Barma-lej/landroid-card/pull/23
- Bump @lit-labs/scoped-registry-mixin from 1.0.0 to 1.0.1 by @dependabot in https://github.com/Barma-lej/landroid-card/pull/24
- Bump eslint from 8.19.0 to 8.21.0 by @dependabot in https://github.com/Barma-lej/landroid-card/pull/25
- Bump lit from 2.2.7 to 2.2.8 by @dependabot in https://github.com/Barma-lej/landroid-card/pull/26
- Bump @babel/preset-env from 7.18.6 to 7.18.9 by @dependabot in https://github.com/Barma-lej/landroid-card/pull/27
- Bump @babel/core from 7.18.6 to 7.18.9 by @dependabot in https://github.com/Barma-lej/landroid-card/pull/28
- Bump rollup from 2.75.7 to 2.77.2 by @dependabot in https://github.com/Barma-lej/landroid-card/pull/29

### New Contributors

- @cm86 made their first contribution in https://github.com/Barma-lej/landroid-card/pull/19

**Full Changelog**: https://github.com/Barma-lej/landroid-card/compare/0.2.2...0.2.3

## Version 0.2.2

### What's Changed

- Add **daily progress bar**
- Add **next scheduled start** to status
- Add `ultrasonic`, `daily_progress`, `next_scheduled_start` attributes to translates
- Clean translations from vacuum entries
- Update README.md by @Danit2 in https://github.com/Barma-lej/landroid-card/pull/15
- Update da.json by @projectraam in https://github.com/Barma-lej/landroid-card/pull/17
- Fix callService with additionaly parameters

### New Contributors

- @Danit2 made their first contribution in https://github.com/Barma-lej/landroid-card/pull/15

**Full Changelog**: https://github.com/Barma-lej/landroid-card/compare/0.2.1...0.2.2

## Version 0.2.1

### What's Changed

- Add swedish translations by @Miicroo in https://github.com/Barma-lej/landroid-card/pull/13
- Bump terser to 5.14.1 -> 5.14.2

### New Contributors

- @Miicroo made their first contribution in https://github.com/Barma-lej/landroid-card/pull/13

**Full Changelog**: https://github.com/Barma-lej/landroid-card/compare/0.2.0...0.2.1

### Known Issues

- Changing zone doesn't work

## Version 0.2.0

### Added

- Added callService to zone change to debugging
- Added polish translation by @SongoQ in https://github.com/Barma-lej/landroid-card/pull/12

### Fixed

- Fixed wrong DateTime Format in attributes [#10](https://github.com/Barma-lej/landroid-card/issues/10)

### New Contributors

- @SongoQ made their first contribution in https://github.com/Barma-lej/landroid-card/pull/12

### Known Issues

- Changing zone doesn't work

**Full Changelog**: https://github.com/Barma-lej/landroid-card/compare/0.1.9...0.2.0

## Version 0.1.9

### Added

- Added info menu under WiFi Icon

### Fixed

- Fixed Start action command button
- Fixed Edgecut action command button

### Known Issues

- Changing zone don't work

## Version 0.1.8

### Added

- Added ability to disable and enable animation
- Added ability to disable and enable configuration panel
- [Translate] Added slovenian translation by @mitchoklemen

### What's Changed

- Update and rename en.json to sl.json by @mitchoklemen in <https://github.com/Barma-lej/landroid-card/pull/11>
- Change zone number to Human Readable Format [MTrab/landroid_cloud/issue#232](https://github.com/MTrab/landroid_cloud/issues/232)

### New Contributors

- @mitchoklemen made their first contribution in <https://github.com/Barma-lej/landroid-card/pull/11>

**Full Changelog**: <https://github.com/Barma-lej/landroid-card/compare/0.1.7...0.1.8>

## Version 0.1.7

### Fixes

- Added default locales to try to fix [#10](https://github.com/Barma-lej/landroid-card/issues/10)

## Version 0.1.6

### Fixes

- Try to fix [#10](https://github.com/Barma-lej/landroid-card/issues/10)

## Version 0.1.5

### Added

- Added stats (Click on graph icon)
- Added **Current zone** to status
- Added **Rain delay remaining** to status
- Added **Eror description** to status
- Added compatibility with Landroid Cloud < 2.1 [#7](https://github.com/Barma-lej/landroid-card/issues/7)
- Added new element configBar
- [Translate] Added danish translation by @projectraam
- [Translate] Added italian translation by [Sofa_Surfer](https://community.home-assistant.io/t/worx-landroid-package/119345/325)
- [Translate] Added translations of errors
- [Translate] Added yes and no for boolean values
- [README.MD] Added **Worx** Landroid L1000 WR147E to supported mode by @elvis7
- [README.MD] Added link to **Home Assistant templating**

### Changes

- Change option `map` to `camera`
- [Translate] Fr. Moved action to action section

### Fixes

- Fix #7 Battery not showing if Landroid Cloud integration < 2.1

### Known Issues

- Changing zone don't work

## Version 0.1.4

- Fix WiFi Quality (if rssi > -49)
- Added French translate by @Skyber1967
- Translate: Move actions to action group

## Version 0.1.3

- Fix #3 regeneratorRuntime is not defined

## Version 0.1.2

### What's Changed

- Adapt to Landroid Cloud > 2.0.3
- Added battery status (Click on battery icon)
- Bump actions/checkout from 2 to 3 by @dependabot in #1
- Bump rollup-plugin-serve from 1.1.0 to 2.0.0 by @dependabot in #2

### New Contributors

@dependabot made their first contribution in #1

Full Changelog: <https://github.com/Barma-lej/landroid-card/commits/0.1.2>

## Version 0.1.1

- Added Party Mode
- Added Lock
- Changed `paper elements` to `mwc elements` in editor

## Version 0.1.0

- Fork from [Vacuum Card](https://github.com/denysdovhan/vacuum-card/)
- Adjustement `vacuum` to `landroid mower`
