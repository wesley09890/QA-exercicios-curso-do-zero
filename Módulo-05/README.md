## 🐞 Projeto: Teste Exploratório e Regressivo + Ciclo de Vida do Bug

Projeto com foco em **teste exploratório** e **teste de regressão** em uma funcionalidade de loja/e-commerce, incluindo caderno de testes, bug reports e um relatório explicando o ciclo completo de um bug.

### Ciclo do bug
- **Aberto** → bug relatado, disponível para análise.
- **Em Correção** → bug analisado e em desenvolvimento pela equipe.
- **Em Reteste** → QA revalida a correção repetindo os passos originais.
- **Resolvido** → problema não ocorre mais; o caso de teste passa a "Passou".
- **Não é Bug** → comportamento considerado esperado após análise da equipe.
- **Won't Fix** → problema reconhecido, mas correção não priorizada no momento (com motivo documentado).

### Regressão
Após uma correção, além do reteste, é feita uma **regressão direcionada**, testando os casos com relação direta à alteração — sem necessidade de reexecutar toda a suíte, salvo quando o escopo exigir uma regressão mais ampla.

### Artefatos no projeto
- Caderno de testes
- Bug reports
- Relatório do ciclo do bug

### Aprendizado
Reforça que o trabalho do QA não termina ao reportar o bug: acompanhar seu ciclo até o reteste e garantir que a correção não impactou outras partes do sistema é parte essencial do processo de qualidade.
