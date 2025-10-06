# Libft - 42 School Project

## 📋 Description
**Libft** est un projet fondamental du tronc commun à 42, consistant en la réimplémentation de fonctions standards de la librairie C ainsi que des fonctions utilitaires supplémentaires. Ce projet permet d'approfondir la compréhension des mécanismes bas niveau en C et de construire une bibliothèque personnelle réutilisable dans les projets futurs.

## 🎯 Objectifs
- Comprendre le fonctionnement des fonctions standards de la librairie C
- Maîtriser la manipulation de mémoire et de chaînes de caractères
- Développer une bibliothèque réutilisable et optimisée
- Appliquer les bonnes pratiques de programmation en C

## 📁 Structure du Projet
libft/
├── srcs/ # Sources des fonctions
├── includes/ # Fichier d'en-tête libft.h
├── Makefile # Système de compilation
└── README.md # Documentation

text

## 🛠️ Fonctions Implémentées

### 🔤 Partie 1 - Fonctions Libc
- **Vérification de caractères** : `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`
- **Manipulation de chaînes** : `ft_strlen`, `ft_strlcpy`, `ft_strlcat`, `ft_strchr`, `ft_strrchr`, `ft_strnstr`, `ft_strncmp`
- **Manipulation mémoire** : `ft_memset`, `ft_memcpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`, `ft_bzero`
- **Conversion** : `ft_atoi`, `ft_toupper`, `ft_tolower`
- **Allocation mémoire** : `ft_calloc`, `ft_strdup`

### 📝 Partie 2 - Fonctions Supplémentaires
- **Manipulation de chaînes avancée** : `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`, `ft_strmapi`
- **Gestion de sortie** : `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`
- **Fonctions utilitaires** : `ft_itoa`, `ft_striteri`

### 🎁 Bonus
- **Gestion de listes chaînées** :
  - `ft_lstnew`, `ft_lstadd_front`, `ft_lstsize`, `ft_lstlast`
  - `ft_lstadd_back`, `ft_lstdelone`, `ft_lstclear`, `ft_lstiter`, `ft_lstmap`

## 🚀 Installation et Utilisation
```bash
git clone [URL-du-repository]
cd libft
make
c
#include "libft.h"
// Compiler avec : -L. -lft
📊 Compilation
Le Makefile supporte les règles suivantes :

make - Compile la bibliothèque

make clean - Supprime les fichiers objets

make fclean - Supprime les fichiers objets et la bibliothèque

make re - Recompile entièrement le projet

💡 Compétences Développées
Algorithmie et structures de données

Gestion manuelle de la mémoire

Optimisation du code

Création de systèmes de build

Programmation modulaire

Ce projet sert de fondation pour les développements ultérieurs dans le cursus 42, fournissant un ensemble d'outils essentiels pour la manipulation de données en C.

text
un seul fchier
markdown
# Libft - 42 School Project

## 📋 Description
Libft est un projet fondamental du tronc commun à 42, consistant en la réimplémentation de fonctions standards de la librairie C ainsi que des fonctions utilitaires supplémentaires. Ce projet permet d'approfondir la compréhension des mécanismes bas niveau en C et de construire une bibliothèque personnelle réutilisable dans les projets futurs.

## 🎯 Objectifs
- Comprendre le fonctionnement des fonctions standards de la librairie C
- Maîtriser la manipulation de mémoire et de chaînes de caractères
- Développer une bibliothèque réutilisable et optimisée
- Appliquer les bonnes pratiques de programmation en C

## 🛠️ Fonctions Implémentées

### 🔤 Partie 1 - Fonctions Libc
**Vérification de caractères** : ft_isalpha, ft_isdigit, ft_isalnum, ft_isascii, ft_isprint  
**Manipulation de chaînes** : ft_strlen, ft_strlcpy, ft_strlcat, ft_strchr, ft_strrchr, ft_strnstr, ft_strncmp  
**Manipulation mémoire** : ft_memset, ft_memcpy, ft_memmove, ft_memchr, ft_memcmp, ft_bzero  
**Conversion** : ft_atoi, ft_toupper, ft_tolower  
**Allocation mémoire** : ft_calloc, ft_strdup

### 📝 Partie 2 - Fonctions Supplémentaires
**Manipulation de chaînes avancée** : ft_substr, ft_strjoin, ft_strtrim, ft_split, ft_strmapi  
**Gestion de sortie** : ft_putchar_fd, ft_putstr_fd, ft_putendl_fd, ft_putnbr_fd  
**Fonctions utilitaires** : ft_itoa, ft_striteri

### 🎁 Bonus
**Gestion de listes chaînées** : ft_lstnew, ft_lstadd_front, ft_lstsize, ft_lstlast, ft_lstadd_back, ft_lstdelone, ft_lstclear, ft_lstiter, ft_lstmap

## 🚀 Installation et Utilisation
```bash
git clone [URL-du-repository]
cd libft
make
c
#include "libft.h"
// Compiler avec : -L. -lft
📊 Compilation
Le Makefile supporte les règles suivantes :

make - Compile la bibliothèque

make clean - Supprime les fichiers objets

make fclean - Supprime les fichiers objets et la bibliothèque

make re - Recompile entièrement le projet

💡 Compétences Développées
Algorithmie et structures de données

Gestion manuelle de la mémoire

Optimisation du code

Création de systèmes de build

Programmation modulaire

Ce projet sert de fondation pour les développements ultérieurs dans le cursus 42, fournissant un ensemble d'outils essentiels pour la manipulation de données en C.
