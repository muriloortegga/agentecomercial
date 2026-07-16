# Pipeline de Vendas e Funil Comercial (Commercial Pipeline)

Este documento define a estrutura operacional de 14 etapas do funil de vendas da **Eme Creative Hub**. Cada etapa possui regras estritas de entrada, saída e prazos para manter a higiene do CRM.

---

## 🏗️ As 14 Etapas do Pipeline de Vendas

### 1. Lead Descoberto
*   **Objetivo**: Adicionar potenciais clientes mapeados ao pipeline.
*   **Critério de Entrada**: Possuir o nome da marca e um link para site ou rede social.
*   **Critério de Saída**: O agente iniciar a pesquisa detalhada do lead.
*   **Campos Obrigatórios**: Nome do Lead, Link de Origem, Status.
*   **Prazo Recomendado**: Até 2 dias nesta etapa.

### 2. Lead Pesquisado
*   **Objetivo**: Entender o perfil do lead com base em fatos e inferências.
*   **Critério de Entrada**: Início do preenchimento da pesquisa de acordo com [playbooks/LEAD_RESEARCH.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/playbooks/LEAD_RESEARCH.md).
*   **Critério de Saída**: Conclusão da pesquisa com dados gravados no perfil.
*   **Campos Obrigatórios**: Nome do Decisor, Cargo, Sinais de Necessidade.
*   **Prazo Recomendado**: Até 3 dias.

### 3. Lead Qualificado
*   **Objetivo**: Validar a aderência do lead ao ICP da empresa.
*   **Critério de Entrada**: Pesquisa concluída com sucesso.
*   **Critério de Saída**: Verificação de Red Flags concluída.
*   **Campos Obrigatórios**: Aprovação de Qualificação (Sim/Não).
*   **Prazo Recomendado**: Até 1 dia.

### 4. Lead Priorizado
*   **Objetivo**: Calcular o Score e classificar o lead em Tiers.
*   **Critério de Entrada**: Lead validado como qualificado (sem Red Flags ativos).
*   **Critério de Saída**: Score de 0 a 100 calculado e registrado.
*   **Campos Obrigatórios**: Score Final.
*   **Prazo Recomendado**: Até 1 dia.

### 5. Aquecimento (Warm-up)
*   **Objetivo**: Criar conexões orgânicas pré-abordagem.
*   **Critério de Entrada**: Lead com Score > 50 movido para fila de abordagem.
*   **Critério de Saída**: Execução de curtidas, follows ou respostas de Stories.
*   **Campos Obrigatórios**: Data de início do aquecimento.
*   **Prazo Recomendado**: De 3 a 5 dias.

### 6. Primeiro Contato (Outreach)
*   **Objetivo**: Enviar a primeira mensagem de abordagem consultiva.
*   **Critério de Entrada**: Finalização do período de aquecimento.
*   **Critério de Saída**: Mensagem enviada e registrada no CRM.
*   **Campos Obrigatórios**: Texto da abordagem enviada, Data do Envio.
*   **Prazo Recomendado**: Envio imediato ao entrar na etapa.

### 7. Conversa Iniciada
*   **Objetivo**: Estimular a resposta do lead e iniciar diálogo genuíno.
*   **Critério de Entrada**: Resposta positiva ou neutra do lead ao primeiro contato.
*   **Critério de Saída**: Identificação de que o lead possui uma dor que a Eme resolve.
*   **Campos Obrigatórios**: Data da resposta do lead, Próxima Ação.
*   **Prazo Recomendado**: Responder em até 4 horas úteis após a mensagem do lead.

### 8. Diagnóstico (Qualificação Ativa)
*   **Objetivo**: Entender a fundo os problemas criativos do lead e avaliar o momento.
*   **Critério de Entrada**: Conversa ativa fluindo no direct ou WhatsApp.
*   **Critério de Saída**: Convite aceito para chamada de diagnóstico de 10 a 15 minutos.
*   **Campos Obrigatórios**: Data agendada para a chamada, Principais Dores Documentadas.
*   **Prazo Recomendado**: Até 5 dias nesta etapa.

### 9. Reunião Agendada
*   **Objetivo**: Realizar a chamada de alinhamento e levantamento de briefing.
*   **Critério de Entrada**: Chamada marcada na agenda do fundador.
*   **Critério de Saída**: Chamada realizada com sucesso.
*   **Campos Obrigatórios**: Resumo do Briefing.
*   **Prazo Recomendado**: Ocorrer em até 7 dias úteis.

### 10. Proposta Comercial
*   **Objetivo**: Desenhar a proposta personalizada e o escopo financeiro.
*   **Critério de Entrada**: Reunião de briefing realizada.
*   **Critério de Saída**: Apresentação/PDF de proposta enviado ao cliente.
*   **Campos Obrigatórios**: Valor da Proposta, Data de Validade da Proposta.
*   **Prazo Recomendado**: Enviar em até 3 dias úteis após a reunião.

### 11. Negociação
*   **Objetivo**: Ajustar termos contratuais, escopos e formas de pagamento.
*   **Critério de Entrada**: Proposta enviada e aberta para debate.
*   **Critério de Saída**: Acordo verbal fechado ou recusa final do lead.
*   **Campos Obrigatórios**: Data de Follow-up ativa.
*   **Prazo Recomendado**: Até 10 dias de negociação ativa.

### 12. Ganho (Won)
*   **Objetivo**: Iniciar onboarding do novo cliente e faturamento.
*   **Critério de Entrada**: Contrato assinado ou primeiro pagamento compensado.
*   **Critério de Saída**: Passagem do cliente para o time de entrega (Designers/Freelancers).
*   **Campos Obrigatórios**: Valor do Contrato Fechado, Data de Início.
*   **Prazo Recomendado**: Imediato.

### 13. Perdido (Lost)
*   **Objetivo**: Rastrear perdas e extrair aprendizados operacionais.
*   **Critério de Entrada**: Lead recusa a proposta ou silencia na cadência completa de follow-up.
*   **Critério de Saída**: Arquivamento da oportunidade.
*   **Campos Obrigatórios**: Motivo de Perda, Aprendizado Obtido.
*   **Prazo Recomendado**: Imediato.

### 14. Nutrição (Nurturing)
*   **Objetivo**: Manter contato passivo enviando insights em intervalos longos.
*   **Critério de Entrada**: Lead qualificado sem timing de compra no momento.
*   **Critério de Saída**: Lead demonstrar interesse ativo novamente e voltar para "Conversa Iniciada".
*   **Campos Obrigatórios**: Intervalo de Contato (ex: a cada 30 dias).
*   **Prazo Recomendado**: Sem prazo (fluxo contínuo).

---

## 🚫 Motivos de Perda Padronizados (Lost Reasons)
Ao mover um lead para a etapa **Perdido**, selecione obrigatoriamente um destes motivos:
1.  *Sem orçamento (Price)*: O lead achou o valor acima de sua capacidade financeira.
2.  *Sem timing/Urgência*: O lead tem interesse, mas priorizou outros investimentos no momento.
3.  *Parceria existente*: O lead já possui uma agência ou designer que atende perfeitamente.
4.  *Sem resposta (Silenciou)*: O lead parou de responder durante a negociação ou cadência de follow-up.
5.  *Perfil inadequado (Anti-ICP)*: Identificamos Red Flags graves após iniciada a conversa.
