# Actividad 1.1 - Lenguaje Markdown.

###### **_Luis Orlando Negrin Delgado_**.

# Ejemplo 1: Encabezados

# Encabezado 1.
## Encabezado 2.
### Encabezado 3.
#### Encabezado 4.

**_Para crear un encabezado tendremos que poner entre 1 y 6 almohadillas mas un espacio seguido de la palabra_**.

# Ejemplo 2: Emphasis

- **_El primer ejemplo se realiza añadiendo una _ al principio y al final._**
- Ejemplo: _buenas_.
- **_Para el segundo ejemplo, añadiremos dos asteriscos al principio y al final de la palabra_**
- Ejemplo: **Hola**.
- **_En el tercer ejemplo mostraremos una combinacion de los primeros ejemplos_**
- Ejemplo: **_Muy buenas_**.
- **_Por ultimo veremos el formato subrayado_**
- Ejemplo: ~~Muy bien.~~

# Ejemplo 3: Listas
1. Objeto 1
2. Objeto 2
3. Objeto 3
4. Objeto 4
    - Ejemplo por puntos 1.
    - Ejemplo por puntos 2.
    - Ejemplo por puntos 3.

**_Para crear una lista enumerada lo unico que tendremos que hacer es poner 1.+ espacio, dejando el espacio podremos escribir, para hacer una lista por puntos (desordenada), tendremos que hacer lo mismo que antes pero con guiones y un espacio._**

# Ejemplo 4: Link

**Para poner un titulo con un enlace tendremos que poner el titulo entre corchetes ] [ mas el enlace entre parentesis.**

 Ejemplo: [Buenas Google](https://www.google.com)
 
 **Tambien podemos poner el titulo junto el link y un comentario**
 
 Ejemplo: [Hola Google](https://www.google.com "Google's Homepage")
 
 **Existe otra forma llamada referencial, para que funcione pondremos un titulo con una palabra como referencia, pero a esa palabra clave le tendremos que dar un valor**
 
 Ejemplo: [La extension n.cage es la mejor][n.cage]
 
[n.cage]: https://chrome.google.com/webstore/detail/ncage/hnbmfljfohghaepamnfokgggaejlmfol?hl=ES

# Ejemplo 5: Imagenes
Para el primer ejemplo tendremos que poner el comando ![alt text] mas el link de la imagen entre parentesis. 

**Inline-style:** 
![alt text](http://editorconfig.org/logos/atom.png "Logo Title Text 1")

Luego tenemos otro modo de poner imagenes llamado referencial, que es como explicamos en el apartado anterior referente a los links.Tendremos que poner el comando ![alt text] mas la palabra clave [logo].

Reference-style: 
![alt text][logo]

[logo]: https://avatars0.githubusercontent.com/u/19570767?v=4

# Que codificacion usa este fichero de texto.

Consta de una codificacion UTF-8.

# Principales instrucciones: Git.

1. La funcion de git add podemos registrar los cambios en la parte del Indice.

2. La funcion de git commit -m, describe los cambios realizados.

3. La funcion git git pull origin master -m "mensaje" descarga e incorpora los cambios al repositorio remoto.

4. La funcion de git push origin master carga todos los repositorios locales al repositorio remoto.

