# First Grep

#### Description
Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/495d43ee4a2b9f345a4307d053b4d88d/file)? This would be really tedious to look through manually, something tells me there is a better way.


## Hints
### 1
grep [tutorial](https://ryanstutorials.net/linuxtutorial/grep.php)

## Solucion
```bash
┌──(masterfer㉿PcMaster)-[~]
└─$ cd Downloads                  
                                                                                   
┌──(masterfer㉿PcMaster)-[~/Downloads]
└─$ ls                            
file  obsidian_0.15.9_amd64.snap  strings
                                                                                   
┌──(masterfer㉿PcMaster)-[~/Downloads]
└─$ grep "picoCTF" file             
picoCTF{grep_is_good_to_find_things_dba08a45}
  
```

picoCTF{grep_is_good_to_find_things_dba08a45}
