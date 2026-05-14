# ttripleai-ai-agents
Autonomous B2B workflows and AI agents built with n8n, LangChain, and OCR. Official repository of @ttripleai.

# @ttripleai - Autonomous Business Ecosystems 🚀

Bienvenido al repositorio oficial de **@ttripleai**. En este espacio presento la arquitectura de mis ecosistemas de automatización B2B, diseñados para transformar procesos manuales en flujos autónomos de alto rendimiento.

Como estudiante de Ingeniería en Inteligencia Artificial (UNL, Argentina), mi enfoque se centra en la creación de lógica algorítmica personalizada, integrando agentes de IA con memoria, visión artificial (OCR) y sincronización de datos en tiempo real.

## 📂 Proyectos Destacados

### 1. 🏥 KineCust - Gestión Inteligente para Centros de Salud
*(Archivo: `Workflow_Kine_BETA.json`)*
Un sistema avanzado de recepción y triaje para consultorios médicos.
- **Triaje Semántico:** El agente analiza el síntoma del paciente y asigna automáticamente el recurso necesario (Magneto/Gimnasio).
- **Gestión de Restricciones:** Controla la capacidad máxima por horario leyendo directamente de Google Calendar.
- **Vínculo con Obras Sociales:** Consulta requisitos y copagos en bases de datos externas antes de confirmar turnos.
- **OCR de Órdenes:** Procesa imágenes de pedidos médicos para extraer diagnósticos y sesiones de forma autónoma.

### 2. 💰 @ttripleai Finanzas - Verificación de Pagos 24/7
*(Archivo: `Workflow_Inmobiliaria_BETA.json`)*
Ecosistema diseñado para la conciliación bancaria y administrativa automatizada.
- **Auditoría Omnicanal:** Monitorea entradas en Gmail y WhatsApp simultáneamente.
- **Visión Artificial (OCR):** Analiza comprobantes (PDF/JPG) para extraer montos, fechas y números de operación con alta precisión.
- **Conciliación Automática:** Cruza los datos con planillas de Google Sheets para validar transacciones y actualizar estados de deuda.

### 3. 🍔 BurgerMood - Agente de Ventas Transaccional
*(Archivo: `Workflow_BurgerMood.json`)*
Flujo de e-commerce gastronómico con validación estricta de datos.
- **Base de Conocimiento:** El agente consulta precios y stock en tiempo real desde Google Sheets para evitar alucinaciones.
- **Captura de Leads:** Recopila datos de envío, preferencias y métodos de pago, enviando el pedido listo para cocina al sistema de gestión.

### 4. 🧠 Secretario Ejecutivo Personal
*(Archivo: `SecretarioFacu.json`)*
Asistente privado de alta disponibilidad para la gestión de productividad.
- **Interfaz Híbrida:** Capacidad de transcribir y ejecutar comandos desde audios de WhatsApp o texto.
- **Gestión de Calendario y Mail:** Creación y modificación de eventos complejos y lectura de correos clave.
- **Memoria de Largo Plazo:** Implementación de nodos de memoria para mantener el contexto de tareas pendientes.

## 🛠️ Stack Tecnológico
- **Orquestación:** n8n (Arquitectura Self-Hosted en VPS con Docker).
- **Inteligencia Artificial:** Google Gemini 2.5 Flash / OpenAI, LangChain Agents.
- **Integraciones:** WhatsApp Business API, Gmail API, Google Calendar API, Google Sheets API.
- **Lógica Custom:** Implementación de nodos de código en JavaScript y expresiones regulares (Regex) para limpieza de datos.

---
© 2026 **@ttripleai** - Innovative Engineering Solutions
