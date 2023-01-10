# Documentación MP4UF1 (apuntes)
#### Indice 
- GITHUB
- Markdown
- HTML

1. **GITHUB-GITHUB_PAGES**

   a) Crear cuenta de Github.
   
   Lo primero que hicimos fue crear una cuenta de [GitHub](https://github.com:Portada "Pagina_GitHub"), una vez creada la cuenta de GitHub y verificada, ya podriamos 
   empezar a usar nuestra cuenta.
   
   b) Creacion de repositorios.
   
   Cuando ya estamos dentro del GitHub podemos crear repositorios como se ve en las siguientes imagenes:
   
   ![1](Screenshot_3.png "Creacion")
   ![2](Screenshot_4.png "Creacion")
   
   En “repository name” ponemos el nombre que queremos que tenga nuestro nuevo repositorio.
   
   Tenemos que elegir si queremos que el repositorio sea público o privado. Si posteriormente queremos activar GitHub pages para poder publicar el repositorio (sólo 
   HTML, CSS básico, no PHP) ha de ser público.
   
   Marcamos la opción de creación del archivo README o no, dependiendo de:
   
   - Si creamos el archivo README, el repositorio se crea e inicializa automáticamente en GitHub.
   
   - En caso de que no se marque el archivo README.md, el repositorio en GitHub se creará vacío y no inicializado.

   -**Clonado y trabajo en local (GIT) de un repositorio de GitHub inicializado (activo).**
  
   Después vamos a la terminal y nos colocamos en la carpeta de nuestro proyecto, ahí escribiremos la siguiente linea:
  
   - git remote add origin [URL de tu repositorio]
   
   Con esto ya tenemos linkeado nuestro repositorio con github o el servicio que estemos usando en el momento. Ahora, si ya tienes archivos para tu primer commit, 
   sigamos los siguientes pasos para subirlo a github, comenzando por agregar los archivos al commit con:
   
   - git add .

   Luego, podemos hacer el commit agregándole un mensaje, recuerda ser clara al escribir este mensaje, pues los otros programadores de tu proyecto lo verán: 
  
   - git commit -m "Un Mensaje"

   Ahora ya estamos listos para hacer push y que los cambios se reflejen en github usando la linea:
  
   - git push -u origin master

   Notar que usamos la opción "-u", esto lo usaremos solo esta vez, y sirve para indicar que estaremos creando esta rama en el repositorio remoto (github en este          caso), si no lo usamos git no sabrá donde subir el commit que recién hiciste, pues master solo existe en tu computadora por el momento.
   
   c) Importar repositorio ya existente en GitHub.
   
   Para poder importar un repositorio tenemos que copiar la URL del repositorio que queramos importar, en la siguientes imagenes se explica como se hace el proceso.
   
   ![3](Screenshot_5.png "Creacion")
   
   Cuando ya tenemos la URL copiada tenemos que ir a repositorios y darle a New
   
   ![4](Screenshot_3.png "Creacion")
   
   Una vez dentro nos aparece una opcion "import a repository" le damos click
   
   ![5](Screenshot_6.png "Creacion")
   
   En “old repository’s clone URL” pegamos la URL del repositorio a importar mientras que en “Repository Name” ponemos el nombre que queremos que tenga nuestro 
   repositorio clonado.
   
   ![6](Screenshot_7.png "Creacion")
   
   d) Cómo activar GitHub pages para un repositorio.
   
   Para poder activar el pages de un repositorio tenemos que ir a settings
   
   ![7](Screenshot_9.png "Creacion")
   
   Vamos en la opcion de PAGES, el repositorio debe estar en publico para poder activarse. Si el repositorio esta en privado no va dejar
   
   ![8](Screenshot_8.png "Creacion")
   
   Escogemos a qué rama asociar “pages” (por defecto “main”) y a qué carpeta (por defecto “root”) y aplicamos configuración con “Save”. Una vez procesado, nos muestra 
   la URL del repositorio.
   
   ![9](Screenshot_10.png "Creacion")
   
   Una vez darle al Save nos va salir este mensaje el cual nos confirma que se va a generar la URL
   
  2. **MarkDown**

 - __Encabezados__: Entre mas # mas pequeño es el es encabezado, tiene como maximo 6 "#" 

   .# Encabezado 1 (H1)
  
   .###### Encabezado 6 (H6)

 - __Estilos de letra__:

Texto en cursiva: Para tener un texto en cursiva tenemos que empezar con * y terminal con * o en vez de usar * podemos usar _ y al final _

Texto en negrita Para tener el texto en negrita se empieza con ** y se finaliza con ** o tambien se puede con __ y se finaliza igual con __

Se puede usar con cualquier texto las dos combinaciones juntas

 - __Listas__:

Para la lista ordenada empezamos con 1 pero el número de orden no ha de ser necesariamente consecutivo

.1. Titulo 1 Lista ordenada 

.2. Titulo 2 Lista ordenada

Pero para la lista desordenada podemos utilizar 3 elementos pueden ser +,* o -

.- Titulo 1 Lista desordenada

.- Titulo 2 Lista desordenada

- __Codigo__:

El código se ha de incluir entre acentos graves (`). Si en el código aparece un acento grave, se ha de introducir el carácter dos veces al principio de la sección del código.

``Todo esto es `código`.``

También se puede marcar el área correspondiente al código insertando tres acentos graves al principio y al final. Junto a los tres iniciales se puede indicar el lenguaje (HTML, JavaScript) para que incluso se muestre con los colores adecuados:
```html
<html>
  <head>
  </head>
</html>
```
- __Enlances__:

[Link].(https://ejemplo.com/ "Título opcional del enlace")

Primero se incluye el texto del link entre corchetes y posteriormente el link entre paréntesis

- __Imagenes__:

![Logo].(Imagen subida a nuestro repositorio "Título opcional de la imagen")

Para poder poner una foto necesito previamente subir la imagen para poder luego insertarla 

- __Tablas__:

.| Encabezado1 | Encabezado2 | Encabezado3 |

.| ----------- | :---------: | ----------: |

.| Item1 | Boli | 20$ |

.| Item2 | Grapadora | 40$ |

.| Item3 | Tipex | 10$ |

- Los dos puntos se usan para alinear las columnas (izquierda, centrado, derecha).
- No es necesario que estén alineadas verticalmente. Solo a nivel visual para claridad del código.
- Se han de poner al menos tres guiones para separar cada encabezado

3. **HTML**

Las paginas web tienen como mínimo una página creada con HTML, la primera página html tiene que tener el nombre de "index.html" ya que el navegador entenderia que esa es la página principal y es la primera que va amostrar.

Para crear una página HTML hay que seguir estos pasos:

