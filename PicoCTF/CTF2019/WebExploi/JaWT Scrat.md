# JaWT Scratchpad

#### Description
Check the admin scratchpad! `https://jupiter.challenges.picoctf.org/problem/63090/` or http://jupiter.challenges.picoctf.org:63090

## Hints
### 1
What is that cookie?
### 2
Have you heard of JWT?

## Solucion
eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ1c2VyIjoiZmVyIn0.wufhGmDSJBd1ugYI4JLDndi6P-42nLnDZF-nTH47xWA


jwt encriptado con nuestro usuario lo desencriptamos con jhon y la lista de palabras de linux guardando la firma en un archivo, habiendo encontrado la palabra 
ilovepico
Modificamos el JWT con admin y la palabra ilovepico en la firma
Modificamos la cookie con la nueva palabra en la firma y refrescamos el sitio
el cual entrara con admin y nos entregara la bandera.



eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ1c2VyIjoiYWRtaW4ifQ.gtqDl4jVDvNbEe_JYEZTN19Vx6X9NNZtRVbKPBkhO-s



## Links 
https://jwt.io/

https://github.com/openwall/john