# Aprendiendo-a-usar-Githop
• Crear cuenta gratuita Github  • Leer tutorial de inicio: https://docs.github.com/es/github/getting -started-with-github  • Crear manual de uso en base a lo aprendido.  • Incluir al final resumen de cómo puedo usar Git/Github en mi vida académica o profesional.
¿Cómo se utiliza Github pages?
GitHub es un sitio "social coding". Te permite subir repositorios de código para almacenarlo en el sistema de control de versiones Git. Tu puedes colaborar en proyectos de código, y el sistema es código abierto por defecto, lo que significa que cualquiera en el mundo puede encontrar tu código en GitHub, usarlo, aprender de el, y mejorarlo. ¡Tú puedes hacer eso con el código de otras personas tambien!

Publicando contenido
Github es una comunidad muy importante y útil para involucrarse, y Git/GitHub es un sistema de control de versiones muy popular — la mayoría de las empresas de tecnología ahora lo utilizan en su flujo de trabajo. GitHub tiene una característica muy útil llamada GitHub pages, que te permite publicar el código del sitio en vivo en la Web.

Configuración básica de Github
Primero que todo, instala Git en tu máquina. Este es el software del sistema de control de versiones subyacente en el que GitHub funciona.
Una vez te hayas registrado, inicia sesión en github.com con tu nombre de usuario y contraseña.
Preparando tu código para subirlo
Tú puedes almacenar cualquier código que tu quieras en un repositorio de Github, pero para usar la característica páginas de Github con pleno efecto, tu código debe estar estructurado como un sitio web típico, por ejemplo que el punto de entrada primario sea un archivo HTML llamado index.html.

La otra cosa que necesitas hacer antes de seguir adelante es inicializar el directorio de código como un repositorio Git. para hacer esto:

Apunta la línea de comandos a tu directorio test-site (o como se llame el directorio que contiene tu sitio web). Para esto, usa el comando cd (Es decir "cambio de directorio"). Esto es lo que deberías digitar si has puesto tu sitio web en un directorio llamado test-site en tu escritorio:
cd Desktop/test-site
Copy to Clipboard
Cuando la línea comandos está apuntando hacia el interior del directorio de tu sitio web, digita el siguiente comando, que le dice a la herramienta git para convertir el directorio en un repositorio git:
git init
Copy to Clipboard
An aside on command line interfaces
La mejor manera de subir tu código a Github es mediante la linea de comandos — esta es una ventana donde tú escribe comandos para hacer cosas como crear archivos y ejecutar programas, en lugar de hacer clic dentro de una interfaz de usuario. 

Nota: Tú también podrías considerar una interfaz gráfica de usuario de Git para hacer el mismo trabajo, si te sientes incómodo con la linea de comandos.

Cada sistema operativo viene con una herramienta de línea de comandos:

Windows: Command Prompt se puede acceder pulsando la tecla Windows, tipeando Command Prompt, Y elegirlo de la lista que aparece. Nota que Windows tiene sus propias convenciones de comando diferentes de Linux y OS X, así que los comandos abajo pueden variar en su máquina.
OS X: Terminal se puede encontrar en Aplicaciones > Utilidades.
Linux: Por lo general, puede extraer una terminal con Ctrl + Alt + T. Si eso no funciona, busca Terminal en una barra de aplicaciones o menú.
Esto puede parecer un poco espantoso al principio, pero no te preocupes — que pronto conseguiras la caída de los conceptos básicos. Tú le dices a la computadora que haga algo en la terminal, digitando un comando y oprimiendo la tecla Enter, como se ha visto anteriormente.

Creando un repositorio para tu código
A continuación, tu necesitas crear un nuevo repositorio para colocar tus archivos en el. Has clic en el signo más (+) en la parte superior derecha de la página de inicio de GitHub, luego escoge Nuevo Repositorio.

En esta página, en la caja Nombre del Repositorio, digita el nombre para tu repositorio de código, por ejemplo my-repository.
También llena una descripción para decir lo que tu repositorio va a contener. Tu pantalla debe mostrar algo como esto:

Has Clic en Crear repositorio; Esto debería llevarte a la siguiente página: 

Subiendo tus archivos a GitHub
En la página actual, tú estás interesado en la sección …o empujar un repositorio existente desde la línea de comandos. Tú deberias ver dos lineas de código listado en esta sección. Copia la totalidad de la primera línea, pégala en la línea de comandos, presiona la tecla Enter. El comando debería mostrarte algo como esto:
git remote add origin https://github.com/chrisdavidmills/my-repository.git
A continuación, digita los siguientes dos comandos, presionando Enter despues de cada uno. Estos preparán el código para subirlo a GitHub, y pida a GIt que administre estos archivos.
git add --all
git commit -m 'adding my files to my repository'
Copy to Clipboard
Por último, empuja el código hasta GitHub yendo a la página de GitHub en la que estas e ingresando en la terminal el segundo de los dos comandos que vimos …o empuje un repositorio existente desde la sección de línea de comandos:
git push -u origin master
Copy to Clipboard
Ahora necesitas crear la rama gh-pages de tu repositorio; actualiza la página actual y verá una página del repositorio algo así como la de abajo. Tú necesitas presionar el boton que dice Branch: master, digita gh-pages en el campo de texto, luego presiona el boton azul que dice Create branch: gh-pages. Esto crea una rama de código especial llamada gh-pages que es publicada en una ubicación especial. La URL toma la forma username.github.io/my-repository-name, asi en mi caso de ejemplo, la URL debería ser https://chrisdavidmills.github.io/my-repository. La página mostrada es la página index.html.

Navega tu dirección web de GitHub pages en un nuevo ta del navegador, y tu deberias ver tu sitio en linea! Mandalo por correo electrónico a tus amigos y muestra tu dominio.
Nota: Si te atascas, la página de inicio de GitHub Pages también es muy útil.

Un mayor conocimiento de GitHub
Si deseas realizar más cambios en su sitio de prueba y cargarlos en GitHub, simplemente tendrás que realizar el cambio en tus archivos como antes. A continuación, debes introducir los siguientes comandos (pulsando Intro después de cada uno) para empujar los cambios a GitHub:

git add --all
git commit -m 'another commit'
git push
Puedes reemplazar otro commit con un mensaje más adecuado para describir qué cambio acaba de hacer.

Apenas hemos arañado la superficie de Git.Para obtener más información, comience con el sitio de ayuda de GitHub.
 Incluir al final resumen de cómo puedo
usar Git/Github en mi vida académica o
profesional.
Creo que puedo utilizar Githop para  compartir codigo con mis compañeros en las tareas que nos vayan dejando  en nuestra paso en la Universidad, posteriormente en un ambiente laboral para faciliar la comunicación,.
