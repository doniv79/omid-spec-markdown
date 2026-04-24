# Changelog

All notable changes to the OMID API specification are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/).

## [1.5] - 2024-06-10

### Added
- CTV support in OM Web Video SDK for Smart TV web apps on WebOS and Tizen Web TV platforms.
- JavaScript-Managed Sessions: ability to start and finish iOS & Android OMID sessions via JavaScript APIs.
- Picture-in-Picture (PiP) detection and measurement signals (where available) in iOS & Android SDKs.

## [1.4] - 2023-09-30

### Added
- Identifying CTV Traffic: device category, environment, and operating system identification for native apps.
- Last Activity signal indicating someone is "still watching".
- Display Connection Status: detection of when the TV display is off but applications may still be running.

## [1.3] - 2022-06-22

### Added
- Better classification: new ad session types and creative types for robust creative measurement.
- Improved transparency: new Begin to Render impression definition with capability to use different impression types transparently.
- Brand safety support: capability to declare the content URL in which the ad is being shown.
- Audio ad support: new creative type for audio and new rules for audio measurement.
- Friendly obstruction support: capability to declare friendly obstructions and the reason for the obstruction.

### Changed
- Simplified integration: OM SDK activation method made easier to use.

## [1.2] - 2018-06-14

### Added
- OMID for Web Video/Audio support.
- `apiVersion` property on the top-level context object.
- `environment` property new value `"web"` for web case.
- `accessMode` property (`"limited"` vs `"full"`).
- `videoElement` and `slotElement` properties for non-sandbox mode.
- `measuringVideoElement` and `measuringSlotElement` properties.
- VAST 4.1 values: `adServingId`, `transactionId`, `podSequence`, `adCount`.
- `omidImplementer` property on `omidJsInfo` subobject.

### Changed
- General documentation rewritten, clarified, and usage examples added throughout.
- `supports` array: removed `"vlid"` value (video lifecycle interface is not optional).

## [1.1] - 2018-04-10

### Added
- Initial Release.
