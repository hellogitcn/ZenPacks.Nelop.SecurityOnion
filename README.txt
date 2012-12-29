Simple zenpack to ensure all critical process of the SecurityOnion distro are monitored.

Normal Installation (packaged egg)

1) Download the appropriate egg file for the version of Zenoss you are running.
2) Ensure you are logged in as the zenoss user:
	$ sudo su - zenoss
3) Install the ZenPack:
	$ zenpack --install ZenPacks.community.SecurityOnion-1.0.3-py2.7.egg
4) Restart these services:
	$ zenoss restart
5) From the Web GUI remodel the your SecurityOnion server and all processes should be monitored.
