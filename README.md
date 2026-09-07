# ✈️ Corporate Travel Manager - Système de Gestion de Billets d'Avion & Staff Travel

## 📝 Présentation du projet
Ce projet est une solution d'entreprise (B2B) clé en main conçue pour automatiser et centraliser la gestion, la demande et la validation des billets d'avion au sein d'une agence de voyage ou d'une compagnie aérienne. Elle intègre un module complet de **Staff Travel** et une gestion avancée des rôles, permettant de dématérialiser les flux manuels traditionnels (e-mails, fichiers Excel) via un workflow numérique fluide, sécurisé et performant.

> **Note :** Pour des raisons de confidentialité et de propriété intellectuelle, le code source de ce projet est maintenu privé. Ce dépôt sert de vitrine technique pour présenter l'architecture et l'interface de la solution.

---

## 📸 Captures d'écran & Démo

### Application Mobile Multi-Rôles (Salariés, RH, Admin, Staff Travel)
L'application mobile native s'adapte dynamiquement selon le profil de l'utilisateur connecté pour offrir les fonctionnalités adaptées :

<img width="300" height="350" alt="Screenshot_20260605_125150_Gallery" src="https://github.com/user-attachments/assets/4cbdf505-6dd4-4c71-a7bd-e7fe1d946842" />
<img width="300" height="350" alt="Screenshot_20260605_125124_Gallery" src="https://github.com/user-attachments/assets/fd7241f3-2d66-4274-a1ca-ac34294d5f40" />
<img width="300" height="350" alt="Screenshot_20260605_151117_Gallery" src="https://github.com/user-attachments/assets/4ae01206-7190-4347-a99a-edf0fa2185ff" />
<img width="300" height="350" alt="Screenshot_20260605_125101_Gallery" src="https://github.com/user-attachments/assets/a87b70bb-0720-41b8-b6d8-d2c0ccf240fd" />
<img width="300" height="350" alt="Screenshot_20260605_125005_Gallery" src="https://github.com/user-attachments/assets/7c232ea7-1abf-4f20-8f98-c68bfa3f4fcc" />
<img width="300" height="350" alt="Screenshot_20260605_124933_Gallery" src="https://github.com/user-attachments/assets/a9b638e4-667c-4952-ab89-49e1af5f0618" />
<img width="300" height="350" alt="Screenshot_20260605_124913_Gallery" src="https://github.com/user-attachments/assets/293a7a81-a02c-4fab-b355-4d766daceb6d" />
<img width="300" height="350" alt="Screenshot_20260605_125224_Gallery" src="https://github.com/user-attachments/assets/0bacdafa-0edb-4368-80a0-9385f476f802" />


### Tableau de Bord Web (Gestion & Approbations)
L'interface web permet aux gestionnaires de l'agence d'administrer globalement les demandes, d'intégrer les billets et de suivre les budgets de l'entreprise :
* **Pour les Agents Staff Travel :** Gestion opérationnelle du ticketing. Dès qu'une demande est validée, l'agent Staff Travel accède au dossier pour importer et uploader le billet correspondant:
  <img width="1568" height="796" alt="5" src="https://github.com/user-attachments/assets/f3e4b845-55ef-4d53-9da6-5069caa08314" />
  <img width="1697" height="935" alt="6" src="https://github.com/user-attachments/assets/7b1ab5b8-09d7-4f3a-b1bb-a4637fffc260" />
  <img width="1696" height="917" alt="1" src="https://github.com/user-attachments/assets/1028f6af-6dff-4e8c-8c12-dfeb6ae13d37" />
  <img width="1692" height="912" alt="3" src="https://github.com/user-attachments/assets/657a2a0a-79bb-4e51-8e2e-ad277acdb30a" />
  <img width="1687" height="613" alt="2" src="https://github.com/user-attachments/assets/084b48e5-8e39-49ea-8ae0-f3de6e104982" />
  <img width="813" height="677" alt="4" src="https://github.com/user-attachments/assets/7aaaed0b-56a7-4392-9dce-e7133048ac4a" />





---

## 🛠️ Stack Technique & Architecture

Le projet **Air SA** illustre une architecture full-stack moderne et polyvalente,
combinant la puissance de l'écosystème **.NET Core** pour le backend et le mobile
avec la souplesse d'**Angular** pour le web :
* **Back-end :** API REST robuste développée avec **.NET Core**, assurant la gestion
des flux métier, l'authentification/autorisation sécurisée (JWT / Micro-services /
Rôles) et le stockage de documents.
* **Front-end Web :** Interface d'administration dynamique, réactive et scalable
conçue avec **Angular 22** (TypeScript, Tailwind CSS, services REST).
* **Application Mobile :** Application native multiplateforme (Android / iOS)
développée avec **.NET MAUI** (XAML, MVVM, Firebase).
---

## ✨ Fonctionnalités Clés

*   **Espace Mobile Multi-Profils :** Une seule application mobile avec un affichage et des droits dynamiques selon le rôle de l'utilisateur (**Salariés, RH, Administrateurs, Gestionnaires Staff Travel**).
*   **Gestion complète du Staff Travel :** Processus mobile de bout en bout permettant aux employés et ayants droit de gérer leurs avantages de voyage professionnels et personnels.
*   **Intégration d'API & Consommation de Données :** Système connecté à l'API Back-end pour l'envoi, le traitement et la récupération des données de vol en temps réel.
*   **Upload & Téléchargement de Billets :** Génération ou téléversement du billet côté administration, permettant au salarié de voir instantanément les détails de son itinéraire sur son mobile et de télécharger son e-ticket.
*   **Workflow de validation hiérarchique :** Circuit d'approbation automatisé permettant aux RH et aux Admins de valider ou rejeter les demandes directement depuis leur interface.

## ~Tableau Récapitulatif des Stack Technologies (Badges GitHub)
Pour un rendu visuel moderne au sommet de votre README, vous pouvez ajouter ces badges Shield.io :
Couche Technologies & Frameworks
* Backend .NET Core / ASP.NET Web API, C#, Entity Framework Core, JWT
* Frontend Web Angular, TypeScript, Tailwind CSS, HTML5/CSS3
* Mobile .NET MAUI, XAML, C# (Architecture MVVM)
* DevOps & Tools Docker, Git, OpenAPI / Swagger, Azure DevOps
