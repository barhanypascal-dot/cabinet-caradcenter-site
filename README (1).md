# 🌍 Site web du Cabinet CARAD

Ce dépôt contient le code source du site internet du **Centre Africain de Recherche et d’Analyse des Données (CARAD)**, un cabinet spécialisé en suivi-évaluation, recherche appliquée, analyse de données et renforcement de capacités en Afrique.

## 🎯 Objectifs du site
- Présenter le CARAD, sa mission et ses valeurs
- Mettre en avant les services, projets et réalisations
- Publier des ressources (rapports, articles, guides)
- Faciliter le contact avec partenaires, clients et experts
- Offrir une vitrine professionnelle en ligne

## 🗂️ Arborescence du site
- **Accueil**
- **À propos**
- **Domaines d’expertise**
- **Services**
- **Projets & Réalisations**
- **Ressources**
- **Équipe**
- **Partenaires & Clients**
- **Carrières & Opportunités**
- **Contact**

## 🚀 Technologies prévues
- **Frontend** : HTML5, CSS3, JavaScript (ou framework comme React/Vue si besoin)
- **Backend** (optionnel) : PHP ou Node.js
- **Base de données** : MySQL (si besoin de contenus dynamiques)
- **CMS possible** : WordPress/Drupal si administration simplifiée
- **Design** : Responsive (mobile-first), Tailwind CSS ou Bootstrap
- **Hébergement** : GitHub Pages (statique), Netlify, Vercel ou serveur mutualisé (OVH, Hostinger)

## 📂 Structure du dépôt
```
carad-site/
│── index.html           # Page d'accueil
│── about.html           # À propos
│── expertise.html       # Domaines d’expertise
│── services.html        # Services
│── projects.html        # Projets et réalisations
│── resources.html       # Ressources
│── team.html            # Équipe
│── partners.html        # Partenaires & Clients
│── careers.html         # Carrières & opportunités
│── contact.html         # Contact
│
├── assets/
│   ├── css/             # Feuilles de style (style.css)
│   ├── js/              # Scripts JavaScript
│   ├── img/             # Images (logo, équipe, icônes)
│   └── docs/            # Rapports et ressources téléchargeables
│
├── README.md            # Documentation du projet
└── LICENSE              # Licence (MIT par défaut)
```

## 🛠️ Installation et développement local
1. **Cloner le dépôt**
   ```bash
   git clone https://github.com/ton-compte/carad-site.git
   cd carad-site
   ```

2. **Ouvrir en local**
   - Ouvrir `index.html` dans un navigateur  
   - Ou utiliser un serveur local :
     ```bash
     python3 -m http.server 8000
     ```

3. **Modifier le contenu**
   - Les fichiers HTML sont les pages
   - `assets/css/style.css` contient le design personnalisé
   - `assets/js/` contient les scripts interactifs

## 🌐 Déploiement
- **Option 1 : GitHub Pages**
  1. Pousser le code sur la branche `main`
  2. Activer **Pages** dans les paramètres du repo
  3. Le site sera disponible à :  
     `https://ton-compte.github.io/carad-site/`

- **Option 2 : Netlify ou Vercel**
  - Connecter le dépôt GitHub et déployer automatiquement

- **Option 3 : Hébergeur web (OVH, Hostinger…)**
  - Uploader les fichiers via FTP ou Git

## 👥 Contributeurs
- **Pascal Mufungizi** – Coordinateur & Expert MERL  
- **Équipe CARAD** – Contributeurs au contenu et design

---

## 📄 Licence
Projet distribué sous licence **MIT** (libre utilisation et modification avec attribution).
