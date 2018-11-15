# Week-9-Project-Honeypot
Time Spent: **5** hours spent in total

# Which Honeypot(s) you deployed
I deployed Ubuntu - Dionaea with HTTP.

# Any issues you encountered
During the installation of the MHN Admin Application, I encountered a repository that either did not exist or was made private. To correct this, I had to do some research and then update the install_hpfeed.sh file with the correct repository name. 

# A summary of the data collected: number of attacks, number of malware samples, etc.
Instantly after deploying the honeypot, I received serveral attacks. While the honeypot remained up, I received attacks from various countries. Many attacks had a destination port of 8088, but there were many other ports that were attacked. Some attackers attacked more than once. In total, I received 158 attacks.

# Any unresolved questions raised by the data collected
Why is port 8088 such a popular port to attack?
