# Pipeline de Vendas e Funil Comercial no HubSpot (Commercial Pipeline)

Este documento define a estrutura do funil de vendas da **Eme Creative Hub** sincronizada com o **HubSpot**. Cada etapa possui critérios de entrada, saída, campos obrigatórios e automações de tarefas.

---

## 🏗️ As Etapas do Pipeline de Vendas no HubSpot

### 1. Lead Descoberto (Subscriber / Prospect)
*   **Objetivo**: Registrar o mapeamento inicial de uma empresa ou profissional com potencial aderência ao ICP.
*   **Critério de Entrada**: Nome da empresa/decisor e ao menos um link verificado (Instagram, LinkedIn ou Site).
*   **Critério de Saída**: Início da pesquisa detalhada de contexto e necessidades.
*   **Registro no CRM**: Cadastro básico do objeto *Contact* e *Company* no HubSpot.

### 2. Lead Pesquisado (Lead)
*   **Objetivo**: Entender o contexto real da empresa com base em fatos e inferências fundamentadas.
*   **Critério de Entrada**: Início da coleta de informações em fontes públicas (Instagram, Google, LinkedIn).
*   **Critério de Saída**: Preenchimento dos sinais de necessidade e capacidade.
*   **Campos no CRM**: Cargo do Decisor, Sinais de Necessidade, Sinais de Capacidade.

### 3. Lead Qualificado (Marketing Qualified Lead - MQL)
*   **Objetivo**: Validar a aderência ao ICP Nacional ou Internacional Assíncrono da Eme.
*   **Critério de Entrada**: Pesquisa de contexto concluída e ausência de Red Flags impeditivas.
*   **Critério de Saída**: Cálculo do Score do lead (0 a 100).
*   **Campos no CRM**: Status de Qualificação, Confirmação do ICP.

### 4. Lead Priorizado (Sales Qualified Lead - SQL)
*   **Objetivo**: Definir o canal recomendado e preparar a abordagem consultiva.
*   **Critério de Entrada**: Score calculado e classificação no Tier 1 ou Tier 2.
*   **Critério de Saída**: Rascunho da abordagem redigido e registrado como nota/rascunho no CRM.
*   **Campos no CRM**: Score Final, Canal Recomendado, Rascunho da Abordagem.

### 5. Aquecimento / Abordagem Preparada (Opportunity Created)
*   **Objetivo**: Apresentar a abordagem personalizada para aprovação do fundador.
*   **Critério de Entrada**: Mensagem consultiva pronta para revisão.
*   **Critério de Saída**: Aprovação formal do fundador para envio (via Direct manual ou E-mail).
*   **Campos no CRM**: Status de Aprovação, Data Limite de Revisão.

### 6. Primeiro Contato Realizado (Outreach Sent)
*   **Objetivo**: Enviar a abordagem aprovada e aguardar retorno.
*   **Critério de Entrada**: Confirmação do envio manual do Direct ou disparo do e-mail.
*   **Critério de Saída**: Registro da mensagem enviada na linha do tempo do HubSpot.
*   **Campos no CRM**: Data de Envio, Canal Utilizado, Tarefa de Follow-up agendada.

### 7. Conversa Iniciada (In Discussion)
*   **Objetivo**: Conduzir o diálogo consultivo focado nos problemas de marca e posicionamento do lead.
*   **Critério de Entrada**: Resposta positiva ou neutra do lead.
*   **Critério de Saída**: Identificação de dor clara e abertura para diagnóstico/proposta.
*   **Campos no CRM**: Histórico de Interações, Dor Principal Identificada.

### 8. Proposta / Apresentação de Ativos (Proposal Sent)
*   **Objetivo**: Apresentar o escopo da oferta (Ecossistema de Marca, Identidade Visual, Site ou Ativos) e proposta financeira.
*   **Critério de Entrada**: Alinhamento inicial de necessidades realizado.
*   **Critério de Saída**: Envio oficial da proposta formalizada.
*   **Campos no CRM**: Valor do Negócio (mínimo R$ 1.000, médio R$ 2.000), Data de Validade da Proposta.

### 9. Negociação (In Negotiation)
*   **Objetivo**: Ajustar condições de pagamento, parcelamento e escopo dentro do contrato.
*   **Critério de Entrada**: Proposta analisada pelo cliente com abertura para contratação.
*   **Critério de Saída**: Aceite dos termos ou encerramento da negociação.
*   **Campos no CRM**: Condições de Pagamento Negociadas, Tarefa de Follow-up Ativa.

### 10. Ganho / Fechado (Closed Won)
*   **Objetivo**: Formalizar a contratação e iniciar entregas graduais.
*   **Critério de Entrada**: Contrato formal assinado e sinal de pagamento confirmado.
*   **Critério de Saída**: Transição para a rotina de produção e entrega de ativos.
*   **Campos no CRM**: Valor Final do Contrato, Data de Assinatura, Link do Contrato.

### 11. Perdido (Closed Lost)
*   **Objetivo**: Registrar perdas e extrair aprendizados operacionais.
*   **Critério de Entrada**: Recusa formal ou interrupção definitiva das interações.
*   **Critério de Saída**: Arquivamento com motivo obrigatório.
*   **Campos no CRM**: Motivo de Perda (Closed Lost Reason), Aprendizado Registrado.

### 12. Nutrição (Nurturing)
*   **Objetivo**: Manter relacionamento de longo prazo sem pressão comercial.
*   **Critério de Entrada**: Lead qualificado sem timing de compra no momento.
*   **Critério de Saída**: Reabertura de contato direto para novo diagnóstico.
*   **Campos no CRM**: Frequência de Nutrição, Último Conteúdo Compartilhado.

---

## 🚫 Motivos de Perda no HubSpot (Closed Lost Reasons)

1.  **Sem Orçamento (Price)**: Orçamento abaixo do ticket mínimo de R$ 1.000.
2.  **Sem Timing / Sem Urgência**: Lead com interesse, mas prioridades operacionais vigentes.
3.  **Fornecedor Atual Satisfatório**: Lead atendido por agência/designer interno sem intenção de mudança.
4.  **Silenciou / Sem Resposta**: Ausência de retorno após cadência completa de follow-ups.
5.  **Desqualificado (Anti-ICP)**: Identificação posterior de Red Flags graves ou des alinhamento cultural.
