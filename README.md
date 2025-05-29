## DIO Resumos Git e Github

Repo para armazenar resumos sobre Git.[DIO](https://www.dio.me/)

## Documentação
- [Documentação Git] (google.com)

## Resumos das Aulas
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


