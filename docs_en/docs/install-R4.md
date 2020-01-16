The installation process on Raspberry Pi has not been thouroughly tested by the development team, but we tested compatatibily for all libraries used by Alison.

# Installing Raspbian

Follow Raspbian installing instructions on the website: https://www.raspberrypi.org/downloads/raspbian/
Flash Raspbian image on the micro SD card. It is possible to use Balena Etcher which is a cross-platform tool for flashing images to SD cards & USB drives

# Setup the Raspberry Pi 4

## Password
The default password for Pi session is “raspberry”. It can be redefined. To do so, you only need a serial connection with a keyboard, a computer mouse, a screen and an HDMI cable. 

## Enable SSH
It is possible to connect to the Raspberry Pi without keyboard, computer mouse, screen or HDMI cable, using SSH. To do so, you should enable this command following these instructions : 
In the Raspberry Pi console enter "raspi-config", choose “Interfacing options” and select SSH. Choose “Enable” or "Yes".

# Project installation

The source code of our project is available on a git foundation. To collect all the files you need to enter " sudo git clone https://github.com/alison-foundation/alisonproject.git " on the console. 

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
pip3 install phue
pip3 install libnmf 

# Troubleshooting

If you have any issues installing libraries with pip, you can try using [Conda](https://docs.conda.io/en/latest/). All the libraries are not available, but all the problematic ones are in it. You might want to look at Conda forge to find non-official libraries that usually are pretty-well maintained by the community.
