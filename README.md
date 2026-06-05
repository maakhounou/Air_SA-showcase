# ✈️ Corporate Travel Manager - Système de Gestion de Billets d'Avion & Staff Travel

## 📝 Présentation du projet
Ce projet est une solution d'entreprise (B2B) clé en main conçue pour automatiser et centraliser la gestion, la demande et la validation des billets d'avion au sein d'une agence de voyage ou d'une compagnie aérienne. Elle intègre un module complet de **Staff Travel** et une gestion avancée des rôles, permettant de dématérialiser les flux manuels traditionnels (e-mails, fichiers Excel) via un workflow numérique fluide, sécurisé et performant.

> **Note :** Pour des raisons de confidentialité et de propriété intellectuelle, le code source de ce projet est maintenu privé. Ce dépôt sert de vitrine technique pour présenter l'architecture et l'interface de la solution.

---

## 📸 Captures d'écran & Démo

### Application Mobile Multi-Rôles (Salariés, RH, Admin, Staff Travel)
L'application mobile native s'adapte dynamiquement selon le profil de l'utilisateur connecté pour offrir les fonctionnalités adaptées :

<img width="300" height="300" alt="Screenshot_20260605_125150_Gallery" src="https://github.com/user-attachments/assets/4cbdf505-6dd4-4c71-a7bd-e7fe1d946842" />
<img width="300" height="2400" alt="Screenshot_20260605_125124_Gallery" src="https://github.com/user-attachments/assets/fd7241f3-2d66-4274-a1ca-ac34294d5f40" />
<img width="300" height="2400" alt="Screenshot_20260605_125101_Gallery" src="https://github.com/user-attachments/assets/a87b70bb-0720-41b8-b6d8-d2c0ccf240fd" />
<img width="300" height="2400" alt="Screenshot_20260605_125034_Gallery" src="https://github.com/user-attachments/assets/506d549e-382e-42ee-9b08-0d88ba52a747" />
<img width="300" height="2400" alt="Screenshot_20260605_125005_Gallery" src="https://github.com/user-attachments/assets/7c232ea7-1abf-4f20-8f98-c68bfa3f4fcc" />
<img width="300" height="2400" alt="Screenshot_20260605_124933_Gallery" src="https://github.com/user-attachments/assets/a9b638e4-667c-4952-ab89-49e1af5f0618" />
<img width="300" height="2400" alt="Screenshot_20260605_124913_Gallery" src="https://github.com/user-attachments/assets/293a7a81-a02c-4fab-b355-4d766daceb6d" />
<img width="300" height="2400" alt="Screenshot_20260605_125224_Gallery" src="https://github.com/user-attachments/assets/0bacdafa-0edb-4368-80a0-9385f476f802" />


### Tableau de Bord Web (Gestion & Approbations)
L'interface web permet aux gestionnaires de l'agence d'administrer globalement les demandes, d'intégrer les billets et de suivre les budgets de l'entreprise :


---

## 🛠️ Stack Technique & Architecture

Le projet exploite la puissance de l'écosystème **.NET** pour offrir une expérience unifiée, hautement sécurisée et performante :

*   **Back-end :** API REST robuste développée avec **.NET Core** pour la gestion des flux, de l'authentification (JWT/Rôles) et du stockage sécurisé des documents.
*   **Front-end Web :** Interface d'administration dynamique conçue avec **Blazor**.
*   **Application Mobile :** Application native multiplateforme (Android / iOS) développée avec **.NET MAUI**.

---

## ✨ Fonctionnalités Clés

*   **Espace Mobile Multi-Profils :** Une seule application mobile avec un affichage et des droits dynamiques selon le rôle de l'utilisateur (**Salariés, RH, Administrateurs, Gestionnaires Staff Travel**).
*   **Gestion complète du Staff Travel :** Processus mobile de bout en bout permettant aux employés et ayants droit de gérer leurs avantages de voyage professionnels et personnels.
*   **Intégration d'API & Consommation de Données :** Système connecté à l'API Back-end pour l'envoi, le traitement et la récupération des données de vol en temps réel.
*   **Upload & Téléchargement de Billets :** Génération ou téléversement du billet côté administration, permettant au salarié de voir instantanément les détails de son itinéraire sur son mobile et de télécharger son e-ticket.
*   **Workflow de validation hiérarchique :** Circuit d'approbation automatisé permettant aux RH et aux Admins de valider ou rejeter les demandes directement depuis leur interface.
