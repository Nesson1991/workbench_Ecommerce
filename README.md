# Refinando o Modelo Conceitual de Banco de Dados E-Commerce com MySQL Workbench

Este repositório contém o projeto desenvolvido durante o desafio de **Formação SQL Database Specialist** na plataforma DIO. O objetivo do projeto foi **refinar um modelo conceitual de banco de dados para um sistema de E-Commerce**, utilizando o **MySQL Workbench** para a modelagem.

## 💡 Aprendizado

O desafio focou na **criação de um modelo relacional** para representar as principais entidades do sistema de E-Commerce, como **Clientes**, **Produtos**, **Pedidos**, e seus relacionamentos. Durante a modelagem, conceitos como **chaves primárias**, **chaves estrangeiras**, e **integridade referencial** foram aplicados para garantir um banco de dados robusto e confiável.

### 📌 Principais Etapas:
- Definição das entidades e atributos principais;
- Estabelecimento dos relacionamentos entre as tabelas;
- Implementação do modelo no MySQL Workbench através do diagrama ER (Entidade-Relacionamento);
- Ajustes no design para otimização e escalabilidade.

### 🔧 Detalhes do Refinamento Solicitado:
1. **Cliente PJ e PF** – Uma conta pode ser **Pessoa Jurídica (PJ)** ou **Pessoa Física (PF)**, mas **não pode conter ambas as informações simultaneamente**. Para isso, o modelo foi ajustado com uma estrutura condicional, permitindo a escolha de uma das duas modalidades para cada cliente.
   
2. **Pagamento** – O sistema foi refinado para permitir que cada cliente tenha **mais de uma forma de pagamento cadastrada**. Foi criado um relacionamento adequado entre as entidades de **Clientes** e **Pagamentos**, garantindo flexibilidade no processo de checkout.

3. **Entrega** – Cada pedido possui um **status de entrega** e um **código de rastreio** associados. Essas informações foram incluídas como atributos adicionais na entidade **Entrega**, assegurando que o cliente possa acompanhar o status e o progresso da entrega em tempo real.

## 🛠️ Ferramentas Utilizadas

- **MySQL Workbench**: Ferramenta principal para a modelagem do banco de dados.
- **MySQL**: Banco de dados relacional para testar e implementar o projeto.

## 📂 Estrutura do Projeto

O repositório contém:
- O arquivo de **modelagem visual** gerado no MySQL Workbench (.mwb);
- Script SQL para **criação das tabelas** com seus respectivos relacionamentos.
