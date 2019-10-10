<p align="center">
  <a href="https://invertase.io/oss/react-native-firebase">
    <img width="160px" src="./cover.png"><br/>
  </a>
  <h2 align="center">PTR - PDF Tatoo Remover</h2>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/react-native-firebase"><img src="https://img.shields.io/npm/dm/react-native-firebase.svg?style=flat-square" alt="NPM downloads"></a>
  <a href="https://www.npmjs.com/package/react-native-firebase"><img src="https://img.shields.io/npm/v/react-native-firebase.svg?style=flat-square" alt="NPM version"></a>
  <a href="/LICENSE"><img src="https://img.shields.io/npm/l/react-native-firebase.svg?style=flat-square" alt="License"></a>
  <a href="https://lerna.js.org/"><img src="https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg?style=flat-square" alt="Maintained with Lerna"></a>
</p>

---

> A simple and easy to use wrapper arround qpdf and sed to remove a string from a pdf (like a watermark for example).

---

## Installation
To use this lib, **QPDF** and **SED** need to be installed.

SED is installed by default on the  most popular linux distros.

To install **QPDF**
- On Linux:
```
sudo apt update
sudo apt install qpdf
```

- On MacOS
```
brew install qpdf
```

- Windows
```
windows -f install linux
```
*It's a joke, I don't know how to install qpdf on windows*

## Usage
```javascript 1.8
const tatooRemover = require("pdf-tatoo-remover");
```
