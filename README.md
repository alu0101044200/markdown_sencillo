# Markdown


![](http://i.imgur.com/IMTN5cy.png)  

*******
Tutorial creado por [Juan Cuenca](https://github.com/juanqenk)
*******
 

## Qué es markdown  
Según la definición de su creador, John Gruber:  
 

  >*Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML).*   


Podemos decir que es un archivo cuya sintaxis dota al texto de formato de una forma sencilla sencilla y rápida. Funciona bien en:

- Github
- Gmail
- Inbox By Google
- Thunderbird
- Google Groups
- Evernote
- Blogger
- Google Sites
- Outlook/Hotmail
- Yahoo email
- Wordpress
- Freshdesk
- Fastmail
- ProtonMail 
- ...

## Índice
1.- [Encabezados](#header)  
2.- [Énfasis](#emphasis)  
3.- [Listas](#lists)  
4.- [Links](#links)  
5.- [Imágenes](#images)  
6.- [Código](#code)  
7.- [Tablas](#tables)  
8.- [Citas](#blockquotes)  
9.- [Lineas horizontales](#lines)  
10.- [Emojis](#emojis)  
11.- [Tareas](#task)  
12.-[Creación de índices](#index)

<a name="header"/>
## Encabezados
Para crear encabezados simplemente se ha de preceder el título un número de almohadillas según el nivel de título de que se trate.  	

```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

# H1
## H2
### H3
#### H4
##### H5
###### H6

<a name="emphasis"/>

## Énfasis
Podemos añadir énfasis al texto con el uso de las negritas, cursivas o el tachado. 
```
*cursiva con asteriscos* o _cursiva con guiones_.

 **negrita con asteriscos** o __negrita con guiones__.

**negrita y _cursiva_**.

~~Tachado~~
```

*cursiva con asteriscos* o _cursiva con guiones_.

 **negrita con asteriscos**  o __negrita con guiones__.

**negrita y _cursiva_**.

~~Tachado~~


<a name="lists"/>

## Listas

Podemos crear tanto listas ordenadas como listas sin orden. Para ello disponemos de diferentes métodos. 

```no-highlight
1. Primer item
2. Segundo item
	* Subelemento
1. No importa el número
	1. Subelemento ordenado
4. Otro item.
```
1. Primer item
2. Segundo item
	* Subelemento
1. No importa el número
	1. Subelemento ordenado
4. Otro item.  

Para las listas sin orden se pueden usar asteriscos, signo menos o signo mas. 

```
* asteriscos
- signo menos
+ signo mas
```

* asteriscos
- signo menos
+ signo mas

<a name="links"/>

## Enlaces

Tenemos varias formas para añadir enlaces. 

```no-highlight
[Enlace sin título](https://www.google.com)

[Enlace con título](https://www.google.com "Google's Homepage")

[Enlace como referencia][Texto arbitrario de referencia]

[Referencia relativa a un archivo](./documento.txt)

[Referencia como artículo científico][1]

[Referencia simple]


[Texto arbitrario de referencia]: https://github.com/
[1]: https://es.python.org/
[Referencia simple]: http://www.reddit.com
```

[Enlace sin título](https://www.google.com)

[Enlace con título](https://www.google.com "Google's Homepage")

[Enlace como referencia][Texto arbitrario de referencia]

[Referencia relativa a un archivo](./documento.txt)

[Referencia como artículo científico][1]

[Referencia simple]


[Texto arbitrario de referencia]: https://github.com/
[1]: https://es.python.org/
[Referencia simple]: http://www.reddit.com

<a name="images"/>

## Imágenes

Las imágenes se añaden, como los enlaces, de manera directa o como referencia. 

```no-highlight

![imagen directa](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png "Pop")


![imagen referencia][logo]

[logo]: https://www.python.org/static/community_logos/python-logo-master-v3-TM.png "Pop en referencia"
```


![imagen directa](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png "directo")


![imagen referencia][logo]

[logo]: https://assets-cdn.github.com/images/modules/logos_page/GitHub-Mark.png "referencia"

<a name="code"/>

## Código

Los bloques de código forman parte de Markdown, pero el resaltado de sintaxis no. Sin embargo, muchos renderizadores, como Github, admiten el resaltado de numerosos lenguajes de programación. 

```no-highlight
	```
	Así se añade un bloque de código
	```
```

```
Así se añade un bloque de código
```
Si queremos que se muestre el resaltado de la sintaxis debemos añadir el nombre del lenguaje de programación.
 
	```python
	s = "Python syntax highlighting"
	print(s)
	```
```python
s = "Python syntax highlighting"
print(s)
```

<a name="tables"/>

## Tablas

Las tablas tampoco forman parte de Markdown, pero variantes y algunos servicios nos permiten visualizarlas correctamente. 

```no-highlight

| Las        | Tablas           | Molan |
| ------------- |:-------------:| -----:|
| col 3 esta      | alineada a dcha | $1600 |
| col 2 esta      | centrada     |   $12 |
| col 1 | alinea a izq      |    $1 |
```
| Las            | Tablas       | Molan |
| ------------- |:-------------:| --------:|
| col 3 esta  | alineada a dcha | $1600 |
| col 2 esta  | centrada     |   $12 |
| col 1          | alinea a izq |    $1 |


<a name="blockquotes"/>

## Citas

```no-highlight
> Se pueden añadir citas 
> con más **Markdown** dentro. 
 
```

> Se pueden añadir citas 
> con más **Markdown** dentro. 

<a name="lines"/>

## Lineas horizontales

Se pueden añadir al poner tres o más de los siguientes elementos: 

```

---

***
___

```
---

***
___


<a name="emojis"/>

## Emojis
No son propios de Markdown pero algunos servicios, como github, los permiten mostrar. 
```
 :laughing: :kissing_heart: :innocent: :green_heart:   
 ( consulta algunos emojis en este [link](http://www.emoji-cheat-sheet.com/) )
```
 :laughing: :kissing_heart: :innocent: :green_heart:   
 ( consulta algunos emojis en este [link](http://www.emoji-cheat-sheet.com/) )
 
 <a name="task"/>
 
## Tareas
```
- [ ] una tarea
	- [ ] una subtarea
- [x] tarea finalizada

```
- [ ] una tarea
	- [ ] una subtarea
- [x] tarea finalizada

<a name="index"/>
## Creación de índices

Esta [plantilla](./indice.md) para la creación de índices en Markdown puede ser de utilidad. 

