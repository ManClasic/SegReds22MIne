# Tab, Tab, Attack

#### Description
Using tabcomplete in the Terminal will add years to your life, esp. when dealing with long rambling directory structures and filenames: [Addadshashanammu.zip](https://mercury.picoctf.net/static/9689f2b453ad5daeb73ca7534e4d1521/Addadshashanammu.zip)

## Hints
### 1
After `unzip`ing, this problem can be solved with 11 button-presses...(mostly Tab)...

## Solucion
```bash
┌──(masterfer㉿PcMaster)-[~]
└─$ cd Downloads 
                                                                                   
┌──(masterfer㉿PcMaster)-[~/Downloads]
└─$ cd Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/Onnissiralis/Ularradallaku 
                                                                                   
┌──(masterfer㉿PcMaster)-[~/…/Assurnabitashpi/Maelkashishi/Onnissiralis/Ularradallaku]
└─$ ls
fang-of-haynekhtnamet
                                                                                   
┌──(masterfer㉿PcMaster)-[~/…/Assurnabitashpi/Maelkashishi/Onnissiralis/Ularradallaku]
└─$ file fang-of-haynekhtnamet 
fang-of-haynekhtnamet: ELF 64-bit LSB pie executable, x86-64, version 1 (SYSV), dynamically linked, interpreter /lib64/ld-linux-x86-64.so.2, for GNU/Linux 3.2.0, BuildID[sha1]=72a56ba85df661b5a985999a435927c01095cccf, not stripped
                                                                                   
┌──(masterfer㉿PcMaster)-[~/…/Assurnabitashpi/Maelkashishi/Onnissiralis/Ularradallaku]
└─$ ./fang-of-haynekhtnamet 
*ZAP!* picoCTF{l3v3l_up!_t4k3_4_r35t!_2bcfb2ab}

```

picoCTF{l3v3l_up!_t4k3_4_r35t!_2bcfb2ab}