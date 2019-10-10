<a href="https://github.com/lk-geimfari/rmanns/">
    <p align="center">
      <img src="./cover.png">
    </p>
</a>


<p align="center"> **PTR** **P**DF **T**atoo **R**emover </p>
<p> A simple and easy to use wrapper arround qpdf and sed to remove a string from a pdf (like a watermark for example) </p>

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
