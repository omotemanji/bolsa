BOLSALAB 0.1 — aplicación web para analizar acciones
====================================================

ARCHIVOS
- index.html: aplicación completa en un solo archivo.

CÓMO USARLA
1. Abre index.html en un navegador para probarla.
2. En Resumen, pulsa “Cargar ejemplos de demostración” para probar la interfaz. Son datos ficticios.
3. Añade tus acciones en “Analizador” e introduce los datos fundamentales.
4. En “Comparador”, selecciona hasta cuatro acciones.
5. En “Histórico”, guarda cierres históricos por fecha.
6. Exporta copias JSON periódicamente para conservar tus datos.

COTIZACIONES AUTOMÁTICAS
- En “Datos y ajustes”, introduce tu clave de Twelve Data.
- Guarda la clave y elige una acción para actualizar su cotización.
- El ticker debe coincidir con el formato admitido por el proveedor.
- La cotización automática necesita conexión a Internet y puede estar sujeta a límites del plan/API.
- La clave se almacena en el navegador del dispositivo. No compartas el archivo exportado si contiene información que quieras mantener privada.

PUBLICAR EN GITHUB PAGES
1. En GitHub, abre el repositorio que quieras utilizar.
2. Sube index.html a la raíz del repositorio (puedes renombrar el archivo a index.html).
3. En Settings → Pages, configura la publicación desde la rama principal y la carpeta raíz.
4. Abre la URL de Pages desde Safari o Chrome. Para instalarla como icono, utiliza la opción “Añadir a pantalla de inicio” del navegador compatible.

LIMITACIONES DE ESTA VERSIÓN
- Los fundamentales se introducen manualmente.
- La puntuación es orientativa, usa umbrales genéricos y no está ajustada al sector.
- No incluye todavía DCF completo, sincronización en la nube ni descarga automática de históricos/fundamentales.
- Los datos se guardan localmente por navegador; usa Exportar datos para hacer copias.
- No constituye asesoramiento financiero.
