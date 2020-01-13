# Automatically connect to expressvpn on boot up with systemd
A script and configuration for automatic start on boot for expressVPN with systemd in linux.

How it works.
1. install ExpressVPN from their ExpressVPN homepage.
2. copy expressvpnconnect.service file to /etc/systemd/system/
3. copy expressvpn.sh file to /usr/bin/
4. do following command to make it executable: "sudo chmod +x  /usr/bin/expressvpn.sh" to make it executable.

Done! you can reboot the computer and verify that the VPN starts on bootup.

Hope it helps.
