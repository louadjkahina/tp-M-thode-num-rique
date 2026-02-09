# tp-M-thode-num-rique
# 🐍 TPs Python - Initiation aux Méthodes Numériques

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**Université** : [Nom de votre université]  
**Enseignant** : [Votre nom]  
**Contact** : [louadj.kahina@gmail.com]  
**Année universitaire** : 2025-2026

---

## 📋 À propos

Ce repository contient les **Travaux Pratiques (TPs)** d'initiation à Python, conçus pour préparer les étudiants au cours de **Méthodes Numériques**. 

Les TPs couvrent les fondamentaux de la programmation Python avec un accent particulier sur les outils de calcul scientifique (NumPy, Matplotlib).

---

## 🎯 Objectifs Pédagogiques

À la fin de cette série de TPs, vous serez capable de :

- ✅ Écrire des programmes Python structurés et propres
- ✅ Manipuler des données avec NumPy (vecteurs, matrices)
- ✅ Créer des visualisations scientifiques avec Matplotlib
- ✅ Définir et utiliser des fonctions pour résoudre des problèmes mathématiques
- ✅ Utiliser Git et GitHub pour versionner votre code
- ✅ Implémenter des algorithmes de méthodes numériques de base

---

## 📅 Planning des TPs

| Semaine | Thème | Contenu | Deadline | Statut |
|---------|-------|---------|----------|--------|
| **1** | [Bases Python](semaine_1_bases/) | Variables, types, opérations | 15/02/2025 | 📝 |
| **2** | [Listes et Boucles](semaine_2_listes_boucles/) | Structures de données, itérations | 22/02/2025 | 📝 |
| **3** | [Fonctions](semaine_3_fonctions/) | Définition, paramètres, retour | 01/03/2025 | 📝 |
| **4** | [NumPy](semaine_4_numpy/) | Arrays, opérations vectorielles | 08/03/2025 | 📝 |
| **5** | [Matplotlib](semaine_5_matplotlib/) | Visualisation de données | 15/03/2025 | 📝 |
| **6** | [Projet Final](semaine_6_projet/) | Synthèse des compétences | 22/03/2025 | 🎯 |

**Légende :**  
📝 TP à compléter | ✅ Terminé | 🎯 Projet final

---

## 📂 Structure du Repository

```
tps-python-initiation/
│
├── README.md                          # Ce fichier
├── INSTRUCTIONS.md                    # Guide détaillé pour les étudiants
├── LICENSE                            # Licence MIT
├── .gitignore                         # Fichiers à ignorer par Git
│
├── semaine_1_bases/                   # Semaine 1
│   ├── README.md                      # Description de la semaine 1
│   ├── TP1_bases_python.ipynb         # Notebook à compléter
│   └── exemples/                      # Exemples de code
│       └── exemple_variables.py
│
├── semaine_2_listes_boucles/          # Semaine 2
│   ├── README.md
│   ├── TP2_listes_boucles.ipynb
│   └── exemples/
│
├── semaine_3_fonctions/               # Semaine 3
│   ├── README.md
│   ├── TP3_fonctions.ipynb
│   └── exemples/
│
├── semaine_4_numpy/                   # Semaine 4
│   ├── README.md
│   ├── TP4_numpy.ipynb
│   └── exemples/
│
├── semaine_5_matplotlib/              # Semaine 5
│   ├── README.md
│   ├── TP5_matplotlib.ipynb
│   └── exemples/
│
├── semaine_6_projet/                  # Semaine 6
│   ├── README.md
│   └── sujet_projet.md                # Énoncé du projet final
│
└── ressources/                        # Ressources complémentaires
    ├── guide_github.md                # Guide GitHub pour étudiants
    ├── guide_colab.md                 # Guide Google Colab
    ├── aide_memoire_python.pdf        # Cheat sheet Python
    └── faq.md                         # Questions fréquentes
```

---

## 🚀 Comment Commencer ?

### Pour les Étudiants

Vous avez **deux options** pour travailler sur ces TPs :

#### Option 1️⃣ : Fork + Google Colab (Recommandé)

**Avantages** : Apprenez Git, créez votre portfolio GitHub

1. **Créez votre compte GitHub** (si pas déjà fait)
   - Allez sur https://github.com/signup
   - ⚠️ Utilisez un nom d'utilisateur **professionnel** (ex: `prenom-nom`)

2. **Forkez ce repository**
   - Cliquez sur le bouton **"Fork"** en haut à droite de cette page
   - Vous avez maintenant votre propre copie !

3. **Ouvrez les TPs dans Google Colab**
   - Allez sur https://colab.research.google.com
   - Fichier → Ouvrir → Onglet GitHub
   - Collez l'URL de **VOTRE fork**
   - Sélectionnez le notebook à ouvrir

