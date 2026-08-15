# Asistente de Correo Automatizado con IA en n8n

Flujo de automatización desarrollado en **n8n** que procesa mensajes de contacto entrantes mediante un agente de **Google Gemini** con salida estructurada en JSON y envía respuestas automáticas personalizadas vía **Gmail API**.

## 🧩 Diagrama del Flujo

![Diagrama de n8n](./diagrama.png)

## 🛠️ Tecnologías y Nodos

* **n8n** (Self-hosted)
* **Google Gemini Chat Model** (`gemini-1.5-flash`)
* **Structured Output Parser** (Salida normalizada en JSON)
* **Gmail API / OAuth2** (Envío automatizado)

## 🚀 Cómo importarlo

1. Descarga el archivo `email-ai-agent-workflow.json`.
2. En tu instancia de n8n, ve a **Workflows > Import from File**.
3. Configura tus propias credenciales para:
   * Google Gemini API (Google AI Studio).
   * Gmail OAuth2.
4. Activa el flujo y prueba con el nodo manual.
