# Repositório de Dados Auxiliares e Snapshots (Data)

Esta pasta é reservada exclusivamente para armazenar relatórios brutos exportados, snapshots não sensíveis de análise e documentos temporários de suporte à operação comercial da **Eme Creative Hub**.

---

## 🛑 REGRA FUNDAMENTAL: CRM OFICIAL
**O HubSpot é a fonte oficial, primária e única dos dados comerciais da Eme Creative Hub.**
Esta pasta **NÃO** deve ser utilizada para criar ou manter CRMs paralelos em arquivos CSV, JSON ou planilhas locais.

---

## 🗂️ Uso Permitido para Arquivos Locais
*   **Exports Temporários de Relatórios**: Arquivos CSV exportados do HubSpot para análises estatísticas off-line.
*   **Logs de Enriquecimento de Dados**: Arquivos temporários gerados durante minerações de dados (ex: Vibe Prospecting, Apollo) antes de serem validados e cadastrados no HubSpot.
*   **Snapshots Descaracterizados**: Tabelas agregadas utilizadas em estudos de caso anonimizados e acompanhamento de experimentos.

---

## 🛡️ Regras de Segurança, Privacidade e LGPD

1.  **Proibição Absoluta de Credenciais**: Nunca armazenar senhas, tokens de API (`.env`), chaves privadas ou tokens de acesso nesta pasta.
2.  **Não Armazenar Dados Sensíveis**: Manter apenas dados corporativos públicos B2B. Nunca armazenar dados pessoais sensíveis, documentos pessoais (CPF/RG) ou informações financeiras privadas de decisores.
3.  **Proteção via `.gitignore`**: Garantir que arquivos com listas temporárias contendo e-mails ou contatos estejam incluídos no `.gitignore` para evitar exposição pública no GitHub.
4.  **Descarte de Dados**: Após a importação e validação das informações no HubSpot, os arquivos brutos temporários de extração devem ser removidos ou arquivados com segurança.
