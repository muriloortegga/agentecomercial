# Repositório de Dados Estruturados (Data)

Esta pasta é reservada para armazenar e organizar arquivos de dados estruturados utilizados na operação comercial da **Eme Creative Hub**.

---

## 🗂️ Possíveis Formatos de Arquivos
Futuramente, esta pasta conterá arquivos nos seguintes formatos:
*   **CSV / JSON**: Listas consolidadas de leads, logs de importação e exports estruturados de ferramentas.
*   **Markdown**: Perfis detalhados de leads, sumários de pesquisas específicas.
*   **CRM Exports**: Relatórios brutos exportados para análise off-line.
*   **Resultados de Experimentos**: Tabelas consolidadas de testes de e-mails ou interações.

---

## 🛡️ Regras de Segurança e LGPD (Lei Geral de Proteção de Dados)

Ao lidar com dados comerciais, o Agente e o fundador devem seguir estritamente estas diretrizes:

1.  **Não Armazenar Senhas**: Nunca grave senhas, chaves privadas ou credenciais de acesso nesta pasta.
2.  **Não Armazenar Tokens de APIs**: Tokens de autenticação de ferramentas (Make, Instagram, CRM) devem ficar exclusivamente em variáveis de ambiente `.env` locais seguras.
3.  **Evitar Dados Pessoais Sensíveis**: Armazene apenas dados corporativos públicos B2B (e-mail comercial, perfil profissional, telefone corporativo). Não salve CPFs, dados de faturamento pessoal ou informações privadas dos decisores.
4.  **Uso do `.gitignore`**: Arquivos contendo dados de contato diretos que não devem ser expostos publicamente no GitHub devem ser adicionados ao arquivo `.gitignore` para evitar vazamento acidental de dados.
5.  **Respeito à LGPD**: leads têm o direito de solicitar a remoção de seus dados das listas de prospecção. Se um lead solicitar a exclusão de contatos, delete suas informações imediatamente dos arquivos locais.
6.  **Rastreabilidade de Dados**: Todo arquivo de dados salvo nesta pasta deve conter metadados indicando a **Origem dos Dados** (ex: Apify Scraper, Preenchimento Manual) e a **Data de Extração**.
