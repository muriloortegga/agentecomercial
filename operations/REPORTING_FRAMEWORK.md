# Estrutura de Relatórios e Métricas Comerciais (Reporting Framework)

Este documento estabelece o padrão de relatórios diários e semanais de vendas da **Eme Creative Hub**, alimentados pelos dados do **HubSpot** e registrados como inteligência no repositório.

---

## 🎯 Princípios de Relatórios

1.  **HubSpot como Fonte da Verdade**: Todas as métricas de volume, conversão e tempo no funil devem derivar de consultas oficiais ao HubSpot.
2.  **Métricas Orientadas à Decisão**: Nenhuma métrica deve ser acompanhada sem suportar uma decisão ou indicar uma necessidade de ajuste no processo comercial.
3.  **Transparência e Evidências**: Indicar sempre a fonte dos dados, o período analisado, a definição do indicador e eventuais limitações.

---

## 📊 1. Relatório Diário Operacional (Daily Briefing)

Apresentado ao final de cada sessão diária de trabalho:

*   **Novos Leads Pesquisados & Qualificados**: Quantidade de leads mapeados no dia.
*   **Registros Criados no HubSpot**: Número de contatos e empresas salvos no CRM.
*   **Leads Descartados (Anti-ICP)**: Quantidade e motivos de desqualificação prévia.
*   **Abordagens Preparadas**: Rascunhos de e-mails ou Directs salvos no CRM aguardando aprovação.
*   **Abordagens Enviadas**: Mensagens autorizadas e enviadas (via Direct manual ou E-mail).
*   **Respostas Recebidas**: Interações iniciadas por leads.
*   **Gargalo do Dia**: Principal trava observada na sessão.
*   **Próxima Melhor Ação**: Prioridade imediata para o dia seguinte.

---

## 📈 2. Relatório Semanal de Desempenho (Weekly Review)

Consolidado ao final de cada ciclo semanal e registrado em [operations/WEEKLY_REVIEW.md](WEEKLY_REVIEW.md):

### Funil de Vendas (Métricas de Volume e Conversão)
- **Leads Pesquisados**: Total de empresas analisadas na semana.
- **Taxa de Qualificação**: % de leads pesquisados que atenderam ao ICP.
- **Abordagens por Canal**: Total de envios divididos por Instagram Direct, E-mail Individual e Sequência HubSpot.
- **Taxa de Resposta (Reply Rate)**: % de abordagens que geraram conversas ativas.
- **Taxa de Diagnóstico / Reunião**: % de conversas que evoluíram para chamadas/briefings.
- **Propostas Enviadas**: Número de propostas formais entregues.
- **Novos Clientes Fechados (Closed Won)**: Total de contratos assinados e valor gerado.
- **Valor do Pipeline**: Soma estimada de todas as oportunidades ativas no HubSpot.

### Análise de Perdas e Qualidade
- **Motivos de Perda (Closed Lost Reasons)**: Distribuição das perdas por Preço, Timing, Concorrência ou Silêncio.
- **Sintese de Objeções**: Lista de dúvidas ou resistências recorrentes apresentadas pelos leads.
- **Métricas de Esforço**: Tempo total investido pelo fundador e pelo agente durante a semana.

### Aprendizados & Decisões Estratégicas
- **Mensagens com Maior Conversão**: Quais ganchos ou observações reais geraram mais respostas.
- **Segmentos Mais Aderentes**: Qual nicho B2B respondeu melhor ao tom de voz da Eme.
- **Experimento Sugerido para a Próxima Semana**: Hipótese a ser testada no [operations/EXPERIMENT_BACKLOG.md](EXPERIMENT_BACKLOG.md).

---

## 🏷️ Padrão de Identificação de Métricas

Todo número apresentado em relatórios deve ser acompanhado de sua tag de evidência:
*   `[CRM - HubSpot]` — Dado extraído diretamente de relatórios/APIs do HubSpot.
*   `[Manual - Fundador]` — Registro de atividade executada manualmente pelo fundador.
*   `[Estimado - Hipótese]` — Projeção ou hipótese a ser validada.
