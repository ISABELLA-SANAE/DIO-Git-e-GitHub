
# DIO | Resumos Git e GitHub

Repositório para armazenar resumos sobre Git e GitHub do Curso "Versionamento de Código com Git e GitHub" da [Digital Innovation One.](https://www.dio.me/)

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/pt?hl=pt)

## ⚙️ Configuração e Inicialização do Git
|Comandos	| Para o que servem?|
|------------|-----------------|
|git config --global user.name "Seu Nome" | Define seu nome no Git.|
|git config --global user.email "exemplo@gmail.com" | Define seu e-mail no Git.|
|git config --global init.defaultBranch main|Configura a Branch padrão|
|git init	|Inicializa um novo repositório Git na pasta atual|
|git clone <URL> [--branch <branch> --single-branch]	|Clona um repositório remoto (opcionalmente apenas uma branch específica)|
|git help <comando>|Mostra ajuda sobre um comando específico|

## ⌨️ Comandos para trabalhar com Repositórios Remotos do GitHub
| Comandos | Para o que servem? |
|----------|--------------------|
|git remote add <origin> <URL>|	Adiciona um repositório remoto (ex: origin) ao projeto local|
|git rm <arquivo>|	Remove um arquivo do Git e do diretório de trabalho.|
|git remote show origin|	Mostra informações detalhadas sobre o repositório remoto|
|git push -u --set-upstream <origin> <main>|	Envia commits locais para o remoto e estabelece relação de tracking|
|git push origin <branch>|	Envia commits locais para o repositório remoto.|
|git pull origin <branch>|	Puxa alterações do repositório remoto e mescla localmente.|
|git pull|	Puxa alterações do remoto e mescla automaticamente na branch local|
|git fetch <origin> <main>|	Baixa alterações do remoto sem mesclar (permite revisão antes)|
|git remote -v|	Lista os repositórios remotos configurados.|
|git tag <versão>|	Cria uma tag (marcação) para versões (ex: v1.0.0).|

## 📦 Controle de Versão Básico
|Comandos |	Para o que servem?|
|---------|-------------------|
|git status|	Mostra o estado atual (arquivos modificados, staged, etc.)|
|git add <arquivo>|	Adiciona arquivos ao staging area (prepara para commit)|
|git add .	| Adiciona todos os arquivos modificados ao staging|
|git commit -m "mensagem"|	Cria um commit com as alterações em staging|
|git commit --amend	|Altera o último commit (mensagem ou arquivos incluídos)|
|git log|	Mostra o histórico de commits|
|git diff|	Exibe diferenças entre arquivos modificados e a última versão|

## ⏪ Desfazendo Alterações
|Comandos| Para o que servem?|
|------------|---------------|
|git reset --soft|	Remove o último commit, mas mantém alterações em staging|
|git reset --mixed (padrão)|	Remove o último commit e tira arquivos do staging|
|git reset --hard	|Apaga completamente o último commit e todas as alterações|
|git restore --staged <arquivo>	|Remove um arquivo do staging (mas mantém as alterações)|
|git restore <arquivo>|	Descarta alterações em um arquivo (antes do commit).|
|git reflog|	Mostra um log completo de TODAS as ações no repositório (útil para recuperar commits apagados)|
|git revert <commit-hash>	|Cria um novo commit desfazendo um commit anterior.|

## 📦 Stash (Alterações Temporárias)
|Comandos	|Para o que servem?|
|--------------|-----------------|
|git stash	|Guarda alterações não commitadas em uma "pilha" temporária|
|git stash pop	|Aplica as alterações stashadas mais recentes e as remove da pilha|
|git stash apply|	Aplica as alterações, mas não as remove da pilha|
|git stash list|	Mostra todas as alterações guardadas no stash|

## 🔄 Comandos de Branch (Ramificação)
| Comandos | Para o que servem? |
|----------|--------------------|
|git branch|	Lista todas as branches locais.|
|git branch <nome>|	Cria uma nova branch.|
|git checkout <branch>|	Muda para uma branch específica.|
|git checkout -b <nova-branch>|Cria e muda para uma nova branch.|
|git merge <branch>|	Mescla uma branch com a branch atual.|
|git branch -d <branch>|	Deleta uma branch local.|
|git push origin --delete <branch>|	Deleta uma branch remota.|
|git branch -v|	Lista branches locais com informações adicionais|
|git branch --list|	Lista todas as branches locais|
|git branch --delete <branch>|	Remove uma branch local|
|git push --set-upstream origin <branch>|	Define branch local para rastrear remota.|

## ☁️ Comandos de Terminal (e/ou PowerShell) 
| Comandos | Para o que servem? |
|----------|--------------------|
|cat | "concatenate", ou seja, ele irá mostrar o conteúdo de um arquivo|
|cd | "change directory", ou seja, ele irá mudar de diretório|
|pwd | "present working directory", ou seja, ele irá mostrar o caminho do diretório atual|
|mv| "move", ou seja, irá mover ou renomear um arquivo/diretório |
|dir | "directory", ou seja, lista todos os arquivos e diretorios atuais|
|mkdir | "make directory", ou seja, irá criar um diretório|
|touch | Cria um arquivo vazio ou atualiza timestamp|
|rm | "remove", ou seja, vai remover um arquivo |
|cp| "copy", ou seja, copia um arquivo ou diretório |
|echo <cria mensagem>| Criará uma mensagem|
| ls | Lista todos os arquivos e diretorios atuais|
|grep| Busca por padrões em um arquivo|
|find| Busca arquivos/diretórios |
|chmod| Altera permissões|
|chown| Muda o dono de um arquivo |
|su | Muda de usuário|
|man| Manual de Comandos|
|rmdir|"remove directory", ou seja, removerá um diretório|
|clear|Limpa a tela|

## 🔍 Referências
- [Edição de Arquivos Markdown](https://readme.so/pt)
- [Atlassian - Use bem o Git](https://www.atlassian.com/br/git)

