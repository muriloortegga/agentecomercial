# Prompt Diário de Início de Turno (Daily Start Prompt)

Este documento define a instrução padronizada que o fundador pode utilizar no início de qualquer sessão de trabalho com o Agente Comercial.

---

## 💬 Comando do Fundador

Para iniciar a rotina comercial diária, o fundador digita simplesmente:

> **"Bom dia. Tenho [X] minutos."**  
> *(onde [X] pode ser 15, 30 ou 60 minutos)*

---

## ⚙️ Algoritmo de Execução da IA

Ao receber o comando acima, o agente de IA deve executar automaticamente o seguinte fluxo de checagem e síntese, **sem aguardar novas instruções**:

1.  **Ler o Repositório**:
    *   Ler [operations/COMMAND_CENTER.md](COMMAND_CENTER.md) e [operations/CURRENT_SPRINT.md](CURRENT_SPRINT.md).
    *   Verificar pendências na missão ativa em `missions/`.
2.  **Consultar o CRM HubSpot**:
    *   Consultar tarefas vencidas ou agendadas para o dia no HubSpot.
    *   Verificar se há novas interações ou registros atualizados.
3.  **Consultar o Gmail (se aplicável)**:
    *   Verificar se há respostas de e-mails de negociações ou abordagens recentes.
4.  **Priorizar as Ações** (conforme a hierarquia do [operations/DAILY_ROUTINE.md](DAILY_ROUTINE.md)):
    *   *Respostas de leads > Negociações ativas > Follow-ups vencidos > Abordagens prontas para aprovação > Nova pesquisa*.
5.  **Apresentar o Plano Diário Adaptado ao Tempo**:
    *   Se 15 minutos: Apresentar apenas desbloqueio de respostas e follow-ups críticos.
    *   Se 30 minutos: Apresentar respostas, tarefas e aprovação de rascunhos.
    *   Se 60 minutos: Incluir pesquisa de novos leads e atualização de métricas.
6.  **Submeter Ações Externas para Aprovação**:
    *   Listar claramente os rascunhos de e-mails, Directs ou inscrições em sequências que necessitam da autorização explícita do fundador.
7.  **Atualizar o Command Center**:
    *   Ao concluir o tempo da sessão, atualizar o painel executivo em [operations/COMMAND_CENTER.md](COMMAND_CENTER.md) com os novos números do HubSpot.

---

## 📝 Exemplo de Resposta Esperada do Agente

```markdown
Bom dia, Murilo! Plano de ação montado para os seus 30 minutos de hoje:

### 📥 1. Respostas & Atendimentos Prioritários (10 min)
- [ ] Responder ao e-mail do lead [Nome da Empresa] (Proposta enviada ontem). Rascunho preparado abaixo.

### ⏱️ 2. Follow-ups Vencidos no HubSpot (10 min)
- [ ] Executar tarefa de acompanhamento no Instagram Direct para [Nome do Lead].

### ✍️ 3. Rascunhos Prontos para Sua Aprovação (10 min)
- [ ] **Direct 1** (Empresa de Engenharia em Cotia): [Texto do rascunho...]
- [ ] **Direct 2** (Consultoria B2B em SP): [Texto do rascunho...]

Deseja aprovar o envio dos Directs acima com o comando `Aprovar Directs [IDs]`?
```
