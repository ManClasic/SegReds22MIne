# Retos Bandit  #8
# Level 7 ->8

# Objetivo
The password for the next level is stored in the file **data.txt** next to the word **millionth**

# Datos de acceso
ssh bandit7@**bandit.labs.overthewire.org** -p2220

user: bandit7
pass: HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs

## NUEVA CONTRASENIA
z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S

# Solucion 
bandit7@bandit:~$ cat data.txt | grep millionth
millionth       cvX2JJa4CFALtqS87jk27qwqGhBM9plV

## NUEVA CONTRASENIA
TESKZC0XvTetK0S9xNwm25STk5iWrBvP

# Notas adicionales
Utilizando el | simbolo y grep mas la palabra que queremos buscar que en este caso fue millionth


# Referencias 