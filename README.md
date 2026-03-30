# 🤖 Prompt Generator 2026

Una aplicación web estática y ligera (100% frontend) diseñada para construir prompts profesionales, estructurados y altamente efectivos para Modelos de Lenguaje Grande (LLMs como ChatGPT, Claude, Gemini, etc.).

La herramienta ayuda a desarrolladores, ingenieros y profesionales a aplicar las mejores prácticas de *Prompt Engineering* (como Chain-of-Thought, Few-Shot prompting y definición estricta de roles) generando automáticamente una salida estructurada en formato XML, lo que reduce las alucinaciones de la IA y mejora drásticamente la calidad de las respuestas.

## ✨ Características Principales

*   **⚡ 100% Estático y Privado:** No requiere Node.js, base de datos ni backend. Se ejecuta completamente en el navegador del usuario a través de un único archivo HTML.
*   **🎭 Biblioteca de Roles Expertos:** Incluye decenas de *system prompts* predefinidos de alto nivel (perfiles con "20+ años de experiencia") divididos por áreas: Desarrollo, Ciberseguridad, Data/IA, DevOps, Producto, Legal, Negocios, etc.
*   **🏗️ Estructura XML en Tiempo Real:** Genera el prompt en vivo utilizando etiquetas XML (`<system_role>`, `<task_definition>`, `<chain_of_thought>`, etc.) para maximizar la comprensión del modelo.
*   **💡 Ayudas Contextuales (Tooltips):** Incluye buenas prácticas y ejemplos *inline* en cada campo para enseñar al usuario a escribir mejores instrucciones.
*   **🛠️ Interfaz Moderna:** Diseño "Dark Mode" responsivo construido con Tailwind CSS y Lucide Icons.
*   **📋 Funciones de Utilidad:** Gestión de stack tecnológico mediante etiquetas (tags), guardado de roles/esquemas personalizados en memoria, y botones rápidos para limpiar o copiar el resultado al portapapeles.

## 🛠️ Tecnologías

*   HTML5
*   Vanilla JavaScript
*   Tailwind CSS (vía CDN)
*   Lucide Icons (vía CDN)

## 🚀 Cómo usarlo

Simplemente clona el repositorio o descarga el archivo `index.html` y ábrelo en cualquier navegador web moderno. ¡No requiere instalación ni dependencias!
