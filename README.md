# Maxim Burnosov

**Full-Stack Engineer (Python)** — LLM automation · VoIP / WebRTC · crypto payments
📍 Athens, Greece · [LinkedIn](https://www.linkedin.com/in/makcext) · makcext@gmail.com · 📄 [Download CV (PDF)](./cv.pdf)

I turn manual business processes into production software, and I ship whole products on my own:
domain model, backend, UI and infrastructure.

---

### 🔥 What I'm building now

- **LLM email automation:** a 3-stage LLM pipeline (Claude, NVIDIA NIM) classifies inbound trading email and turns supplier rate offers into structured deals. Nobody re-keys data by hand any more, and data errors fell from **544 to 0**.
- **AI invoice extraction:** PDF and Excel invoices are read page by page as images and returned as structured data with line items. Automatic checks (totals, VAT, IBAN, duplicates) and CRM matching auto-approve clean invoices and send the rest to a finance review app. **800+ invoices** processed.
- **VoIP self-service platform:** customer and staff portals over a closed billing system, a **WebRTC browser softphone** (Kamailio + rtpengine), a Telegram bot and USDT top-ups. Ansible rolls out a new white-label instance with one command.
- **AML risk engine for TRON/USDT:** taint tracing through the transaction graph, address-poisoning detection and sanctions scoring. Sold through an API, Telegram bots and the web.
- **AI agent for telecom hardware:** a LangGraph agent and MCP server that drives GSM modems and SIM cards with a human approving each step, and onboards SIM cards from a photo.
- **Treasury "Liquidity Board":** payment planning on an append-only journal, so the same invoice can't be paid twice.

### 🧰 Stack

**Core:** Python · Django / DRF · FastAPI · PostgreSQL · Go
**AI:** LLM pipelines (Claude, NVIDIA NIM) · LangGraph · MCP
**Frontend:** TypeScript · React · Next.js · Tailwind
**Telecom:** SIP · Kamailio · rtpengine · WebRTC · SMPP · GSM
**Crypto:** TRON / USDT · on-chain analytics · Stripe
**Data & infra:** Kafka · Debezium · Redis · RabbitMQ · Docker · Ansible · CI/CD

