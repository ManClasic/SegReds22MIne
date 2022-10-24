# Tapping

#### Description
Theres tapping coming in from the wires. What's it saying `nc jupiter.challenges.picoctf.org 21610`.

## Hints
### 1
What kind of encoding uses dashes and dots?
### 2
The flag is in the format PICOCTF{}

## Solucion


```bash
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Crypto]
└─$ nc jupiter.challenges.picoctf.org 21610 
.--. .. -.-. --- -.-. - ..-. { -- ----- .-. ... ...-- -.-. ----- -.. ...-- .---- ... ..-. ..- -. ...-- ----. ----- ..--- ----- .---- ----. ..... .---- ----. } 


PICOCTFM0RS3C0D31SFUN3902019519
```

PICOCTF{M0RS3C0D31SFUN3902019519}

## Referencias
https://gchq.github.io/CyberChef/