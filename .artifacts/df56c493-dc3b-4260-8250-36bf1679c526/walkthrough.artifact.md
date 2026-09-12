# Resumen de Implementación: Dashboard del Asistente UPC

Se ha desarrollado el panel principal (Dashboard) de la aplicación, proporcionando un punto central de interacción para el usuario.

## Pantallas Desarrolladas

1.  **Bienvenida**: Puerta de entrada.
2.  **Inicio de Sesión**: Acceso seguro.
3.  **Dashboard (Inicio)**: Panel de control con acceso rápido.
4.  **Chat del Asistente**: Interacción directa por IA.
5.  **Registro y Recuperación**: Flujos de gestión de cuenta.

## Detalles de la Pantalla de Inicio (HomeScreen)

- **Saludo Personalizado**: Cabecera dinámica "Hola, Valentina 👋".
- **Tarjeta de Asistente**: Un componente destacado que muestra el estado del bot y una breve descripción de sus capacidades.
- **Preguntas Sugeridas (Chips)**: Una rejilla de botones interactivos con iconos representativos para facilitar el acceso a temas comunes (Horarios, Matrículas, etc.).
- **Barra de Búsqueda Estilizada**: Un campo de entrada con esquinas muy redondeadas y botón de acción directa.
- **Navegación Inferior**: Implementación de `NavigationBar` con iconos personalizados para Inicio, Chats, Avisos y Perfil.

## Flujo de Navegación Actualizado

- Al pulsar **"Iniciar sesión"** en el login, el usuario es dirigido al **Dashboard**.
- Al interactuar con la **Tarjeta del Asistente** en el Dashboard, se abre la pantalla de **Chat**.

## Resultado Visual

La aplicación ahora tiene una estructura completa y profesional, siguiendo los estándares de diseño de Material 3 y la identidad visual de la UPC.

![Vista Previa Dashboard](C:/Users/sebas/AndroidStudioProjects/ChatBot/app/src/main/java/com/example/chatbot/HomeScreen.kt)
