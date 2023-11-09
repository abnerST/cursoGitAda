# Principais comandos:
* git init -> Inicia um repositório git
* git status -> Retorna o status da árvore nos arquivos do repositório
* git diff -> Mostra os valores alterados nos arquivos
* git diff --staged -> Mostra os valores alterados dos arquivos que já estão em staged
* git commit -m -> Cria o snapshot do repositório com os arquivos em estado de staged e coloca uma mensagem nesse commit
* git log -> Retorna o histórico dos commits executados
* git restore -> Restaura o arquivo para a versão atual, removendo as alterações antes delas estarem na área de staged
* git restore --stage -> Retorna os arquivos da área de staged para modified

# Comandos para utilização de repositórios remotos(GitHub,GitLab)
* git remote -v -> Listar as conexões remotas que você tem com outros repositórios.
* git remote add < nome> < url> -> adiciona uma nova conexão remota informando o nome a ser utilizado e a url de onde está o repositório.
* git remote rename < nome antigo> < nome novo> -> renomeia uma conexão remota
* git branch < nome da branch> -> cria uma nova branch
* git branch -D < nome da branch> -> deleta uma branch
* git branch -M < nome da branch> -> renomeia a branch atual para a definida
* git push -> Leva todas as modificações (Commitadas) para o repositório remoto.
* git pull -> Faz o download de todas as alterações feitas no repositório remoto.
