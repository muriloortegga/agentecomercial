# Briefing de Execução para o Claude Cowork

> **Instrução:** Este documento é um briefing autocontido para ser utilizado pelo Claude Cowork na execução da missão `2026-07-22_primeiros-leads-hubspot`.

---

## 🎯 Objetivo do Claude Cowork

Pesquisar, qualificar, calcular score, verificar duplicidades e cadastrar no **HubSpot** os primeiros **15 leads reais** da Eme Creative Hub, preparando rascunhos de abordagens consultivas para os 5 melhores perfis sem realizar nenhum contato externo.

---

## 🛠️ Passo a Passo de Execução no Cowork

### Passo 1: Leitura do Contexto e Diretrizes
1. Ler o contexto institucional em [context/COMPANY_CONTEXT.md](../context/COMPANY_CONTEXT.md) e [context/OFFER_CONTEXT.md](../context/OFFER_CONTEXT.md).
2. Ler as definições de ICP em [context/ICP_CONTEXT.md](../context/ICP_CONTEXT.md).
3. Ler o tom de voz em [context/BRAND_VOICE.md](../context/BRAND_VOICE.md).

### Passo 2: Pesquisa e Mineração de Leads
1. Buscar empresas reais em **Cotia, Vargem Grande Paulista, SP e Brasil B2B** (serviços profissionais, engenharia, arquitetura, tecnologia, consultorias) usando Google, Instagram, Vibe Prospecting ou Apollo.
2. Identificar o nome do fundador/decisor, o e-mail corporativo público e o perfil do Instagram/site.
3. Procurar evidências reais de necessidade (ex: marca visualmente fraca, desalinhamento entre Instagram e site, falta de materiais comerciais).

### Passo 3: Verificação de Duplicidade no HubSpot
1. Antes de salvar, consultar o e-mail ou domínio no HubSpot para garantir que o lead não está cadastrado.

### Passo 4: Cadastro e Qualificação no HubSpot
1. Criar os objetos *Contact* e *Company* no HubSpot preenchendo:
   - Nome completo do decisor e cargo.
   - Nome oficial da empresa e domínio do site.
   - Segmento e localização (Cotia/VGP/SP/Brasil).
   - E-mail e redes sociais verificadas.
   - Sinais observados de necessidade e capacidade.
   - Score calculado (0 a 100) e justificativa.
   - Canal recomendado (*Instagram Direct* ou *E-mail Individual*).

### Passo 5: Preparação dos Rascunhos de Abordagem
1. Para os 5 melhores leads (maior Score), redigir um rascunho de abordagem consultiva personalizada baseada em uma observação real.
2. Salvar o rascunho como Nota/Campo no HubSpot.

---

## 🛑 REGRAS DE SEGURANÇA E PROIBIÇÕES DO COWORK

*   **NÃO enviar e-mails.**
*   **NÃO enviar Instagram Directs.**
*   **NÃO inscrever contatos em sequências.**
*   **NÃO ativar campanhas ou workflows.**
*   **NÃO excluir ou mesclar registros no CRM.**
*   **NÃO criar novas propriedades estruturais sem autorização.**
*   **NÃO fazer git commit ou git push.**
*   **NÃO inventar dados de contato (e-mail, cargo, telefone).**

---

## 📋 Entregável Final do Cowork

Produzir um relatório final contendo:
1. Lista dos 15 leads cadastrados no HubSpot (Nome da empresa, Decisor, Score e Canal Recomendado).
2. Os 5 rascunhos de abordagem submetidos para revisão do fundador no [operations/COMMAND_CENTER.md](../operations/COMMAND_CENTER.md).
3. Confirmação de que nenhum envio, ativação ou commit foi realizado.
