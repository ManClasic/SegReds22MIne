# Retos Bandit  #15
# Level 14 -> 15

# Objetivo
The password for the next level can be retrieved by submitting the password of the current level to **port 30000 on localhost**.

# Datos de acceso
ssh bandit14@**bandit.labs.overthewire.org** -p2220

user: bandit14
pass: fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq

# Solucion 
bandit14@bandit:~$ nc localhost 30000
fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq
Correct!
jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt


bandit14@bandit:~$ 


# Notas adicionales
Para este problema podemos  utilizar dos opciones el comando telnet o el comando netcats, con el cual solucionamos  este nivel. Poniendo la contrasenia del nivel y el puerto nos arrojaria la siguiente..

# Referencias 