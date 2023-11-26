Para visualizar as branchs do projeto
git branch

Para criar uma brancha
git branch nome_da_branch
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
dentro da minha branch eu dou um merge na main, para acessar as novas informações
e dps committo a minha branch para a main
git merge main
git add .
git commit -m "novas informações
acesso a main e dou push
