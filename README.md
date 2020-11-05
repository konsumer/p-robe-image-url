# probe-image

This is an isomorphic way to get the dimensions of an image.

# WIP

THis is a stub. I will finish when I have a little more time.

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