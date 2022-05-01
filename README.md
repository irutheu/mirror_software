# mirror_software
Software for smart mirro project.

## Installation:
- python -m venv venv38
- . venv38/bin/activate
- pip install -r requirements.txt


## Raspberry PI custom settings
- In boot/config.txt change parameter "dtoverlay" to "vc4-fkms-v3d"
- Run in run: "xrandr --output HDMI-1 --rotate right"

## Kiosk mode
Run in terminal: "firefox -kiosk *main_page_path*"