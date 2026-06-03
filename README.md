# 🛒 Paulo Henrique Market

## 📋 Sobre o Projeto

O Paulo Henrique Market é uma aplicação de console desenvolvida em Java com foco na prática de Programação Orientada a Objetos (POO), estruturas de dados e regras de negócio.

O sistema simula um pequeno mercado, permitindo o cadastro de produtos, listagem de itens disponíveis, compras, gerenciamento de carrinho e finalização de pedidos.

Este projeto foi criado com o objetivo de fortalecer conhecimentos em Java e desenvolvimento backend, aplicando conceitos utilizados em sistemas reais.

---

# 🚀 Funcionalidades

### 📦 Cadastro de Produtos
- Cadastro de novos produtos
- Definição de nome e preço
- Geração automática de ID

### 📃 Listagem de Produtos
- Exibição dos produtos cadastrados
- Visualização de ID, nome e preço formatado

### 🛒 Carrinho de Compras
- Adição de produtos ao carrinho
- Controle automático de quantidade
- Atualização de itens já existentes

### 💳 Finalização de Compra
- Exibição dos produtos comprados
- Exibição da quantidade de cada item
- Cálculo automático do valor total
- Limpeza automática do carrinho após a compra

### 💰 Formatação Monetária
- Exibição dos valores em Real (R$)
- Utilização de classe utilitária para padronização

---

# 🧠 Conceitos Aplicados

### 🔹 Programação Orientada a Objetos (POO)

- Encapsulamento
- Classes e Objetos
- Construtores
- Métodos
- Sobrescrita de métodos (`toString()`)

### 🔹 Estruturas de Dados

- ArrayList
- HashMap
- Map

### 🔹 Organização do Projeto

- Separação por pacotes
- Reutilização de código
- Classe utilitária
- Responsabilidade única

---

# 🏗️ Estrutura do Projeto

```text
src
│
├── main
│   └── Mercado.java
│
├── modelo
│   └── Produto.java
│
└── utils
    └── Utils.java
