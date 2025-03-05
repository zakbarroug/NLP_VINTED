# 🔍 Moteur de recherche sémantique d'avis Vinted avec explications      ![image](https://github.com/user-attachments/assets/2dda9447-bc63-47a2-9914-50ee26fdc578)


Ce projet propose un moteur de recherche d'avis client de Vinted qui identifie rapidement les avis les plus pertinents et offre des explications claires sur leur intérêt.
![image](https://github.com/user-attachments/assets/9c43395e-8d04-4e86-9c5f-ece9f4d227e7)

## 📌 Présentation du Projet

Le projet s'appuie sur SBERT (Sentence-BERT) pour effectuer une recherche sémantique avancée dans les avis clients, combiné à Falcon pour générer automatiquement des explications simples et accessibles. L'interface interactive permet de tester et de visualiser facilement les résultats.

## 💡 Fonctionnalités

- **Recherche avancée d'avis**  
  Identifie les avis les plus pertinents en fonction d'une requête utilisateur.
- **Explications claires**  
  Fournit une explication concise sur la pertinence d'un avis pour faciliter la compréhension.
- **Interface interactive**  
  Une interface conviviale basée sur Gradio pour tester et démontrer le moteur de recherche.
- **Optimisation de la recherche**  
  Utilisation de FAISS pour une indexation rapide et efficace des avis.

## 🛠 Technologies Utilisées

- **Python**  
  Langage principal du projet.
- **SBERT (Sentence-BERT)**  
  Pour la recherche sémantique des avis.
- **FAISS**  
  Pour une indexation et une recherche rapides.
- **Falcon**  
  Pour la génération des explications.
- **Gradio**  
  Pour l'interface web interactive.
- **Google Play Scraper**  
  Pour récupérer les avis depuis le Play Store.
- **Pandas, Matplotlib, WordCloud**  
  Pour la manipulation et la visualisation des données.
