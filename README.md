# LED-Matrix-Controller
This sketch controls a NeoPixel compatible LED matrix to display different images when different buttons are pressed.

To use it, install the Adafruit_NeoPixel library and confirm the LED_PIN an LED_COUNT variables in the sketch.

At this point in time I don't have logic to change the image with buttons, it just cycles through them every 10 seconds. So far there are 3 images: a heart, a sad face, and a happy face.

To generate the images use gimp to edit/create a 16x16 image (or whatever size your LED matrix is) and export it as "C source code (*.c)"
