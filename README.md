# LicitFlow 14.133 — Gestão Paramétrica SEI! Bahia ➔ PNCP

> **Painel 360° para Coordenação de Licitações do CBMBA.**
> Integra a fase preparatória interna com a fase de disputa externa, mapeando pregoeiros, prazos preclusivos da Lei 14.133/2021 e gerando certidões oficiais em 1 clique para o SEI.

---

## 🚀 Funcionalidades

1. **Funil 360° (Kanban):**
   * *1. DFD, ETP & Riscos* ➔ *2. Pesquisa de Preços & TR* ➔ *3. Análise Jurídica PGE* ➔ *4. Publicado no PNCP / Licitações-e2*.
2. **Integração Realtime com a Extensão `PluginNato`:**
   * Recebe transmissões automáticas do SEI! Bahia via `window.postMessage`, área de transferência ou payload de URL (`#/import?payload=...`).
3. **Painel de Agentes de Contratação & Pregoeiros:**
   * Distribuição de processos por militar/servidor da seção (ex: CAP PM Leonardo, SGT PM Guilherme, SD PM Cauã).
4. **Calculadora de Prazos Preclusivos (Lei 14.133/2021):**
   * Contagem em dias úteis dos prazos de impugnação, esclarecimentos e recursos (Art. 164 c/c Art. 183).
5. **Gerador de Despachos & Certidões para o SEI:**
   * Copia o texto em HTML padronizado para colar direto no editor do SEI! Bahia.
6. **Progressive Web App (PWA):**
   * 100% instalável em Android, iOS e Windows, com suporte offline-first.

---

## 🛠️ Tecnologias
* HTML5 / Tailwind CSS
* JavaScript ES6+ (Client-side, sem necessidade de build/compilação)
* Service Worker + Cache API (PWA)
* Integração DOM com PluginNato
