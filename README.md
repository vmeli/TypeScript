# Comenzando con TypeScript

* Instalando el compilador TypeScript

~~~
    npm install -g typescript
~~~

* Usando el compilador

    * Creamos un archivo con la extensión .ts
    * Abrimos la terminal y ejecutamos el siguiente comando 
    ~~~
        tsc namefile.ts 
    ~~~
    * Se genera el archivo namefile.js (podemos ejecutar `node namefile.js`) 
    * Se utiliza el siguiente flag para el compilado automático del archivo namefile.ts
    ~~~ 
        tsc --watch namefile.ts
    ~~~

* Archivo tsconfig
    
    ~~~
        tsc --init
    ~~~



