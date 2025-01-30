# Chatbot Simple avec NLP en Python

Ce projet consiste à créer un **chatbot basique** capable de répondre à des questions en utilisant des techniques de **traitement du langage naturel (NLP)**. Il repose sur l'algorithme de **similarité cosinus** pour trouver la meilleure réponse parmi un ensemble de questions et réponses pré-définies.

## Table des matières
- [Description](#description)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Exemple de base de données](#exemple-de-base-de-données)
- [Améliorations possibles](#améliorations-possibles)
- [Contribuer](#contribuer)
- [Licence](#licence)

## Description

Le but de ce projet est de créer un chatbot qui peut répondre à des questions sur un sujet donné. Il utilise **TF-IDF (Term Frequency - Inverse Document Frequency)** pour transformer les questions en vecteurs numériques et la **similarité cosinus** pour trouver la réponse la plus pertinente parmi un ensemble de données.

### Fonctionnalités :
- Le chatbot répond à des questions simples sur un domaine spécifique (ex: programmation en Python).
- Il peut être amélioré en ajoutant plus de questions et réponses ou en utilisant des techniques avancées de NLP.

## Prérequis

- Python 3.x
- Bibliothèques : 
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `nltk`

## Installation

### Cloner le dépôt

Clone ce dépôt sur ton ordinateur :

```bash
git clone https://github.com/ton-utilisateur/chatbot-nlp.git
cd chatbot-nlp
