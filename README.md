# Hackintosh-Dell-Latitude-E5440
#### I am sharing my hackintosh clover configuration files for my Dell Latitude E5440. Feel free to use them and contribute! :)

![My Dell Latitude E5440 running macOS Mojave](https://i.imgur.com/QqpBcfe.jpg)
My Dell Latitude E5440 running macOS Mojave (boots Catalina too!)

### My laptop's specs:
* CPU: Intel Core i5 4210U
* RAM: 8GB DDR3
* Graphics: Intel HD 4400
* SSD: 120GB

### Working:

* Display: brightness, integrated graphics with acceleration
* WiFi: had to replace the Intel WiFi card with a Broadcom BCM4322, very easy to do since Dells do not have a whitelist
* USB: All USB 2.0 and 3.0 ports work flawlessly
* Audio: Works with a few hiccups (explained below)
* Sleep
* Ethernet
* HDMI output: Works with a few hiccups (explained below)
* Touchpad
* Integrated camera

### Bugs:

* Audio: After booting, headphone jack does not work, this can be fixed by putting the laptop into sleep and waking it up.
* HDMI: Weird glitches when the computer boots with the HDMI plugged in.
* VGA: Will not work, as this is not supported by macOS for Haswell graphics at all
* Card reader: not tested
* NVIDIA graphics: Will not work. If you have a model with NVIDIA graphics, you want to add nv_disable=1 to your boot flags.

#### (Those may vary depending on the specs of your laptop)
