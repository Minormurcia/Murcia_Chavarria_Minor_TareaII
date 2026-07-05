# Murcia_Chavarria_Minor_TareaII

# Backlog y Sprint para Proyecto React con Firebase

## Estudiante

**Nombre:** Minor Murcia

**Curso:** Técnicas de Programación

**Tarea II**

---

# Descripción del Proyecto

## Nombre del Proyecto

Control de Gastos Personales

## Descripción

El proyecto consiste en desarrollar una aplicación web utilizando React y Firebase que permita a los usuarios registrar, consultar y administrar sus ingresos y gastos personales. El sistema busca facilitar el control financiero mediante una interfaz sencilla, autenticación de usuarios y almacenamiento seguro de la información.

---

# Product Backlog

| ID | Historia de Usuario | Prioridad | Story Points |
|----|---------------------|-----------|--------------|
| HU-01 | Como usuario, quiero registrarme para poder acceder a la aplicación. | Alta | 3 |
| HU-02 | Como usuario, quiero iniciar sesión para acceder a mi información personal. | Alta | 3 |
| HU-03 | Como usuario, quiero registrar ingresos y gastos para controlar mi dinero. | Alta | 8 |
| HU-04 | Como usuario, quiero editar o eliminar movimientos para corregir errores. | Media | 5 |
| HU-05 | Como usuario, quiero visualizar el balance mensual para conocer mi situación financiera. | Media | 5 |
| HU-06 | Como usuario, quiero consultar el historial de transacciones para revisar movimientos anteriores. | Baja | 3 |

---

# Planificación del Sprint

**Duración del Sprint:** 2 semanas

## Historias seleccionadas

- HU-01 Registro de usuarios.
- HU-02 Inicio de sesión.
- HU-03 Registro de ingresos y gastos.

---

# Tareas del Sprint

## HU-01 Registro de usuarios

- Diseñar formulario de registro.
- Validar datos.
- Configurar Firebase Authentication.
- Guardar usuario en Firestore.
- Realizar pruebas.

### Criterios de aceptación

- El usuario puede crear una cuenta correctamente.
- No se permiten correos duplicados.
- Se muestra un mensaje de confirmación.

---

## HU-02 Inicio de sesión

- Crear pantalla de inicio de sesión.
- Integrar Firebase Authentication.
- Validar usuario y contraseña.
- Mostrar mensajes de error.
- Realizar pruebas.

### Criterios de aceptación

- El usuario puede iniciar sesión correctamente.
- Se valida la información ingresada.
- Se muestran mensajes de error cuando corresponda.

---

## HU-03 Registro de ingresos y gastos

- Crear formulario de movimientos.
- Validar información.
- Guardar datos en Firestore.
- Mostrar lista de movimientos.
- Calcular saldo automáticamente.

### Criterios de aceptación

- El usuario puede registrar ingresos.
- El usuario puede registrar gastos.
- El saldo se actualiza automáticamente.
- La información queda almacenada correctamente.

---

# Justificación de la priorización

Las historias HU-01, HU-02 y HU-03 fueron seleccionadas para el primer Sprint debido a que representan las funcionalidades esenciales para que la aplicación pueda ser utilizada. Primero es necesario que los usuarios puedan registrarse e iniciar sesión para posteriormente registrar sus ingresos y gastos. Las historias relacionadas con edición de movimientos, historial y balance mensual fueron priorizadas para futuros Sprint debido a que dependen del funcionamiento de las características principales.

---

# Tecnologías utilizadas

- React
- Firebase Authentication
- Cloud Firestore
- Bootstrap
- Chart.js

---

# Conclusión

La planificación del Product Backlog y del Sprint permite organizar el desarrollo del proyecto de forma ordenada, priorizando las funcionalidades más importantes para entregar un producto funcional en cada iteración. El uso de Trello facilita el seguimiento del avance de las tareas y la aplicación de conceptos básicos de metodologías ágiles.