# PW Crack 1

#### Description
Can you crack the password to get the flag? Download the password checker [here](https://artifacts.picoctf.net/c/51/level1.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/51/level1.flag.txt.enc) in the same directory too.


## Hints
### 1
To view the file in the webshell, do: `$ nano level1.py`

### 2
To exit `nano`, press Ctrl and x and follow the on-screen prompts.

### 3
The `str_xor` function does not need to be reverse engineered for this challenge.


## Solucion
```bash
┌──(masterfer㉿PcMaster)-[~/Downloads]
└─$ nano level1.py 
                                                                                   
┌──(masterfer㉿PcMaster)-[~/Downloads]
└─$ python3 level1.py 
Please enter correct password for flag: 1
That password is incorrect
                                                                                   
┌──(masterfer㉿PcMaster)-[~/Downloads]
└─$ nano level1.py   
                                                                                   
┌──(masterfer㉿PcMaster)-[~/Downloads]
└─$ python3 level1.py
Please enter correct password for flag: 691d
Welcome back... your flag, user:
picoCTF{545h_r1ng1ng_56891419}
                                  
```

picoCTF{545h_r1ng1ng_56891419}

Analizamos el codigo de python y vemos que la contrasenia es 691d al introduzirla nos arrojara la bandera correcta.