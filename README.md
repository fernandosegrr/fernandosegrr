<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0f172a,100:2563eb&text=Fernando%20Guerrero&fontColor=ffffff&fontSize=46&fontAlignY=40&desc=Chatbots%20de%20WhatsApp%20%C2%B7%20Automatizaci%C3%B3n%20%C2%B7%20Desarrollo%20web&descSize=18&descAlignY=62" alt="Fernando Guerrero" width="100%" />

**NexAI · Chatbots de WhatsApp, automatización y desarrollo web**

<a href="https://nexaisolutions.dev"><img src="https://img.shields.io/badge/Sitio%20web-nexaisolutions.dev-2563eb?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Sitio web" /></a>
<a href="mailto:jaimefernando3112@gmail.com"><img src="https://img.shields.io/badge/Correo-jaimefernando3112%40gmail.com-0f172a?style=for-the-badge&logo=gmail&logoColor=white" alt="Correo" /></a>

</div>

## Qué hago

- **Chatbots de WhatsApp:** diseño e integración de flujos conversacionales conectados a APIs, bases de datos y CRM.
- **Automatización de procesos:** orquestación con webhooks, colas de eventos y sincronización entre servicios.
- **Desarrollo web:** aplicaciones y paneles administrativos con React, Next.js, Node.js y TypeScript.
- **Infraestructura de mensajería:** mantenimiento de un fork técnico de Evolution API enfocado en estabilidad operativa.

---

## Proyectos

### [evoapi-resilient](https://github.com/fernandosegrr/evoapi-resilient) — Proyecto destacado

Fork no oficial e independiente basado en Evolution API `2.3.7`, enfocado en estabilidad operativa y endurecimiento de seguridad para despliegues sobre PostgreSQL, Redis y Node.js. **Sin garantía ni soporte; úsalo bajo tu responsabilidad y respalda tu base de datos antes de migrar.**

- Parche vía `patch-package` para enviar `ACK` a stanzas `<status>` de nivel superior en Baileys `7.0.0-rc12` y mitigar desconexiones por falta de confirmación.
- Reconexión automática por instancia con backoff exponencial, jitter, vigía para intentos atascados en `connecting` y manejo fail-closed de proxies.
- Deduplicación de mensajes en PostgreSQL mediante índice único, cabecera `Idempotency-Key`, cola de webhooks desacoplada y marcas de latencia (`receivedAtMs`, `enqueuedAtMs`, `dispatchedAtMs`).
- Protección de identidad de instancia autenticado frente a sobrescrituras desde `query` o `body`, además de manejo seguro de `@lid` y mensajes de Meta Ads.
- Resolución resiliente de la versión de WhatsApp Web con caché en disco y fallback inmediato si GitHub no responde.

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

---

### [Fin](https://github.com/fernandosegrr/Fin)

Aplicación web de finanzas personales enfocada en el control mensual de ingresos, gastos y objetivos financieros.

- Registro y seguimiento de transacciones, movimientos recurrentes y balances por mes.
- Gestión de presupuestos, categorías personalizadas y metas de ahorro.
- Panel reactivo con actualización en tiempo real y módulo de asesoría financiera.

<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
</p>

---

### [NexLift](https://github.com/fernandosegrr/NexLift)

Aplicación web progresiva (PWA) para registrar entrenamientos de gimnasio y calcular progresión de carga, repeticiones y descargas.

- Entrenador adaptativo con seguimiento de rendimiento, carga inteligente y análisis de sesiones.
- Almacenamiento local offline con Dexie y sincronización con backend en Node.js y Prisma.
- Gráficas de evolución con Recharts y exportación de rutinas/reportes a PDF.

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" />
</p>

---

### [fsi_proyect](https://github.com/fernandosegrr/fsi_proyect)

Vehículo robótico terrestre a escala (`LIDIA`) con tracción omnidireccional, navegación asistida y control inalámbrico en tiempo real.

- Control en tiempo real sobre ESP32 DevKit con cola determinista de comandos y comunicación por WebSocket.
- Núcleo de navegación y evasión en `C99` acompañado de pruebas unitarias y simulación Monte Carlo en Python.
- Aplicación móvil Android para operación manual y monitoreo, junto con verificación criptográfica de artefactos.

<p>
  <img src="https://img.shields.io/badge/C99-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C99" />
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android" />
</p>

---

## Herramientas

<div align="center">

<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n" />

</div>

## Contacto

- Sitio web: [nexaisolutions.dev](https://nexaisolutions.dev)
- Correo: jaimefernando3112@gmail.com

<img src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=100&color=0:2563eb,100:0f172a" width="100%" alt="" />
