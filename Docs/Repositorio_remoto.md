# COMÓ CREAR UN REPOSITORIO REMOTO👽

## El paso mas importante es crear tu cuenta de GitHub, lo único que se necesita es un email y contraseña.

- Al ingresar a tu cuenta de GitHub debes de crear un proyecto para poder subir el repositorio local creado anteriormente.

  Entonces para esto primero se debe ir donde dice __“your repository”__ en tu cuenta de GitHub para ver tus repositorios creados.

- Luego vas Y le das la opción de __“new repository”__. Se debe ingresar los datos que te pide de el repositorio que se quiera crear, para finalizar con el boton de __“create repository”__.

  De momento tu repositorio remoto ya está creado en GitHub.

### Pues bien ya que está creado, falta vincular el repositorio remoto con el repositorio local.

- El siguiente paso es subir el repostorio creado en git bash a GitHub.

- Para este paso lo que se tiene que hacer es copiar el link del repositorio remoto que en este caso se encuentra en GitHub, luego entras a git bash y debes de añadir el repositorio remoto que tienes en GitHub  usando el siguiente
  <comando git remote add origin "pegas el link que te dan en GITHUB"> y así ya se añadido el repositorio remoto al repositorio local.

- Luego lo que se debe de hacer es subir el repositorio local al repositorio creado en GitHub, entonces para eso se debe de usar el siguiente <comando git push origin main>, Y ya te confirma que tu repositorio local se subió al repositorio creado por GitHub.

- Luego debes de ir a la página de GitHub y simplemente actualizar la página nuevamente. Y ahí ya te debería mostrar los archivos del repositorio local subido a GitHub.

- El siguiente paso sería crear un **README.md** Un README no es más que un documento que describe realmente lo que hace el repositorio.

  Para esto debes de darle al boton __“add a README”__ para así agregar el archivo README al repositorio.

- Luego a esto se le debe crear un commit en el repositorio remoto igual que como se hace con el repositirio local y para esto se debe dar al botón __“commit new file”__ , hecho esto ya se puede ver que el archivo README ya se a añadido

  al repositorio remoto y podemos ver que hay un cambio en nuestro repositorio remoto pero ese cambio aún no se encontrará dentro del repositorio local.

- El siguiente paso es hacer un pull en el repositorio remoto, la función del pull es básicamente mantener la copia del proyecto que está en remoto.

**Ejemplo, en el caso que estuvieras en un proyecto grande y algunos trabajadores estuvieran trabajando sobre este proyecto, pull lo que va a hacer es actualizar el repostirio local con algunos cambios que estén en ese momento en el 
  
  repositorio remoto**.Entonces para hacer esta opción de obtener todos los archivos actualizados de mi repositorio remotos se debe utilizar el siguiente <comando git pull origin main> , y ahí te debe de decir que se encuentra
 
  actualizado el repositorio remoto con todos los cambios que se a hecho en el repositorio remoto hacia el repositorio local.

| __Botones importantes en GITHUB__   | **Comandos importantes**                  |
|------------|------------------------|-------------------------------------------|
| _your repository_                   | <comando git remote add "pegas el link">  |
| _new repository_                    | <comando git push origin main >           |
| _add a README| 28_                  | <comando git pull origin main>            |
| _commit new file_                   |                                           |
|-------------------------------------|-------------------------------------------|

### IMPORTANTe: NO USAR EL COMANDO DE GIT PULL ANTES DE HACER EL PUSH, PORQUE SE TE BORRA TODO LO CREADO EN EL REPOSITORIO LOCAL!!!

