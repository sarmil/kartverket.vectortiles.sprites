# Sprite genering for [kartverket.vectortiles](https://github.com/kartverket/kartverket.vectortiles) repository

According to the [sprite style spec](https://docs.mapbox.com/mapbox-gl-js/style-spec/sprite/) a single png and accompanying json file containing all symbol images is required for a map style. This repository contains a script for generating a sprite from a set of svg files.

More symboles can be found on [Geonorge](https://register.geonorge.no/register/symbol)


Se [How to create a sprite](https://support.maptiler.com/i643-own-map-icons-sprites) for more information.

Here a other version of spritezero-cli is used, since the original one was not updadet to a newer version of spritezero.

## Usage

npm install -g https://github.com/geoloniamaps/spritezero-cli
spritezero [output filename] [input directory]

