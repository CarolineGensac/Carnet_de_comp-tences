# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'état (_state_) pour contrôler l'affichage d'un composant ❌ / ✔️

  > c'est une variable interne qui permet de modifier l’affichage d’un composant sans recharger la page.
  ✔ Permet de réagir aux interactions utilisateur.
  ✔ Évite de modifier directement le DOM.
  ✔ Met à jour uniquement le composant concerné.

  exemple :
  ```javascript
  import { useState } from "react";

  function ToggleText() {
    const [visible, setVisible] = useState(true); // Déclare l'état "visible"
  
    return (
      <div>
        {visible && <p>Texte affiché !</p>}
        <button onClick={() => setVisible(!visible)}>Afficher / Cacher</button>
      </div>
    );
  }
  
  export default ToggleText;
  ```

- les composants enfants et les _props_ qu'on leur passe ❌ / ✔️
- le déclenchement d'instructions en fonction des actions de l'utilisateur ❌ / ✔️
- le déclenchement d'instructions en fonction de l'étape du cycle de vie du composant ou du changement de valeur de ses props ❌ / ✔️
- l'usage d'un reducer (_useReducer_) pour gérer un état composé dans un composant
- l'état stocké dans un composant avec un _context provider_ et accessible dans ses descendants via `useContext` ❌ / ✔️

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
