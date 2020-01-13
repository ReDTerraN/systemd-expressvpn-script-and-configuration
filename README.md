# systemd-expressvpn-script-and-configuration
A script and configuration for automatic start on boot for expressVPN with systemd in linux.

How it works.

1. copy expressvpnconnect.service file to /etc/systemd/system/
2. copy expressvpn.sh file to /usr/bin/
3. do following command to make it executable: "sudo chmod +x  /usr/bin/expressvpn.sh" to make it executable.

Done! you can reboot the computer and verify that the VPN starts on bootup.

Hope it helps.
