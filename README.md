# SSH-Brute

`ssh.py` is a simple brute force tool written in Python

# Installation

First, you must have pwntools library installed in order for the script to work in Kali Linux:

# Debian/Ubuntu/Kali

   `apt-get update`  
   `apt-get install python3 python3-pip python3-dev git libssl-dev libffi-dev build-essential`  
   `python3 -m pip install --upgrade pip`  
   `python3 -m pip install --upgrade pwntools`  

# Dependencies

   Python3  
   PIP  
   pwn tools  
   [Daniel Miessler's SecLists](https://github.com/danielmiessler/SecLists)
    
# Usage/Modifications

    Line 4 - Edit 'host'  
    Line 5 - Edit 'username'  
    Line 6 - Edit 'attempts'
    Line 8 - Edit '<NAME.txt>' password list
    
# Credits

Huge shoutout to [Riley Kidd](https://twitter.com/247CTF) for his expertise and great instruction. I can't recommend his courses enough for learning Python and it's uses for penetration testing.
