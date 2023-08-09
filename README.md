# Ender 3 Neo Printer Project

These are my configuration files for the Klipper install on my Ender 3 Neo. I have included a list of features in the configuration file and some works in progress. I also listed out the hardware and software used for my prints. Macros have been broken out into a seperate configuraion file for better readability. I'm working on addtional documentation and diagrams regarding some of my additions.

Edit repo

## Configuration Features
* Mainsail frontend
* CR Touch
* Beeper & LCD integration
* Custom macros
  - Start/End
  - Beeper (M300)
  - Color change (M600)
  - LED controls  
* PID autotuning
* Input shaper
* Screws tilt adjust
* MCU temperature reportin
* Raspberry Pi as secondary MCU
  - Raspberry Pi Camera
  - ADXL345 accelerometer
  - Host temperature reporting
  - Custom LED controller
  - HTU21D environment sensor

## Hardware & Software
* Ender 3 Neo
* BTT SKR Mini E3 V3.0
* Capricorn PTFE
* Raspberry Pi 4B with camera
* SuperSlicer

## Works In Progress
* This write up!

### Credits
* [KIAUH](https://github.com/th33xitus/kiauh) 
  - <sub>Klipper installation made super easy</sub>
* [Ellis3DP](https://ellis3dp.com/Print-Tuning-Guide/)
  - <sub>For all the tuning needs</sub>
* [SuperSlicer](https://github.com/supermerill/SuperSlicer)
  - <sub>The most Klipper friendly slicer</sub>  
* [Klipper](https://www.klipper3d.org)
  - <sub>And you can't forget who made this all possible</sub>    

If this was useful, I'd appricate a cold beer or hot coffee: [![coffee](https://www.buymeacoffee.com/assets/img/custom_images/black_img.png)](https://www.buymeacoffee.com/alteredworkshop)

<sub>Please consider this to be a work in progress. I am constantly tinkering, improving, and breaking things. Remember, this is my configuration and it may not work as intended on your machine. Review the files before deploying as I am not responsible for damage to your hardware.</sub>
