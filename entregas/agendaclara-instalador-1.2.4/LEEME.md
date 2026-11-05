# AgendaClara 4.0.4 — instalador completo 1.2.4

[Descargar ZIP completo](./AgendaClara-4.0.4-instalador-completo-1.2.4.zip?raw=true). Descomprimir y leer `LEEME-PRIMERO.txt` e `INFORME-INSTALADOR-COMPLETO.md`.

**Preparado para un piloto por centro.** Las cinco baterías Windows pasaron en [42095457502](https://github.com/vygos7/historia/actions/runs/42095457502), incluidas pruebas de permisos y seis recuperaciones consecutivas. La revisión posterior sólo incorpora documentación: ejecutables y pruebas permanecen idénticos y se verifican por SHA-256.

Se corrigió el fallo reproducido al guardar sesiones tras una reversión (`File.Replace`, HRESULT `80070497`), conservando la escritura atómica y los permisos. El cliente r2 verificado entre Dirección y Jefatura se mantiene idéntico.

- Centro nuevo: ejecutar `Instalar-AgendaClara-Servidor.exe` como administrador en su servidor. El asistente genera instaladores de puestos con identidades propias del centro.
- Puesto existente: `Instalar-AgendaClara-Cliente.exe` actualiza el programa conservando la conexión.
- El colegio que ya funciona con r2 no necesita reinstalar el servidor por esta entrega.

Cada centro debe revisar nombre/IP estable, red IPv4, puerto y subredes autorizadas, políticas y routers, Windows compatible, .NET Framework 4.8 y copias externas con clave separada. La regla local incluye Dominio, Privado y Público, limitada al programa, puerto y redes indicadas. No se desactiva IPv6 ni la validación TLS.

Antes de extenderlo, validar dos puestos: conectar, crear y borrar un acontecimiento y comprobar la propagación y el reinicio. El instalador completo no se ha ejecutado aún en una red escolar real ni se han certificado todas las versiones de Windows. Los EXE carecen de firma Authenticode; respetar la política del centro.

El ZIP incluye requisitos, instrucciones, causas, archivos modificados y evidencias. Las pruebas se ejecutaron exclusivamente en Windows efímero de GitHub con datos sintéticos y permisos de repositorio de sólo lectura. No ejecutar las baterías de prueba en el colegio.
