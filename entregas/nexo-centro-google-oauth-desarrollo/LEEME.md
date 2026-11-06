# Nexo Centro 4.2.0 — integración oficial Google en desarrollo

Nueva copia independiente de 4.0.4 estable y 4.1.0 experimental. La versión estable y la demo descargada no se modifican.

Se implementa el recorrido solicitado: Conectar con Google → elegir formulario en Google Picker → seleccionar salida y copiar enlace → recoger automáticamente su evaluación. No se piden al usuario scripts, plantillas, secretos ni identificadores de proyecto.

**No es una entrega lista para instalar.** Falta el registro de aplicación de Nexo Centro en Google, que debe preparar el responsable del desarrollo, y la validación completa con Google real. Las credenciales de la aplicación no existen en este entorno. `Assets/GoogleApp.json` es un marcador vacío y la pantalla no simula una conexión disponible.

Consultar `ESTADO-GOOGLE.md`. `Compilar-DesarrolloGoogle.ps1` compila y ejecuta las pruebas de desarrollo. Los scripts de distribución e instaladores permanecen bloqueados hasta completar las verificaciones externas.
