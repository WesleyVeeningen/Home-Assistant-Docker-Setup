# Home-Assistant-Docker-Setup

sudo apt install chromium-browser unclutter

nano ~/.config/lxsession/LXDE-pi/autostart

@xset s off
@xset -dpms
@xset s noblank
@unclutter -idle 0
@chromium-browser --kiosk --noerrdialogs --disable-infobars http://localhost:8123
