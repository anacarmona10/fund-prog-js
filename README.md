# Creación y manejo de ramas
Las ramas fueron relativamente fáciles de crear, cuando se tiene inicializado el git prácticamente solo es cosa de saberse el comando correcto.
En la gestión también es sencillo, también se trata de saber cuál es el comando correcto, pero en este caso también hay que tener en cuenta en qué momento se utilizan estos mismos comandos.
### En este proyecto:
Solo se creó una rama llamada feature/operadores-calculadora-propina, en donde se manejó el desarrollo de una calculadora de propinas que recibe el precio de la cuenta y el porcentaje de propina que el cliente debe dejar. Por este proyecto nos centraremos en la rama, al haber hecho todo en solo 3 commits y una sola rama, fue realmente fácil hacer el manejo de la rama, pues solo "empujé" los cambios una vez terminé el trabajo propuesto, sin necesidad de "empujar" mas ramas, mas cambios ni más commits después de haber terminado el trabajo propuesto.
# Ejemplos de comandos utilizados en la fusión de ramas
En este proyecto solo se hizo una fusión de ramas entre feature/operadores-calculadora-propina y develop. Primero entonces se utilizó un comando "git switch" para transportarnos a la rama develop ya que estaba en la otra rama, luego se utilizó el comando "git merge" seguido de la rama que contenía el desarrollo para fusionarlas
# Proceso paso a paso de sincronización local con remoto
Primero, me aseguré de que el "quick setup" tuviera el protoicolo de comunicación "https" para copiar el link que allí se encuentra y con él hacer la vinculación en la terminal de git del proyecto con el comando "git remote add origin" seguido del link. Luego se empujan todos los cambios actuales con el comando "git push --all" seguido también de este mismo link. 
# Retos afrontados y aprendizajes clave
Este proyecto tuvo aprendizajes muy útiles debido a que me dió una introducción al tema de las ramas, sus fusiones y la forma de subirlas al repositorio remoto. En cuestión de retos solo fue el miedo a hacer algo mal debido a la inexperiencia, pero no creo que haya tenido mayores problemas.
