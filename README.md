# RaspberryPi Scripts & Programs
Random code for RaspberryPi related stuff


## [cpuled.py](https://github.com/MrHDR/RaspberryPi/blob/master/cpuled.py)
Utilizes [Blinkt](https://thepihut.com/products/blinkt) to display CPU Temperature in 8 stages using 8 RGB Led's

Example:

![Leds](http://i.imgur.com/GHo3ujM.png)


1 Led = Below 10 Celcius

2 Leds = Between 10 & 20 Celcius

3 Leds = Between 20 & 30 Celcius

4 Leds = Between 30 & 40 Celcius

5 Leds = Between 40 & 50 Celcius

6 Leds = Between 50 & 60 Celcius

7 Leds = Between 60 & 70 Celcius

8 Leds = Above 70 Celcius

## [RsInstall.sh](https://github.com/MrHDR/RaspberryPi/raw/master/RsInstall.sh)
Runescape Installer for the Raspberry Pi

Warning: Rs3 will probably not work.(Limited Ram) OSRS However, will run on a Raspberry Pi 3B

Downloads the files and launchers to quickly launch RS3 Or OSRS from the desktop (Raspbian Full Only)

### Usage
```
wget https://github.com/MrHDR/RaspberryPi/raw/master/RsInstall.sh
sudo sh ./RsInstall.sh
sudo rm RsInstall.sh
```
#### If you do not want to run my script and would rather run the client manually you will need the following:

The [Legacy Runescape Windows Client](http://www.runescape.com/downloads/runescape.msi?13042016) & [lessmsi](https://github.com/activescott/lessmsi)
