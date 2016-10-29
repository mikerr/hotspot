# hotspot
Create a wifi hotspot 

Provide Wifi access from wired ethernet (Access Point)

    iptables-restore < iptables.ipv4.nat.eth0

Provide wired ethernet access from wifi (gaming adaptor)

    iptables-restore < iptables.ipv4.nat.to-eth0
    
Give Wifi access from another Wifi AP (e.g. BTWiFi-with-FON)

    iptables-restore < iptables.ipv4.nat.wlan1
    
Ready made SD .img at https://sourceforge.net/projects/pi-ap/
