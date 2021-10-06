# Decryption

## Group Members
 - Aaron Wageman
 - Justin Hirner
 - Precious Shittu

## Subtopics
 - Spotting weak passwords 
 - 


## Tools Used
 - John The Ripper
 - Tutorial guide for John The Ripper: https://www.varonis.com/blog/john-the-ripper/
 - John The Ripper command docs: https://www.openwall.com/john/doc/OPTIONS.shtml
 - John The Ripper modes docs: https://www.openwall.com/john/doc/MODES.shtml

# How to Install and run John the Ripper
 - To start, go to the John the Ripper website. You can either Google "John the Ripper password cracker" or you can choose to follow this link: https://www.openwall.com/john/
 - Once there, download the binary file for your bit OS. We chose the installation of the 64-bit version. 
 - Once installed, find the zip file and extract it to a folder for which you want to keep it. 
 - Now, open the folder that you extracted the contents to, and open the "run" folder. 
 - Open your "Git Bash here" command, and run the command "./john"
 - Now you should have full access to the program


# Spotting Weak Passwords (Aaron Wageman)

## Sources Used
 - John The Ripper
 - Tutorial guide for John The Ripper: https://www.varonis.com/blog/john-the-ripper/
 - John The Ripper command docs: https://www.openwall.com/john/doc/OPTIONS.shtml
 - John The Ripper modes docs: https://www.openwall.com/john/doc/MODES.shtml

## Overview
John The Ripper can be used as a tool in IT. John The Ripper's password cracker allows for companies to see if their employees are following good password practices.
John the ripper has 3 modes:
  - single crack 
  - wordlist
  - incremental

Single crack mode cracks password hashes by using login names, "GECOS", and the users home directory names. Wordlist mode allows the user to try and break the password with a list of popular passwords such as "password". John the ripper takes the words from the wordlist and makes them into hashes. Then these hashes are compared to the hashes supplied in the password file given by the user. Lastly, is the incremental which is a brute-force password cracker. There are some issues with the incremental mode. The incremental mode can take long amounts of time and can sometimes never end if the password is too strong (which is good for the password).

### Code and Processes

Using the wordlist method:
1. Download the mynewwordlist.txt and newpassworddoc.txt from our github
2. Use git bash here in the "run" folder (See How to install above)
3. Run the command: ./john newpassworddoc.txt -wordlist="mynewwordlist.txt" --format=Raw-SHA256


5. Then run ./john --show --format=Raw-SHA256 newpassworddoc.txt











