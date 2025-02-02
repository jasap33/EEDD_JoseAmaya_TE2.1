TAREA EVALUABLE 2.1. TRABAJO CON GIT (Visual Studio Code)

Objetivos

Conocer cómo trabajar con GIT desde Visual Studio Code.
Conocer el entorno de VS Code para trabajar con git.
Conocer el lenguaje de marcado Markdown y su utilización en el desarrollo de documentación.
Entrega

El documento justificativo de la realización de la tarea se realizará en formato Markdown, el nombre del fichero será readme.md y estará dentro de la carpeta UT2\TE2.1 dentro del repositorio oficial del alumno para la asignatura.

El fichero readme.md debe contener los siguientes apartados:

Cada uno de los puntos de la tarea.
Explicación de los pasos realizados y una imagen/gif justificativo del paso. (las imagenes se guardarán en la carpeta UT2\TE2.1\img).
El nombre de la imagen debe ser el número del punto y subpunto seguido de la extensión correspondiente (.png, .jpg, .gif).
Ejemplo: 01.1.png, 02.5.gif, 03.3.jpg.
Copia este documento como plantilla para la realización de este ejercicio en tu repositorio.

📦 Recursos

📁 GIT

Visualizar conceptos con D3

Taller de introducción a GIT

Guía de supervivencia de GIT

SOS Git

Escrbir en Markdown

Curso de GIT y GITHUB (youtube)

💡 Para obtener la url de un fichero en GIThub y que esta URL pertenezca a un commit específico, desde el navegador, desde el teclado pulsar y y se copia la url con el hash del commit.
📹 GIF

ScreenToGif grabar la pantalla y convertirlo en gif.
➕ Extensiones de VSCode

Git Graph
Markdown All in One
Markdown Emoji
1. Crear repositorio local y subir a GITHUB

1.Crea una carpeta llamada UT2.1.a.

2.Inicializa un repositorio local en la carpeta UT2.1.a. adjunta la imagen

![Cap1](img/f1.png)

3.Revisa qué rama se ha creado por defecto. ¿Desde dónde los visualizas? adjunta la imagen
Rama por defecto

![Cap2](img/f2.png)

4.Renombrar la rama por defecto a main en caso de que tenga otro nombre. adjunta un gif

![Cap3](img/f3.png)

5.Agrega un fichero README.md.

# UT2.1.a

Repositorio de prueba para la tarea 2.1.a

6.Agrega el fichero README.md al stage area. adjunta un gif

![Cap4](img/f4.png)
 

7.Realiza un commit con el mensaje "Add README". adjunta un gif

![Cap5](img/f5.png)
 

8.Agrega otro fichero 01.xml con siguiente texto.

<?xml version="1.0" encoding="UTF-8"?>
<libreria>
    <libro>
        <titulo>El Quijote</titulo>
        <autor>Miguel de Cervantes</autor>
        <editorial>Editorial Castalia</editorial>
        <fecha>1605</fecha>
        <genero>Novela</genero>
        <precio>20</precio>
    </libro>
</libreria>

9.Agrega el fichero 01.xml al stage area y realiza el commit "Add file 01.xml" adjunta un gif

![Cap6](img/f6.png)
 

10.Agrega una nueva rama llamada fea/wac01 con la ayuda git-graph. adjunta un gif

![Cap7](img/f7.png)

11.En qué rama estas ahora mismo? ¿Cómo sabes en qué rama estás? adjunta la imagen y explica en breves palabras.

// Estoy en la rama main actualmente. Puedo saber en qué rama estás ejecutando el comando git branch

Rama actual

12.Estando en la rama fea/wac01 agrega un fichero 02.xml, y agrega al área de stage y realiza commit "Add file 02". adjunta un gif

<?xml version="1.0" encoding="UTF-8"?>
<libreria>
    <libro>
        <titulo>El Hobbit</titulo>
        <autor>J.R.R. Tolkien</autor>
        <editorial>Minotauro</editorial>
        <fecha>1937</fecha>
        <genero>Fantasía</genero>
        <precio>15</precio>
    </libro>
</libreria>

![Cap8](img/f8.png)

13.Muestra el log (pantalla de git-graph donde se visualize el commit). adjunta la imagen
Log rama fea/wac01

![Cap9](img/f9.png)

14.Posicionate de nuevo en la rama main, y crea otra rama fea/wac02, posicionandote directamente en ella. Agrega un fichero 03.xml, agrega al área de stage y realiza commit "Add file 03".

