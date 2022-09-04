# Retos Bandit  #10
# Level 9  -> 10

# Objetivo
The password for the next level is stored in the file **data.txt** in one of the few human-readable strings, preceded by several ‘=’ characters.

# Datos de acceso
ssh bandit9@**bandit.labs.overthewire.org** -p2220

user: bandit9
pass: UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR


## NUEVA CONTRASENIA
EN632PlfYiZbn3PhVK3XOGSlNInNE00t

# Solucion 
bandit9@bandit:~$ cat  data.txt  | strings | grep ==
========== the
bu========== password
4iu========== is
b~==P
========== G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s


# Notas adicionales
Apartir  de este reto fallo bandit y tuvimos que volver a sacar las contrasenias anteriores.
Aqui concatenamos el comando  cat para sacar las strings y aparte que contengan dobles =

# Referencias 