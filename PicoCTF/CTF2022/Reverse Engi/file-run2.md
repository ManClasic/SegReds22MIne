# file-run2

#### Description
Another program, but this time, it seems to want some input. What happens if you try to run it on the command line with input "Hello!"? Download the program [here](https://artifacts.picoctf.net/c/352/run).

## Hints
### 1
Try running it and add the phrase "Hello!" with a space in front (i.e. "./run Hello!")

## Solucion
```bash
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Reversing22/filerun2]
└─$ ls   
run
                                                                                                                           
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Reversing22/filerun2]
└─$ ./run
zsh: permission denied: ./run
                                                                                                                           
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Reversing22/filerun2]
└─$ chmod +x ./run                              
                                                                                                                           
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Reversing22/filerun2]
└─$ ./run         
Run this file with only one argument.
                                                                                                                           
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Reversing22/filerun2]
└─$ ./run Hello!
The flag is: picoCTF{F1r57_4rgum3n7_96f2195f}  

```


## Referencias