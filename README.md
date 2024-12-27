INSTALAR OPENVPN Ubuntu-server24.04

1-wget https://git.io/vpn -O openvpn-install.sh
2-chmod +x openvpn-install.sh 

3-sudo bash openvpn-install.sh 

4-sudo systemctl cat openvpn-iptables.service

5-sudo less /etc/openvpn/server/server.conf

6-sudo systemctl status openvpn-server@server.service 

7-sudo ls -l /root/

8-sudo mv /root/domingo08.ovpn .

9-scp domingo08@38.50.165.116:/home/domingo08/scripts/*.ovpn .

