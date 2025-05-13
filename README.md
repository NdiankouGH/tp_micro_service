# TP Microservice avec Spring Boot

Ce projet est un TP basé sur une architecture **microservices** avec **Spring Boot**, géré en plusieurs services indépendants, chacun ayant sa propre logique métier.

## 📦 Structure du projet

tp_micro_service/
│
├── apiGateway/ → Service de Gateway (Spring Cloud Gateway)
├── serviceAuth/ → Service d'authentification (JWT)
├── serviceCommande/ → Service de gestion des commandes
├── serviceDiscovery/ → Service Eureka Discovery (naming)
├── serviceProduit/ → Service de gestion des produits et des catégories 
└── tp_ms_front/ → Front-end du projet (si applicable)


## 🧰 Technologies utilisées

- Java 17+
- Spring Boot
- Spring Cloud (Eureka, Gateway)
- Maven
- IntelliJ IDEA
- REST APIs

## ⚙️ Lancer le projet

Chaque microservice peut être lancé séparément avec :

```bash
cd serviceAuth
./mvnw spring-boot:run
