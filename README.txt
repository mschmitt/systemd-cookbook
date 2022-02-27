Systemd units for random stuff I formerly ran from /etc/rc.local or @reboot from crontab

Note that user units need session lingering to be enabled: 

apt-get install dbus-user-session
loginctl enable-linger <user>