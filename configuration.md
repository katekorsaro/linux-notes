# user level

## EDITOR variable
`export EDITOR="/usr/bin/nvim"`
to set nvim as default text editor

# system level

## webcam
packages: v4l-utils guvcview
`v4l2-ctl --list-devices` to list devices
`guvcview /dev/video0` to see webcam feed
