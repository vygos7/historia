# Nexo Centro 4.0.4 — interfaz r1

[Descargar Nexo Centro](./NexoCentro-4.0.4-interfaz-r1.zip?raw=true). Descomprimir y leer `LEEME-PRIMERO.txt` e `INFORME-NEXO-CENTRO.md`.

**Versión de prueba con ocho baterías Windows correctas: 552 comprobaciones, 0 fallos.** [Resultados y capturas reales de WPF](https://github.com/vygos7/historia/actions/runs/42106266327). La revisión final sólo añade documentación; los ejecutables y pruebas permanecen idénticos a los validados.

Nueva marca Nexo Centro, calendario despejado y vista diaria agrupada, sin lista lateral permanente de colores. Ajustes conserva categorías, calendario escolar, copias, conexión y resumen de hoy. Se mantienen todas las funciones anteriores.

Se conservan exactamente 18 archivos de lógica, 27 bibliotecas externas y el payload completo del servidor validado. Los identificadores internos antiguos se mantienen para reconocer datos y accesos existentes. El ZIP incluye las evidencias y los archivos modificados.

**Puesto ya configurado:** cerrar la aplicación y ejecutar `Instalar-NexoCentro-Cliente.exe` con el usuario habitual. No reinstalar el servidor para probar la interfaz.

**Centro nuevo:** usar `Instalar-NexoCentro-Servidor.exe`, que genera los instaladores Nexo Centro de cada puesto. Revisar la configuración de red propia del centro.

No se ha modificado la instalación del colegio. Falta revisar esta interfaz en sus equipos reales: comprobar apariencia, creación, edición y borrado sincronizados entre dos puestos antes de extenderla. Los EXE no están firmados con Authenticode. No ejecutar las baterías Pruebas sobre el colegio.
