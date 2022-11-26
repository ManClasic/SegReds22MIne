# file-run1

#### Description
A program has been provided to you, what happens if you try to run it on the command line? Download the program [here](https://artifacts.picoctf.net/c/309/run).

## Hints
### 1
To run the program at all, you must make it executable (i.e. `$ chmod +x run`)

### 2
Try running it by adding a '.' in front of the path to the file (i.e. `$ ./run`)

## Solucion


```bash
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Reversing22/filerun1]
└─$ ls
run
                                                                                                                           
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Reversing22/filerun1]
└─$ ./run 
zsh: permission denied: ./run
                                                                                                                           
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Reversing22/filerun1]
└─$ chmod +x ./run

                                                                                                                           
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Reversing22/filerun1]
└─$ ./run         
The flag is: picoCTF{U51N6_Y0Ur_F1r57_F113_e5559d46} 

```


## Referencias