# SVGPath [![MIT License][license-image]][license-url] [![Build Status][travis-image]][travis-url]

A Swift Library for parsing SVG path strings into UIBezierPaths

```swift
let svgPath = "M85.384 32.884C115.46 68.38 239.47 170.94 281.4 " +
	"192.53 311.84 126.2 274.938 43.767 244.68 0c97.903 58.96 146.498 " +
	"167.557 121.765 254.406 28.978 28.984 40.134 89.26 29.742 108.594 " +
	"-25.357-45.46-67.378-39.82-93.413-24.977C176.784 409.845 24.18 " +
	"296.47 0 233.15c68.297 56.465 170.137 65.246 226.388 27.535C165.59 " +
	"217.78 56.806 89.835 36.638 54.818c42.772 38.274 116.565 96.602 " +
	"161.76 122.154C159.906 137.854 108.122 72.34 85.384 32.884z"

let path = UIBezierPath(svgPath: svgPath)
```

[license-image]: http://img.shields.io/badge/license-MIT-blue.svg?style=flat
[license-url]: LICENSE

[travis-url]: http://travis-ci.org/timrwood/SVGPath
[travis-image]: http://img.shields.io/travis/timrwood/SVGPath/develop.svg?style=flat
