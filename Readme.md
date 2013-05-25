
# hn-button-snippet

  Template functions for rendering Hacker News buttons.

## Installation

    $ component install segmentio/hn-button-snippet

## API
    
### snippet
```js
var snippet = require('hn-button-snippet');
snippet();
```

Will render the full snippet:

```html
<a href="https://news.ycombinator.com/submit" class="hn-button">Vote on HN</a>
<script type="text/javascript">var HN=[];HN.factory=function(e){return function(){HN.push([e].concat(Array.prototype.slice.call(arguments,0)))};},HN.on=HN.factory("on"),HN.once=HN.factory("once"),HN.off=HN.factory("off"),HN.emit=HN.factory("emit"),HN.load=function(){var e="hn-button.js";if(document.getElementById(e))return;var t=document.createElement("script");t.id=e,t.src="//hn-button.herokuapp.com/hn-button.js";var n=document.getElementsByTagName("script")[0];n.parentNode.insertBefore(t,n)},HN.load();</script>
```

### button
```js
var snippet = require('hn-button-snippet');
snippet();
```

Will render just the button:

```html
<a href="https://news.ycombinator.com/submit" class="hn-button">Vote on HN</a>
```

### script
```js
var snippet = require('hn-button-snippet');
snippet();
```

Will render just the script:

```html
<script type="text/javascript">var HN=[];HN.factory=function(e){return function(){HN.push([e].concat(Array.prototype.slice.call(arguments,0)))};},HN.on=HN.factory("on"),HN.once=HN.factory("once"),HN.off=HN.factory("off"),HN.emit=HN.factory("emit"),HN.load=function(){var e="hn-button.js";if(document.getElementById(e))return;var t=document.createElement("script");t.id=e,t.src="//hn-button.herokuapp.com/hn-button.js";var n=document.getElementsByTagName("script")[0];n.parentNode.insertBefore(t,n)},HN.load();</script>
```

## License

  MIT