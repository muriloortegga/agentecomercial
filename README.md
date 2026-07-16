# Agente Comercial — Eme Creative Hub

Este repositório contém a estrutura de um **Agente Comercial baseado em arquivos**, projetado para operar como um cérebro comercial descentralizado e executável via Claude Code, Claude Cowork e outros agentes autônomos.

O objetivo do sistema é estabelecer um método de aquisição de clientes B2B de forma enxuta, eficiente e humana, focado no direct do Instagram e em canais consultivos, minimizando o tempo operacional diário do fundador.

---

## 🎯 Propósito do Repositório

Transformar este repositório em um ativo comercial vivo para a **Eme Creative Hub**. O repositório armazena todo o contexto estratégico da empresa, os playbooks de execução tática, o pipeline de vendas atualizado e o histórico de aprendizados obtidos em cada abordagem comercial.

### 🧠 O que é o Agente Comercial?
O Agente Comercial é um assistente cognitivo operando como um **Chief Revenue Officer (CRO)** virtual. Ele executa rotinas comerciais, pesquisa leads qualificados, desenha roteiros personalizados de abordagem baseados em contextos reais e documenta decisões e experimentos.

Ele **não** é uma ferramenta de disparo de spam ou automação de mensagens em lote. Ele atua sob premissas de prospecção consultiva e valorização da voz humana genuína.

---

## ⚙️ Diferença entre Estratégia, Operação e Automação

No design deste sistema, as responsabilidades estão bem separadas:

*   **Estratégia ([core/](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/core/) e [context/](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/context/))**: Define *quem* abordamos (ICP), *o que* oferecemos (Oferta), as regras éticas e operacionais de tomada de decisão.
*   **Operação ([playbooks/](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/playbooks/) e [operations/](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/operations/))**: Define o *como* (passo a passo de prospecção, qualificação, follow-ups) e as rotinas de revisão de pipeline diárias/semanais.
*   **Automação ([playbooks/AUTOMATION_DESIGN.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/playbooks/AUTOMATION_DESIGN.md))**: Otimização técnica de tarefas repetitivas, implementada apenas *depois* que o processo manual for validado e provar seu valor.

---

## 📂 Estrutura das Pastas

```text
agentecomercial/
├── core/         # Regras, modos de operação e protocolos do agente
├── context/      # Contexto corporativo, ICP, oferta e tom de voz (Eme Creative Hub)
├── playbooks/    # Manuais passo a passo para prospecção, SEO, CRM e qualificação
├── operations/   # Rotina diária/semanal, controle do pipeline e metas (KPIs)
├── templates/    # Modelos de mensagens, propostas, relatórios e missões
├── missions/     # Histórico de missões comerciais executadas
├── data/         # Arquivos de dados estruturados e listas de leads (LGPD compliant)
└── logs/         # Registros de decisões, aprendizados e alterações do repositório
```

---

## 🚀 Como começar hoje

Para iniciar a operação da máquina comercial, siga este fluxo:

1.  **Preencher o contexto da empresa**: Edite o arquivo [COMPANY_CONTEXT.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/context/COMPANY_CONTEXT.md) com as informações básicas da Eme Creative Hub.
2.  **Preencher oferta e ICP**: Detalhe os serviços e diferenciais no [OFFER_CONTEXT.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/context/OFFER_CONTEXT.md) e o perfil de cliente ideal no [ICP_CONTEXT.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/context/ICP_CONTEXT.md).
3.  **Criar uma missão**: Copie o [MISSION_TEMPLATE.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/templates/MISSION_TEMPLATE.md) para a pasta [missions/](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/missions/) com o nome `YYYY-MM-DD_nome-da-missao.md`.
4.  **Executar a pesquisa**: Use o playbook [LEAD_RESEARCH.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/playbooks/LEAD_RESEARCH.md) para encontrar e enriquecer os dados dos primeiros alvos comerciais.
5.  **Registrar resultados**: Adicione novos leads ao [COMMERCIAL_PIPELINE.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/operations/COMMERCIAL_PIPELINE.md) e preencha seus perfis individuais.
6.  **Revisar aprendizados**: Ao finalizar uma missão, registre as descobertas no [LEARNING_LOG.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/logs/LEARNING_LOG.md).

---

## 🔄 Como iniciar uma nova missão

Toda atividade comercial importante executada por um agente deve ser tratada como uma **Missão**.
1. Crie um arquivo em [missions/](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/missions/) com o padrão `YYYY-MM-DD_nome-da-missao.md` com base no template [MISSION_TEMPLATE.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/templates/MISSION_TEMPLATE.md).
2. Peça para o agente ler o escopo da missão e executar as tarefas descritas.
3. Ao finalizar, o agente atualiza o status para `Concluída` e registra as conclusões e os próximos passos.

---

## 🧠 Como atualizar os aprendizados

Toda vez que uma abordagem comercial falhar, tiver sucesso ou uma nova premissa for testada:
*   Documente a data, a hipótese e o aprendizado prático em [logs/LEARNING_LOG.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/logs/LEARNING_LOG.md).
*   Se o aprendizado alterar uma premissa estratégica básica, atualize [context/COMMERCIAL_ASSUMPTIONS.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/context/COMMERCIAL_ASSUMPTIONS.md) e [core/DECISION_RULES.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/core/DECISION_RULES.md).

---

## 🛠️ Próximos Passos Recomendados (Não Implementado)

A estrutura atual é um sistema operacional documental (Zero Code). Os próximos passos evolutivos do repositório incluem:
1.  **Missão 01**: Definir o ICP inicial e Oferta de Entrada da Eme Creative Hub.
2.  **Missão 02**: Montar a primeira lista de 10 leads altamente qualificados no Instagram.
3.  **Automações Futuras**: Integração com APIs para enriquecimento de leads (ex: Lusha, Apify) e alertas de novos leads no Slack/WhatsApp do fundador (sempre após validação do processo manual).