# Usage
	
```javascript
var haystack = ["ActionScript", "AppleScript", "Asp", ...];
$('#container').suggest(haystack, { 
  suggestionColor   : '#cccccc',     // default
  moreIndicatorClass: 'suggest-more' // default
});
```

```html
<input type="text" name="search" id="search" />
```

More information and demo can be found [here](http://polarblau.github.com/suggest/).

The plugin will generate the CSS required based on the input's styles.
	
This plugin currently doesn't support remote resources for haystacks for performance reasons. This might change in the future.