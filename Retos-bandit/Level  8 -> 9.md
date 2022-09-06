# Retos Bandit   #9
# Level 8 -> 9

# Objetivo
The password for the next level is stored in the file **data.txt** and is the only line of text that occurs only once

# Datos de acceso
ssh bandit8@**bandit.labs.overthewire.org** -p2220

user: bandit8
pass: cvX2JJa4CFALtqS87jk27qwqGhBM9plV

## NUEVA CONTRASENIA
TESKZC0XvTetK0S9xNwm25STk5iWrBvP

# Solucion 
```bash
bandit8@bandit:~$ cat data.txt | sort | uniq -u
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
```


## NUEVA CONTRASENIA
EN632PlfYiZbn3PhVK3XOGSlNInNE00t


# Notas adicionales
Utilizamos las opciones de cat que es sort para oSrdenar los datos y uniq para que nos arroje el valor unicop que tiene de datos con el pipe |


# Referencias 