4. **Travaillez et sauvegardez**
   - Complétez les exercices
   - Sauvegardez régulièrement : Fichier → Enregistrer dans GitHub

5. **Soumettez votre travail**
   - Créez une Pull Request vers ce repository
   - Voir [INSTRUCTIONS.md](INSTRUCTIONS.md) pour le détail

#### Option 2️⃣ : Téléchargement + Colab (Plus simple)

1. Téléchargez le notebook de la semaine
2. Uploadez-le dans Google Colab
3. Travaillez dessus
4. Partagez le lien Colab avec votre enseignant

📖 **Guide complet** : Consultez [INSTRUCTIONS.md](INSTRUCTIONS.md)

### Pour les Enseignants/Collaborateurs

```bash
# Cloner le repository
git clone https://github.com/[VOTRE-ORG]/tps-python-initiation.git
cd tps-python-initiation

# Créer une branche pour vos modifications
git checkout -b amelioration-tp2

# Faire vos modifications
# ...

# Commit et push
git add .
git commit -m "Amélioration du TP2"
git push origin amelioration-tp2

# Créer une Pull Request sur GitHub
```

---

## 💻 Environnement de Travail

### Option A : Google Colab (Recommandé)

✅ **Avantages** :
- Gratuit et dans le cloud
- Aucune installation nécessaire
- Fonctionne sur ordinateur, tablette, téléphone
- NumPy et Matplotlib pré-installés

**Accès** : https://colab.research.google.com

### Option B : Installation Locale

Si vous préférez travailler en local :

#### Avec Anaconda (Recommandé pour débutants)

1. Téléchargez Anaconda : https://www.anaconda.com/download
2. Installez Anaconda
3. Lancez Jupyter Notebook depuis Anaconda Navigator

#### Avec pip (Pour utilisateurs avancés)

```bash
# Créer un environnement virtuel
python -m venv venv

# Activer l'environnement
# Windows :
venv\Scripts\activate
# Linux/Mac :
source venv/bin/activate

# Installer les dépendances
pip install jupyter numpy matplotlib pandas scipy

# Lancer Jupyter
jupyter notebook
```

---

## 📚 Prérequis

### Connaissances Requises

- ✅ Mathématiques niveau lycée (fonctions, équations)
- ✅ Logique de base
- ❌ **Aucune expérience en programmation requise** - ce cours part de zéro !

### Outils Nécessaires

- Un **compte Google** (pour Colab)
- Un **compte GitHub** (pour versionner votre code)
- Un **navigateur web** moderne (Chrome, Firefox, Safari, Edge)
- Une **connexion internet**

---

## 📖 Ressources Complémentaires

### Documentation Officielle

