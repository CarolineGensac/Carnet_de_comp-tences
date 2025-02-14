# Langage Javascript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les `structures` de base du langage ✔️
  ### Structures de base de JavaScript

1. **Types de données** : Primitifs (`Number`, `String`, `Boolean`, `Undefined`, `Null`, `Symbol`, `BigInt`) et Objets.  
2. **Variables** : `var`, `let`, ou `const`.
```var globalVar = "Je suis global"; // Éviter var (pas de portée bloc)
let localVar = "Je peux être réassigné";
const constantVar = "Je ne change jamais";```

3. **Structures de contrôle** : Conditions, boucles ...`if`, `else`, `switch`, `for`, `while`, `do...while`, `for...in`, `for...of`.
 > Elles permettent de prendre des décisions (if) ou de répéter des actions (for, while).
 
5. **Fonctions** : Blocs de code réutilisables (`function` ou fléchées `=>`).
 > Ce sont des blocs de code qui exécutent une tâche et qu'on peut réutiliser facilement.

6. **Objets et tableaux** : Collections de paires clé-valeur (objets) ou d'éléments ordonnés (tableaux).
 > Les objets regroupent des infos sous forme de paires (clé: valeur), et les tableaux sont des listes organisées.

7. **Opérateurs** : Arithmétiques (+, -, /, *), logiques ( ||, &&, !), comparatifs (==, =!), et affectations.
 >  Ce sont des signes (+, -, ===, &&) qui permettent de faire des calculs, des comparaisons ou des conditions.

8. **Gestion des erreurs** : Bloc `try...catch` pour capturer les exceptions.
 >  On utilise try...catch pour éviter que le programme plante en cas de problème.

9. **Modules** : Organisation du code avec `export` et `import {}`.
 > Ils permettent de diviser le code en petits morceaux qu'on peut importer et utiliser ailleurs.

- les normes `ecmascript` ❌ / ✔️
- 
- l'utilisation de l'`asynchrone`  ✔️ (async / await/ etc)
 > permet d’effectuer des requêtes réseau de manière efficace sans bloquer l'exécution du programme.

### Exemple de récupération d'article en JavaScript avec `async/await`

```
// récupérer les données
async function fetchArticle(url) {
  try {
    const response = await fetch(url);  // Effectuer la requête HTTP
    if (response.ok) {
      const articleData = await response.text();  // Récuperesle corps de la réponse
      console.log("Article récupéré); 
    } else {
      console.log(`Erreur lors de la récupération de l'article : ${response.status}`);
    }
  } catch (error) {
    console.log("Erreur de réseau ou autre erreur :", error);
  }
}

// URL de l'article à récupérer
const articleUrl = "https://example.com/article";  // Remplacez par une URL réelle

// Appel de la fonction pour récupérer l'article
fetchArticle(articleUrl);

- 
  1. **JavaScript est mono-thread, ce qui signifie qu'il ne peut exécuter qu'une tâche à la fois.**
  2. **L'asynchronie permet de ne pas bloquer le fil principal lorsqu'une tâche longue est exécutée, en continuant à traiter d'autres opérations pendant ce temps.**
  
- les spécifités du mot-clef `this` ❌ / ✔️

  **a moitié**

## 💻 Je code en Javascript

### Un exemple de code commenté ❌ / ✔️

```javascript
(e) => mc2;
```

### Utilisation dans un projet ❌ / ✔️

[lien github](...)

Description :

### J'ai utilisé ce langage en production ❌ / ✔️

[lien du projet](...)

Description :

### J'ai utilisé ce langage en environement professionnel ❌ / ✔️

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

