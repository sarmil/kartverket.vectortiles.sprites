# Sprite genering for [kartverket.vectortiles](https://github.com/kartverket/kartverket.vectortiles) repository

According to the [style spec](https://docs.mapbox.com/mapbox-gl-js/style-spec/sprite/), a sprite is a single png image and accompanying json file containing all symbol images. This is required for a map style.

This repository contains the svg files used in [kartverket.vectortiles](https://github.com/kartverket/kartverket.vectortiles).

More symboles can be found on [Geonorge](https://register.geonorge.no/register/symbol)

Se [How to create a sprite](https://support.maptiler.com/i643-own-map-icons-sprites) for more information.

Here a different version of spritezero-cli is used, since the original one was not updadet to a newer version of spritezero.

## Usage

npm install -g https://github.com/geoloniamaps/spritezero-cli
spritezero [output filename] [input directory]

## Example
spritezero landtopo ./img

