Hello and welcome to my WPA2 dictionary script.

First things first. The following can only be run in a POSIX system.
In my case I have used Backtrack
If you want to use another POSIX system make sure to do:
                                                        
                                                        apt-get install airmon-ng
                                                        
                                                        apt-get install airodump-ng
                                                        
                                                        apt-get install aireplay-ng
                                                        
                                                        apt-get install aircrack-ng

1. Create a folder ./Desktop/crackcap
2. Create a folder ./Desktop/dictionary
                     
                      In the folder "dictionary" you will put a .txt file with your dictionary. 
                      
                      (A dictionary is a collection of as many passwords you can come by).
                      
                      If you want to be sure of a succesfull crack, enter the password of the AP you want to crack.

3. Open terminal and paste the script to: nano /usr/sbin/cackwpa2 and save changes
4. In terminal and write: chmod +x /usr/sbin/crackwpa2

5. In terminal write: crackwpa2

Have fun