- [Python Documentation](https://docs.python.org/fr/3/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Jupyter Documentation](https://jupyter.org/documentation)

### Tutoriels Recommandés

- [Python pour les débutants](https://www.python.org/about/gettingstarted/)
- [W3Schools Python](https://www.w3schools.com/python/)
- [Real Python](https://realpython.com/)
- [NumPy Quickstart](https://numpy.org/doc/stable/user/quickstart.html)

### Outils Interactifs

- [Python Tutor](http://pythontutor.com/) - Visualiseur d'exécution de code
- [Repl.it](https://replit.com/) - IDE en ligne
- [LeetCode](https://leetcode.com/) - Exercices de programmation

### Cheat Sheets

- [Python Cheat Sheet](ressources/aide_memoire_python.pdf)
- [NumPy Cheat Sheet](https://numpy.org/doc/stable/user/numpy-for-matlab-users.html)
- [Matplotlib Cheat Sheet](https://matplotlib.org/cheatsheets/)

---

## 🎓 Évaluation

### Notation

| Type | Poids | Détails |
|------|-------|---------|
| **Participation** | 10% | Assiduité, questions en cours |
| **TPs 1-5** | 30% | 6 points par TP |
| **Mini-projets** | 30% | Semaines 2, 3, 5 (10 points chacun) |
| **Projet final** | 30% | Semaine 6 (30 points) |

### Critères de Notation (par TP)

- ✅ **Fonctionnalité** (40%) : Le code fonctionne sans erreur
- ✅ **Complétude** (30%) : Tous les exercices sont traités
- ✅ **Qualité du code** (20%) : Code propre, commenté, structuré
- ✅ **Compréhension** (10%) : Utilisation correcte des concepts

### Deadlines

- **TPs hebdomadaires** : 1 Tp par chaque semaine
- **Projet final** : 19/03/2025 à remettre 15/04 à voir
- **Pénalité de retard** : -1 point par jour (max 10 jours)

---

## 🤝 Contribuer

Vous avez trouvé une erreur ? Une amélioration à suggérer ?

### Pour les étudiants

1. Créez une **Issue** en décrivant le problème/suggestion
2. Ou contactez directement l'enseignant par email

### Pour les enseignants/développeurs

1. Forkez le projet
2. Créez une branche : `git checkout -b feature/amelioration`
3. Commitez vos changements : `git commit -m 'Ajout de...'`
4. Poussez vers la branche : `git push origin feature/amelioration`
5. Ouvrez une Pull Request

---

## ❓ FAQ - Questions Fréquentes

### Q : Je n'ai jamais programmé, est-ce que je vais y arriver ?

**R :** Oui ! Ce cours est conçu pour les **débutants absolus**. Nous partons de zéro et progressons étape par étape.

### Q : Puis-je utiliser un autre langage que Python ?

**R :** Non, les TPs doivent être réalisés en Python. C'est le langage standard en calcul scientifique.

### Q : J'ai un Mac/Windows/Linux, est-ce compatible ?

**R :** Oui ! Google Colab fonctionne sur **tous les systèmes** via un navigateur web.

### Q : Combien de temps prévoir par TP ?

**R :** Entre **2 et 4 heures** selon votre niveau et votre rapidité. Ne vous y prenez pas la veille !

### Q : Puis-je travailler en binôme ?

**R :** Les TPs sont **individuels**, mais vous pouvez vous entraider pour comprendre les concepts. Chacun doit soumettre son propre code.

### Q : GitHub est-il obligatoire ?

**R :** **Fortement recommandé** pour apprendre Git et créer votre portfolio, mais des alternatives existent (voir avec l'enseignant).

### Q : J'ai un problème technique, qui contacter ?

**R :** 
1. Consultez d'abord la [FAQ technique](ressources/faq.md)
2. Posez votre question sur le forum/Discord de la classe
3. Contactez l'enseignant en dernier recours

---

## 📞 Support et Contact

### Enseignant

- **Email** : [louadj.kahina@gmail.com]
- **Application** : [Discord]


### Canaux de Communication

- **Email** : Pour questions personnelles/administratives
- **Issues GitHub** : Pour bugs/suggestions techniques
- **[Discord/WhatsApp]** : Pour questions rapides entre étudiants
- *

### Temps de Réponse

- Email : 24-48h (jours ouvrés)
- Issues GitHub : 48-72h
- Discord : Variable (entre étudiants)

---

## 📜 Licence

Ce projet est sous licence **MIT License**.

Vous êtes libre de :
- ✅ Utiliser ce matériel pour apprendre
- ✅ Modifier et adapter pour vos besoins
- ✅ Partager avec d'autres étudiants
- ✅ Utiliser dans des projets personnels

**Conditions** :
- Mentionnez l'auteur original
- Conservez la licence MIT

Voir [LICENSE](LICENSE) pour plus de détails.

---

## 🌟 Remerciements

- **Python Software Foundation** - Pour le langage Python
- **NumPy Community** - Pour NumPy
- **Matplotlib Team** - Pour Matplotlib
- **Google** - Pour Google Colab
- **GitHub** - Pour l'hébergement

---

## 📈 Statistiques du Cours

![GitHub Stars](https://img.shields.io/github/stars/[VOTRE-ORG]/tps-python-initiation?style=social)
![GitHub Forks](https://img.shields.io/github/forks/[VOTRE-ORG]/tps-python-initiation?style=social)
![GitHub Issues](https://img.shields.io/github/issues/[VOTRE-ORG]/tps-python-initiation)


---

## 🗺️ Roadmap

### Version Actuelle : 1.0

- ✅ 6 TPs progressifs
- ✅ Exemples de code
- ✅ Projet final

### Version Future : 2.0 (Prévue)

- ⏳ Vidéos explicatives
- ⏳ Tests automatiques
- ⏳ Exercices supplémentaires
- ⏳ Projets bonus

---

## 🎯 Après ce Cours

Une fois ce cours terminé, vous serez prêts pour :

1. **Méthodes Numériques** 🔢
   - Résolution d'équations
   - Intégration numérique
   - Équations différentielles

2. **Data Science** 📊
   - Analyse de données avec Pandas
   - Machine Learning avec scikit-learn
   - Visualisations avancées



## 📣 Annonces

### 📌 Dernières Mises à Jour

- **[Date]** : Ajout du TP5 sur Matplotlib
- **[Date]** : Correction d'une coquille dans le TP2
- **[Date]** : Ajout de ressources complémentaires

### 🎉 Événements

- **[Date]** : Session de révision avant le projet final
- **[Date]** : Conférence invitée sur Python en industrie

---

<div align="center">

### 💪 Bon courage et bon code ! 🐍

---

**Made with ❤️ by [Votre nom]**

**⭐ N'oubliez pas de star ce repo si vous le trouvez utile ! ⭐**

</div>
