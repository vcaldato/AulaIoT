# Comandos Github

## git status - Visualiza as alterações feitas
## git add - Adicionar a Stage
## git commit -m - indica as alterações que você fez no seu projeto
## git push - Sobe o diretório para o GitHub
## git pull - atualiza o repositório local, significa dois comandos (git fetch e git merge)
## git log - Acessa o histórico da sua branch atual (main):
## git tag -a v1.0 -m "Versão 1.0" - Cria uma tag do seu projet
## Inclua um título no index.html (ou outra modificação), crie uma branch com o nome feature/inclusão-do-título:
git checkout -b feature/inclusão-do-título
## Edite index.html
git add index.html
git commit -m "Adiciona título ao index.html"
## Como acessar uma branch?
git checkout nome-da-branch
## Como trocar de branch?
git checkout nome-da-branch
## Como deletar uma branch?
Local: git branch -d nome-da-branch
Remoto: git push origin --delete nome-da-branch
## Entre na main branch e faça um merge da branch desejada para integrar ao main:
git checkout main
git merge nome-da-branch
## Para resolver o conflito do código, por que é preferível utilizar o rebase em vez do merge?
O rebase cria um histórico mais linear e limpo, enquanto o merge pode criar um histórico com mais ramificações e commits de merge.
## Como inserir apenas um commit de uma branch para a main?
git cherry-pick hash-do-commit
## Resete seu código até algum momento utilizando como parâmetro o hash do commit:
git reset --hard hash-do-commit
## Crie um arquivo tipo txt e guarde em sua stash:
echo "Conteúdo do arquivo" > arquivo.txt
git add arquivo.txt
git stash push -m "Arquivo txt em stash"
## Como fazer um Pull-Request?
No GitHub: Vá para o repositório, clique em "Pull requests", depois "New pull request" e siga as instruções.
## Como adicionar Reviewers em seu repositório:
No GitHub: Ao criar ou editar um Pull Request, você pode adicionar revisores na seção "Reviewers" no lado direito.



![]()
