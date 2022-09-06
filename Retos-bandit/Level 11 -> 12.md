# Retos Bandit #12
# Level 11 -> 12

# Objetivo
The password for the next level is stored in the file **data.txt**, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions

# Datos de acceso
ssh bandit11@**bandit.labs.overthewire.org** -p2220

user: bandit11
pass: 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM

# Solucion 
```bash
bandit11@bandit:~$ ls
data.txt
bandit11@bandit:~$ cat data.txt 
Gur cnffjbeq vf WIAOOSFzMjXXBC0KoSKBbJ8puQm5lIEi
bandit11@bandit:~$ cat data.txt |  tr 'n-za-mN-ZA-M' 'a-zA-Z'
The password is JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv
```

# Notas adicionales
Utilizamos el metodo d e desencriptacion 13 veces sobre el string que contiene el archivo d ata.txt para dar conn el pass original.

# Referencias 