# Implementación de Pantalla de Inicio "Asistente UPC"

Este plan detalla los pasos para crear la pantalla de inicio (Dashboard) utilizando Jetpack Compose, siguiendo el diseño de la sexta imagen proporcionada.

## Cambios Propuestos

### Interfaz de Usuario (Compose)

#### [NEW] [HomeScreen.kt](file:///C:/Users/sebas/AndroidStudioProjects/ChatBot/app/src/main/java/com/example/chatbot/HomeScreen.kt)
Implementar la pantalla de inicio:
- **Cabecera**: Saludo personalizado "Hola, Valentina 👋" y subtítulo.
- **Tarjeta del Asistente**:
    - Imagen de perfil, nombre y estado "En línea".
    - Icono de IA (destello).
    - Texto descriptivo de ayuda.
- **Sección de Preguntas Sugeridas**:
    - Título "Preguntas sugeridas".
    - Rejilla/Lista de botones (Chips) con iconos: Información académica, Horarios, Calendario, Matrículas, Reglamento estudiantil.
- **Barra de Búsqueda**: Campo de texto estilizado "Escribe tu pregunta...".
- **Barra de Navegación Inferior**: Iconos y etiquetas para "Inicio", "Chats", "Avisos" y "Perfil".

#### [MODIFY] [MainActivity.kt](file:///C:/Users/sebas/AndroidStudioProjects/ChatBot/app/src/main/java/com/example/chatbot/MainActivity.kt)
- Añadir el estado `home` a la lógica de navegación.
- Actualizar `onLoginSuccess` para navegar a `home`.
- Configurar la navegación desde `home` hacia `chat` al interactuar con el asistente.

## Plan de Verificación

### Verificación Manual
- Validar el diseño visual de la tarjeta y los chips sugeridos.
- Comprobar que la barra de navegación inferior se muestre correctamente.
- Verificar la transición fluida entre Login -> Inicio -> Chat.
