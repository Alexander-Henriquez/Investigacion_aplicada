# Investigacion_aplicada

# ToDo List App

## Descripción

La aplicación ToDo List es una herramienta útil para gestionar tareas. Permite a los usuarios agregar, editar y eliminar tareas, manteniendo un registro organizado y accesible de sus actividades pendientes. La aplicación está desarrollada con Android Studio y Kotlin, utilizando Jetpack Compose para la interfaz de usuario y Room para la persistencia de datos.

## Características

- **Agregar Tareas**: Los usuarios pueden agregar nuevas tareas con un título y descripción.
- **Editar Tareas**: Las tareas existentes se pueden editar para actualizar su información.
- **Eliminar Tareas**: Los usuarios pueden eliminar tareas que ya no son necesarias.
- **Persistencia de Datos**: Las tareas se guardan en una base de datos SQLite, asegurando que las tareas se mantengan entre sesiones de usuario.

## Estructura del Proyecto

### Backend

- **Responsable**: Oswaldo Henriquez
- **Detalles**:
  - Configuración de la base de datos SQLite utilizando Room.
  - Implementación del DAO (Data Access Object) para las operaciones CRUD (Crear, Leer, Actualizar, Eliminar).
  - Creación del repositorio que interactúa con el DAO.
  - Implementación del ViewModel para gestionar los datos y proporcionar la lógica de negocio a la interfaz de usuario.

### Frontend

- **Responsable**: Diego
- **Detalles**:
  - Diseño e implementación de la interfaz de usuario utilizando Jetpack Compose.
  - Configuración de la navegación entre pantallas.
  - Creación de las pantallas de agregar/editar tareas y la lista de tareas.
  - Integración con el ViewModel para interactuar con los datos.
