# Padrões de Entrega (Output Standards)
> **Versão**: 0.2 — Núcleo Operacional

Define formatação, componentes obrigatórios e padrões específicos para cada tipo de entrega do Agente Comercial.

---

## 📋 Estrutura Geral de Entregas de Alta Relevância

Toda análise, plano ou recomendação estratégica deve conter, quando aplicável:

| Campo | Descrição |
|---|---|
| **Objetivo** | Uma frase sobre o que a entrega resolve. |
| **Contexto** | Dados e informações de apoio disponíveis. |
| **Diagnóstico** | Problema ou oportunidade identificada. |
| **Hipótese** | O que acreditamos ser verdade e que será testado. |
| **Recomendação** | Proposta direta de solução ou ação. |
| **Plano** | Etapas sequenciais para execução. |
| **Responsáveis** | Agente Comercial ou Fundador — para cada etapa. |
| **Matriz ICE** | Impacto (1–10), Confiança (1–10), Esforço (1–10). |
| **Riscos** | Efeitos colaterais negativos ou falhas prováveis. |
| **Dependências** | Bloqueios externos ou entradas necessárias. |
| **Métrica de Sucesso** | KPI que medirá se a recomendação funcionou. |
| **Próxima Melhor Ação** | Ver seção específica abaixo. |

---

## ✅ Padrão de Próxima Melhor Ação (NBA)

Qualquer lead ou oportunidade ativa deve ter uma próxima ação definida com os seguintes campos:

| Campo | Descrição |
|---|---|
| **Etapa atual** | Etapa exata no pipeline. |
| **Último contato ou observação** | Data e resumo. |
| **Próxima melhor ação** | Ação específica e executável. |
| **Responsável** | Agente ou Fundador. |
| **Data ou condição** | Quando ou sob qual condição executar. |
| **Justificativa** | Por que esta é a melhor próxima ação. |
| **Risco de não agir** | O que se perde se a ação não for feita. |
| **Critério para avançar ou encerrar** | O que define que esta etapa está concluída. |

**Próximas ações proibidas** (vagas demais para gerar execução):

> ❌ "Acompanhar" · "Manter contato" · "Pesquisar mais" · "Falar depois" · "Ver com calma"

**Exemplos de próximas ações válidas:**

> ✅ "Enviar follow-up com link do case de SaaS rebranding até quinta-feira" 
> ✅ "Aguardar resposta até dia 22; se sem retorno, iniciar mensagem de encerramento" 
> ✅ "Agendar chamada de 15 min para apresentar proposta — condição: lead confirmar interesse"

---

## 📊 Padrão para Dashboards e Relatórios

Todo dashboard ou relatório deve responder uma pergunta de negócio. Não criar dashboard apenas para visualização.

Campos obrigatórios para cada métrica apresentada:

| Campo | Descrição |
|---|---|
| **Pergunta respondida** | Qual decisão este dado apoia? |
| **Público** | Quem usa este dado? |
| **Período** | Janela de tempo analisada. |
| **Fonte** | De onde vem o dado. |
| **Fórmula** | Como a métrica é calculada. |
| **Frequência de atualização** | Diária, semanal, mensal. |
| **Limitações** | O que este dado não captura. |
| **Ação esperada** | O que deve acontecer se o valor estiver abaixo/acima do threshold. |

---

## 🗃️ Padrão para CRM e Pipeline

O CRM só é útil se os campos forem consistentemente preenchidos. Campos obrigatórios para oportunidades ativas:

| Campo | Obrigatório? | Origem | Responsável |
|---|---|---|---|
| ID / Nome do Lead | ✅ Sim | Pesquisa | Lead Intelligence |
| Etapa Atual | ✅ Sim | Pipeline | CRM Manager |
| Score (0–100) | ✅ Sim | Scoring | Lead Intelligence |
| Origem (Source) | ✅ Sim | Registro | SDR |
| Valor Estimado | ✅ Sim | Estimativa | Growth Strategist |
| Data Último Contato | ✅ Sim | Histórico | SDR / Fundador |
| Próxima Melhor Ação | ✅ Sim | Análise | CRM Manager |
| Data de Follow-up | ✅ Sim | Planejamento | CRM Manager |
| Histórico de Conversas | ✅ Sim | Registro | SDR / Fundador |
| Ativo de Conteúdo Enviado | ⬜ Opcional | Registro | SDR |
| Motivo de Perda | ✅ Se perdido | Análise | CRM Manager |
| Aprendizado | ✅ Se perdido | Reflexão | CRM Manager |

**Regra de arquivamento**: leads sem interação há mais de 15 dias na mesma etapa devem ser movidos para Nutrição ou marcados como Perdidos — nunca mantidos como "ativos" sem próxima ação.

**Critério de qualidade**: um campo "Próxima Melhor Ação" vago é equivalente a ausente.

---

## 🛠️ Padrões Específicos por Tipo de Artefato

### 📄 1. Plano Comercial
- Canal de aquisição definido, segmentação de ICP específica, orçamento (se houver).
- Cronograma semanal dividido em fases: teste → validação → escala.

### 👥 2. Lista de Leads

Tabela obrigatória com colunas:

| Empresa | Decisor | Cargo | Canal | Score | Status | Link Perfil |
|---|---|---|---|---|---|---|

### 🔍 3. Análise de Lead Individual
- Dividir em: `[Fato]` (observado no site/posts) e `[Inferência]` (leitura de gargalos prováveis).
- Proposta do gancho de conversa com justificativa baseada em fato verificável.
- Nível de evidência explícito para cada informação usada.

### 💬 4. Mensagem de Abordagem
- Texto limpo, sem clichês ou frases motivacionais de vendas.
- Estrutura: Contexto Real Observado + Dúvida/Dor Provável + Pergunta de Baixo Atrito.
- **Entregue sempre como rascunho** — aguarda aprovação do fundador antes de qualquer envio.

### 📅 5. Cadência de Contato
- Dias de contato (Dia 1, Dia 3, Dia 7…).
- Canal e variação de mensagem para cada dia.
- Critério de encerramento explícito.

### 🧪 6. Experimento Comercial
- Preencher via [templates/EXPERIMENT_TEMPLATE.md](../templates/EXPERIMENT_TEMPLATE.md).
- Nível de evidência alvo (ver [core/DECISION_RULES.md § Níveis de Evidência](DECISION_RULES.md)).
- Critérios de sucesso: não apenas taxa de resposta, mas qualidade da resposta, avanço no pipeline, esforço e impacto na reputação.

### ⚙️ 7. Automação de Processo
- Fluxograma: Trigger → Action → Fallback.
- Tempo economizado vs. tempo de manutenção estimado.
- Resposta às 5 perguntas do princípio do menor sistema necessário.

### 📋 8. Procedimento Operacional Padrão (POP)
- Passos sequenciais, exceções, tratamento de erros.
- Data de criação e de próxima revisão.

### 🚀 9. Missão Comercial
- Usar [templates/MISSION_TEMPLATE.md](../templates/MISSION_TEMPLATE.md).
- Status deve ser um dos definidos em [core/EXECUTION_PROTOCOL.md § Status de Missões](EXECUTION_PROTOCOL.md).
