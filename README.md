# Kwon-Choi
KAIST-DICIA MASTERCLASS

dli@dli-desktop:$ cd Downloads
dli@dli-desktop:~/Downloads$ git clone  https://github.com/jetsonworld/jetson-fan-ctl.git
dli@dli-desktop:~/Downloads$ ls
# jetson-fan-ctl

dli@dli-desktop:~/Downloads$ cd jetson-fan-ctl
dli@dli-desktop:~/Downloads/jetson-fan-ctl$ sudo sh install.sh

#Open terminal again
dli@dli-desktop:~$ sudo apt-get upgrade
dli@dli-desktop:~$ sudo apt-get update
#wait...

dli@dli-desktop:~$ sudo pat install python3-pip
# Installing this, Screen capture is available
dli@dli-desktop:~$ sudo pip3 list
dli@dli-desktop:~$ sudo -H pip3 install -U jetson-stats

dli@dli-desktop:~$ pip3 list|grep jetson

dli@dli-desktop:~$ reboot
# computer is rebooting
dli@dli-desktop:~$ jtop
# showing jetson's current stats

dli@dli-desktop:~$ ifconfig
# confirm jetson nano's ip address

dli@dli-desktop:~$ ls /dev/video0 -l
# confirm jetson can configure the cam

dli@dli-desktop:~$ git clone https://github.com/jetsonhacks/USB-Camera.git
dli@dli-desktop:~$ ls
dli@dli-desktop:~$ cd USB-Camera
dli@dli-desktop:~/USB-Camera$ ls
dli@dli-desktop:~/USB-Camera$ python3 usb-camera-gst.py

dli@dli-desktop:~$ nvgstcapture-1.0 --mode=1 --camsrc=0 --cap-dev-node=0 --automate --capture-auto
                                                 
dli@dli-desktop:~$ nvgstcapture-1.0 --mode=1 --camsrc=0 --cap-dev-node=0 --automate --capture-auto 
dli@dli-desktop:~$ nvgstcapture-1.0 --mode=2 --camsrc=0 --cap-dev-node=0
# capture current screen cam showes


