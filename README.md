
# JD Menu

<br>

> A lightweight, simple to use sliding menu.

<br>

## Installation

<br>

#### NPM

```
npm install jd-menu --save
```

<br>

#### Yarn

```
yarn add jd-menu
```

<br>

#### Bower
```
bower install jd-menu --save
```

<br>

## Usage 

```
$(".some-menu).jdMenu({'duration': 500, 'theme': 'custom});
```

> Require (NPM / Yarn)

```javascript
require('jd-menu');
```

> Import (NPM / Yarn)

```javascript
import jdMenu from 'jd-menu';
```

> Require (Bower)

```javascript
require('SomePath/bower_components/jd-menu');
```

> SASS (NPM / Yarn)

```css
@import 'SomePath/node_modules/jd-menu/dist/css/master.css';
```
> SASS (Bower)

```css
@import 'SomePath/bower_components/jd-menu/dist/css/master.css';
```

<br>

## Options

> All of the differnet options with there default values.

```javascript
{    
  arrows: true,
  animation: 'slide',
  duration: 300,
  customArrow:'<i class="fa fa-chevron-right"></i>',
  customBack: `<li class="js-back"><span><i class="fa fa-chevron-left"></i> Back</span></li>`,
  theme: 'default'    
}
```
 
<br>

#### Arrows

```javascript
{
  arrows: true, // Default
  arrows: flase
}
```

<br>

#### Duration

```javascript
{
  duration: 300, // Default
  arrows: 500 // Example
}
```

<br>

#### Arrows Content

```javascript
{
  customArrow: '<i class="fa fa-chevron-right"></i>', // Default (Font Awesome)
  customArrow: '<i class="material-icons">keyboard_arrow_right</i>' // Example (Material Icons)
}
```

<br>

#### Back Button Content

> You need to keep the js-back class :)

```javascript
{
  customBack: '<li class="js-back"><span><i class="fa fa-chevron-left"></i> Back</span></li>', // Default
  customBack: <li class="js-back"><i class="material-icons">keyboard_arrow_left</i></li> // Example
}
```

<br>

#### Theme

> More base themes coming soon !

```javascript
{
  theme: 'default', // Default
  theme: 'custom' // Example
}
```

<br>

## Dependencies

<br>

#### Font Awesome (For Arrows)

<br>

#### jQuery