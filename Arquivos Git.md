Verificar conexo com a repo remoto!
Vamos começar" Novo Repo remoto, enviar os arquivos.

git config --global user.name "mesmo nome que esta na conta github"
git config --global user.email "mesmo e-mail que esta na conta github"
git remote add origin endereço da repo remoto
-
git init = criar um novo repo.
git status = verificar os status dos arquivos.
git add . = adicionar todos arquivos de uma vez no repo local.
git add nome do arquivo = adicionar um arquivo separado na repo local.
git commit nome do arquivo -m "msg" = comentar en um arquivo expecifico para enviar ao repo remoto.
git commit -a -m "msg" = comentar o envio de todos arquivos para repo remoto.
git push origin nome da branch = enviar os arquivos para repo remoto.