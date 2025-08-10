# CS50 Filters Project

## Problem Overview
Implement a program that applies filters (blur, grayscale, reflect, sepia) to BMP images.

You can apply only one filter at a time using command line flags:
- `-b` for blur
- `-g` for grayscale
- `-r` for reflect
- `-s` for sepia

## Heres the Demo on how i run these commands and how the program hadles errors
  [![asciicast](https://asciinema.org/a/m0KmInXYlkF8DvbJDTYLPARrr.svg)](https://asciinema.org/a/m0KmInXYlkF8DvbJDTYLPARrr)

## Examples

| Filter     | Input Image                                   | Output Image                                  |
|------------|----------------------------------------------|----------------------------------------------|
| Grayscale  | ![grayscale input](img/courtyard.bmp) | ![grayscale output](img/images-grayscale.bmp) |
| Sepia      | ![sepia input](img/stadium.bmp)          | ![sepia output](img/stadium-sepia.bmp)         |
| Blur       | ![blur input](img/yard.bmp)             | ![blur output](img/yard-blurred.bmp)            |
| Reflect    | ![reflect input](img/tower.bmp)       | ![reflect output](img/tower-reflected.bmp)      |
