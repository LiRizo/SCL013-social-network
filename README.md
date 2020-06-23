# Creando una Red Social

## Índice

* [1. PawLovers](#1-PawLovers)
* [2. Planificación del proyecto y diseño](#2-Planificación-del-proyecto-y-diseño)
* [3. Historia de usuario](#3-Historia-de-usuario)

***

## 1. PawLovers <img src="https://github.com/LiRizo/SCL013-social-network/blob/master/src/images/iconos/Paw.png">

PawLovers es mucho más que una red social para mascotas. Es todo un universo en torno al mundo de los perros, gatos, pájaros, hamsters, etc. Concursar por la mejor fotografia ya que ¡Ellos son lo primero! En esta comunidad.

En PawLovers podrás relacionarte con gente mascotera como tú, compartir tus experiencias en compañía de tu mascota

Además podrás encontrar empresas y servicios profesionales del sector de los animales de compañía, ayudar a otros animales que lo están pasando mal y mucho más.

### Pruebala
[Link PawLover](https://lirizo.github.io/SCL013-social-network/src/index.html)

## 2. Planificación del proyecto y diseño

### Trello

<img src="https://github.com/LiRizo/SCL013-social-network/blob/master/src/images/MaterialReadme/TrelloPL.JPG">

[Link Trello](https://trello.com/b/LvAEjZ51/social-network)

### Diagrama de flujo

Se realizo una busqueda de diseño que fuera amigable para el usuario y facil de recorrer. antes de avanzar a una etapa mas avanzada.

<img src="https://github.com/LiRizo/SCL013-social-network/blob/master/src/images/MaterialReadme/diagramaDeFlujo.jpg" width= 502px height= 565px>

### Prototipo de Alta fidelidad

Con este prototipo se presento a distintas personas para recibir feeback e implementarlas antes de comenzar con el codigo.

<img src="https://github.com/LiRizo/SCL013-social-network/blob/master/src/images/MaterialReadme/prototipoDeAltaFidelidad.JPG" width= 747px height= 745px>

### Busqueda de diseño <i class="fas fa-palette"></i>

- Paleta de colores
En la búsqueda de la paleta de colores, se quería demostrar jovialidad y una sensación de naturaleza, para eso buscamos colores que a simple vista te trasladan al mundo animal.
y se consiguió una paleta que iba de la mano con lo que se estaba buscando.
[Paleta de Referencia](https://paletasdecolores.com/paleta-de-colores-252/)
hasta llegar a esto
<img src="https://github.com/LiRizo/SCL013-social-network/blob/master/src/images/MaterialReadme/paletaDeColor.png" width= 592px height= 453px>

- Tipografía 
La tipografía debía ser sutil y delicada así que se eligió la font manjari  que curiosamente su nombre significa "albahaca sagrada" o "flor".
- Logo
En la búsqueda del logo pasamos por varias referencias inspiradoras, que podrán ver en el link a continuación.
[Referencias para el logo](https://www.pinterest.cl/lirizoc/idea-pawlovers/)

Luego se prosiguió rápidamente a la creación del mismo,
se probaron varias ideas una al lado de la otra en el prototipo de alta fidelidad. 
<img src="https://github.com/LiRizo/SCL013-social-network/blob/master/src/images/MaterialReadme/PruebasLogo.JPG" width= 870px height= 590px>
Dando como resultado final:
<img src="https://github.com/LiRizo/SCL013-social-network/blob/master/src/images/iconos/logoPawLovers.png" width= 530px height= 300px>

Y se eligió una tipografía que fuera divertida, un poco desordenada, Puedes apreciar un pequeño fragmento comentado del diseñador principal de la Font Neucha "traducido del idioma ruso significa "no saber cómo crear fuentes correctamente". Jovanny Lemonad Era lo que se estaba buscando en ella, una fuente libre y con un toque orgánico que traslada a lo natural.

[Google Font Neucha](https://fonts.google.com/specimen/Neucha)

### d.Experiencia de usuario UX.

Se obtuvo una grata llegada, se obtuvo varios comentarios que se rescataron para mejorar la interacion con los usuarios.

## 3. Historia de usuario

### Historia de usuario 1: Ingreso al sitio web (mobile)

Como invitado, puedo hacer clic en “Ingresar” para ver el modal con el formulario de inicio de sesión/registro para poder realizar comentarios, publicaciones, dar likes y editar mis publicaciones y la información de mi cuenta.

* [] Investigar, las especificaciones de cada componente elemental para poder ejecutar las necesidades del usuario.
* [] Tener un prototipo para recibir feedback de los potenciales usuarios.
* [] definir paletas y diseño del mismo.

### Historia 2 Inicio de sesión y registro a través de modal (mobile)

- Usuario: invitado
- Necesita: acceder a los formularios de inicio de sesión y registro
- Para: crear publicaciones, hacer comentarios, dar like y editar mis publicaciones y la información de mi cuenta
- Criterios de aceptación: modal con dos formularios (inicio de sesión y registro), cada uno en una pestaña. Se activa al hacer clic en “Ingresar”. Una vez logueado, “Ingresa” se transforma en el ícono de perfil de usuario y se activan las opciones de publicar, comentar, likes y la patita para editar
- Definición de Terminado:

* [] Crear modal básico con pestaña de formulario de inicio de sesión y registro (html, css y js).
* [] Crear enlace para abrir modal desde el header de la página de inicio.
* [] Crear funcionalidad de autenticación de usuario y asociar inicio de sesión y registro con las pestañas correspondientes del modal. 
* [] Crear opción de cierre de sesión provisoria (solo para probar la funcionalidad, después la cambiamos para ver cómo se ve mejor).
* [] Dar el estilo definitivo al modal (colores de pestañas, botones, hovers, animaciones, etc.).

### Historia 3 Acceso a categorías de publicaciones (mobile)

- Usuario: quiero tener la vida más fácil
- Necesita: tener un menú de categorías.
- Para: moverse libremente dentro de la app web.
- Criterios de aceptación: Agregar menú superior con información sobre las páginas para navegar. (Móvil, web a un lado derecho).
- Definición de Terminado:


* [] Agregar las categorías al header (solo para el móvil)
* [] Asignar color
* [] Ordenar los iconos en el header
* [] Hacer la animación del search
* [] Hacer las redirecciones

### Historia 4 Carrusel concurso fotográfico

- Usuario: interactuar con diferentes usuarios
- Necesita: participar en concursos de fotos a mascotas
- Para: ver diferentes mascotas y entretenerme votando por los más kawaii
- Criterios de aceptación: agregar un menú carrusel para poder ver las fotos que se han postulado y poder votar por la preferida. 
- Definición de Terminado: poder ver todos los concursantes y votar por el favorito

* [] Recopilar las imagenes y enumerarlas.
* [] Investigar de los diferentes tipos de carrusel.
* [] Implementarlos en su campo asignado.
* [] Definir diseño y medidas.

### Historia 5: Plantilla de Categorías

- Usuario: que entra a buscar algo en especifico
- Necesita: no estar logeado y poder conseguir la informacion que busca
- Para: que al buscar sobre 1 categoría en especifica me salga todo relacionado con ella
- Criterios de aceptación: que funcione para todas las categorias.
- Definición de Terminado: tener una plantilla de categorías. que contenga una pestaña para hacer un post referente a la categoría, y poder ver y comentar, repostear el de otros.

* [] Crear la plantilla del new post. 
* [] Crear planilla de los posts creados.
* [] Crear botones de like, comentario y boton (paw) con edit y borrar.
* [] Asignar un nombre para luego vincularlo con la categoria correspondiente.

### Historia 6: Plantilla de Información (más sobre PL)

- Usuario: que entra a buscar de qué trata la red social.
- Necesita: que esté todo en un solo lugar
- Para: que el usuario interesado que no este tan decido a registrarse, resuelvan sus dudas.
- Criterios de aceptación: que sea una informacin util y acotada.
- Definición de Terminado: tener una plantilla de información. donde puedas saber más sobre los creadores y el fin de la red social.

* [] Vincular con Href a la categoria correspondiente.
* [] Trabajo en el css.
* [] Testear con posibles usuarios para comprobar una información efectiva.



