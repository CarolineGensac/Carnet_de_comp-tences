# GraphQL

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

### la différence entre REST et GraphQL ✔️

- REST :
va à l’URL /users, et te retourne toutes les infos sur les utilisateurs, même si tu en voulais moins.
✅ Simple
❌ Pas très flexible
📍 Un endpoint par type de données

- GraphQL :
On demande ce que l'on veux : "Donne-moi juste le nom et l’email de l’utilisateur", et il ne te retourne que ça, rien de plus.
✅ Ultra flexible
❌ Plus complexe à mettre en place
📍 Un seul endpoint, tu fais ta requête comme tu veux

### les besoins auxquels répond GraphQL ✔️

Récupérer exactement ce qu’on veut (ni plus, ni moins)
GraphQL te laisse choisir les champs que tu veux
```javascript
query {
  user(id: 1) {
    name
    email
  }
}

```
Réduire le nombre d’appels réseau

Donner + de contrôle au front-end
🧠 Le client décide de la forme des données

### la définition d'un schéma

 En GraphQL, un schéma définit la structure de l'API et les types de données qui peuvent être demandés ou modifiés. C'est une sorte de contrat entre le client et le serveur, qui décrit précisément quelles données sont disponibles, comment elles peuvent être récupérées, et comment elles peuvent être modifiées.

#### composant d'un schéma :
  
 Types : Définissent les objets et leurs propriétés.

Requêtes (Query) : Permettent de récupérer des données.

Mutations : Permettent de modifier les données (ajouter, mettre à jour, supprimer).

Subscriptions : Permettent de recevoir des mises à jour en temps réel (comme des notifications). // non abordé


### Query ✔️

- Une query (requête) en GraphQL est utilisée pour récupérer des données du serveur. C’est l’équivalent d’une requête GET dans une API REST sauf que tu peux spécifier exactement quelles données tu veux obtenir.

```javascript
query GetCategories {
  getCategories {
    id
    name
    description
  }
}
```

### Mutation ✔️

- Les Mutations en GraphQL :
Les mutations sont utilisées pour modifier des données sur le serveur. Elles sont l'équivalent des requêtes POST, PUT, DELETE dans une API REST.

Contrairement à une query (qui récupère des données), une mutation te permet de créer, mettre à jour ou supprimer des données.


### Subscription ❌ / ✔️


a check 


## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

### Utilisation dans un projet ❌ / ✔️

[lien github](...)

Description :

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
