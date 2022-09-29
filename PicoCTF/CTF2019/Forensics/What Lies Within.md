# What Lies Within

#### Description
There's something in the [building](https://jupiter.challenges.picoctf.org/static/011955b303f293d60c8116e6a4c5c84f/buildings.png). Can you retrieve the flag?

## Hints
### 1
There is data encoded somewhere... there might be an online decoder.

## Solucion
Con el decodificador inline abrimos la imagen
O
Con la herramienta zsteg de kali
```bash
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Forensics2019/whatLiesWithin]
└─$ zsteg -a buildings.png | grep picoCTF
b1,rgb,lsb,xy       .. text: "picoCTF{h1d1ng_1n_th3_b1t5}"


```

## Referencias 
https://stylesuxx.github.io/steganography/