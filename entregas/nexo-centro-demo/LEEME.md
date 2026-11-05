# Nexo Centro — demo con datos ficticios

[Descargar demo con datos](./NexoCentro-DEMO-con-datos.zip?raw=true). Extraer el ZIP completo y abrir `ABRIR-DEMO.cmd`. No requiere instalar ni restaurar nada: la agenda ya viene cargada. Usar ese acceso, no el ejecutable interno de Programa.

Incluye **187 eventos, 599 tareas, 37 memorias y 12 categorías**. El 5 de noviembre de 2026 muestra 16 acontecimientos; la semana del 9 al 13 tiene 56 apariciones. Hay preparativos pendientes y terminados, memorias, histórico, repeticiones, traslados y excepciones. Todo es ficticio, incluido el calendario de ejemplo.

[19 comprobaciones Windows correctas, sin fallos](https://github.com/vygos7/historia/actions/runs/42113971475), con capturas de la aplicación real como artefacto `resultados-nexo-demo`. Se comprobó restauración, tareas, memorias, integridad y carga de las vistas. La revisión final sólo añade documentación: el cliente, las pruebas y los datos son idénticos a los comprobados.

Se utiliza el cliente Nexo Centro r1 sin modificar su funcionalidad, con agenda y configuración propias dentro de la carpeta DEMO y sin conectarse a Jefatura. No se ha modificado la instalación del colegio. No cambiar la casilla de inicio automático desde la demo: ese ajuste pertenece al usuario de Windows y puede afectar al arranque de la aplicación habitual.

La copia está en `Copias/NexoCentro-DEMO-2026-11.sqlite3`. Se puede restaurar desde Copias de seguridad de una agenda **DEMO local**, sustituyendo lo que contenga esa demo. No es un archivo cifrado `.acbackup` y no debe restaurarse sobre la agenda real.
