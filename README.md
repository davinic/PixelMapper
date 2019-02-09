# PixelMapper for TouchDesigner

This project allows you to define LED pixel strips in a table, map them to sources, and output them to ArtNet/DMX. Based on the parameters in the fixtures table, the strips will render in 3d space and map to 3d input sources. 

This setup was developed using a Advatek PixLite4MkII running two WS2812B pixel strips of different lengths. My pixels were wired from the right so both of my inputs are rotated 180 degrees on the y axis. 

## Current Limitations:
* Sends one universe per strip. This needs to be optimized to allow chaining of strips which need to cross universe boundaries.  
* Not yet tested with 3d input sources
