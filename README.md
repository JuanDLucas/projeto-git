# meu-projeto

git init 
- iniciar novo projeto com git (inicia versionamento)

git add <nome-arquivo>/. 
- add os arquivos prontos para commit (ex: add o index.html caso tenha alguma alteração para commit)

git commit -m "mensagem de commit"
- commit arquivos preparados

git log
- mostra últimos commits

git status 
- mostra estado das ramificações

git diff 
- mostra alterações na atual ramificação

git merge
-  mescla ramificação com a main/master

git branch 
- mostra as branches e a atual selecionada*

git branch -b <nome-da-branch>
- cria nova branch com o histórico da branch atual

git checkout <nome-da-branch>
- muda para essa branch

git remote add <nome(origin)> <url>
- add novo repositório remoto

git push <nome(origin)> <nome-da-branch>
- manda alterações locais para repósitorio remoto

git pull <nome(origin)> <nome-da-branch>
- atualiza nossa branch de acordo com repositório remoto

git fetch
- atualiza novo histórico local de acordo com o remoto
- sincroniza local com remoto