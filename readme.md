
### Dummy.js – Crash test your front-end builds with:
#### Repeatable Elements, Dummy Text and Placeholder Images

![dummy.js](https://user-images.githubusercontent.com/1904774/31058166-1dade7b4-a6a4-11e7-8005-7c143fd3a60e.png)

Dummy.js is a simple drop-in script that makes it easy to fill your HTML with dummy text and images for development.


_Latest documentation and examples can be found at:_
### https://dummyjs.com/


## Usage

Add the script tag to your HTML page:

```HTML
<script src="https://dummyjs.com/js"></script>
```

or, for short:
```HTML
<script src="//dummyjs.com/js"></script>
```

## Dummy Text

```HTML
<p data-dummy></p>
```

Choose the amount of words:
```HTML
<p data-dummy="150"></p>
```

Render dummy markup for `ol` `ul` `table`:
```HTML
<table data-dummy></table>
```

Choose a random amount of words between 3 and 10:
```HTML
<p data-dummy="3,10"></p>
```

## Dummy Images


```HTML
<img data-dummy="400x300" />
```

Defaults to the size of the parent container
```HTML
<img data-dummy />
```

Custom Text
```HTML
<img data-dummy="400x300" data-text="person" />
```

Custom Colors
```HTML
<img data-dummy="400x300" data-color="#0000ff" data-text-color="#fff" />
```

## Repeat Elements

```HTML
<div data-repeat="3">Team Member</div>
```

Repeat a random amount of times between 3 and 10:
```HTML
<p data-repeat="3,10"></p>
```

## Kitchen Sink

Output all the common tags including headings, paragraphs, etc. Great for base styling.

```HTML
<div data-dummy="sink"></div>
```

## Copy Elements

Duplicate elements into other areas of your webpage. Pass a CSS selector like `.myelement` or `.post h3`

```HTML
<div data-copy=".pagination"></div>
```

## More Docs and Examples are available at:

**https://dummyjs.com/**

- Bootstrap examples https://dummyjs.com/docs/bootstrap.html
- Shh.. New features https://dummyjs.com/docs/undocumented.html

### Usage with jQuery and other Frameworks
Vanilla Javascript:
```JS
Dummy.text(2, 6)
Dummy.src(300, 400)
```

jQuery:
```JS
jQuery('p').dummy(30)
```

Vue.js:
https://www.npmjs.com/package/vue-dummy

Other Frameworks / Module Builders: `npm install dummyjs --save`
```JS
var Dummy = require('dummyjs');
```
