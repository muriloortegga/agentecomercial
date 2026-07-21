# Registro de Aprendizados Comerciais (Learning Log)

Este arquivo consolida os principais aprendizados e lições extraídas de missões, experimentos e interações com leads ao longo da operação comercial da **Eme Creative Hub**.

---

## 📚 Como Usar Este Log

Ao encerrar uma missão ou experimento, o Agente Comercial deve registrar aqui:
*   O que funcionou e por quê.
*   O que falhou e qual foi a causa raiz identificada.
*   Qual ajuste deve ser feito nos playbooks, templates ou premissas.

---

## 🗓️ Registro de Aprendizados

| Data | Origem (Missão/Experimento) | Categoria | Aprendizado | Ação Corretiva Recomendada | Status |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 16/07/2026 | Inicialização do Agente Comercial | Estratégia | A estrutura baseada em arquivos Markdown é suficiente para operar a fase inicial de aquisição sem código complexo. | Manter formato atual por 60 dias antes de avaliar migração para banco de dados. | **Aplicada** |
| 21/07/2026 | 2026-07-22_primeiros-leads-hubspot (Rodada 4) | Operação | HubSpot `numberofemployees` é campo NUMBER nativo e rejeita strings de faixa (ex: "51-200") — falha em lote inteiro se um objeto tiver o campo mal formatado. | Nunca preencher `numberofemployees` com faixas; usar apenas número inteiro ou omitir e registrar a faixa em texto livre no `description`. | **Aplicada** |
| 21/07/2026 | 2026-07-22_primeiros-leads-hubspot (Rodada 4) | Pesquisa | Geocodificação por cidade (`city_region`) do Vibe Prospecting/Explorium não cobre bem municípios brasileiros pequenos (Cotia retornou cidades dos EUA). | Para leads no ICP regional (Cotia/VGP), continuar usando pesquisa manual (Google); reservar Vibe Prospecting para escopo nacional com filtro `company_country_code`. | **Aplicada** |
| 21/07/2026 | 2026-07-22_primeiros-leads-hubspot (Rodada 3-4) | Estratégia | Pedidos de volume agressivo ("100+ leads/1h") tendem a colidir com regras de não-invenção de dados; pausar com `AskUserQuestion` antes de agir evita tanto violar regras quanto travar a missão. | Manter o padrão de usar `AskUserQuestion` sempre que um pedido do fundador exigir trade-off entre volume/qualidade/custo não coberto pelas regras existentes. | **Aplicada** |
| `[Data]` | `[Nome da Missão ou EXP0X]` | `[Pesquisa / Estratégia / Produção / Operação / Análise / Automação]` | `[O que foi aprendido?]` | `[Qual mudança deve ser feita nos arquivos do sistema?]` | `[Pendente / Aplicada]` |
