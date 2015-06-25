# mongo-time

![screenshot](icon_144.png)
## Description
Mongo Time is a animated Pebble watchface that slides numbers in and out each minute. It is designed to be easy to read with very large numbers and a clean look. I originally created this watch because I wanted a watch face that was super easy to read and had a classy look. The Pebble Big Time watchface had this but lacked a stylish animation. So this project was created to have an easy to read watchface that had nice style on time transitions.

##Design
The Original Pebble is limited on font size and memory space. Like Pebble's Big Time watch face this watchface uses png images to display digits. Mongo Time adds animation calls to shift the number images in and out. The total transition time is always the same, regardless of the number of digits changed. This is so the watch remains readable at all times.

##Limitations
- Because the numbers are image files the colors can not be changed (Basalt Pebble Time watches)



## References
- [http://developer.getpebble.com/guides/publishing-tools/pebble-tool/](pebble tool commands)

A Pebble watchfaced based on pebbles on [big-time](https://github.com/pebble-examples/big-time) project.
##Build/Test Notes
- pebble login
- pebble list
- pebble build
- pebble install --emulator basalt
- pebble --debug install --emulator basalt
- pebble logs --emulator basalt

## etc
- I have had little success getting the emulator to work in aplite mode in the current dev kit (PebbleSDK 3.0-beta11)

