#  Requirements — Marret Café

**Proyecto:** Marret Café – Sistema Web de Reservas y Pastelería Artesanal  
**Evaluación N°3 — Diseño y Desarrollo de Software**  
**Profesor:** Cristian Iglesias Vera  
**Equipo:** Fundación NTT Data 2 – Team 2  

---

##  1. Introducción

El sistema **Marret Café** busca digitalizar el proceso de atención y reservas de una cafetería artesanal, permitiendo a los usuarios **crear, consultar y cancelar reservas en línea**, y al personal **gestionar productos, usuarios y estados de reservas** desde un panel administrativo.

Este documento describe los **requerimientos funcionales y no funcionales**, los **actores del sistema**, los **casos de uso**, la **trazabilidad** y el **alcance** del sistema.

---

##  2. Actores del Sistema

| Actor | Descripción | Interacción Principal |
|--------|--------------|------------------------|
| **Usuario (Cliente)** | Persona que accede al sitio web para ver el menú, registrarse, crear reservas y enviar mensajes de contacto. | Interfaz pública y formulario de reservas. |
| **Administrador (Staff)** | Personal encargado de administrar productos, usuarios y estados de las reservas. | Panel administrativo y gestión interna. |

---

##  3. Objetivos del Sistema

- Automatizar el proceso de **reservas y gestión de productos**.  
- Reducir los tiempos de atención y errores manuales.  
- Mejorar la **experiencia del cliente** mediante una interfaz web simple e intuitiva.  
- Establecer la **base técnica y estructural** para una futura implementación completa.

---

##  4. Casos de Uso Principales

| Nº | Caso de Uso | Actor | Descripción | Prioridad |
|----|--------------|--------|--------------|------------|
| **CU-01** | Registrarse e iniciar sesión | Usuario | Permite crear una cuenta o autenticarse en el sistema. | Alta |
| **CU-02** | Explorar menú y productos | Usuario | Visualiza productos de café y pastelería. | Media |
| **CU-03** | Crear reserva | Usuario | Registra una reserva con fecha, hora y cantidad de personas. | Alta |
| **CU-04** | Ver o cancelar reservas | Usuario | Permite consultar y cancelar reservas. | Media |
| **CU-05** | Gestionar productos | Admin | CRUD de productos (crear, editar, eliminar). | Alta |
| **CU-06** | Actualizar estado de reserva | Admin | Cambiar el estado de una reserva (Pendiente, Confirmada, Cancelada). | Alta |
| **CU-07** | Gestionar usuarios | Admin | Administrar cuentas y roles de usuarios. | Media |

---

##  5. Requerimientos Funcionales

| ID | Requerimiento | Descripción | Actor |
|----|----------------|-------------|--------|
| **RF01** | Registro/Login | Permitir al usuario autenticarse en el sistema. | Usuario |
| **RF02** | Crear reserva | Generar reservas con validaciones de fecha y hora. | Usuario |
| **RF03** | Cancelar reserva | El usuario puede cancelar una reserva activa. | Usuario |
| **RF04** | Gestionar productos | CRUD de productos (nombre, precio, tipo, stock). | Admin |
| **RF05** | Actualizar estado de reserva | Cambiar estado entre Pendiente, Confirmada, Cancelada. | Admin |
| **RF06** | Gestionar usuarios | Alta, baja y roles administrativos. | Admin |
| **RF07** | Validaciones de campos | Formularios deben mostrar mensajes de error claros. | Ambos |

---

##  6. Requerimientos No Funcionales

| ID | Requerimiento | Descripción |
|----|----------------|-------------|
| **RNF01** | Usabilidad | Interfaz simple y responsive, accesible desde distintos dispositivos. |
| **RNF02** | Seguridad | Encriptación de contraseñas y manejo seguro de datos. |
| **RNF03** | Rendimiento | Carga promedio de vistas menor a 2 segundos. |
| **RNF04** | Escalabilidad | Posibilidad de ampliar el sistema sin rediseñarlo. |
| **RNF05** | Mantenibilidad | Código modular y documentado. |
| **RNF06** | Disponibilidad | Funcionamiento correcto sin depender de conexión constante. |

---

##  7. Trazabilidad (Casos de Uso → Clases UML)

| Caso de Uso | Clases Relacionadas | Descripción Técnica |
|--------------|--------------------|----------------------|
| **CU-01** Registrarse / Login | Usuario | Autenticación mediante credenciales y roles. |
| **CU-02** Explorar productos | Producto, Categoría | Consulta al catálogo activo. |
| **CU-03** Crear reserva | Usuario, Reserva, EstadoReserva | Registro con fecha y hora. |
| **CU-04** Cancelar reserva | Usuario, Reserva | Cambia el estado de la reserva. |
| **CU-05** Gestionar productos | Admin, Producto, Categoría | CRUD completo en panel. |
| **CU-06** Actualizar estado | Admin, Reserva, EstadoReserva | Modificación del estado. |
| **CU-07** Gestionar usuarios | Admin, Usuario | Control de roles y cuentas. |

---

## 📋 8. Reglas de Negocio

- Un usuario debe iniciar sesión para crear o cancelar reservas.  
- Las reservas solo pueden hacerse en horarios disponibles.  
- Solo los administradores pueden gestionar productos y usuarios.  
- Los estados válidos de una reserva son: **Pendiente**, **Confirmada**, **Cancelada**.  
- Un producto inactivo no se mostrará en la carta.

---

##  9. Alcance del Proyecto

### Incluye:
- Sistema web de reservas (interfaz pública y panel admin).  
- Gestión de productos, reservas y usuarios.  
- Diseño UML y documentación técnica.  

### No incluye:
- Pasarelas de pago o integración con correos.  
- Autenticación con redes sociales.  
- API externa (fase futura).

---

##  10. Cronograma de Entregas

| Semana | Actividad | Entregable | Responsable |
|---------|------------|-------------|--------------|
| 1 | Diagramas UML | `casodeuso.wsd` y `uml.wsd` | Michael |
| 2 | Documento de requerimientos | `requirements.md` | Felipe |
| 3 | Plan de implementación | `implementation_plan.md` | Nicolás |
| 4 | Integración final y exposición | `slides/Presentación Marret Cafe.pdf` | Equipo |

---


## 🪪 Licencia
Uso académico — Universidad Católica de Temuco.  
Proyecto presentado para la asignatura **Diseño y Desarrollo de Software**.

