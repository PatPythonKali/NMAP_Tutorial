# Put in a variable the IP address
export IP=192.168.1.166


# 1. Check for LIVE systems
# NMAP the whole network
nmap -sP 192.168.1.0/24 -Oa 