# html2canvas-angular

This a angular service wrapper for [niklasvh](https://github.com/niklasvh)/[html2canvas](https://github.com/niklasvh/html2canvas).
There are two files
 * __sample.html__ - has a bare-bones angular body to test out the service
 * __html2canvas-angular.js__ - contains a minified version of html2canvas and a basic service wrapper.
## Method Reference

__RenderBody__ 
_returns:_ promise
Captures the current body and resolves the promise with a canvas element of the page.

