# :book: **Alguns comandos GIT para rápida consulta**

​			**_<u>Criando um repositório</u>_** :books:

- **git bash** no local em que se encontra a pasta workspace

- **ls** para listar as pastas deste local

- **cd workspace** para navegar dentro da pasta desejada

- **mkdir** (nome da nova pasta, neste caso: livro-receitas) para criar a nova pasta desejada

- **cd livro-receitas** para navegar dentro da pasta livro-receitas

- **git init** para iniciar um repositório git e versionaliza-lo

- **ls -a** flag para visualizar pastas ocultas

- **git config --global [user.email](http://user.email) "seu e-mail aqui"** para primeiro acesso

- **git config --global [user.name](http://user.name) seu name aqui** também para configurar primeiro acesso

- **git add \***

- **git commit -m "commit inicial"**

- **mv [arquivo.](http://arquivo.bd)md ./nova pasta/** move um arquivo de local

- **git status** verifica em qual estágio está seu arquivo

  

​			:construction_worker_woman:	**_<u>Trabalhando com GitHub</u>_**

- **git config --list** lista todas as configurações do meu git

- **git config --global --unset [user.email](http://user.email)**

- **git config --global --unset [user.name](http://user.name)**

- **git remote add origin** https://github.com/Kmiatelli/livro-receitas.git para copiar o repositório local para o remoto

- **git remote -v** lista os repositórios remotos cadastrados

- **git push origin master** para enviar (empurrar) o repositório local para o remoto (GitHub)



​		:red_circle:	**_<u>Resolvendo conflitos</u>_**

**Como os conflitos acontecem no GitHub e como resolve-los**

_Conflito de merge:_

Os **conflitos de merge** ocorrem quando alterações concorrentes são feitas na mesma linha de um arquivo ou quando uma pessoa edita um arquivo e outra pessoa exclui o mesmo arquivo.

- **git pull origin master** para puxar o repositório commitado de volta e corrigir o conflito 



