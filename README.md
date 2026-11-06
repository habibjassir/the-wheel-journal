# The Wheel Journal

Bitácora local para la estrategia de opciones *The Wheel*: put vendido → asignación → call cubierto → called away.

Hecha por [habibjassir](https://github.com/habibjassir).

Calcula el **costo ajustado real** de tus acciones descontando las primas cobradas, y organiza tus operaciones en ciclos que acumulan primas hasta que tú decides cerrarlos.

## Descargar

Ve a **[Releases](../../releases/latest)** y descarga el instalador de la última versión:

- `TheWheelJournal_X.Y.Z_x64-setup.exe`: **recomendado**. Se instala solo para tu usuario y no pide permisos de administrador.
- `TheWheelJournal_X.Y.Z_x64.msi`: alternativa para instalar en todo el equipo. Pide permisos de administrador.

Requisitos: Windows 10 u 11 de 64 bits.

Los instaladores no están firmados, así que Windows puede mostrar un aviso de SmartScreen. Para continuar, elige "Más información" → "Ejecutar de todas formas". Cada versión incluye `SHA256SUMS.txt` para comprobar que el archivo no se alteró:

```powershell
Get-FileHash .\TheWheelJournal_X.Y.Z_x64-setup.exe -Algorithm SHA256
```

## Qué hace

- **Registra cada operación de la rueda:** venta de puts y calls, asignación, vencimiento, called away, roll, cierre anticipado y compra o venta de acciones, con una vista previa antes de guardar.
- **Calcula por ciclo:** costo ajustado, punto de equilibrio, prima acumulada, ganancia máxima y rendimiento anualizado.
- **Muestra tu capital** disponible y comprometido, y tus resultados del mes, del año o de todo el historial.
- **Lleva una bitácora** con calendario, motivo y ánimo de cada operación. Puedes editar o eliminar movimientos.
- **Permite importar y exportar** tus datos en CSV, con revisión antes de guardar y opción de deshacer.
- **Tiene tres temas visuales:** Luna de jardín, Anillos y Órbita.

## Tus datos

- **Solo en tu equipo:** viven en `%APPDATA%\app.thewheeljournal`. La app no tiene servidor ni envía nada a internet.
- **Copias de respaldo:** se hace una al día al abrir la app (se guardan las 10 más recientes), y también puedes crear y restaurar copias desde Ajustes.
- **Al desinstalar:** tus datos se conservan.

## Licencia

Uso gratuito para fines personales, según [LICENSE.md](LICENSE.md). La app **no es asesoría financiera**: los cálculos son orientativos. Las licencias de los componentes de terceros están en `THIRD-PARTY-NOTICES.txt`, que se publica con cada versión y también se puede ver en la app, en Ajustes → Acerca de.

## Cambios

Cada versión en [Releases](../../releases) explica qué cambió.
