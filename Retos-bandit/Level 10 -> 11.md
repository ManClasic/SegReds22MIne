# Retos Bandit #11
# Level 10 -> 11

# Objetivo
The password for the next level is stored in the file **data.txt**, which contains base64 encoded data

# Datos de acceso
ssh bandit10@**bandit.labs.overthewire.org** -p2220

user: bandit10
pass: G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s

# Solucion 
bandit10@bandit:~$ ls
data.txt
bandit10@bandit:~$ cat data.txt 
VGhlIHBhc3N3b3JkIGlzIDZ6UGV6aUxkUjJSS05kTllGTmI2blZDS3pwaGxYSEJNCg==
bandit10@bandit:~$ cat data.txt | base64 --decode
The password is 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM


# Notas adicionales
Mostramos los archivos pero noos muestra una cadena muy  larga la cual esta en base 64 y tenemos que usar el comanndo  decode base 64 para sacar la contrasenia.

# Referencias 