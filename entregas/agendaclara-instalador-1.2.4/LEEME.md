# AgendaClara 4.0.4 — instalador completo 1.2.4

[Descargar el ZIP completo](./AgendaClara-4.0.4-instalador-completo-1.2.4.zip?raw=true). Descomprimir y leer `LEEME-PRIMERO.txt` e `INFORME-INSTALADOR-COMPLETO.md`.

Incorpora exactamente el cliente r2 comprobado entre Dirección y Jefatura. No contiene claves, identidades ni datos de centros.

- Centro nuevo: ejecutar `Instalar-AgendaClara-Servidor.exe` en su servidor; el asistente genera los instaladores específicos de los puestos.
- Puesto existente: `Instalar-AgendaClara-Cliente.exe` actualiza el programa conservando la conexión.
- El colegio que ya funciona con r2 no necesita reinstalar el servidor por esta entrega.

Cinco baterías Windows correctas en [esta ejecución](https://github.com/vygos7/historia/actions/runs/42090238340) y [la siguiente](https://github.com/vygos7/historia/actions/runs/42090975117), que incluye tres recuperaciones consecutivas. Los EXE se identifican con SHA-256 en `compilacion.json`; el ZIP tiene su propio `SHA256SUMS.txt`.

**Distribución para piloto por centro.** Falta verificar su red, permisos y sistemas reales. Una ejecución intermedia devolvió HTTP 503 al acceder tras una reversión; su causa no está demostrada y no se repitió en cuatro recuperaciones posteriores. El informe incluido explica este límite y el diagnóstico añadido. No se considera certificada la actualización masiva de servidores. Probar dos puestos y conservar copia externa y clave de recuperación separada antes de extender la instalación.

La regla local incluye Dominio, Privado y Público, limitada al programa, puerto y redes indicadas. Routers, VLAN, políticas corporativas, nombre/IP estable y copias externas requieren preparación propia del centro. Los EXE carecen de firma Authenticode.

La validación automatizada usa únicamente Windows efímero de GitHub y permisos de repositorio de sólo lectura. No ejecutar las baterías de prueba sobre el colegio.
