# Setup EduRoam on Raspberry Pi

Follow these steps:

1. Copy the file [ca.pem](./ca.pem) to the `.config` folder in your home folder. (If this folder doesn't exist then create it)
2. Click on the Wi-Fi icon in the top right corner of the desktop. ![WiFi Menu](wifi-menu.png)
3. Select `Advanced Options` ![WiFi Advanced Options](wifi-edit-connections.png)
4. Select `Edit Connections` to open the Network Connections panel ![WiFi Edit Connections](wifi-network-connections.png)
5. Select the WiFi network and edit to open the Editing panel. The following images show the settings in each tab. In the Wireless Security tab, navigate the "CA certificate' to the file just downloaded `ca.pem`. ![WiFi Edit General Tab](wifi-edit-general.png) ![WiFi Edit Wireless Tab](wifi-edit-wireless.png) ![WiFi Wireless Security Tab](wifi-edit-security.png) ![WiFi Edit Proxy Tab](wifi-edit-proxy.png) ![WiFi Edit IPv4 Tab](wifi-edit-ipv4.png) ![WiFi Edit IPv6 Tab](wifi-edit-ipv6.png)
