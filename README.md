# Analyzing the Diamonds dataset

[![Status](https://img.shields.io/badge/Status-Work%20in%20progress-orange.svg)](https://github.com/BarbaraStempien/DA--Diamonds-Are-Forever)

## Table of Contents

* [Description](#description)
* [Tools & Dependencies](#tools)
* [Contributing](#contributing)
* [License](#license)

## Description

Prices of 50,000 round cut diamonds

A dataset containing the prices and other attributes of almost 54,000 diamonds. Data frame has 53940 rows and 10 variables:

    price      price in US dollars (\$326--\$18,823)
    carat      weight of the diamond (0.2--5.01)
    cut        quality of the cut (Fair, Good, Very Good, Premium, Ideal)
    color      diamond colour, from J (worst) to D (best)
    clarity    a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
    x          length in mm (0--10.74)
    y          width in mm (0--58.9)
    z          depth in mm (0--31.8)
    depth      total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)
    table      width of top of diamond relative to widest point (43--95)

## Tools & Dependencies

Analysis has been performed in the [Jupyter Notebook](http://jupyter.org/), using R kernel.

## Contributing

If you want to contribute, check out [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[MIT License](LICENSE)

Copyright (c) 2018 Barbara Stempien

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
