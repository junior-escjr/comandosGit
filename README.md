# comandosGit

### Comando para clonar uma branch
git clone -b my-branch git@github.com:user/myproject.git (código do SSH)

### Remove arquivos que foram deletados
git rm $(git ls-files --deleted)
