# Minhas anotações de comandos Git

---

Comandos Git | Descrição dos comandos |
-------------| -------------|
`git --version`| Verifica a versão do git |
`git config --global user.name "Nome"` | Configura o nome de usuário |
`git config --global user.email "Email"` | Configura o email de usuário |
`git clone urlDoRepositório` | Clona o repositório |
`git init` | Inicializa um repositório local|
`git status` | Verifica o status do repositório |
`git add nomeDoArquivo` | Adiciona um arquivo específico |
`git add .` | Forma mais comum de adicionar vários arquivos de uma vez |
`git rm --cached nomeDoArquivo` | Remove um arquivo específico que foi adicionado |
`git rm --cached -r -f .` | Remove todos os arquivo adicionados |
`git commit -m "Sua mensagem"` | Salvar (comentar) um arquivo no repositório do git |
`git diff` | Visualizar alterações feitas no arquivo |
`git diff --staged` ou `git diff --cached` | Comparação da área staged (preparada) e modified (modificada) |
`git log` | Histórico de commits |
`git log -numeroDeCommits` | Visualizar uma quantidade exata de commits |
`git log --oneline` | Visualizar somente as mensagens dos commits |
`git log --stat` | Mostra o log de quais arquivos foram modificados |
`git commit --amend -m "Sua mensagem"` | Alterar um commit anterior |
`git commit --amend --no-edit` | Usa o último commit feito para outro arquivo adicionado (add o arquivo antes) |
`git checkout númeroHash` | Volta para uma versão exata do arquivo |
`git checkout master` | Volta para a versão mais recente do arquivo já salvo |
`git clean -f` | Remove arquivos não rastreados (*Untracked*)
`git reset --hard`| Remove qualquer arquivo, mesmo modificado |
`git update-index --skip-worktree nomeDoArquivo` | Ignora (não rastreia) o arquivo e suas demais extensões |
`git update-index --no-slip-worktree nomeDoArquivo` | Volta a rastrear o arquivo |
`git clone urlDoRepositório` | Clona um repositório específico |
`git push` | Manda arquivos e alterações do programa para o servidor remoto |
`git pull` | Traz as informações do servidor remoto para o servidor local |
