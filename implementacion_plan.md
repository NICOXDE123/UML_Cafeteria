#  Implementation Plan — Marret Café

**Proyecto:** Marret Café – Sistema Web de Reservas y Pastelería Artesanal  
**Evaluación N°3 — Diseño y Desarrollo de Software**  
**Profesor:** Cristian Iglesias Vera  

##  Objetivo General
Definir un **plan de implementación técnica** que permita convertir el diseño UML y los requerimientos funcionales del sistema **Marret Café** en un prototipo web funcional y escalable.

---

##  Stack Tecnológico (Propuesto)

| Componente | Tecnología |
|-------------|-------------|
| **Frontend (Vista)** | HTML5, CSS3, Bootstrap (versión CDN) |
| **Lógica de Negocio (Opcional)** | PHP o Angular (futuro desarrollo) |
| **Base de Datos** | MySQL |
| **Gestión de Versiones** | Git + GitHub |
| **Herramientas de Diseño** | PlantUML, Canva, VS Code |

> 💡 En esta evaluación se prioriza el diseño UML y la planificación, no la codificación completa.

---

##  Arquitectura Conceptual

El sistema está compuesto por tres módulos principales:

1. **Módulo de Usuarios:** registro, inicio de sesión y gestión de perfil.  
2. **Módulo de Reservas:** creación, consulta y cancelación de reservas.  
3. **Módulo Administrativo:** gestión de productos, usuarios y estado de reservas.

---

##  Historias de Usuario y Tareas

| ID | Historia / Tarea | Descripción | Responsable | Criterios de Aceptación |
|----|------------------|--------------|--------------|--------------------------|
| **US-01** | Registro e inicio de sesión | Permitir a los usuarios registrarse y autenticarse. | Felipe | Validación de campos y confirmación visual. |
| **US-02** | Explorar productos | Mostrar carta de productos (cafetería y pastelería). | Nicolás | Listado funcional y diseño responsivo. |
| **US-03** | Crear reserva | Generar reserva con fecha, hora y cantidad de personas. | Nicolás | Formulario funcional y mensaje de confirmación. |
| **US-04** | Ver y cancelar reservas | Mostrar reservas del usuario y permitir su cancelación. | Felipe | Lista con opción de cancelar. Estado actualizado. |
| **US-05** | Gestión de productos | CRUD de productos con control de stock. | Michael | Funcionalidad completa y validaciones. |
| **US-06** | Gestión de usuarios | Alta, baja y roles de usuarios. | Michael | Tabla de usuarios y rol administrativo funcional. |
| **US-07** | Actualizar estado de reservas | Cambiar estado (Pendiente, Confirmada, Cancelada). | Michael | Cambio reflejado en interfaz de admin. |

---

## Cronograma de Implementación

| Semana | Actividad | Responsable | Entregable |
|---------|------------|--------------|-------------|
| **Semana 1** | Revisión de requerimientos y modelado UML | Michael | `uml.wsd`, `casodeuso.wsd`, PNG exportados |
| **Semana 2** | Documentación de requisitos y trazabilidad | Felipe | `requirements.md` |
| **Semana 3** | Creación del plan de implementación | Nicolás | `implementation_plan.md` |
| **Semana 4** | Integración final y presentación | Equipo | `slides/Presentación Marret Cafe.pdf` |

---

## Trazabilidad (Casos de Uso → Tareas Técnicas)

| Caso de Uso | Clases Relacionadas | Tareas Asociadas |
|--------------|--------------------|------------------|
| Crear reserva | Usuario, Reserva, EstadoReserva | US-03 |
| Cancelar reserva | Usuario, Reserva | US-04 |
| Gestionar productos | Admin, Producto, Categoría | US-05 |
| Gestionar usuarios | Admin, Usuario | US-06 |
| Actualizar estado | Admin, Reserva, EstadoReserva | US-07 |

---

##  Estrategia de Pruebas

| Tipo de Prueba         | Descripción                                             | Responsable |
|----------------        |--------------                                           |--------------|
| **Pruebas Unitarias** | Verificar funcionamiento de funciones individuales (simulado). | Michael |
| **Pruebas de Integración** | Validar coherencia entre módulos de reservas y productos. | Felipe |
| **Pruebas de Validación** | Revisión de formularios y mensajes de error. | Nicolás |
| **Pruebas de Documentación** | Revisión final de requisitos y UML. | Equipo completo |

---

##  Riesgos Identificados

| Riesgo | Descripción | Mitigación |
|---------|--------------|-------------|
| ❌ Retrasos en la entrega | Descoordinación o cambios de horario | Comunicación interna y planificación semanal |
| ⚙️ Falta de experiencia con UML | Dificultad en relaciones y atributos | Revisión cruzada del equipo |
| 💾 Problemas técnicos en Git | Conflictos o errores de subida | Uso de ramas personales y commits frecuentes |
| 🌐 Dependencia de conexión a internet | Fallas en demostración | Copia local del repositorio en PDF |

---

##  Próximos Pasos

1. Finalizar revisión de requerimientos.  
2. Ajustar diagramas UML según retroalimentación del profesor.  
3. Preparar prototipo web (futuro desarrollo).  
4. Integrar todo el material en la presentación final PDF.

---

## ✅ Estado Actual

| Elemento | Estado |
|-----------|--------|
| Diagramas UML | ✔️ Finalizados |
| Documentación de Requisitos | ✔️ Completa |
| Plan de Implementación | ✔️ Entregado |
| Presentación PDF | ✔️ Lista |
| Subida a GitHub | ✔️ Realizada |

---

## 🪪 Licencia
Uso académico — Universidad Católica de Temuco.  
Proyecto presentado para la asignatura **Diseño y Desarrollo de Software**.
