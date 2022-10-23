# MacroHard WeakEdge

#### Description
I've hidden a flag in this file. Can you find it? [Forensics is fun.pptm](https://mercury.picoctf.net/static/2e739f9e0dc9f4c1556ea6b033c3ec8e/Forensics is fun.pptm)

## Hints
### (None)
## Solucion

```bash
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Forensics2021/macrohardweakedge]
└─$ unzip Forensics\ is\ fun.pptm 

┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Forensics2021/macrohardweakedge]
└─$ ls     
'[Content_Types].xml'   docProps  'Forensics is fun.pptm'   ppt   _rels
                                                                                                
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Forensics2021/macrohardweakedge]
└─$ cat ppt/slideMasters/hidden 
Z m x h Z z o g c G l j b 0 N U R n t E M W R f d V 9 r b j B 3 X 3 B w d H N f c l 9 6 M X A 1 f Q  
```

 picoCTF{D1d_u_kn0w_ppts_r_z1p5}
## Referencias