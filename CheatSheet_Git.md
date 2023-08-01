## CheatSheet

*git init* 

- comando para inicializar um repositório git. 
  
  PS_1: Só uma vez por projeto!!
  
  PS_2: ter certeza que estou iniciando na pasta onde vou desenvolver meu projeto.
  
  PS_3: o git não consegue "bisbilhotar" pastas acimas da sua posição hierárquica.
  
  PS_4: cuidar para não iniciar 2x o git no mesmo projeto (considerando que ele enxerga subpastas abaixo do seu nível hierárquico).

*git add <file_name.md>* 

- adiciona o arquivo no purgatório (Staging area)

*git commit -m* "meaningful message"* 

(meaningful message - por quê? como? efeitos? limitações?_)

- você se compromete com essa tualização, ou seja, você criou uma versão deste projeto no seu repositório Git (repositório local).

- Por que o commit é tão importante? 
  
  Porque ele era salvar diferentes arquivos na linha do tempo do projeto.

(meaningful message - por quê? como? efeitos? limitações?_)

- Vantagem: tem como fazer parágrafos, uma mensagem mais longa.
  
  protocolo: 
  
  i = insert
  
  esc - :wq (w salva e q sai)
  
  enter 

*git status* 

- verifica mudanças incomuns, staged e unstaged changes, modificações... tudo. 

- verifica as 3 áreas e retorna para o usuário.

*git log* 

- ver o histórico de commits da minha linha do tempo
  
  --help (ajuda)
  
  -n <n*> (escolher um número específico de commits para ver)
  
  --abbrev-commit (abrevia a ID do commit)

*git diff*

*git show* 

- os dois mostram como viajar nas linhas do tempo do Git e comparar os commits.

- --help

- +adição e - deletado <ID1> <ID2>

*git remote add* <name> <ssh>

- Cria um link da máquina local para o repositório remoto (ou seja GitHub)

*git push*

- envia tudo para o repositório remoto.

*git pull*

- Puxar informações do GitHub para o meu repositório local. 

*git revert*

- reverter o último commit que foi feito num arquivo. Se for o primeiro o arquivo será deletado.

- se não especificar, será o último commit. Pode especificar com o ID do commit.

*git reset*

- good option when you realize that the changes being made to a particular local branch should be somewhere else. You can reset and move to the desired branch without losing your file changes.

*git clone*

- melhor maneira de pegar qualquer cópia no GitHub

*git branch* <name>

- criar uma linha do tempo em paralelo, independente.

- main/master, o principal, tem um histórico. 

- o branch tem um histórico alternativo (log)

- utilidades:
  
  1. fazer testes sem alterar o que já está funcional 
  
  2. colaborar em um projeto para trabalhar em diferentes tarefas
  
  3. utilidade: procurar por soluções diferentes no mesmo problema 

*git checkout <branch_name>*

- usado para mover entre os branches

- usado para mover entre commits
