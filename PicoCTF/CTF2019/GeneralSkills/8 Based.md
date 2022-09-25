# Based

#### Description
To get truly 1337, you must understand different data encodings, such as hexadecimal or binary. Can you get the flag from this program to prove you are on the way to becoming 1337? Connect with `nc jupiter.challenges.picoctf.org 29221`.


## Hints
### 1
I hear python can convert things.
### 2
It might help to have multiple windows open.

## Solucion
```bash
┌──(masterfer㉿PcMaster)-[~]
└─$ nc jupiter.challenges.picoctf.org 29221
Let us see how data is stored
pear
Please give the 01110000 01100101 01100001 01110010 as a word.
...
you have 45 seconds.....

Input:
pear
Please give me the  154 141 155 160 as a word.
Input:
lamp
Please give me the 6c696d65 as a word.
Input:
lime
You've beaten the challenge
Flag: picoCTF{learning_about_converting_values_00a975ff}

```

picoCTF{learning_about_converting_values_00a975ff}

## Referencias

https://www.rapidtables.com/convert/number/binary-to-ascii.html
https://www.rapidtables.com/convert/number/hex-to-ascii.html
http://www.unit-conversion.info/texttools/octal/