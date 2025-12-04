# 📄 SCCT - Sistema de Control de Calidad en Taller (FINAL)

## 1. Resumen Ejecutivo, Problema y Solución (Criterio 1)

### 🚀 Título del Proyecto
**SCCT - Sistema de Control de Calidad en Taller**

### 🎯 Problema y Justificación
La empresa Muebles Prácticos S.A. de C.V. experimenta un alto índice de desperdicio de material y costos de reproceso debido a la falta de trazabilidad en los defectos de producción.

### 💡 Solución y Arquitectura
Se implementa el SCCT, una solución basada en la nube (Google Workspace) para la trazabilidad inmediata de los defectos.
* **Front-End (Input):** Google Forms.
* **Back-End (Lógica):** Google Apps Script.
* **Base de Datos:** Google Sheets.
* **Visualización (Output):** Google Looker Studio.

---

## 2. Requerimientos y Configuración (Criterio 1)

### Requerimientos Funcionales Implementados
1.  **Catálogos:** Implementación de catálogos de **Estaciones** y **Tipos de Defecto**.
2.  **Captura Móvil:** La interfaz fue diseñada para ser accesible y funcional en dispositivos móviles/tabletas (Requerimiento de Interfaz Externa).
3.  **Lógica de Validación:** El código de Apps Script verifica que los datos de entrada existan en la hoja `Catálogo` antes de procesar el registro.
4.  **Diseño:** El tiempo de captura no excede los 20 segundos para el operador (Requerimiento de Diseño).

### ⚙️ Configuración y Enlaces del Producto
| Componente | Enlace para Acceso |
| :--- | :--- |
| **Producto Funcional (Criterio 4)** | https://docs.google.com/forms/create?hl=es-419(https://docs.google.com/forms/d/e/1FAIpQLSfVAu8Wraod6yPClLeslO3hduD0FPLmoDMMirhX-J7VIm9uoQ/viewform?usp=preview) |
| **Dashboard de Reportes** | https://www.youtube.com/watch?v=lISeeBBvPKU(https://lookerstudio.google.com/reporting/8954ec5c-2400-4036-9427-8c3e88836f26) |
| **Base de Datos** | https://docs.google.com/spreadsheets/create?hl=es(https://docs.google.com/spreadsheets/d/1SznYaGlY0472qCH6ptXq0haku1pUZbwF6cJaIqVmsQk/edit?resourcekey=&gid=467314913#gid=467314913) |
| **Código Fuente** | https://developers.google.com/apps-script/guides/projects(https://script.google.com/u/0/home/projects/12I6i57pPSYMVpNm_O7AJM8A9TpiEWQNpOc4bPTSULJgZHL5Q1dl1r1ze/edit) |

---

## 3. Uso y Contribución (Criterio 2)

### 🧑‍💻 Guía de Uso
1.  **Captura:** El operador accede al Formulario, selecciona la estación y el defecto, y envía el registro.
2.  **Monitoreo:** El supervisor accede al Dashboard para ver la concentración de fallas por estación y tipo.

### 🤝 Guía de Contribución (Criterio 5)
El desarrollo se realizó siguiendo el flujo de trabajo Gitflow simplificado:
1.  **Ramas:** Desarrollado con ramas `main` (Producción) y `develop` (Desarrollo).
2.  **Commits y Etiquetas:** Se usaron etiquetas como `feat:` (feature) y `docs:` (documentation) en los mensajes de *commit* para categorizar el trabajo.

---

## 4. Repositorio y Desarrollo (Criterio 5)

| Actividad de GitHub | Cumplimiento |
| :--- | :--- |
| **Uso de Ramas** | Desarrollado con ramas `main` y `develop`. |
| **Commits y Etiquetas** | Se generaron *commits* con etiquetas y mensajes claros (Ej. `feat:`, `docs:`). |
| **Pull Requests** | Se generaron *Pull Requests* para fusionar el código de desarrollo a la rama principal (`main`). |

## 5. Evidencia del Producto (Criterio 3)

### 📹 Video de Demostración
El video demuestra el flujo completo: 1) Captura de datos en el Formulario, 2) Ejecución del código de validación en la Hoja `Registros` (Resultado "OK"), y 3) Visualización de la actualización en el Dashboard de Looker Studio.

> **URL del Video:** [Video de YouTube](https://youtu.be/9RJK2wX_5aI)
