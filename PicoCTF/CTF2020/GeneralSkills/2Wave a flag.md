#  Wave a flag

#### Description
Can you invoke help flags for a tool or binary? [This program](https://mercury.picoctf.net/static/f95b1ee9f29d631d99073e34703a2826/warm) has extraordinarily helpful information...

## Hints
### 1
This program will only work in the webshell or another Linux computer.

## Solucion

```bash
──(masterfer㉿PcMaster)-[~]
└─$ wget https://mercury.picoctf.net/static/f95b1ee9f29d631d99073e34703a2826/warm
--2022-09-13 09:27:05--  https://mercury.picoctf.net/static/f95b1ee9f29d631d99073e34703a2826/warm
Resolving mercury.picoctf.net (mercury.picoctf.net)... 18.189.209.142
Connecting to mercury.picoctf.net (mercury.picoctf.net)|18.189.209.142|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 10936 (11K) [application/octet-stream]
Saving to: ‘warm’

warm                 100%[=====================>]  10.68K  --.-KB/s    in 0s      

2022-09-13 09:27:05 (173 MB/s) - ‘warm’ saved [10936/10936]

                                                                                   
┌──(masterfer㉿PcMaster)-[~]
└─$ chmod +x warm       
                                                                                   
┌──(masterfer㉿PcMaster)-[~]
└─$ ./warm -h
Oh, help? I actually don't do much, but I do have this flag here: picoCTF{b1scu1ts_4nd_gr4vy_f0668f62}
```