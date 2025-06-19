# Sistema de Aprendizaje Personalizado - Flipped Classroom

Este proyecto implementa un sistema interactivo de aprendizaje personalizado diseñado para entornos de "Flipped Classroom". Utiliza **Streamlit** para la interfaz de usuario, **Pandas** para la gestión de datos y **Altair** para la visualización del progreso del estudiante. El objetivo principal es ofrecer contenido educativo adaptado al nivel de conocimiento individual de cada estudiante en diferentes conceptos temáticos.

---

## 🚀 Características Principales

* **Contenido Personalizado**: Proporciona material de estudio (texto y ejemplos prácticos) que se ajusta automáticamente al nivel de conocimiento (Básico, Intermedio, Avanzado) de cada estudiante para un concepto específico.
* **Seguimiento Visual del Progreso**: Muestra un gráfico interactivo con los niveles de conocimiento actuales del estudiante en cada concepto, permitiendo una visión clara de su dominio.
* **Gestión de Estudiantes y Contenido**: Carga datos de estudiantes y contenido temático desde archivos CSV, facilitando la administración del material y los perfiles de usuario.
* **Actualización de Nivel de Conocimiento**: Incluye una funcionalidad para actualizar el nivel de conocimiento de un estudiante en un concepto determinado, permitiendo registrar su progreso o realizar ajustes manuales.
* **Fácil de Usar**: Interfaz intuitiva construida con Streamlit, accesible a través del navegador web.

---

## 🛠️ Tecnologías Utilizadas

* **Python 3.x**
* **Streamlit**: Para la creación de la interfaz de usuario web.
* **Pandas**: Para la manipulación y gestión de datos (CSV).
* **Altair**: Para la creación de visualizaciones interactivas de datos.

---

## 📁 Estructura del Proyecto
.
├── app.py                     # Archivo principal de la aplicación Streamlit
├── contenido_tematico.csv     # Datos del contenido educativo por concepto y nivel
├── estudiantes.csv            # Datos de los estudiantes y sus niveles de conocimiento
└── requirements.txt           # Lista de dependencias del proyecto

## 🚀 Ejecución de la Aplicación

Una vez que hayas configurado todo, puedes iniciar la aplicación Streamlit desde tu terminal (asegúrate de tener activado tu entorno virtual):https://flippedclassroomcontenidopersonalizado-drmqo77mtedzp4jcbzggcc.streamlit.app/
