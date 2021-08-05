# uplay
fake python MPRIS player based on bluez simple-player example

To run:

- copy the .conf file to the pointed directory.
- systemctl reload dbus
- connect bluetooth hosts
- run ./uplay in one host
- send Play/Pause commands from the other host (using d-feet or dbus-send)
