Iniciar novo packet com GIT na maquina
### git init

Definir as configurações do usuário
### git config --local user.name Marcos
### git config --local user.email mvvmvenancio@gmail.com

Baixar os arquivos do GIT
### git clone --branch <branch_name> <repository_url>
Exemplos
### git clone --branch main https://github.com/mvvmmarcos/mvvm_movie.git

Verificar a branch
### git branch

Relizar as atualizações
### git pull

Verificar os arquivos alterados
### git status

Adicionar o arquivo criado, adicionar arquivo ao índice de preparação (staging area).
O índice de preparação é uma área intermediária entre o diretório de trabalho (working directory) e o repositório Git
### git add <file>
Exemplo
### git add README.md

Adicionar todos os arquivos modificados
### git add .
