# selectize-bootswatch
Bootswatch skins for selectize

Provides CSS files ready to use for [selectize.js](http://selectize.github.io/selectize.js/) (v0.12.2) with [Bootswatch](https://bootswatch.com/) (v3.3.6) themes.

# Usage
```html
<!-- Include Bootstrap & Bootswatch as usual -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet" />
<link href="https://maxcdn.bootstrapcdn.com/bootswatch/3.3.6/cosmo/bootstrap.min.css" rel="stylesheet" />

<!-- Include Selectize js as usual -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/selectize.js/0.12.2/js/standalone/selectize.min.js"></script>

<!-- Include a Bootswatch-selectize css instead, choose one in the css folder corresponding to your selected bootswatch theme -->
<link rel="stylesheet" type="text/css" href="selectize.cosmo.css" />

<!-- Create your selectize component as usual -->
<script>
$(function() {
	$('select').selectize(options);
});
</script>
```
