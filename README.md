# jenkinsrepo

Dépôt de test pour une pipeline d'intégration continue (**CI/CD**) avec **Jenkins**, **Docker** et **Maven**.

## Description

Ce projet contient un `Jenkinsfile` servant de démonstration pour la mise en place d'une pipeline CI/CD automatisée avec Jenkins. Le build est exécuté dans un conteneur Docker basé sur Maven et Java (Temurin 21).

## Technologies utilisées

- [Jenkins](https://www.jenkins.io/) (pipeline CI/CD)
- [Docker](https://www.docker.com/) (`maven:3.9.9-eclipse-temurin-21-alpine`)
- [Maven](https://maven.apache.org/)

## Structure

```
.
└── Jenkinsfile   # Définition de la pipeline Jenkins
```

## Pipeline

La pipeline Jenkins effectue les étapes suivantes :

1. **Build** : lance `mvn --version` dans un conteneur Docker Maven

## Contact

**Auteur :** resendecode  
**GitHub :** [github.com/resendecode](https://github.com/resendecode)