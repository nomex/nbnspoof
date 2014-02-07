This tool was created in 2007 by Robert Wesley McGrew.

I've made a few changes to add support to targeted spoofing.

Usage
nbnspoof.py [-v] -i <interface> -n <regexp> -h <ip address> -m <MAC> [-p <ip address>]

-v Verbose output of sniffed NBNS name queries, and responses sent
-i The interface you want to sniff and send on
-n A regular expression applied to each query to determine whether a
   spoofed response will be sent
-h The IP address that will be sent in spoofed responses
-p (optional) The IP address of the victim (if unset, pwn all)
-m The source MAC address for spoofed responses
