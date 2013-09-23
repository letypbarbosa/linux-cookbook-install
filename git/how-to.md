Receitas básicas
===


### Para não ter que ficar redigitando a senha quando fizer push...

Crie um arquivo texto com o seguite nome:

    .netrc

Insira no arquivo

    machine github.com login seu-login-no-github password sua-senha-no-github

Obs: serve também para os repostiŕios no google code

    machine code.google.com login seu-login-no-github password sua-senha-no-github


###  Configurar atalho para "push"

    git config --global push.default matching
    git config --global push.default simple


### Deletar branch remoto via terminal

    git push origin :nome-do-branch
