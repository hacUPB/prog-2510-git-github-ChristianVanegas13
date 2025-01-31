## Pasos y Normas Para Hacer El Uso De Git Correctamente. 

## Primer Paso:

**NOTA**: Antes de empezar a usar Git, es importante configurarlo con tus datos personales para que cada vez que hagas un commit, Git pueda asociarlo con tu identidad. Para hacerlo, utilizas comandos específicos que actualizan el archivo de configuración de Git con esta información.

1. **Como Configurar Tu Nombre de Usuario y Correo Electrónico En Git**
    
 Para configurar tu nombre y correo electrónico en Git, debes usar estos comandos:

 git config --global user.name "Tu Nombre": Este comando se usa para definir tu nombre de usuario.

 git config --global user.email "tu.email@ejemplo.com": Este comando se usa para establecer tu correo electrónico.

 Estos comandos guardarán la información en la configuración global de Git, lo que significa que se aplicarán a todos los repositorios en tu computadora.Y asi podaras usar Git correctamente.


2. **Como Verificar la Configuración Del Sistema**

  git config --list: Este comando se usa para verificar la configuración de Git en tu sistema. 

 Al ejecutar este comando correctamente, podrás ver toda la configuración actual de Git en tu sistema. Busca tu nombre y correo electrónico en la lista para verificar que estén correctos. Si necesitas cambiarlos, simplemente usa los mismos comandos que usaste 
 inicialmente, y eso sobrescribirá los valores anteriores.

 **IMPORTANTE**: Es muy iportante tener en cuenta que, en ocasiones, el editor que se abre al ejecutar ciertos comandos en Git puede no permitirte ingresar más comandos directamente. Si esto ocurre, puedes salir del editor presionando la tecla Q (Quit), lo que te
 devolverá a la línea de comandos. 

 3. **Conclusion Del Primer Paso.

    Asegúrate de que tu nombre y correo electrónico siempre estén correctos.
    
**Recuerda** : Siempre que uses una computadora diferente, como las de una sala de cómputo, asegúrate de verificar el usuario configurado, ya que el equipo puede ser usado por otras personas y no tener tu información.

 ## Segundo paso:

  **como Crear Un Repositorio Local y Realizar El Control De Versiones**

  **🔥 Importante: Cuando crees tus repositorios para el curso, asegúrate de guardarlos en una carpeta fuera de sistemas de almacenamiento en la nube, como OneDrive, para evitar conflictos con Git.

  - En Windows, se recomienda usar la carpeta Documentos. Dentro de esta, crea una nueva carpeta con un nombre distintivo, por ejemplo, Repositorios_NombreCurso.

  - En Mac, puedes crear una carpeta en tu Home.

1. **Como Navegar por los directorios de tu computadora

  Debes Abrir Git Bash si estás en Windows o Terminal en Mac. Luego, debes usar los siguientes comandos. 
  
  cd: para moverte entre carpetas.
  
  cd ..: para retroceder una carpeta.

  Esto te permitirá ubicarte en el lugar donde quieres guardar tus repositorios.

 


