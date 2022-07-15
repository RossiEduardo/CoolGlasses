

![logo](imagens/imagem-readme.png)

Projeto desenvolvido para a disciplina de Introdução ao Desenvolvimento Web, no ano de 2022.

O tema escolhido por nós foi desenvolver um website que realiza a venda de óculos.

### Autores

| NUSP     | Nome                       |
|----------|----------------------------|
| 11796594 |	Thiago Henrique dos Santos Cardoso     |
| 10716887 |  Eduardo Vinicius Barbosa Rossi         |
| 11796830 |  Adrio Oliveira Alves                   |

### Tabela de conteúdos 

- [1. Requisitos](#1-requisitos)
- [2. Descrição do Projeto](#2-descrição-do-projeto)
- [3. Comentários sobre o código](#3-comentários-sobre-o-código)
- [4. Plano de teste](#4-plano-de-teste)
- [5. Resultados dos testes](#5-resultados-dos-testes)
- [6. Building](#6-building)
- [7. Problemas](#7-problemas)
- [8. Comentários](#8-comentários)

## 1. Requisitos

- O sistema deve permitir dois tipos de usuários: administradores e clientes. 
- O usuário deve se registrar utilizando seu nome, email e senha.
- O usuário pode atualizar seu perfil a qualquer momento, adicionando foto, CPF, endereço, telefone e celular ou alterando o que já está lá. 
- O usuário pode verificar os itens disponíveis, utilizando para isso a aba de produtos.
- O cliente pode realizar compras, utilizando para isso as informações do seu cartão, CPF e endereço de entrega. É preciso estar logado.
- Uma compra é feita clicando sobre o produto e adicionando ele ao carrinho e após isso, acessando o carrinho e finalizando-a. 
- O administrador pode realizar a inclusão, remoção ou edição de produtos. 
- Os produtos são registrados com ID, título, cor, tipo da lente, gênero, categoria, preço, descrição, quantidade disponível, quantidade vendida e imagem. 


## 2. Descrição do projeto

CoolGlasses é uma loja virtual de óculos. O projeto será desenvolvido implementando HTML, CSS, javascript e outros, além do uso de um banco de dados. 

### Diagrama de navegação
![navegacao](imagens/diagramaNavegacao.png)

#### Mockups

Os mockups se encontram no diretório 'mockups', além de todos estarem contidos também nesse link para o figma que foi utilizado: [Figma ](https://www.figma.com/file/Q0Aj5abwo0EIDR1jyfYADb/CoolGlasses?node-id=0%3A1)

Acesso aos arquivos dos mockups: 
- [Home](/mockups/home.png)
  - [Produtos](/mockups/produtos.png)
    - [Produto](/mockups/produto.png)
- [Login](/mockups/login.png)
- [Cadastro](/mockups/cadastro.png)
- [Perfil do Cliente](/mockups/perfil.png)
- [Carrinho](/mockups/carrinhoo.png)
  - [Finalizar Compra](/mockups/finalizarcompra.png)

### Funcionalidades

- Apresentar alguns produtos na homepage.
- Apresentar todos os produtos com preços com a possibilidade também de filtrar por tipos de óculos.
- Visualizar de um produto em sua pagina especifica, contendo com uma descrição e um botão para adicionar ao carrinho.
- Possibilidade do usuário se registrar com nome, e-mail e senha.
- Acessar e editar as credenciais do usuário após estar logado.
- Apresentar os produtos no carrinho, com possibilidade de editar quantidades, etc.
- Finalizar compra, a partir da inserção do CPF, número do cartão, data de validade do cartão, codigo de segurança e endereço de entrega

### Informações armazenadas no Servidor

#### Contas
- CPF
- Nome
- Foto
- Telefone
- Celular
- Endereço
- E-mail
- Senha

#### Produtos
- ID
- Título
- Categoria
- Preço
- Descrição
- Imagem
- Quantidade Disponível
- Quantidade Vendida

## 8. Comentários

#### Como rodar
1) Abra dois terminais
2) No primeiro, entre na pasta cool-glasses, que baixou do repositório e digite
~ npm run serve ~
3) No segundo, entre na pasta cool-glasses, que baixou do repositório e digite
~ npx json-server --watch .\src\objects\index.js ~


## 3. Comentários sobre o código
## 4. Plano de teste
## 5. Resultados dos testes
## 6. Building
## 7. Problemas
## 8. Comentários
