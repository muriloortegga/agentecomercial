# Playbook — Desenho e Decisão de Automações (Automation Design)

Este playbook orienta como avaliar, desenhar e implementar integrações e automações na operação comercial da **Eme Creative Hub**.

---

## 🎯 Objetivo
Evitar a criação de automações frágeis ou desnecessárias que geram custos e manutenção complexa. O foco é estabelecer critérios de seleção claros sobre quando automatizar um processo ou quando mantê-lo manual/semiautomático.

---

## 🚦 Quando Usar e Quando Não Usar

*   **Quando Usar**: Ao planejar integrar ferramentas (ex: enviar contatos de leads qualificados do direct para o Notion automaticamente ou gerar alertas no WhatsApp).
*   **Quando Não Usar**: Para processos novos que ainda estão sendo validados de forma manual pela primeira vez.

---

## 📥 Entradas
*   Fluxo do processo manual atual desenhado.
*   Estimativa de tempo e frequência gasto na tarefa manual.
*   Diretrizes de [core/DECISION_RULES.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/core/DECISION_RULES.md).

---

## 🏗️ Matriz de Decisão: Quando Automatizar?

| Categoria | Frequência | Tempo Gasto | Previsibilidade | Ação Recomendada |
| :--- | :---: | :---: | :---: | :--- |
| **Manter Manual** | Baixa (< 5x/mês) | Baixo (< 10 min) | Baixa / Criativo | Interação direta, prospecção personalizada e negociações. |
| **Semiautomatizar** | Média (diário) | Médio (2h/semana) | Média / Regras claras | Geração de rascunhos de mensagens, alertas de follow-ups no CRM. |
| **Automatizar** | Alta (diário) | Alto (> 3h/semana) | Alta / Lógica fixa | Transferência de dados, atualização de planilhas de relatórios, backups. |
| **Não Fazer** | Baixa | Alto | Muito baixa | Integrações complexas com plataformas fechadas ou instáveis. |

---

## 🔄 Fluxo de Desenvolvimento da Automação

Ao decidir automatizar, documente o processo seguindo estas etapas:

1.  **Processo Atual**: Como o fluxo funciona manualmente hoje?
2.  **Frequência e Tempo**: Quantas vezes a tarefa ocorre e quantas horas mensais ela consome?
3.  **Entradas (Inputs)**: Quais dados exatos entram no fluxo (ex: Nome do Lead, Perfil do Instagram, Data)?
4.  **Saídas (Outputs)**: O que o fluxo deve gerar no final (ex: Nova linha na tabela do Notion)?
5.  **Previsibilidade**: O processo possui desvios criativos ou é 100% lógico e padronizado?
6.  **Custo Estimado**: Qual o valor das licenças de ferramentas de integração (ex: Make, Zapier) necessárias?
7.  **Manutenção**: Quem dará suporte se a automação falhar?

---

## ⚙️ Regras de Resiliência: Erros e Fallback

Toda automação deve prever o que fazer se algo der errado:

*   **Tratamento de Erros**: Se uma etapa falhar, o fluxo não deve travar silenciosamente. Configure notificações imediatas de erro para o WhatsApp ou e-mail do fundador.
*   **Logs**: Mantenha registros curtos com data, hora, ID do lead e status de cada execução do fluxo automático.
*   **Revisão Humana**: Antes de enviar mensagens automáticas diretas a leads, o fluxo deve criar um rascunho pendente de aprovação humana.
*   **Fallback (Alternativa de Erro)**: Se a API do Instagram cair, a automação deve salvar os leads em uma planilha de backup para tratamento manual posterior.

---

## ❌ Erros Comuns
*   **Automatizar processos instáveis**: Tentar automatizar uma tarefa manual que muda de formato a cada semana.
*   **Desprezar o tempo de manutenção**: Esquecer que automações quebram frequentemente por atualizações de APIs e demandam tempo de reparo.

---

## 📊 Métricas do Playbook
*   **Índice de Resiliência**: Garantir que 95% das execuções automáticas ocorram sem erros críticos ou perda de dados de leads.

---

## 📋 Checklist de Desenho de Automação
- `[ ]` Testei o processo manualmente com sucesso pelo menos 10 vezes antes de planejar a automação?
- `[ ]` Desenhei as entradas, saídas e a lógica do fluxo?
- `[ ]` Defini um fluxo de fallback manual caso a API falhe?
- `[ ]` O tempo economizado cobre o tempo de configuração e custo da ferramenta?
