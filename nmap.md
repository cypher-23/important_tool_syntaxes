nmap

running a quick scan : **sudo nmap &lt;ip&gt;**

```linux
sudo nmap <ip>
```

running a scan for only port enum: **sudo nmap -T4 -p- &lt;ip&gt;**

```linux
sudo nmap -T4 -p- <ip>
```

running a port scan with open ports : **sudo nmap -T4 -p p1,p2,...  &lt;ip&gt; {p1 p2 p3 being the open ports}**

```linux
sudo nmap -T4 -p <port_list> <ip>
```

running when there is no icmp ping : **sudo nmap -T4 -p- -A -Pn &lt;ip&gt;**

```linux
sudo nmap -T4 -p- -A -Pn <ip>
```