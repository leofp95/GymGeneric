# GymGeneric
## Instrucciones
### Instalar Node.js
Descargar node [aquí](https://nodejs.org/en/).
### Instalar Ionic y Cordova
Una vez que tenemos instalado node y npm, ejecutamos lo siguiente en el command prompt o en la terminal:
```
npm install -g ionic cordova
```
### Descargar GitHub Desktop
Instrucciones de descarga de GitHub Desktop [aquí](https://help.github.com/desktop/guides/getting-started-with-github-desktop/installing-github-desktop/).
### Clonar repositorio
Ya con GitHub Desktop instalado, le damos click al boton verde que dice **Clone or download** y seleccionamos la opción **Open in desktop**.
### Descargar módulos de node, plataformas del proyecto y plugins
1. Abrimos Command Prompt (Windows) o la terminal (MacOS, Linux).
2. Navegamos hacia la carpeta del proyecto (*gym-app*) utilizando el comando `cd <ruta del directorio>`. Usualmente se descarga en la ruta *Documents/GitHub/GymGeneric/*.
3. Dentro de *gym-app* ejecutamos `npm install` y esperamos a que se descargue todo.
4. Luego ejecutamos `ionic cordova prepare` para instalar plugins y dependencias.
### Correr el proyecto en el browser
Dentro de *gym-app* ejecutamos `ionic serve`.
