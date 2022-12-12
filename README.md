![Screenshot of the style rendered](/example.webp?raw=true)
# Map Libre Example

## Introduction
This repository contains an adaptation of the [Klokantech Terrain style](https://github.com/IllusionVK/klokantech-terrain-gl-style) to make it work with [MapTiler](https://www.maptiler.com/) tiles served by [mbtileserver](https://github.com/consbio/mbtileserver).

## Try it

In order to solve CORS requirements, you have to launch a local reverse proxy by using the following command (it required Caddy webserver) :
```sh
caddy run --config Caddyfile
```

Then open the following link : http://localhost:3000
