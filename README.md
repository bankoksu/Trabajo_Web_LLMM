## Trabajo Web LLMM
### Documento requisitos funcionales.

 - inicio.
	Ten�amos en mente 3 posibles p�ginas(de un videojuegos, de las criptomonedas o una p�gina de chistes ). Nos centramos en que pod�amos hacer y en cual nos dar�a mas juego a la hora de aplicar **CSS y JS** . Fuimos probando por separado que pod�amos hacer y cual no daba **mas libertad** a la hora de armarla, as� que nos quedamos con la de videojuegos. Ten�amos muchas ideas, el problema viene cuando los armas y no hacen lo que tenias pensado. La base era  una pagina inicial donde estuviesen las noticias, una gu�a, gameplays(v�deos de gente jugando), un sorteo y un registro. Todo esto pensado para poder dar uso a lo aprendido de **CSS y JS** .
	Al principio fue probar que pod�amos hacer y como lo llevar�amos a cabo, nuestras investigaciones nos llevaron a muchos lados usando frameworks para poder hacerlas y a las limitadas herramientas que ten�amos se buscaron otras v�as. La p�gina principal se hizo el contenido para luego buscar que efecto agregarle, se descarto la pagina de sorteo y se agrego una de mapa. La pagina de noticias da uso de JS para mostrar mas o menos noticias, la de registro es mas compleja usando estado, comprobaci�n de los inputs y usando **CSS y JS** para conseguir cambios en el momento de su uso, el mapa presenta un JS que usa una lupa para ver mejor la imagen y la gu�a presenta equipaciones con un efecto para ver caracter�sticas a su lado pasando el mouse por encima de la imagen. Agregamos y quitamos cosas sobre la marcha(mientras la terminamos)determinado por el factor si funcionaba o no algunas cosas estabas bien en efecto pero no ven�an al conjunto de la p�gina. 

##  diagrama


```mermaid
graph LR
A[requisitos funcionales] --> B(pagina mapas)
A --> C(p�gina guia)
A --> E(p�gina inicio)
A --> F(noticias)
A --> G(galer�a)
A --> H(p�gina registro)
B --> D{validador W3C}
C --> D
E --> D
F --> D
G --> D
H --> D
D --> I(creaci�n pagina)
Z(todas las p�ginas)--> Y(fase TDD)
Y --> X(correrca implementaci�n)
Y -- si no funciona fase inicial--> Z
```


	

 - Final
	 se descartaron algunas p�ginas por su mal funcionamiento y no poder repararla para que quedaran bien. aunque gracias a Adrian que me ayudo a mejorar las cosas que hacia pudimos entregar algo que funciona y combina con la p�gina. el trabajo nos ayudo a ver como funcionan muchas cosas y tambi�n darnos cuenta cuanto nos falta por aprender. al final fueron 4 paginas acabadas.

**integrantes:**
**Adrian Carmona Belmonte**
**Alex Olmos Ceron**