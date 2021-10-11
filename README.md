[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=5793147&assignment_repo_type=AssignmentRepo)

# Guía de Markdown
## Desarrollo y mantenimiento de sistemas informáticos
#### Antonella Sofia Garcia Alvarez
#### alu0101227610@ull.edu.es

### Formatear texto

* Poner el **texto en negrita**

Para lograr este efecto, lo que tenemos que hacer es poner:

~~~
**texto en negrita**
~~~

* Poner el _texto en cursiva_

Muchas veces para dar enfasis, formatemos el texto a cursiva. Para ello tenemos que escribir:

~~~
_texto en cursiva_
~~~

y si además queremos juntar texto en negrita con el texto en cursiva lo que tenemos que hacer es:

~~~
**_ Texto en negrita y cursiva _**
~~~

### Cabeceras

Para los títulos, normalmente queremos dar más enfasis al texto. Para ello existen un total de 6 tamaños disponibles. Para utilizarnos necesitamos hacer lo siguiente:

~~~
# Cabecera 1
## Caberecera 2
### Cabercera 3
~~~

Esto nos dará como resultado:

# Cabecera 1
## Cabecera 2
### Cabecera 3

Si seguimos añadiendo hashtags, seguirá cambiando el tamaño.

### Enlaces

Para tener un trabajo limpio también es util que formateemos los enlaces para que tengan un color diferente e incluso para tan solo al darle a una palabra nos redirija al enlance.

Existen dos tipos de enlaces, tenemos el enlace en línea que escribiríamos asi:

~~~
[enlace](www.github.com)
~~~

Estos nos muestra:

[enlace](www.github.com)

Después también tenemos los enlaces referenciales que se escriben de la siguiente manera:

~~~
[github1][enlace-github]
[github2][enlace-github]

[enlace-github]:www.github.com
~~~

Esto da como resultado:

[github1][enlace-github]
[github2][enlace-github]

[enlace-github]:www.github.com

### Imágenes

Las imagenes funcionan parecido a los enlaces, escribiendo que vamos a implementar una imagen al lado del enlace nos imprimirá la imagen en texto:
~~~
![imagen1](https://www.dexerto.es/wp-content/uploads/sites/3/2021/04/23/guia-morgana-jungla-temporada-11-league-of-legends-portada.jpg)
~~~
Se transforma en:
![imagen1](https://www.dexerto.es/wp-content/uploads/sites/3/2021/04/23/guia-morgana-jungla-temporada-11-league-of-legends-portada.jpg)

También podemos implementar imagenes con el mismo funcionamiento de los enlaces referenciales:
~~~
![Imagen2][Enlace imagen2]
[Enlace imagen2]: https://esports.as.com/2019/04/10/league-of-legends/reduccion-escalados-habilidad-afectaran-Morgana_1234986498_196345_1440x810.jpg
~~~
Que muestra lo siguiente:
![Imagen2][Enlace imagen2]

[Enlace imagen2]: https://esports.as.com/2019/04/10/league-of-legends/reduccion-escalados-habilidad-afectaran-Morgana_1234986498_196345_1440x810.jpg

### Listas

También puede ser interesante saber como formatear listas, tanto ordenadas como no ordenadas:

Para las listas no ordenadas:
~~~
* Lista1
    * Lista2
    Listado no ordenado
* Lista 3
~~~
* Lista1
    * Lista2
    Listado no ordenado
* Lista 3

Y las listas ordenadas, como vimos en clase, las hacemos así:

~~~
1. Manzanas
2. Peras
3. Uvas
~~~

1. Manzanas
2. Peras
3. Uvas