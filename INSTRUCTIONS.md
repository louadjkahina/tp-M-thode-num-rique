# 📘 INSTRUCTIONS - Guide Complet pour les Étudiants

## 🎯 Bienvenue !

Ce document contient **toutes les instructions** pour réussir vos TPs Python. Lisez-le attentivement avant de commencer.

---

## Table des Matières

1. [Configuration Initiale](#-1-configuration-initiale)
2. [Workflow Hebdomadaire](#-2-workflow-hebdomadaire)
3. [Soumettre un TP](#-3-soumettre-un-tp)
4. [Bonnes Pratiques](#-4-bonnes-pratiques)
5. [Résolution de Problèmes](#-5-résolution-de-problèmes)
6. [Évaluation](#-6-évaluation)

---

## 🚀 1. Configuration Initiale

### A. Créer votre Compte GitHub

**⏱️ Durée estimée : 5 minutes**

1. Allez sur **https://github.com/signup**

2. Remplissez le formulaire :
   - **Email** : Utilisez votre email étudiant `@universite.fr`
   - **Mot de passe** : Choisissez un mot de passe fort
   - **Nom d'utilisateur** : ⚠️ **TRÈS IMPORTANT** - Choisissez un nom PROFESSIONNEL
   
   ✅ **Bons exemples** :
   - `jean-dupont`
   - `marie-martin`
   - `ahmed-benali-dev`
   
   ❌ **À éviter** :
   - `supergamer2024`
   - `xx-dark-lord-xx`
   - `coolboy123`
   
   **Pourquoi ?** Les recruteurs regardent GitHub. Un nom professionnel = meilleure impression.

3. Vérifiez votre email et cliquez sur le lien de confirmation

4. **Complétez votre profil** :
   - Photo : Une vraie photo de vous (professionnel)
   - Bio : "Étudiant(e) en [votre formation] | Python, NumPy, Méthodes Numériques"
   - Localisation : Votre ville

### B. Activer le Pack Étudiant GitHub (BONUS)

**⏱️ Durée : 5 minutes (validation : 1-7 jours)**

1. Allez sur **https://education.github.com/pack**
2. Cliquez sur **"Get student benefits"**
3. Remplissez le formulaire avec votre email étudiant
4. Uploadez une preuve (carte étudiant, certificat de scolarité)
5. Attendez la validation par email

**Ce que vous obtenez GRATUITEMENT** :
- Repositories privés illimités
- GitHub Copilot (assistant IA pour coder)
- Canva Pro
- Heroku, DigitalOcean, etc.
- Cours gratuits sur diverses plateformes

### C. Forker le Repository du Cours

**⏱️ Durée : 2 minutes**

1. Allez sur le repository du cours (lien fourni par l'enseignant)
   - URL : `https://github.com/[ORGANISATION]/tps-python-initiation`

2. En haut à droite, cliquez sur le bouton **"Fork"**
   
   ![Fork Button](https://docs.github.com/assets/cb-23088/mw-1440/images/help/repository/fork_button.png)

3. Sur la page du fork :
   - **Owner** : Votre compte (automatique)
   - **Repository name** : Laissez `tps-python-initiation`
   - **Description** : "Mes TPs Python pour le cours de Méthodes Numériques"
   - ☑️ **Copy the main branch only** : Cochez

4. Cliquez **"Create fork"**

5. ✅ **Vous avez maintenant VOTRE copie personnelle du repository !**
   - URL de votre fork : `https://github.com/VOTRE-NOM/tps-python-initiation`

### D. Configurer Google Colab

**⏱️ Durée : 2 minutes**

1. Allez sur **https://colab.research.google.com**

2. Connectez-vous avec votre compte Google (celui de votre université si possible)

3. Autorisez Colab à accéder à GitHub :
   - Menu **"Fichier"** → **"Ouvrir un notebook"**
   - Onglet **"GitHub"**
   - Cliquez sur **"Autoriser l'accès à GitHub"**
   - Connectez-vous à GitHub si demandé
   - Autorisez Colab

4. ✅ **Colab peut maintenant lire et écrire dans vos repos GitHub !**

---

## 📝 2. Workflow Hebdomadaire

### Vue d'Ensemble

```
Lundi : Nouveau TP publié
   ↓
Mardi-Jeudi : Vous travaillez sur le TP
   ↓
Vendredi-Samedi : Finalisation
   ↓
Dimanche 23h59 : DEADLINE - Soumission via Pull Request
```

### Étape par Étape

#### Étape 1 : Synchroniser votre Fork (Si besoin)

**À faire si l'enseignant a ajouté de nouveaux TPs**

1. Allez sur **VOTRE FORK** sur GitHub
2. Si vous voyez un message : "This branch is X commits behind [prof]/tps-python"
3. Cliquez sur **"Sync fork"** → **"Update branch"**
4. ✅ Votre fork est à jour !

#### Étape 2 : Ouvrir le TP dans Google Colab

1. Allez sur **https://colab.research.google.com**

2. **"Fichier"** → **"Ouvrir un notebook"**

3. Cliquez sur l'onglet **"GitHub"**

4. Dans le champ de recherche, entrez :
   - `https://github.com/VOTRE-NOM/tps-python-initiation`
   - ⚠️ Remplacez `VOTRE-NOM` par votre nom d'utilisateur GitHub !

5. La liste des notebooks s'affiche

6. Cliquez sur celui de la semaine, par exemple :
   - `semaine_1_bases/TP1_bases_python.ipynb`

7. ✅ Le notebook s'ouvre dans Colab !

#### Étape 3 : Travailler sur le TP

**Pendant votre travail :**

1. **Lisez les instructions** de chaque exercice attentivement

2. **Écrivez votre code** dans les cellules prévues

3. **Testez votre code** :
   - Exécutez une cellule : `Shift + Enter`
   - Vérifiez les résultats
   - Corrigez si nécessaire

4. **Commentez votre code** :
   ```python
   # Calcul de la moyenne
   total = sum(notes)
   moyenne = total / len(notes)  # Division par le nombre de notes
   print(f"La moyenne est : {moyenne}")
   ```

5. **Sauvegardez régulièrement** (voir étape 4)

#### Étape 4 : Sauvegarder dans GitHub

**⚠️ IMPORTANT : Sauvegardez toutes les 30 minutes minimum !**

1. Dans Colab, menu **"Fichier"** → **"Enregistrer une copie dans GitHub"**

2. Une fenêtre s'ouvre avec plusieurs champs :

   **a) Repository**
   - Sélectionnez **VOTRE FORK** : `VOTRE-NOM/tps-python-initiation`
   - ⚠️ PAS le repository du prof !

   **b) Branch**
   - Laissez `main` (par défaut)

   **c) File path**
   - Laissez tel quel, par exemple : `semaine_1_bases/TP1_bases_python.ipynb`

   **d) Commit message** (le plus important !)
   - Décrivez ce que vous avez fait
   
   ✅ **Bons exemples** :
   - "Exercices 1 et 2 complétés"
   - "TP1 terminé - tous les exercices validés"
   - "Correction de l'exercice 3"
   - "Ajout de commentaires"
   
   ❌ **Mauvais exemples** :
   - "update"
   - "modif"
   - "test"
   - "zzz"

3. Cliquez **"OK"**

4. ✅ **Votre travail est sauvegardé sur GitHub !**

5. **Vérifiez** : Allez sur votre fork GitHub, vous devriez voir votre nouveau commit

**🔁 Répétez cette sauvegarde régulièrement pendant tout le TP**

#### Étape 5 : Vérifier votre Travail

Avant de soumettre, assurez-vous que :

- [ ] Tous les exercices sont complétés
- [ ] Tout le code s'exécute sans erreur
- [ ] Les résultats sont corrects
- [ ] Le code est commenté
- [ ] Vous avez fait plusieurs commits (preuve de travail progressif)

---

## 📤 3. Soumettre un TP

### Quand Soumettre ?

- **Deadline** : Dimanche 23h59 de chaque semaine
- **Anticipez !** Ne vous y prenez pas la dernière minute

### Comment Soumettre ? (Pull Request)

#### Étape 1 : Dernière Sauvegarde

1. Finalisez votre TP dans Colab
2. Faites une **dernière sauvegarde dans GitHub**
3. Message de commit : "TP[X] final - prêt pour évaluation"

#### Étape 2 : Créer la Pull Request

1. Allez sur **VOTRE FORK** sur GitHub (dans le navigateur)
   - `https://github.com/VOTRE-NOM/tps-python-initiation`

2. Vous verrez un message jaune en haut :
   ```
   This branch is X commits ahead of [prof]/tps-python-initiation:main
   ```
   Cela signifie : "Vous avez fait X sauvegardes (commits) depuis le fork"

3. Cliquez sur **"Contribute"** → **"Open pull request"**

4. **Page de création de la Pull Request** :

   **a) Vérifiez la direction** :
   - **base repository** : Le repo du prof (à gauche)
   - **head repository** : Votre fork (à droite)
   - ✅ C'est bon si ça va de votre fork → repo du prof

   **b) Titre de la PR** :
   ```
   TP[Numéro] - Votre Nom Prénom
   ```
   Exemples :
   - `TP1 - Jean Dupont`
   - `TP2 - Marie Martin`

   **c) Description** (IMPORTANT !) :
   
   Utilisez ce template :
   ```markdown
   ## 📋 Résumé
   - ✅ Tous les exercices complétés
   - ⏱️ Temps passé : environ X heures
   
   ## 📝 Détails par Exercice
   - **Exercice 1** : Terminé sans problème
   - **Exercice 2** : Terminé, j'ai mis du temps à comprendre les listes
   - **Exercice 3** : Terminé avec aide de la documentation
   - **Exercice 4** : Terminé
   
   ## 🤔 Difficultés Rencontrées
   - J'ai eu du mal avec [concept X]
   - La boucle while était difficile à comprendre au début
   
   ## ❓ Questions pour le Professeur
   - Y a-t-il une meilleure façon de faire l'exercice 5 ?
   - Ma méthode pour l'exercice 3 est-elle optimale ?
   
   ## 💡 Ce que j'ai Appris
   - Manipulation des listes
   - Utilisation des boucles for
   - Importance des commentaires dans le code
   ```

5. Cliquez **"Create pull request"**

6. ✅ **Votre TP est soumis !**

#### Étape 3 : Confirmation

Vous devriez recevoir une notification :
- Par email (si activé dans GitHub)
- Sur GitHub : la PR apparaît dans l'onglet "Pull requests" du repo du prof

**Que se passe-t-il après ?**
- Le professeur reçoit une notification
- Il examine votre code
- Il laisse des commentaires
- Il vous attribue une note
- Il ferme la Pull Request (avec ou sans merge)

---

## ✅ 4. Bonnes Pratiques

### Code de Qualité

#### 1. Nommage des Variables

✅ **Bon** :
```python
nombre_etudiants = 25
moyenne_classe = 14.5
nom_etudiant = "Jean Dupont"
```

❌ **Mauvais** :
```python
n = 25  # Trop court, pas clair
x = 14.5  # Pas descriptif
var1 = "Jean Dupont"  # Nom générique
```

#### 2. Commentaires

✅ **Bon** :
```python
# Calcul de la moyenne des notes
total = sum(notes)
moyenne = total / len(notes)

# Affichage du résultat avec 2 décimales
print(f"Moyenne : {moyenne:.2f}")
```

❌ **Mauvais** :
```python
# calcul
total = sum(notes)  # total
moyenne = total / len(notes)  # moyenne
```

#### 3. Indentation

✅ **Bon** :
```python
if age >= 18:
    print("Majeur")
    peut_voter = True
else:
    print("Mineur")
    peut_voter = False
```

❌ **Mauvais** :
```python
if age >= 18:
print("Majeur")  # Manque l'indentation !
    peut_voter = True
```

#### 4. Espaces

✅ **Bon** :
```python
resultat = a + b
liste = [1, 2, 3, 4, 5]
```

❌ **Mauvais** :
```python
resultat=a+b
liste=[1,2,3,4,5]
```

### Organisation du Travail

#### Planning Recommandé

| Jour | Action | Durée |
|------|--------|-------|
| **Lundi** | Lire l'énoncé du TP | 15 min |
| **Mardi** | Exercices 1-2 | 1h |
| **Mercredi** | Exercices 3-4 | 1h |
| **Jeudi** | Exercice 5-6 | 1h |
| **Vendredi** | Relecture, commentaires | 30 min |
| **Samedi** | Tests, corrections | 30 min |
| **Dimanche** | Soumission (avant 23h59) | 15 min |

#### Méthode Pomodoro

1. ⏰ Travaillez 25 minutes concentré
2. ☕ Pause de 5 minutes
3. 🔁 Répétez 4 fois
4. 🍽️ Grande pause de 15-30 minutes

**Avantage** : Meilleure concentration, moins de fatigue

### Gestion des Commits

#### Fréquence Idéale

- ✅ **Commit toutes les 30 minutes** minimum
- ✅ **Commit après chaque exercice terminé**
- ✅ **Commit avant une grande modification**

#### Messages de Commit Informatifs

✅ **Bons messages** :
```
"Exercice 1 terminé - manipulation de variables"
"Correction bug exercice 3 - problème de boucle"
"Ajout de commentaires détaillés"
"Optimisation exercice 5 - utilisation list comprehension"
"TP2 final - tous exercices validés"
```

❌ **Mauvais messages** :
```
"update"
"fix"
"test"
"zzz"
"final" (sans détails)
```

---

## 🛠️ 5. Résolution de Problèmes

### Problèmes Techniques Courants

#### Problème 1 : "Je ne peux pas sauvegarder dans GitHub depuis Colab"

**Solutions** :
1. Vérifiez que vous êtes connecté à GitHub dans Colab
2. Menu Fichier → Déconnecter de GitHub → Reconnecter
3. Vérifiez que le repository sélectionné est VOTRE fork
4. Essayez en navigation privée

#### Problème 2 : "Mon code ne s'exécute pas"

**Checklist** :
- [ ] Avez-vous exécuté toutes les cellules précédentes ?
- [ ] Y a-t-il des erreurs dans les cellules précédentes ?
- [ ] L'indentation est-elle correcte ?
- [ ] Les parenthèses sont-elles bien fermées ?
- [ ] Avez-vous importé les bibliothèques nécessaires ?

**Méthode de debug** :
```python
# Ajoutez des print() pour voir les valeurs
print("Avant la boucle:", variable)
for i in range(10):
    print("Dans la boucle, i =", i)
print("Après la boucle:", variable)
```

#### Problème 3 : "Erreur : name 'X' is not defined"

**Cause** : Vous utilisez une variable avant de l'avoir définie

**Solution** :
```python
# ❌ Mauvais
print(resultat)
resultat = 5

# ✅ Bon
resultat = 5
print(resultat)
```

#### Problème 4 : "IndentationError"

**Cause** : Mauvaise indentation

**Solution** :
```python
# ❌ Mauvais
if condition:
print("Test")  # Manque l'indentation

# ✅ Bon
if condition:
    print("Test")  # 4 espaces d'indentation
```

#### Problème 5 : "Je ne trouve plus mon travail"

**Solutions** :
1. Vérifiez dans Google Drive → Dossier "Colab Notebooks"
2. Vérifiez sur votre fork GitHub
3. Menu Fichier → Historique des révisions (dans Colab)

### Où Demander de l'Aide ?

#### 1. Aide Automatique

- **Google** : Cherchez l'erreur exacte
- **Stack Overflow** : Questions/réponses programmation
- **Documentation Python** : https://docs.python.org/fr/3/

#### 2. Aide Humaine (Par ordre de priorité)

1. **Camarades de classe** : Entraide entre étudiants (WhatsApp/Discord)
2. **Forum de la classe** : Posez votre question publiquement
3. **Issues GitHub** : Pour problèmes techniques du repo
4. **Email au professeur** : En dernier recours

#### Comment Bien Poser une Question ?

✅ **Bonne question** :
```
Titre : Erreur "list index out of range" dans l'exercice 3 du TP2

Bonjour,

J'ai une erreur que je ne comprends pas dans l'exercice 3 du TP2.

Mon code :
[collez votre code]

L'erreur :
[collez l'erreur complète]

Ce que j'ai essayé :
- J'ai vérifié que ma liste n'était pas vide
- J'ai ajouté des print() pour voir les valeurs

Pouvez-vous m'aider ?

Merci !
```

❌ **Mauvaise question** :
```
Ça marche pas help
```

---

## 📊 6. Évaluation

### Critères de Notation

Chaque TP est noté sur **20 points** :

| Critère | Points | Description |
|---------|--------|-------------|
| **Fonctionnalité** | 8 | Code fonctionne sans erreur |
| **Complétude** | 6 | Tous les exercices traités |
| **Qualité** | 4 | Code propre, commenté, structuré |
| **Compréhension** | 2 | Utilisation correcte des concepts |

#### Détail des Critères

**1. Fonctionnalité (8 points)**
- Toutes les cellules s'exécutent sans erreur : 8/8
- Quelques erreurs mineures : 6/8
- Erreurs importantes : 4/8
- Code ne fonctionne pas : 0-2/8

**2. Complétude (6 points)**
- Tous les exercices faits : 6/6
- 1 exercice manquant : 5/6
- 2 exercices manquants : 4/6
- Plus de 2 manquants : 0-3/6

**3. Qualité (4 points)**
- Code bien indenté : 1 point
- Variables bien nommées : 1 point
- Commentaires pertinents : 1 point
- Structure claire : 1 point

**4. Compréhension (2 points)**
- Utilisation appropriée des concepts : 2/2
- Utilisation partielle : 1/2
- Incompréhension : 0/2

### Bonifications

Vous pouvez gagner des points bonus :

- **+0.5** : Code particulièrement élégant/optimisé
- **+0.5** : Utilisation de concepts non vus en cours (mais corrects)
- **+0.5** : Aide apportée à d'autres étudiants (forum)
- **+1** : Contribution au repo (correction de typos, amélioration doc)

**Maximum** : 2 points de bonus par TP

### Pénalités

- **-1 point/jour** : Retard (maximum 3 jours)
- **-2 points** : Code plagié (première fois) + avertissement
- **0/20** : Code plagié (récidive)
- **-1 point** : PR sans description
- **-0.5** : Aucun commentaire dans le code

### Après la Correction

#### Ce que Vous Recevez

1. **Note** : X/20 avec éventuels bonus/malus
2. **Commentaires** : Directement dans la Pull Request
3. **Suggestions** : Pour améliorer votre code

#### Que Faire Après ?

1. **Lisez les commentaires** attentivement
2. **Comprenez vos erreurs**
3. **Appliquez les conseils** au TP suivant
4. **Posez des questions** si quelque chose n'est pas clair

---

## 🎓 Conseils pour Réussir

### Mindset

1. **Commencez tôt** - Pas de précipitation de dernière minute
2. **Pratiquez régulièrement** - 1h par jour > 7h d'un coup
3. **N'ayez pas peur de l'erreur** - On apprend en se trompant
4. **Demandez de l'aide** - Rapidement, ne restez pas bloqué
5. **Amusez-vous** - La programmation peut être fun !

### Stratégies d'Apprentissage

#### Méthode des 3 Passes

**Passe 1** : Lecture rapide
- Lisez tout le TP en 5-10 minutes
- Identifiez les exercices faciles/difficiles

**Passe 2** : Exercices faciles
- Faites les exercices que vous comprenez
- Gagnez en confiance

**Passe 3** : Exercices difficiles
- Attaquez les plus complexes
- Prenez votre temps
- Cherchez de l'aide si besoin

#### Technique Feynman

1. **Essayez** de faire l'exercice
2. **Expliquez** votre solution à voix haute (même seul)
3. **Identifiez** ce que vous ne comprenez pas bien
4. **Simplifiez** et réexpliquez

Si vous ne pouvez pas expliquer simplement, c'est que vous n'avez pas bien compris.

---

## 📅 Calendrier Récapitulatif

| Date | TP | Deadline | Note |
|------|-----|----------|------|
| Sem. 1 | TP1 - Bases | 15/02/2025 23h59 | /20 |
| Sem. 2 | TP2 - Listes/Boucles | 22/02/2025 23h59 | /20 |
| Sem. 3 | TP3 - Fonctions | 01/03/2025 23h59 | /20 |
| Sem. 4 | TP4 - NumPy | 08/03/2025 23h59 | /20 |
| Sem. 5 | TP5 - Matplotlib | 15/03/2025 23h59 | /20 |
| Sem. 6 | Projet Final | 22/03/2025 23h59 | /30 |

**Note finale** = (TP1 + TP2 + TP3 + TP4 + TP5) × 0.3 + Projet × 0.3 + Participation × 0.1

---

## ✅ Checklist Avant Soumission

Avant de créer votre Pull Request, vérifiez :

- [ ] Tous les exercices sont complétés
- [ ] Tout le code s'exécute sans erreur (testez cellule par cellule)
- [ ] Les résultats sont corrects
- [ ] Le code est bien indenté
- [ ] Les variables ont des noms clairs
- [ ] Le code est commenté
- [ ] J'ai fait plusieurs commits (au moins 3-4)
- [ ] Mes messages de commit sont clairs
- [ ] J'ai rempli la description de la Pull Request
- [ ] J'ai relu mon code une dernière fois

---

## 🆘 Contact Urgence

**En cas de problème technique majeur :**

1. **Email** : [email.prof@universite.fr]
2. **Objet** : "URGENT - TP[X] - [Votre nom]"
3. **Contenu** : Décrivez le problème avec captures d'écran

**Le professeur s'engage à répondre dans les 24h.**

---

<div align="center">

## 🎯 Vous avez tout lu ? Bravo !

**Vous êtes prêt(e) à réussir vos TPs Python ! 💪🐍**

**En cas de doute, relisez ce document. Tout y est ! 📖**

---

**Dernière mise à jour** : [Date]  
**Version** : 1.0

</div>
