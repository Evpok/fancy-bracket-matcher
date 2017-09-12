Change Log
==========
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to
[Semantic Versioning](http://semver.org/).

## [2.1.0] - 2017-09-12
[2.1.0]: https://github.com/Evpok/fancy-bracket-matcher/compare/v2.0.0...v2.1.0
### Changed
  - Highlight colour is now set to `@syntax-color-modified` which by default is the original orange. We thus come back to our former look while still allowing syntax themes to override it to a more suitable colour.
  - Brought back a more exploding effect to the animation. 

## [2.0.0] - 2017-09-11
[2.0.0]: https://github.com/Evpok/fancy-bracket-matcher/compare/v1.0.2...v2.0.0
### Changed
  - The highlight colour now depends on the syntax theme. (Yes, an option to change it is underway, 🐻 with me)
  -
## [1.0.2] - 2017-08-18
[1.0.2]: https://github.com/Evpok/fancy-bracket-matcher/compare/v1.0.1...v1.0.2
### Fixed
  - Fix [issue #5](https://github.com/Evpok/fancy-bracket-matcher/issues/3)

## [1.0.1] - 2017-01-11
[1.0.1]: https://github.com/Evpok/fancy-bracket-matcher/compare/v1.0.0...v1.0.1
### Fixed
  - Fix [issue #3](https://github.com/Evpok/fancy-bracket-matcher/issues/3) by removing shadow selectors, thanks to [Michael van Olden](https://github.com/emveeoh). This probably break compatibility with [Atom < 1.13](http://blog.atom.io/2016/11/14/removing-shadow-dom-boundary-from-text-editor-elements.html).


## [1.0.0] - 2017-01-11
[1.0.0]: https://github.com/Evpok/fancy-bracket-matcher/releases/tag/v1.0.0
First stable release
