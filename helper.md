## Inrodução ao Git via linha comando.

1. Cria um repositório

2. Adicionar um projeto do GitHub na minha máquina loca

   > git clone <endereço do repositório>

3. Adicionar no repositorio

   > git add . ou git add nomedoArquivo.extensão

4. Listar arquivos

   > git status

5. Adicionando arquivos para commit

   > git add . ou git add nomedoArquivo.extensão

6. Adicionando uma mensagem do meu commit.

   > git commit -m "minha mensagem informando o que é esse commmit"

7. Submetendo meus arquivos locais para o GitHub
   > git push

## Criando novas branches

1.  Criando uma nova branch

> git checkout -b "nomedaminhabranch"

2. Criar ou altero arquivos

> git status

3. Adicionar arquivos

> git add . ou git add "nome do arquivo.extensão"

4. Adicionar mensagem de commit

> git commit -m "informando a minha alteraçao"

5. Submeter minhas alterações para o github

> git push --set-upstream origin "nomedaminhabranch"

Visualizar qual é meu repositório local trackeado com o github.

> git remote -v

### Doc

Explicando sobre git commit semantic

> https://www.conventionalcommits.org/pt-br/v1.0.0-beta.4/
