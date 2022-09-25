# Where are the robots

#### Description
Can you find the robots? `https://jupiter.challenges.picoctf.org/problem/36474/` ([link](https://jupiter.challenges.picoctf.org/problem/36474/)) or http://jupiter.challenges.picoctf.org:36474

## Hints
### 1
What part of the website could tell you where the creator doesn't want you to look?

## Solucion

Agregamos a la ruta de la pagina robots.txt la ccual nos llevara aqui 

```
User-agent: *
Disallow: /477ce.html
```

Entonces regresamos a la ppagina principal y en vez de agregar robots.txt, agregaremos al final 477ce.html
Entonces tendremos la bandera.
```
  <div class="content">
	<p>Guess you found the robots<br />
	  <flag>picoCTF{ca1cu1at1ng_Mach1n3s_477ce}</flag></p>
      </div>
      <footer></footer>
  </body>
</html>
```

