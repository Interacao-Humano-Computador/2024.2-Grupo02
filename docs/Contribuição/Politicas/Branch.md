

# Politícas de Branch

## Histórico de Versão

|    Data    | Data Prevista de Revisão | Versão |          Descrição           |                   Autor                    |                Revisor                 |
| :--------: | :----------------------: | :----: | :--------------------------: | :----------------------------------------: | :------------------------------------: |
| 10/11/2024 |        10/11/2024        |  1.0   |     Criação do Documento     |  [João Victor C. Nobre](https://github.com/Gam13)   |                                      |

## Fluxo de Branches para Contribuição

O projeto possui três branches principais, cada uma com um papel específico:

- **`main`**: Contém a versão mais estável e revisada do projeto. Atualizações nessa branch ocorrem apenas após a aprovação de um novo ponto de controle.
- **`gh-pages`**: Utilizada para o deploy da documentação, sendo atualizada após a integração de mudanças estáveis na branch `main`.
- **`devel`**: Branch destinada à versão de desenvolvimento da documentação, onde as últimas alterações são integradas. Ela contém mudanças que podem estar incompletas ou em fase de revisão.

## Diretrizes para Contribuição

1. **Qual branch devo usar como base para minhas alterações?**
   - Inicie seu trabalho na branch `devel`, pois ela contém as alterações mais recentes e em progresso. Assim, você sempre estará trabalhando com a versão mais atualizada da documentação. Após um ponto de controle, as alterações de `devel` passam por revisão e são movidas para `main`, garantindo uma nova versão estável.

2. **Como criar uma nova branch para minhas contribuições?**
   - Siga os passos abaixo para criar uma branch local a partir da `devel`:
     ```bash
     git checkout devel
     git pull origin devel
     git checkout -b <sua-nova-branch>
     ```
Aqui está a seção reformulada com as instruções de nomenclatura para as branches:

3. **Como devo nomear minhas branches?**
   - Ao criar uma branch, é importante que seu nome seja claro e informativo. Ele deve indicar tanto o tipo de alteração quanto o conteúdo específico. Abaixo estão exemplos de sufixos para identificar o tipo de modificação:

     - **fix**: Para correções, como ajustes em erros ou bugs. Exemplo: `fix_cronograma`.
     - **new**: Para novos recursos ou documentos que estão sendo adicionados. Exemplo: `new_introducao`.
     - **upd**: Para atualizações em conteúdo já existente, sem introduzir novos recursos ou se tratar de uma correção. Exemplo: `upd_manual_uso`.

   - Lembre-se de substituir o termo entre parênteses e ajustar o nome da branch conforme o conteúdo específico que está sendo modificado.

### Resumo dos sufixos para nomes de branches:
- **fix**: Correções
- **new**: Novo conteúdo
- **upd**: Atualizações