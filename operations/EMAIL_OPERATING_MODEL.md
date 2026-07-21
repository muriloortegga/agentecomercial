# Modelo Operacional de E-mail — Eme Creative Hub

Este documento define a separação estratégica entre o uso de **E-mails Individuais via Gmail** e **Sequências de E-mail via HubSpot**, estabelecendo os fluxos de trabalho e as travas de segurança da Eme Creative Hub.

---

## 🆚 E-mail Individual (Gmail) vs. Sequência (HubSpot)

| Critério | E-mail Individual (via Gmail) | Sequência de E-mail (via HubSpot) |
|---|---|---|
| **Quando usar** | Leads estratégicos Tier 1, respostas a conversas, propostas personalizadas, follow-ups de alta sensibilidade. | Grupos coerentes de leads B2B qualificados com perfil e dore semelhantes. |
| **Ferramenta** | Gmail (Manual / Assistido) | HubSpot Sequences |
| **Nível de Personalização** | **Alta / Total** (baseada em observações específicas do site, posicionamento e marca). | **Média / Estruturada** (templates com campos personalizados e contextualizados por segmento). |
| **Aprovação** | Rascunho submetido individualmente ao fundador antes do envio. | Aprovação formal da lista e do template da sequência antes da inscrição. |
| **Critério de Saída** | Resposta do lead ou encerramento da oportunidade. | Automático assim que o lead responde ou agenda reunião. |

---

## 📧 1. Fluxo de E-mail Individual pelo Gmail

Utilizado para abordagens altamente consultivas de alto valor:

1.  **Pesquisar & Qualificar**: Mapear o lead, identificar uma dor ou inconsistência de marca e verificar o e-mail corporativo.
2.  **Redigir Rascunho**: O agente ou operador redige uma mensagem curta, direta e consultiva (seguindo o tom de voz em `context/BRAND_VOICE.md`).
3.  **Registrar no CRM**: Salvar o rascunho da mensagem no campo `outreach_draft` ou como Nota no HubSpot.
4.  **Solicitar Autorização**: Apresentar a mensagem ao fundador via comando ou relatório.
5.  **Enviar pós-Aprovação**: O fundador autoriza ou realiza o envio através do Gmail.
6.  **Registrar na Linha do Tempo**: Marcar a atividade de e-mail enviado no HubSpot.
7.  **Agendar Próxima Ação**: Criar uma tarefa de follow-up no HubSpot para 3 a 5 dias úteis.

---

## 🚀 2. Fluxo de Sequência de E-mail no HubSpot

Utilizado quando há um grupo coerente de leads qualificados do mesmo nicho B2B:

1.  **Definir Segmento & Hipótese**: Selecionar um grupo de leads qualificados no HubSpot (ex: PMEs de Engenharia em SP).
2.  **Criar Lista de Trabalho**: Agrupar os contatos no HubSpot em uma Lista Estática.
3.  **Desenhar a Sequência**: Estruturar de 2 a 4 passos de e-mail intercalados por tarefas manuais de acompanhamento.
4.  **Revisar Variáveis de Personalização**: Garantir que cada contato na lista tenha os campos de personalização preenchidos.
5.  **Definir Critérios de Entrada e Saída**:
    *   *Entrada*: Lead qualificado no Tier 1 ou 2 sem contato prévio.
    *   *Saída*: Resposta do e-mail, clique no link de agendamento ou pedido de descadastro.
6.  **Submeter a Sequência para Aprovação**: Apresentar o modelo da sequência e a lista de contatos ao fundador através do comando:  
    `Aprovar inscrição na sequência [nome] para [IDs]`.
7.  **Inscrever Apenas Contatos Aprovados**: Iniciar a sequência no HubSpot somente após autorização explícita.
8.  **Monitorar & Interromper**: Se um lead responder, a sequência é interrompida automaticamente pelo HubSpot.

---

## 🚫 Regras Proibidas no Uso de E-mail

1.  **PROIBIDO envio sem aprovação**: Nenhum e-mail individual ou disparo de sequência pode ocorrer sem autorização formal do fundador.
2.  **PROIBIDA inclusão automática de novos contatos**: Nunca inscrever automaticamente um lead recém-cadastrado em uma sequência sem qualificação e aprovação prévias.
3.  **PROIBIDAS mensagens genéricas ("Spam")**: E-mails com elogios superficiais falsos ou propostas milagrosas de vendas são terminantemente proibidos.
4.  **PROIBIDO manter na sequência após resposta**: Se o lead responder por qualquer canal (e-mail, Instagram, telefone), remover o contato da sequência imediatamente.
