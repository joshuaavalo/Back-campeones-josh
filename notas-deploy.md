

# PASOS A SEGUIR PARA DEPLOY EN HEROKU.

1. Ir a index.js para hacer que nuestro puerto sea dinamico y se pueda manejar desde la variable de entorno PORT.  
    ANTES: const PORT = 3001;   / DESPUES: const PORT = process.env.PORT || 3001;.

2. Instalamos heroku en nuestro proyecto.///// npm i -b heroku //////.

3. creamos archivo en nuestra raiz para configurar heroku.   ProcFile

