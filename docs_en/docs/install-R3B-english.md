# Installing Raspbian

Follow Raspbian installing instructions on the website : https://www.raspberrypi.org/downloads/raspbian/
Flash Raspbian image on the micro SD card. It is possible to use Balena Etcher which is a cross-platform tool for flashing images to SD cards & USB drives

# Setup of the Raspberry Pi 3B+

## Password
The default passwordfor pi session is “raspberry”. It can be redefined. To do so, you only need a serial connection with a keyboard, a computer mouse, a screen and an HDMI cable. 

## Enable SSH
To be connect to the Raspberry Pi without keyboard, computer mouse, screen and HDMI cable, it is possible to use SSH. To do so, you should enable this command following these instrcutions : 
In Raspberry Pi console enter "raspi-config", chose “Interfacing options” and select SSH. Chose “Enable” or "Yes".

# Project installation

The source code of our project is available on a git foundation. To collect all the files you need to enter "sudo git clone https://github.com/alison-foundation/alisonproject.git" on the console. 

# Dependencies installation 

pip3 install numpy
pip3 install scipy
pip3 install matplotlib
pip3 install sklearn
sudo apt-get update
sudo apt-get install portaudio19-dev
pip3 install pyaudio
sudo apt-get install llmv
pip3 install librosa

pip3 install libnmf (to be verified)
