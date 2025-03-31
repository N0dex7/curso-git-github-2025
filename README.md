# Curso Git e GitHub 2025


Um curso para iniciantes
aprenderem a trabalhar com
versionamento de código e
repositórios remotos com GitHub.

Além disso, vamos trabalhar com
GitFlow ao final do curso e
Visual Studio Code.

ESSA É UMA VERSÃO DE ESTUDOS DO FELIPE LIMA,
CONFIRA O CONTEÚDO COMPLETO NO CANAL DO YOUTUBE DO TÉO
(https://www.youtube.com/@teomewhy)

## Fluxo de trabalho Git local

01. git checkout -b <nova-branch>
02. cria ou atualiza arquivos
03. git status
05. git add *arquivos*
06. git status
07. git commit -m "minha mensagem"
08. git checkout main
09. git merge nova_branch

## Fluxo de trabalho GitHub <> Local (projeto próprio ou da sua empresa)
01. git clone <endereco do projeto>
02. git checkout -b <nova_branch>
03. alterações de arquivos
04. git status
05. git add *arquivos*
06. git status
07. git commit -m "nova mensagem"
08. git push origin <nova_branch>
09. abrir Pull request no GitHub para main
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -D <nova_branch>

## Fluxo de trabalho GitHub <> Local (projetos open-source)
01. Fork do projeto para seu próprio github
02. git clone <endereco do projeto fork>
03. git checkout -b <nova_branch>
04. alterações de arquivos
05. git status
06. git add *arquivos*
07. git status
08. git commit -m "nova mensagem"
09. git push origin <nova_branch>
10. abrir Pull request no GitHub da branch fork para a main do projeto original
11. excluir <nova_branch> origin
12. git checkout main
13. git branch -D <nova_branch>