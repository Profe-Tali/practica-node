
## Tutorial: Instalación de Node.js en Windows
### Paso 1: Descargar Node.js
<img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fprogramaconleo.com%2Fcomo-instalar-node-js%2F&psig=AOvVaw2O55cmLDI0SrwLv_dJedSB&ust=1684877866366000&source=images&cd=vfe&ved=0CBMQjhxqFwoTCICb26fxif8CFQAAAAAdAAAAABAJ" alt="imagen de descargar">
  <li> Ve al sitio web oficial de Node.js en https://nodejs.org. </li>
<li>En la página de inicio, verás dos versiones para descargar: "LTS" (recomendada para la mayoría de los usuarios) y "Current" (la versión más reciente pero potencialmente menos estable).</li>
<li>Haz clic en la versión que prefieras (recomendamos la versión LTS para mayor estabilidad) y se iniciará la descarga del instalador.</li>
### Paso 2: Ejecutar el instalador de Node.js

  <li>Una vez que se haya descargado el instalador, ábrelo haciendo doble clic en el archivo descargado (por ejemplo, node-v14.17.0-x64.msi).</li>
  <li>Aparecerá el asistente de instalación de Node.js. Haz clic en "Siguiente" para continuar.</li>
  
### Paso 3: Aceptar los términos de la licencia
   
<li>Lee los términos de la licencia y, si estás de acuerdo, selecciona la opción "Acepto los términos de la licencia".
  Haz clic en "Siguiente" para continuar.</li>
  
### Paso 4: Seleccionar la ubicación de instalación 
<li>Puedes elegir la ubicación de instalación predeterminada o seleccionar una ubicación personalizada haciendo clic en "Examinar" y eligiendo una carpeta diferente.</li>
  <li>Haz clic en "Siguiente" para continuar.</li>
  
### Paso 5: Seleccionar los componentes a instalar

<li>En esta pantalla, puedes seleccionar los componentes que deseas instalar junto con Node.js. La configuración predeterminada suele ser suficiente para la mayoría de los casos. </li>
    <li>Haz clic en "Siguiente" para continuar.</li>
    
### Paso 6: Seleccionar el menú de inicio
    <li>Aquí puedes seleccionar si deseas crear un acceso directo en el menú de inicio.</li>
    <li>Haz clic en "Siguiente" para continuar.</li>
### Paso 7: Confirmar la instalación 
    <li>Verifica la configuración de instalación en la pantalla de confirmación.</li>
    <li>Haz clic en "Instalar" para comenzar la instalación de Node.js.</li>
### Paso 8: Completar la instalación 
<li>El asistente de instalación instalará Node.js y las herramientas relacionadas en tu sistema.</li>
  <li>Una vez completada la instalación, haz clic en "Finalizar" para cerrar el asistente.</li>
  
### Paso 9: Verificar la instalación
  <li>Abre una ventana de comandos (cmd) o PowerShell en tu computadora.</li>
  <li>Escribe el siguiente comando:</li> 
  
  ```
node --version

```
  Esto mostrará la versión de Node.js instalada.
<li>También puedes verificar la versión de npm (el administrador de paquetes de Node.js) con el siguiente comando:</li>

```
npm --version

```
  
Esto mostrará la versión de npm instalada.
¡Felicidades! Ahora tienes Node.js instalado en tu sistema Windows. Puedes comenzar a desarrollar aplicaciones con Node.js y aprovechar su poderoso ecosistema de paquetes y herramientas.

Espero que este tutorial te sea útil y te deseo éxito en tus proyectos con Node.js.

 <hr> 
  
## Intalación DE NODEJS  en Linux  
## Tutorial: Instalación de Node.js en Linux
* Paso 1: Abrir una terminal <br>
<b> Abre una terminal en tu distribución de Linux. Puedes hacerlo desde el menú de aplicaciones o usando el atajo de teclado Ctrl + Alt + T. </b>

* Paso 2: Actualizar los paquetes del sistema
Es importante mantener los paquetes del sistema actualizados. Ejecuta el siguiente comando para actualizarlos:


```
sudo apt update

```


### Paso 3: Instalar el administrador de versiones de Node.js
El administrador de versiones de Node.js nos permite gestionar diferentes versiones de Node.js en nuestro sistema. Instalaremos NVM (Node Version Manager) usando el siguiente comando:

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash

```

### Paso 4: Cerrar y abrir la terminal
Es necesario cerrar la terminal actual y abrir una nueva para que los cambios surtan efecto. Puedes cerrar la terminal usando el comando exit o simplemente cerrando la ventana.

### Paso 5: Verificar la instalación del NVM
Una vez que hayas abierto la nueva terminal, verifica que el NVM se haya instalado correctamente ejecutando el siguiente comando:


```

nvm --version

```
Deberías ver la versión del NVM instalado.

### Paso 6: Instalar la última versión estable de Node.js
Ahora vamos a instalar la última versión estable de Node.js utilizando el NVM. Ejecuta el siguiente comando:

```

nvm install stable


```
Esto descargará e instalará la última versión estable de Node.js en tu sistema.

###  Paso 7: Verificar la instalación de Node.js y npm
Para asegurarnos de que Node.js se haya instalado correctamente, ejecuta el siguiente comando:


```

node --version

```


https://github.com/nodesource/distributions/blob/master/README.md
