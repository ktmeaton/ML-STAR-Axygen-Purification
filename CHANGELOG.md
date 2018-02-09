# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project "attempts" to adhere to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## To-Do
- Fix loop-counter steps
- Ehtanol removal step is a tad drippy
- Remember: EB mixing is a separate step because of liquid-following mode

## [v0.1.4] - 2018-0126

## Added
- Notes file for informal changes

## [v0.1.3] - 2017-10-16

## Added
- Proper sequence control for pipetting loops
- Many liquid editor fixes for ADC

### Changed
- Changed Z coordinates for labware: touch off, reach bottomm, pull back to set height
- 50 uL tips bend, not the best option
- "Not executed error" handling (is the correct option)
- Avoid "From Labware defition"
- Insufficient liquid error, "use available" is a better choice
- Mixing: submerge depth is additional on top of earlier set value
- LLD detection settings
- Submerge depth
- TADM tolerance bands volume specific
- TADM curves: steep decline = bottom out (too close to bottom)

## [v0.1.2] - 2017-09-21
### Added
- Functional method!

## [v0.1.1] - 2017-09-21
### Added
- README.md
- CHANGELOG.md
- Full method, draft

https://github.com/ktmeaton/ML-STAR-Axygen-Purification.git

[Unreleased]: https://github.com/ktmeaton/ML-STAR-Axygen-Purification/compare/v0.1.3...HEAD
[v0.1.3]: https://github.com/ktmeaton/ML-STAR-Axygen-Purification/compare/v0.1.2...v0.1.3
[v0.1.2]: https://github.com/ktmeaton/ML-STAR-Axygen-Purification/compare/v0.1.1...v0.1.2
[v0.1.1]: https://github.com/ktmeaton/ML-STAR-Axygen-Purification/compare/v0.1.1...v0.1.1
