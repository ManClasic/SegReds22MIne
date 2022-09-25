# Fixme1.py

#### Description
Fix the syntax error in this Python script to print the flag. [Download Python script](https://artifacts.picoctf.net/c/38/fixme1.py)


## Hints
### 1
Indentation is very meaningful in Python

### 2
To view the file in the webshell, do: `$ nano fixme1.py`

### 3
To exit `nano`, press Ctrl and x and follow the on-screen prompts.

### 4
The `str_xor` function does not need to be reverse engineered for this challenge.

## Solucion
```bash
┌──(masterfer㉿PcMaster)-[~/Downloads]
└─$ nano fixme1.py   
                                                                                   
┌──(masterfer㉿PcMaster)-[~/Downloads]
└─$ python3 fixme1.py
That is correct! Here's your flag: picoCTF{1nd3nt1ty_cr1515_09ee727a}
                                                                       
```

picoCTF{1nd3nt1ty_cr1515_09ee727a}

en el ultimo print no debia llevar identacion.