# Fixme2.py

#### Description
Fix the syntax error in the Python script to print the flag. [Download Python script](https://artifacts.picoctf.net/c/67/fixme2.py)


## Hints
### 1
Are equality and assignment the same symbol?

### 2
To view the file in the webshell, do: `$ nano fixme2.py`

### 3
To exit `nano`, press Ctrl and x and follow the on-screen prompts.

### 4
The `str_xor` function does not need to be reverse engineered for this challenge.

## Solucion
```bash
┌──(masterfer㉿PcMaster)-[~/Downloads]
└─$ python3 fixme2.py 
  File "/home/masterfer/Downloads/fixme2.py", line 22
    if flag = "":
       ^^^^^^^^^
SyntaxError: invalid syntax. Maybe you meant '==' or ':=' instead of '='?
                                                                                   
┌──(masterfer㉿PcMaster)-[~/Downloads]
└─$ nano fixme2.py   
                                                                                   
┌──(masterfer㉿PcMaster)-[~/Downloads]
└─$ python3 fixme2.py
That is correct! Here's your flag: picoCTF{3qu4l1ty_n0t_4551gnm3nt_f6a5aefc}
                                            
```

picoCTF{3qu4l1ty_n0t_4551gnm3nt_f6a5aefc}

Era un error de asignacion en vez de un solo = eran 2 == en el ultimo if