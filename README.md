#  Architecture Microservices : Client React pour API REST

## Étape : Installation de Node.js, npm et React

**Vérification de l'installation**

<img width="859" height="259" alt="Capture d&#39;écran 2025-12-01 222109" src="https://github.com/user-attachments/assets/514a9722-19d3-4f62-9532-02929f232c12" />

**Installation de Create React App**

<img width="959" height="474" alt="Capture d&#39;écran 2025-12-01 222140" src="https://github.com/user-attachments/assets/11de4cb4-3080-4c5c-9762-06713a12d52e" />

---

## Étape : Initialisation du Projet React

**Création d'un projet React :**

<img width="960" height="498" alt="Capture d&#39;écran 2025-12-01 223617" src="https://github.com/user-attachments/assets/0e0f1e8e-cb1b-46d2-ad04-a822e2f9c7c2" />

---

## Étape : Configuration du Endpoint

// src/config.js
const API_BASE_URL = "http://localhost:8082/api";

export default API_BASE_URL;

---

## Étape : Création des Composants

Un composant React est une unité de base qui permet de structurer une application. Dans cette étape, un composant nommé CompteList est créé pour afficher une liste des comptes récupérés depuis l'API REST.

---

## Étape : Création du Formulaire

Un formulaire React est un élément interactif qui permet aux utilisateurs de saisir des données et de les envoyer à un serveur. Dans cette étape, un composant nommé CompteForm est créé pour ajouter ou mettre à jour un compte via l'API REST.

---

## Étape : Intégration dans l'Application

Cette étape consiste à intégrer les composants CompteList et CompteForm dans le fichier principal App.js afin de les afficher dans l'application React.

***Fichier src/App.js***

Le fichier App.js est le point d'entrée de l'application. Il sert à assembler les différents composants pour former l'interface utilisateur.

---

## Étape : Test de l'Application

**Execution du application MsBanqueApplication**

<img width="945" height="452" alt="Capture d&#39;écran 2025-12-01 233615" src="https://github.com/user-attachments/assets/ee49e1cd-2f3a-4ac6-b1d4-94576334f9d9" />

**Postman**

<img width="960" height="495" alt="Capture d&#39;écran 2025-12-02 000547" src="https://github.com/user-attachments/assets/4e94160f-62a6-4a06-b091-1e206a556cdd" />

**Base de données**

<img width="247" height="101" alt="Capture d&#39;écran 2025-12-01 235310" src="https://github.com/user-attachments/assets/8a650305-58ab-43a5-834b-e9a8823491f4" />

**Exécuter l'application avec :**

```
npm start
```

**L'application sera disponible sur http://localhost:3000.**

<img width="921" height="499" alt="Capture d&#39;écran 2025-12-02 000608" src="https://github.com/user-attachments/assets/267dbe52-8890-4722-b234-df8cc0583c06" />

**Ajout d'un Compte**

<img width="919" height="503" alt="Capture d&#39;écran 2025-12-02 000633" src="https://github.com/user-attachments/assets/30edb39e-94cd-4c00-9c4f-3780c2d82bba" />

**Element ajouté**

<img width="920" height="501" alt="Capture d&#39;écran 2025-12-02 000642" src="https://github.com/user-attachments/assets/130b39d7-2a50-44b1-abfc-2a8ec0db8c7e" />

**Test avec Postman**

<img width="960" height="500" alt="Capture d&#39;écran 2025-12-02 000655" src="https://github.com/user-attachments/assets/4d7ade13-1560-4b31-8a07-6cb80124e39b" />

---

## Structure du projet

<img width="383" height="490" alt="image" src="https://github.com/user-attachments/assets/88460b9e-420d-450e-b508-f52c48b2df11" />

**Compte-client**

<img width="371" height="434" alt="image" src="https://github.com/user-attachments/assets/48fc7dce-9072-43b2-9a76-eb03bc00ccb5" />

**Compte-Rest**

<img width="367" height="447" alt="image" src="https://github.com/user-attachments/assets/01471fea-fbdb-44e7-a41c-8d764b6021a1" />

---


## Auteur

**Nom :** JARDI Siham

**Cours :** Architecture Microservices : Conception, Déploiement et Orchestration

**Date :** Decembre 2025

**Encadré par :** Pr.Mohamed LACHGHAR


