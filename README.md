# 🪐 SWAPI Postman Testing

> Coleção de testes automatizados de API utilizando **Postman + JavaScript**, com foco em boas práticas de **Quality Assurance (QA)** e validação de respostas JSON.

---

## 📖 Sobre o projeto

Este repositório reúne uma **Collection do Postman** criada para praticar testes automatizados consumindo a **SWAPI (Star Wars API)**.

O objetivo foi consolidar conceitos fundamentais de **testes de API**, trabalhando exclusivamente com requisições **GET** e desenvolvendo validações robustas para garantir a integridade dos dados retornados pela API.

### 🎯 Objetivos

* Praticar testes automatizados de API
* Validar respostas HTTP e estrutura JSON
* Utilizar **Path Variables** para requisições dinâmicas
* Escrever testes reutilizáveis em **JavaScript**

---

## 🚀 Testes implementados

Cada endpoint possui validações automatizadas que garantem a qualidade da resposta da API.

### ✅ Status Code

Verifica se a requisição retorna corretamente:

* **200 OK**

### 📦 Estrutura de dados

Garante que propriedades obrigatórias estejam presentes no JSON, como:

* `name`
* `title`
* `episode_id`

### 🔍 Type Checking

Valida o tipo de cada informação retornada, por exemplo:

| Campo          | Tipo esperado |
| -------------- | ------------- |
| `episode_id`   | Number        |
| `director`     | String        |
| `release_date` | String        |

### 🛡️ Validação de conteúdo

Evita respostas incompletas verificando que campos obrigatórios:

* Não sejam `null`
* Não estejam vazios (`""`)
* Possuam valores válidos

---

## 🛠️ Tecnologias utilizadas

| Tecnologia     | Finalidade                        |
| -------------- | --------------------------------- |
| **Postman**    | Criação e execução da Collection  |
| **JavaScript** | Scripts de testes automatizados   |
| **SWAPI**      | API REST utilizada para os testes |

---

## ⚙️ Como executar

1. Clone este repositório.
2. Abra o **Postman**.
3. Clique em **Import** e selecione a Collection (`.json`).
4. Abra qualquer requisição e informe um **ID válido** nas **Path Variables**.
5. Clique em **Send**.
6. Confira os resultados na aba **Test Results**.

---

## 📂 Estrutura do projeto

```text
📦 swapi-postman-testing
 ┣ 📜 SWAPI.postman_collection.json
 ┗ 📜 README.md
```

---

## 📚 Conceitos praticados

* Testes de API REST
* Validação de Status Code
* Assertions com `pm.test()`
* Path Variables
* Estruturação de Collections
* Quality Assurance (QA)

---

## ⭐ Resultado

Este projeto demonstra a aplicação de **boas práticas em testes automatizados de APIs**, servindo como portfólio para estudos em **QA**, **Postman** e **automação de testes**.

