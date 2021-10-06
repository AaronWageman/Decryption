# Decryption

# Group Members
 - Aaron Wageman
 - Justin Hirner
 - Precious Shittu

# Subtopics
 - Spotting weak passwords 
 - 


# Tools Used
 - John The Ripper
 - Tutorial guide for John The Ripper: https://www.varonis.com/blog/john-the-ripper/
 - John The Ripper command docs: https://www.openwall.com/john/doc/OPTIONS.shtml
 - John The Ripper modes docs: https://www.openwall.com/john/doc/MODES.shtml


# Spotting Weak Passwords (Aaron Wageman)

### Sources Used
 - John The Ripper
 - Tutorial guide for John The Ripper: https://www.varonis.com/blog/john-the-ripper/
 - John The Ripper command docs: https://www.openwall.com/john/doc/OPTIONS.shtml
 - John The Ripper modes docs: https://www.openwall.com/john/doc/MODES.shtml

John The Ripper can be used as a tool in IT. John The Ripper's password cracker allows for companies to see if their employees are following good password practices.
John the ripper has 3 modes:
  - single crack 
  - wordlist
  - incremental

Single crack mode cracks password hashes by using login names, "GECOS", and the users home directory names. Wordlist mode allows the user to try and break the password with a list of popular passwords such as "password". John the ripper takes the words from the wordlist and makes them into hashes. Then these hashes are compared to the hashes supplied in the password file given by the user. Lastly, is the incremental which is a brute-force password cracker. There are some issues with the incremental mode. The incremental mode can take long amounts of time and can sometimes never end if the password is too strong (which is good for the password).

### Code And Processes





