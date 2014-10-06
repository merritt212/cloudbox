Cloudbox
========
Yet another sound map template built with SoundCloud + Mapbox

Define the map HTML
-------------------

Options:

* `data-location` - map center point (latitude, longitude)
* `data-zoom` - starting zoom level
* `data-style` - [Mapbox style ID](https://www.mapbox.com/design/)

```html
<div id="map"
	data-location="40.7127837,-74.0059413"
	data-zoom="12"
	data-style="examples.map-i86nkdio">
</div>
```

Add marker links
----------------

Options:

* `data-location` - marker location (latitude, longitude)
* `data-description` - optional text
* `data-symbol` - [Maki marker symbol](https://www.mapbox.com/maki/)
* `data-color` - hex color of marker
* `data-size` - set to `large`, `medium`, or `small`

```html
<a href="https://soundcloud.com/spenczar/canal-mulberry"
	data-location="40.71703,-73.998649"
	data-description="Recorded in Chinatown using Coresound binaural omnidirectional microphones. Feb 23, 2006."
	data-symbol="bus"
	data-color="#271B1D"
	data-size="small"
	class="marker">Canal &amp; Mulberry</a>
```
