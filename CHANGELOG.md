# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project "attempts" to adhere to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [v0.1.5] - 2019-0528
- Fixed tip reloading as best as possible
- Still don't know how to prepare for when Tip50 runs out exactly at each level
- 2019-0528: 3X Stable Run Through Success

## [v0.1.4] - 2019-04-12

## Added
- Notes file for informal changes
- New submethod CheckTipSeq to check if the tips are about to run out 

## Changed
- How loop counters work (no more ChannelPattern library)
- Grip Height from 4 to 10. I don't know why this parameter would have changed.
- Disabled AntiDroplet control for the recovering the final supernantant. It was giving firmware errors that were not recoverable.
- Tube for the bead-isopropanol mix is now programmed for a 50 mL falcon.
- Removed AntiDroplet control for all steps not involving solvents
- 2019-0207: Improved Tip Reloading Submethod, hard-coded 50uL NTR rack number though

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
