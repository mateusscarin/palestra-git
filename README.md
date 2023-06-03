# Palestra Git
Repositório com intuito de documentar o conteúdo abordado na palestra lecionada ao pessoal da turma do 3º Semestre de Sistemas para Internet 
## Sistema de controle de versão 
- Software versioning
- Gerenciamento de mudanças

## Porque utilizar?
- Segurança
- Colaboração
- Organização
- Controle das versões
- Rastreio de modificações

## Conventional commits
- Commits semânticos
- Convenção do Angular
- Padronização de commits
- Auxílio para automatizações

## Convetional commits
- build: mudanças envolvendo configurações e dependências
- ci: integração contínua
- docs: alterações em documentação
- feat: uma nova funcionalidade
- fix: uma correção de um bug
- perf: alteração que visa melhora no desempenho
- refac: alteração que não é nem bug nem novo recurso
- style: mudanças que não afetam o significado do código
- test: adição de testes

## Exemplos de SCV
- Git
- Mercurial
- TFS

## Commit atômico
- Boa prática
- Facilita mensagem do commit
- Melhor descrição

## Conflito no git
- Mesclagem de alterações
- Ex: pull, merge, rebase, push...
- Commits em arquivos iguais

## Git x GitHub 
![git_vs_github](https://github.com/mateusscarin/palestra-git/assets/79494982/ead0c173-129d-4302-aef8-2b62eeedd44f)

### HISTORICO
- `git log`
- `git log --graph`
- `git log --oneline`
- `git diff <hashcommit> <hashcommit>`

### BRANCHES
- `git checkout <branch>`
- `git checkout -b <new-branch>`
- `git branch -d <branch>`
- `git stash`
- `git tag <tag-name>`

### ATUALIZAR E PUBLICAR
- `git remote add <shortname> <url>`
- `git fetch <remote>`
- `git pull <remote> <branch>`
- `git push <remote> <branch>`
- `git push --tags`

### FUNDIR E REBASE
- `git merge <branch>`
- `git rebase <branch>`
- `git rebase --abort`
- `git rebase --continue`

### DESFAZER
- `git reset HEAD~<quant-commit(s)>`
- `git revert <hash-commit>`
- `git reset <hash-commit>`

### OUTROS COMANDOS
- `git init`
- `git clone <link-rep-remoto>`
- `git help`

## Bibliografia
- https://git-scm.com/docs 
- https://blog.betrybe.com/desenvolvimento-web/versionamento-software-codigo/ 
- https://aws.amazon.com/pt/devops/continuous-integration/ 
- https://github.com/angular/angular/ 
