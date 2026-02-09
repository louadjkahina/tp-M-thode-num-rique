# 📘 Semaine 1 : Les Bases de Python

## 🎯 Objectifs de la Semaine

À la fin de ce TP, vous serez capable de :

- ✅ Comprendre et utiliser les variables en Python
- ✅ Connaître les types de données de base (`int`, `float`, `str`, `bool`)
- ✅ Effectuer des opérations mathématiques
- ✅ Manipuler des chaînes de caractères
- ✅ Utiliser les fonctions `print()`, `type()`, `len()`
- ✅ Formater des sorties avec f-strings

---

## 📚 Prérequis

- ✅ Compte GitHub créé
- ✅ Fork du repository effectué
- ✅ Google Colab accessible
- ❌ **Aucune connaissance en programmation requise** - on part de zéro !

---

## 📂 Contenu de cette Semaine

### Fichiers

- **TP1_bases_python.ipynb** : Notebook à compléter (exercices 1-2)
- **exemples/** : Dossier avec des exemples de code
  - `exemple_variables.py` : Exemples de déclaration de variables
  - `exemple_operations.py` : Exemples d'opérations mathématiques
  - `exemple_strings.py` : Exemples de manipulation de chaînes

---

## 🗓️ Planning Recommandé

| Jour | Activité | Durée estimée |
|------|----------|---------------|
| **Lundi** | Lire l'énoncé + regarder vidéo | 30 min |
| **Mardi** | Exercice 1 - Variables et types | 1h |
| **Mercredi** | Exercice 2 - Chaînes de caractères | 1h |
| **Jeudi-Vendredi** | Relecture, tests, commentaires | 30 min |
| **Samedi** | Buffer (si besoin de plus de temps) | - |
| **Dimanche** | Soumission (avant 23h59) | 15 min |

**Durée totale estimée** : 3 heures

---

## 📖 Concepts Abordés

### 1. Variables et Affectation

Une **variable** est comme une boîte qui contient une valeur.

```python
# Créer une variable
age = 25

# Modifier une variable
age = 26

# Utiliser une variable
print(age)  # Affiche : 26
```

**Règles de nommage** :
- ✅ Commencer par une lettre ou `_`
- ✅ Contenir lettres, chiffres, `_`
- ❌ Pas d'espaces
- ❌ Pas de caractères spéciaux (@, #, !, etc.)

**Exemples** :
```python
# ✅ Bon
nom_etudiant = "Jean"
age_2024 = 20
_variable = 10

# ❌ Mauvais
2eme_note = 15  # Commence par un chiffre
nom-etudiant = "Jean"  # Contient un tiret
mon age = 20  # Contient un espace
```

### 2. Types de Données

Python a plusieurs types de base :

| Type | Description | Exemple |
|------|-------------|---------|
| `int` | Nombre entier | `42`, `-17`, `0` |
| `float` | Nombre décimal | `3.14`, `-0.5`, `2.0` |
| `str` | Chaîne de caractères | `"Bonjour"`, `'Python'` |
| `bool` | Booléen (vrai/faux) | `True`, `False` |

```python
# Exemples
age = 25                    # int
taille = 1.75              # float
prenom = "Alice"           # str
est_etudiant = True        # bool

# Connaître le type
print(type(age))           # <class 'int'>
print(type(taille))        # <class 'float'>
print(type(prenom))        # <class 'str'>
print(type(est_etudiant))  # <class 'bool'>
```

### 3. Opérations Mathématiques

Python peut faire des calculs comme une calculatrice :

| Opération | Symbole | Exemple | Résultat |
|-----------|---------|---------|----------|
| Addition | `+` | `5 + 3` | `8` |
| Soustraction | `-` | `5 - 3` | `2` |
| Multiplication | `*` | `5 * 3` | `15` |
| Division | `/` | `5 / 2` | `2.5` |
| Division entière | `//` | `5 // 2` | `2` |
| Reste (modulo) | `%` | `5 % 2` | `1` |
| Puissance | `**` | `5 ** 2` | `25` |

```python
a = 10
b = 3

print(a + b)   # 13
print(a - b)   # 7
print(a * b)   # 30
print(a / b)   # 3.333...
print(a // b)  # 3
print(a % b)   # 1
print(a ** b)  # 1000
```

### 4. Chaînes de Caractères (Strings)

Une **chaîne** est du texte entre guillemets.

```python
# Création
prenom = "Alice"
nom = 'Dupont'  # Guillemets simples ou doubles

# Concaténation (assembler)
nom_complet = prenom + " " + nom
print(nom_complet)  # Alice Dupont

# Longueur
print(len(prenom))  # 5

# Méthodes utiles
print(prenom.upper())     # ALICE
print(prenom.lower())     # alice
print(prenom.capitalize()) # Alice
print(prenom.replace("A", "E"))  # Elice
```

### 5. Formatage avec f-strings

Les **f-strings** permettent d'insérer des variables dans du texte :

```python
nom = "Alice"
age = 25
taille = 1.65

# Ancienne méthode (à éviter)
phrase = "Je m'appelle " + nom + " et j'ai " + str(age) + " ans."

# ✅ Méthode moderne : f-string
phrase = f"Je m'appelle {nom} et j'ai {age} ans."
print(phrase)
# Je m'appelle Alice et j'ai 25 ans.

# Avec formatage
phrase = f"Je mesure {taille:.2f} mètres."
print(phrase)
# Je mesure 1.65 mètres.
```

---

## 💻 Exercices

### Exercice 1 : Variables et Types

**Objectif** : Créer des variables et afficher leurs types

**Consignes** :
1. Créez les variables suivantes :
   - `prenom` : votre prénom (str)
   - `age` : votre âge (int)
   - `taille` : votre taille en mètres (float)
   - `est_etudiant` : True (bool)

2. Affichez chaque variable avec son type

**Résultat attendu** :
```
Alice est de type <class 'str'>
25 est de type <class 'int'>
1.65 est de type <class 'float'>
True est de type <class 'bool'>
```

### Exercice 2 : Opérations Mathématiques

**Objectif** : Effectuer des calculs

**Consignes** :
1. Créez deux variables : `a = 10` et `b = 3`
2. Calculez et affichez :
   - La somme
   - La différence
   - Le produit
   - La division
   - La division entière
   - Le reste
   - a à la puissance b

**Résultat attendu** :
```
Somme : 13
Différence : 7
Produit : 30
Division : 3.3333...
Division entière : 3
Reste : 1
Puissance : 1000
```

---

## 🎬 Démonstration (Séance en Présentiel)

Pendant la séance, nous verrons ensemble :

### Partie 1 : Premier Programme (15 min)

```python
# Notre premier programme Python !
print("Bonjour le monde !")
print("Je suis en train d'apprendre Python")
```

### Partie 2 : Variables (20 min)

```python
# Créer des variables
nom = "Alice"
age = 20

# Les utiliser
print(nom)
print(age)

# Modifier une variable
age = 21
print(age)
```

### Partie 3 : Calculs (15 min)

```python
# Python comme calculatrice
resultat = 5 + 3
print(resultat)

# Avec des variables
prix_unitaire = 10
quantite = 5
total = prix_unitaire * quantite
print(f"Total : {total} euros")
```

### Partie 4 : Strings (15 min)

```python
prenom = "Jean"
nom = "Dupont"

# Concaténation
nom_complet = prenom + " " + nom
print(nom_complet)

# f-string
message = f"Bonjour {prenom} {nom} !"
print(message)
```

---

## 🎯 Compétences Validées

À la fin du TP1, vous devez pouvoir :

- [ ] Créer des variables de différents types
- [ ] Afficher des valeurs avec `print()`
- [ ] Utiliser `type()` pour vérifier un type
- [ ] Faire des calculs mathématiques de base
- [ ] Assembler des chaînes de caractères
- [ ] Utiliser des f-strings pour formater du texte
- [ ] Comprendre les messages d'erreur de base

---

## 📝 Notes Importantes

### Erreurs Courantes

#### Erreur 1 : NameError

```python
print(resultat)
resultat = 10
```
**Erreur** : `NameError: name 'resultat' is not defined`

**Solution** : Définir la variable AVANT de l'utiliser
```python
resultat = 10
print(resultat)
```

#### Erreur 2 : TypeError

```python
age = 25
message = "J'ai " + age + " ans"
```
**Erreur** : `TypeError: can only concatenate str (not "int") to str`

**Solution** : Convertir ou utiliser f-string
```python
# Solution 1 : conversion
message = "J'ai " + str(age) + " ans"

# Solution 2 : f-string (meilleur)
message = f"J'ai {age} ans"
```

#### Erreur 3 : IndentationError

```python
age = 25
    print(age)
```
**Erreur** : `IndentationError: unexpected indent`

**Solution** : Pas d'indentation inutile au début
```python
age = 25
print(age)
```

### Conseils

1. **Testez chaque cellule** avant de passer à la suivante
2. **Lisez les erreurs** - elles vous disent souvent ce qui ne va pas
3. **Utilisez des noms de variables descriptifs** - `age` plutôt que `a`
4. **Commentez votre code** - expliquez ce que vous faites
5. **Sauvegardez régulièrement** dans GitHub

---

## 🔗 Ressources Complémentaires

### Documentation

- [Python Docs - Types de base](https://docs.python.org/fr/3/library/stdtypes.html)
- [W3Schools - Variables](https://www.w3schools.com/python/python_variables.asp)
- [Real Python - f-strings](https://realpython.com/python-f-strings/)

### Vidéos (optionnel)

- "Python pour débutants - Variables" (YouTube)
- "Comprendre les types en Python" (YouTube)

### Exercices Supplémentaires

Si vous terminez tôt, essayez :

1. **Convertisseur de température**
   - Créez une variable `celsius = 25`
   - Convertissez en Fahrenheit : `F = C × 9/5 + 32`
   - Affichez : "25°C = 77.0°F"

2. **Calculateur d'IMC**
   - Créez `poids = 70` (kg) et `taille = 1.75` (m)
   - Calculez IMC : `IMC = poids / taille²`
   - Affichez le résultat

3. **Formateur de nom**
   - Créez `prenom = "jean"` et `nom = "dupont"`
   - Affichez "DUPONT Jean" (nom en majuscules)

---

## ✅ Auto-Évaluation

Avant de soumettre, vérifiez :

- [ ] J'ai créé toutes les variables demandées
- [ ] J'ai utilisé les bons types (int, float, str, bool)
- [ ] Tous mes calculs sont corrects
- [ ] J'ai utilisé des f-strings
- [ ] Mon code est commenté
- [ ] Tout s'exécute sans erreur
- [ ] J'ai fait plusieurs commits
- [ ] Mes messages de commit sont clairs

**Score personnel** : ____ / 8 critères validés

---

## 📤 Soumission

**Deadline** : Dimanche 15/02/2025 à 23h59

**Comment soumettre** :
1. Finalisez votre notebook
2. Dernière sauvegarde dans GitHub
3. Créez une Pull Request (voir [INSTRUCTIONS.md](../INSTRUCTIONS.md))
4. Remplissez la description de la PR

**N'oubliez pas** : Plus vous commencez tôt, moins vous serez stressé !

---

## 🎓 Prochaine Semaine

**Semaine 2 : Listes et Boucles**

Vous apprendrez à :
- Stocker plusieurs valeurs dans des listes
- Parcourir des données avec des boucles
- Manipuler des collections

**Préparez-vous** : Relisez ce TP1, les concepts de base seront utilisés !

---

## 📞 Besoin d'Aide ?

- **Forum de la classe** : Posez vos questions
- **Email** : [prof@universite.fr]
- **Heures de permanence** : Mardi 14h-16h

---

<div align="center">

**Bon courage pour votre premier TP Python ! 🐍💪**

**N'oubliez pas : Tout le monde a commencé par le début. Vous allez y arriver ! 🚀**

</div>
