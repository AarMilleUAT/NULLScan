# NULLScan
In this command, the following options are used:

-sN: Specifies a NUL scan, which sets the TCP null flag on packets.
-p 1-65535: Specifies the range of ports to scan.
--reason: Shows the reason for the port state (open, closed, filtered, etc.).
--script=banner: Enables the script to display banners of services running on the target.
--traceroute: Enables traceroute to determine the network path to the target.
-oA: Specifies the output format as three different file types (normal, XML, and grepable) with the same base name.
scan_results: Specifies the base name for the output files.
target_ip_address: Specifies the IP address of the target to scan.
