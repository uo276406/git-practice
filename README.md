# git-practice

Ejercicio:

En la mayoría de nuestros proyectos se trabaja con 3 entornos, Producción que es el que se publica a todo el mundo, Pre-producción que es donde el cliente valida y Desarrollo que se refiere al entorno en nuestro equipo; por tanto desarrollo no es único; hay uno por cada miembro del equipo que desarrolla.

Revisa la guía de git de TCK para ver y entender el flujo de trabajo.

## 1
Crear las rama de **staging** para el entorno de pre y **integration** para controlar las puestas en producción.

## 2 corregir ortografía

Crea una rama **feature/** + el número de la tarea que vayas a acometer y un título descriptivo; en este caso podría ser por ejemplo **feature/2--fix-accents**

Arregla la página 2 ya que le faltan los acentos.

## 3 Crear una PR de la tarea 2

Crear una Pull Request de la tarea anterior y añadir a un revisor.

Las PR apuntarán a la rama de integración.

## 4 Terminar página 3

La página 3 está incompleta hay que añadir el número de página al texto.

Proceder como marca el flujo de tck; crear la feature con su nombre corregir y publicar su PR.

## 5 Añadir una línea a cada una de las tres página

Añadir una línea con el texto que quieres en las páginas 1, 2 y 3

Proceder como marca el flujo de tck; crear la feature con su nombre corregir y publicar su PR.

## 6 Mergear en staging la tarea 2

Mergear en staging la tarea 2 para que la podamos revisar

## 7 Mergear en staging las tareas 3, 4 y 5

Mergear todo en staging para revisar las tareas.

## 8 Cerrar PR'S

Cerrar todas las PR's

Si hay conflictos se deben resolver; el proceso es mergear la rama de integración en la rama de la PR, corregir el conflicto y hacer push.

## 9 Poner en producción

Mergear **integration** en **master**