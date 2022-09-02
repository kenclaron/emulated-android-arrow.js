# Emulated-Android-Arrow.js
![npm](https://img.shields.io/npm/dt/emulated-android-arrow.js)
> Smooth vanilla JavaScript arrow slider like Android launcher's arrow for website.

[Website for preview](http://kenclaron.ru)

## Table of contents
- [Features](#features)
- [Getting started](#getting-started)
  - [Syntax](#syntax)
  - [Example](#example)
- [License](#license)
- [Browser support](#browser-support)
- [Author](#author)

## Features

- Cross-browser support
- Desktop and mobile platforms support
- Supports custom settings (check out the available [syntax](#syntax))

## Main

```text
dist/
├── emulated-android-arrow.js
└── emulated-android-arrow.min.js   (compressed)
```

## Getting Started

### Installation

```
npm install emulated-android-arrow.js
```

In browser:

```html
<script src="/path/to/emulated-android-arrow.js"></script>
```

### Usage

#### Syntax

```js
  new EmulatedAndroidArrow(parent, crossSupport, mobile, direction);
```

- **parent**
  - Type: `HTMLElement`
  - The HTMLElement as parent for arrow element.

- **crossSupport** (optional)
  - Type: `Boolean`
  - 180 degree rotation on mobile devices when true. (default: true)

- **mobile** (optional)
  - Type: `Boolean`
  - True: Only mobile devices | False: All devices (default: false)

- **direction** (optional)
  - Type: `Number`
  - Starting direction (0: none, 1: top, -1: bottom) (default: 0)

#### Example

```js
  new EmulatedAndroidArrow(document.body, true, false, 1);
```

## License

The Emulated-Android-Arrow.js licensed under the [MIT license](https://opensource.org/licenses/MIT).

## Browser support

- Chrome (49.0.2623 or latest)
- Firefox (45.0 or latest)
- Opera (36.0.2130.32 or latest)
- Edge (25.10586/EdgeHTML 13.10586 or latest)
- Safari (9.0 or latest)

## Author

> You can express your gratitude by clicking on one of the links

- [Personal website](https://kenclaron.github.io/kenclaron/)
- [VK](https://vk.com/club190729942)

___________________________________

[↑ back to top](#table-of-contents)
