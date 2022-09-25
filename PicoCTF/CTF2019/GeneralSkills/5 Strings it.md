# Strings it

#### Description
Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/5bd86036f013ac3b9c958499adf3e2e2/strings) without running it?


## Hints
### 1
[strings](https://linux.die.net/man/1/strings)

## Solucion
```bash
┌──(masterfer㉿PcMaster)-[~]
└─$ cd Downloads   
                                                                                   
┌──(masterfer㉿PcMaster)-[~/Downloads]
└─$ ls
obsidian_0.15.9_amd64.snap  strings
                                                                                   
┌──(masterfer㉿PcMaster)-[~/Downloads]
└─$ strings strings | grep picoCTF
picoCTF{5tRIng5_1T_827aee91}

```

picoCTF{5tRIng5_1T_827aee91}

## Referencias 
https://linux.die.net/man/1/strings
