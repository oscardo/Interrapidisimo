# Prueba Interrapidísimo

**Creada por:** Oscar Eduardo Ortiz Pinzón  
**Fecha de entrega:** 11 de mayo de 2025 - 11:26 p.m.

## Tecnologías utilizadas

- **Base de datos:** SQL Server Express 2022  
- **Back End:** .NET 8 (Framework Core) con C# en Visual Studio 2022 Community Edition  
- **Front End:** Angular 19  

---

## Estructura del Proyecto

| Imagen                 | Explicación |
|------------------------|------------|
| Formulario de usuario  | **Base de datos**: Una base de datos en SQL Server es un conjunto estructurado de datos almacenados y gestionados por el motor de Microsoft. Permite definir tablas, relaciones, consultas, procedimientos y transacciones con integridad y rendimiento. |
| Formulario de usuario  | **Backend (Visual Studio .NET 8)**: Una REST API creada con .NET 8 permite definir controladores con endpoints HTTP (GET, POST, PUT, DELETE) y usar EF Core 8 para interactuar con SQL Server. Visual Studio 2022 proporciona herramientas integradas para prueba y depuración. |
| Formulario de usuario  | **Backend (REST API)**: Servicio web que permite la comunicación entre aplicaciones usando métodos HTTP. Facilita la separación del frontend y backend, ideal para aplicaciones web y móviles escalables. |
| Formulario de usuario  | **Swagger**: Al ejecutar la API en Visual Studio (F5 o Ctrl+F5), se abre Swagger UI automáticamente en el navegador (ej. `https://localhost:7233/swagger`), permitiendo explorar y probar los endpoints disponibles. |
| Formulario de usuario  | **Frontend General**: Aplicación Angular (localhost:4200) donde el estudiante se registra, selecciona materias, ve profesores (sin repetir), y compañeros de clase. Incluye formularios validados y navegación fluida. |
| program.component.html | Define la interfaz para registrar o editar un programa. Permite ingresar título, descripción, fecha y duración. Vincula al modelo con `[(ngModel)]`, y envía datos al backend. Incluye botón de cancelar y reiniciar. |
| student.component.html | Formulario para registrar estudiantes. Permite ingresar datos, seleccionar 3 materias, y ver compañeros. Usa `[(ngModel)]` y se conecta al backend. Incluye opción de reinicio. |
| professor.component.html | Permite registrar profesores y asignarles hasta 2 materias. Usa `[(ngModel)]`, y ofrece editar, eliminar o reiniciar. |
| materias.component.html | Gestiona el registro y visualización de materias. Permite asociarlas con profesores y mostrar relación con créditos y docentes. |
| Módulo profesor-materia | Administra la relación entre profesores y materias. Garantiza que un profesor tenga máximo dos asignaciones sin duplicar. Facilita edición y consulta. |
| Módulo estudiante-materia | Permite que un estudiante escoja hasta 3 materias sin repetir profesor. Valida reglas de inscripción y muestra compañeros por clase. |
| Módulo de roles         | Define los niveles de acceso (admin, profesor, estudiante). Controla qué puede hacer cada tipo de usuario. Garantiza seguridad y personalización. |
| Módulo de usuarios      | Gestiona el registro, edición y acceso de los usuarios. Asigna roles, valida sesiones y mantiene perfiles seguros y únicos. |

---

## Contacto

- **LinkedIn:** [Oscar Eduardo Ortiz Pinzon]([https://www.linkedin.com/in/](https://www.linkedin.com/in/oscardo2000/))
- **Página web:** [Oscar Ortiz](https://oscardo.github.io/) <!-- reemplaza con tu URL real -->
- **Correo electrónico:** [oscardo2000@gmail.com](mailto:oscardo2000@gmail.com)
- **Teléfono:** [Llamar al: +57 300 464 XXXX](tel:+573004642976)
- **WhatsApp:** [Escríbeme por WhatsApp](https://wa.me/573004642976)


