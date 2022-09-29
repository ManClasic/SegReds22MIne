# extensions

#### Description
This is a really weird text file [TXT](https://jupiter.challenges.picoctf.org/static/e7e5d188621ee705ceeb0452525412ef/flag.txt)? Can you find the flag?

## Hints
### 1
How do operating systems know what kind of file it is? (It's not just the ending!

## Solucion
```bash
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Forensics2019/extensions]
└─$ mv flag.txt flag.png
                                                                                                
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Forensics2019/extensions]
└─$ file flag.png  
flag.png: PNG image data, 1697 x 608, 8-bit/color RGB, non-interlaced
                                                                                                
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Forensics2019/extensions]
└─$ open flag.png 


picoCTF{now_you_know_about_extensions}

```


## Referencias

https://en.wikipedia.org/wiki/List_of_file_signatures