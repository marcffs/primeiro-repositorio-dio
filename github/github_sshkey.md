#GitHub Configurando Chave SSH
##Gerando chave SSH
_$ ssh-keygen -t ed25519 -C "your_email@example.com"_
Providenciar chave pública ao GitHub (~/.ssh/ed25519.pub)

##Adicionar chave privada ao ssh-agent
_$ eval "$(ssh-agent -s)"_
_$ ssh-add ~/.ssh/id_ed25519_

