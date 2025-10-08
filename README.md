Marret-Cafe

**Evaluación N°3 — Diseño y Desarrollo de Software**  
**Profesor:** Cristian Iglesias Vera  
**Sección:** 01 — TU en Informática Diurno  

--- 
**Integrantes y Roles del Equipo**

| **Integrante**       | **Rol Principal**            | **Responsabilidades**                                                              |
|----------------------|------------------------------|-----------------------------------------------------------------------------------|
| *Nicolás Huenchual*  | **Líder / Coordinador**      | Organización del equipo, control de tiempos, revisión general y entrega final.     |
| *Michael Flores*     | **Diseñador UML / QA**        | Creación de diagramas UML (clases y casos de uso), validación técnica y control de calidad. |
| *Felipe Salazar*     | **Analista de Requisitos / Presentador** | Documentación funcional, trazabilidad y exposición del proyecto.                |

### Repositorio

/Marret-Cafe
├── README.md # Documento principal con la descripción del proyecto y cómo usarlo
├── requirements.md # Requerimientos funcionales y no funcionales
├── implementation_plan.md # Plan de implementación técnica, cronograma y tareas
├── repo.url.txt # Link del repositorio en GitHub para facilitar el acceso
├── diagrams/ # Carpeta con los diagramas UML
│ ├── casodeuso.wsd # Diagrama de casos de uso (PlantUML)
│ ├── casodeuso.png # Diagrama de casos de uso exportado
│ ├── uml.wsd # Diagrama de clases (PlantUML)
│ └── uml.png # Diagrama de clases exportado
├── slides/ # Carpeta con la presentación en PDF
│ └── Presentación Marret Cafe.pdf # Presentación final del proyecto
├── documentación/ # Documentos adicionales
│ ├── especificación_requerimientos.pdf # Documento detallado de requisitos
│ ├── casos_de_uso.pdf # Especificación de los casos de uso
│ ├── diagrama_clases.pdf # Especificación del diagrama de clases
│ └── plan_implementación.pdf # Plan de implementación completo
├── frontend/ # Carpeta para el desarrollo frontend
│ ├── index.html # Página principal HTML
│ ├── estilos/ # Estilos CSS
│ │ ├── main.css # Estilos globales
│ └── scripts/ # Scripts JavaScript
│ └── app.js # Lógica de la aplicación (frontend)
├── backend/ # Carpeta para el desarrollo backend (Node.js)
│ ├── controllers/ # Controladores para las rutas de la API
│ ├── models/ # Modelos de datos (productos, reservas, etc.)
│ ├── routes/ # Rutas de la API
│ └── config/ # Configuración del servidor y base de datos
│ ├── database.js # Conexión con la base de datos
│ └── server.js # Configuración del servidor Express
├── base_datos/ # Carpeta con información de la base de datos
│ ├── diagrama_entidad_relación.png # Diagrama ER de la base de datos
│ └── script_sql_marret.sql # Script SQL para crear las tablas de la base de datos

**Descripción del Proyecto**

-El proyecto **Marret Café** tiene como propósito **digitalizar el proceso de atención y reservas** de una cafetería artesanal, brindando una **plataforma web moderna** que permita a los clientes **realizar reservas en línea** y al personal **gestionar productos, reservas y usuarios** desde un panel administrativo.

-Este trabajo corresponde a la **fase de diseño técnico**, donde se presentan los **diagramas UML**, la **documentación de requerimientos** y el **plan de implementación**, como base para el desarrollo futuro del sistema.


**Contenidos Principales**

### requirements.md
Documento de *requerimientos funcionales y no funcionales*, actores del sistema, casos de uso, objetivos, trazabilidad y cronograma general.

### implementation_plan.md
*Plan de implementación técnica*, tareas semanales, responsables, historias de usuario y criterios de aceptación.

### Carpeta /diagrams/
Contiene los *diagramas UML* del sistema:
- *casodeuso.wsd / .png:* Interacciones entre actores y casos de uso.  
- *uml.wsd / .png:* Diagrama de clases con relaciones y atributos principales.

### Carpeta /slides/

-Incluye la *presentación oficial en PDF* (exportada desde Canva o PowerPoint).

### Carpeta /frontend

-Contiene los archivos básicos del frontend, como index.html, archivos de estilo (main.css) y scripts (app.js).

-La carpeta /assets contiene imágenes e íconos para el sitio web.

### Carpeta /backend

-La carpeta /controllers incluye los controladores de la API REST.

-La carpeta /models contiene los modelos de datos que interactúan con la base de datos.

-/config/database.js y /config/server.js configuran la base de datos y el servidor.

---

**Objetivos del Proyecto**

- Diseñar la *estructura lógica y funcional* del sistema web de reservas.  
- Aplicar el *modelado UML* para representar actores, clases y flujos principales.  
- Establecer una *trazabilidad clara* entre requerimientos, clases y tareas.  
- Documentar los *roles, planificación y entregables* del equipo.  

---

**Cronograma de Trabajo (Resumen)**

| Semana | Actividad                                                  | Responsable    |
| ------ | ---------------------------------------------------------- | -------------- |
| 1      | Diseño de diagramas UML y estructura básica                | Michael        |
| 2      | Redacción de requisitos y análisis de funcionalidades      | Felipe         |
| 3      | Plan de implementación y tareas técnicas                   | Nicolás        |
| 4      | Implementación del prototipo y preparación de presentación | Todo el equipo |
