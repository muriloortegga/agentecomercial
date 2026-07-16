# Protocolo de Execução de Missões Comercial

Este documento define o fluxo obrigatório que o Agente Comercial deve seguir desde o recebimento até o encerramento de qualquer missão neste repositório.

---

## 🔄 Fluxo de Execução em 12 Etapas

Sempre que uma nova missão for iniciada, o agente deve seguir rigorosamente estes passos:

1.  **Compreender o objetivo**: Ler a missão proposta e entender o problema comercial a ser resolvido.
2.  **Identificar o resultado esperado**: Definir claramente como será a entrega física (ex: uma lista no pipeline, um roteiro personalizado, uma análise de concorrentes).
3.  **Verificar o contexto disponível**: Consultar os arquivos de contexto ([context/](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/context/)) e dados existentes.
4.  **Listar informações ausentes**: Levantar tudo o que falta saber para executar a tarefa com perfeição.
5.  **Formular hipóteses**: Para as informações ausentes, criar hipóteses lógicas que possam ser testadas.
6.  **Escolher o modo operacional**: Selecionar um ou mais modos de atuação descritos em [core/OPERATING_MODES.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/core/OPERATING_MODES.md) adequados para a tarefa.
7.  **Selecionar playbooks**: Identificar quais manuais de [playbooks/](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/playbooks/) devem orientar o trabalho técnico.
8.  **Montar plano de execução**: Esboçar o passo a passo lógico antes de começar a editar arquivos ou realizar pesquisas.
9.  **Executar**: Realizar as atividades práticas da missão de forma organizada.
10. **Validar**: Conferir as entregas contra as regras e padrões de qualidade definidos.
11. **Registrar decisões**: Anotar no [logs/DECISION_LOG.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/logs/DECISION_LOG.md) e as lições no [logs/LEARNING_LOG.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/logs/LEARNING_LOG.md).
12. **Entregar próximos passos**: Sugerir as próximas ações prioritárias para dar continuidade aos resultados obtidos.

---

## 🗂️ Classificação de Tarefas Comerciais

Todas as subtarefas contidas em uma missão devem ser classificadas em uma das seguintes categorias:

*   **Pesquisa**: Coleta e qualificação de dados de leads, análise de mercado ou mapeamento de canais.
*   **Estratégia**: Ajuste de ICP, definição de ofertas, estruturação de canais ou desenho de campanhas.
*   **Produção**: Redação de roteiros de prospecção, e-mails comerciais ou posts focados em aquisição.
*   **Operação**: Higiene do CRM, atualização do pipeline de vendas e controle de status de abordagens.
*   **Análise**: Leitura de taxas de conversão, interpretação de feedbacks de leads e análise de KPIs.
*   **Automação**: Mapeamento de fluxos e modelagem de regras para automatização futura de tarefas.
*   **Documentação**: Atualização de premissas, alteração de guias e registro de logs.
*   **Revisão**: Auditoria de processos, controle de qualidade de dados ou validação de entregas prévias.

---

## 🏆 Critérios de Conclusão de uma Missão

Uma missão é considerada concluída (`Status: Concluída`) apenas se atender aos seguintes critérios:

1.  **Entregável Concreto**: O resultado esperado especificado no escopo da missão foi efetivamente gerado (não apenas discutido teoricamente).
2.  **Validação de Padrões**: A entrega atende a todos os requisitos de formatação e conteúdo de [core/OUTPUT_STANDARDS.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/core/OUTPUT_STANDARDS.md).
3.  **Higiene de Links**: Todos os novos links criados entre arquivos estão apontando para destinos corretos (sem links quebrados).
4.  **Ausência de Placeholders**: Não existem tags `[PREENCHER]` nos artefatos entregues (exceto se explicitamente autorizado pelo escopo da missão).
5.  **Atualização dos Logs**: O [logs/CHANGELOG.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/logs/CHANGELOG.md) e [logs/LEARNING_LOG.md](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/logs/LEARNING_LOG.md) foram atualizados com as decisões e aprendizados da missão.
6.  **Lista de Próximos Passos**: O fechamento da missão contém de 2 a 5 tarefas objetivas e priorizadas para a próxima etapa comercial.
