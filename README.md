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
