<img src="http://rawgit.com/caiogondim/blooming-menu/master/logo/logo.svg">

# BloomingMenu 
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

AwesomeMenu made with CSS


## Preview

<img src="http://rawgit.com/caiogondim/blooming-menu/master/gif-preview/center.gif">
<img src="http://rawgit.com/caiogondim/blooming-menu/master/gif-preview/bottom-left.gif">


## API


### constructor

#### `opts.startAngle`

Type: `Number`

Default: `90`


#### `opts.endAngle`

Type: `Number`

Default: `0`


#### `opts.radius`

Type: `Number`

Default: `80`


#### `opts.itemAnimationDelay`

Type: `Number`

Default: `0.04`


#### `opts.animationDuration`

Type: `Number`

Default: `0.4`


#### `opts.fatherElement`

Type: `HTMLElement`

Default: `document.body`


#### `opts.itemWidth`

Type: `Number`

Default: 50


#### `opts.containerCSSClass`

Type: `String`

Default: `'blooming-menu__container'`


#### `opts.mainCSSClass`

Type: `String`

Default: `'blooming-menu__main'`


#### `opts.mainContent`

Type: `String`

Default: `'+'`


#### `opts.itensContainerCSSClass`

Type: `String`

Default: `'blooming-menu__itens'`


#### `opts.itensCSSClass`

Type: `String`

Default: `'blooming-menu__item'`


Every method below is an instance method.

### obj.`render`

Attachs the instance to the DOM and binds all event listeners.

### obj.`remove`

Removes all DOM elements and event listeners.

### obj.`open`

Opens the menu programmatically.

### obj.`close`

Closes the menu programmatically.

### obj.`selectItem(num)`

Select programatically the `num` item of the menu.


## Credits
- Project icon by Chamaquito Pan de Dulce
- Menu items by [Google Material Design](https://github.com/google/material-design-icons)
- [Base16](https://github.com/chriskempson/base16) Ocean color scheme
- This lib is a port in JavaScript of the Objective-C lib [AwesomeMenu](https://github.com/levey/AwesomeMenu)
