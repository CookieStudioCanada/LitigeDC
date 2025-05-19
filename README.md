# Litige DC - Gestion de Dossiers de Litige

Une application web moderne pour la gestion de dossiers de litige fiscal et administratif.

## Fonctionnalités

- 📁 Gestion des dossiers de litige
- 📄 Gestion des documents (CRUD)
- 📝 Génération de documents (lettres, oppositions, avis)
- 🔍 Suivi des articles de loi pertinents
- 📱 Interface responsive

## Technologies utilisées

- HTML5
- CSS3
- JavaScript
- Bootstrap 5.3.3
- Bootstrap Icons 1.11.3

## Installation

1. Clonez le dépôt :
```bash
git clone [URL_DU_REPO]
```

2. Ouvrez `index.html` dans votre navigateur

## Structure du projet

- `index.html` - Page principale listant les dossiers
- `file.html` - Page de détail d'un dossier
- `README.md` - Documentation du projet

## Fonctionnalités à venir

- [ ] Authentification des utilisateurs
- [ ] Stockage cloud des documents
- [ ] Export PDF des documents
- [ ] Notifications par email
- [ ] API REST pour l'intégration
- [X] Modal de création de document détaillé
- [ ] **Fonctionnalité "AI Detect" :**
  - **Objectif :** Simplifier et automatiser la saisie d'informations lors de la création de *nouveaux dossiers* et fournir des suggestions intelligentes.
  - **Fonctionnement envisagé (pour la création de dossier) :**
    1. L'utilisateur initie la création d'un nouveau dossier et peut joindre des documents initiaux (ex: mise en demeure, contrat de base, etc.).
    2. Une IA analyse le contenu de ces documents initiaux.
    3. **Extraction automatique pour le dossier :**
        - Suggère un titre pertinent pour le dossier.
        - Pré-remplit la description du dossier avec les informations clés extraites.
        - Détecte et suggère le type de dossier (ex: litige fiscal, vérification, opposition) et identifie le client principal.
        - Peut identifier les articles de loi potentiellement pertinents à lister pour le dossier.
    4. **Suggestions intelligentes pour le dossier :**
        - Propose des premières étapes ou actions à considérer pour ce nouveau dossier.
        - Aide à la rédaction de prompts pour interagir avec une IA d'assistance juridique ou administrative concernant ce dossier.
  - **Interface utilisateur :** Un bouton "Lancer la détection IA" dans le modal de création de *dossier* permettrait d'initier ce processus après le téléversement de documents initiaux. Les suggestions apparaîtraient ensuite pour validation par l'utilisateur.

## Contribution

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou une pull request.

## Licence

MIT 