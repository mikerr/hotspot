# hotspot
Create a wifi hotspot 

Give Wifi access from wired ethernet:

    iptables-restore < iptables.ipv4.nat.eth0

Give Wifi access from another Wifi AP (e.g. BTWiFi-with-FON)

    iptables-restore < iptables.ipv4.nat.wlan1
    
Ready made SD .img at https://sourceforge.net/projects/pi-ap/
