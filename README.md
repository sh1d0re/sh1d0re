sudo systemctl stop dhcpcd


sudo systemctl disable dhcpcd

sudo systemctl enable NetworkManager

sudo systemctl start NetworkManager



nmcli device wifi hotspot ifname wlan0 ssid MyPiHotspot password "MySecurePassword"

nmcli connection modify Hotspot ipv4.method shared


nmcli connection up Hotspot

nmcli connection modify Hotspot autoconnect yes

