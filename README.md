<div align="center">

# 🚗 CarLog

### Sistema de Locação de Veículos para Motoristas e Entregadores

<p>
  <strong>🚘 Mobilidade para quem trabalha na estrada.</strong>
</p>

<img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-F2C94C?style=for-the-badge">
<img src="https://img.shields.io/badge/Projeto-Acadêmico-2F80ED?style=for-the-badge">
<img src="https://img.shields.io/badge/UNICEPLAC-2026-27AE60?style=for-the-badge">
<img src="https://img.shields.io/badge/Spring%20Boot-Backend-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">

</div>

---

# 📋 Sobre o Projeto

O **CarLog** é um sistema de locação de veículos desenvolvido como projeto acadêmico da **UNICEPLAC**.

A plataforma tem como foco atender **motoristas e entregadores** que precisam de um veículo para realizar suas atividades profissionais.

O projeto busca oferecer uma solução digital para tornar o processo de locação de veículos mais **simples, organizado e eficiente**.

---

# 🎓 Identificação Acadêmica

| 📌 Informação | 📋 Detalhes |
|---|---|
| 🏫 **Instituição de Ensino** | UNICEPLAC |
| 🎓 **Curso** | Análise de Desenvolvimento |
| 📚 **Disciplina** | PROJETO INTEGRADO EM PROGRAMAÇÃO WEB |
| 👨‍🏫 **Orientador** | Profº Hudson Neves |
| 🚗 **Projeto** | CarLog |
| 🚧 **Status** | Em desenvolvimento |

---

# 🎯 Objetivo Geral

Desenvolver um sistema de locação de veículos destinado a **motoristas e entregadores**, proporcionando uma solução digital para facilitar o acesso e o gerenciamento dos veículos disponíveis para locação.

---

# 💡 Problema

Motoristas e entregadores muitas vezes precisam de um veículo para exercer suas atividades profissionais.

O **CarLog** busca facilitar esse processo através de uma plataforma que centraliza as informações relacionadas à locação de veículos, tornando a experiência mais organizada para os usuários.

---

# 👥 Público-Alvo

O sistema é destinado principalmente a:

- 🚗 Motoristas;
- 🛵 Entregadores;
- 👤 Profissionais que necessitam de veículos para realizar suas atividades.

---

# ⚙️ Funcionalidades

As funcionalidades do sistema estão sendo desenvolvidas pela equipe.

### 🚗 Veículos

- Cadastro de veículos;
- Consulta de veículos;
- Gerenciamento de veículos.

### 👤 Usuários

- Cadastro de usuários;
- Gerenciamento de usuários.

### 📋 Locações

- Processo de locação;
- Gerenciamento das locações;
- Consulta das informações de locação.

> ⚠️ As funcionalidades definitivas serão atualizadas conforme o desenvolvimento do projeto.

---

# 🛠️ Tecnologias Utilizadas

<div align="center">

### ☕ Backend

<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">

<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">

### 🌐 Frontend

<img src="https://img.shields.io/badge/A%20ser%20definido%20pela%20equipe-808080?style=for-the-badge">

### 🗄️ Banco de Dados

<img src="https://img.shields.io/badge/A%20ser%20definido%20pela%20equipe-808080?style=for-the-badge">

</div>

> **Observação:** Java foi incluído por ser a linguagem utilizada pelo Spring Boot. As demais tecnologias serão adicionadas conforme forem definidas pela equipe.

---

# 🌱 Spring Boot

O **Spring Boot** é utilizado no desenvolvimento do backend do CarLog.

Ele facilita a criação da aplicação Java, permitindo estruturar os recursos do sistema e disponibilizar os serviços necessários para o funcionamento da aplicação.

A utilização do Spring Boot também permite uma organização adequada do projeto, facilitando sua manutenção e evolução.

---

# 🏗️ Arquitetura da Solução

A arquitetura do sistema será baseada na separação das responsabilidades entre as diferentes partes da aplicação.

A estrutura definitiva da arquitetura será documentada conforme o desenvolvimento do projeto.

> **A ser definido pela equipe.**

---

# 🔌 API

O sistema poderá utilizar uma API para realizar a comunicação entre o frontend e o backend desenvolvido com Spring Boot.

Exemplo de fluxo:

```text
👤 Usuário
     │
     ▼
🌐 Frontend
     │
     │ HTTP Request
     ▼
☕ Spring Boot
     │
     ▼
🗄️ Banco de Dados
     │
     ▼
☕ Spring Boot
     │
     │ HTTP Response
     ▼
🌐 Frontend
     │
     ▼
👤 Usuário
