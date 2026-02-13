# Event-System 

## Sobre o projeto
Este repositório faz parte do curso **Java Professional** da **DevSuperior** (Módulo 2).  
O **Event-System** é um sistema de gerenciamento de eventos, desenvolvido como **desafio prático avaliativo** para aplicar conceitos de **JPA/Hibernate** e **mapeamento objeto-relacional** com **Spring Boot**.

O projeto está **concluído** e foi construído **minimizando consultas externas**, como forma de testar e validar meu conhecimento adquirido até aqui.

---

## Modelo de domínio
O sistema foi modelado com base no seguinte esquema de classes:

<img width="849" height="369" alt="image" src="https://github.com/user-attachments/assets/1f080fbe-2189-4a59-ad2a-64fce830a5c3" />

Cada entidade possui seus relacionamentos devidamente configurados conforme o diagrama acima.

---

## Objetivos do projeto
- Criar e mapear entidades (`Atividade`, `Categoria`, `Bloco`, `Participante`)  
- Implementar relacionamentos:
  - **Many-to-One** (Atividade → Categoria)  
  - **One-to-Many** (Atividade → Bloco)  
  - **Many-to-Many** (Participante ↔ Atividade)  
- Configurar banco de dados **H2** para testes  
- Popular dados iniciais com `import.sql`

---

## Povoamento
O banco foi populado com dados iniciais para testes, conforme mostrado abaixo:

<img width="879" height="545" alt="image" src="https://github.com/user-attachments/assets/5cf23bcb-8dea-4427-a995-587d87fc68c9" />

### Exemplos de tabelas populadas
- **Participante**
<img width="434" height="265" alt="image" src="https://github.com/user-attachments/assets/7fb47566-8dea-4bb5-8e70-a67f716697d1" />

- **Atividade**
<img width="838" height="185" alt="image" src="https://github.com/user-attachments/assets/77f27943-2ce9-4d7c-829a-8e6a3e373720" />

- **Participante-Atividade**
<img width="512" height="347" alt="image" src="https://github.com/user-attachments/assets/af0a8b98-b685-40ef-9d73-621d31deaecc" />

- **Bloco**
<img width="638" height="218" alt="image" src="https://github.com/user-attachments/assets/40881478-70e1-4205-9d86-de62f94dfe48" />

- **Categoria**
<img width="376" height="198" alt="image" src="https://github.com/user-attachments/assets/9f1cc133-831d-439a-9d2c-10760375f6fd" />

<span style="color:gray"><i>Nota: os dados foram semeados com datas antigas apenas para seguir o mapeamento sugerido no desafio.</i></span>

---

## Tecnologias utilizadas

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" 
       alt="Java" width="30" height="30" title="Java"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" 
       alt="Spring Boot" width="30" height="30" title="Spring Boot"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/hibernate/hibernate-plain.svg" 
       alt="Hibernate" width="30" height="30" title="Hibernate/JPA"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/maven/maven-original.svg" 
       alt="Maven" width="30" height="30" title="Maven"/>
 <img src="https://www.h2database.com/html/images/h2-logo-2.png" 
     alt="H2 Database" width="30" height="30" title="H2 Database"/>
</p>

---

## Objetivo pessoal
Este projeto foi desenvolvido como parte do meu aprendizado no curso **Java Professional**.  
Além de consolidar conceitos de **backend com Spring Boot** e **JPA/Hibernate**, este desafio serviu como **forma de avaliação prática**, para verificar minha capacidade de modelar e implementar um sistema completo.

---

✍️ Projeto concluído — feito para estudo, prática e avaliação.
