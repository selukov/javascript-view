# Javascript View

Firefox extension to view javascript file. It automatically deminify,
beautify and syntax-highlight the javascript file.

# Credits:
1. [Rainbow](http://craig.is/making/rainbows) syntax highlighter.
2. [beautify.js](https://github.com/einars/js-beautify/blob/master/beautify.js) for deminify and beautify javascript.
3. [Prism](http://prismjs.com) is a lightweight, extensible syntax highlighter, built with modern web standards in mind.

# Changelog

## version 1.2.0
- swap rainbow.js with prism.js

## version 1.1.3
- fix bug that causing cpu utilization to reach 100%

## version 1.1.2
- add overflow-x scroll to prevent long line gets wrapped and messes up the line number

## version 1.1.1
- fix bug when viewing html page which ends in .js in its url (https://github.com/rahmat-budiharso/javascript-view/issues/1)

## version 1.1.0
- add line number

## Version 1.0.1
- use textContent rather than innerHTML
- fix bug when '&&' is escaped into '& &amp;'

## Version 1.0
- Initial commit
