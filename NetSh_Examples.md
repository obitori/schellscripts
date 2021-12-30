# netsh
## Open Firewall Port
netsh advfirewall firewall add rule name="TCP port 8989" dir=in enable=yes action=allow protocol=TCP localport=8989

## Delete Firewall Port
netsh advfirewall firewall delete rule name="TCP port 8989"