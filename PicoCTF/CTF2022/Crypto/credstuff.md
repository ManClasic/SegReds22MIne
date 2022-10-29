# credstuff

#### Description
We found a leak of a blackmarket website's login credentials. Can you find the password of the user `cultiris` and successfully decrypt it? Download the leak [here](https://artifacts.picoctf.net/c/534/leak.tar). The first user in `usernames.txt` corresponds to the first password in `passwords.txt`. The second user corresponds to the second password, and so on.

## Hints
### 1
Maybe other passwords will have hints about the leak?


## Solucion

```bash
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Crypto/credstuff]
└─$ tar -xvf leak.tar 
leak/
leak/passwords.txt
leak/usernames.txt

┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Crypto/credstuff]
└─$ ls
leak  leak.tar
┌──(masterfer㉿PcMaster)-[~/…/PicoCTF/Crypto/credstuff/leak]
└─$ ls
passwords.txt  usernames.txt

┌──(masterfer㉿PcMaster)-[~/…/PicoCTF/Crypto/credstuff/leak]
└─$ vim usernames.txt
:/`cultiris` linea 378

┌──(masterfer㉿PcMaster)-[~/…/PicoCTF/Crypto/credstuff/leak]
└─$ cat passwords.txt | head -n 378 | tail -n 1
cvpbPGS{P7e1S_54I35_71Z3}


┌──(masterfer㉿PcMaster)-[~/…/PicoCTF/Crypto/credstuff/leak]
└─$ echo ‘cvpbPGS{P7e1S_54I35_71Z3}’ | tr 'A-Za-z' 'N-ZA-Mn-za-m'
‘picoCTF{C7r1F_54V35_71M3}’


```


## Referencias
