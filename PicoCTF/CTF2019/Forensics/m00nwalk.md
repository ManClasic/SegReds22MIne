# m00nwalk

#### Description
Decode this [message](https://jupiter.challenges.picoctf.org/static/d6fcea5e3c6433680ea4f914e24fab61/message.wav) from the moon.

## Hints
### 1
How did pictures from the moon landing get sent back to Earth?

### 2
What is the CMU mascot?, that might help select a RX option

## Solucion
```bash
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Forensics2019/m00nwalk]
└─$ sstv -d message.wav -o salida.png
[sstv] Searching for calibration header... Found!    
[sstv] Detected SSTV mode Scottie 1
[sstv] Decoding image...   [##############################################################] 100%
[sstv] Drawing image data...
[sstv] ...Done!



picoCTF{beep_boop_im_in_space}
```


## Referencias

https://github.com/colaclanth/sstv
