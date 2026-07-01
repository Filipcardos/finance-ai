# 💸 Amon Finance AI

> API inteligente para análise e classificação de gastos financeiros utilizando Java + Spring Boot

---

## 📌 Sobre o Projeto

O **Amon Finance AI** é uma API REST desenvolvida em Java com foco em análise financeira inteligente.

A aplicação é capaz de:
- Classificar automaticamente transações
- Gerar insights financeiros
- Servir como base para integração com IA generativa

Este projeto foi desenvolvido com foco em **arquitetura limpa, boas práticas e experiência de produto**, simulando uma solução real de fintech.

---

## ✨ Funcionalidades

 Classificação automática de despesas  
 API REST estruturada  
 Integração com banco de dados  
 Estrutura preparada para IA  
 Organização em camadas (Controller, Service, Repository)  

---

## 🧠 Exemplo de uso
```
📥 Entrada
  {  "descricao": "Uber viagem", "valor": 30}

📥 Saída

{  "id": 1, "descricao": "Uber viagem", "valor": 30.0,
  "categoria": "Transporte"}
```

## 🛠️ Tecnologias Utilizadas

 Java 17

 Spring Boot

 Maven

 JPA / Hibernate

 H2 Database

🔧 Lombok

## 🏗️ Arquitetura
O projeto segue uma arquitetura em camadas:
controller → recebe requisições
service → lógica de negócio (inteligência)
repository → acesso ao banco
model → entidades

## 💼 Objetivo do Projeto
Este projeto foi desenvolvido para:

Demonstrar habilidades em Java Backend
Aplicar boas práticas de arquitetura
Criar um sistema com potencial real de mercado
Evoluir para uma aplicação com IA integrada


## 👨‍💻 Autor
Filipe Cardoso

