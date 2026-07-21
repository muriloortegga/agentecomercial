# Mapa de Propriedades do HubSpot — Eme Creative Hub

Este documento mapeia o dicionário de dados e propriedades necessárias para os objetos **Contact (Contato)** e **Company (Empresa)** no HubSpot, separando propriedades nativas de propriedades customizadas propostas.

---

## 🗂️ 1. Objeto: CONTACT (Contato / Decisor)

### Propriedades Nativas do HubSpot (Existentes)
*   `firstname` — Primeiro Nome do Decisor
*   `lastname` — Sobrenome do Decisor
*   `email` — E-mail Profissional Verificado
*   `jobtitle` — Cargo (ex: Fundador, CEO, Diretor de Marketing)
*   `phone` / `mobilephone` — Telefone de Contato / WhatsApp (quando público e legítimo)
*   `linkedin_url` — Perfil Profissional do Decisor
*   `lifecyclestage` — Estágio no Ciclo de Vida (Subscriber, Lead, MQL, SQL, Opportunity, Customer)
*   `hs_lead_status` — Status do Lead (New, Open, In Progress, Unqualified, Connected)

### Propriedades Customizadas Propostas (Aguardando Aprovação para Criação)
*   `icp_type` — Tipo de ICP (*Nacional* vs. *Internacional Assíncrono*)
*   `lead_score` — Score de Qualificação (0 a 100)
*   `lead_score_reason` — Justificativa Resumida do Score
*   `recommended_channel` — Canal Recomendado (*Instagram Direct*, *E-mail Individual*, *Sequência HubSpot*)
*   `outreach_draft` — Rascunho da Abordagem Consultiva Redigida
*   `approval_status` — Status de Aprovação do Fundador (*Rascunho*, *Aprovado*, *Rejeitado*)
*   `observed_facts` — Fatos Observados em Canais Públicos
*   `grounded_inferences` — Inferências Estratégicas sobre o Negócio

---

## 🏢 2. Objeto: COMPANY (Empresa / Marca)

### Propriedades Nativas do HubSpot (Existentes)
*   `name` — Nome Oficial / Razão Social da Empresa
*   `domain` — Domínio do Site Oficial (ex: `empresa.com.br`)
*   `industry` — Segmento de Atuação (Engenharia, Serviços Profissionais, Tecnologia, etc.)
*   `city` / `state` — Cidade e Estado da Operação (ex: Cotia, SP)
*   `country` — País (Brasil, EUA, etc.)
*   `numberofemployees` — Porte Estimado da Equipe
*   `description` — Descrição Curta da Atividade

### Propriedades Customizadas Propostas (Aguardando Aprovação para Criação)
*   `need_signals` — Sinais Observados de Necessidade (ex: Identidade fraca, site antigo, material desalinhado)
*   `capacity_signals` — Sinais Observados de Capacidade Financeira (ex: Vagas abertas, anúncios ativos, sede própria)
*   `red_flags` — Alertas de Desqualificação ou Riscos Identificados
*   `probable_service` — Oferta Recomendada (*Ecossistema de Marca*, *Identidade Visual*, *Site*, *Conteúdo*, *Internacional USD*)
*   `brand_asset_gap` — Lacuna de Ativos de Marca Identificada

---

## 📑 3. Objeto: DEAL (Negócio / Oportunidade)

### Propriedades Nativas do HubSpot (Existentes)
*   `dealname` — Nome do Negócio (ex: *[Nome da Empresa] — Ecossistema de Marca*)
*   `pipeline` — Pipeline Comercial Padrão
*   `dealstage` — Etapa do Negócio no Funil
*   `amount` — Valor Estimado do Contrato (R$)
*   `closedate` — Data Prevista de Fechamento
*   `closed_lost_reason` — Motivo Obrigatório de Perda

### Propriedades Customizadas Propostas (Aguardando Aprovação para Criação)
*   `payment_terms_notes` — Condições e Parcelamento Negociados
*   `learning_log_notes` — Aprendizado Extraído da Negociação

---

## 🛑 Protocolo de Adição de Novas Propriedades

Antes de criar qualquer nova propriedade no HubSpot via API ou Painel:
1.  Verificar se existe uma propriedade nativa equivalente no HubSpot.
2.  Submeter a proposta de nova propriedade ao fundador pelo comando:  
    `Aprovar criação das propriedades [nomes]`.
3.  Registrar a criação aprovada neste mapa documental.
