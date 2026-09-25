## 🧪 Prática: BDD/Gherkin + Execução Manual de Testes

Exercício com 4 cenários de login (válido, usuário inválido, senha inválida, campos vazios), escritos em **Gherkin** e executados manualmente em uma página de teste de login.

### O que foi praticado
- Escrita de cenários em **Gherkin** (Given/When/Then), incluindo `Scenario Outline` com `Examples` para agrupar casos de credenciais inválidas.
- Transformação de um cenário BDD em **caso de teste formal** (pré-condição, massa de dados, passos, resultado esperado x obtido).
- Comparação entre **resultado esperado e obtido**, identificando um bug: no cenário de campos vazios, o sistema exibiu "username inválido" em vez de avisar sobre campos obrigatórios.
- Registro de **bug report** estruturado (prioridade, severidade, passos, evidência).

### Aprendizado
Reforça o ciclo do QA — planejar, escrever, executar, validar e reportar — e mostra que até fluxos simples de login podem esconder falhas de mensagem/UX que só aparecem testando os *edge cases*, não só o caminho feliz.
