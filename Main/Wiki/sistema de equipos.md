## Sistema de Equipos

- Con el propósito de tener una mejor organización con respecto a los posibles "grupos" que se den dentro de un "Mundo" o "Servidor", se añade un **"Sistema de Equipos"**. Para llevar a cabo su funcionamiento, el administrador del mundo deberá seguir los siguientes pasos:

---

### Creación de un Equipo (Proceso Automático)

- Entrar al behavior pack del día 1 *(ya que solamente en los días 1-4 se puede llevar a cabo este proceso de forma que este mismo sea "automático"),* más específicamente, a `_valley dimesional dia 1\scripts` y ejectuar el archivo `main.js`.

- En la línea número 8 del `main.js` aparecerá la plantilla para crear los equipos, solo basta con modificar los valores mostrados de forma que coincidan con los nombres de los integrantes que quieras añadir al equipo y el nombre que le quieras dar al equipo como tal. El ejemplo de la plantilla se muestra a continuación:

![plantilla_equipos](https://github.com/MiguelVeraXd/Valley-Dimensional-Wiki/blob/main/Main/Wiki/assets/crafteo/plantilla_equipos.png)

*__IMPORTANTE:__ Solo se puede tener un máximo de 10 personas en un mismo equipo.*

- Por último, una vez estén creados los equipos y se hayan guardado los cambios dentro del archivo, se debe ejecutar el comando `/reload` dentro del "Mundo / Servidor" para que el código ya modificado funcione correctamente.

***De esta forma, cada vez que un jugador entre al "Mundo / Servidor", la respectiva "tag" le será asignada automáticamente.***

---

### Creación de un Equipo (Proceso Manual)

- Ahora bien, si se quieren crear equipos en días diferentes al 1-4 y/o se quiere llevar a cabo este proceso sin la necesidad de entrar a los archivos del Add-On, el proceso será manual, con la colocación de una "tag" mediante el comando: `/tag @*nametag del jugador* add m:*nombre del team*`. 

***Lo mismo se tendrá que hacer si un jugador no se conectó en los días 1-4, en estos casos, el sistema automático no le debió haber dado la tag correspondiente, y se tendrá que realizar el comando para ese jugador en específico.***

---
 
### Cambio de un Equipo

- Para mover a una persona de un equipo a otro, se deberá ejecutar la siguiente serie de comandos: `/tag @*nametag del jugador* remove m:*nombre del team al cual ya no forma parte*` y `/tag @*nametag del jugador* add m:*nombre del nuevo team*`.
