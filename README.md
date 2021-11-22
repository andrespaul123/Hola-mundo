# Hola-mundo
Es una aplicacion con electron, con la visualizacion  de un hola mundo

no se añadio la carpeta node_modules por eltamaño de carpetas.
CREAMOS NUESTRA PRIMERA APLICACION.
npm init       
El initcomando interactivo le pedirá que establezca algunos campos en su configuración.
npm init -y  
el init-y agrega directamente los campos por defecto.

Su package.jsonarchivo debería verse así:

{
  "name": "my-electron-app",
  "version": "1.0.0",
  "description": "Hello World!",
  "main": "main.js",
  "author": "Jane Doe",
  "license": "MIT"
}

Luego, instale el electronpaquete en el archivo de su aplicación devDependencies.

npm install --save-dev electron

Finalmente, desea poder ejecutar Electron. En el scriptscampo de su package.jsonconfiguración, agregue un startcomando como este:

{
  "scripts": {
    "start": "electron ."
  }
}
Este startcomando le permitirá abrir su aplicación en modo de desarrollo.
npm start
Nota: Este script le dice a Electron que se ejecute en la carpeta raíz de su proyecto. En esta etapa, su aplicación arrojará inmediatamente un error que le indicará que no puede encontrar una aplicación para ejecutar.







