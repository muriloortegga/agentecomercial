# Regras de Decisão Comercial (Decision Rules)
> **Versão**: 0.2 — Núcleo Operacional

Define os critérios objetivos de tomada de decisão para a operação comercial da **Eme Creative Hub**. Estas regras complementam os princípios constitucionais de [core/SYSTEM_PROMPT.md](SYSTEM_PROMPT.md).

---

## 🚦 Hierarquia de Priorização Geral

Ao avaliar qualquer decisão de abordagem, use esta ordem (mais importante primeiro):

1. Aderência ao ICP — ver [context/ICP_CONTEXT.md](../context/ICP_CONTEXT.md).
2. Sinal de necessidade verificável — post, site, vaga, problema observável.
3. Contexto real disponível para ancorar a conversa.
4. Potencial de relacionamento de longo prazo.
5. Probabilidade de resposta (canal ativo, tom compatível).
6. Valor potencial estimado do contrato.
7. Esforço operacional do fundador.

---

## 🔍 Regras de Pesquisa, Qualificação e Abordagem

### Desqualificar imediatamente se:
- É concorrente direto ou parceiro próximo de cliente atual.
- Não atinge aderência mínima ao ICP (porte, segmento ou decisor inadequado).
- Site abandonado ou marca inativa há mais de 6 meses sem explicação.
- Perfil do decisor tem indicação explícita de não aceitar abordagens comerciais.
- Presença de Red Flag crítico listado em [context/ICP_CONTEXT.md](../context/ICP_CONTEXT.md).

### Colocar em Nutrição (sem abordar agora) se:
- Aderência ao ICP é média, mas não há sinal de necessidade verificável no momento.
- Lead está em movimento visível (lançamento, contratações) que sugere timing ruim para abordagem.
- Já foi abordado nos últimos 60 dias sem resposta, mas sem sinal de desinteresse explícito.

### Realizar pesquisa adicional antes de abordar se:
- Lead é Tier 1 e o gancho de conversa ainda não está claro.
- O decisor tem publicações complexas que podem indicar objeções ou preferências específicas.
- Não há sinal de necessidade óbvio — pesquisar antes de concluir que não há necessidade.

> **Regra crítica**: não encontrar um sinal de necessidade **não significa** que o lead possui uma necessidade. Significa apenas que não há evidência suficiente. Lacuna de informação ≠ conclusão comercial.

### Abordar quando:
- Aderência ao ICP é alta (Tier 1) ou média com sinal de necessidade claro (Tier 2).
- Existe ao menos um elemento verificável e relevante para personalizar a mensagem.
- O decisor tem canal ativo acessível para abordagem.

### Priorizar abordagem manual e personalização profunda quando:
- Lead é Tier 1 com alto valor estimado.
- Existe dor ou sinal de necessidade específico e urgente observável.
- Lead publicou questionamento, problema ou dúvida conectável à oferta da Eme.

### Usar template como estrutura (nunca como substituto de contexto) quando:
- Tier 2 com dor e segmento padronizados e um elemento verificável disponível.
- Fluxos de follow-up depois do primeiro contato personalizado.

> **Regra**: templates estruturam mensagens, mas nunca substituem contexto real. Toda abordagem precisa conter ao menos um elemento verificável e relevante. Leads com aderência insuficiente não devem ser abordados — apenas nutridos, reavaliados ou desqualificados. **Nenhuma mensagem deve ser enviada apenas para aumentar volume**.

---

## 💬 Regras de Follow-Up

### Fazer follow-up quando:
- Lead visualizou a mensagem e não respondeu após 3 dias úteis.
- Conversa pausada sem retorno do lead após 4 dias úteis.
- Surgiu novo contexto relevante (post, lançamento, vaga) que justifica retomada.

### Interromper follow-up imediatamente quando:
- Lead sinalizou desinteresse explícito ("Não temos interesse", "Já temos fornecedor").
- Lead foi grosseiro ou demonstrou incompatibilidade cultural.

### Encerrar a cadência (break-up message) após:
- 3 tentativas de follow-up sem resposta (4 mensagens no total).

### Retomar contato (após encerramento) quando:
- Surgir sinal novo e verificável de necessidade (lançamento, nova vaga, post sobre problema relevante).
- Passou um ciclo de 60 dias e o contexto mudou — registrar como novo contato.

---

## ⚙️ Regras de Automação vs. Manual

### Manter manual obrigatoriamente:
- Redação da primeira mensagem de abordagem (outreach).
- Qualificação final e scoring de leads Tier 1.
- Qualquer negociação de proposta e fechamento de contrato.
- Envio de qualquer mensagem a leads ou clientes.

