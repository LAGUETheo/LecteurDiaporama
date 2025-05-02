# 📸 SAE1.01 - LecteurDiaporama

**LecteurDiaporama** est un projet développé dans le cadre de la SAE1.01 (*Situation d'Apprentissage et d'Évaluation*) en 2022. L’objectif était de transformer une base de code procédural (V0) en une application complète orientée objet, avec interface graphique et fonctionnalités avancées autour de la gestion et la visualisation de diaporamas.

## 🗂️ Table des versions

| Version | Description |
|--------|-------------|
| **V1** | Transformation du code procédural fourni (V0) en code orienté objet avec les mêmes fonctionnalités. |
| **V2** | Création de l'interface graphique de la fenêtre principale de l'application (utilisation de Qt ou équivalent). |
| **V3** | Affichage des images dans l'interface graphique + implémentation de `Fichier >> Quitter`. |
| **V4** | Mise en place du mode de défilement automatique du diaporama. |
| **V5** | Ajout des fonctionnalités : <br>• `Fichier >> Diaporama >> Charger un diaporama` <br>• `Fichier >> Diaporama >> Changer la vitesse de défilement` <br>• `Fichier >> Diaporama >> Enlever le diaporama`. |
| **V6** | Migration des fonctionnalités de la V5 pour qu'elles interagissent avec une base de données (SQLite ou équivalent). |
| **V7** | Fonctionnalités bonus : <br>• Stylisation des fenêtres <br>• Animations lors du changement d'image <br>• `Fichier >> Diaporama >> Créer un diaporama` avec contraintes de la BDD. |

## 🛠️ Technologies utilisées

- **Langage** : C++
- **Interface graphique** : Qt (recommandé pour V2+)
- **Base de données** : SQLite (V6+)
- **Outils** : Qt Creator, g++, CMake (optionnel)

## 📦 Installation

### Prérequis

- Qt (5 ou 6)
- CMake (si utilisé)
- Un compilateur C++ compatible (g++, MSVC, clang...)

### Compilation avec Qt Creator

1. Ouvrir le `.pro` ou `CMakeLists.txt` dans Qt Creator.
2. Configurer le projet selon votre environnement.
3. Compiler et exécuter.

## 🎮 Fonctionnalités principales

- Lecture manuelle ou automatique d’un diaporama
- Chargement/suppression de diaporamas
- Création de diaporamas personnalisés (V7)
- Vitesse de lecture paramétrable
- Interface graphique stylisée et interactive
