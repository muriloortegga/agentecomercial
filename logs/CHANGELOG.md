# Changelog — Histórico de Evoluções do Sistema (Changelog)

Este arquivo registra cronologicamente todas as evoluções, adições e ajustes feitos na estrutura do Agente Comercial da **Eme Creative Hub**.

---

## 📖 Convenção de Tipos de Mudança

*   **[ADD]**: Novo arquivo ou funcionalidade adicionada ao sistema.
*   **[MOD]**: Modificação ou atualização de um arquivo existente.
*   **[DEL]**: Remoção de um arquivo ou regra obsoleta.
*   **[FIX]**: Correção de erro em um arquivo existente.
*   **[REFACTOR]**: Reorganização de estrutura sem alterar conteúdo funcional.

---

## 🗓️ Histórico de Versões

### v1.0.0 — 16/07/2026 — Estrutura Base Inicial

**Objetivo**: Criação da primeira versão funcional do sistema de Agente Comercial baseado em arquivos.

**Arquivos Adicionados**:

*   **[ADD]** `README.md` — Visão geral e mapa de navegação do repositório.
*   **[ADD]** `CLAUDE.md` — Guia de integração com modelos de IA (Claude / Gemini).
*   **[ADD]** `core/SYSTEM_PROMPT.md` — Prompt base de comportamento do agente.
*   **[ADD]** `core/EXECUTION_PROTOCOL.md` — Fluxo de 12 etapas de execução de missões.
*   **[ADD]** `core/OPERATING_MODES.md` — 6 modos operacionais do agente.
*   **[ADD]** `core/OUTPUT_STANDARDS.md` — Padrões de formatação e entrega.
*   **[ADD]** `core/DECISION_RULES.md` — Regras lógicas de tomada de decisão comercial.
*   **[ADD]** `context/COMPANY_CONTEXT.md` — Template de contexto institucional da empresa.
*   **[ADD]** `context/OFFER_CONTEXT.md` — Template de detalhamento de ofertas comerciais.
*   **[ADD]** `context/ICP_CONTEXT.md` — Template de Perfil de Cliente Ideal (ICP).
*   **[ADD]** `context/BRAND_VOICE.md` — Guia de tom de voz comercial e comunicação.
*   **[ADD]** `context/COMMERCIAL_ASSUMPTIONS.md` — Matriz de hipóteses e premissas estratégicas.
*   **[ADD]** `playbooks/INSTAGRAM_OUTREACH.md` — Manual de prospecção via direct do Instagram.
*   **[ADD]** `playbooks/LEAD_RESEARCH.md` — Manual de pesquisa e inteligência de leads.
*   **[ADD]** `playbooks/LEAD_SCORING.md` — Modelo de pontuação de leads (0 a 100).
*   **[ADD]** `playbooks/FOLLOW_UP.md` — Manual de acompanhamento consultivo.
*   **[ADD]** `playbooks/CRM_MANAGEMENT.md` — Manual de gestão e higiene do CRM.
*   **[ADD]** `playbooks/SEO_GROWTH.md` — Manual de SEO e credibilidade orgânica.
*   **[ADD]** `playbooks/CONTENT_TO_PIPELINE.md` — Manual de conversão de conteúdo em vendas.
*   **[ADD]** `playbooks/AUTOMATION_DESIGN.md` — Manual de desenho e decisão de automações.
*   **[ADD]** `operations/COMMERCIAL_PIPELINE.md` — Pipeline de vendas com 14 etapas.
*   **[ADD]** `operations/DAILY_ROUTINE.md` — Rotina comercial diária (15, 30 e 60 min).
*   **[ADD]** `operations/WEEKLY_REVIEW.md` — Ritual de revisão semanal de desempenho.
*   **[ADD]** `operations/KPI_FRAMEWORK.md` — Framework de KPIs e metas comerciais.
*   **[ADD]** `operations/EXPERIMENT_BACKLOG.md` — Backlog de 7 experimentos comerciais iniciais.
*   **[ADD]** `templates/LEAD_PROFILE_TEMPLATE.md` — Template de perfil individual de lead.
*   **[ADD]** `templates/OUTREACH_MESSAGE_TEMPLATE.md` — Template de mensagem de abordagem.
*   **[ADD]** `templates/FOLLOW_UP_TEMPLATE.md` — Template de acompanhamentos (3 módulos).
*   **[ADD]** `templates/OPPORTUNITY_TEMPLATE.md` — Template de oportunidade de venda.
*   **[ADD]** `templates/EXPERIMENT_TEMPLATE.md` — Template de experimento comercial.
*   **[ADD]** `templates/SOP_TEMPLATE.md` — Template de Procedimento Operacional Padrão.
*   **[ADD]** `templates/MISSION_TEMPLATE.md` — Template de missão comercial.
*   **[ADD]** `missions/README.md` — Guia de nomenclatura e exemplos de missões.
*   **[ADD]** `data/README.md` — Políticas de segurança e LGPD para dados estruturados.
*   **[ADD]** `logs/DECISION_LOG.md` — Registro cronológico de decisões estratégicas.
*   **[ADD]** `logs/LEARNING_LOG.md` — Registro de aprendizados e lições de missões.
*   **[ADD]** `logs/CHANGELOG.md` — Este arquivo. Histórico de evoluções do sistema.

---

> **Próxima Revisão Planejada**: Após a execução das 3 primeiras missões comerciais reais, revisar os playbooks, ajustar o modelo de scoring e atualizar as premissas em `context/COMMERCIAL_ASSUMPTIONS.md`.
