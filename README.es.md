[English](https://github.com/rodrigoteixeiraferreira/rodrigoteixeiraferreira/blob/main/README.md) · [Português](https://github.com/rodrigoteixeiraferreira/rodrigoteixeiraferreira/blob/main/README.pt-BR.md) · **Español**

# Rodrigo Teixeira Ferreira

**Ingeniero de Automatización e IA** — n8n · Supabase · PostgreSQL · RAG

Construyo agentes de IA donde la lógica de negocio vive en la base de datos, no en el prompt.

Disponibilidad, precios, transacciones atómicas y cálculo de saldos son funciones SQL.
El modelo interpreta la intención y elige la herramienta. Tres consecuencias: corre en
modelos económicos, no depende de un proveedor específico, y no se equivoca en cuentas
que nunca hace. Cuando un modelo sí decide algo, su tasa de error se mide por muestra, y
arriba del límite deja de decidir solo.

---

### Proyectos

**[comparador-listas-fornecedores](https://github.com/rodrigoteixeiraferreira/comparador-listas-fornecedores)** — Comparador de listas de precios de proveedores: estudio de caso y demo que corre
Entregado en octubre de 2026 a un supermercado de barrio. Lee listas de precios de
proveedores en planilla, PDF y foto, identifica cada línea en el catálogo de la tienda con
una cascada en SQL y muestra quién vende más barato. Criterio de aceptación: cero falsos
positivos — 0 contradicciones en los pares confirmados, error de la IA medido por muestra
(1 en 145). La demo pública está reescrita desde cero, con datos ficticios, y se prueba
sola: 0 pares equivocados en 5 mundos generados, 51 de 51 listas arruinadas retenidas en el
portón.
`PostgreSQL` · `Supabase` · `Python` · `Next.js` · `Claude Code`

**[agente-matriculas-ia](https://github.com/rodrigoteixeiraferreira/agente-matriculas-ia)** — Agente de IA para inscripciones
Consulta cursos, verifica cupos y registra preinscripciones por chat. Las reglas de negocio
son funciones SQL versionadas: el modelo interpreta la intención y elige la herramienta,
pero nunca decide sobre un cupo.
`FastAPI` · `Google Gemini` · `PostgreSQL` · `Docker` · `CI`

**[agente-hoteleiro-ia](https://github.com/rodrigoteixeiraferreira/agente-hoteleiro-ia)** — Agente de reservas para hoteles independientes
Disponibilidad real por solapamiento de fechas, reserva atómica con `FOR UPDATE`,
entrada multimodal (audio, imagen, PDF) y protocolo antifraude en comprobantes de pago.
El agente nunca confirma un pago — retiene la habitación y una persona verifica.
Costo medido: US$ 0,032 por conversación completa de reserva, en el modelo más económico de la línea.
`n8n` · `Supabase` · `pgvector` · `Google Gemini` — [video de demostración](https://youtu.be/eq6xmbjIrdc)

**[agente-prevendas-telecom-n8n](https://github.com/rodrigoteixeiraferreira/agente-prevendas-telecom-n8n)** — Sistema multiagente de preventa B2B
Un orquestador que enruta hacia tres subagentes especializados — calificación de leads,
guía de portabilidad y triaje por SLA — todos leyendo de una única base vectorial
central, de modo que no puedan contradecirse.
`n8n` · `Supabase` · `pgvector` · `RAG`

---

### Stack

`n8n` `Supabase` `PostgreSQL` `PL/pgSQL` `pgvector` `RAG` `Python` `FastAPI` `Next.js`
`Google Gemini` `Claude API` `APIs REST` `Docker` `Lovable` `Cursor` `Claude Code` `Git`

---

### Sobre mí

Radicado en Argentina — GMT-3, mismo huso horario que Brasil y cuatro
horas de diferencia con España. Trabajo 100% remoto.
Portugués (nativo) · Español (fluido) · Inglés (lectura técnica).

Cada repositorio acá es algo que puedo explicar y modificar. Nada es decorativo.

[LinkedIn](https://www.linkedin.com/in/rodrigo-teixeira-ferreira-2b00a31b6) · flechamedicina@gmail.com
