# HaleTeam1

## GitHub:

Baixe e instale o Desktop Github. Não precisa configurar nada, só ir na linha de comandos Git Shell.

Crie uma pasta em algum lugar apropriado. "mkdir <PASTA>"
Dentro da pasta, digite no Git Shell,

"git clone https://github.com/arkhenrique/haleTeam1.git"

depois entre na pasta do haleTeam1. Nela, você poderá utilizar todos os comandos do git.

# Comandos úteis:
## git status
Ele mostra o status dos arquivos que foram modificados/criados/deletados

## git add

Ele adiciona na sua máquina as modificações que vc fez nos arquivos do "git status"

Ex: mudei um arquivo chamado OLA.php
Quando vc der "git status", ele vai aparecer em vermelho "modified: OLA.php".
Vc vai dar um "git add OLA.php". Após, dê um "git status" novamente, a linha ficará verde do OLA.php.

## git commit -m "MUDEI TAL COISA"
Agora, temos que comitar todas as modificações que foram feitas (depois de dar "git add" em todos os arquivos)

Ex: já dei "git add OLA.php".
agora damos um: git commit -m "adicionei tal item no arquivo"
SIM, precisa de uma mensagem (-m)

##git push origin branch
Agora, temos que mandar pra Nuvem (site do github).
Entâo, dê um: git push origin master

##ÁRVORE DO ROLÊ
Para ver os negócios mudados e tudo mais entre no link abaixo:
https://github.com/arkhenrique/haleTeam1/network
Cada ponto, mostra um commit. e passando o mouse sobre ele, dá para ver a tal mensagem. que é importante.

# Branchs

Leia isso: https://git-scm.com/book/pt-br/v1/Ramifica%C3%A7%C3%A3o-Branching-no-Git-O-que-%C3%A9-um-Branch

## git checkout -b feature/mudando_acao1
Para criar uma branch, utilize o comando acima.

## git branch
Verifica todas as branchs que estão no seu PC. 

## git branch -D feature/mudando_acao1
Exclui uma branch, no caso "feature/mudando_acao1"


# COMANDOS MAIS IMPORTANTES

Dei o clone, peguei o repositório, dai alguém colocou algo novo. Como pegar?
## git fetch
Ele pega todos os arquivos que estão na nuvem e traz pra sua máquina SEM adicionar ao repositório

## git pull
Junta tudo o que foi feito no seu repositório

## git checkout -- OLA.php
PQP, quero voltar ao estado original de um arquivo.

