
Bootcamp Ciência de Dados com Python by Santander

# Comandos Git e GitHub

Alguns dos comandos e funcionalidades do Git usados no dia a dia. Entretanto o Git oferece muitas outras opções para gerenciar eficientemente seu código-fonte e colaborar com outros desenvolvedores.

# 📚 Documentação
 
 - [Documentação Git](https://git-scm.com/doc)
 - [Documentação GitHub](https://docs.github.com/)
 - [IA para comandos Git](https://www.gitfluence.com/)


# 💻 Resumos

### Configuração inicial e gerenciamento de mudanças

 Comandos | Descrição 
----------|---------
 git init |  Inicializa um novo repositório Git na pasta atual.
 git add .| Adiciona todas as mudanças na área de preparação (staging area).
git status| Mostra o status das mudanças no seu repositório.
git commit -m *"Nome do comentário"* | Comentar a última alteração
git log   | Exibe o histórico de commits feitos.
git restore *nomedoarquivo* | Desfaz as modificações de um arquivo para o estado do último commit.
git commit --amend -m "*Novo comentário*" | Permite corrigir o último commit.



### Conectar com Repositório Remoto

| Comandos | Descrição |
|-------|---------|
| git remote add origin URL |  Conecta o repositório local a um repositório remoto (usando SSH).
| git push -u origin main | Envia as mudanças locais para o repositório remoto na branch principal.
|git clone URL *novonomedapasta*| Mostra o status das mudanças no seu repositório.
|git clone URL --branch *nomedabranch* --single-branch| Clona um repositório remoto e uma branch específica.
|git fetch origin main | Baixa as alterações do repositório remoto sem mesclá-las.
|git merge origin main | Mescla as alterações do repositório remoto na branch local.
||

### Gerenciamento de Branches

| Comandos | Descrição |
|-------|---------|
| git checkout -b *nomedabranch* | Cria e troca para uma nova branch.
| git branch -v | Lista os últimos commits de cada branch.
|git merge *nomedabranch*| Mescla uma branch na branch atual.
|git branch -D *nomedabranch*| Deleta uma branch.
|git stash | Guarda as mudanças em um local temporário para trocar de branch.
||

### Gitignore e Histórico

| Comandos | Descrição |
|-------|---------|
| touch *exemplo-nome.md* | Cria um novo arquivo.
| echo *exemplo-nome.md* > .gitignore | Adiciona o arquivo ao .gitignore.
|echo > .gitignore| Remove o arquivo do .gitignore.
|git reflog | Exibe o histórico de comandos Git executados.
||
