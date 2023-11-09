# user level

## EDITOR variable
`export EDITOR="/usr/bin/nvim"`
to set nvim as default text editor

# system level

## notification-daemon
check file /usr/share/dbus-1/services/org.freedesktop.systemd1.service
edit the *Exec* part adding the notification daemon. Usually /usr/lib/notification-daemon/notification-daemon

## webcam
packages: v4l-utils guvcview
`v4l2-ctl --list-devices` to list devices
`guvcview /dev/video0` to see webcam feed
