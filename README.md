## Computer_Security_lab_1
##### By Nevin Leh
For this assignment I decided on using metasploit as it was the tool demonstrated in class. After opening metasploit I   entered **use auxiliary/scanner/ssh/ssh_login**. I then entered the settings seen in the following screenshot.
![alt text](http://i.imgur.com/kRcDaKg.png?1 "Settings on metasploit")  
Unfortanetly the nmap list I used did not contain the desired password. I changed my list and retried with the fasttrack  word list instead.
![alt text](http://i.imgur.com/NDkmzHh.png "Success!")  
The new wordlist succeeded! As you can see the password is changeme.
