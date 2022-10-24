# Packets Primer

#### Description
Download the packet capture file and use packet analysis software to find the flag.

-   [Download packet capture](https://artifacts.picoctf.net/c/200/network-dump.flag.pcap)


## Hints
### 1
Wireshark, if you can install and use it, is probably the most beginner friendly packet analysis software product.

## Solucion

```bash
 ──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Forensics2022/packetsprimer]
└─$ ls                            
network-dump.flag.pcap
                                                                                                
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Forensics2022/packetsprimer]
└─$ strings network-dump.flag.pcap 
k&Nar
n#('
k&Na
k&Na`
n#('
k&Na;
n#('
p i c o C T F { p 4 c k 3 7 _ 5 h 4 r k _ b 9 d 5 3 7 6 5 }
k&Naa
ep&Na(
p&NaX
p&Na28
p&Na
        
```
picoCTF{p4ck37_5h4rk_b9d53765}


## Referencias