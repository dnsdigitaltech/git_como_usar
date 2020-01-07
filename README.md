# GIT COMO USAR - PASSO A PASSO

## I - INTRODUÇÃO AO CONTROLE DE VERSÃO COM GIT 

   1. ### O que é o Git-SCM

       * Sistema de Controle de Versão Distribuído
       * SCM - Source Control Management
       * Criado por Linus Torvalds (2005)
       * Auxiliar no desenvolvimento do Linux

   2. ### O que é o Git-SCM
   
       * Durante do desenvolvimento do software queremos saber:
           * O que mudou e quando?
           * Quem fez a mudança?
           * Podemos reproduzir esta mudança?
       * Identificação
       * Documentação
       * Controle
       * Auditoria
       * Artefatos:
           * Código fonte
           * Documentação do software
           * Manual do usuário

   3. ### Controle de Versão

      **O controle de versão faz o 'merge' entre as alterações.**
      
      * Ferramentas de controle de versão
         * Subversion (SVN)
         * Mercurial
         * CVS - Concurrent Versioning System
         * Bazaar
         * Git - é o mais rápido e eficiente
         
         **O Git é distribuído, ou seja,você pode fazer todo controle de versão sem está conectar com o servidor, já o SVN é necessário está conectado!**
         
   4. ### O que é GitHub
      
      * Servidor de repositório Git
      * Surgiu em 2008
      * + 10 milhões de repositórios
      * + 10 milhoes de usuários
      * **Git** e **GitHub** não é a mesma coisa:
         * O Git é um controlador de versão
         * O GitHub é um servidor de repositório Git
      * Empresas que estão no GitHub
         * Google
         * NASA
         * Twitter
         * Facebook
         * Spotify
         * Netflix
         * Linkedin
         * ...
      * Empresas que usam o Git Versionador
         * Google
         * Android
         * Microsoft
         * LibreOffice
         * Gnome
         * Eclipe
         * PostgreSQL
         * GCC
         * KDE
         * ...
   
   5. ### Servidores Git
   
      | Servidores/Suportes | Git | Mercurial | SVN |
      |---------------------|-----|-----------|-----|
      |       GitHub        |  V  |           |     |
      |       GitLab        |  V  |           |     |
      |      Bitbucket      |  V  |     V     |     |
      |     SourceForge     |  V  |     V     |  V  |
      |      Gogle Code     |  V  |     V     |  V  |
      
      **OBS: o Google Code descontinuu em 2016 e quem tinha conta lá ele pediu pra migrar para o GitHub.**
   
   6. ### Ferramentas Git
   
      * Instalar o Git:
         ```
         sudo apt-get install git
         ```
      * Escolha sua interface gráfica
         [https://git-scm.com/downloads/guis](https://git-scm.com/downloads/guis)
      * Recomendado: GitEye [https://www.collab.net/downloads/giteye](https://www.collab.net/downloads/giteye)
   
   7. ### Criar conta no GitHub
      * Crie sua conta pois é muito interessante ter uma conta pois é o seu portfólio hoje.
      * S egue o endereço para criação de conta: [https://github.com/](https://github.com/)  
      
## II - BÁSICO EM GIT

   1. ### Chave SSH e documentação GIT 
      
      **É necessário para não ficar pedingo login e senha sempre quando fizer o 'merge'. Para criar a chave basta seguir os passos abaixo clicando no link e seguir os passos:**
      [https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent](https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
   
   2. ### Ajuda
   
      * Quando precisar de ajuda
      
         ```
         git help command
         ```
      * Site oficial
         [https://git-scm.com/](https://git-scm.com/)
         
      * Documentação completa
         [https://git-scm.com/doc](https://git-scm.com/doc)
         
   3. ### Primeiros comandos GIT
   
      * Criando nosso primeiro repositório
         ```
         git init MeuRepositorio
         ```
         * Será criado o diretório **MeuRepositorio** configurado como um repositório Git
         * Todas as configurações do repositório ficam na pasta **.git**
         **OBS: você pode usar o ```git init MeuRepositorio``` para criar o repositorio com o git ou apenas o acessar o seu repositório criado e digitar ```git init``` para receber as configurações do Git.**
      * Criando um arquivo animais, abra o diretório pelo terminal ```cd MeuRepositorio``` depois crie o arquivo animais, com alguns nomes e o salve.
         ```nano animais```
      * Vamos versionar no git nosso arquivo animais com os seguintes passos:
         * ```git add animais``` Adiciona as mudanças do arquivo ao git
         * ```git commit -m 'criação do aquivo animais'``` Efetua o commit e cria o nome da alteração no git
         * Configure seu nome e email
            ```git config --global user.name "MeuUserName" git config --global user.email "meuemail@email.com"```
               Use o mesmo email e user name do seu GitHub.
      * Após configurar o user name e email efetue o commit novamente ```git commit -m 'criação do aquivo animais'``
   
         
    
