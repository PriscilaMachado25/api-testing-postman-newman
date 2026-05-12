# API Automation Testing - Postman & Newman 🚀

Este projeto contém uma suíte de testes automatizados para validação de APIs, focada em garantir a integridade dos dados e o cumprimento das regras de negócio.

## 🛠️ Tecnologias Utilizadas
* **Postman:** Criação e execução das coleções de testes.
* **Newman:** Execução dos testes via linha de comando (CLI).
* **JavaScript:** Scripts de pré-requisição e testes (assertions).
* **JSON:** Formato de troca de dados.

## 📝 O que é testado?
* Verificação de Status Codes (200, 201, 400, etc).
* Validação de JSON Schema.
* Testes de Contrato.
* Validação de tempo de resposta (Performance básica).
* Testes de ponta a ponta (E2E) entre diferentes endpoints.

## 🚀 Como executar os testes

### Pré-requisitos
Ter o **Node.js** instalado e o Newman globalmente:
```bash
npm install -g newman
