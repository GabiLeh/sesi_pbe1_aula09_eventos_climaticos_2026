# Eventos Climáticos 2026
Foi revisado em sala de aula pelo professor Wellington (SENAI/SESI - Amparo) ``SQL``, ``JSON`` e ``JS`` de modo que seja criado um servidor funcional com usuários e sendo possível adicionar novos.
##### MER DER do projeto
<img src="docs/mer_der_conceitual.png">

##### Diagrama de Classes do projeto
<img src="docs/uml_dc.png">

## Tecnologias Utilizadas
* VS code
* mySQL
* Thunder Client

## Instruções para testar
1 Clone esse repositório <br>
2 Abra-o no [VS Code](https://code.visualstudio.com/download?_exp_download=d53503e735)<br>
3 Instale a extensão Thunder Client<br>
4 Clique em "New Request"<br>
5 Troque o link ao lado de GET por "http://localhost:3000/usuarios"<br>
6 Clique no GET e troque-o por POST<br>
7 Copie e cole, editando as informações:
``
{
  "nome": "macaco",
  "email": "makakin@email.com",
  "senha": "123"
}
`` <br>
8 Clique em SEND, e seu Thunder Client deverá ficar assim:<br>
<img src="docs/prints/cadastro.png">

### Ao iniciar o servidor e ir em http://localhost:3000/usuarios o novo usuário aparecerá com os outros já cadastrados:
<img src="docs/prints/get.png">

## Prints dos testes de cadastrar usuário
<img src="docs/prints/cadastro.png">

## Prints dos testes de cadastrar evento
<img src="docs/prints/cadastroevento.png">
<img src="docs/prints/cadastroevento2.png">

## Prints dos testes de listar
<img src="docs/prints/atualizarusuario2.png">

## Prints dos testes de atualizar usuário
<img src="docs/prints/atualizarusuario.png">
<img src="docs/prints/atualizarusuario2.png">

## Prints dos testes de atualizar evento
<img src="docs/prints/atualizarevento.png">
<img src="docs/prints/atualizarevento2.png">

## Prints dos testes de excluir usuário
<img src="docs/prints/exclusaousuario.png">
<img src="docs/prints/exclusaousuario2.png">

## Prints dos testes de excluir evento
<img src="docs/prints/exclusaoevento.png">
<img src="docs/prints/exclusaoevento2.png">

## Prints dos testes de resumo
<img src="docs/prints/eventosresumo.png">

## Prints dos testes de login
<img src="docs/prints/login.png">