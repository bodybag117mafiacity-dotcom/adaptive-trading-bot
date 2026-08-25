# Contributing to Adaptive Trading Bot

Merci de votre intérêt pour contribuer au projet **Adaptive Trading Bot — Portfolio Opportunity Engine**.  
Ce document explique comment participer, proposer des améliorations, corriger des bugs ou ajouter des modules.

---

## 🧩 Types de contributions acceptées

Vous pouvez contribuer de plusieurs façons :

- améliorer les modules existants (scanner, engines, portfolio, exchange)
- ajouter de nouvelles stratégies
- optimiser les performances
- corriger des bugs
- améliorer la documentation
- ajouter des tests unitaires
- proposer des idées pour le moteur d’opportunité ou de risque

Toutes les contributions sont les bienvenues tant qu’elles respectent les règles ci‑dessous.

---

## 📦 Structure du projet

Le projet est organisé en modules :

core/        → moteurs principaux (scanner, opportunity, risk, math, strategy, execution)
portfolio/   → gestion du portefeuille, positions, ledger, settlement
exchange/    → intégrations API (Binance, Kucoin, DEX, EVM)
utils/       → outils, scoring, logging
config/      → fichiers de configuration
docs/        → documentation technique
tests/       → tests unitaires et d’intégration

Code

Merci de respecter cette structure lors de l’ajout de nouveaux fichiers.

---

## 🔧 Workflow GitHub

### 1. Fork du projet
Créez un fork du repository sur votre compte GitHub.

### 2. Clone du fork
git clone https://github.com/votre-compte/adaptive-trading-bot.git (github.com in Bing)

Code

### 3. Créez une branche pour votre contribution
git checkout -b feature/nom-de-la-feature

Code

### 4. Faites vos modifications
Respectez les conventions du projet et la structure des modules.

### 5. Ajoutez des tests
Toute nouvelle fonctionnalité doit inclure des tests dans `tests/`.

### 6. Commit propre
git commit -m "Ajout: description claire de la contribution"

Code

### 7. Push
git push origin feature/nom-de-la-feature

Code

### 8. Pull Request
Créez une **Pull Request** vers le repository principal.

---

## 🧪 Tests obligatoires

Avant de soumettre une PR, assurez-vous que :

- tous les tests passent  
- les nouveaux modules ont leurs propres tests  
- aucune régression n’est introduite  
- le code respecte les conventions PEP8  

---

## 📘 Style de code

Merci de respecter :

- PEP8  
- noms de classes en PascalCase  
- noms de fonctions en snake_case  
- commentaires clairs  
- docstrings pour chaque module  

---

## 🔒 Licence & Droits

Le code source est sous licence **Apache 2.0**.  
L’usage commercial est soumis à la licence **ROYALTY_LICENSE.md**.

En contribuant :

- vous acceptez que votre code soit intégré sous Apache 2.0  
- vous acceptez les conditions de la licence commerciale du projet  
- vous restez crédité comme contributeur

---

## 🤝 Code of Conduct

Soyez respectueux, professionnel et constructif.  
Les contributions toxiques ou irrespectueuses seront rejetées.

---

## 📨 Contact

Pour toute question, idée ou demande de collaboration commerciale :  
**Contactez l’auteur du projet directement.**
