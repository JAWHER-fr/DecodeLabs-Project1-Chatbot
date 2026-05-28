# Project 1: Rule-Based AI Chatbot Engine

## Domain: Artificial Intelligence Track
**Developed by:** Dridi Jawher  
**Framework Layer:** Heuristic Rule-Based NLP Logic  

## System Architectural Design
Ce projet implémente un agent conversationnel basé sur des règles strictes (Rule-Based Chatbot). Le système utilise des structures de contrôle conditionnelles et une normalisation des chaînes de caractères pour faire correspondre les intentions de l'utilisateur (User Intents) à des réponses prédéfinies, simulant ainsi un assistant académique automatisé.

### Pipeline de l'Architecture :
1. **Input Layer :** Capture des requêtes textuelles brutes de l'utilisateur.
2. **Text Normalization :** Nettoyage des données d'entrée (conversion en minuscules, suppression des espaces inutiles) pour éviter les erreurs de syntaxe.
3. **Intent Matching Layer :** Évaluation des correspondances via des structures conditionnelles optimisées.
4. **Fallback Mechanism :** Gestion des requêtes inconnues grâce à une réponse de secours par défaut pour maintenir l'interaction.

## Structure des Fichiers
* `chatbot.py` - Le code source principal du chatbot.
* `DecodeLabs_Project1_Dridi_Jawher.pdf` - Le rapport technique officiel.
* `README.md` - Documentation du projet.

## Instructions d'Exécution
Aucune bibliothèque externe n'est requise. Exécutez simplement le script avec Python standard :
```bash
python chatbot.py
