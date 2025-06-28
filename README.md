DESCRIPTION DU PROJET                                                                                           T 


Spécifications fonctionnelles :

Plateforme de commerce électronique :

Le site web sera développé comme une plateforme conviviale et intuitive de commerce électronique, proposant une large gamme de produits répartis dans différentes catégories.
Les utilisateurs auront la possibilité de naviguer à travers les produits, de les ajouter à leur panier et de finaliser leurs achats.

Chatbot :

Une intégration d'un chatbot sur le site web permettra d'interagir avec les utilisateurs afin de comprendre leurs besoins et de leur fournir des recommandations de produits.
Le chatbot exploitera des techniques de traitement du langage naturel (NLP) pour comprendre les requêtes des utilisateurs et leur fournir des réponses contextualisées.

Recommandations de produits :

À partir de l'analyse des données utilisateur telles que l'historique d'achat, les préférences de produits et les interactions sur le site, le chatbot générera des recommandations personnalisées.
Ces recommandations seront élaborées grâce à des algorithmes d'apprentissage automatique prenant en compte les tendances du marché et les données démographiques.

Intégration avec le processus d'achat :

Le chatbot assistera les utilisateurs tout au long du processus d'achat en leur fournissant des informations sur les produits, en répondant à leurs questions et en les guidant dans leur parcours d'achat.

Contraintes techniques :

Le développement de l'application se fera en utilisant le langage de programmation Python.
Pour le chatbot, l'utilisation de bibliothèques de traitement du langage naturel (NLP) sera privilégiée.

Travail demandé :

Élaboration d'une conception détaillée comprenant au minimum un diagramme de cas d'utilisation et un diagramme de classe, répondant ainsi aux exigences du projet.
Développement d'une application fonctionnelle conforme à la conception établie, suivie de son déploiement sur GitHub.
                                                                                             
 
Présentation d'un rapport de projet documentant les différentes étapes de conception, développement et déploiement.

Diagramme de cas d’utilisations :

![image](https://github.com/user-attachments/assets/d1b5ec09-a92a-4bbb-9045-ee156f304701)

le diagramme de classe

![image](https://github.com/user-attachments/assets/ec7dca40-4d0e-49da-bf51-7449f54f677e)

Les langages utilisés

Python :


![image](https://github.com/user-attachments/assets/ebbe89a4-5e99-450d-a4b2-d828ac1febe0)

Django:


![image](https://github.com/user-attachments/assets/23b91505-15b9-4054-a6d2-2763f981ecdc)

![image](https://github.com/user-attachments/assets/cd7204c2-088f-4038-b7a1-da3470caf2e4)

HTML:

![image](https://github.com/user-attachments/assets/b78f451f-50e6-4271-9dd0-b3ade4876fd4)




Les tests
![image](https://github.com/user-attachments/assets/4259dbb7-78f1-49c1-9aff-67f60c4010cc)

![image](https://github.com/user-attachments/assets/e23268b1-d97a-4877-bbe2-bccba3c80a6b)

![image](https://github.com/user-attachments/assets/399b40c3-da1e-4940-bd8a-77f158e77abc)

![image](https://github.com/user-attachments/assets/8953cfd9-9f89-440b-a602-811d21d31bf4)

![image](https://github.com/user-attachments/assets/400cda8c-1c50-4abd-b8b1-329d1a5f50d4)

![image](https://github.com/user-attachments/assets/727874ac-3c41-4c71-bad0-4bbe2298fdff)

![image](https://github.com/user-attachments/assets/7a9bc6bc-b039-4e2c-a919-892e28decee5)

![image](https://github.com/user-attachments/assets/85a34651-5b1d-497f-8c77-9176d05719ad)

![image](https://github.com/user-attachments/assets/14b0cef1-7a4f-4c18-ae3c-d2d23e3003e0)

![image](https://github.com/user-attachments/assets/9fc0ac00-4f36-4c9f-813a-6d194f2ff1f5)

![image](https://github.com/user-attachments/assets/3caa9f93-7b37-433c-9c44-0806f6334bec)

![image](https://github.com/user-attachments/assets/f3634a0f-bded-4405-8877-9e64146c022f)














# Installation

Follow these steps to set up the Django ChatGPT Chatbot:

1. Clone the repository:
```
git clone https://github.com/SonOfOgre666/Bi3Smart.git
cd Bi3Smart
```

2. Set up your OpenAI API key:

   Open `consumers.py` in (Bi3Smart/chat/consumers.py) and add openai_api_key:

   ```python
   OPENAI_API_KEY = 'your_api_key' # Replace YOUR_API_KEY with your openai apikey 
   ```

# Usage

To run the Django Bi3Smart Project, follow these steps:

## For Mac/ Linux

```
.venv/Scripts/activate
python manage.py runserver
```

## For Windows

```
.venv\Scripts\activate
sudo .venv/Scripts/activate
python manage.py runserver
```
