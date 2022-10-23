# b00tl3gRSA2

#### Description
In RSA d is a lot bigger than e, why don't we use d to encrypt instead of e? Connect with `nc jupiter.challenges.picoctf.org 19566`.
## Hints
### 1
What is e generally?


## Solucion
```bash

```


## Refrencia RSA
P - numero primo
Q - numero primo
N - modulo
tn - totient n
E - exponente (llave publica) - 65337
D - llave privada
C - mensaje cifrado
M - mensaje en texto plano

n = p * q
tn = (p-1) * (q-1)
d = e mod inv tn

Encriptar: pow(m,e,n)
c = m ^ e mod n

Desencriptar: pow(c,d,n)
m = c ^ d mod n