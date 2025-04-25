This network sniffer captures packets passing through your network interface and breaks them down into their components, providing information about:

Ethernet frames (source/destination MAC addresses)
IPv4 packets (IP addresses, TTL, protocol)
TCP segments (ports, sequence numbers, flags)
UDP packets (ports, length)
ICMP packets (type, code)
HTTP data when detected

How to Use the Sniffer

Save the code to a file named network_sniffer.py
Run it with administrator/root privileges (required for raw socket access):

# On Linux/Mac:
sudo python3 network_sniffer.py [interface_name]

# On Windows (in Administrator PowerShell/CMD):
python network_sniffer.py [interface_name]
The interface name is optional - if not provided, the default interface will be used.