<?xml version="1.0" encoding="UTF-8"?>
<libreria>
    <libro>
        <titulo>El Señor de los Anillos</titulo>
        <autor>J.R.R. Tolkien</autor>
        <editorial>Minotauro</editorial>
        <fecha>1954</fecha>
        <genero>Fantasía</genero>
        <precio>25</precio>
    </libro>
</libreria>

15.Posicionate en la rama main y muestra los ficheros que hay en el directorio. (mostrar el arból de directorios de VS Code). adjunta la imagen
Ficheros en main

![Cap10](img/f10.png)

16.Realizar un merge de la rama fea/wac01 en la rama main. adjunta un gif

![Cap11](img/f11.png)

17.Muestra el el log, y los ficheros que hay en el directorio. (mostrar el arból de directorios de VS Code) adjunta la imagen 

![Cap12](img/f12.png)
 

18.Elimina la rama fea/wac01 sin posibilidad de recuperación. adjunta un gif

![Cap13](img/f13.png)
 

19.Realiza un merge de la rama fea/wac02 en la rama main.

20.Muestra el log, y los ficheros que hay en el directorio. (Imagen) adjunta la imagen Log y ficheros en main

![Cap14](img/f14.png)

21.Vuelve a la rama fea/wac02 y modifica el fichero 03.xml añadiendo un nuevo libro.

<?xml version="1.0" encoding="UTF-8"?>
<libreria>
    <libro>
        <titulo>El Señor de los Anillos</titulo>
        <autor>J.R.R. Tolkien</autor>
        <editorial>Minotauro</editorial>
        <fecha>1954</fecha>
        <genero>Fantasía</genero>
        <precio>25</precio>
    </libro>
    <libro>
        <titulo>El Silmarillion</titulo>
        <autor>J.R.R. Tolkien</autor>
        <editorial>Minotauro</editorial>
        <fecha>1977</fecha>
        <genero>Fantasía</genero>
        <precio>25</precio>
    </libro>
</libreria>
Agrega al área de stage y realiza commit "Update 03 file. Add book El Silmarillion".
adjunta un gif, donde se visualize el contenido del fichero y el commit

![Cap15](img/f15.png)
 

22.Realiza un merge de la rama fea/wac02 en la rama main. adjunta un gif

![Cap16](img/f11.png)
 

23.Muestra el log del repositorio, y muestra el contenido del fichero 03.xml. (Imagen visualizando comandos) adjunta gif 

![Cap16](img/f16.png)
 

24.Ahora, en la rama main modifica el fichero 03.xml incluyendo un nuevo libro.

<?xml version="1.0" encoding="UTF-8"?>
<libreria>
    <libro>
        <titulo>El Señor de los Anillos</titulo>
        <autor>J.R.R. Tolkien</autor>
        <editorial>Minotauro</editorial>
        <fecha>1954</fecha>
        <genero>Fantasía</genero>
        <precio>25</precio>
    </libro>
    <libro>
        <titulo>El Silmarillion</titulo>
        <autor>J.R.R. Tolkien</autor>
        <editorial>Minotauro</editorial>
        <fecha>1977</fecha>
        <genero>Fantasía</genero>
        <precio>25</precio>
    </libro>
    <libro>
        <titulo>El Hobbit</titulo>
        <autor>J.R.R. Tolkien</autor>
        <editorial>Minotauro</editorial>
        <fecha>1937</fecha>
        <genero>Fantasía</genero>
        <precio>15</precio>
    </libro>
</libreria>
Agrega al área de stage y realiza commit "Update 03 file. Add book El Hobbit".
adjunta un gif, donde se visualize el contenido del fichero y el commit

![Cap17](img/f17.png)
 

25.Agrega un nuevo fichero 04.xml sobre libros ciencia-ficcion, en la rama main.

<?xml version="1.0" encoding="UTF-8"?>
<libreria>
    <libro>
        <titulo>El fin de la eternidad</titulo>
        <autor>Isaac Asimov</autor>
        <editorial>Edhasa</editorial>
        <fecha>1955</fecha>
        <genero>Ciencia ficción</genero>
        <precio>20</precio>
    </libro>
</liberia>
Agrega al área de stage y realiza commit "Add 04 file. Add cienca-ficcion books".

![Cap20](img/f20.png)

26.Muestra el registro de commits (log) y los ficheros que hay en el directorio. adjunta una imagen
Log y ficheros en main

