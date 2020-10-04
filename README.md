# ipkg

Deny all but allow only KG zone

Working in Ubuntu 16.04

How to use it:

sudo apt install iptables-persistent

git clone https://github.com/constantinekg/ipkg && cd ipkg && chmod +x ipkg.py

sudo -s

crontab -e

add line at the end:

15 4 * * * cd ~ & /etc/ipkg

So every day at 4:15 am your iptables rules will update.
