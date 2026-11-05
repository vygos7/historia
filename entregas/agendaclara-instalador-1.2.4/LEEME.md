# AgendaClara 4.0.4 — instalador completo 1.2.4 en validación

**NO DISTRIBUIR hasta validar esta revisión.**

La ejecución [42092628799](https://github.com/vygos7/historia/actions/runs/42092628799) demostró la causa del HTTP 503 posterior a una reversión: `File.Replace` fallaba al guardar `security.json` durante la autenticación (HRESULT `80070497`). Esta revisión sustituye esa operación por renombración atómica con conservación explícita de permisos. Se comprueban DACL, archivo bloqueado, temporales y seis recuperaciones consecutivas.

El ZIP incluye el informe y los requisitos de cada centro. El cliente r2 que ya funciona en el colegio se conserva idéntico; no reinstalar su servidor por esta entrega. Las pruebas se ejecutan únicamente en Windows efímero con datos sintéticos.
