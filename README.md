# Lena.js
_Library for image processing_

# Demo

[http://fellipe.com/demos/lena-js/](http://fellipe.com/demos/lena-js/)

[![Dependency Status](https://david-dm.org/davidsonfellipe/lena-js.png)](https://david-dm.org/davidsonfellipe/lena-js)

## Current filters

* gaussian
* grayscale
* highpass
* invert
* laplacian
* prewitt
* rgb
* roberts
* saturation
* sepia
* sharpen
* sobel
* thresholding
* lowpass 3x3
* lowpass 5x5

## Install via bower

`bower install lena.js`

## Developing new filters

Follow those steps to develop new filters.

| Steps | Description | Command |
| :----------- | :----------- | :-------------- |
| **01** | Install npm | `sudo npm install` |
| **02** | If you have installed Grunt globally in the past, you will need to remove it first | `npm uninstall -g grunt` |
| **03** | Install grunt-cli | `npm install -g grunt-cli` |
| **04** | Install grunt to current project | `npm install grunt --save-dev` |
| **05** | And finally run it with | `grunt watch` |


#### Author

[![Davidson Fellipe](http://gravatar.com/avatar/054c583ad5dc09a861874e14dcb43e4c?s=70)](https://github.com/davidsonfellipe)
<br>
[Davidson Fellipe](https://github.com/davidsonfellipe)

#### Contribute

Anyone and everyone is welcome to contribute. See some [developers](https://github.com/davidsonfellipe/lena.js/graphs/contributors) that helped.


## License

Code is under [MIT](http://davidsonfellipe.mit-license.org) license
