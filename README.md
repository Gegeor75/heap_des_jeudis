# Heap des jeudis

**Programme d’apprentissage du C**

Une séance hebdo en peer learning avec des niveaux hétérogènes, c'est exactement le format de la piscine : on va donc en faire une force. Le planning repose sur trois niveaux (N1 débutant, N2 a déjà codé, N3 connaît déjà un peu le C), un tronc commun, et une séance dont la structure reste la même chaque semaine.

Format de la séance hebdo (2h)

1. Tour de table : chacun montre une fonction qui a posé problème. (15mn)

2. Binômes mixtes (N3 avec N1, N2 avec N2) : correction croisée à la norme 42, sans donner la solution, en posant des questions. (45mn)

3. Défi commun chronométré, le même sujet pour tous mais avec des bonus par niveau. (45mn)

4. N3 présente un concept de la semaine suivante aux autres (expliquer = consolider). (15mn)

Les binômes tournent chaque semaine. Entre les séances, chacun avance seul sur son palier et peut passer au suivant dès que je valide ses exos.

Semaine 1 — Terminal, Git, compiler
Tronc commun : shell,
`gcc -Wall -Wextra -Werror`,
premier commit,
lecture de la Norme.

N1 : écrire et compiler `ft_putchar`.
N2 : `ft_print_alphabet`, `ft_print_numbers`. N3 : configurer un dépôt partagé pour le groupe + script de vérification de norme.
Défi commun : afficher l'alphabet à l'envers.

Semaine 2 — Conditions et boucles
Commun : `if`, `while`, ASCII, `write`.
N1 : `ft_is_negative`, `ft_print_comb`.
N2 : `ft_print_comb2`.
N3 : `ft_putnbr` avec `INT_MIN`.
Défi : `ft_print_comb` en 25 lignes maximum par fonction.

Semaine 3 — Pointeurs
Commun : schéma mémoire sur papier, `&`, `*`.
N1 : `ft_ft`, `ft_swap`.
N2 : `ft_div_mod`, `ft_ultimate_div_mod`.
N3 : `ft_rev_int_tab`, `ft_sort_int_tab`.
Défi : expliquer à son binôme pourquoi `ft_swap` ne marche pas sans pointeurs, puis la coder.

Semaine 4 — Chaînes
Commun : `\0`, parcours de chaîne.
N1 : `ft_strlen`, `ft_putstr`.
N2 : `ft_strcpy`, `ft_strcmp`, `ft_strupcase`.
N3 : `ft_strncat`, `ft_strlcpy`, `ft_strstr`.
Défi : `ft_strcmp` testée avec les cas limites (chaîne vide, chaînes égales, préfixe).

Semaine 5 — Mémoire dynamique
Commun : `malloc`/`free`, détection de fuites.
N1 : `ft_strdup`.
N2 : `ft_range`, `ft_ultimate_range`.
N3 : `ft_split`, `ft_strjoin`.
Défi : `ft_strdup` sans aucune fuite, vérifié par le binôme avec Valgrind.

Semaine 6 — Compilation, structures, argv
Commun : Makefile, fichiers `.h`.
N1 : `ft_print_params`.
N2 : `ft_rev_params`, `ft_sort_params`.
N3 : structures + pointeurs sur fonctions (`ft_foreach`, `ft_map`).
Défi : construire ensemble une petite librairie avec son Makefile, chacun y contribue une fonction.

Semaine 7 — Récursivité, bases, listes
Commun : principe de récursion, cas d'arrêt.
N1 : `ft_factorial`, `ft_power`.
N2 : `ft_atoi`, `ft_putnbr_base`.
N3 : `ft_atoi_base`, listes chaînées (`ft_create_elem`, `ft_list_push_front`).
Défi : `ft_fibonacci` récursive, puis comparer avec la version itérative de son binôme.

Semaine 8 — Rush collectif
Tout le groupe en équipes de 2-3 mixtes sur `Rush00` (rectangles ASCII) ou `Rush01` (Sudoku). Correction par une autre équipe selon la grille officielle. Debrief : ce qui a bloqué, comment on lit un sujet, gestion du temps.

Pourquoi c'est évolutif
Chaque palier est une porte, pas un plafond : un N1 qui finit vite passe aux exos N2 la même semaine. Le N3 n'est jamais inactif, il a toujours un exo avancé et un rôle d'explicateur. Et les défis communs garantissent que personne ne décroche du rythme du groupe.
