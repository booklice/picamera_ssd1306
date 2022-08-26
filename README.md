# Picamera with OLED SSD1306

Picamera video streaming with oled ssd1306 (128x64).

## Installation and Usage

<img src="https://github.com/youn9jo/picamera_ssd1306/blob/main/ssd1306.png" height="250" align="left" />

<img src="https://github.com/youn9jo/picamera_ssd1306/blob/main/img.jpg" height="250" align="center" />

```shell
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install python3-pip
sudo pip3 install --upgrade setuptools
cd ~
sudo pip3 install --upgrade adafruit-python-shell
wget https://raw.githubusercontent.com/adafruit/Raspberry-Pi-Installer-Scripts/master/raspi-blinka.py
sudo python3 raspi-blinka.py
pip install opencv-python
pip install picamera2
sudo python app.py
```



## References

- https://github.com/raspberrypi/picamera2/blob/main/examples/capture_video.py
- https://github.com/micropython/micropython/blob/master/drivers/display/ssd1306.py
- https://github.com/souviksaha97/oled-video-player/blob/master/oled-viewer.py