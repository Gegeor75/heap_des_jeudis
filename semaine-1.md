# Semaine 1 – Terminal, Git et compilation en C

**Programme de formation**  
**Niveau :** Débutant  
**Date :** Jeudi 19 novembre 2026  
**Durée :** Environ 3 heures

---

## 1. Présentation de la semaine

**Thème : Terminal, Git et compilation**

- **Tronc commun :** Shell, `gcc -Wall -Wextra -Werror`, premier commit et lecture de la Norme 42.
- **N1 :** Écrire et compiler `ft_putchar`.
- **N2 :** Écrire `ft_print_alphabet` et `ft_print_numbers`.
- **N3 :** Configurer un dépôt partagé pour le groupe et créer un script de vérification de la Norme.
- **Défi commun :** Afficher l'alphabet à l'envers.

### Objectif général

L'objectif de cette première semaine est de mettre en place un environnement de travail propre, de maîtriser les premières commandes indispensables et de commencer à programmer en C dans des conditions proches de la Piscine 42.

Le fonctionnement de la formation sera le suivant :

**Cours → Démonstrations → Exercices pratiques → Validation → Défi final**

---

## 2. Objectifs de la semaine

À la fin de cette session, tu dois être capable de :

- Utiliser le Terminal pour naviguer dans les répertoires et manipuler des fichiers.
- Créer et organiser un projet C.
- Compiler un programme avec `cc -Wall -Wextra -Werror`.
- Comprendre les premières commandes Git et effectuer un commit.
- Comprendre les principales règles de la Norme 42.
- Écrire et compiler trois fonctions simples en C.

---

## 3. Déroulement de la session

### Bloc 1 – Terminal Unix

**Durée : 30 minutes**

Commandes à maîtriser :

| Commande | Fonction                                           |
| -------- | -------------------------------------------------- |
| `pwd`    | Afficher le répertoire courant                     |
| `ls -la` | Lister les fichiers, y compris les fichiers cachés |
| `cd`     | Changer de répertoire                              |
| `mkdir`  | Créer un dossier                                   |
| `touch`  | Créer un fichier                                   |
| `cat`    | Afficher le contenu d'un fichier                   |
| `cp`     | Copier un fichier                                  |
| `mv`     | Déplacer ou renommer un fichier                    |
| `rm`     | Supprimer un fichier                               |
| `find`   | Rechercher des fichiers                            |

### Bloc 2 – Compilation C

**Durée : 30 minutes**

Comprendre :

- Le rôle du compilateur `cc` (ou GCC).
- Les options `-Wall`, `-Wextra` et `-Werror`.
- La différence entre un fichier `.c` et un exécutable.
- Les erreurs de compilation et les warnings.

**Commande de référence :**

```bash
cc -Wall -Wextra -Werror main.c -o programme
```

### Bloc 3 – Git et premier commit

**Durée : 30 minutes**

Commandes à connaître :

```bash
git init
git status
git add .
git commit -m "Initial commit"
git log
```

Comprendre le fonctionnement :

- Du dépôt local.
- De l'index (staging area).
- Des commits.
- De l'historique des modifications.

### Bloc 4 – La Norme 42

**Durée : 20 minutes**

Points essentiels :

- Indentation avec des tabulations.
- Limitation de la longueur des lignes.
- Déclaration des variables.
- Respect des prototypes.
- Organisation des fonctions.
- Utilisation des fonctions autorisées.

### Bloc 5 – Programmation

**Durée : 60 minutes**

Trois exercices progressifs :

- **N1 :** `ft_putchar`
- **N2 :** `ft_print_alphabet`
- **N2 :** `ft_print_numbers`

### Bloc 6 – Défi commun

**Durée : 15 minutes**

Afficher l'alphabet à l'envers, de `z` à `a`.

---

## 4. Exercices de programmation

Nous allons appliquer une règle importante :

> Je te donne les consignes, tu écris ton code, puis tu me le soumets pour correction. Je ne donne pas la solution immédiatement.

### N1 – Exercice 1 : `ft_putchar`

**Objectif :** créer une fonction qui affiche un caractère.

**Prototype imposé :**

```c
void ft_putchar(char c);
```

**Contraintes :**

- Utiliser uniquement `write`.
- Ne pas utiliser `printf`.
- Respecter le prototype.
- Compiler sans aucune erreur ni aucun warning.

**Résultat attendu pour un appel avec `'A'` :**

```text
A
```

### N2 – Exercice 2 : `ft_print_alphabet`

**Objectif :** afficher l'alphabet en minuscules, dans l'ordre alphabétique.

**Prototype :**

```c
void ft_print_alphabet(void);
```

**Résultat attendu :**

```text
abcdefghijklmnopqrstuvwxyz
```

**Contraintes :**

- Utiliser `write`.
- Utiliser une boucle `while`.
- Ne pas utiliser de tableau de caractères.
- Ne pas utiliser `printf`.

### N2 – Exercice 3 : `ft_print_numbers`

**Objectif :** afficher les chiffres de 0 à 9.

**Prototype :**

```c
void ft_print_numbers(void);
```

**Résultat attendu :**

```text
0123456789
```

**Contraintes :**

Identiques à l'exercice précédent.

### Défi commun – Alphabet inversé

**Challenge :** créer une fonction qui affiche l'alphabet dans l'ordre inverse.

**Prototype :**

```c
void ft_print_reverse_alphabet(void);
```

**Résultat attendu :**

```text
zyxwvutsrqponmlkjihgfedcba
```

---

## 5. Organisation du projet

Je te conseille de créer cette arborescence sur ton Mac :

```text
semaine_01/
│
├── ex00/
│   └── ft_putchar.c
│
├── ex01/
│   └── ft_print_alphabet.c
│
├── ex02/
│   └── ft_print_numbers.c
│
├── ex03/
│   └── ft_print_reverse_alphabet.c
│
├── main.c
└── README.md
```

**Règles d'organisation :**

- Chaque exercice devra pouvoir être compilé et testé indépendamment.
- Chaque fonction devra respecter son prototype.
- Le code devra respecter la Norme 42.
- Les fichiers devront être versionnés avec Git.

---

## 6. Validation de la semaine

Voici les critères que nous utiliserons pour valider ton travail.

### Checklist de progression – 0/10

- [ ] Naviguer dans le Terminal sans assistance.
- [ ] Créer l'arborescence du projet.
- [ ] Compiler avec `-Wall -Wextra -Werror`.
- [ ] Initialiser un dépôt Git.
- [ ] Effectuer un premier commit.
- [ ] Comprendre les règles essentielles de la Norme 42.
- [ ] Coder et compiler `ft_putchar`.
- [ ] Coder et compiler `ft_print_alphabet`.
- [ ] Coder et compiler `ft_print_numbers`.
- [ ] Réussir le défi de l'alphabet inversé.

---

## 7. Bilan de la semaine

À la fin de la session, nous ferons un bilan portant sur :

1. Les commandes Terminal maîtrisées.
2. La compréhension de la compilation C.
3. L'utilisation de Git.
4. Le respect de la Norme 42.
5. L'autonomie dans la réalisation des exercices.

**Critère de réussite :** les quatre fonctions doivent être écrites, compilées et validées sans erreur ni warning.

**Prochaine étape :** passer à la semaine 2 avec de nouveaux exercices de programmation C et une difficulté progressive.
