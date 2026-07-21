# Modelo Operacional do HubSpot — Eme Creative Hub

Este documento estabelece as diretrizes de governança, cadastro, atualização e integração do **HubSpot** como a **fonte oficial e única da verdade comercial** da Eme Creative Hub.

---

## 🎯 Objetivo da Integração

Garantir que todas as interações, contatos, empresas, negócios, atividades e relatórios comerciais estejam centralizados no HubSpot. O repositório GitHub atua como cérebro de regras e estratégia, enquanto o HubSpot atua como a memória operacional do pipeline.

---

## 🗂️ Objetos do HubSpot Utilizados

1.  **Contacts (Contatos)**: Pessoas físicas/decisores (Fundadores, CEOs, Diretores).
2.  **Companies (Empresas)**: Organizações B2B e marcas clientes.
3.  **Deals (Negócios/Oportunidades)**: Oportunidades comerciais no pipeline de vendas.
4.  **Tasks (Tarefas)**: Lembretes de follow-up, revisões e tarefas comerciais.
5.  **Activities (Atividades)**: Logs de e-mails, notas, chamadas e interações registradas.
6.  **Lists (Listas)**: Segmentações dinâmicas e estáticas para acompanhamento.
7.  **Sequences & Campaigns**: Cadências de e-mail e campanhas de marketing estruturadas.

---

## 📋 Regras de Criação de Registros

Antes de criar qualquer registro no HubSpot, o agente ou operador deve obrigatoriamente:

1.  **Pesquisar Duplicidade**: Buscar por e-mail, domínio da empresa e nome completo no HubSpot antes de salvar.
2.  **Confirmar ao Menos Uma Fonte Pública**: Registrar a fonte de descoberta (ex: Instagram Direct, LinkedIn, Vibe Prospecting, Google).
3.  **Separar Fato de Inferência**:
    *   *Fato*: Informação confirmada em canal público (ex: "Empresa possui site com erro visual mobile").
    *   *Inferência*: Dedução lógica (ex: "Empresa parece ter dificuldade de conversão").
4.  **Preencher Apenas Informações Verificáveis**: Nunca inventar e-mails, cargos ou dados de contato. Se um dado for desconhecido, mantê-lo em branco.
5.  **Vincular Contato à Empresa**: Sempre associar o objeto *Contact* ao respectivo objeto *Company*.

---

## 🔄 Regras de Atualização e Manutenção

*   **Preservação de Dados**: Nunca sobrescrever notas ou históricos anteriores sem justificativa explícita.
*   **Próxima Melhor Ação**: Toda oportunidade ativa deve ter o campo de *Próxima Ação* e *Data de Follow-up* preenchidos.
*   **Encerrando Negócios**: Ao mover um negócio para "Closed Lost", preencher obrigatoriamente o campo *Closed Lost Reason* e a nota de aprendizado.
*   **Atualização Pós-Interação**: Toda resposta recebida ou mensagem enviada deve ser registrada na linha do tempo do objeto no HubSpot.

---

## 🛡️ Matriz de Autonomia e Aprovações

### Ações Permitidas Sem Aprovação Prévia (Autônoma)
- Pesquisar duplicidades no CRM.
- Ler e analisar registros de contatos, empresas e negócios.
- Criar ou atualizar registros de contatos/empresas com dados públicos verificados.
- Criar notas internas de contextualização e rascunhos de mensagens.
- Agendar tarefas internas de acompanhamento ou lembretes no CRM.
- Organizar listas internas e gerar relatórios operacionais.

### Ações que EXIGEM Autorização Explícita do Fundador
- **Enviar qualquer e-mail** (individual ou em massa).
- **Inscrever contatos em Sequências do HubSpot**.
- **Ativar ou modificar Workflows/Automações**.
- **Disparar ou confirmar envio de Instagram Directs**.
- **Excluir ou mesclar registros** no HubSpot.
- **Criar novas propriedades estruturais** no sistema.
- **Mudar etapas de pipelines formais**.

---

## 🚫 Proibições Absolutas

1.  **Não Criar CRM Paralelo**: Proibido manter planilhas CSV ou bancos de dados paralelos no GitHub ou Notion como cadastro oficial de leads.
2.  **Não Armazenar Credenciais**: Nunca gravar chaves de API, senhas ou tokens do HubSpot no repositório.
3.  **Não Iniciar Contato Direto**: Criar um registro no HubSpot **não autoriza** a abordagem comercial sem aprovação do fundador.
