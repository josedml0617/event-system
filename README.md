# Event-System 
## Sobre o projeto
Este repositório faz parte do curso **Java Professional** da **DevSuperior** (Módulo 2).  
O **Event-System** é um sistema de gerenciamento de eventos, desenvolvido como desafio prático para aplicar conceitos de **JPA/Hibernate** e **mapeamento objeto-relacional** com **Spring Boot**.

O projeto está **concluído** e foi construído como parte do aprendizado.

## Modelo de domínio
O sistema foi modelado com base no seguinte esquema de classes:

<img width="849" height="369" alt="image" src="https://github.com/user-attachments/assets/1f080fbe-2189-4a59-ad2a-64fce830a5c3" />[

Cada entidade possui seus relacionamentos devidamente configurados conforme o diagrama acima.

## Objetivos do projeto
- Criar e mapear entidades (`Atividade`, `Categoria`, `Bloco`, `Participante`)  
- Implementar relacionamentos:
  - **Many-to-One** (Atividade → Categoria)  
  - **One-to-Many** (Atividade → Bloco)  
  - **Many-to-Many** (Participante ↔ Atividade)  
- Configurar banco de dados **H2** para testes  
- Popular dados iniciais com `import.sql`

- ## Povoamento
<img width="879" height="545" alt="image" src="https://github.com/user-attachments/assets/5cf23bcb-8dea-4427-a995-587d87fc68c9" />

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



## Objetivo pessoal
Este projeto foi desenvolvido como parte do meu aprendizado no curso **Java Professional**.  
A ideia foi aplicar na prática os conceitos de **backend com Spring Boot**, reforçar o uso de **JPA/Hibernate** e ganhar experiência em **modelagem de sistemas reais**.

---

✍️ Projeto concluído — feito para estudo e prática.
