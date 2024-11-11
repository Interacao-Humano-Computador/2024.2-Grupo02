## Histórico de Versão

|    Data    | Data Prevista de Revisão | Versão |          Descrição           |                   Autor                    |                Revisor                 |
| :--------: | :----------------------: | :----: | :--------------------------: | :----------------------------------------: | :------------------------------------: |
| 10/11/2024 |        10/11/2024        |  1.0   |     Criação do Documento     |  [João Victor C. Nobre](https://github.com/Gam13)   |          [Lucas Sales](https://github.com/Lux-Sales)                            |

---

## Diretrizes para Pull Requests

Os Pull Requests (PRs) são uma parte fundamental do fluxo de trabalho no Git, permitindo a revisão e a integração das alterações de uma branch para outra. Aqui estão as práticas a seguir ao criar e gerenciar Pull Requests:

### Quando criar um Pull Request?
- **Após a conclusão de uma tarefa ou funcionalidade**: Sempre crie um PR quando terminar uma alteração significativa, como uma correção de bug, a adição de uma nova funcionalidade ou a atualização de um recurso.
- **Após revisar as mudanças**: Antes de submeter um PR, revise suas alterações localmente para garantir que tudo esteja funcionando corretamente e que o código esteja limpo e bem documentado.

### Como criar um Pull Request?
1. **Escolha a branch correta**: O PR deve ser feito da sua branch de trabalho para a branch `devel`.
2. **Descreva claramente o que foi feito**: O título e a descrição do PR devem ser claros e objetivos. Indique o que foi alterado, adicionado ou corrigido e, se necessário, explique o contexto das mudanças.
   
   **Exemplo de título de PR**:
   
   - **[fix]** Corrigir caminho da logo

   - **[new]** Ata da reunião do dia 09/11/2024

**Verifique a compatibilidade do código**: Certifique-se de que suas alterações estão compatíveis com o restante do código do projeto, sem causar conflitos.

**Solicite uma revisão**: Escolha revisores adequados para avaliar seu PR e fornecer feedback construtivo.

### Como fazer a revisão de um Pull Request?
- **Evite aceitar seu próprio PR**: Não é recomendável revisar e aprovar suas próprias mudanças. Muitas vezes, tendemos a acreditar que nosso trabalho está correto, o que pode nos impedir de identificar problemas ou melhorias. Por isso, é fundamental que outro membro da equipe avalie e revise suas alterações para garantir uma visão imparcial e um código de melhor qualidade.
- **Leia o código cuidadosamente**: Ao revisar um PR, avalie a qualidade do código, a clareza das mudanças e a aderência aos padrões de desenvolvimento do projeto.
- **Teste as alterações**: Sempre que possível, teste as alterações para garantir que o código funciona conforme esperado e não introduza novos problemas.
- **Forneça feedback claro e construtivo**: Comente diretamente nas linhas de código relevantes ou na descrição do PR, detalhando quaisquer melhorias, correções ou sugestões.

### Benefícios de Pull Requests bem feitos:
- **Colaboração eficiente**: PRs permitem que múltiplos desenvolvedores revisem e contribuam para as mudanças, garantindo que o código seja de alta qualidade.
- **Histórico bem documentado**: Cada PR serve como uma documentação das alterações feitas, facilitando o entendimento do que foi modificado no projeto e por quê.
- **Menos conflitos**: Ao revisar e integrar mudanças com frequência, você evita grandes conflitos de código e facilita a manutenção do projeto.

### Resumo:
- **Criação do PR**: Após concluir suas alterações, crie um Pull Request para integrar sua branch à branch principal de desenvolvimento (`devel`).
- **Revisão do PR**: Peça para outros desenvolvedores revisarem suas alterações e forneçam feedback.
