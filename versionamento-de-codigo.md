# Versionamento de Código


## Controle de Versão

O controle de versão consiste basicamente em um sistema que permite registrar alterações feitas no desenvolvimento de um software. É a partir dele que toda a equipe envolvida no projeto têm acesso ao histórico das versões anteriores do software, podendo recuperar uma versão específica ou compreender quais mudanças foram feitas por outras pessoas.

## Git

Git é um sistema de controle de versões usado principalmente no desenvolvimento de software, inicialmente projetado e desenvolvido por Linus Torvalds para o desenvolvimento do kernel Linux.

Desde seu nascimento em 2005, Git evoluiu e amadureceu para ser fácil de usar. Ele é incrivelmente rápido, é muito eficiente com projetos grandes, e ele tem um incrível sistema de ramos (branchs) para desenvolvimento não linear.

![exemplo branch](imagens/exemplo-branch.png)


### Principais comandos

Comando                         | Descrição
--------------------------------|-------------------------------------------------------
git init                        | inicializa o git no repositório local
git add nome-do-arquivo         | adiciona um arquivo modificado ao stagging (área temporária) 
git add .                       | adiciona todos os arquivos modificados ao stagging (área temporária) 
git status                      | mostra os status dos arquivos modificados
git commit -m "mensagem"        | cria um commit
git pull                        | puxa as atualizações mais recente (remoto -> local)
git push                        | envia as atualizações mais recentes (local -> remoto)
git remote add origin caminho   | faz um link entre seu repositório local com o remoto 
git checkout -- nome-arquivo    | descarta as alterações locais do arquivo informado
git checkout -b nome-da-branch  | cria uma branch a partir da atual
git checkout nome-da-branch     | troca de branch
git merge nome-da-branch        | mescla a branch passada no parâmetro com a atual
git commit --amend              | permite editar a mensagem do último commit local pelo editor de texto do terminal (cuidado para não ficar presa no VIM!)
git remote -v                   | mostra as URLs para onde o git está apontando
git log                         | mostra o histórico de commits, com data, hora, mensagem e autora (caso fique presa nessa lista, aperte "q" para sair)
git branch                      | lista todas as branchs locais
git diff                        | mostra no terminal a diferença entre os arquivos editados localmente


## Github

GitHub é uma plataforma de hospedagem de código-fonte com controle de versão usando o Git. Ele permite que qualquer pessoa cadastrada na plataforma contribua em projetos privados e/ou de código-fonte aberto (Open Source) de qualquer lugar do mundo.