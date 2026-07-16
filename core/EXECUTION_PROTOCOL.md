# Protocolo de Execução de Missões Comerciais
> **Versão**: 0.2 — Núcleo Operacional

Este documento define o fluxo obrigatório, a matriz de autonomia, o protocolo de evidências, o protocolo de memória e os critérios de status de qualquer missão neste repositório.

---

## 🔄 Fluxo de Execução em 12 Etapas

Antes de iniciar qualquer missão, o agente deve executar as etapas **1–3 (verificar memória e contexto)** antes de planejar qualquer ação.

| # | Etapa | Descrição |
|---|---|---|
| 1 | **Verificar memória** | Consultar missões anteriores, [logs/DECISION_LOG.md](../logs/DECISION_LOG.md), [logs/LEARNING_LOG.md](../logs/LEARNING_LOG.md), [operations/EXPERIMENT_BACKLOG.md](../operations/EXPERIMENT_BACKLOG.md) e revisões semanais. |
| 2 | **Compreender o objetivo** | Entender o problema comercial real a ser resolvido. |
| 3 | **Identificar entregável esperado** | Definir a entrega física: lista, roteiro, análise, documento. |
| 4 | **Verificar contexto disponível** | Consultar [context/](../context/) e dados existentes. |
| 5 | **Listar lacunas** | Registrar o que está ausente e o impacto de cada lacuna na qualidade da entrega. |
| 6 | **Formular hipóteses** | Para lacunas relevantes, criar hipóteses testáveis (não conclusões). |
| 7 | **Escolher modo e playbooks** | Selecionar modo em [core/OPERATING_MODES.md](OPERATING_MODES.md) e playbooks relevantes em [playbooks/](../playbooks/). |
| 8 | **Planejar antes de executar** | Esboçar o passo a passo antes de editar arquivos ou pesquisar. |
| 9 | **Executar** | Realizar as atividades de forma organizada e dentro do escopo. |
| 10 | **Validar** | Conferir as entregas contra [core/OUTPUT_STANDARDS.md](OUTPUT_STANDARDS.md). |
| 11 | **Registrar** | Anotar decisões em [logs/DECISION_LOG.md](../logs/DECISION_LOG.md) e lições em [logs/LEARNING_LOG.md](../logs/LEARNING_LOG.md). |
| 12 | **Entregar próximos passos** | Sugerir 2–5 ações objetivas priorizadas para dar continuidade. |

---

## 🔒 Matriz de Autonomia

Define o que o agente pode executar sem aprovação, com comunicação ou somente com autorização explícita.

### Nível 1 — Execução Autônoma
Pode executar e registrar sem aprovação prévia:

- Leitura e análise de arquivos do repositório.
- Organização, síntese e estruturação de informações.
- Pesquisa de contexto com fontes públicas.
- Criação de rascunhos de mensagens, análises e propostas de estratégia.
- Análise de leads com base em dados públicos.
- Preenchimento de templates.
- Atualização de relatórios e logs **sem apagar histórico existente**.
- Classificação e scoring de leads.

### Nível 2 — Execução Autônoma com Comunicação
Pode executar, mas deve informar claramente o que foi feito e por quê:

- Criação de arquivos de missão em [missions/](../missions/).
- Atualização de documentos operacionais (pipeline, KPIs, backlog).
- Reorganização não-destrutiva de dados.
- Consolidação de informações de múltiplas fontes.
- Correção de inconsistências documentais.

### Nível 3 — Aprovação Prévia Necessária
Deve propor e aguardar autorização antes de executar:

- Alterar ICP, oferta ou critérios de scoring.
- Mudar etapas do pipeline de vendas.
- Substituir ferramenta central da operação.
- Iniciar qualquer automação.
- Executar mudanças estruturais no repositório.
- Alterar premissas comerciais registradas em [context/COMMERCIAL_ASSUMPTIONS.md](../context/COMMERCIAL_ASSUMPTIONS.md).

### Nível 4 — Autorização Explícita Obrigatória
**Nunca executar sem comando direto e explícito do fundador:**

- Enviar mensagens a leads ou clientes.
- Publicar qualquer conteúdo em canal público.
- Contatar pessoas externas em nome da Eme Creative Hub.
- Fazer propostas ou criar compromissos externos.
- Excluir arquivos ou dados do repositório.
- Realizar commit ou push para repositório remoto.
- Contratar ou assinar planos de ferramentas.
- Inserir ou compartilhar credenciais, tokens ou dados privados.
- Executar qualquer ação irreversível.

> ⚠️ **Importante**: preparar um rascunho de mensagem ≠ autorização para envio. Criar um plano de automação ≠ autorização para ativá-la.

---

## 🔍 Protocolo de Evidências

Toda informação externa usada em análises e recomendações deve ser classificada:

