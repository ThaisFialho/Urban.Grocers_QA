# 🧪 Urban.Grocers_QA

Este projeto foi realizado como parte do curso de QA da TripleTen, com foco em testar os novos recursos da API do sistema Urban.Grocers.  
A tarefa consistiu em analisar os requisitos do back-end, planejar os testes e validá-los utilizando o Postman.

---

## 🎯 Objetivo

Testar os novos endpoints implementados pelos desenvolvedores, garantindo que atendam aos requisitos funcionais especificados na documentação da API (apiDoc).  
As áreas testadas envolvem o gerenciamento de kits de produtos e o serviço de entrega "Order and Go".

---

## 📌 Funcionalidades Testadas

- Adição de produtos com IDs e quantidades variados, incluindo casos inválidos e limites de quantidade.
- Testes com kits inexistentes e diferentes números de produtos.
- Validação dos parâmetros deliveryTime, productsCount e productsWeight com valores válidos, inválidos, vazios e ausentes.
- Testes para garantir respostas corretas em múltiplas combinações.

---

## 🛠️ Ferramentas Utilizadas

- Postman para envio das requisições e análise das respostas  
- Planilha para organizar e documentar o checklist de testes  
- apiDoc como base técnica para análise dos requisitos da API  
- Jira para relatar os bugs (quando aplicável)

---

## ✅ Resultado

- Elaborei um checklist completo de testes baseado na documentação técnica (apiDoc) para as duas funcionalidades novas  
- Executei os testes no Postman  
- Validei os comportamentos esperados da API, incluindo respostas positivas e erros  
- Registrei os resultados dos testes em uma planilha  
- Reportei bugs quando necessário, simulando um ambiente profissional com uso do Jira

---

## 📚 O que aprendi

- Como interpretar e transformar requisitos técnicos de uma API em cenários de teste práticos  
- Criação de checklists e documentação de testes de forma organizada e profissional  
- Execução de testes manuais em APIs REST utilizando o Postman  
- Identificação de comportamentos esperados e falhas da API  
- Comunicação clara de resultados e possíveis erros

---

## 🚀 Melhorias Futuras

- Automatizar os testes com ferramentas como Newman  
- Adicionar validações com JSON Schema para reforçar a estrutura das respostas  
- Implementar mais testes negativos para aumentar a cobertura  
- Realizar testes de carga nos endpoints mais críticos  
- Versionar e integrar o checklist com ferramentas de CI/CD

