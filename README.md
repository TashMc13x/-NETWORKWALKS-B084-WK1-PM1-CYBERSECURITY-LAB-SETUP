# -NETWORKWALKSEMMANUEL-B083-WK1-PM1-CYBERSECURITY-LAB-SETUP
Lab setup for cybersecurity, Assignment 1
The steps used to set up the Kali Linux:
1. Download the VM box and Kali Linux from google drive provided.
2. Installed VM box.
3. Set up the Nat Network, Ensuring the IPv4 was as directed.
4. Mounted Kali Linux ( Since the file from the google drive was a .iso file and not in a zipped folder, I had to use the "New" option and select the .iso file that was downloaded in order to have it mounted into VM box.
5. After Kali Linux was mounted, Installation was commenced. During the installation, I had to select the options for setting up the username and password instead of it auto-populating as showed in the video guide. Basically, manually entered the host name, domain name and password as Kali. 
6. Once set up was done, the wired 1 connection was edited, I had to change the DNS from 8.8.8.8 to 10.0.0.2 so the network could run.
7. I made a google search and the network worked, connection was fine. 
8. Created a snapshot of the kali Linux as directed. 

Additional Issues encountered:
When Kali Linux was restarted, there was a network issue, so I had to use the terminal to enter the commands provided. Network was fixed after that. Restarted and now works with no issues.

Also, went ahead and checked the network settings for the kali Linux VM and created a shared folder, that should automount on start up.
