# Missão Prática: Ferramentas, Automação, IA e Soft Skills

## Por que fiz esse módulo

Esse módulo fecha o ciclo de fundamentos técnicos do curso QA do Zero, saindo do teste manual "na tela" e entrando em três frentes que qualquer QA júnior precisa dominar no dia a dia: **testar API**, **validar dados direto no banco** e **criar a primeira automação**. A ideia não foi só cumprir tarefa, mas simular uma rotina real de QA, documentando tudo como entrega de portfólio.

## Objetivo

Validar o comportamento de uma aplicação em três camadas diferentes, cobrindo sempre cenário de sucesso **e** cenário de erro:

- **API (Postman)** — GET de recurso existente (200), GET de recurso inexistente (404), POST de criação (201) e um login incompleto (400) numa API alternativa.
- **Banco de dados (SQL)** — consultas de seleção, filtro por país, ordenação alfabética, contagem total e agrupamento por país, usadas para checar integridade e duplicidade de dados.
- **Automação (Cypress e Maestro)** — dois testes end-to-end de login, um web e um mobile, indo do "testar manualmente" para o "testar automatizado e repetível".

## Por que isso é relevante

Testar só pela interface não garante que os dados estão corretos por trás — a API pode responder certo e o banco ainda ter uma inconsistência, por exemplo. Fazer as três frentes juntas mostra a cobertura completa do fluxo (interface → API → persistência) e é exatamente esse tipo de raciocínio que separa um QA júnior "só clicador de tela" de um QA que entende o sistema como um todo. Ter uma automação rodando, mesmo que simples, também é o primeiro passo para reduzir teste manual repetitivo e liberar tempo para teste exploratório.

## O que foi entregue

- Prints de GET 200, GET 404, POST 201 e login 400 no Postman.
- Prints das consultas SQL (SELECT, WHERE, ORDER BY, COUNT, GROUP BY) com análise do resultado.
- Teste automatizado de login no Cypress (web) e fluxo de login no Maestro (mobile), ambos passando.

## Conclusão

O módulo reforça um princípio central de QA: **não basta testar o "caminho feliz"**. Validar erros, dados persistidos e ter pelo menos uma automação funcionando são diferenciais que já aproximam a prática de uma rotina real de QA em empresa — e é isso que compõe o portfólio no GitHub.

