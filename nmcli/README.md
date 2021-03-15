# NetworkManager (nmcli)

## New Connection
```sh
# show device status
nmcli dev status
# new ethernet connecton
nmcli con add type ethernet con-name <name> ifname <interface>
```

## New Wifi
```sh
# rescan
nmcli device wifi rescan
# list
nmcli device wifi list
# add connection
nmcli --ask device wifi connect <ssid-name>
```

## Interactive Mode
```sh
# start interactive editing
nmcli con edit <con-name>
# show all options
print
# show only some options
print connection
print ipv4
```
