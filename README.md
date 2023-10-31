# Galvis_Alejandro
      1º) Pull request: es una acción. Una vez hechos los cambios desde el repositorio local se hará un push para subir los cambios locales al repositorio remoto propio y desde este repositorio remoto hacer una solicitud de fusión al autor del repositorio original desde el cual se hizo el fork para integrar los cambios a la rama original.
      2º) Merge conflict: Ocurre cuando dos ramas no son compatibles y no se pueden integrar correctamente puesto que se ha borrado, se ha añadido y/o tienen información contradictoria. Se soluciona generalmente de manera manual identificando dentro del directorio cuál es la información incompatible y limpiando el código sobre el que se han hecho las modificaciones. Una vez resuelto esto se integra la rama principal en la que se está trabajando para hacer compatibles los cambios y postriormente se cambia a la principal para integrar la rama secundaria a la principal y así completar el "merge" y solucionar el conflicto.
      3º)  Fusión "main" y "examen_parcial": Asumiendo que se han añadido los cambios realizados y se han hecho los commits respectivos, me ubicaría en la rama "examen_parcial" y haría "git merge main" para integrar main a "examen_paracial" en primer lugar, y después haría un commit para ponerle nombre al cambio e identificarlo en caso de ser necesario. En segundo lugar, me ubicaría en "main" y ejecutaría "git merge examen_parcial" para integrar los cambios ralizados en esta rama junto a la información que llevé de main y así hacer compatible y definitva la integración de la rama "examen_parcial" a la rama "main".
      4º) Haría un git reset. Hasta ahora no lo he necesitado así que no sé qué pasa después. No obstante no utilizaría un git reset hard pues esto borraría probablemente la información que no quiero que sea borrada de mi área de trabajo.
      5º) Fork y para qué se utiliza: se realiza mediante la página de github. Viendo un repositorio remoto cuyo autor no somos nosotros, nos aparece una opción en verde que se llama "fork" en la parte derecha de la pantalla. Esta acción clonará ese repositorio externo sobre el que se trabajará de manera local para así después hacer un "pull request" al autor original con las modificaciones realizadas sobre los archivos o códigos respectivos. 
      6º) a) Estando en "Nombre_del_alumno" (raíz) hago "cd Universidad/UAX" y dentro de "UAX" ejecuto "nano archivo.txt" para entrar al directorio. Esto es una ruta absoluta pues se está pasando por todos los directorios desde el raíz hasta llegar a donde se desea.
          b) Estando en "Universidad" haría cd UAX y dentro de UAX "nano archivo.txt". Esto es una ruta relativa pues de un solo paso se está llegando a donde se desea.
      7º)  7.1) b) git clone.
           7.2) a) git branch.
           7.3) c) git checkout.
           7.4) b) git add.
           7.5) b) git commit.
           7.6) a) git push.
           7.7) c) git pull.
           7.8) d) git merge.
           7.9) a) git reset -hard.
           7.10) c) git log.
      8º) En primer lugar, integraría la rama develop tanto en matemáticas como en diseño UX; de nada vale seguir adelante con las modificaciones si no hay compatibilidad de cualquiera de las dos ramas donde se han hecho los cambios, con la rama de develop ya que es la que va a recibir todas las moodificaciones en última instancia. Una vez, tanto matemáticas como diseño UX sean compatibles con develop, procedería a integrar diseño UX en matemáticas; diseño UX trabaja con todas las modificaciones de matemáticas por lo que es normal verificar la compatibilidad de diseño en matemáticas para después integrar matemáticas en diseño y asegurarse de dos cosas: 
             1) Matemáticas y diseño son compatibles con develop.
             2) Sus respectivas compatibilidades con develop son compatibles entre sí sobre todo diseño UX con matemáticas pues la primera trabaja con las modificaciones de la segunda.
        Ya verificando todo esto, quedaría toda esta última modificación en diseño UX que estaría integrado con develop y a su vez con matemáticas. Asumiendo que todos los posibles conflictos de código han sido resueltos, ubicándome en develop, fusionaría diseño UX para realizar los últimos cambios respectivos y verificar que funcione de manera correcta. 
      9º) Práctica 3: C) Añadiste el botón "x^4" al archivo "index.html" en tu repositorio local, creaste un commit con los cambios y luego subiste el repositorio local al remoto en la rama principal (master).









      
