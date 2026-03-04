# 📚 Application de Gestion (PHP MVC)

## 📖 Description
Cette application est un projet développé en **PHP** suivant l’architecture **MVC (Model - View - Controller)**.  
Elle permet de gérer l’authentification des utilisateurs et la gestion des étudiants.

---

## 🚀 Fonctionnalités

- 🔐 Authentification (login / logout)
- 🛡️ Sécurité (CSRF, validation)
- 👨‍🎓 Gestion des étudiants
- 📦 Architecture MVC propre
- 🔄 Routing personnalisé

---

## 🏗️ Architecture du projet
````
project-root/
│
├── public/
│ └── index.php
│
├── src/
│ ├── Core/
│ │ ├── Router.php
│ │ ├── Request.php
│ │ ├── Response.php
│ │
│ ├── Security/
│ │ ├── Auth.php
│ │ ├── Csrf.php
│ │ ├── Middleware.php
│ │ ├── Validator.php
│ │ ├── Sanitizer.php
│ │
│ ├── Controller/
│ │ ├── BaseController.php
│ │ ├── AuthController.php
│ │ ├── EtudiantController.php
│ │
│ ├── Dao/
│ │ ├── DBConnection.php
│ │ ├── Logger.php

````

## Captures d'ecran 

### <img width="793" height="412" alt="Capture d’écran du 2026-03-02 12-54-12" src="https://github.com/user-attachments/assets/fa7249e8-44d2-47ac-b04e-7708a0c25609" />
### <img width="793" height="209" alt="Capture d’écran du 2026-03-02 12-53-51" src="https://github.com/user-attachments/assets/734b9955-845c-4e12-8b4f-be138575ec36" />
