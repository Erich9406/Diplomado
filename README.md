Este repositorio contiene la implementación técnica del trabajo de grado/diplomado centrado en el diseño e implementación de un Agente Conversacional con Arquitectura RAG (Retrieval-Augmented Generation) y orquestación de flujos de trabajo en n8n integrados con Google Workspace.

🚀 Descripción del Proyecto
El sistema está diseñado para actuar como un asistente virtual inteligente capaz de consultar bases de conocimientos centralizadas (documentos técnicos, reglamentos y guías en formato PDF/Drive) y responder de manera precisa mediante procesamiento de lenguaje natural. Además, integra automatizaciones con la API de Google Workspace para registrar la actividad de los usuarios y agendar citas automáticamente.

🛠️ Arquitectura y Tecnologías
Modelo LLM: OpenAI GPT-4 / GPT-3.5-Turbo.  
Framework RAG: Arquitectura de Recuperación Aumentada por Generación.  
Ingeniería de Prompts: Framework CO-STAR para el control de respuesta y mitigación de alucinaciones.  
Orquestación: n8n (Workflows para Webhooks, Google Drive, Google Sheets, Google Calendar y Gmail).  
