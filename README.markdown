----------------------------------------------------
# Use for educational purposes ONLY

## This is a maintained fork of Torshammer  
It works with the new TOR port 9150  

#### TORS HAMMER HOW TO  
----------------------------------------------------
```console
git clone https://github.com/Aathithya-Shanmuga-Sundaram/torshammer.git
cd torshammer
```
You should now see a terminal-based GUI interface.
**Tor'shammer interface has it's own basic help menu that tells you how to run the script according to your target.**

Example usage:
```console
python torshammer.py -t 192.168.1.100 -r 100000 -T
python3 torshammer.py -t "www.example.com" -r 100000
```
- The larger the thread count, the more efficient and effective the attack!!
- -T adds the Tor function which provides security, as well, as providing a new identity in case the site is
programmed to ban IP addresses which leave an open connection for "x" amount of time. Tor'shammer's method of
combining this is clever and effective, making it the powerful tool it is. However, Tor'shammer is only effective to
apache servers which do not run nginx.


NOTE: I'm not the owner of this tool, i debugged and made this running on current version

Lastly Used in: 14/03/2025
