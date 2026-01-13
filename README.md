# EduPath 🎓

**EduPath** es una plataforma educativa inteligente diseñada para personalizar la experiencia de aprendizaje mediante el uso de **Inteligencia Artificial Adaptativa**. Permite a los educadores gestionar grupos y lecciones, mientras que los estudiantes reciben recomendaciones personalizadas basadas en su rendimiento en tiempo real.

---

## 🚀 Características Principales

-   **Dashboard de Docente**: Creación y gestión de grupos, asignaciones y lecciones interactivas.
-   **Dashboard de Estudiante**: Seguimiento de progreso, ganancia de puntos (XP) y gamificación.
-   **IA Adaptativa**: Sistema que recomienda la siguiente lección y ajusta la dificultad según el rendimiento del usuario.
-   **Generación de Exámenes con IA**: Microservicio que procesa archivos PDF para generar exámenes automáticamente utilizando modelos de lenguaje (Google Gemini).
-   **Arquitectura de Microservicios**: Separación clara entre el cliente, el servidor de datos y la lógica de inteligencia artificial.

---

## 🛠️ Stack Tecnológico

### Frontend
-   **Framework**: [React 19](https://react.dev/) + [Vite](https://vitejs.dev/)
-   **Lenguaje**: TypeScript
-   **Estado**: Redux Toolkit & Persist
-   **Estilos**: Tailwind CSS v4 + Radix UI
-   **Iconos**: Lucide React

### Backend (Node)
-   **Framework**: Express.js
-   **Lenguaje**: TypeScript
-   **Base de Datos**: MongoDB (Mongoose)
-   **Autenticación**: JWT (JSON Web Tokens) & Bcrypt

### Inteligencia Artificial (Python)
-   **Framework**: FastAPI
-   **Orquestador**: LangChain
-   **Modelo**: Google Generative AI (Gemini)
-   **Vector DB**: ChromaDB
-   **Procesamiento**: PyPDF

---

## 📂 Estructura del Proyecto

```text
edupath/
├── edupath_front/    # Aplicación React (Vite + TS)
├── edupath_back/     # API Node.js (Express + MongoDB)
├── IA/               # Microservicio de IA (FastAPI + Python)
└── README.md         # Documentación general
