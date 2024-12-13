# pi-ssd1351
repo for a oled display whith a ssd1351 driver

first install with: 
  https://luma-oled.readthedocs.io/en/latest/software.html

Then get the examples working as in:
  https://github.com/rm-hull/luma.examples

then the examples can be run with:
  ~/luma-env/bin/python3  luma.examples/examples/video.py -d ssd1351  -i spi --height 128 -r 3 --bgr
