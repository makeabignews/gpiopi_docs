首先进行扫描
```
sudo hcitool lescan
```

```
sdptool browse 8C:BE:BE:C5:2C:C7
```

ls

```
obexftp -b 8C:BE:BE:C5:2C:C7 -c / -l
```

download

```
obexftp -b 8C:BE:BE:C5:2C:C7 -c /Android -g djaof.dll
```

upload

```
obexftp -b 8C:BE:BE:C5:2C:C7 -c /Android -p hello.txt
```

成为一个iBeacon基站
```
hciconfig hci0 up
hciconfig hci0 leadv 3
hciconfig hci0 noscan
hcitool -i hci0 cmd 0x08 0x0008 1E 02 01 1A 1A FF 4C 00 02 15 63 6F 3F 8F 64 91 4B EE 95 F7 D8 CC 64 A8 63 B5 00 00 00 00 C8
```


读取蓝牙温度计
```bash
sudo gatttool -b C6:05:04:03:F1:BF --char-read -a 0x001b
```