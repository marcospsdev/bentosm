# BentoSM — Sistema de Supermercado

Início de um sistema desktop para supermercado, feito em **2018** durante o Ensino Médio Técnico em Informática, com **Java Swing** no NetBeans e banco **MySQL**.

## O que tem

- Tela de cadastro de clientes em Java Swing
- Camada de produtos: model, DAO e conexão com o MySQL
- Modelagem do banco (`bentosm.sql`) com clientes, produtos, usuários, vendas e itens de venda

## Como rodar

1. Crie o banco com o script `bentosm.sql`
2. Ajuste servidor, usuário e senha em `src/conexoes/ConexaoMySql.java`
3. Abra o projeto no NetBeans (as bibliotecas estão em `biblioteca/`) e execute `view.ViewCliente`
