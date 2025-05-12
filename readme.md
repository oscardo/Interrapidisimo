# Oscar Eduardo Ortiz Pinzón

**Full Stack | Desarrollador de Software**  
Bogotá - Colombia  
📞 (+57) 3004642976  
📧 oscardo2000@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/oscardo2000)

---

## Perfil Profesional

Desarrollador de Software con 18 años de experiencia en diferentes tecnologías. Actualmente enfocado en el ecosistema Microsoft .NET para mejorar, automatizar y optimizar procesos técnicos, operativos y administrativos. Profesional integral, proactivo, responsable y comprometido con metas desafiantes en el diseño e implementación de proyectos de TI.

---

## Experiencia

### GlobalHitss — Desarrollador Estandar (Junio 2019 - Presente)  
Trabajo con el Core de negocios de Claro Colombia para optimizar canales de venta en más de 5.000 puntos de call center.  
**Tecnologías:** Angular, Visual Basic .Net, C#, Visual Basic 6, Oracle, SQL Server.

### Corporación Universitaria Republicana — Docente (Enero 2020 - Diciembre 2020)  
Encargado de materias básicas y avanzadas, obteniendo reconocimiento en simposio internacional por aplicaciones de reconocimiento facial.  
**Tecnologías:** C#, Java, Python, OpenCV.

### IT Consultancy — Desarrollador de Cobis (Junio 2018 - Febrero 2019)  
Integración entre Cobis y Banco Agrario en módulos de cartera, créditos y cajeros automáticos.  
**Tecnologías:** C++, C#, Visual Basic 6, Oracle, AS400.

### Controles Empresariales — Consultor Microsoft (Febrero 2017 - Junio 2018)  
Lideré el desarrollo de Intranet/Internet de la ARN (Presidencia), capacitando 30 oficinas a nivel nacional.  
**Tecnologías:** C#, VB6, Oracle, Microsoft BI, SharePoint 2013, Project Server.

🔗 [Historial completo en LinkedIn](https://www.linkedin.com/in/oscardo2000/)

---

## Habilidades

- **Lenguajes:** C#, C++, C, JavaScript, Visual Basic 6/.Net, PHP, Python, OpenCV  
- **Frameworks/Herramientas:** Angular, Azure, UIPath, SharePoint, Unity, Android  
- **Bases de datos:** SQL Server, Oracle, Azure SQL, NoSQL, MongoDB  
- **Idiomas:** Inglés (Intermedio), Portugués (Fluido), Italiano (Básico), Español (Nativo)  
- **Certificaciones:** RPA Infrastructure UIPath, RPA Solution Architect UIPath, ITIL v3, SharePoint 2007/2010  

---

## Educación

- **SENA – Bogotá, Colombia**  
  Especialización en Gestión y Seguridad de Bases de Datos — *Diciembre 2019*

- **Universidad Internacional de La Rioja – España (Virtual)**  
  Magíster en Ingeniería de Software y Sistemas Informáticos — *Noviembre 2018*

- **Universidad del Tolima – Ibagué/Bogotá, Colombia**  
  Ingeniero en Sistemas — *Diciembre 2011*

---

## Prueba Técnica

**Requisitos del test:**

- Los resultados deben enviarse como documento adjunto.
- Los entregables deben estar adjuntos.

**Descripción funcional:**

1. Aplicación para registro de estudiantes con CRUD.
2. Estudiantes se adhieren a un programa de créditos.
3. Hay 10 materias, cada una con 3 créditos.
4. Cada estudiante puede seleccionar solo 3 materias.
5. Hay 5 profesores que dictan 2 materias cada uno.
6. Un estudiante no puede tener clases con el mismo profesor.
7. Puede ver registros de otros estudiantes.
8. Puede ver los nombres de compañeros por clase.

**Entregables:**

- Aplicación web o cliente-servidor.
- Scripts de base de datos para MySQL / SQL Server.

---

## Descarga del Proyecto

🔗 [Google Drive](https://drive.google.com/drive/folders/1-LD4IoUxif9Wnp6A387zscfU9MRx5Hca?usp=drive_link)  
🔗 [GitHub](https://github.com/oscardo/Interrapidisimo)  
📦 PruebaInter_OrtizPinzonOscarEduardo.zip

**Instrucciones de descarga:**

- El archivo `AcademicSystem.bak` en la carpeta `database` puede ser restaurado en SQL Server.
- El backend se encuentra comprimido como `AcademicSystemAPI.zip`, contiene el proyecto en Visual Studio 2022 con .NET 8.
- Ejecutar con `F5` para correr la API automáticamente.

---

## Angular - Guía de Desarrollo

### Servidor de desarrollo
```bash
ng serve
```
Navega a `http://localhost:4200/`. La app se recargará automáticamente si cambias archivos fuente.

### Instalación con nodemon
```bash
npm install --save-dev nodemon
```
Agrega a `package.json`:
```json
"ng-serve-nodemon": "nodemon --watch src --exec \"ng serve\""
```
Corre con:
```bash
npm run ng-serve-nodemon
```

### Generación de código
```bash
ng generate component nombre-del-componente
```
También puedes generar directivas, pipes, servicios, clases, guards, interfaces, enums y módulos.

### Compilación
```bash
ng build
```

### Pruebas unitarias
```bash
ng test
```
Ejecuta pruebas usando [Karma](https://karma-runner.github.io).

### Pruebas End-to-End
```bash
ng e2e
```
Instala un paquete compatible para poder ejecutar estas pruebas.

### Ayuda adicional
```bash
ng help
```
[Documentación oficial de Angular CLI](https://angular.io/cli)


---
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

- **LinkedIn:** [Oscar Eduardo Ortiz Pinzon](https://www.linkedin.com/in/oscardo2000/)
- **Página web:** [Oscar Ortiz](https://oscardo.github.io/) <!-- reemplaza con tu URL real -->
- **Correo electrónico:** [oscardo2000@gmail.com](mailto:oscardo2000@gmail.com)
- **Teléfono:** [Llamar al: +57 300 464 XXXX](tel:+573004642976)
- **WhatsApp:** [Escríbeme por WhatsApp](https://wa.me/573004642976)


