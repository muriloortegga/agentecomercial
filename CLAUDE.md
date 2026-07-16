# CLAUDE.md — Diretrizes para Agentes de IA

Este arquivo fornece as diretrizes e regras de comportamento para você (Claude Code, Claude Cowork ou outro agente de IA) ao interagir com este repositório.

## 🧭 Princípios Operacionais da IA

1.  **Leitura do Core**: Sempre leia os arquivos da pasta [core/](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/core/) e do diretório [context/](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/context/) antes de propor alterações estratégicas ou iniciar uma nova missão.
2.  **Uso de Playbooks**: Siga rigorosamente os passo a passos descritos na pasta [playbooks/](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/playbooks/) para execução de atividades táticas (como pesquisa e abordagens).
3.  **Sistema Baseado em Missões**: Qualquer tarefa relevante deve ser executada através da criação de um arquivo em [missions/](file:///Users/muriloortega/Desktop/SITES/agentecomercial/agentecomercial/missions/) baseado no template adequado. Não trabalhe solto sem um escopo definido.
4.  **Consistência e Validação**: Ao atualizar um arquivo, garanta que os links e referências em outros documentos não sejam quebrados. Sempre valide a consistência interna da documentação.
5.  **Fatos vs. Inferências**: Em relatórios e pesquisas de leads, separe claramente o que é um **Fato** (ex: o lead postou que está contratando designers no Instagram) de uma **Inferência** (ex: o lead parece ter um gargalo na produção criativa).
6.  **Gerenciamento de Premissas**: Nunca altere premissas comerciais ou regras estratégicas silenciosamente. Se uma premissa estiver errada, a alteração deve ser proposta e registrada nos logs após validação.
7.  **Sem Código Desnecessário**: Não crie código de aplicação, banco de dados ou integrações de automação sem uma missão explícita aprovada pelo fundador. Priorize a inteligência documental.
8.  **Gestão de Dependências**: Não instale pacotes ou bibliotecas de terceiros no repositório sem a autorização expressa do usuário.

---

## 📝 Protocolo de Encerramento de Turno/Tarefa

Ao final de cada turno de trabalho ou conclusão de comando, você **deve** apresentar um resumo contendo a seguinte estrutura em sua resposta final:

1.  **Resumo do que foi realizado**: O que foi feito de forma concisa.
2.  **Arquivos criados ou alterados**: Lista com caminhos relativos ou absolutos funcionais em markdown.
3.  **Decisões tomadas**: O racional por trás de qualquer escolha importante do período.
4.  **Pendências**: O que não foi finalizado.
5.  **Próximos passos recomendados**: Próximas ações ordenadas por prioridade.
6.  **Riscos ou hipóteses**: Riscos técnicos/comerciais identificados ou novas hipóteses a serem testadas.
