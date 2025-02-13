# Conciertos Conectados

## Descripción General
Este proyecto consiste en el desarrollo de una aplicación de eventos de música que permite a los usuarios explorar, comprar y gestionar entradas para diversos conciertos y eventos musicales. La plataforma ofrecerá una experiencia intuitiva y enriquecedora, facilitando la búsqueda de eventos según categorías, así como el acceso a información detallada sobre cada evento.

## Funcionalidades Principales

### 1. Página de Inicio:
- Buscador: Permite a los usuarios buscar eventos específicos o similares.
- Menú de Categorías: Ofrece diversas categorías como conciertos de música, exhibiciones, espectáculos de pie y teatro, etc.
- Eventos de Tendencia: Muestra eventos populares con cards que incluyen imágenes, nombre de la banda, título del evento, lugar, fecha y precio.
- Eventos Cerca de Usted: Muestra eventos relevantes en la proximidad del usuario, utilizando información de ubicación.

### 2. Página de Detalles:
- Cards de Presentación: Incluye imagen del evento, nombre de la banda, título del evento, lugar, fecha y la cantidad de asistentes adquieros de los usuarios (con fotos de perfil).
- Descripción: Proporciona información detallada sobre el evento, con un botón "ver más" que despliega un diálogo con información adicional si es necesario.
- Valor y Localización: muestra la ubicación del evento, presenta el precio de la entrada y un botón para realizar la compra.

### 3. Página de Compra de Boleta:
- Card de Evento: Muestra una imagen del evento (diferente de la de presentación) junto con información del artista, título del evento, código de boleta, puerta, silla, fecha, hora y código de barras para facilitar el acceso al evento.

## Instrucciones de uso:
- Requiere la instalacion de un navegador como Google Crome o similares.

## Implementación:
- Uso de GitHub para trabajo Organizado.
- Uso de Conventional Commits + CommitsMoji para mayor entendimienot y organizacion de trabajo.

## Tecnologías Utilizadas
- **Frontend**: CSS
- **Backend**: HTML
- **Maquetacion**: Figma -> https://www.figma.com/community/file/1243768936820156796

## Estructura de Carpetas:

CONCIERTOS-CONECTADOS/
├── storage/
│   ├── font-Detail/
│   ├── font-index/
│   ├── font-Tickets/
│   ├── img-Detail/
│   ├── img-index/
│   ├── img-Tickets/
├── style/
│   ├── style-Detail.css
│   ├── style-index.css
│   ├── style-Tickets.css
│   ├── variables-Detail.css
│   ├── variables-index.css
│   ├── variables-Tickets.css
├── views/
│   ├── Detail.html
│   ├── Tickets.html
├── index.html
├── README.md

## Resultado esperado
- Funcionalidades y Fluidez: La aplicación debe ser completamente navegable y responsiva, con un diseño visual atractivo y consistente. Las secciones principales deben permitir al usuario buscar (simulado con redirecciones) eventos, ver detalles, y realizar la compra de entradas sin problemas.
- Código Limpio y Organizado: Estructura clara del proyecto (carpetas), con código bien comentado y fácil de entender, siguiendo buenas prácticas de HTML, CSS y JavaScript. La lógica debe estar bien modularizada.
- Uso de GitHub con Conventional Commits: Buen manejo de versiones en GitHub, con mensajes de commit claros y descriptivos, siguiendo convenciones.
- Documentación Completa: Un Readme.md detallado que incluya descripción del proyecto, instrucciones de uso e implementación, y tecnologías empleadas.

## Futuras Mejoras
- Integración de Lenguaje javascript.
- Integración de Bases de Datos.