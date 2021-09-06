# Comandos-Git-bash
<h2>Comandos básicos para se utilizar no Git, e um pequeno guia de como utilizá-los!</h2>

<h2><li><strong>Índice</h2></strong></li>
<ol>
<li><em>Nome e Usuário</em></li>
<li><em>Clonando um Repositorio Existente</em></li>
<li><em>Gravando Alterações</em></li>
<li><em>Commits</em></li>
<li><em>Histórico de Commits</em></li>
<li><em>Limpar a Tela</em></li>
</ol>

<em><h2>1 - Nome e Usuário</h2></em>

A primeira coisa que você deve fazer quando instalar o Git é definir o seu nome de usuário e endereço de e-mail. Isso é importante porque todos os commits no Git utilizam essas informações, e está imutavelmente anexado nos commits que você realiza:

<li><strong>git config --global user.name "John Doe"</strong></li>
<li><strong>git config --global user.email johndoe@example.com</strong></li>


=======================================================================================

<em><h2>2 - Clonando um Repositorio Existente</h2></em>

Você clona um repositório com git clone [url]. Utilizamos esse comando na ultima aula prática do curso <h5>"Criando seu Primeiro Repositorio no Github Para Compartilhar Seu Progresso"</h5>
          
<li><strong>git clone [url]</strong></li>


=======================================================================================

<em><h2>3 - Gravando Alterações</h2></em>
        
Quando um repositório é inicialmente clonado, todos os seus arquivos estarão monitorados e inalterados porque você simplesmente os obteve e ainda não os editou. Conforme você edita esses arquivos, o Git passa a vê-los como modificados, porque você os alterou desde seu último commit. Você seleciona esses arquivos modificados e então faz o commit de todas as alterações selecionadas e o ciclo se repete.

Para passar a monitorar um novo arquivo, use o comando git add. Para monitorar o arquivo README, você pode rodar isso:

<li><strong>git add README</strong></li>


=======================================================================================

<em><h2>4 - Commits</h2></em>

Armazena o conteúdo atual do índice em um novo commit, juntamente com uma mensagem de registro do usuário que descreve as mudanças.
Se usa o commit depois de já ter feito o git add, para fazer o commit:

<li><strong>git commit -m "Mensagem"</strong></li>
Para commitar também os arquivos versionados mesmo não estando no Stage basta adicionar o parâmetro -a

<li><strong>git commit -a -m "Mensagem"</strong></li>
Refazendo commit quando esquecer de adicionar um arquivo no Stage:

<li><strong>git commit -m "Mensagem" --amend</strong></li>
O amend é destrutivo e só deve ser utilizado antes do commit ter sido enviado ao servidor remoto.

=======================================================================================

<em><h2>5 - Histórico de Commits</h2></em>

Depois que você tiver criado vários commits, ou se clonou um repositório com um histórico de commits existente, você provavelmente vai querer ver o que aconteceu. A ferramente mais básica e poderosa para fazer isso é o comando:

<li><strong>git log</strong></li>


=======================================================================================

<em><h2>6 - Limpar a Tela</h2></em>

Para limpar a tela do Git, basta pressionar <li><strong>CTRL + L</strong></li>.

=======================================================================================



## Link úteis:
[Lista de comandos básicos](https://comandosgit.github.io/)
