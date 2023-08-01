# Curso de Git e GitHub

1. Instalação e configuração - GitBash, Marktext e NodeJS #NodeJS não conseguimos instalar até então.

2. Abrir uma pasta para o curso
   
   *pwd*
   
   *cd Documents/*
   
   *mkdir curso_Git*
   
   *cd curso_Git*

3. <mark>**Conceitos (possivelmente só o que é necessário para a atividade)**</mark>
   
   **What is Git Repository? And GitHub?**
   
   Git is a tool to keep track (compare and analyze as well) of different versions of work.
   
   GitHub is a plataform to host and backup your work.
   
   Areas conceituais :
   
   - Area de desenvolvimento: onde eu desenvolvo e salvo meus arquivos referentes ao projeto, ou seja, sua pasta, seu computador.
   
   - Área de staging: é o 'purgatório' onde ue jogo as coisas antes de salvar no meu repositório git.
     
     Por que a staging area é important?
     
     Porque também pode ser considerada uma etapa de classificação dos arquivos, onde eu posso correlacionar arquivos diferentes tipo file_A e file_C, na mesma mensagem.
   
   - Repositório local: o  .git, onde o git faz a gestão das versões dos teus arquivos.

4. Criando o repositório do Git
   
   *git init*
   
   *git add dictionary_Git_GitHub*
   
   *git commit -m "meaningful message"*

meaningful message: why was it changed? How this adresses the issue? Effects due to the change and Limitations of the change. 

por que o commit é tão importante?

 porque ele era salvar diferentes arquivos na linha do tempo do projeto.

# 

# GIT HUB

O GitHub NÃO é um armazenamento de dados. É um **repositório remoto**!

Recomenda-se que todo repositório Git tenha um README.txt

- detailed description of your project and tool usage

.gitignore (arquivo oculto)

Lista de arquivos que não deve ser adicionado no repositório.

- data files

- backup files

- intermediate files 

# Colab Flavia-Ricardo

1. Como fazer colaboração:
   
   - Primeiro criar uma pasta fora do seu diretório no qual está o git;
   
   - Abrir o Git Bash e dar um "cd" para esse diretório criado para o colaborador;
   
   - Realizar o comando:
     
     -     git clone <SSH>

<<<<<<< HEAD
Dicionário

- Git: Ferramenta para acompanhar diferentes versões do seu trabalho

- GITHUB: Plataforma armazenar e fazer Backup dos repositórios Git.

***O que é necessário para trabalhar em colaboração?***

1. Enviar/aceitar acesso ao repositório remoto do seu parceiro.

2. Clonar o repositório remoto dele com o comanbdo *git clone* *SSH key* (que pode ser encontrada na aba Code do projeto no GitHub)

3. Fazer as alterações necessárias nos arquivos, em seu repositório local e subir as alterar na mesma rotina anterior:
   
   *git add*
   
   *git commit*
   
   *git push*
   =======
   
   git checkout ID: cuidado! modificar o passado pode trazer riscos a sua saúde em desespero, lembre-se de criar um branch para não perder tudo que você fez! (*git switch*)
   
   > > > > > > > 
