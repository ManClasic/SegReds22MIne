# PW Crack 2

#### Description
Can you crack the password to get the flag? Download the password checker [here](https://artifacts.picoctf.net/c/17/level2.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/17/level2.flag.txt.enc) in the same directory too.


## Hints
### 1
Does that encoding look familiar?

### 2
The `str_xor` function does not need to be reverse engineered for this challenge.

## Solucion
```bash
┌──(masterfer㉿PcMaster)-[~/Downloads]
└─$ nano level2.py   
                                                                                   
┌──(masterfer㉿PcMaster)-[~/Downloads]
└─$ python3          
Python 3.10.5 (main, Jun  8 2022, 09:26:22) [GCC 11.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> print("chr(0x34) + chr(0x65) + chr(0x63) + chr(0x39)")
chr(0x34) + chr(0x65) + chr(0x63) + chr(0x39)
>>> print(chr(0x34) + chr(0x65) + chr(0x63) + chr(0x39))
4ec9
>>> exit()
                                                                                   
┌──(masterfer㉿PcMaster)-[~/Downloads]
└─$ python3 level2.py 
Please enter correct password for flag: 4ec9
Welcome back... your flag, user:
picoCTF{tr45h_51ng1ng_9701e681}
                                 
```

picoCTF{tr45h_51ng1ng_9701e681}

Analizamos el codigo y vemos que la contrasenia esta en base diferente, por lo que salimos y usamos python desde la ocnsola para imprimir la contrasenia y asi poder obtener la bandera.
