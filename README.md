Week 9 assignment
For this weeks assignment we created honeypots to monitor network exploits on our open ports.The honeypots I created were
the normal dionaea honeypot which just detects when malware is scanning for open ports. I was most familiar with that honeypot, but i
also used elastichoney, and a pOf honeypot. Downloading and setting up the honeypots were overwhelming since there was lots of new commands and VM's along with technology that needed to be installed to get it to work. My virtual machines ran on the google cloud with my 
free trial. I had issues with disabling my firewall on google cloud to get the MHN admin site to work as well as opening the ports within myhoneypot to see all of the attacks.In total I had roughly 1000 attacks over a 24 hour period from all over the world mostly coming from the command nmap. Nmap, or network mapper, is a security scanner used to discover hosts and services on a network. It maps the network by 
sending packets.In the server VM, I installed nmap using apt and then I ran a scan against the honeypot VM.

GIF:
https://imgur.com/a/ps2E2
