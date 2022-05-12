# rsa-raw
Textbook RSA encode &amp; decode

## Overview
In order to encipher, use `RSA.encipher(YOUR_DATA)`. The `YOUR_DATA` should be a `Buffer`. Again, to decipher, use the same procedure but this time `RSA.decipher(YOUR_DATA)`. Additional functions include returning the `Modulus` using `RSA.modulus()`, and producing a scrambled `Modulus` using `RSA.scrambleMod()`.

Keep in mind that this is as simple as possible, padding is disabled.

## License
Open-source under [Apache 2.0 license](https://www.apache.org/licenses/LICENSE-2.0).
