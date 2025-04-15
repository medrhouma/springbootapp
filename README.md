    # 🌿 Spring Boot + Thymeleaf - Démo ISET Tozeur

Ce projet est un exemple simple d’application web développée avec **Spring Boot 3** et le moteur de templates **Thymeleaf**. Il permet de générer dynamiquement des vues HTML à partir du backend Java.

---

## 🧰 Technologies utilisées

- **Java 21**
- **Spring Boot 3**
- **Thymeleaf**
- **Maven**
- **HTML5 & CSS3**
- **IntelliJ IDEA** (ou tout autre IDE)

---

## 🎯 Objectif pédagogique

- Apprendre à créer un projet Spring Boot avec Thymeleaf
- Créer des pages dynamiques HTML avec des fragments, des conditions, et des listes
- Comprendre la gestion des ressources statiques (CSS, images)
- Mettre en place un contrôleur de base pour afficher une vue

---

## 🗂 Structure du projet

```
backend/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/isett/backend/
│   │   │       └── controllers/
│   │   │           └── HomeController.java
│   │   └── resources/
│   │       ├── templates/
│   │       │   ├── index.html
│   │       │   └── fragments/
│   │       │       └── details.html
│   │       ├── static/
│   │       │   ├── css/
│   │       │   │   └── styles.css
│   │       │   └── img/
│   │       │       └── logo.png
│   │       └── application.properties
├── pom.xml
└── README.md
```

---

## 🚀 Démarrer le projet

1. **Cloner le dépôt :**
   ```bash
   git clone https://github.com/ton-utilisateur/springboot-thymeleaf-demo.git
   ```

2. **Ouvrir dans un IDE** (comme IntelliJ)

3. **Exécuter l’application** :
   - Lancer la classe principale annotée avec `@SpringBootApplication`

4. **Accéder dans le navigateur :**
   ```
   http://localhost:8080/
   ```

---

## 📄 Exemple d’utilisation

- Affichage simple : `http://localhost:8080/`
- Affichage avec détails : `http://localhost:8080/?showDetails=true`

---

## 🧠 Auteur

- Mohamed Rhouma  
- Étudiant à l’ISET Tozeur  
- [LinkedIn](https://www.linkedin.com/in/rhouma-mohamed-6291b02b4)  
- [GitHub](https://github.com/medrhouma)

---

## 📜 Licence

Projet open-source à but pédagogique. Libre à l’utilisation.
    
