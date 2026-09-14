 # Biblioteca Online

Sistema de biblioteca online desenvolvido para permitir que usuários
naveguem por livros, visualizem informações, adicionem produtos ao
carrinho e realizem pedidos.


# Sobre o projeto

O projeto consiste em uma plataforma de compra de livros com uma
interface simples e intuitiva.

O usuário pode criar uma conta, acessar a página inicial, pesquisar
livros, visualizar detalhes de uma obra, adicionar o livro ao carrinho
e escolher uma forma de pagamento.


# Funcionalidades

# Cadastro

- Cadastro de usuário
- Campo para nome
- Campo para e-mail
- Criação de senha
- Confirmação de senha
- Botão para entrar na plataforma

# Página inicial

- Exibição dos livros mais buscados
- Seção "Continuar lendo"
- Menu de navegação
- Categorias
- Carrinho
- Busca
- Perfil do usuário

# Detalhes do livro

- Exibição da capa
- Nome da obra
- Autor
- Descrição
- Avaliação
- Preço
- Sugestões de livros relacionados
- Botão para comprar

# Carrinho

- Visualização dos livros adicionados
- Informações do produto
- Valor do pedido
- Opção de finalizar a compra

# Pagamento

O sistema disponibiliza duas formas de pagamento:

- Cartão de crédito
- PIX

Após selecionar uma forma de pagamento, o usuário pode finalizar
o pedido.


# Fluxo do sistema

```text
┌──────────────┐
│   Cadastro   │
└──────┬───────┘
       ↓
┌──────────────┐
│ Página Inicial│
└──────┬───────┘
       ↓
┌──────────────┐
│ Livro/Produto│
└──────┬───────┘
       ↓
┌──────────────┐
│   Comprar    │
└──────┬───────┘
       ↓
┌──────────────┐
│   Carrinho   │
└──────┬───────┘
       ↓
┌──────────────┐
│   Pagamento  │
└──────┬───────┘
       ↓
┌──────────────┐
│ Finalizar    │
│    Pedido    │
└──────────────┘
