# Git Básico
## Configurando Git no Linux
_$ git_
Terminal bash sugere instalar o git
#### Definindo identidade
_$ git config --global user.name "John Doe"_
_$ git config --global user.email johndoe@example.com_
#### Nome padrão de branch (master->main)
_$ git config --global init.defaultBranch main_
#### Checando suas configurações
_$ git config --list_
_$ git config user.name_
_$ git config user.email_

### CLI Git

#### Cria novo repositório
_$ git init_
#### Adiciona arquivos untrack e/ou arquivos modified à stage
_$ git add_
#### Compromete arquivos à unmodified
_$ git commit -m "mensagem"_
-m é a flag para mensagem
#### Estado atual
_$ git status_

