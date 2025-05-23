# 📦 Déploiement de logiciels avec PSAUM

## 🛠️ Contexte

Dans le cadre de mon alternance au sein du **Service Desk (SDK)**, j’utilise quotidiennement **PSAUM**, un portail interne de déploiement logiciel. Cet outil permet d’installer à distance des logiciels sur les postes utilisateurs à partir d’une bibliothèque centralisée, en lien avec l’infrastructure MECM.

## 📌 Exemple de situation

Lorsqu’un utilisateur demande l’installation d’un logiciel (ex. : navigateur, antivirus, outil métier), un ticket est ouvert via **DIADEM**. À partir de ce ticket :
- Je récupère l’**adresse MAC** du poste à équiper.
- Je sélectionne le logiciel à installer depuis la bibliothèque PSAUM.
- Je valide et lance le **déploiement automatisé**.

Le processus, entièrement géré par **MECM**, peut prendre entre **24 et 48 heures**, selon la taille du logiciel et la disponibilité des ressources réseau.

## 🔧 Traitement technique

En tant que technicien SDK :
- Je m’assure que la machine cible est bien référencée dans **MECM**.
- J’enregistre la demande dans **PSAUM** en spécifiant l’adresse MAC et le nom du logiciel.
- Je vérifie que le logiciel figure dans la **bibliothèque de paquets validés**.
- Je valide le lancement de l’installation à distance via le serveur KAS.

## ✅ Résultat

Le logiciel est déployé automatiquement sur le poste sans intervention physique. Cette méthode garantit un **gain de temps**, une **homogénéité des installations**, et une **réduction des erreurs humaines**.

---

## 🧠 Compétences mobilisées

- Maîtrise de **PSAUM** et de l’environnement **MECM**
- Gestion automatisée des installations logicielles à distance
- Connaissance des **adresses MAC et de l’inventaire réseau**
- Organisation et suivi rigoureux des demandes utilisateurs via DIADEM
