###nmap
```
sudo apt install nmap
```
扫描所有活动主机
```
nmap -sn 192.168.2.*
```

扫描22端口开放的主机
```
sudo nmap -sS -p22 --open 192.168.2.*
```