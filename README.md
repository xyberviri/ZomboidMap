# ZomboidMap
Online Map for Project zomboid 

Use [CartoZed](https://theindiestone.com/forums/index.php?/topic/21633-cartozed/) to export your map

Then use [libvips](https://www.libvips.org/) to convert your end result into tiles for leaflet.

```vips.exe dzsave input.png images --layout google --background 0 --centre --suffix .jpg[Q=100]```

See an example here: https://media.epicgamer.org/pz/

Adjust transforms on line 39 to correct zooming, 

Export maps so they are always squared to avoid issues iwth conversion. 
