## Histórico de Versão
|    Data    | Data Prevista de Revisão | Versão |          Descrição           |                   Autor                    |                Revisor                 |
| :--------: | :----------------------: | :----: | :--------------------------: | :----------------------------------------: | :------------------------------------: |
| 10/11/2024 |        10/11/2024        |  1.0   |     Criação do Documento     |  [João Victor C. Nobre](https://github.com/Gam13)   |  |

### Pré-requisitos de software

#### Windows:
- [Python](https://www.python.org/downloads/) (inclui o `pip`, o gerenciador de pacotes do Python)
- [Git](https://git-scm.com/downloads) (Necessário para a clonagem e contribuição)

#### Linux:
- Python 3 (instalável com o comando abaixo):
    ```bash
    sudo apt install python3 python3-pip
    ```

## Primeiros passos

1. **Verifique a instalação do Python**  
   No terminal (ou prompt de comando), execute:
   ```bash
   python --version
   ```
   Se a versão do Python não aparecer, siga as instruções do site oficial do [Python](https://www.python.org/downloads/) para instalar a versão mais recente.

2. **Instale o MkDocs usando pip**  
   Com o Python instalado, use o `pip` para instalar o MkDocs:
   ```bash
   pip install mkdocs
   ```

3. **Verifique a instalação do MkDocs**  
   Confirme que o MkDocs foi instalado corretamente:
   ```bash
   mkdocs --version
   ```
   Se o comando mostrar a versão do MkDocs, a instalação foi bem-sucedida.

## MkDocs instalado e agora?

Com o MkDocs instalado visite o repositório do projeto [aqui](https://github.com/Interacao-Humano-Computador/2024.2-Grupo02)

## Clonando o Projeto e Executando o Servidor Local

1. **Clone o Repositório**  
   Primeiro, abra o terminal ou prompt de comando e navegue até o diretório onde deseja clonar o projeto. Execute o comando abaixo para clonar o repositório:
   ```bash
   git clone https://github.com/Interacao-Humano-Computador/2024.2-Grupo02
   ```

2. **Acesse o Diretório do Projeto**  
   Após clonar o repositório, entre na pasta do projeto com o seguinte comando:
   ```bash
   cd 2024.2-Grupo02
   ```
    Você também pode abrir um terminal no diretório do repositório, usando IDEs ou as próprias ferramentas do sistema operacional


3. **Instale as Dependências**  
   Verifique se você tem todas as dependências necessárias do projeto. Se o MkDocs possui plugins específicos ou temas personalizados, eles devem estar listados no arquivo `requirements.txt`. Instale-os com o comando:
   ```bash
   pip install -r requirements.txt
   ```

4. **Execute o Servidor Local do MkDocs**  
   Para visualizar o projeto localmente, inicie o servidor local com o seguinte comando:
   ```bash
   mkdocs serve
   ```
   O MkDocs estará acessível em `http://127.0.0.1:8000/` no navegador. As alterações realizadas nos arquivos de documentação são atualizadas automaticamente no navegador enquanto o servidor estiver em execução.

5. **Personalize e Edite o Conteúdo**  
   Com o servidor local em execução, você pode editar os arquivos Markdown (`.md`) no diretório `docs` do projeto. Ao salvar as alterações, o servidor atualizará automaticamente a visualização no navegador.

---

Seguindo esses passos, você poderá visualizar e editar a documentação do projeto localmente. Para contribuir, você pode criar commits com suas mudanças e enviar um *pull request* para o repositório principal.

* Lembre-se as páginas criadas devem ser adicionadas em mkdocs.yml