### Semiautomatizar (rascunho automático + revisão humana) quando:
- Tarefa ocorre diariamente com lógica previsível.
- O risco de erro é baixo e o tempo de revisão é menor que a execução manual.

### Automatizar quando:
- Processo foi executado manualmente com sucesso ≥ 10 vezes seguidas.
- Tempo manual supera 3 horas semanais.
- Risco de erro humano na transferência de dados é crítico.
- Automação inclui log de erros e ponto de revisão humana antes de qualquer ação externa.

---

## 📐 Princípio do Sistema Mínimo Necessário

Antes de adicionar qualquer complexidade (ferramenta, campo, etapa, automação, dashboard), o agente deve responder:

1. **Qual problema real isso resolve?**
2. **Esse problema já ocorre com frequência suficiente para justificar a solução?**
3. **Existe solução manual mais simples que funciona?**
4. **O benefício compensa o custo de manutenção e o risco?**
5. **Como saberemos se foi útil?**

Se não houver resposta clara para todas as perguntas, não adicionar complexidade.

**Evitar prematuramente**:
- CRM sofisticado antes de existir volume suficiente.
- Dashboard antes de existir dado confiável.
- Automação antes de processo manual validado.
- Muitas variações de teste antes de validar a hipótese básica.
- SEO programático antes de validar oferta e intenção de busca.
- Enriquecimento excessivo de dados que não afetam decisões.
- Novos campos, ferramentas ou etapas sem uso claro e imediato.

---

## 📈 Regras de SEO, Conteúdo e Pipeline

### Criar conteúdo de apoio (em vez de ou além do outbound) quando:
- Leads travam no diagnóstico por falta de autoridade percebida da Eme.
- A mesma objeção aparece em ≥ 3 conversas diferentes no pipeline.

### Converter dúvida recorrente em página de SEO quando:
- A mesma dúvida aparece em ≥ 3 conversas E existe intenção de busca verificável no Google.
- A página resolve a dúvida de forma completa e posiciona a Eme como referência no nicho.

### Priorizar SEO local e autoridade orgânica quando:
- Existe alta intenção de busca para os serviços da Eme no nicho-alvo.
- Leads da prospecção ativa pesquisam a marca antes de responder.

---

## 🧪 Níveis de Evidência para Experimentos

Substituem expressões vagas como "volume estatisticamente relevante". Calibrados para operação pequena.

| Nível | Definição | O que indica |
|---|---|---|
| **Sinal inicial** | Resultado promissor, mas em amostra pequena (< 10 leads). | Continuar testando, não concluir. |
| **Evidência operacional** | Padrão repetido em amostra pequena (10–20 leads). | Suficiente para continuar e refinar. |
| **Evidência forte** | Resultado consistente em diferentes ciclos ou grupos (≥ 20 leads em ≥ 2 ciclos). | Pode virar playbook. |
| **Pronto para escala** | Resultado mantém qualidade após aumento controlado de volume. | Escalar com monitoramento. |

### Critérios para escalar um experimento (todos necessários):

- [ ] Taxa de resposta acima do threshold definido.
- [ ] Qualidade das respostas — conversas reais, não educadas.
- [ ] Avanço no pipeline — leads chegam a reunião ou proposta.
- [ ] Aderência das oportunidades — fits reais, não qualificados a força.
- [ ] Esforço manual dentro do limite do fundador.
- [ ] Sem impacto negativo observável na reputação.
- [ ] Capacidade operacional disponível para absorver o volume.

### Abandonar um experimento quando:
- Volume mínimo atingido e a métrica de sucesso ficou abaixo do threshold definido no [templates/EXPERIMENT_TEMPLATE.md](../templates/EXPERIMENT_TEMPLATE.md).
- Atrito operacional severo (> 2h diárias do fundador).
- Impacto negativo observável na reputação ou nas relações.

---

## 🧩 Regras de Evolução Estratégica

### Propor mudança de oferta quando:
- ≥ 5 leads qualificados recusaram a proposta com a mesma objeção de escopo, prazo ou formato.
- Taxa de conversão Diagnóstico → Proposta abaixo de 10% por 30 dias consecutivos.

### Propor mudança de ICP quando:
- ≥ 30 leads de um nicho abordados com 0% de respostas positivas ou reuniões.
- Clientes do segmento atual apresentam margem baixa ou alto atrito de entrega.

> Mudanças de ICP ou oferta requerem aprovação prévia do fundador (Nível 3 de autonomia). Ver [core/EXECUTION_PROTOCOL.md § Matriz de Autonomia](EXECUTION_PROTOCOL.md).
