# 🚦 Chatbot de Educación Vial

Aplicación web fullstack que integra un chatbot inteligente en tiempo real para responder preguntas sobre educación vial, utilizando la API de Groq. El objetivo del proyecto es mejorar el aprendizaje interactivo y accesible sobre normas de tránsito mediante una interfaz moderna y escalable.

## 📌 Descripción General

Este proyecto implementa un sistema web con arquitectura simple pero extensible:

- **Frontend**: Interfaz web en HTML, CSS y JavaScript
- **Backend**: Servidor en Node.js con Express
- **IA**: Integración con API de Groq para respuestas inteligentes en tiempo real

Está diseñado como base para evolucionar hacia una aplicación más robusta tipo SaaS, con autenticación, dashboard y módulos educativos avanzados.

## 🧱 Estructura del Proyecto

```
chatbot-educacion-vial/
│
├── index.html        # Interfaz principal del chatbot
├── style.css         # Estilos de la aplicación
├── script.js         # Lógica del frontend (interacción + fetch API)
├── server.js         # Backend con Express + conexión a Groq
├── package.json      # Dependencias del proyecto
└── README.md         # Documentación
```

## ⚙️ Tecnologías Utilizadas

### Frontend
- HTML5
- CSS3
- JavaScript (Vanilla)

### Backend
- Node.js
- Express
- CORS
- groq-sdk
- dotenv

## 🚀 Instalación y Configuración

### 1. Clonar el repositorio
```bash
git clone https://github.com/TU-USUARIO/chatbot-educacion-vial.git
cd chatbot-educacion-vial
```

### 2. Inicializar el proyecto
```bash
npm init -y
```

### 3. Instalar dependencias
```bash
npm install express cors groq-sdk dotenv
```

### 4. Configurar variables de entorno

Crear archivo `.env`:

```
GROQ_API_KEY=tu_api_key_aqui
```

⚠️ **Importante**: No subir este archivo al repositorio.

### 5. Ejecutar el servidor
```bash
node server.js
```

Servidor disponible en: `http://localhost:3000`
