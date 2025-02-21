# Casos de Teste
<br/>



**Feature:Registro**
<br/>

**Cenário 1 : Registro bem-sucedido**
<br/>
 
 TC01
 * Dado que o usuário deseja criar uma conta
 * Quando ele preencher os campos "Nome", "E-mail" e "Senha" corretamente clicar em "Registrar"
 * E clicar em "Registrar"
 * Então o sistema deve criar a conta com sucesso e redirecioná-lo para a tela de login
<br/>


**Cenário 2 :  Registro com e-mail já cadastrado**
<br/>

TC02
* Dado que o usuário já tem uma conta registrada
* Quando ele tentar criar uma nova conta usando o mesmo e-mail
* Então o sistema deve exibir a mensagem "E-mail já cadastrado"
* E impedir o registro
<br/>



**Cenário 3 : Registro com senha fraca**
<br/>

TC03
* Dado que o usuário deseja criar uma conta
* Quando ele inserir uma senha com menos de 8 caracteres
* E tentar registrar
* Então o sistema deve exibir a mensagem "A senha deve ter pelo menos 8 caracteres"
* E impedir o cadastro
<br/>


**Cenário 4 : Registro com e-mail inválido**
<br/>

TC04
* Dado que o usuário deseja criar uma conta
* Quando ele inserir um e-mail com formato inválido (exemplo: "usuario.com.br")
* E tentar registrar
* Então o sistema deve exibir a mensagem "Formato de e-mail inválido"
<br/>


**Feature:Login**
<br/>

**Cenário 5 : Login bem-sucedido**
<br/>

TC05
* Dado que o usuário tem um cadastro válido
* Quando ele inserir um usuario e senha corretos e clicar em "Entrar"
* Então ele deve ser autenticado com sucesso 
* E redirecionado para a tela inicial
<br/>


**Cenário 6 :  Logout bem-sucedido**
<br/>

TC06
* Dado que o usuário está logado no sistema
* Quando ele clicar no botão de "Sair"
* Então ele deve ser deslogado
* E redirecionado para a tela de login
<br/>


**Cenário 7 : Login com usuario em branco**
<br/>

TC07
* Dado que o usuário deseja fazer login
* Quando ele deixar o campo usuario em branco
* E clicar em "Entrar"
* Então o sistema deve exibir uma mensagem "Preencha este campo"
<br/>


**Cenário 8 :  Login com senha vazia**
<br/>

TC08
* Dado que o usuário acessou a tela de login
* Mas deixar o campo "Senha" em branco
* E clicar em "Entrar"
* Então o sistema deve exibir a mensagem "O campo senha é obrigatório"
<br/>


**Cenário 9 : Login com senha no formato certo mas minuscula"??"**
<br/>

TC09
* Dado que o usuário deseja fazer login
* Quando ele inserir um usuario correto
* Mas a senha correta  em formatação minuscula "tia14mae32$"
* E clicar em "Entrar"
* Então o sistema deve exibir uma mensagem "Credenciais invalida"
<br/>


**Cenário 10 : Login bem-sucedido após redefinição de senha**
<br/>

TC10
* Dado que o usuário redefiniu sua senha recentemente
* Quando ele inserir a nova senha e clicar em "Entrar"
* Então ele deve conseguir acessar sua conta normalmente
<br/>

