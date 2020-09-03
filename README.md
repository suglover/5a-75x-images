# 5a-75x-images

A collection of flash images from Colorlight 5A-75B / 5A-75E boards.

## How to dump image

To read out a flash chip on your board, you need an ftdi-based JTAG adapter and [ecpprog](https://github.com/gregdavill/ecpprog) software.
You can use the following command to dump the image:
```
ecpprog -r image.bin -R 4M
```
If you have a flash chip of a different size, replace 4M with a matching size.

Please, send your image to suglover@protonmail.com, including the description of the board (board type+version and full FPGA chip name)! All images will be uploaded here.

## See also

[Chubby75](https://github.com/q3k/chubby75) is a project to reverse engineer, document and provide tools for LED Receiver Cards. This project aims to reuse LED controller boards available on the market as FPGA development boards. There is a pinout documentation available for several Colorlight boards:

* [Colorlight 5A-75B V6.1](https://github.com/q3k/chubby75/blob/master/5a-75b/hardware_V6.1.md)
* [Colorlight 5A-75B V7.0](https://github.com/q3k/chubby75/blob/master/5a-75b/hardware_V7.0.md)
* [Colorlight 5A-75E V6.0](https://github.com/q3k/chubby75/blob/master/5a-75e/hardware_V6.0.md) - only for a board based on the CABGA256 package
* [Colorlight 5A-75E V7.1](https://github.com/q3k/chubby75/blob/master/5a-75e/hardware_V7.1.md)
