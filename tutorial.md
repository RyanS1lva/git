GIT – VERSIONAMENTO DE ARQUIVOS
Conceitos:
*Branch → Ramificações dentro do projeto, ótimo para desenvolver diferentes funcionalidades dentro de um projeto

*Commit → Postar as alterações do código

*Merge → Junção da branch de alteração com a branch principal, o que permite diversas modificações simultaneas em um código, desde que não seja na mesma linha e sim adições ao código

*Remote → Plataforma com os repositórios

*Push → Colocar o commit no remote(GitHub), pós commit é necessário colocar no remote para não alterar somente na máquina local e sim no repositório

*Pull → Pega uma alteração do remote para a máquina local

Iniciando um versionamento:
git init → no terminal do git para iniciar o git nesta pasta
git add  > NOME ARQUIVO<  ou git add . para todos os arquivos→ deixa o arquivo no stading 
git status → mostra o status do repositório
git commit -m "primeiro commit" → executa o commit no arquivo em standing, entre aspas escreve uma mensagem sobre o commit
git branch -M "main" → altera o nome da branch, nesse caso ela se torna main
git remote add origin https://github.com/RyanS1lva/projeto-git.git → adiciona a conexão com o repositório
git push -u origin main → envia o repositório para o git 

outris comandos:
push origin main → usado depois do primeiro push, não é necessário a utilização mais do “-u”
git checkout -b "novo-botao" → cria uma nova branch, nesse caso uma chamada “novo-botao”
git checkout >NOME DA BRANCH< → para simplesmente trocar de branch
git merge >NOME DA BRANCH< → faz a junção das branch’s
git clone >LINK DO REPOSITÓRIO< → para copiar um repositório
git pull → puxa as atualizações de versão conforme o repositório para o arquivo local
clear → para limpar o terminal git
cd >NOME DO ARQUIVO< → para entrar no arquivo git
