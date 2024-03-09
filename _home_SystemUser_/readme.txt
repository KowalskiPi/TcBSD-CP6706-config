/home/SystemUser/.config/openbox/autostart.sh
-> edit

#!/bin/sh

firefox --kiosk --private-window localhost:1010
xset dpms 0 0 0
xset s noblank
xset s off

-> run
chmod +x /home/SystemUser/.config/openbox/autostart.sh
