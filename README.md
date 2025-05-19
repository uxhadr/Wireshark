# Wireshark
I started by installing a Ubuntu VM on my Virtualbox
When Ubuntu was setup I ran the following commands: 
To upgrade my sytem: `sudo apt update && sudo apt upgrade -y`
To install Wireshark: `sudo apt install wireshark -y`
I also selected yes for wireshark to allow non-superusers to be able to capture packets
After it was completed I ran the command `Wireshark` which opened wireshark
![image](https://github.com/user-attachments/assets/da55ae0c-b1f3-4609-a0d2-ad08d4862cb2)

Wireshark was showig me the time, source, destination, protocol ,length and info but as a security analyst I would need more information.
So on the bottom I expanded the `User Datagram Protocol` then right-clicked on source port and slected appy as column. which added a sourceport column.
I did the same to add a destination port.