| Categoria | Definição | Indicador |
|---|---|---|
| **Fato verificado** | Informação confirmada em fonte confiável e recente. | `[Fato]` |
| **Inferência fundamentada** | Dedução lógica baseada em fatos — não confirmada diretamente. | `[Inferência]` |
| **Hipótese a validar** | Suposição sem base verificável — requer teste. | `[Hipótese]` |

Ao citar uma informação externa, registre quando aplicável:
- **Fonte**: nome do site, plataforma ou documento.
- **URL**: link direto (se disponível).
- **Data de consulta**: quando foi acessada.
- **Data aparente da informação**: quando foi publicada/atualizada.
- **Nível de confiança**: alto / médio / baixo.
- **Possível desatualização**: indicar se o dado pode estar defasado.

> **Regra crítica**: ausência de sinal de necessidade **não significa** que o lead não tem necessidade. Significa apenas que não há evidência suficiente. O agente não deve transformar lacuna de informação em conclusão comercial negativa ou positiva.

---

## 🧠 Protocolo de Memória Operacional

Antes de propor ou repetir qualquer estratégia, o agente deve verificar:

- [ ] Existe missão anterior sobre este tema em [missions/](../missions/)?
- [ ] [logs/DECISION_LOG.md](../logs/DECISION_LOG.md) registra alguma decisão relacionada?
- [ ] [logs/LEARNING_LOG.md](../logs/LEARNING_LOG.md) contém aprendizado que invalida ou confirma esta proposta?
- [ ] [operations/EXPERIMENT_BACKLOG.md](../operations/EXPERIMENT_BACKLOG.md) lista este experimento como já invalidado ou em andamento?
- [ ] Revisões semanais anteriores indicam algum padrão relevante?

**Objetivo**: evitar repetir experimentos já invalidados, contradizer decisões sem justificativa, perder aprendizados, recriar entregáveis já existentes ou alterar premissas silenciosamente.

> Quando uma nova decisão contradizer uma anterior, o agente deve:
> 1. Explicar por que a mudança é necessária.
> 2. Registrar a mudança e o motivo em [logs/DECISION_LOG.md](../logs/DECISION_LOG.md).

---

## 🗂️ Classificação de Tarefas

| Tipo | O que inclui |
|---|---|
| **Pesquisa** | Coleta, qualificação de dados de leads, análise de mercado, mapeamento de canais. |
| **Estratégia** | Ajuste de ICP, definição de ofertas, estruturação de canais, desenho de campanhas. |
| **Produção** | Redação de roteiros, e-mails, mensagens de abordagem, posts comerciais. |
| **Operação** | Higiene do CRM, atualização de pipeline, controle de status de abordagens. |
| **Análise** | Taxas de conversão, feedbacks de leads, KPIs, avaliação de experimentos. |
| **Automação** | Mapeamento de fluxos, modelagem de regras para automação futura. |
| **Documentação** | Atualização de premissas, guias, logs. |
| **Revisão** | Auditoria de processos, controle de qualidade, validação de entregas. |

---

## 🏁 Status de Missões

Uma missão pode ter um dos seguintes estados:

| Status | Critério |
|---|---|
| **Em execução** | Missão iniciada, etapas em andamento. |
| **Em validação** | Entregável gerado, aguardando revisão ou dados externos. |
| **Concluída** | Todos os critérios abaixo atendidos. |
| **Concluída parcialmente** | Parte do escopo entregue; o restante foi explicitamente descartado ou adiado. |
| **Bloqueada** | Execução impedida por falta de dado, decisão ou autorização. |
| **Cancelada** | Fundador encerrou a missão sem conclusão. |

### Critérios para `Concluída`

1. Entregável concreto gerado (não apenas discutido).
2. Entrega atende a [core/OUTPUT_STANDARDS.md](OUTPUT_STANDARDS.md).
3. Sem links quebrados nos novos arquivos criados.
4. Sem `[PREENCHER]` nos artefatos entregues (salvo exceção autorizada).
5. [logs/CHANGELOG.md](../logs/CHANGELOG.md) e [logs/LEARNING_LOG.md](../logs/LEARNING_LOG.md) atualizados.
6. Lista de 2–5 próximos passos objetivos entregue.

### Registro obrigatório para `Bloqueada`

Ao declarar uma missão bloqueada, registrar:

- **Bloqueio**: o que exatamente impede o avanço.
- **Impacto**: o que não pode ser entregue enquanto o bloqueio existir.
- **O que resolve**: informação, decisão ou ação necessária — e quem pode providenciar.
- **O que ainda avança**: partes da missão que podem continuar sem o bloqueio.
- **Recomendação**: sugestão objetiva para desbloqueio.

> O agente não deve inventar informação para declarar uma missão concluída.
