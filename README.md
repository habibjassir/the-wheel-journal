# The Wheel Journal

*[Read in English](README.en.md)*

Bitácora local para la estrategia de opciones *The Wheel*: put vendido → asignación → call cubierto → called away.

Hecha por [habibjassir](https://github.com/habibjassir).

Calcula el **costo ajustado real** de tus acciones descontando las primas cobradas, y organiza tus operaciones en ciclos que acumulan primas hasta que tú decides cerrarlos.

## Descargar

Instálala desde la **[Microsoft Store](https://apps.microsoft.com/detail/9NFB586L8CS5)**. Es gratis, viene firmada por Microsoft y se actualiza sola.

Requisitos: Windows 10 (versión 1809 o posterior) u 11, de 64 bits.

Si instalaste una versión anterior con un instalador `.exe` o `.msi` (hasta la 0.4.0), ya no recibe actualizaciones. Instala la versión de la Store: encuentra tus datos sola. Después desinstala la anterior. Por si acaso, exporta un CSV (Ajustes → Datos) o guarda una copia de respaldo antes.

## Qué hace

- **Registra cada operación de la rueda:** venta de puts y calls, asignación, vencimiento, called away, roll, cierre anticipado y compra o venta de acciones, con una vista previa antes de guardar.
- **Calcula por ciclo:** costo ajustado, punto de equilibrio, prima acumulada, ganancia máxima, rendimiento anualizado y cuánto llevas ganado o perdido.
- **Consulta precios de mercado:** muestra cómo vas con el precio de hoy, la distancia al strike de cada opción y los dividendos. La pantalla Posiciones reúne tus acciones y contratos con el precio actualizado cada minuto.
- **Muestra tu capital** disponible y comprometido, y tus resultados del mes, del año o de todo el historial.
- **Te avisa de los vencimientos** semana a semana, con el colateral que libera cada una.
- **Lleva una bitácora** con calendario, motivo, ánimo y etiquetas de cada operación. Puedes editar o eliminar movimientos, incluido un roll completo.
- **Permite importar y exportar** tus datos en CSV, con revisión antes de guardar y opción de deshacer. También importa la exportación de actividad de Wealthsimple.
- **Está en español y en inglés**, y tiene tres temas visuales: Luna de jardín, Anillos y Órbita.

## Tus datos

- **Solo en tu equipo:** la app no tiene servidor ni cuentas. Solo se conecta a internet para consultar en Yahoo Finance precios públicos de tus tickers y de tres índices bursátiles (envía los símbolos, nada más), y se puede apagar en Ajustes.
- **Copias de respaldo:** se hace una al día al abrir la app (se guardan las 10 más recientes), y también puedes crear y restaurar copias desde Ajustes.
- **Al desinstalar:** Windows borra los datos de la app. Si quieres conservarlos, exporta un CSV o guarda una copia de respaldo antes.

## Privacidad

La app no recopila datos personales. Detalle en [PRIVACIDAD.md](PRIVACIDAD.md).

## Reportar un error o sugerir una idea

Abre un [issue](../../issues/new/choose) con la plantilla que corresponda. Lo que escribas ahí es público: no compartas datos de tu cuenta, nombres de broker, montos reales ni capturas con información personal.

The Wheel Journal es un proyecto personal: leo todos los reportes y respondo cuando puedo.

## Licencia

Uso gratuito para fines personales, según [LICENSE.md](LICENSE.md) ([LICENSE.en.md](LICENSE.en.md) en inglés). La app **no es asesoría financiera**: los cálculos son orientativos. Las licencias de los componentes de terceros se pueden ver en la app, en Ajustes → Acerca de.

## Cambios

Cada versión en [Releases](../../releases) explica qué cambió. Ahí solo van las notas: la app se instala y se actualiza desde la Store.
