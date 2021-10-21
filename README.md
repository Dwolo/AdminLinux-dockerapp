1. La aplicacion necesita NodeJS, fue comprobado con la version 12.
2. Van a ser necesarion los paquetes: python g++ make
3. Por organizacion copiar y correr la aplicacion en el path `/app`
4. Para instalar la aplicacion hay que correr el comando `yarn install --production` en la carpeta del repositorio.
5. El comando para correr la aplicacion es: `node src/index.js`
6. Cambiar linea en src/static/js/app.js

```
 -                <p className="text-center">No items yet! Add one above!</p>
 +                <p className="text-center">You have no todo items yet! Add one above!</p>
```
