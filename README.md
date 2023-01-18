# Simple IP blocking and packet (+message) sending app
Block and allow IP for incoming/outgoing traffic on Linux <br>
Send different packets <br>
Send message with socket to any port <br>
It is recommended to run the tool as a sudo user.

# Installation
$ git clone https://github.com/MaqaMansur/ibps-app-for-linux/ <br>
$ cd ibps-app-for-linux <br>
$ pip install -r requirements.txt <br>
$ sudo python ibps.py

# Note
If you want to view firewall rules : <br>
$ sudo iptables --list
