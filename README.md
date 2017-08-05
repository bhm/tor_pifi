# Tor Pi FI for Raspberry Pi Zero W

## Elevator pitch

Badabing bada boom, Tor over wlan1 interface and connection over wlan0.

In simpler terms. 

1. Raspi Zero W connects via onboard chip. 
2. Hosts WiFi over attached adapter.

## Motivation

So you find a ton of Raspi PiFi tutorials, right? Right. 
They go through all the hoops. 

Voodoo this. Command line this. Comment that out. Insert this...

Problem being 

1. Often those don't work at all. Found out the hard way.
2. Steps null each other out
3. Tutorials don't go indepth or assume a lot of stuf.
4. You need to do this stuff over and over again.

## Enter a Dragon

### BHM's HERE WITH A SCRIPT TO CONFIGURE A WIFI ACCESS POINT!
### WITH ONE SIMPLE YES, Y OR ENTER YOU CAN ADDITIONALLY 
### CONFIGURE A TOR CONNECTION

## Do it

1. Flash Raspbian.
2. scp the file over to Raspi `scp ./tor_pifi_wlan1.sh pi@192.168.0.0:/home/pi/` (insert a proper Raspi IP)
3. Connect it via SSH (network or USB)
4. Make the script runnable `chmod +x ./tor_pifi_wlan1.sh`
5. Run `sudo ./tor_pifi_wlan1.sh`


