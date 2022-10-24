# Lookey here

#### Description
Attackers have hidden information in a very large mass of data in the past, maybe they are still doing it. Download the data [here](https://artifacts.picoctf.net/c/295/anthem.flag.txt).

## Hints
### 1
Download the file and search for the flag based on the known prefix.

## Solucion

```bash
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Forensics2022/lookeyhere]
└─$ cat anthem.flag.txt | grep picoCTF
      we think that the men of picoCTF{gr3p_15_@w3s0m3_58f5c024}
                                                                      
```

## Referencias