# 🧪 Testes de API - JSONPlaceholder

## 📌 Sobre o projeto

Este projeto contém testes manuais de API realizados na JSONPlaceholder, uma API pública que simula um sistema de posts (como uma rede social simples).

O objetivo foi validar o comportamento dos principais endpoints de posts.

---

## 🚀 O que foi testado

- ✔️ Listar posts  
- ✔️ Buscar post por ID  
- ✔️ Filtrar posts por usuário  
- ✔️ Criar post  
- ✔️ Deletar post  
- ❌ Buscar post inexistente (teste negativo)  

---

## 🧠 Como os testes foram feitos

Os testes foram feitos manualmente utilizando o Postman, verificando:

- Status code das respostas  
- Estrutura dos dados retornados  
- Comportamento da API em cenários inválidos  

---

## ⚠️ Observação

A API é mockada, ou seja, as alterações (POST/DELETE) não são salvas de verdade.

---

## 📂 Arquivos do projeto

- Collection do Postman com as requisições  
- Evidências das execuções na pasta `/evidencias`  

---

## 📌 Conclusão

A API apresentou comportamento consistente nos cenários testados, incluindo respostas corretas para casos de erro.

Este projeto demonstra conhecimentos básicos em testes manuais de API e validação de serviços REST.
