# Buenas Prácticas para escribir Commits
**Versión:** 0.0.1
**Autores:** Equipo de Desarrollo
**Objetivo:** Definir y comunicar las mejores prácticas para escribir commits con el fin de mejorar la claridad, la trazabilidad y la colaboración en el desarrollo de software. Este documento tiene como objetivo establecer pautas que faciliten la comprensión del historial de cambios, la identificación de problemas y la colaboración efectiva entre los miembros del equipo.

------------------------------------------------------------------------
1. **Usa el verbo imperativo** (Add, Change, Fix, Remove, …)
El verbo presente es una forma de expresar la acción que se realiza en el commit. Por ejemplo, _Add_ significa que se añade un nuevo archivo, _Change_ significa que se modifica un archivo existente y _Fix_ significa que se arregla un bug.

2. **No uses punto final ni puntos suspensivos en tus mensajes**
Usar puntuación, más allá de las comas, es innecesario a la hora de crear un buen mensaje de commit. Cada carácter cuenta a la hora de crear un buen mensaje de commit así que no lo desperdicies con puntos innecesarios.

![image.png](/.attachments/image-62ca420b-d577-45ad-af93-0e77e75a8f17.png)


3. **Usa como máximo 50 carácteres para tu mensaje de commit**
Sé corto y conciso. Si tienes mucho que explicar seguramente es que tu commit hace demasiadas cosas. Puedes separarlo en diferentes commits. 
Haz que el mensaje sea claro, directo y que realmente refleje los cambios que lleva.

![image.png](/.attachments/image-6a45ce25-cfc0-48fa-a933-78b0d87daff8.png)

4. **Añade todo el contexto que sea necesario en el cuerpo del mensaje de commit**
A veces necesitas proveer de más contexto a tu commit. Para ello, en lugar de saturar el sumario del commit, añade información que sea necesaria en el cuerpo del mensaje. 
Puedes lograrlo usando `git commit -m "Add summary of commit" -m "This is a message to add more context."` 


5. **Usa un prefijo para tus commits para hacerlos más semánticos**
Cuando un proyecto crece, es necesario que existan ciertas reglas para que el historial sea legible. Para ello, puedes añadir un prefijo para darle más significado a los commits que realizas. Por ejemplo:

![image.png](/.attachments/image-793d494a-f077-488f-9abe-8835c521509f.png)
![image.png](/.attachments/image-ba9b0825-b502-4418-b298-0d2c34a35d75.png)

**Estos serían los prefijos:**

| Prefijo| Descripción |
|--|--|
| feat | Una nueva característica para el usuario. |
| edit | Editar o mejorar una característica. |
| fix | Arregla un bug que afecta al usuario. |
| perf | Cambios que mejoran el rendimiento del sitio |
| build | Cambios en el sistema de build, tareas de despliegue o instalación. |
| ci | Cambios en la integración continua. |
| docs |  Cambios en la documentación. |
| refactor|  Refactorización del código como cambios de nombre de variables o funciones.|
| style | Cambios de formato, tabulaciones, espacios o puntos y coma, etc; no afectan al usuario. |
| test | Añade tests o refactoriza uno existente.|
| chore | Confirmaciones varias, p. modificando .gitignore |

