# LAB 2: Network commands for testing and trouble shooting

## OBJECTIVES

- To learn and understand various network commands used for testing and troubleshooting network connectivity.
- To study the working and output of basic network diagnostic commands in the Windows operating system.

---

## THEORY

### Requirement – Windows Operating System

Network commands are essential utilities used for testing, monitoring, and troubleshooting computer networks. These commands assist network administrators and users in identifying connectivity problems, IP configuration issues, routing errors, and communication failures. In the Windows Operating System, network commands are executed through the Command Prompt (CMD).

Some network commands are:

1. Ping  
2. tracert  
3. ipconfig  
4. nslookup  
5. netstat -a  
6. pathping  
7. route  
8. arp -a  
9. hostname  
10. getmac  
11. nbstat  

---

## 1. Ping

Ping is used to test the connectivity between the local computer and a remote host. It sends ICMP echo requests and measures the response time to check whether the destination is reachable.

**Syntax:**
```
ping <ip address domain>
```

---

## 2. Tracert

Tracert traces the route taken by data packets from the source to the destination. It helps identify network delays or failures at specific hops along the path.

**Syntax:**
```
tracert <domain_name>
```

---

## 3. ipconfig

Ipconfig displays the current IP configuration of the system, including IP address, subnet mask, and default gateway. It is useful for diagnosing network configuration issues.

**Syntax:**
```
ipconfig
```

---

## 4. nslookup

Nslookup is used to query DNS servers to obtain information about domain names and their corresponding IP addresses. It helps in troubleshooting DNS-related problems.

**Syntax:**
```
nslookup <domain_name>
```

---

## 5. netstat -a

Netstat -a shows all active TCP connections and listening ports on the computer. It is useful for monitoring network activity and detecting unauthorized connections.

**Syntax:**
```
netstat -a
```

---

## 6. pathping

Pathping combines the features of ping and tracert to analyze network performance. It provides detailed statistics about packet loss at each router along the path.

**Syntax:**
```
pathping <destination>
```

---

## 7. route

The route command displays and modifies the IP routing table. It helps control how network packets are forwarded to different destinations.

**Syntax:**
```
route print
```

---

## 8. arp -a

Arp -a displays the ARP table, which maps IP addresses to MAC addresses. It is useful for identifying devices connected to the local network.

**Syntax:**
```
arp -a
```

---

## 9. hostname

The hostname command displays the name of the current computer on the network. It helps identify the system within a local or domain network.

**Syntax:**
```
hostname
```

---

## 10. getmac

Getmac displays the MAC addresses of all network adapters on the system. It is helpful for network identification and troubleshooting.

**Syntax:**
```
getmac
```

---

## 11. nbstat

Nbtstat displays NetBIOS over TCP/IP statistics and name tables. It is used to diagnose NetBIOS name resolution problems on a network.

**Syntax:**
```
nbtstat -n
```

---

## Discussion

In this laboratory exercise, various network commands available in the Windows Operating System were studied and executed using the Command Prompt. Commands such as ping, tracert, ipconfig, and nslookup were used to test connectivity, analyze network paths, and verify IP and DNS configurations. Monitoring commands like netstat, arp, and getmac helped in observing active connections, IP-to-MAC mappings, and hardware addresses. Through this experiment, it was observed that each command serves a specific role in network troubleshooting. Some commands focus on connectivity testing, while others provide routing, name resolution, and interface information. The practical use of these commands improved understanding of how data flows through a network and how common network problems can be identified efficiently.

---

## Conclusion

In conclusion, Windows network commands were successfully studied and demonstrated using the Command Prompt.
