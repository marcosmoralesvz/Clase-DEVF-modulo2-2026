🚐 Transportadora Turística Zentido

 es una página web moderna y minimalista diseñada para facilitar la reserva de servicios de transporte turístico. El proyecto cuenta con una interfaz de pantalla dividida (*split-screen*) y un sistema de captura de datos conectado directamente a Google Sheets.

Características

Diseño Split-Screen: Una mitad enfocada en la identidad visual y la otra en la conversión (formulario).
Conexión con Google Sheets: Utiliza la API de [Sheet.best](https://sheet.best/) para almacenar las reservas en una hoja de cálculo en tiempo real sin necesidad de un backend complejo.
Validación de Datos: Formulario con campos obligatorios y validación de formato de correo.
Interfaz Interactiva: Mensaje de confirmación dinámico tras el envío mediante JavaScript (Fetch API).

Requisitos para Réplica

Si deseas clonar este proyecto y usarlo con tu propia base de datos:

1. Crea una hoja de cálculo en **Google Sheets** con los encabezados: `nombre`, `email`, `destino`, `comentarios`.
2. Vincula la hoja en [Sheet.best](https://sheet.best/) para obtener tu propia URL de API.
3. Reemplaza la URL en la función `fetch()` dentro del archivo `index.html`.
