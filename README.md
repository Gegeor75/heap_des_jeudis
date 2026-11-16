# Heap des jeudis
## Programme d’apprentissage du C

Une séance hebdomadaire en **peer learning**, avec des niveaux hétérogènes : c'est exactement le format de la piscine. Nous allons donc en faire une force !

Le planning repose sur :
- **Trois niveaux** :
  - N1 : débutant
  - N2 : a déjà codé
  - N3 : connaît déjà un peu le C
- Un **tronc commun** pour tous les participants.
- Une séance dont la structure reste identique chaque semaine.

---

## 1. Format de la séance hebdomadaire (2h)

| Étape | Activité | Durée |
|---|---|---:|
| 1 | **Tour de table :** chacun présente une fonction qui lui a posé problème. | 15 min |
| 2 | **Binômes mixtes :** N3 avec N1, N2 avec N2. Correction croisée à la norme 42, sans donner la solution, mais en posant des questions. | 45 min |
| 3 | **Défi commun chronométré :** même sujet pour tous, avec des bonus selon le niveau. | 45 min |
| 4 | **Transmission :** un N3 présente un concept de la semaine suivante aux autres (expliquer, c'est consolider). | 15 min |

**Organisation entre les séances :**
- Les binômes tournent chaque semaine.
- Entre les séances, chacun avance seul sur son palier.
- Chaque participant peut passer au niveau suivant dès validation de ses exercices.

---

## 2. Programme pédagogique sur 8 semaines

### Semaine 1 — Terminal, Git et compilation

**Tronc commun :**
- Shell
- Compilation : `gcc -Wall -Wextra -Werror`
- Premier commit Git
- Lecture de la Norme 42

**Exercices par niveau :**

| Niveau | Exercices |
|---|---|
| N1 | Écrire et compiler `ft_putchar` |
| N2 | `ft_print_alphabet`, `ft_print_numbers` |
| N3 | Configurer un dépôt partagé pour le groupe et créer un script de vérification de norme |

**Défi commun :** afficher l'alphabet à l'envers.

---

### Semaine 2 — Conditions et boucles

**Tronc commun :**
- `if`
- `while`
- ASCII
- `write`

**Exercices par niveau :**

| Niveau | Exercices |
|---|---|
| N1 | `ft_is_negative`, `ft_print_comb` |
| N2 | `ft_print_comb2` |
| N3 | `ft_putnbr` avec `INT_MIN` |

**Défi commun :** réaliser `ft_print_comb` en 25 lignes maximum par fonction.

---

### Semaine 3 — Pointeurs

**Tronc commun :**
- Schéma mémoire sur papier
- Opérateur `&`
- Opérateur `*`

**Exercices par niveau :**

| Niveau | Exercices |
|---|---|
| N1 | `ft_ft`, `ft_swap` |
| N2 | `ft_div_mod`, `ft_ultimate_div_mod` |
| N3 | `ft_rev_int_tab`, `ft_sort_int_tab` |

**Défi commun :** expliquer à son binôme pourquoi `ft_swap` ne fonctionne pas sans pointeurs, puis coder la fonction.

---

### Semaine 4 — Chaînes de caractères

**Tronc commun :**
- Caractère de fin de chaîne `\0`
- Parcours de chaîne

**Exercices par niveau :**

| Niveau | Exercices |
|---|---|
| N1 | `ft_strlen`, `ft_putstr` |
| N2 | `ft_strcpy`, `ft_strcmp`, `ft_strupcase` |
| N3 | `ft_strncat`, `ft_strlcpy`, `ft_strstr` |

**Défi commun :** tester `ft_strcmp` avec les cas limites :
- Chaîne vide
- Chaînes identiques
- Chaîne préfixe d'une autre

---

### Semaine 5 — Mémoire dynamique

**Tronc commun :**
- `malloc` et `free`
- Détection des fuites mémoire

**Exercices par niveau :**

| Niveau | Exercices |
|---|---|
| N1 | `ft_strdup` |
| N2 | `ft_range`, `ft_ultimate_range` |
| N3 | `ft_split`, `ft_strjoin` |

**Défi commun :** réaliser `ft_strdup` sans aucune fuite mémoire, avec vérification par le binôme à l'aide de Valgrind.

---

### Semaine 6 — Compilation, structures et argv

**Tronc commun :**
- Makefile
- Fichiers `.h`

**Exercices par niveau :**

| Niveau | Exercices |
|---|---|
| N1 | `ft_print_params` |
| N2 | `ft_rev_params`, `ft_sort_params` |
| N3 | Structures et pointeurs sur fonctions : `ft_foreach`, `ft_map` |

**Défi commun :** construire ensemble une petite bibliothèque avec son Makefile. Chaque participant contribue avec une fonction.

---

### Semaine 7 — Récursivité, bases et listes chaînées

**Tronc commun :**
- Principe de récursivité
- Cas d'arrêt

**Exercices par niveau :**

| Niveau | Exercices |
|---|---|
| N1 | `ft_factorial`, `ft_power` |
| N2 | `ft_atoi`, `ft_putnbr_base` |
| N3 | `ft_atoi_base`, listes chaînées : `ft_create_elem`, `ft_list_push_front` |

**Défi commun :** coder `ft_fibonacci` en version récursive, puis comparer avec la version itérative réalisée par son binôme.

---

### Semaine 8 — Rush collectif

**Organisation :**

Tout le groupe travaille en équipes de 2 à 3 personnes, avec des niveaux mixtes.

**Sujets possibles :**
- `Rush00` : rectangles ASCII
- `Rush01` : Sudoku

**Correction :**
- Chaque équipe fait corriger son travail par une autre équipe.
- Utilisation de la grille officielle de correction.

**Débrief collectif :**
- Qu'est-ce qui a bloqué ?
- Comment mieux lire et comprendre un sujet ?
- Comment améliorer la gestion du temps ?

---

## 3. Pourquoi ce programme est évolutif ?

Chaque palier est une **porte, pas un plafond**.

- Un participant N1 qui termine rapidement ses exercices peut passer aux exercices N2 dès la même semaine.
- Le N3 n'est jamais inactif : il dispose toujours d'un exercice avancé et joue également un rôle d'explicateur.
- Les défis communs permettent de maintenir une dynamique collective et garantissent que personne ne décroche du rythme du groupe.

**L'objectif : progresser individuellement tout en apprenant collectivement.**
