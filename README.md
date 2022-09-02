## NPM INIT

#### Algunas consideraciones acerca de cómo inicializar correctamente un package-json:

1. npm init.
2. Declarar el nombre del proyecto.
3. **SEMVER SEMANTIC VERSION**: El versionado semántico, sirve para realizar un buen seguimiento de las modificaciones de nuestro software a lo largo del tiempo. Las modificaciones pequeñas cambian el último número, las modificaciones importantes el segundo número y el cambio total de versión modifica el primer número.
4. Descripción libre sobre el proyecto.
5. Declarar el archivo main del proyecto (no necesariamente tiene que ser index.js).
6. testing.
7. git repository.
8. **Keywords**: Palabras clave.
9. **Autor:** Nombre de usuario de GitHub.
10. Licencia.
11. **scripts**: Sirve para crear nuestros propios comandos. Ej: Si mi script va a ser --- "ejecutar": "node app.js" --- (dentro del package-json), entonces mi línea de comando va a ser --- npm run ejecutar ---. Si mi archivo principal se encuentra dentro de una carpeta, entonces también hay que especificarlo dentro del script. Ej --- "ejecutar": node src/app.js" ---.
12. Los scripts no pueden finalizar en coma, son únicos en su naturaleza y puede haber más de uno. Inclusive, se pueden nombrar dos scripts distintos que hagan exactamente lo mismo.
13. Una buena práctica para no mezclar el funcionamiento de node.js con el material del proyecto, es crear una carpeta source/src.
14. Cuando trabajamos con las dependencies es importante aclarar, en la instalación de paquetes, si los vamos a utlizar como indispensables para el funcionamiento del proyecto o si los vamos a utilizar como parte del desarrollo del proyecto. Para esto, utilizamos el -D si queremos que en el package-json figure como desarrollo y no como paquete esencial. Ej --- npm i nodemon -D ---.
15. nodemon se encarga de vigilar el comportamiento de los archivos del proyecto y los cambios en el código.

