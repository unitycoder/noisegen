# noisegen

**note: noisegen is currently under development and is not publicly available.**

## Overview

**noisegen** is a web-tool used to generate noise and coherent noise using a variety of algorithms.

The resulting images may be used in a number of applications from background images, terrain heightmaps, textures, and more. It is also intended as a learning platform for the exploration and understanding of the various noise generation techniques.

It is implemented entirely client-side using JavaScript and HTML5. It has a dependency on the following libraries:

* [jQuery 3.1.1](https://jquery.com/)
* [Spectrum Colorpicker](https://github.com/bgrins/spectrum)

## Noise

The following 2D noise algorithms are available, or will soon be available, for use. They are split into 'pure noise' and 'coherent noise' categories:

**Pure Noise (via Random)**

* XorShift32
* XorShift128
* WELL512
* CMWC131104
* _Mersenne Twister 128 ([not yet available](https://github.com/ssell/noisegen/issues/9))_
* _Mersenne Twister 19937 ([not yet available](https://github.com/ssell/noisegen/issues/8))_

**Coherent Noise**

* Perlin Noise
* Simplex Noise
* _Wavelet Noise ([not yet available](https://github.com/ssell/noisegen/issues/3))_
* _Worley Noise ([not yet available](https://github.com/ssell/noisegen/issues/27))_
* _Diamond-Square ([not yet available](https://github.com/ssell/noisegen/issues/4))_

## Examples

The following are example images generated by **noisegen**.

**Perlin Noise (Raw & Clouds)**

![](https://cloud.githubusercontent.com/assets/734145/23099240/2d52f4e0-f630-11e6-942c-b3156c60bcb5.png)

![](https://cloud.githubusercontent.com/assets/734145/23099239/2d5001fe-f630-11e6-98c6-50c3573b64be.png)

**Simplex Noise (Raw & Islands)**

![](https://cloud.githubusercontent.com/assets/734145/23100239/0ec437b8-f64a-11e6-850b-a3fd919f6a4e.png)
![](https://cloud.githubusercontent.com/assets/734145/23100247/30d64378-f64a-11e6-8d18-ad1e2fa7d33e.png)

## License 

**noisegen** is licensed under the Apache License, v2.0 which may be read [here](https://github.com/ssell/noisegen/blob/master/LICENSE). 

