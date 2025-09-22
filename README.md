# Cybersecurity-Task1
# The Nmap command i used successfully scanned 256 hosts on the 192.168.1.0/24 network.
# Details Breakdown....
# 1command Info
Command: nmap -T4 -A 192.168.1.0/24
This command told Nmap to perform an aggressive scan(-A) with an aggressive timming template (-T4) on the entire 192.168.1.0/24 network ,which include all 256 possible IP address in that range.
# 2General Info
Hosts up:256: this mean Nmap found 256 active device on the network.This indicate that all IP address in the specified rangeresponded to Nmap,confirming they are in use.
Hosts down:0: No hosts were found.
Open ports:0: They are the key result.
Filtered ports:256000: This largest number is the most important clue.It indicate the top 1000 most common ports on all 256 hosts(256 hosts *1000ports=256000 filtered ports) were blocked by a firewall.
Closed ports:0: Nmap found zero ports it could definitively identify as closed.
# 3Scan Info
Scan type:syn: Nmap used a SYNscan, also known as a half-open scan,which is the default  and a  very commonmethod for stealthy port scanning.
Protocol:tcp:The scan was performed using thr TCP protocol.
Scanned:1000ports: this confirms that Nmap scanned the top 1000most common ports on each of the hosts.

