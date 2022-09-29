# shark on wire 1

#### Description
We found this [packet capture](https://jupiter.challenges.picoctf.org/static/483e50268fe7e015c49caf51a69063d0/capture.pcap). Recover the flag.

## Hints
### 1
Try using a tool like Wireshark
### 2
What are streams?

## Solucion
Con WireShark de kali abrimos el archivo que descargamos del reto.
Seguimos un archivo UDP de stream hasta dar con la bandera.

```bash
picoCTF{StaT31355_636f6e6e}
```
