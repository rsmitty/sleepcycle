# sleepcycle
An old C++ script to automate sleep/wake in Ubuntu. It's ugly, but it works! Relies heavily on crontab and rtcwake commands.

The absolute basics are that the cpp file reads desired start and end times from the config file, then installs the corresponding rtcwake commands into root's crontab.
