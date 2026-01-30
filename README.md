# Password-generator

**English**

# Advanced Password Generator with Graphical Interface
## Project Overview

This project is an advanced password generator developed in Python, featuring a graphical interface (Tkinter) that allows easy creation of:
highly robust random passwords (with configurable constraints),
automatically generated complex phrases combining readability and security,
automatic analysis of the generated password strength.

This project was designed as part of cybersecurity awareness, aiming to promote good password management practices that are essential for both users and organizations.

## Objectives and Purpose

This generator addresses several key challenges:

### ✔ 1. Creating strong passwords

It integrates a cryptographic engine based on the secrets module, ensuring secure and non-predictable password generation.

### ✔ 2. Creating a memorable "complex phrase"

Passwords generated using this mode combine: \
- random word assembly, \
- transformations (leet, alternating uppercase/lowercase), \
- added entropy through hashing, \
- injection of numbers and special characters.

➡ This mode provides a password that is robust, unique, and easier to remember than a purely random string.

### ✔ 3. Promoting cybersecurity best practices

This project technically illustrates several essential recommendations: \
- Use a different password for each service
This reduces risks in case of data leaks or service compromise. \
- Choose long and complex passwords
A strong password combines length, character diversity, and unpredictability. \
- Avoid repetitive or personal patterns
No birthdates, names, pets, etc. \
- Rely on a password manager
Humans are not designed to remember 50 complex passwords.

Password managers such as Bitwarden, KeePass, Dashlane, etc. allow users to: \
- store unique passwords, \
- avoid password reuse, \
- easily use long and complex passwords. \

➡ This project demonstrates concretely how to generate such passwords.

## Why are strong passwords essential?

In more than 80% of cybersecurity incidents (source: Verizon DBIR),
weak, reused, or compromised passwords play a direct role.

An attacker may exploit: \
- credential stuffing (automatically testing stolen credentials on other sites), \
- brute force attacks, \
- cracking via hashed databases, \
- social engineering, \
- dictionary attacks. 

A strong password: \
- exponentially increases the time required to crack it, \
- prevents exploitation of passwords already leaked elsewhere, \
- significantly reduces the overall attack surface of a user or organization. \

## Program Features
Graphical Interface (Tkinter)

No command line required → simple and intuitive usage.

“Classic” Mode

Generates a password that meets the following constraints: \
- total length, \
- number of uppercase letters, \
- number of lowercase letters, \
- number of digits, \
- number of special characters.

If the constraints are insufficient, the program automatically completes the password.

“Automatic Complex Phrase” Mode

Generates a password composed of: \
- randomly selected words, \
- security-enhancing transformations, \
- reinforcement hashing, \
- random special characters, \
- cryptographically secure shuffling.

Integrated Strength Analyzer

The program automatically evaluates the password strength based on multiple criteria and displays a score ranging from:

Very weak → Excellent 🔒

## Program Execution
### Requirements:

Python 3.x

Tkinter (included by default in most Python distributions)

Running from Visual Studio Code:

Open the .py file

Click Run (or press F5)

The graphical interface appears → you can generate your passwords




**Français ** 

# Générateur de Mots de Passe Avancé avec Interface Graphique
##Présentation du projet

Ce projet est un générateur de mots de passe avancé développé en Python, équipé d’une interface graphique (Tkinter) permettant de créer facilement : \
- des mots de passe aléatoires hautement robustes (avec contraintes configurables), \
- des phrases complexes générées automatiquement, combinant lisibilité et sécurité, \
- une analyse automatique de la robustesse du mot de passe généré.

Ce projet a été conçu dans un contexte de sensibilisation à la cybersécurité, afin de promouvoir de bonnes pratiques de gestion des mots de passe, essentielles tant pour les utilisateurs que pour les organisations.

## Objectifs et utilité

Ce générateur répond à plusieurs enjeux :

### ✔ 1. Créer des mots de passe forts

Il intègre un moteur cryptographique basé sur secrets, garantissant une génération sécurisée et non prédictible.

### ✔ 2. Créer une "phrase complexe" mémorisable

Les mots de passe générés via ce mode combinent : \
- assemblage de mots aléatoires, \
- transformations (leet, majuscules/minuscules alternées), \
- ajout d’entropie via un hash, \
- injection de chiffres et caractères spéciaux.

➡ Ce mode permet d’obtenir un mot de passe robuste, unique et plus facile à mémoriser qu’une chaîne aléatoire pure.

### ✔ 3. Promouvoir les bonnes pratiques cybersécurité

Ce projet illustre techniquement plusieurs recommandations essentielles : \
- Utiliser un mot de passe différent pour chaque service
Cela réduit les risques en cas de fuite ou de compromission d’un site. \
- Choisir des mots de passe longs et complexes
Un mot de passe robuste combine longueur, diversité de caractères et imprévisibilité. \
- Éviter les schémas répétitifs ou personnels
Pas de dates de naissance, noms, animaux, etc. \
- S’appuyer sur un gestionnaire de mots de passe
Les humains ne sont pas faits pour retenir 50 mots de passe complexes.


Un gestionnaire comme Bitwarden, KeePass, Dashlane, etc. permet : \
- d’enregistrer des mots de passe uniques, \
- d’éviter la réutilisation, \
- de faciliter l’usage de mots de passe longs. \

➡ Ce projet démontre concrètement comment générer ce type de mot de passe.

## Pourquoi les mots de passe robustes sont essentiels ?

Dans plus de 80% des incidents de cybersécurité (source : Verizon DBIR),
les mots de passe faibles, réutilisés ou compromis jouent un rôle direct.

Un attaquant peut exploiter : \
- le credential stuffing (tester automatiquement des comptes volés sur d'autres sites),
- le bruteforce, \
- le cracking via bases de données hashées, \
- l’ingénierie sociale, \
- des attaques par dictionnaire. \

### Un mot de passe robuste : \
- augmente exponentiellement le temps nécessaire pour le casser, \
- empêche toute exploitation de mots de passe déjà divulgués ailleurs, \
- réduit globalement les surfaces d’attaque d’un utilisateur ou d’une entreprise. \

## Fonctionnalités du programme
### Interface Graphique (Tkinter)

Aucune ligne de commande → usage simple et intuitif.

### Mode “Classique”

Génère un mot de passe respectant les contraintes suivantes : \
- longueur totale, \
- nombre de majuscules, \
- nombre de minuscules, \
- nombre de chiffres, \
- nombre de caractères spéciaux.

Si les contraintes ne suffisent pas, le programme complète automatiquement le mot de passe.

### Mode “Phrase Complexe Automatique”

Génère un mot de passe composé : \
- de mots sélectionnés aléatoirement, \
- de transformations sécurisantes, \
- d’un hash de renforcement, \
- de caractères spéciaux aléatoires, \
- d’un mélange cryptographiquement aléatoire.

### Analyse de robustesse intégrée

Le programme évalue automatiquement la robustesse du mot de passe selon plusieurs critères, puis affiche un score allant de :

Très faible → Excellent 🔒

## Exécution du programme
### Prérequis :

Python 3.x

Tkinter (inclus automatiquement dans la majorité des distributions Python)

### Lancer depuis Visual Studio Code :

Ouvre le fichier .py

Clique sur Run (ou F5)

L'interface graphique apparaît → tu peux générer tes mots de passe
