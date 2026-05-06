# 📱 Projeto Mobile - FIAP

## 👨‍💻 Integrantes

* Davi Vieira - 556798

---

## 📖 Descrição do Projeto

Este projeto consiste no desenvolvimento de uma aplicação mobile com foco em cadastro e gerenciamento de produtos, incluindo leitura de código de barras.

O aplicativo permite:

* Cadastrar produtos
* Listar produtos cadastrados
* Ler código de barras via scanner
* Excluir produtos
* Navegar entre telas de forma simples e intuitiva

---

## 🚀 Melhorias Implementadas

### 📱 Melhoria 2: Teclado em telas pequenas

Foi implementado o uso de `KeyboardAvoidingView` para evitar que o teclado sobreponha os campos de entrada, melhorando a usabilidade em dispositivos com telas menores.

---

### 🔄 Melhoria 3: Preservação de dados ao voltar do leitor

Os dados do produto, especialmente o código de barras, agora são preservados ao retornar da tela de leitura, utilizando parâmetros de navegação (`route.params`).

---

### 📜 Melhoria 4: Ajuste de rolagem em telas pequenas

Foi aplicado o uso de `ScrollView` para permitir a rolagem da tela, garantindo que todos os elementos sejam acessíveis mesmo em dispositivos menores.

---

## 🛠️ Tecnologias Utilizadas

* React Native
* JavaScript
* Expo (se aplicável)

---

## ⚙️ Funcionalidades

* Cadastro de produtos com nome, preço e código de barras
* Listagem dinâmica dos produtos
* Leitura de código de barras
* Exclusão de itens com confirmação
* Interface adaptada para diferentes tamanhos de tela

---

## 🐞 Correções Realizadas

* Substituição de `window.confirm` por `Alert.alert` (compatível com React Native)
* Ajustes de layout para melhor responsividade
* Correção no fluxo de navegação entre telas

