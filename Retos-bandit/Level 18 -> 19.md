# Retos Bandit  #19
# Level 18 -> 19

# Objetivo
The password for the next level is stored in a file **readme** in the homedirectory. Unfortunately, someone has modified **.bashrc** to log you out when you log in with SSH.

# Datos de acceso
ssh bandit18@**bandit.labs.overthewire.org** -p2220

user: bandit18
pass: hga5tuuCLF6fFzUpnagiMN8ssu9LFrdg

# Solucion 
```bash
┌──(masterfer㉿PcMaster)-[~]
└─$ sshpass ssh nivel18 bandit18@bandit.labs.overthewire.org -p 2220 "/bin/bash"
                         _                     _ _ _   
                        | |__   __ _ _ __   __| (_) |_ 
                        | '_ \ / _` | '_ \ / _` | | __|
                        | |_) | (_| | | | | (_| | | |_ 
                        |_.__/ \__,_|_| |_|\__,_|_|\__|
                                                       

                      This is an OverTheWire game server. 
            More information on http://www.overthewire.org/wargames

cat readme
awhqfNnAbc1naukrpqDYcF95h7HoMTrC
```

# Notas adicionales
En este nivel no se puede accceder porque modificaron el archivo bash y nos saca del servidor.
Se intento desde el bandit0 pero nos marca error y acceso denegado.
Por lo que se opta por entrar desde fuera mediante el bash y asi poder leer la contrasenia sin que nos saque.

# Referencias 