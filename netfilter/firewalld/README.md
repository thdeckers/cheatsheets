# Firewalld (firewall-cmd)

## Ports

```sh
# add service
firewall-cmd [--zone=<zone name>] --add-service=ssh
# remove service
firewall-cmd --remove-service=<service>
# add port
firewall-cmd --add-port=<port>/<proto>
# remove port
firewall-cmd --remove-port=<port>/<proto>
# add port for a short duration
firewall-cmd --add-port=<port>/<proto> --timeout=<Ns|Nm|Nh>

# Examples:
firewall-cmd --add-port=80/tcp

firewall-cmd --add-port=8080/tcp --timeout=1h
```

## Zones

```sh

# list all zones
firewall-cmd --list-all-zones
# list only the name of all zones
firewall-cmd --get-zones
# list zones in use
firewall-cmd --get-active-zones  
# new zone
firewall-cmd --permanent --new-zone=<zone name>
#
#
#
# add sources to a zone
firewall-cmd --zone=<zone> --add-source=<source>
```


