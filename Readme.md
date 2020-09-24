## COMANDOS BÁSICOS GIT ##
-> git version //Ver a versão do git

-> tree .git // Mostra a árvore de diretórios do git

-> git add // Adiciona arquivos ao git pode usar -A ou --all para inclusão de todos os arquivos

-> git status // Mostra dados do working diretory

-> git commit -m "Texto info" // Faz o commit e já insere o comentário

-> git log // Mostra detalhes dos commits (--oneline --decorate --all --graph)

-> git branch nomebranch // Cria uma ramificação do projeto
-> git branch -d nomebranch // Deleta uma ramificação do projeto

-> git merge branchname // Mescla as branch's

-> cat .git/HEAD // Mostra em qual branch está trabalhando

-> git checkout nomebranch //Alterna para a branch desejada
-> git checkout -b nomebranch //Cria e já alterna para a branch criada

-> git fetch remotename // Verifica alterações no repositório
-> git merge remotename/branchname // Mescla atualizações feitas online com seu trabalho local
-> git pull remotename branchname // Pega atualizações online e as mescla com seu trabalho local

-> git stash save "nome" //Para guardar arquivos em stash
-> git stash list //Listar os stashs guardados
-> git stash apply stash@{0} //Retornar os stashs guardados sem deletar o stash
-> git stash pop //Retornar os stashs guardados e deleta os stashs
-> git stash drop stash@{0} //Apaga os stashs guardados
-> git stash drop stash@{0} //Apaga os stashs guardados
-> git stash branch nomebranch //Criar uma nova branch com os arquivos do stashs

-> git remote add remotename https://... //Conectar ao repositório remoto
-> git remote -v // Verificar a conexão
-> git remote rm remotename // Remove o nome do remote
-> git remote rename remotename newremotename // Renomear o destino do remote

-> git push -u origin branch //Enviar para o repositório
-> git push -u origin :branch //Apagar o branch especificado do repositório
-> git pull origin branch //Puxar os dados do repositório

-> git diff ou show -- name-only //Mostrar alterações feitas nos arquivos

-> git checkout HEAD -- nomearq // Recuperar a versão anterior do arquivo dentro do branch atual (Head). Depois do commit não recupera.

-> git revert --no-edit codcommit // Reverter o commit

-> git clone urlprojeto //Clonar um projeto

-> Para contribuir em um projeto do repositório é necessario fazer um fork e depois clonar


