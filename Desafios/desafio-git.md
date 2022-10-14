# Desafio Git / GitHub

* Colocando em prática os conceitos aprendidos em aula.

## Seguem abaixo alguns comandos aprendidos em aula

* git init - inciar repositório
* git add - mover arquivos
* git commit - criar commits
* dir = para saber as pastas do usuario
* cd / = navegação entre pastas
* mkdir cria diretório(Pasta)
* del (nome do arquivo) = deleta arquivos e não diretórios(Pastas)
* rmdir (nome do repositório) /s /q = deleta repositório
* ls -a == Flag para exibir arquivos ocultos
* cd ..== Volta um nível de pastas
* ctrl + l == limpa tela
* cd (nomepasta)/
* git init == inicia git no diretório, criando um repositório no git.
* git add + git commit -m "informação do commit" == commit do diretório no git
* git status == mostra como esta o arquivo
* mv (nome do arquivo ou diretório) ./ (nome do diretório a ser movido) == mover
* git add (nome do arquivo) = mudando para staged
* git add * (todas as alterações) = mudando para staged
* git config --list == verifica as configurações do git
* git config --global --unset user.name == deleta nome do usuario
* git config --global --unset user.email == deleta email do usuário
* git config --global user.email == adiciona email do usuário
* git config --global user.nome == adiciona nome do usuário
* git remote add origin (link endereço no github) == adicionar servidor git ao repositorio
* git remote -v == lista de servidores remotos cadastrados
* ("Origin é apenas um apelido para que não tenha que digitar https o tempo todo")
* git push (apelido dado ao link do git) master == enviar codigo ao github
* git pull origin master == puxar conteudo do github
* git clone (link do repositorio do git) == clona repositório do git (Já traz todas as configurações do git e github)

## Seguem abaixo comandos para criação de uma chave ssh

* -- (Criar chave ssh) --
  * ssh -keygen -t ed5555 -c useruser@gmail.com

* --(ativar chave)--
  * eval $(ssh-agent -s) 
  * $ ssh-add id_ed5555