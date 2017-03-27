# Shutdown RPi on button press #

### Running at startup ###

edit /etc/rc.local and add "sudo python /path/to/script/shutdown_pi.py &" before "exit 0"