![Cap21](img/f21.png)

27.Vuelve un commit atrás, y muestra el log y los ficheros que hay en el directorio. adjunta un gif

![Cap22](img/f22.png)
 

28.Vuelve al commit anterior, y muestra el log y los ficheros que hay en el directorio. adjunta un gif

![Cap23](img/f23.png)
 

29.Posicionate de nuevo en el último commit, y muestra el log y los ficheros que hay en el directorio. adjunta un gif 

![Cap24](img/f24.png)
 

2. Crear repositorio remoto y subir a GITHUB

1.Crea un repositorio remoto en GITHUB llamado EEDD_{NombreApellido}_TE2.1 público, vacio, sin nada.

2.Agrega el repositorio remoto a tu repositorio local. Explica cómo lo haces, y adjunta una imagen donde se visualizen las url's
Repositorio remoto

![Cap25](img/f25s.png)

 //  git init: Este comando inicializa un repositorio Git vacío o reinicializa uno existente en el directorio actual.
git remote add origin 
<URL>: Este comando agrega un nuevo repositorio remoto. origin es el nombre del repositorio remoto, y <URL> es la URL del repositorio remoto en GitHub.
git remote -v: Este comando muestra las URL de los repositorios remotos que has configurado. 

 
3.Sube la rama main al repositorio remoto. adjunta un gif

![Cap26](img/f26s.png)
 

4.Posicionate en la rama fea/wac02 y sube la rama fea/wac02 al repositorio remoto. adjunta un gif

![Cap27](img/f27s.png)
 

5.Ahora desde GITHUB (web) en la rama fea\wac02, modifica el fichero 03.xml añadiendo un nuevo libro.

<?xml version="1.0" encoding="UTF-8"?>
<libreria>
    <libro>
        <titulo>El Señor de los Anillos</titulo>
        <autor>J.R.R. Tolkien</autor>
        <editorial>Minotauro</editorial>
        <fecha>1954</fecha>
        <genero>Fantasía</genero>
        <precio>25</precio>
    </libro>
    <libro>
        <titulo>El Silmarillion</titulo>
        <autor>J.R.R. Tolkien</autor>
        <editorial>Minotauro</editorial>
        <fecha>1977</fecha>
        <genero>Fantasía</genero>
        <precio>25</precio>
    </libro>
    <libro>
        <titulo>El Hobbit</titulo>
        <autor>J.R.R. Tolkien</autor>
        <editorial>Minotauro</editorial>
        <fecha>1937</fecha>
        <genero>Fantasía</genero>
        <precio>15</precio>
    </libro>
    <libro>
        <titulo>El hombre bicentenario</titulo>
        <autor>Isaac Asimov</autor>
        <editorial>Edhasa</editorial>
        <fecha>1976</fecha>
        <genero>Ciencia ficción</genero>
        <precio>20</precio>
</libreria>
Realiza un commit con el mensaje "Update 03 file. Add book El hombre bicentenario". (Muestra pantallazo de GITHUB con el commit realizado) adjunta la imagen

![Cap28](img/f28s.png)

6.Ahora obten los cambios sin acualizar el repositorio local (git fetch origin).
Muestra el log del repositorio local adjunta la imagen

![Cap29](img/f29s.png)

7.Ahora actualiza el repositorio local con los cambios del repositorio remoto (git pull) y muestra el log. adjunta un gif
 
 ![Cap30](img/f30s.png)

8.Haz un merge de la rama fea/wac02 en la rama main. Muestra estado, log, y el contenido fichero 03.xml (Incluye imagen) adjunta un gif

![Cap31](img/f31s.png)
 

9.Sube la rama main al repositorio remoto. adjunta una gif

![Cap32](img/f32s.png)
 

10.Elimina la rama local fea/wac02 sin posibilidad de recuperación. adjunta un gif

![Cap33](img/f33s.png)
 

11.Elimina la rama remota fea/wac02 sin posibilidad de recuperación

// git push origin --delete fea/wac02

12.Muestra desde GITHUB (navegador web) las ramas que tienes el en repositorio remoto. adjunta un gif

![Cap34](img/f34s.png)
 

13.Para finalizar, muestra el log del repositorio local (Incluye imagen) adjunta la imagen

![Cap35](img/f35s.png)

3. Enlace repositorio remoto

1.Incluye el enlace al repositorio remoto en este punto para que el profesor pueda acceder a él.
 // Enlace al repositorio remoto (en que aparece en la URL del navegador)
 