# proj_notebook-py
Introdução a linguagem de programação Python, utilizando Jupyter Notebook.

# Aulas de Programação com Python
## _Desenvolvido por Professor Gustavo_

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

# Introdução ao GIT

O GIT é uma ferramenta de desenvolvimento e é utilizada para gerenciamento de versões. Utilizada atualmente na maioria dos sistemas que estão sendo executados em nuvem sendo versionado a cada atualização de sua plataforma.
A metodologia é que em cada alteração realizada é armazenada de forma sequencial gerando ramificações. Dessa forma, o projetos poderam ser analisados e gerenciados da melhor maneira, aprovando cada uma das suas novas ramificações.
A cada deploy realizado pela equipe gera uma nova versão do projeto, podendo assim desenvolver testes sem que ocorra problemas no sistema já em uso pelo cliente/servidor.

## _Exemplo:_
V.1.1 -> V.1.2 -
| (versão ant)	|
|		------>	V.2.2 
---->V.2.1------|   (versão atual)
(versão teste)

Os tipos de Branch: Branch são como versões do sistema em camadas. Essas camadas podem ser definidas como principais(main), master, entre outras, sendo definidas em qual delas está a aplicação. Vamos conhecer algumas:

Main -> Ramificação principal, nas camadas é a mais importante pois está como padrão para a versão da aplicação em execução.
Master -> Ramificação secundaria, nas camadas é a que pode ser utilizada para desenvolvimento de novas versões.
Test ->Ramificação de teste da aplicação, nas camadas é a que pode ser alteradas e aplicadas em execução laboratórial.

Os Commit: Commits são comentarios obrigatórios que são declarados após as alterações serem adicionadas aos branch. Os desenvolvedores necessitam especificar detalhadamente a alteração realizada para que outros da equipe consigam identificar e adicionarem ao projeto. 

## Introdução ao GitHub

O GITHUB nada mais é que uma hospedagem de versionamentos dos projetos, onde na sua maioria utiliza-se aplicações publicas de diversos grupos de desenvolvimento. Dessa forma pode-se considerar que além de disponibilizar serviços e aplicações, relacionamentos entre equipes de desenvolvedores, tornando-se uma das maiores redes sociais de programadores. Os repositório disponiveis publicos, poderam ser buscados por headhunters, outros programadores, ou empresas de tecnologia, que procuram stacks ou cases relacionados a sua necessidade.

# Comandos GIT:

git config --global user.name "Gustavo Ferreira"
comando de configuração do usuario

git config --global user.email gfmb94@exemplo.com
comando de configuração do email

git status
Comando que visualiza o status da ramificação atual

git add . 
Comando que adiciona todas as novas alterações

git branch
Comando que visualiza em qual ramificação está atualmente

git -version
Comando que visualiza a versão do git

git log
Comando que lista os commits

git clone 'https://github.com/gfmb/aplication.git'
Comando para realizar clonagem do repositorio remoto para local

git push -u origin main
Comando para subir a ramificação atual para o repositorio remoto

git branch -m master main
Comando que muda a ramificação de master para main (principal)
