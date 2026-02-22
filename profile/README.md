# venantvr.ia

Ingénierie LLM, conformité réglementaire santé et SEO augmenté par intelligence artificielle.

## Repos

### Ingénierie LLM et IA

| Repo | Stack | Description |
|------|-------|-------------|
| `vuejs.axiom.llm` | Vue 3 / Tailwind | IDE de prompt engineering : compilation de langage naturel vers des schémas logiques (AST/DSL), édition visuelle de prompts structurés |
| `Rust.AuditGuard` | Rust / Axum | Pré-commit hook IA pour audit de conformité HDS v2 / ISO 27001 / RGPD. Analyse des diffs Git via Gemini, scoring de risque, stockage SQLite, dashboard Swagger/OpenAPI |
| `Python.LangChain.Formation` | Python | Formation complète LangChain : chains, agents, tools, anonymisation médicale, intégration Neo4j, calcul de similarité de graphes, persistance MySQL |

### SEO augmenté par IA

| Repo | Stack | Description |
|------|-------|-------------|
| `Python.SEO.Spider` | Python | Spider SEO avec Gemini : crawl intelligent multi-pages, génération automatique JSON-LD Schema.org, templates Jinja2, interface web Flask |
| `Python.SEO` | Python | Monorepo SEO : 5 sous-packages (scraper FastAPI/Crawl4AI, générateur Gemini, recherche StackExchange, reverse SEO, providers), authentification JWT/bcrypt |
| `Python.SEO.Scraper` | Python / FastAPI | Micro-service de scraping haute performance : Crawl4AI, support PDF (PyMuPDF), pipeline d'extraction (BeautifulSoup + Trafilatura), queue Redis optionnelle |
| `Python.SEO.Gemini` | Python / Flask | Générateur d'articles SEO via Google Gemini, templates Jinja2, cache MySQL, gestion de sites de confiance |
| `Python.SEO.StackExchange` | Python / Flask | Moteur de recherche multi-sources StackExchange avec FTS5 SQLite, traduction FR→EN via Gemini, rate limiting |
| `vuejs.lighthouse.llm` | Vue 3 / Tailwind | Dashboard d'analyse Lighthouse augmentée par LLM : scoring, graphiques Chart.js, export PDF, serveur backend Node.js |

### Conformité et documentation

| Repo | Stack | Description |
|------|-------|-------------|
| `Regulatory` | Markdown | Toolkit conformité : PSSI, RGPD (registre + AIPD), ISO 27001 (guide + checklist), NIS 2, EBIOS RM, spécifique santé/IA |
| `Security.Docs` | Markdown | Documentation cybersécurité francophone (185+ sujets) : ACL, cryptographie, TLS, VPN, préparation CEH |
| `DDD.Docs` | Markdown | Documentation Domain-Driven Design : ubiquitous language, architecture, actors, réglementations |
| `Doc.Pentest.ChatGPT` | Markdown | Points de contrôle pentest pour l'Agence du Numérique en Santé : mots de passe, sessions, CSRF, injections |

### Expérimentation et archives

| Repo | Stack | Description |
|------|-------|-------------|
| `Blockchain.Docs` | Markdown | Documentation blockchain : Ledger/BOLOS, consensus, smart contracts |
| `Python.Blockchain.ChatGPT` | Python | Implémentation pédagogique d'une blockchain en Python |
| `Python.C.ChatGPT` | Python/C | Interop Python/C : librairies partagées (.so), appels ctypes |
| `Python.ChatGPT.Archive` | -- | Archives de conversations IA (exploration, prototypage) |

## Axes

- **Ingénierie LLM** — Prompt engineering visuel (AXIOM), audit de conformité IA (AuditGuard), SEO génératif (GEO)
- **Conformité santé** — HDS v2, PGSSI-S, RGPD, NIS 2, ISO 27001, EBIOS RM
- **SEO augmenté** — Crawl intelligent, Schema.org, génération de contenu par Gemini, analyse Lighthouse
- **Formation** — LangChain, DDD, cybersécurité, blockchain
