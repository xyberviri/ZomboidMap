# ZomboidMap
Online Map for Project zomboid 

Use [CartoZed](https://theindiestone.com/forums/index.php?/topic/21633-cartozed/) to export your map

Then use [libvips](https://www.libvips.org/) to convert your end result into tiles for leaflet.

```vips.exe dzsave input.png images --layout google --background 0 --centre --suffix .jpg[Q=100]```

See an example here: https://media.epicgamer.org/pz/

Adjust transforms on line 39 to correct zooming, 

when map is no longer square because of other maps being imported im not really sure what to do at that point cause html/javascript/leafet/tiles isnt really my strong point. so any help is appreciated this is mostly just hacked together
