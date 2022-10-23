# WebNet0

#### Description
We found this [packet capture](https://jupiter.challenges.picoctf.org/static/0c84d3636dd088d9fe4efd5d0d869a06/capture.pcap) and [key](https://jupiter.challenges.picoctf.org/static/0c84d3636dd088d9fe4efd5d0d869a06/picopico.key). Recover the flag.

## Hints
### 1
Try using a tool like Wireshark.
### 2
How can you decrypt the TLS stream?

## Solucion
Descargamos  los  archivos y abrimos lacapturade paquetes con wireshark
Agregamos la llave al wireshark en preferencias, protocolos y ahi  guardamos lallave.
despues en busqyeda  o  cntrl F buscamos  packet details y en cadena buscamos la bandera picoCTF


Pico-Flag: picoCTF{nongshim.shrimp.crackers}


## Referencias 
