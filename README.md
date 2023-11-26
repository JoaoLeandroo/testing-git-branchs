Para visualizar as branchs do projeto

        git branch


Para criar uma branch, usar o comando: git branch nome_da_branch

        ex: git branch page_home


Para trocar de branch

        git checkout page_home


Para criar uma nova brach e trocar imediatamente pra ela
git checkout -b "nome_da_branch"

        ex: git checkout -b "page_contato"


Para deletar uma brach(não é muito comum de se fazer)
git branch -d nome_da_branch

        ex: git branch -D page_contato


Como unir Branchs, acesse a branch main, ou a desejada
git merge nome_branch

        ex: git merde page_home


Caso a minha branch esteja atrasada em relação as demais e a main ja tenha novas informações
dentro da minha branch atual eu dou um merge na main, para acessar as novas informações e depois
faço um committ da minha branch atual para a main

        git merge main
        git add .
        git commit -m "novas informações


para voltar ao estado inicial de uma branch(ultimo commit)

        git stash 

o comando git stash limpa todas as alterações feitas naquela branch, e retorna ao estado inicial(ultimo commit)


Para reverter uma stash, em caso de arrependimento

        git stash list

passar o id da stash no apply no exemplo estou passando a stash no id 0

        git stash apply 0



Para verificar o que tem nas stash list
o numero representa o id da stash

        git stash show -p 2