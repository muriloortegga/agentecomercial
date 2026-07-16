# Playbook — Pontuação de Leads (Lead Scoring)

Este playbook orienta o cálculo de pontuação (scoring) dos leads no pipeline comercial para priorização das abordagens.

---

## 🎯 Objetivo
Estabelecer um modelo matemático e analítico simples (0 a 100 pontos) para priorizar contatos comerciais de alto impacto e menor esforço para a Eme Creative Hub, evitando desperdício de tempo com leads frios ou sem verba.

---

## 🚦 Quando Usar e Quando Não Usar

*   **Quando Usar**: Após a finalização da pesquisa do lead ([playbooks/LEAD_RESEARCH.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/playbooks/LEAD_RESEARCH.md)) e antes de colocá-lo na fila de abordagem do pipeline.
*   **Quando Não Usar**: Para leads que já estão em conversas ativas de proposta comercial ou pós-reunião.

---

## 📥 Entradas
*   Perfil do lead preenchido com dados reais da pesquisa comercial.
*   Critérios de ICP ([context/ICP_CONTEXT.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/context/ICP_CONTEXT.md)).

---

## 🔢 Modelo de Pontuação (0 a 100 Pontos)

O Score final do lead é a soma dos pontos obtidos nas 9 categorias abaixo.

| Categoria | Critério | Pontuação Máxima |
| :--- | :--- | :---: |
| **1. Aderência ao ICP** | Alinhamento com os segmentos e nichos ideais (Tier 1 = 20 pts, Tier 2 = 10 pts, Outros = 0 pts). | **20 pontos** |
| **2. Sinal de Necessidade** | Problema ou gargalo visual evidente e documentável no site ou posts. | **15 pontos** |
| **3. Capacidade Aparente** | Indícios de saúde financeira (anúncios rodando, tamanho do time, relevância no mercado). | **15 pontos** |
| **4. Acesso ao Decisor** | Perfil do Instagram/LinkedIn do decisor mapeado e ativo para envio de mensagem. | **10 pontos** |
| **5. Qualidade do Contexto** | Facilidade de encontrar um gancho de conversa real e personalizado (sem inventar). | **10 pontos** |
| **6. Timing** | Momento de mercado propício (ex: contratações abertas, lançamento recente). | **10 pontos** |
| **7. Potencial de Ticket** | Probabilidade do lead ter orçamento para comprar a Oferta Principal de design. | **10 pontos** |
| **8. Fator de Risco (Inverso)**| Menor presença de Red Flags estratégicos ou de relacionamento (Sem risco = 5 pts, Risco médio = 0 pts). | **5 pontos** |
| **9. Esforço de Abordagem** | Proximidade de canal ou baixa barreira de aproximação (ex: o lead já segue a Eme). | **5 pontos** |
| **Total Máximo** | **Soma das Categorias** | **100 pontos** |

---

## 🚦 Classificação de Prioridades por Pontuação

*   **Score de 80 a 100 (Tier 1 - Prioridade Crítica)**: Abordar individualmente com personalização máxima.
*   **Score de 50 a 79 (Tier 2 - Prioridade Média)**: Abordar utilizando estruturas com templates adaptáveis.
*   **Score abaixo de 50 (Tier 3 - Baixa Prioridade)**: Não abordar no momento. Manter em lista de nutrição de conteúdo orgânico.

---

## 🚫 Importante: O Score não é Verdade Absoluta
O score serve como um guia inicial para otimizar o tempo do fundador. Um lead com score de 70 que demonstra um sinal de necessidade urgente e imediato de design deve ser priorizado antes de um lead de score 85 que está sem urgência. O bom senso e o contexto real de conversas superam o cálculo matemático.

---

## 🔄 Como Revisar os Pesos com Dados Reais
A cada ciclo de 30 dias:
1.  Analise quais leads geraram as melhores reuniões e contratos fechados.
2.  Verifique quais categorias desta tabela previram com maior acurácia o sucesso comercial.
3.  Ajuste a pontuação máxima das categorias (ex: se "Acesso ao Decisor" for o fator decisivo para a venda, aumente o peso dele e reduza o peso de "Capacidade Aparente").

---

## ❌ Erros Comuns
1.  **Dar pontuação máxima a dados inferidos**: Pontuar com nota máxima "Capacidade Aparente" sem ter visto anúncios ativos ou faturamento.
2.  **Ignorar desqualificadores**: Dar nota 60 a um lead que possui um anti-ICP evidente (Red Flag crítico).

---

## 📊 Métricas do Playbook
*   **Taxa de Abordagem de Alta Prioridade**: Garantir que 100% dos leads abordados no mês possuam score igual ou superior a 50 pontos.

---

## 📋 Checklist de Scoring
- `[ ]` Preenchi as notas de todas as 9 categorias com base nos fatos da pesquisa?
- `[ ]` Verifiquei se o lead possui desqualificadores ativos (Red Flags)?
- `[ ]` Registrei o valor do Score final na planilha/CRM do pipeline?
