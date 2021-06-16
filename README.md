# Elocc-teste
Para realizar este teste serão utilizadas as seguintes tecnologias:
* React com (styled components)
* Nodejs
* Html
* Css
* Testes unitários (opcional)

# Escopo do projeto
* Deverá ser desenvolvido um módulo de cadastro de clientes. 
* Deverá ser desenvolvido um módulo de login e logout do sistema
* O módulo clientes deve conter os seguintes campos (Nome, Sobrenome, Logradouro, Número, Cidade, Estado, Bairro, Complemento, Celular, Telefone Fixo e Email )
* O Back-end deve servir endpoints para o front-end
* O sistema deve seguir os requisitos listados abaixo:

## Requisitos Funcionais

### Cliente

#### **Cadastro**
Deverá ser realizado um cadastro de clientes no sistema com validação de nome e email obrigatórios
#### **Exclusão**
Deverá ser realizado opção de exclusão de clientes do sistema com modal de confirmação antes da exclusão
#### **Alteração**
Deverá ser realizada alteração de dados do cliente com validação de nome e email obrigatórios
#### **Listagem**
Deverá ser exibida uma listagem de clientes cadastrados com opção de consulta por nome e email

### Login

#### **Login**
Deverá ser implementado um sistema de login para acesso aos clientes cadastrados onde o mesmo deve acessar um endpoint retornando um jwt.
Os dados para realizar o login são E-mail e Senha.
#### **Logout**
Deverá ser implementado um sistema de logout

## Requisitos não funcionais

1. Utilizar banco de dados sqlite
2. Utilizar JWT para login
3. Subir tanto font-end como back-end para github em um repositório público

### Tempo de execução do teste

O teste deverá ser executado em no máximo 2 dias.

### Avaliação

A avaliação ocorrerá em no máximo 3 dias após a entrega do projeto. Serão avaliados: codificação, estrutura e organização de código e senso de resolução do problema.
