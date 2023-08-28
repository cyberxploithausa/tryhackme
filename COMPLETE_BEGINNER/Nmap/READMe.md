# Complete Beginner

## Nmap

> Yazeed Ahmed | 2 March 2023

```````````````````````
ip = 

```````````````````````

## ATTACK Vector


####  TASKS

1. What networking constructs are used to direct traffic to the right application on a server? | ports

2. How many of these are available on any network-enabled computer? | 65535

3. [Research] How many of these are considered "well-known"? (These are the "standard" numbers mentioned in the task) | 1024

4. What is the first switch listed in the help menu for a 'Syn Scan' (more on this later!)? | -SS

5. Which switch would you use for a "UDP scan"? | -sU

6. If you wanted to detect which operating system the target is running on, which switch would you use? | -O

7. Nmap provides a switch to detect the version of the services running on the target. What is this switch? | -sV

8. The default output provided by nmap often does not provide enough information for a pentester. How would you increase the verbosity? | -v

9. Verbosity level one is good, but verbosity level two is better! How would you set the verbosity level to two?
(Note: it's highly advisable to always use at least this option) | -vv

10. We should always save the output of our scans -- this means that we only need to run the scan once (reducing network traffic and thus chance of detection), and gives us a reference to use when writing reports for clients.

What switch would you use to save the nmap results in three major formats? | -oA

11. What switch would you use to save the nmap results in a "normal" format? | -oN

12. A very useful output format: how would you save results in a "grepable" format? | -oG

13. Sometimes the results we're getting just aren't enough. If we don't care about how loud we are, we can enable "aggressive" mode. This is a shorthand switch that activates service detection, operating system detection, a traceroute and common script scanning.

How would you activate this setting? | -A

14. Nmap offers five levels of "timing" template. These are essentially used to increase the speed your scan runs at. Be careful though: higher speeds are noisier, and can incur errors!

How would you set the timing template to level 5? | -T5

15. We can also choose which port(s) to scan.

How would you tell nmap to only scan port 80? | -p 80

16. How would you tell nmap to scan ports 1000-1500? | -p1000-1500

17. A very useful option that should not be ignored:

How would you tell nmap to scan all ports? | -p-

18. How would you activate a script from the nmap scripting library (lots more on this later!)? | --scripts

19. How would you activate all of the scripts in the "vuln" category? | --script=vuln

20. Which RFC defines the appropriate behaviour for the TCP protocol? | RFC 793

21. If a port is closed, which flag should the server send back to indicate this? | RST

22.  There are two other names for a SYN scan, what are they? | half-open, stealth

23. Can Nmap use a SYN scan without Sudo permissions (Y/N)? | N

24.  If a UDP port doesn't respond to an Nmap scan, what will it be marked as? | open|filtered

25. When a UDP port is closed, by convention the target should send back a "port unreachable" message. Which protocol would it use to do so? | icmp

26.  Which of the three shown scan types uses the URG flag? | xmas

27. Why are NULL, FIN and Xmas scans generally used? | firewall evasion

28. Which common OS may respond to a NULL, FIN or Xmas scan with a RST for every port? | Microsoft Windows 

29.  How would you perform a ping sweep on the 172.16.x.x network (Netmask: 255.255.0.0) using Nmap? (CIDR notation) | nmap -sn 172.16.0.0/16

30.  What language are NSE scripts written in?| lua

31. Which category of scripts would be a very bad idea to run in a production environment? | intrusive

32. What optional argument can the ftp-anon.nse script take? | maxlist

33. What is the filename of the script which determines the underlying OS of the SMB server? | smb-os-discovery.nse

34. Read through this script. What does it depend on? | smb-brute

35.  Which simple (and frequently relied upon) protocol is often blocked, requiring the use of the -Pn switch? | icmp

36. [Research] Which Nmap switch allows you to append an arbitrary length of random data to the end of packets? | --data-length 

37 . Does the target (10.10.154.234)respond to ICMP (ping) requests (Y/N)? | n

38. Perform an Xmas scan on the first 999 ports of the target -- how many ports are shown to be open or filtered? | 999

39. There is a reason given for this -- what is it?

Note: The answer will be in your scan results. Think carefully about which switches to use -- and read the hint before asking for help! | no response


40. Deploy the ftp-anon script against the box. Can Nmap login successfully to the FTP server on port 21? (Y/N) | y

41. 
























