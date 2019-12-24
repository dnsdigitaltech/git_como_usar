# git_como_usar
Git como usar passo a passo

<h1>INTRODUÇÃO AO CONTROLE DE VERSÃO COM GIT</h1>
    <ol type>
        <li>
            <p>
                <h5><b>O que é o Git-SCM</b></h5>
            </p>
            <ul type="disc">
                <li>Sistema de Controle de Versão Distribuído</li>
                <li>SCM - Source Control Management</li>
                <li>Criado por Linus Torvalds (2005)</li>
                <li>Auxiliar no desenvolvimento do Linux</li>
            </ul>
        </li>
        <li>
            <p>
                <h5><b>O que é o Git-SCM</b></h5>
            </p>
            <ul type="disc">
                <li>
                    Durante do desenvolvimento do software queremos saber:
                    <ul type="circle">
                        <li>
                            O que mudou e quando?
                        </li>
                        <li>
                            O que mudou e quando?
                        </li>
                        <li>
                            Quem fez a mudança?
                        </li>
                        <li>
                            Podemos reproduzir esta mudança?
                        </li>
                    </ul>
                </li>
                <li>Identificação</li>
                <li>Documentação</li>
                <li>Controle</li>
                <li>Auditoria</li>
                <li>
                    Artefatos:
                    <ul type="circle">
                        <li>
                            Código fonte
                        </li>
                        <li>
                            Documentação do software
                        </li>
                        <li>
                            Manual do usuário
                        </li>
                    </ul>
                </li>
            </ul>
        </li>
        <li>
            <p>
                <h5><b>Controle de Versão</b></h5>
            </p>
            <p>O controle de versão faz o 'merge' entre as alterações.</p>
            <ul type="disc">
                <li>
                    Ferramentas de controle de versão
                    <ul type="circle">
                        <li>
                            Subversion (SVN)
                        </li>
                        <li>
                            Mercurial
                        </li>
                        <li>
                            CVS - Concurrent Versioning System
                        </li>
                        <li>
                            Bazaar
                        </li>
                        <li>
                            Git - é o mais rápido e eficiente
                        </li>
                    </ul>
                    <p>O Git é distribuído, ou seja,você pode fazer todo controle de versão sem está conectar com o servidor, já o SVN é necessário está conectado!</p>
                </li>
            </ul>
        </li>
        <li>
            <p>
                <h5><b>O que é GitHub</b></h5>
            </p>
            <ul type="disc">
                <li>Servidor de repositório Git</li>
                <li>Surgiu em 2008</li>
                <li>+ 10 milhões de repositórios</li>
                <li>+ 10 milhoes de usuários</li>
                <li>
                    <b>Git</b> e <b>GitHub</b> não é a mesma coisa:
                    <ul type="circle">
                        <li>
                            O Git é um controlador de versão
                        </li>
                        <li>
                            O GitHub é um servidor de repositório Git
                        </li>
                    </ul>
                </li>
                <li>
                    Empresas que estão no GitHub
                    <ul type="circle">
                        <li>Google</li>
                        <li>NASA</li>
                        <li>Twitter</li>
                        <li>Facebook</li>
                        <li>Spotify</li>
                        <li>Netflix</li>
                        <li>Linkedin</li>
                        <li>...</li>
                    </ul>
                </li>
                <li>
                    Empresas que usam o Git Versionador
                    <ul type="circle">
                        <li>Google</li>
                        <li>Android</li>
                        <li>Microsoft</li>
                        <li>LibreOffice</li>
                        <li>Gnome</li>
                        <li>Eclipe</li>
                        <li>PostgreSQL</li>
                        <li>GCC</li>
                        <li>KDE</li>
                        <li>...</li>
                    </ul>
                </li>
            </ul>
        </li>
        <li>
            <p>
                <h5><b>Servidores Git</b></h5>
            </p>
            <table border="1" class="table">
                <tr>
                    <th>Servidores/Suportes</th>
                    <th>Git</th>
                    <th>Mercurial</th>
                    <th>SVN</th>
                </tr>
                <tr>
                    <td>GitHub</td>
                    <td>V</td>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <td>GitLab</td>
                    <td>V</td>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <td>Bitbucket</td>
                    <td>V</td>
                    <td>V</td>
                    <td></td>
                </tr>
                <tr>
                    <td>SourceForge</td>
                    <td>V</td>
                    <td>V</td>
                    <td>V</td>
                </tr>
                <tr>
                    <td><del>Gogle Code</del></td>
                    <td><del>V</del></td>
                    <td><del>V</del></td>
                    <td><del>V</del></td>
                </tr>
            </table>
            <p>
                OBS: o Google Code descontinuu em 2016 e quem tinha conta lá ele pediu pra migrar para o GitHub.
            </p>
        </li>
        <li>
            <p>
                <h5><b>Ferramentas Git</b></h5>
            </p>
            <ul type="disc">
                <li>
                    Instalar o Git:
                    <p>sudo apt-get install git</p>
                </li>
                <li>
                    Escolha sua interface gráfica
                    <p><a href="https://git-scm.com/downloads/guis" target="_blank">https://git-scm.com/downloads/guis</a></p>
                </li>
                <li>
                    Recomendado: GitEye
                    <p><a href="https://www.collab.net/downloads/giteye" target="_blank">https://www.collab.net/downloads/giteye</a></p>
                </li>
            </ul>
        </li>
        <li>
            <p>
                <h5><b>Criar conta no GitHub</b></h5>
            </p>
            <p>
                Crie sua conta pois é muito interessante ter uma conta pois é o seu portfólio hoje.
                <br/> segue o endereço para criação de conta:<br/>
                <a href="https://github.com/" target="_blank">https://github.com/</a>
            </p>
        </li>
    </ol>
    <h1>II - BÁSICO EM GIT</h1>
    <ol type>
        <li>
            <p>
                <h5><b>Chave SSH e documentação GIT</b></h5>
            </p>
            <p>É necessário para não ficar pedingo login e senha sempre quando fizer o 'merge'. Para criar a chave basta seguir os passos abaixo clicando no link e seguir os passos:</p>
            <a href="https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent" target="_blank">https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent</a>
        </li>
        <li>
            <p>
                <h5><b>Ajuda</b></h5>
            </p>
            <ul type="disc">
                <li>
                    Quando precisar de ajuda
                    <p><code>git help command</code></p>
                </li>
                <li>
                    Site oficial
                    <p><a href="https://git-scm.com/" target="_blank">https://git-scm.com/</a></p>
                </li>
                <li>
                    Documentação completa
                    <p><a href="https://git-scm.com/doc" target="_blank">https://git-scm.com/doc/</a></p>
                </li>
            </ul>
        </li>
        <li>
            <p>
                <h5><b>Primeiros comandos GIT</b></h5>
            </p>
            <ul type="disc">
                <li>
                    Criando nosso primeiro repositório
                    <p><code>git init MeuRepositorio</code></p>
                    <ul type="circle">
                        <li>Será criado o diretório <b>MeuRepositorio</b> configurado como um repositório Git</li>
                        <li>Todas as configurações do repositório ficam na pasta <b>.git</b></li>
                        <p>OBS: você pode usar o <code>git init MeuRepositorio</code> para criar o repositorio com o git ou apenas o acessar o seu repositório criado e digitar <code> git init</code> para receber as configurações do Git.</p>
                    </ul>
                </li>
                <li>
                    criando um arquivo animais, abra o diretório pelo terminal <code>cd MeuRepositorio</code> depois crie o arquivo animais, com alguns nomes e o salve.
                    <p><code>nano animais</code></p>
                    Vamo versionar no git nosso arquivo animais. com os seguintes passos:
                    <ul type="circle">
                        <li><code>git add animais</code> Adiciona as mudanças do arquivo ao git </li>
                        <li><code>git commit -m 'criação do aquivo animais'</code> Efetua o commit e cria o nome da alteração no git</li>
                        <li>
                        Configure seu nome e email <p> <code>git config --global user.name "MeuUserName"</code></p><p><code>git config --global user.email "meuemail@email.com"</code></p> Use o mesmo email e user name do seu GitHub.
                        </li>
                        <li>
                        Após congigurar o euser name e email efetue eo commit novamente <code>git commit -m 'criação do aquivo animais'</code>
                        <p>Se tudo der certo mostra o seguinte comnado de retorno</p>
                        <p><code>[master (root-commit) 4143d19] criação do aquivo animais
                                    file changed, 0 insertions(+), 0 deletions(-)
                                    create mode 100644 animais</code></p>
                        </li>
                    </ul>
                </li>
                <li>
                    Git Status e Log
                    <ul type="circle">
                        <li>
                            <code>git status</code> - Ver o status so repositório com o seguinte retorno
                            <p>
                            <code>
                                On branch master
                                nothing to commit, working tree clean
                            </code>
                            </p>
                        </li>
                        <li>
                        <code>git log</code> - ver últmos comits do repositório com o seguinte retorno
                        <p>
                        <code>
                            commit 4143d196927be74bb07d9146a70fc066931ddfe0 (HEAD -> master)
                            Author: Davi Bernardo <dnssites@gmail.com>
                            Date:   Tue Dec 24 10:40:57 2019 -0300
                                criação do aquivo animais
                        </code>
                        </p>
                        </li>
                    </ul>
                </li>
            </ul>
        </li>
        <li>
            <p>
                <h5><b>Criando repositório no GitHub</b></h5>
            </p>
            <ul type="disc">
                <li>
                    Criar um repositório remoto
                    <ul type="circle">
                        <li>
                            Crie um repositório no GitHub
                            <p>Acesse seu GitHub e clique em criar novo repositório</p>
                            <p>Configure se ele será <b>Public</b> ou <b>Private</p>
                            <p>Ao criar vai aparece uma tela com os comando de configurações deste diretório, vamos pegar todo endereço do git remote do nosso diretório.</p>
                        </li>
                        <li>
                            Configure o repositório remoto
                            <p><code>git remote add {remote} {url}</code></p>
                            <p><code>git remote add origin https://github.com/dnsdigitaltech/meurepositorio.git</code>, <br>basta copiar e colar este comendo no terminal do seu diretório</p>
                            <p><code>git remote -v</code> comando que verifica o origin remote, aparece o seguinte retorno:</p>
                            <p><code>origin  https://github.com/dnsdigitaltech/meurepositorio.git (fetch)</code></p>
                            <p><code>origin  https://github.com/dnsdigitaltech/meurepositorio.git (push)</code></p>
                            <p>Aparece duas vezes: <code>fetch</code> - baixa os arquivos e <code>push</code> envia para o GitHub os arquivos</p>
                            <p>Origin e ó ramo (branch) padrão (principal) do git</p> 
                            <p><code>git push</code> - comando que envia os dados para o servidor remote GitHub</p>
                            <p>
                            <code>
                                fatal: The current branch master has no upstream branch.
                                To push the current branch and set the remote as upstream, use
                                git push --set-upstream origin master
                            </code>
                            </p>
                            <p>OBS: primira vez que você faz z configuração do servidor remote dará este erro <code>git push --set-upstream origin master</code>, pois é necessário setar o branch (ramo) neste caso o <code>origin master</code></p>
                            <p><code>git push --set-upstream origin master</code> - comando para configurar o branch master no repositório de origem.</p>
                            <p><code>git push -u origin master</code> comando mais simples para configurar o master</p>
                            <p>OBS: se caso você não configurou o SSH vai pedir username e senha.</p>
                            <p>
                            Após esta tudo ok aparecerá o seguinte comando:
                            </p>
                            <p>
                            <code>
                            Counting objects: 100% (6/6), done.
                            Delta compression using up to 4 threads
                            Compressing objects: 100% (2/2), done.
                            Writing objects: 100% (6/6), 471 bytes | 471.00 KiB/s, done.
                            Total 6 (delta 0), reused 0 (delta 0)
                            To https://github.com/dnsdigitaltech/meurepositorio.git
                            * [new branch]      master -> master
                            Branch 'master' set up to track remote branch 'master' from 'origin'.
                            </code>
                            </p>
                            <p>
                            OBS: após configurar a primeira vez o <code>git push --set-upstream origin master</code> as demais vezes poderá usar o <code>git push</code>
                            </p>
                        </li>
                        <li>
                            Crie um arquivo README.md   
                            <p>Use o o nano, vi, GEDIT ou outro editor texto para criar o README.md  <code>nano README.md</code>, o GitHub usa para mostrar o conteúdo do documento na página inicial estilo o HTML</p>
                            <p># - usado para colocar titulo</p>
                            <p>![./animais.jpg](Animais) - usado para colocar imagem e () pode colocar o descrição da imagem</p>
                            <p>OBS: Sempre quando fizer um alteração é necessário das os seguintes comandos: <code>git add .</code> - adicionar todos os arquivos ao git, <code>git status</code> - verificar se foram add, <code>git commit -m "texto do commmit"</code> - efetuar o commit das alterações, <code>git log</code> verifica todos os commits, <code>git push</code> - enviar as altereções sincronizando-as o servidor</p>
                        </li>
                        <li>
                            Faça upload das alterações com o seguinte comando    
                            <p><code>git push</code>
                            <ul type="square">
                                <li>   
                                Enviar alterações (commits) de uma branch para o repositório remoto 
                                </li>
                                <li>
                                A primeira vez <code>git push -u origin master</code>
                                </li>
                                <li>
                                O envio é rejeitado se o repositório local não estiver sincronizado
                                <code> git push {remote} {branch}<code> <code> git push</code>
                                </li>
                            </ul>               
                        </li>
                    </ul>
                </li>
            <ul>
        </li>
        <li>
            <p>
                <h5><b>Revisão dos comandos></b></h5>
            </p>
            <ul type="disc">
                <li>
                    Git Add
                    <ul type="circle">
                        <li><code>git add {lista de arquivos} </code> - Adiciona arquivos específicos novos e modificados para o próximo commit </li>
                        <li><code>git add . </code> - Adiciona todos os arquivos novos e modificados para o próximo commit </li>
                    </ul>
                    Git Commit
                    <ul type="circle">
                        <li><code>git commit [-m "mensagem"] </code> - Registra o commit com todos os arquivos que usou o <code> git add .</code> </li>
                        <li>Se o parâmetro de mensagem não for passado abrirá um editor de texto para  excrever a mensagem</li>
                        <li><code>git config --global core.editor gedit</code></li>
                    </ul>
                    Git Workflow
                    <ul type="circle">
                        <li>Basicamente a maior parte do trabalho com o git consiste neste tarefas: - Editar, - Commitar, - Sincronizar com o repositório remoto</li>
                        <li>Exercite esses comandos!</li>
                    </ul>
                    Status dos arquivos
                    <ul type="circle">
                        <li>Edite o arquivo criado posteriormente </li>
                        <li>Crie um novo arquivo e veja o seu status no repositório </li>
                        <li><code>git status </code> - resultado: 
                            <p>
                                <code>
                                    On branch master
                                    Your branch is up to date with 'origin/master'.
                                    Changes not staged for commit:
                                    (use "git add <file>..." to update what will be committed)
                                    (use "git checkout -- <file>..." to discard changes in working directory)
                                            modified:   animais
                                    Untracked files:
                                    (use "git add <file>..." to include in what will be committed)
                                            planetas
                                    no changes added to commit (use "git add" and/or "git commit -a")
                                </code>
                            </p>
                            <p>OBS: que mostra o arquivo aminimais que foi modificado e o novo arquivo planeta, você pode usar <code> git add . </code> para add ao commit ou <code> git checkout -- </code> para descartar as atualizações e o qeuivo voltara ao que era antes desde seu último commit.</p>
                            <p>
                            Vamos dar um <code> git add . </code> veja o resutado abaixo do <code> git status</code>
                            </p>
                            <p>
                                <code>
                                On branch master
                                Your branch is up to date with 'origin/master'.
                                Changes to be committed:
                                (use "git reset HEAD <file>..." to unstage)
                                        modified:   animais
                                        new file:   planetas
                                </code>
                            </p>
                            <p>
                            Vamos dar um <code>git commit -m "Editado o aquivo animais e criado o arquivo planetas"</code>
                            </p>
                            <p>
                                <code>
                                [master cb06b2d] Editado o aquivo animais e criado o arquivo planetas
                                2 files changed, 6 insertions(+), 1 deletion(-)
                                create mode 100644 planetas
                                </code>
                            </p>
                            <p>
                            Vamos dar um <code>git push</code>
                            </p>
                            <p>
                                <code>
                                Counting objects: 100% (6/6), done.
                                Delta compression using up to 4 threads
                                Compressing objects: 100% (2/2), done.
                                Writing objects: 100% (4/4), 429 bytes | 429.00 KiB/s, done.
                                Total 4 (delta 0), reused 0 (delta 0)
                                To https://github.com/dnsdigitaltech/meurepositorio.git
                                3c5f2c5..cb06b2d  master -> master
                                </code>
                            </p>
                            <p>
                            OBS: Você pode ir no seu repositário do GitHub e veja que já foi adiocnado o arquivo planeta e atualizado o arquivo animais
                            </p>
                        </li>
                    </ul>
                </li>
            </ul>
        </li>
        <li>
            <p>
                <h5><b>Estado dos Arquivos no Git</b></h5>
            </p>
            <ul type="disc">
                <p>Os arquivos passaram por 4 estados</p>
                <li>
                Não monitorado (untracked) - quando o arquivo foi criado
                </li>
                <li>
                Monitorado (modified) - quando edita o arquivo
                </li>
                <li>
                Preparado (staged) - quando dar o git add, prepara o arquivo
                </li>
                <li>
                Consolidade (commited) - o arquivo depois de commitar ele estará registrado no repositório
                </li>
            </ul>
        </li>
        <li>
            <p>
                <h5><b>Diff</b></h5>
            </p>
            <ul type="disc">
                <li>
                <code>git diff</code> - Exibir direfenças entre commits e branchs
                </li>
                <li>
                <code>git diff [path]</code> - diferença no diretório
                </li>
                <li>
                <code>git diff HEAD~1</code> - Mostra o que foi alterado no último commit
                <p>OBS:  se voce usar apenas o <code> git diff</code> não contecerá nada, porque eu estou sincronizado, porém se usar o <code> git diff HEAD~1</code> servirá como um apontador (ponteiro) e mostrará o último commit do nosso branch, veja o resultado abaixo:</p>
                <p>
                    <code>
                        diff --git a/animais b/animais
                        index a4e9dcd..2532be6 100644
                        --- a/animais
                        +++ b/animais
                        @@ -1,4 +1,6 @@
                        Cachorro
                        Gato
                        Coelho
                        -Oveha
                        \ No newline at end of file
                        +Oveha
                        +Leão
                        :
                    </code>
                </p>
                </li>
                <li>
                <p>Ver Diff no GitHub</p>
                <p>Basta ir no diretorio, depois em commits e clicar no commit que deseja ver a alteração, em um interface bem interessante. Mostra que fez o commit, quanto tempo, etc..., tem como colocar revisão em toda linha do código.
                </li>
            </ul>
        </li>
    </ol>