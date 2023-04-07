# TCP / IP Tools

## Ping

### Amazon

When www.amazon.com was pinged for 5 packets and:

  * The min/avg/max/stddev statistics for those were: 3.439/7.399/10.003/3.004 ms.
  * There was 0.0% packet loss.
  * The IP address of the website did not change between the pings.
  
### Google

When www.google.com was pinged for 5 packets and:

  * The min/avg/max/stddev statistics for those were: 3.003/7.902/9.300/2.453 ms.
  * There was 0.0% packet loss.
  * The IP address of the website did not change between the pings.
  
### Microsoft

When www.microsoft.com was pinged for 5 packets and:

  * The min/avg/max/stddev statistics for those were: 3.520/7.338/9.629/2.736 ms.
  * There was 0.0% packet loss.
  * The IP address of the website did not change between the pings.

## Traceroute

### Amazon

When the traceroute to www.amazon.com was looked up:

 * The target server's IP address was: 18.172.169.208 (Class A)
 * 64 hops were required to reach the target.
 * From the intermediate server DNS names, it is clear that my ISP is the University of Washington. (I did this from UW campus)
 * All the major steps in the traceroute whose IP address is known fall either under Class A or Class C. Jumps 1,3,4,5 & 12 fall under Class A, and Jumps 2,6 & 12 fall under Class C. Rest of the IP addresses are unknown.

### Google

When the traceroute to www.google.com was looked up:

 * The target server's IP address was: 142.251.33.100 (Class B)
 * 7 hops were required to reach the target.
 * From the intermediate server DNS names, it is not clear what my ISP is. However, after looking the name up, it is clear that the ISP is Wave Broadband.
 * The IP addresses of the major steps fall under all A, B, and C classes. Jumps 3 & 5 falls under Class A, Jumps 1,2 & 4 fall under Class B, and Jump 7 falls under Class C. Rest of the IP addresses are unknown.

### Microsoft

When the traceroute to www.microsoft.com was looked up:

 * The target server's IP address was: 23.216.81.152 (Class A)
 * 8 hops were required to reach the target.
 * From the intermediate server DNS names, it is not clear what my ISP is.
 * The IP addresses of the major steps fall under classes A and B. Jumps 4 & 8 falls under Class A, and Jumps 1 & 2 fall under Class B. Rest of the IP addresses are unknown.
