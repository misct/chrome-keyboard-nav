# Patched keyboardnav.js

Improves performance of [Keyboard Navigation](https://chrome.google.com/webstore/detail/keyboard-navigation/abcekjakjehkpheoaadhkjfcdodpjbgk/reviews)
extension on pages with many links by using a [DocumentFragment](https://developers.google.com/speed/articles/javascript-dom).

Courtesy of [cldello/keyboardnav.js](https://gist.github.com/cldellow/7435859)
Packaged into this repo by [Wayne Bloss](http://github.com/waynebloss)

####### NOTE: The `release-0.1.5_0` directory is the original source of Keyboard Navigation 
that was copied from an installation of the extension on Chrome/Windows.

## Installation

1. Copy the contents of patched-keyboardnav.js and replace the contents of the keyboardnav.js
file that is installed with the Keyboard Navigation extension. On Windows, that file will
typically be located in `%LocalAppData%\Google\Chrome\User Data\Default\Extensions\abcekjakjehkpheoaadhkjfcdodpjbgk\0.1.5_0\`

2. Restart Chrome.