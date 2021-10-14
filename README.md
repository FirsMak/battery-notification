# battery-notifier
## _This is a simple battery notifier_

I used this script for arch+i3

When the battery is approaching a critical value, the script plays a video (I used a video with spider sense)

![alt text](https://github.com/FirsMak/battery-notification/blob/main/screen.png?raw=true)

## Installation
script uses grep and upower
```sh
git clone https://github.com/FirsMak/battery-notifier.git
cd battery-notifier/
sudo cp battery-notifier /usr/local/bin/
sudo cp source/ting3.mp4 /usr/local/bin/
```

## i3
add in config /home/username/.config/i3/config
```sh
exec --no-startup-id battery-notifier
```
