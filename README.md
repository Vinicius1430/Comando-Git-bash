# Comandos-Git-bash
<h2>Comandos básicos para se utilizar no Git, e um pequeno guia de como utilizá-los!</h2>

        <strong><em><h3>Nome e Usuário</h3></em></strong>

A primeira coisa que você deve fazer quando instalar o Git é definir o seu nome de usuário e endereço de e-mail. Isso é importante porque todos os commits no Git utilizam essas informações, e está imutavelmente anexado nos commits que você realiza:

        <li><strong>git config --global user.name "John Doe"</strong></li>
        <li><strong>git config --global user.email johndoe@example.com</strong></li>

======================================================================================================================================================================

        <strong><em><h3>Clonando um Repositorio Existente</h3></em></strong>

Você clona um repositório com git clone [url]. Utilizamos esse comando na ultima aula prática do curso <h5>"Criando seu Primeiro Repositorio no Github Para Compartilhar Seu Progresso"</h5>
          
<li><strong>git clone [url]</strong></li>

======================================================================================================================================================================

        <strong><em><h3>Gravando Alterações</h3></em></strong>
        
Quando um repositório é inicialmente clonado, todos os seus arquivos estarão monitorados e inalterados porque você simplesmente os obteve e ainda não os editou. Conforme você edita esses arquivos, o Git passa a vê-los como modificados, porque você os alterou desde seu último commit. Você seleciona esses arquivos modificados e então faz o commit de todas as alterações selecionadas e o ciclo se repete.

Para passar a monitorar um novo arquivo, use o comando git add. Para monitorar o arquivo README, você pode rodar isso:

<li><strong>git add README</strong></li>

======================================================================================================================================================================


## Link úteis:
[Lista de comandos básicos](https://comandosgit.github.io/)
