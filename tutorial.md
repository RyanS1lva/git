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

clear → para limpar o terminal git
