# Como abrir um repositório no github

## 1. Criar o diretório da aplicação no repositório do github
## 2. Criar uma pasta no seu diretório local
## 3. No terminal do VSCode aberto, digitar : 
   ### echo "# nome-diretorio" >> README.md
   ### git init
   ### git add README.md
   ### git commit -m “chore(README): first commit enviando o README.md”
   ### git branch -M main
   ### git remote add origin https://github.com/acdona/repositorio.git
   ### git push -u origin main (só a primeira vez, depois só git push)
#

## 4. Para clonar o repositório
   ### Abra o VSCode na área de trabalho
   ### Entre no terminal e digite > git clone https://github.com/acdona/teste-com-git.git
   ### Será criada uma pasta na área de trabalho, com o mesmo nome do repositário
   ### Sai do VSCode e arraste a página para a pasta do servidor
#
## Git semântico
Ao realizar commits no git (git commit -m "descricao"), devemos colocar o tipo de comit para entender melhor o que foi feito no projeto.

**✍🏻** **Refactor** - Refatoração de um código. <br>
**✍🏻 chore** - Pequenas alterações que não são novas funcionalidades. <br>
**✍🏻 docs** - Documentação de códigos, documentação técnica. <br>
**✍🏻 style** - Alteração de estilos, formatação, etc. <br>
**✍🏻 feat** - Criação de nova funcionalidade. <br>
**✍🏻 test -** Criação de testes da sua aplicação <br>
**✍🏻** **fix** - Correção de bugs e erros no código. <br>

## Exemplo de commits:
<i>git commit -m "chore(workspace): descrição da atividade ou tarefa feita"</i>

*`git commit -m "chore(checkout): inserindo ícone de pagamento"`*

*`git commit -m "feat(dashboard.profile): criação da tela de perfil"`*

*`git commit -m "feat(dashboard.login): criação da tela de login"`*

*`git commit -m "feat(API.products): desenvolvimento de API de listagem"`*

*`git commit -m "fix(dashboard.galeria): correção na classe CSS"`*
#
## Atualizando o repositório
### git add .
### git commit -m "chore(READ) Atualizando o READ.md"
### git push
#
# Comandos Git:
|comando|descrição|
| ----------- | ----------- |
|`git log`|comando para exibir todo histórico do seu repositório, trazendo informações de commits, e mudanças no projeto|
|`git status`| verifica situação que se encontra a branch, validando se há alterções, commits pendentes, etc.|
|`git add .`| Adiciona todos os arquivos e/ou pastas modificados na lista para commitar.|
|`git add <arquivo-ou-pasta>`| Adiciona arquivos/pastas específicas para realizar o commit na sequencia.|
|`git add -f <arquivo-ou-pasta>`| forçar o commit de arquivos/pastas específicas.|
|`git commit -m "descricao"`| Insere uma descrição do que está sendo comitado (alterações, criação de features, correções de bug, etc).|
|`git branch -a`| lista todas as branchs do repositorio e marca atual que estiver mexendo.|
|`git checkout nome-da-branch`| mudar de branch.|
|`git checkout -b nova-branch`|comando para criar uma nova branch|
|`git pull nome-da-branch`| puxa atualizações remota da branch escolhida|
|`git push nome-da-branch`|envias as modificações prontas já comitadas e atualizadas para a branch remota escolhida|
|`git branch -D nome-da-branch`|comando para deletar uma branch|
|`git diff`|comando para ver as ultimas alterações feitas|
|`git stash`|comando para salvar suas alterações que ainda não foram commitadas|
|`git stash pop`|comando para recuperar as alterações salvas|
