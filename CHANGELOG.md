# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.4] - 2020-05-06
### Modified
- Decrease required PHP version to 7.2

## [1.0.3] - 2020-04-30
### Added
- Add a `loadEventCallback` parameter on `umanitImageLazyLoad` used in the `load` event of yall.js

## [1.0.2] - 2020-04-29
### Added
- Add a CSS file to make a blur effect on lazy load images
- Add a new configuration `umanit_twig_image.lazy_load.blur_class_selector` to specify the class name used to make the
blur effect

## [1.0.1] - 2020-04-27
### Added
- Add a `figureClass` parameter on `umanit_image_figure_lazy_load` and `umanit_image_figure`

### Fixed
- Add `['is_safe' => ['html']]` on functions
- Use `data-srcset` on lazy load functions

### BC Break
- Rename `class` parameter to `imgClass` on all functions

## 1.0.0 - 2020-04-14
First release 🎉

[Unreleased]: https://github.com/umanit/twig-image-extension/compare/1.0.4...master
[1.0.4]: https://github.com/umanit/twig-image-extension/compare/1.0.3...1.0.4
[1.0.3]: https://github.com/umanit/twig-image-extension/compare/1.0.2...1.0.3
[1.0.2]: https://github.com/umanit/twig-image-extension/compare/1.0.1...1.0.2
[1.0.1]: https://github.com/umanit/twig-image-extension/compare/1.0.0...1.0.1
