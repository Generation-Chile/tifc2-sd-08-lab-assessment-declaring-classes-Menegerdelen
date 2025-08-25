# Instrucciones
Las clases son una sintaxis alternativa para definir una **plantilla** para construir objetos. Al igual que las funciones constructoras, pueden usarse para construir objetos con su **propio** conjunto de propiedades y métodos. Como los prototipos, también permiten que los objetos los **hereden**. Los **métodos constructores** de clase se usan para crear una instancia de una clase. Los **métodos compartidos** son heredados por cada instancia.

**¡Hoy estarás definiendo clases, inicializando objetos con propiedades y actuando sobre esas propiedades con métodos!**

Para cada una de estas tareas, estarás construyendo e iterando sobre tu solución de la tarea anterior.


## Tareas

1. Estás trabajando en código que será usado en un videojuego. Te han pedido que crees una clase de objeto. Estas serán usadas para definir jugadores en ese juego. Cada jugador puede elegir su propio nombre, y estos objetos serán usados para almacenarlos.
    * Modifica la clase Player para que acepte un "**nombre**" de jugador en un argumento.
        * La clave de esta propiedad en el objeto resultante **debe** ser "`name`" - ¡recuerda, **las computadoras son muy literales**!


2. Ahora te han pedido que mejores tu código, para que los objetos jugador puedan definir tanto un nombre como un número de nivel.
    * Modifica la clase Player para que acepte un string "nombre" del jugador y un número de "**nivel**" en dos argumentos separados.
        * La clave de esta propiedad en el objeto resultante **debe** ser "`level`" - ¡recuerda, **las computadoras son muy literales**!


3. Ahora te han pedido que incluyas un método que enviará un string a la consola anunciando una subida de nivel.
    * Modifica la clase Player para que acepte un string de nombre de jugador y un número de nivel en dos argumentos separados.
    * Luego, define un método de objeto compartido `info()` que imprimirá el siguiente string, reemplazando los dos marcadores de posición:
        * `<nombre> has reached Level <nivel>!`
            * Un jugador llamado **Tara** en el nivel **6** debería resultar en "`Tara has reached Level 6!`" impreso en la consola.


4. Ahora te han pedido que incluyas un método para subir de nivel a un jugador, incrementando su número de nivel en uno.
    * Modifica la clase Player para que acepte un string de nombre de jugador y un número de nivel en dos argumentos separados.
    * Luego, define un método de objeto compartido `info()` que mostrará el siguiente string:
        * `<nombre> has reached Level <nivel>`!
    * Finalmente, define un segundo método de objeto compartido llamado `levelUp()` que **incrementará** el nivel del jugador.

## Tareas Extras

Si has completado las tareas anteriores, ¡intenta las siguientes tareas extras para **experimentar** más!

5. Experimenta con permitir que el jugador suba de nivel basado en puntos de experiencia ganados.
    * Un punto de experiencia es un **número**. Una subida de nivel debería ocurrir cuando un jugador gana suficientes puntos de experiencia.
    * Intenta añadir un método para permitir que un jugador gane un número dado de puntos de experiencia.
    * ¿Cuántos puntos de experiencia deberían resultar en una subida de nivel? ¿Cómo puedes mantener el registro de este número?


6. Experimenta con permitir que los objetos jugador construidos sean añadidos a un **array** de miembros del grupo.
    * ¿Cómo debería identificarse un array de miembros del grupo en tu código?
    * Intenta añadir métodos para agregar o remover objetos jugador de un grupo dado.


7. Experimenta con permitir que el jugador tenga un inventario de objetos.
    * Intenta añadir métodos para agregar o remover objetos de un inventario.
    * ¿Cómo puedes mantener el registro de la cantidad de cada objeto? ¿Qué **estructura de datos** necesitarías para esto?