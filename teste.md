#**Comandos CMD**#
- `pwd`: pasta atual

- `ls`: lista os itens que tem na pasta

- `cd`: entrar na pasta

- `mkdir`: criar pasta

- `touch`: criar arquivo

- `rm`: apagar arquivo (exclui permanentemente)

- `rm-rf`: apagar pasta (exclui permanentemente)

- `mv`: mover arquivos
    -  `mv <nome-do-arquivo> <nome-do-arquivo-novo>: `usado para renomear arquivos
    
    
`.`: atual
`..`: anterior


----------
## **GIT**##
###**Comandos GIT**###

- `Git init`: inicializa um repositório de git

- `Git config user.name`: configura o nome da assinatura do commit

- `Git config user.email`: configura o email da assinatura do commit

- `Git config --global`

- `Git status`: mostra o status do seu repositório

- `Git add`: adiciona arquivos ao git para serem commitados

- `Git add <nome-do-arquivo>`: adiciona um arquivo específico

- `Git add .` : adiciona todos os arquivos

- `Git commit -m “mensagem do commit”`: faz um registro das alterações do código

- `Git log`: mostra os commits do repositório

    

 - List item

Git log --oneline:

- `Git diff`: mostra as alterações do último commit

- `Git diff <nome-do-arquivo>`: mostra às alterações de um arquivo

- `Git push <link-do-repositorio> master:` faz o upload para o repositório do github do link para a branch master(principal)

- `Git remote add origin <link-do-repositorio>`: adiciona um repositório (endereço remoto) ao nome origin

- `Git push origin master`: faz o upload para origin (link adicionado) para a branch master (principal) - dessa forma não há necessidade de copiar e colar o link toda hora

- `Git clone <link-do-repositorio>`: baixa uma cópia de um repositório do Github para a sua máquina

- `Git pull`: atualiza o seu repositório local caso tenha novas alterações no repositório remoto (repositório do Github)

- `Git merge --continue`: faz a “mescla” de um repositório que contém alterações diferentes das suas


###**Erros**###
- **fatal**: not a git repository (or any of the parent directories): .git : a pasta não é um repositório de git, é necessário iniciá-lo com “git init”

- **fatal: unable to auto-detect email address**: não foi detectado um email, é necessário configurá-lo com git config user.email (não se esqueça de configurar o nome também)

- **On branch master initial commit nothing to commit** : não tem arquivos a serem commitados, é necessário adicioná-los com git add.

- **fatal: your current branch ‘master’ does not have any commits yet** : não foi feito nenhum commit no seu projeto

- **fatal: no configured push destination​** : não foi indicado o local do repositório remoto, é necessário colocá-lo após o push

- **fatal: the current branch master has no upstream branch** : não foi indicado em qual branch o seu código está sendo colocado, é
necessário colocar o ‘master’ no final do push

- **fatal: protocol ‘https’ is not supported** : problema com o link do github, tente copiar e colar novamente o link

- **Error: failed to push some refs to `https://github.com/<user>/<repositorio>` hint: updates were rejected because the remote contains work that you do not have locally** : o repositório remoto contém commits/arquivos que você não tem no seu repositório local. Confira se você está dando push para o local certo e caso você tenha apagado a pasta .git, o ideal é criar um novo repositório no github, pois o conteúdo do seu repositório é diferente do repositório remoto.
