# Playbook — Gestão e Higiene de CRM (CRM Management)

Este playbook orienta como organizar, atualizar e manter saudável a base de contatos e oportunidades comerciais.

---

## 🎯 Objetivo
Garantir que a operação comercial possua visibilidade total sobre o status de cada lead no funil, mantendo a higiene dos dados (sem leads abandonados) de forma a apoiar tomadas de decisão ágeis e assertivas.

---

## 🚦 Quando Usar e Quando Não Usar

*   **Quando Usar**: Diariamente durante as rotinas operacionais comerciais e semanalmente nas reuniões de fechamento de métricas.
*   **Quando Não Usar**: Para armazenar leads frios não qualificados ou contatos pessoais desvinculados da operação comercial.

---

## 📥 Entradas
*   Pipeline atualizado em [operations/COMMERCIAL_PIPELINE.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/operations/COMMERCIAL_PIPELINE.md).
*   Histórico recente de abordagens e interações comerciais.

---

## 🗂️ Campos Mínimos Obrigatórios no CRM
Toda oportunidade registrada na base de dados comercial deve conter, no mínimo:

1.  **ID/Nome do Lead**: Nome do decisor e/ou nome da empresa.
2.  **Etapa Atual**: Etapa exata do funil (de acordo com o pipeline).
3.  **Score**: Pontuação do lead (0 a 100).
4.  **Origem (Source)**: De onde veio o lead (ex: Instagram, Indicação, SEO).
5.  **Valor Estimado**: Receita provável do contrato se a venda for fechada.
6.  **Último Contato**: Data da última mensagem enviada/recebida.
7.  **Próxima Ação**: Descrição objetiva da próxima tarefa comercial (ex: "Enviar proposta").
8.  **Data de Follow-up**: Data em que a próxima ação deve ser realizada.
9.  **Histórico de Conversas**: Notas das principais trocas de mensagens e telefonemas.
10. **Responsável**: Dono da conta (ex: Fundador ou Agente).
11. **Motivo de Perda**: Obrigatório preencher se o lead for para "Perdido" (ex: Preço, Sem timing).
12. **Aprendizado**: Principal lição absorvida durante a negociação desse lead.

---

## 🏗️ Comparativo de Ferramentas de CRM

| Ferramenta | Vantagens | Desvantagens | Quando Escolher |
| :--- | :--- | :--- | :--- |
| **Google Sheets** | Extremamente simples, gratuito, fácil de customizar e integrar com ferramentas automáticas. | Sem controle de histórico estruturado, difícil de gerenciar anotações de conversas longas. | **Fase Inicial (Recomendado)** para testes rápidos de volume pequeno. |
| **Notion** | Visualização excelente em Kanban (quadros), boa gestão de documentos e notas integradas por lead. | Pode se tornar lento com milhares de registros, integrações automáticas mais complexas. | **Fase Intermediária (Recomendado)** para manter relatórios e perfis estruturados no mesmo local. |
| **Airtable** | Combina poder de banco de dados com a facilidade de planilhas. Ótimas automações internas. | Curva de aprendizado média, planos pagos podem ser caros para uso individual. | Para operações com automação de enriquecimento de leads e alertas estruturados. |
| **CRM Dedicado** *(ex: HubSpot)* | Automações robustas de e-mails, relatórios automáticos e controle nativo de atividades de vendas. | Excessivamente complexo para o estágio inicial, configuração demorada, custos altos. | Apenas quando o fundador delegar a operação para um time comercial de vendas ativo. |

*Recomendação para a Eme Creative Hub*: Iniciar utilizando o próprio formato documental em Markdown ou uma tabela simples no **Notion/Google Sheets** até validar as primeiras 5 vendas com o novo método.

---

## 🧹 Rotina de Higiene do CRM
Para manter a base de dados limpa e útil, o CRM Manager deve executar semanalmente:
1.  **Varredura de Prazos**: Mover qualquer lead que esteja na mesma etapa há mais de 15 dias sem interação para "Nutrição" ou "Perdido".
2.  **Validação de Próxima Ação**: Garantir que nenhum lead ativo no funil fique sem uma "Próxima Ação" e "Data de Follow-up" preenchidos.
3.  **Auditoria de Motivos de Perda**: Verificar se todas as oportunidades marcadas como "Perdido" possuem o motivo e o aprendizado documentados.

---

## ❌ Erros Comuns
*   **Criar campos excessivos**: Adicionar dezenas de colunas que ninguém preencherá na rotina diária.
*   **Manter leads "fantasmas"**: Deixar oportunidades na etapa "Negociação" por meses sem resposta apenas para inflar o valor do pipeline.

---

## 📊 Métricas do Playbook
*   **Taxa de Higiene do CRM**: Meta de 100% de conformidade com os campos obrigatórios em oportunidades ativas.

---

## 📋 Checklist de Gestão do CRM
- `[ ]` Atualizei o status de todos os leads que interagiram hoje?
- `[ ]` Preenchi o campo de "Próxima Ação" e "Data de Follow-up" para todos os leads ativos?
- `[ ]` Documentei o motivo e o aprendizado de todas as oportunidades perdidas?
- `[ ]` Removi os contatos inativos das etapas de fechamento?
