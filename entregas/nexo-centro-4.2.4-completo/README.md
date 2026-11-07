# Nexo Centro 4.2.4 · Importación de calendario PDF

**Entrega completa. 678 comprobaciones correctas en Windows; 0 fallos.**

Para probar sin modificar la agenda real, extrae el ZIP y abre **ABRIR-DEMO.cmd**. Usa datos ficticios y un perfil independiente.

En Ajustes → Calendario escolar → Importar calendario desde PDF, elige el archivo, selecciona la etapa y revisa las fechas. Usar estas fechas solo carga un borrador. Completa los festivos municipales y confirma Guardar calendario. Se crea una copia del calendario anterior, recuperable desde el mismo editor.

Primera compatibilidad: formato del calendario provincial de Granada comprobado con el PDF 2026/27. No hace OCR ni interpreta automáticamente otros diseños/provincias. Primer ciclo de Infantil y Deportivas se configuran manualmente. Los trimestres propuestos se identifican como tales.

- Centro ya configurado: actualizar únicamente con Instalar-NexoCentro-Cliente.exe y su .exe.config. No reinstalar el servidor.
- Centro nuevo: instalar primero el servidor y después los clientes personalizados que ese servidor genere.

[Manual PDF de 8 páginas](MANUAL-INSTALACION.pdf). [Pruebas Windows](https://github.com/vygos7/historia/actions/runs/42400995326).

Se conservan las versiones anteriores y el código de red, servidor y almacenamiento. No se ha accedido a la instalación real del colegio.
