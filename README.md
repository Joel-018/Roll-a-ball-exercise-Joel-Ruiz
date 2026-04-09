# Roll-a-ball - Proyecto Modificado

Este proyecto es una versión extendida del tutorial "Roll-a-ball" de Unity.

## Modificación Principal: Sistema de Parálisis del Enemigo

La principal modificación añadida a la mecánica base es un sistema de control sobre el enemigo (la caja roja):

* **Activación por Recolección**: Cada vez que el jugador recolecta **4 objetos** (PickUps), se activa automáticamente la parálisis.
* **Estado de Parálisis**: Durante **5 segundos**, el enemigo detiene su movimiento por completo y cambia su color a **azul** para dar feedback visual al jugador.
* **Interfaz**: Se muestra un mensaje en pantalla indicando que el enemigo ha sido paralizado mientras dure el efecto.
