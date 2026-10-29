**English** · [Português](https://github.com/rodrigoteixeiraferreira/rodrigoteixeiraferreira/blob/main/README.pt-BR.md) · [Español](https://github.com/rodrigoteixeiraferreira/rodrigoteixeiraferreira/blob/main/README.es.md)

# Rodrigo Teixeira Ferreira

**Automation & AI Engineer** — n8n · Supabase · PostgreSQL · RAG

I build AI agents where the business logic lives in the database, not in the prompt.

Availability, pricing, atomic transactions and balance calculations are SQL functions.
The model interprets intent and routes to tools. Three consequences: it runs on cheap
models, it isn't tied to a vendor, and it can't be wrong about numbers it never
calculates. When a model does decide something, its error rate is measured by sample, and
above the limit it stops deciding on its own.

---

### Projects

**[comparador-listas-fornecedores](https://github.com/rodrigoteixeiraferreira/comparador-listas-fornecedores)** — Supplier price-list comparator: case study and runnable demo
Delivered in October 2026 to a neighborhood supermarket. Reads supplier price lists from
spreadsheets, PDFs and photos, matches each line to the store's catalog in a SQL cascade
and shows who sells cheapest. Acceptance criterion: zero false positives — 0 contradictions
in confirmed pairs, AI error measured by sample (1 in 145). The public demo is rewritten
from scratch with fictional data and proves itself: 0 wrong pairs in 5 generated worlds,
51 of 51 corrupted lists held at the gate.
`PostgreSQL` · `Supabase` · `Python` · `Next.js` · `Claude Code`

**[agente-matriculas-ia](https://github.com/rodrigoteixeiraferreira/agente-matriculas-ia)** — AI enrollment agent
Looks up courses, checks open seats and records pre-registrations by chat. The business
rules are versioned SQL functions: the model interprets intent and picks tools, but never
decides about a seat.
`FastAPI` · `Google Gemini` · `PostgreSQL` · `Docker` · `CI`

**[agente-hoteleiro-ia](https://github.com/rodrigoteixeiraferreira/agente-hoteleiro-ia)** — AI booking agent for independent hotels
Real availability by date overlap, atomic reservations with `FOR UPDATE`, multimodal
input (audio, image, PDF), anti-fraud protocol on payment receipts. The agent never
confirms a payment — it holds the room and a human verifies.
Measured: US$ 0.032 per full booking conversation on the cheapest model in the line.
`n8n` · `Supabase` · `pgvector` · `Google Gemini` — [demo video](https://youtu.be/eq6xmbjIrdc)

**[agente-prevendas-telecom-n8n](https://github.com/rodrigoteixeiraferreira/agente-prevendas-telecom-n8n)** — Multi-agent B2B pre-sales system
An orchestrator routing to three specialised sub-agents — lead qualification, number
portability guidance, and SLA triage — all reading from one central vector knowledge
base, so they can't contradict each other.
`n8n` · `Supabase` · `pgvector` · `RAG`

---

### Stack

`n8n` `Supabase` `PostgreSQL` `PL/pgSQL` `pgvector` `RAG` `Python` `FastAPI` `Next.js`
`Google Gemini` `Claude API` `REST APIs` `Docker` `Lovable` `Cursor` `Claude Code` `Git`

---

### About

Based in Argentina — GMT-3, same timezone as Brazil. Working remotely.
Portuguese (native) · Spanish (fluent) · English (technical reading).

Every repository here is something I can explain and modify. Nothing is decorative.

[LinkedIn](https://www.linkedin.com/in/rodrigo-teixeira-ferreira-2b00a31b6) · flechamedicina@gmail.com
