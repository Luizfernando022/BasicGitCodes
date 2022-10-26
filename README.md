# BasicGitCodes

# <span style="color:rgb(10,130,60);">Comandos a serem lembrados:</span>

## cd ../ 

- sair da pasta atual

## cd ./pasta 
- Abrir pasta

## cd Pas + Tab 
- Auto completar Diretório da pasta

## ls ou dir 
- Mostrar os arquivos dentro do diretório atual

## echo "Conteúdo do arquivo" > "Nome do arquivo" 
- Criar arquivos

## cat ./Arquivo.txt 
- Ler conteúdo do arquivo selecionado.

## rm -r "Nome do Arquivo/Pasta" 
- Remover Arquivo/Pasta

## git config --global/local user.email "Email" 
- Configurar email do usuario que está utilizando o git.

## git config --global/local user.name "Nome"
- Configurar a senha do usuario que está utilizando o git.

## git status 
- Mostra os arquivos que foram modificados mas não foi colocado no "Carrinho de compras" 

## git add "Nome do Arquivo" 
- Adicionar arquivos ao "Carrinho de compras"

## git rm --cached "Nome do arquivo" 
- Irá remover o arquivo selecionado do "Carrinho de compras"

## git commit -m "Descrição do commit" 
- Irá comitar o código, fazendo com que ele passe pelo "Caixa" efetuando o pagamento do produto do carrinho.

## git commit 
- Irá abrir uma janela de edição, aonde você pode colocar um titulo no commit e uma descrição. ctrl O pra salvar e ctrl X pra sair.

## git log 
- Irá mostrar todos os commits realizados no repositório, mostrando nome e email de quem comitou, e com o id do commit.

## git log --oneline
- Irá mostrar todos os commits realizados no repositório de maneira sucinta.

## git log --graph
- Irá mostrar todos os commits realizados no repositório, bem detalhado.

## git log -n 3
- irá mostrar os ultimos 3 commits.

## git restore "Nome do Arquivo"
- Irá restaurar arquivos que foram excluídos.

## git checkout "Nome do Arquivo"
- Irá excluir as mudanças feitas, voltando ao que era antes da ultima modificação.

## git checkout "ID do Commit"
- irá fazer com que o código volte ao estado em que era no momento do commit selecionado pelo ID.

## git checkout "Nome da Branch"
- navegar entre as branchs

## git checkout -b "Nome da branch"
- irá criar uma branch com o nome selecionado, depois irá selecionar essa branch pra uso.

## git revert HEAD "ID do Commit"
- Irá reverter as mudanças feitas no commit selecionado.

## git branch
- Mostrará todas as branchs do Repositório

## git branch "Nome da branch"
- Criará uma nova branch

## git branch -D "Nome da branch"
- Irá deletar a branch selecionada 

## git merge "branch a ser emergida"
- Colocará o conteúdo da branch selecionada dentro da branch atual.



# <span style="color:rgb(10,130,60);">Padrões de nomenclatura para mensagens em commits</span>

## Chore - pequena tarefa
- git commit -m "chore : removendo arquivo.txt"

## Fix - correções
- git commit -m "fix : correção no cálculo de médias"

## Feat - inclusão de funcionalidade
- git commit - "feat : inclusão de função para calcular mediana"

## Docs - atualização de documentação<
- git commit -m " docs : atualizando o changelog.nd "
