# venantvr.ia

Ingénierie LLM, conformité réglementaire santé et SEO augmenté par intelligence artificielle.

## Repos

### Ingénierie LLM et IA

**`vuejs.axiom.llm`** <sup>privé</sup>
*Vue 3 / Tailwind* — IDE de prompt engineering : compilation de langage naturel vers des schémas logiques (AST/DSL), édition visuelle de prompts structurés.

**`Rust.AuditGuard`** <sup>privé</sup>
*Rust / Axum* — Pré-commit hook IA pour audit de conformité HDS v2 / ISO 27001 / RGPD. Analyse des diffs Git via Gemini, scoring de risque, stockage SQLite, dashboard Swagger/OpenAPI.

**`Python.LangChain.Formation`** <sup>privé</sup>
*Python / LangChain* — Formation complète LangChain : chains, agents, tools, anonymisation médicale, intégration Neo4j, calcul de similarité de graphes, persistance MySQL.

### SEO augmenté par IA

**`Python.SEO.Spider`** <sup>privé</sup>
*Python / Flask* — Spider SEO avec Gemini : crawl intelligent multi-pages, génération automatique JSON-LD Schema.org, templates Jinja2, interface web Flask.

**`Python.SEO`** <sup>privé</sup>
*Python / FastAPI* — Monorepo SEO : 5 sous-packages (scraper FastAPI/Crawl4AI, générateur Gemini, recherche StackExchange, reverse SEO, providers), authentification JWT/bcrypt.

**`Python.SEO.Scraper`** <sup>public</sup>
*Python / FastAPI* — Micro-service de scraping haute performance : Crawl4AI, support PDF (PyMuPDF), pipeline d'extraction (BeautifulSoup + Trafilatura), queue Redis optionnelle.

**`Python.SEO.Gemini`** <sup>privé</sup>
*Python / Flask* — Générateur d'articles SEO via Google Gemini, templates Jinja2, cache MySQL, gestion de sites de confiance.

**`Python.SEO.StackExchange`** <sup>privé</sup>
*Python / Flask* — Moteur de recherche multi-sources StackExchange avec FTS5 SQLite, traduction FR→EN via Gemini, rate limiting.

**`vuejs.lighthouse.llm`** <sup>privé</sup>
*Vue 3 / Tailwind* — Dashboard d'analyse Lighthouse augmentée par LLM : scoring détaillé, graphiques Chart.js, export PDF (jsPDF + html2canvas), serveur backend Node.js, store Pinia.

### Conformité et documentation

**`Regulatory`** <sup>privé</sup>
*Markdown* — Toolkit conformité : PSSI, RGPD (registre + AIPD), ISO 27001 (guide + checklist), NIS 2, EBIOS RM, spécifique santé/IA.

**`Security.Docs`** <sup>privé</sup>
*Markdown* — Documentation cybersécurité francophone (185+ sujets) : ACL, cryptographie, TLS, VPN, préparation CEH.

**`DDD.Docs`** <sup>public</sup>
*Markdown* — Documentation Domain-Driven Design : ubiquitous language, architecture, actors, réglementations.

**`Doc.Pentest.ChatGPT`** <sup>privé</sup>
*Markdown* — Points de contrôle pentest pour l'Agence du Numérique en Santé : mots de passe, sessions, CSRF, injections.

### Expérimentation et archives

**`Blockchain.Docs`** <sup>privé</sup>
*Markdown* — Documentation blockchain : Ledger/BOLOS, consensus, smart contracts.

**`Python.Blockchain.ChatGPT`** <sup>privé</sup>
*Python* — Implémentation pédagogique d'une blockchain en Python.

**`Python.C.ChatGPT`** <sup>privé</sup>
*Python / C* — Interop Python/C : librairies partagées (.so), appels ctypes.

**`Python.ChatGPT.Archive`** <sup>privé</sup>
Archives de conversations IA (exploration, prototypage).

## Axes

- **Ingénierie LLM** — Prompt engineering visuel (AXIOM), audit de conformité IA (AuditGuard), SEO génératif (GEO)
- **Conformité santé** — HDS v2, PGSSI-S, RGPD, NIS 2, ISO 27001, EBIOS RM
- **SEO augmenté** — Crawl intelligent, Schema.org, génération de contenu par Gemini, analyse Lighthouse
- **Formation** — LangChain, DDD, cybersécurité, blockchain
