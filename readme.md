meu primeiro commit
git init serve para inicializar um repositorio local git
git status serve para fazer uma varedura

git add read.md e um exemplo de adiona um arquivo untracked

git add -A adiciona todos os arquivos untracked 

git commit -m "Primeiro commit" exemplo faznedo um commit obs tem que ter espaço

git log para ver todas as mudanças no git

git branch mostra o branch que vc e sta

git reset --soft volta o ultimo commit antes dele ser commitado mas com com ele (exemplo git add -A) e voce pode fazer as mudanças

git reset --mixed quase a mesma coisa que o soft porem ele volta antes de ser adicionado

git reset --hard ele apaga tudo que foi feito e volta para o primeiro commit que voce fez (exemplo git reset --hard 2942f020f4563deda41e14ce4e7b7db58ce44679 ) esse codigo e o numero do commit que aparece cquando voce da um git log

git diff mostra as atualizaões feitas da ultima fez que voce fez o commit 
git dif --name-only mostra somente os arquivos que foram modificados

git remote add Algumacois serve para adiionar um repositorio remoto

git remote mostra os repositorios remotos adicionadosgit 
git remote -v server para ver mais detalhadamente as opções que tem entre fetch e push e tbm o diretorio de origin no caso o origin (fetch quando alguem faz um modificações no seu repositorio remoto e vc colocar ele no seu repositorio local e o ppush e o contrario

git reset --no-edit +Codigo do commit que vc quer que volte ( git reset serve para voltar a aquilo que foi antes do commit porem sem excluir o arquivo

git push- serve para mandar arquivos do repositorio local para o remoto (exemplo git push origin master)

git -pull serve para buscar do repositorio remoto e colocar no local (ele e o contrariodo push exemplo git pull origin master)

: serve junto com o push para delete um branch do repositorio remoto exemplo "git push origin :teste"

-D serve para deletar um branch do repositorio local exemplo "git branch -D teste"

a opção fork dentro da plataforma github serve para voce contribuir com  outros projetos 

A pasta .gitignore faz ignorar qualquer estenção ou pasta que voce não queirar no repositorio

caso a tela bug tipo por exemplo git log e tem muita informção aperta a tecla Q

