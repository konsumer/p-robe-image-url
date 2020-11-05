# probe-image

This is an isomorphic way to get the dimensions of an image.

## Supported formats

* BMP
* CUR
* DDS
* GIF
* ICNS
* ICO
* JPEG
* KTX
* PNG
* PNM (PAM, PBM, PFM, PGM, PPM)
* PSD
* SVG
* TIFF
* WebP

## usage

```js
import imageProbe from 'probe-image'

imageProbe('https://URL').then(console.log)
```