# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

## Output
```
Microsoft Windows [Version 10.0.26200.8246]
(c) Microsoft Corporation. All rights reserved.

C:\Users\Lekshmeendhra S>ipconfig

Windows IP Configuration


Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 9:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

C:\Users\Lekshmeendhra S>ip config
'ip' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\Lekshmeendhra S>ipconfig

Windows IP Configuration


Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 9:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

C:\Users\Lekshmeendhra S>ipconfig

Windows IP Configuration


Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 9:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 10:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . : saveetha.in
   IPv6 Address. . . . . . . . . . . : 2403:8600:c090:42:0:4fc:8b8b:be59
   Link-local IPv6 Address . . . . . : fe80::b570:7ec2:4c8d:d64f%8
   Autoconfiguration IPv4 Address. . : 169.254.196.9
   Subnet Mask . . . . . . . . . . . : 255.255.0.0
   Default Gateway . . . . . . . . . : fe80::eedd:24ff:fe3d:ced5%8

C:\Users\Lekshmeendhra S>hostname
Lekshmeendhra

C:\Users\Lekshmeendhra S>macaddress
'macaddress' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\Lekshmeendhra S>getmac

Physical Address    Transport Name
=================== ==========================================================
C8-53-09-34-82-44   Media disconnected
E4-1F-D5-AF-8D-4A   \Device\Tcpip_{56707A9D-9CD8-4A89-B486-68AC414DE872}

C:\Users\Lekshmeendhra S>google.com
'google.com' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\Lekshmeendhra S>ping google.com

Pinging google.com [2404:6800:4007:836::200e] with 32 bytes of data:
Reply from 2404:6800:4007:836::200e: time=54ms
Reply from 2404:6800:4007:836::200e: time=151ms
Reply from 2404:6800:4007:836::200e: time=580ms
Reply from 2404:6800:4007:836::200e: time=240ms

Ping statistics for 2404:6800:4007:836::200e:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 54ms, Maximum = 580ms, Average = 256ms

C:\Users\Lekshmeendhra S>tracert google.com

Tracing route to google.com [2404:6800:4007:836::200e]
over a maximum of 30 hops:

  1    16 ms    31 ms   106 ms  2403:8600:c090:42::1
  2     *        *        *     Request timed out.
  3     *        *        *     Request timed out.
  4    59 ms    36 ms   165 ms  lcmaaa-az-in-x0e.1e100.net [2404:6800:4007:836::200e]

Trace complete.

```
## Result
Thus Execution of Network commands Performed 
