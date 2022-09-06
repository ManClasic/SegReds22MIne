# Retos Bandit  #4
# Level 3 -> 4

# Objetivo
The password for the next level is stored in a hidden file in the **inhere** directory.

# Datos de acceso
ssh bandit3@**bandit.labs.overthewire.org** -p2220

user: bandit3
pass: UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

## NUEVA CONTRASENIA
aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG

# Solucion 
```bash
bandit3@bandit:~$ ls
inhere
bandit3@bandit:~$ cd inhere/
bandit3@bandit:~/inhere$ ls
bandit3@bandit:~/inhere$ ls -a
.  ..  .hidden
bandit3@bandit:~/inhere$ cat ./.hidden
pIwrPrtPN36QITSp3EQaw936yaFoFgAB
```


## NUEVA CONTRASENIA
2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe


# Notas adicionales

El comando ls la opcion -a muestra todos los archivos incluso los ocultos.

# Referencias 
https://man7.org/linux/man-pages/man1/ls.1.html