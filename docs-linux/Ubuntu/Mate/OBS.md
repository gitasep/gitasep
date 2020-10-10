# OBS (Open Broadcaster Software) Install linux
Please note that OBS Studio is not fully working on Chrome OS and features like Screen and Window Capture do not work.

xserver-xorg version 1.18.4 or newer is recommended to avoid potential performance issues with certain features in OBS, such as the fullscreen projector.
FFmpeg is required. If you do not have the FFmpeg installed (if you're not sure, then you probably don't have it), you can get it with the following commands:
```shell
sudo apt install ffmpeg
```
Then you can install OBS with the following commands, make sure you enabled the multiverse repo in Ubuntu's software center (NOTE: On newer versions of ubuntu adding a repository automatically apt updates.):
```shell
sudo add-apt-repository ppa:obsproject/obs-studio
sudo apt update
sudo apt install obs-studio
```
