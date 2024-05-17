# Desafío Frontend React

¡Bienvenido al desafío frontend Monbak.

Este desafío está diseñado para evaluar tus conocimientos en React, Redux y Bootstrap. A continuación, encontrarás los requisitos y pasos para completar el desafío.

## Requisitos

1. **React**: Deberás crear componentes funcionales y utilizar hooks cuando sea necesario.
2. **Redux**: Necesitarás configurar un store, crear reducers y actions, y conectar tu aplicación a Redux.
3. **Bootstrap**: Utilizar Bootstrap para el diseño y estilización de tu aplicación siguiendo el ui kit disponible en el directorio `demo/ui`.

## Desafío: Lista de Tareas (To-Do List)

### Objetivo

Desarrollar una aplicación de lista de tareas (To-Do List) donde los usuarios puedan:

- Agregar nuevas tareas.
- Marcar tareas como completadas.
- Actualizar tareas.
- Eliminar tareas.

### Instrucciones

1. **Configuración Inicial**:

   - Inicializa un proyecto de React.
   - Configura Redux en tu proyecto.
   - Instala Bootstrap en tu proyecto.

2. **Componentes**:

   - Crea un componente `TaskList` que muestre la lista de tareas.
   - Crea un componente `TaskItem` para cada tarea individual.
   - Crea un componente `TaskForm` para agregar nuevas tareas.
   - Si lo consideras necesario, puedes crear otros componentes adicionales.

3. **Redux**:

   - Configura un store con un reducer para manejar las tareas.
   - Define actions para agregar, completar, actualizar y eliminar tareas.
   - Conecta los componentes de React con Redux para manejar el estado de las tareas.
   - Utiliza `redux-thunk` para manejar acciones asíncronas.
   - Haz que las tareas se guarden en el `localStorage` para que persistan al recargar la página usando `redux-persist`.

4. **Estilización**:
   - Usa Bootstrap para diseñar y estilizar tu aplicación.
   - Asegúrate de que la aplicación sea responsiva y amigable para el usuario siguiendo el ui kit disponible en el directorio `demo/ui`.
   - Asegurate de usar la fuente `Lato` disponible en `demo/ui/fonts`.
   - Respeta el flujo del usuario explicado en el video `demo/ui/UI-Task-Demo.mp4`.

### Detalles Técnicos

- **TaskForm**:
  - Un campo de entrada para el nombre de la tarea.
  - Un button group para seleccionar la prioridad de la tarea.
  - Un botón para agregar la tarea.
  - Un botón para limpiar el campo de entrada.
  - Componente deber ser un modal a nivel general y no un modal por tarea.
- **TaskList**: (Main Screen)
  - Muestra todas las tareas actuales.
  - Muestra la fecha actual.
  - Muestra un filtro para seleccionar todas las tareas, tareas completadas y tareas pendientes.
  - Debe mostrar un mensaje si no hay tareas.
- **TaskItem**:
  - Muestra el nombre de la tarea.
  - Muestra la prioridad de la tarea.
  - Un checkbox para marcarla como completada.
  - Un botón para eliminarla.
  - Cada tarea debe capturar un click (de preferencia sobre el nombre de la tarea) para editar la tarea.
  - Si la tarea está completada, debe mostrarse con un estilo tachado.

### Bonus

- Agrega pruebas unitarias a tus componentes y acciones.

### Entrega

1. Crea un repositorio en GitHub y sube tu solución.
2. Envía el enlace del repositorio junto con cualquier comentario adicional que quieras hacer sobre tu solución y como ejecutarla.

### Recursos

- [Documentación de React](https://react.dev)
- [Documentación de Redux](https://redux.js.org/introduction/getting-started)
- [Documentación de Bootstrap](https://getbootstrap.com/docs/5.3/getting-started/introduction/)

## ¡Buena suerte!

**Nota**: Este desafío está diseñado para ser completado en una semana (7 días). No dudes en pedir información si algo no está claro.
