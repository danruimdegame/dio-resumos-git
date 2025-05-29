## DIO Resumos Git e Github

Repo para armazenar resumos sobre Git.[DIO](https://www.dio.me/)

## Documentação
- [Documentação Git] (google.com)
  
## Resumos das Aulas
git remote add origin <url> (link rep local a um rep remoto)  
git push -u origin main (push commits ao rep remoto)  
git add . (adiciona todos os arquivos à área de preparação)  
git commit -m"texto" (commita os arquivos da área de preparação)  
rm -rf (remove o .git do diretorio)  
git log (mostra os commits)   
git reflog (mostra todas as alterações além dos commits)  
  
# alterações antes de enviar ao rep remoto
git restore <nomedoarquivo> (substitui o arquivo local pelo commited)  
git commit --amend -m"texto" (altera o texto do último commit)  
git commit --ammend (abre editor de texto "I" para inserir texto "ESC : wq" para sair)  
git reset --soft(arquivos futuros tracked não commited)/--mixed(arquivos futuros untracked)/--hard(deleta os arquivos futuros)<hashdocommitdesejado> (volta a um commit)  
git reset <nomedoarquivo> (remove arquivo da area de preparação)  
git restore --staged <nomedoarquivo> (remove arquivo da area de preparação)  
  
# trabalhando com branchs
git checkout -b nomedabranch (cria uma nova branch)  
Qnd criamos uma nova branch ela aponta para o mesmo commit onde foi criada  
git checkou main (retorna para a branch main)  
git branch -v (mostra as alterações feitas em cada branch)  
git merge teste (alterações feitas na branch nova ficarao juntas com a branch main)  
git branch (mostra as branchs)  
git branch -d nomedabranch (deleta tal branch)  
  
# comandos uteis dia a dia
git fetch (baixa alterações do rep remoto sem merge com os arquivos locais)  
git clone URL --branch nomedabranch --single-b (clona o rep remoto somente(single-b) essa branch)  
git stash (arquiva modificação)
git stash list (mostra as modificacoes arquivadas)
git stash pop/apply (aplicar ou apagar a mod arqivada mais recente)
  
# no github
"." abre um vscode online  
commits podem ser feitas do github através do lápis nos arquivos .md  
  
# para atualizar o rep local com arquivos do rep remoto
git pull


