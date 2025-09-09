# 📊 Grille d'Évaluation Express

> **Outil d'évaluation des modules de démonstration** - Application web moderne et responsive pour évaluer efficacement les présentations de modules.

## 🎯 Description

La **Grille d'Évaluation Express** est une application web HTML/CSS/JavaScript qui permet d'évaluer rapidement et efficacement les modules de démonstration selon 8 critères essentiels. L'outil offre une interface moderne, une sauvegarde automatique et un design optimisé pour l'impression.

## ✨ Fonctionnalités

### 🔍 **Critères d'évaluation (8 points)**
- ✅ **Ouverture du module** - Rappel de l'enjeu client
- ✅ **Avantages explicités** - Bénéfices présentés avant la technique
- ✅ **Démonstration fluide** - Scénario court avec données pertinentes
- ✅ **Micro-Q&A géré** - Questions traitées avec parking-lot
- ✅ **Clarté visuelle** - Essentiel montré sans dispersion
- ✅ **Lien explicite** - Connexion enjeux ↔ fonctionnalités ↔ bénéfices
- ✅ **Timing respecté** - Module bouclé en 3-5 minutes
- ✅ **Next step évoqué** - Transition vers l'étape suivante

### 💾 **Fonctionnalités techniques**
- **Sauvegarde automatique** dans le localStorage du navigateur
- **Calcul de score en temps réel** (0-8 points)
- **Interface responsive** adaptée mobile/desktop
- **Design optimisé pour l'impression**
- **Réinitialisation complète** en un clic
- **Zones de notes** pour chaque critère
- **Feedback constructif** (force + axe d'amélioration)

## 🚀 Déploiement

### 🌐 **Vercel (Recommandé)**
```bash
# Le projet est configuré pour Vercel
# Déployez directement depuis GitHub
```

**URLs d'accès :**
- `https://votre-domaine.vercel.app/` (redirection automatique)
- `https://votre-domaine.vercel.app/grille_express_application_html.html` (accès direct)

### 🏠 **Local**
```bash
# Cloner le projet
git clone https://github.com/Lofp34/grille_evaluation.git
cd grille_evaluation

# Ouvrir directement dans le navigateur
open grille_express_application_html.html

# Ou utiliser un serveur local
npx serve .
```

## 📱 Utilisation

### 🎯 **Évaluation d'un module**
1. **Ouvrir l'application** dans votre navigateur
2. **Cocher les critères** atteints pendant la démonstration
3. **Remplir les notes** pour chaque critère
4. **Consigner une force** observée
5. **Noter un axe d'amélioration** prioritaire
6. **Vérifier le score** calculé automatiquement

### 💾 **Sauvegarde**
- **Automatique** : Toutes les données sont sauvegardées dans le navigateur
- **Persistance** : Les données restent disponibles entre les sessions
- **Réinitialisation** : Bouton "Réinitialiser" pour repartir à zéro

## 🛠️ Structure du projet

```
grille_evaluation/
├── grille_express_application_html.html  # Application principale
├── index.html                            # Point d'entrée avec redirection
├── vercel.json                           # Configuration Vercel
├── package.json                          # Métadonnées du projet
└── README.md                             # Documentation
```

## 🎨 Design

### 🎨 **Palette de couleurs**
- **Background** : `#f6f7fb` (gris clair)
- **Cards** : `#ffffff` (blanc)
- **Text** : `#0b1220` (bleu foncé)
- **Accent** : `#2563eb` (bleu)
- **Muted** : `#556070` (gris)

### 📱 **Responsive Design**
- **Desktop** : Grille 2 colonnes
- **Mobile** : Grille 1 colonne
- **Print** : Optimisé pour l'impression

## 🔧 Technologies

- **HTML5** - Structure sémantique
- **CSS3** - Styles modernes avec variables CSS
- **JavaScript ES6+** - Logique interactive
- **LocalStorage** - Persistance des données
- **Vercel** - Déploiement et hébergement

## 📋 Critères d'évaluation détaillés

| Critère | Description | Points |
|---------|-------------|--------|
| **Ouverture** | Rappel de l'enjeu client formulé dans ses propres mots | 1 |
| **Avantages** | Bénéfices présentés avant la présentation technique | 1 |
| **Démonstration** | Scénario court avec données pertinentes et réalistes | 1 |
| **Micro-Q&A** | Questions traitées en fin de module avec parking-lot créé | 1 |
| **Clarté visuelle** | Essentiel montré sans dispersion ni surcharge | 1 |
| **Lien explicite** | Connexion claire enjeux ↔ fonctionnalités ↔ bénéfices | 1 |
| **Timing** | Module bouclé en 3–5 minutes maximum | 1 |
| **Next step** | Transition vers le module suivant ou étape suivante | 1 |

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer :

1. **Fork** le projet
2. **Créer** une branche feature (`git checkout -b feature/AmazingFeature`)
3. **Commit** vos changements (`git commit -m 'Add some AmazingFeature'`)
4. **Push** vers la branche (`git push origin feature/AmazingFeature`)
5. **Ouvrir** une Pull Request

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 👤 Auteur

**Lofp34** - [GitHub](https://github.com/Lofp34)

## 🙏 Remerciements

- Design inspiré des meilleures pratiques UX/UI modernes
- Optimisé pour les évaluations rapides et efficaces
- Interface intuitive pour tous les utilisateurs

---

⭐ **N'hésitez pas à donner une étoile si ce projet vous est utile !**
