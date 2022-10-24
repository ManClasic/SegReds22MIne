# information

#### Description
Files can always be changed in a secret way. Can you find the flag? [cat.jpg](https://mercury.picoctf.net/static/e5825f58ef798fdd1af3f6013592a971/cat.jpg)

## Hints
### 1
Look at the details of the file
### 2
Make sure to submit the flag as picoCTF{XXXXX}

## Solucion

W5M0MpCehiHzreSzNTczkc9d

cGljb0NURnt0aGVfbTN0YWRhdGFfMXNfbW9kaWZpZWR9
```bash
(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Forensics2021/information]
└─$ hexeditor cat.jpg          
                                                                                                
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Forensics2021/information]
└─$ echo W5M0MpCehiHzreSzNTczkc9d | base4 -d
Command 'base4' not found, did you mean:
  command 'basez' from deb basez
  command 'basex' from deb basex
  command 'base64' from deb coreutils
Try: sudo apt install <deb name>
                                                                                                
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Forensics2021/information]
└─$ echo W5M0MpCehiHzreSzNTczkc9d | base64 -d
[�42���!����573��]                                                                                                
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Forensics2021/information]
└─$ echo cGljb0NURnt0aGVfbTN0YWRhdGFfMXNfbW9kaWZpZWR9 | base64 -d
picoCTF{the_m3tadata_1s_modified}  
```

picoCTF{the_m3tadata_1s_modified}  

## Referencias