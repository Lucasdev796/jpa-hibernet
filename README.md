# 🧠 Aulão: Introdução ao JPA e Hibernate (com bônus de Maven e MySQL)

Este projeto faz parte de um super aulão prático sobre **mapeamento objeto-relacional** utilizando **Java, JPA (Java Persistence API), Hibernate, Maven e MySQL**.  
Ideal para quem quer entender como funciona a persistência de dados em aplicações Java de forma profissional.

---

## 📚 O que aprendi

- Visão geral sobre **Mapeamento Objeto-Relacional (ORM)**
- Introdução à **JPA** e sua função no ecossistema Java
- Integração com o banco de dados **MySQL**
- Criação de projetos com **Maven**
- Conceitos importantes de persistência:
  - Contexto de persistência
  - Mapa de identidade (cache de objetos)
  - Carregamento tardio (lazy loading)
  - E muito mais!

---

## ✅ Pré-requisitos

- Lógica de programação
- Conceitos básicos de Programação Orientada a Objetos (POO)
- Noções básicas de banco de dados

---

## 🧰 Tecnologias utilizadas

- **Java**
- **Maven**
- **MySQL** (via XAMPP)
- **JPA**
- **Hibernate (como implementação da JPA)**

---

## 🧱 Principais Classes JPA

### 🔹 EntityManager
Responsável por realizar operações como inserir, atualizar, deletar e consultar objetos persistidos.

📌 [Documentação oficial](https://docs.oracle.com/javaee/7/api/javax/persistence/EntityManager.html)

### 🔹 EntityManagerFactory
Utilizada para criar instâncias do `EntityManager`.

📌 [Documentação oficial](https://docs.oracle.com/javaee/7/api/javax/persistence/EntityManagerFactory.html)

---

## 🛠️ Passo a passo para executar o projeto

1. **Instale o XAMPP** e inicie os serviços Apache e MySQL
2. Acesse o **phpMyAdmin** e crie uma base de dados chamada:

3. Crie um novo projeto Maven na sua IDE:
- File → New → Other → Maven Project
- Marque "Create simple project"
- Group Id: `com.educandoweb`
- Artifact Id: `aulajpamaven`

4. Adicione as dependências do Hibernate e do MySQL no `pom.xml`
5. Crie as entidades, configure o `persistence.xml`, e implemente os testes no `main()`

---

## 📌 Observações importantes

- JPA é uma **especificação (JSR 338)**, e o Hibernate é uma **implementação** que permite seu uso na prática.
- A arquitetura típica envolve o uso de `EntityManagerFactory` (escopo da aplicação) e `EntityManager` (escopo da thread ou requisição).

---

## 👨‍🏫 Agradecimentos

Esse conteúdo faz parte das aulas da [DevSuperior](https://devsuperior.com.br), com o professor **Nélio Alves**.  
Gratidão por mais uma aula de qualidade!

---

## 📷 Imagens da arquitetura e fluxo

> 🔻 Adicione aqui os arquivos de imagem `myImage` se tiver disponíveis  
(*ex: diagramas, prints da estrutura do projeto ou fluxo da aplicação*)

---

## 🚀 Vamos codar!

Clone o repositório, siga os passos e mergulhe no mundo da persistência com JPA e Hibernate.  
Qualquer dúvida ou sugestão, fique à vontade pra abrir uma issue ou entrar em contato.

---

🧑‍💻 *Projeto criado com fins didáticos e aprendizado prático de JPA + Hibernate com Maven e MySQL.*


