![Logo, Javascript](/assets/images/js-logo.png) # Markdown-JS
------------------------------------------
### BASICS

inclure du JS dans un fichier HTML 

`<script type="text/javascript">LE code JS sera ICI</script>`

Appeler un fichier Javascript externe

  `<script src="myscript.js"></script>`

Ajouter des commentaires

  `// Single line comments` 
  `/* Multi-line 
  comments */` 

---
### VARIABLES

var = peut être réaffecté mais accessible uniquement dans une fonction

```const = Ne peuvent pas être réaffectés et ne sont pas accessibles avant qu'ils n'apparaissent dans le code```

let = Similaire au const, cependant il peut être réaffecté mais pas re-déclaré 


#### Numbers

`var age = 20`

#### Text(strings)

`var a = "Nicolas"`

#### Boolean

`var b = true`

#### Constants numbers

`const PI = 3.14`

#### Objects 

```
  Var name = {
    firstName:"Nicolas"
    lastName:"Pokus"
  }
```

---
### OPERATOR

#### Operators Basic

* `+`  Addition

* `-`  Soustraction

* `*`  Multiplication

* `/`  Division

* `(..)`  Grouping operator

* `%`  Modulo (reste)

* `++`  Increment numbers

* `--`  Decrement numbers

#### Operators Logique

* `&&`  et

* `||`  ou

* `!`  non ou inverse

#### Operators de comparaison

* `==`  égale à

* `===`  valeur égale et type égale

* `!=`  pas égale

* `!==`  valeur pas égale et type pas égale

* `>`  plus grand que

* `<`  plus petit que

* `>=`  plus grand et égale

* `<=`  plus petit ou égale à 

* `?`  operateur ternaire

---
### ARRAYS

`var fruit=["Banana", "Apple", "Pear"];`

---

### Méthodes de gestion des tableaux – Array

* `pop()` : Supprime le dernier élément d’un tableau

* `push()` : Ajoute un nouvel élément à la fin du tableau

* `sort()` : Trie les éléments par ordre alphabétique

* `reverse()` : Trier les éléments dans un ordre décroissant

* `shift()` : Supprime le premier élément d’un tableau

* `toString()` : Convertit des éléments en chaînes de caractères

* `unshift()` : Ajoute un nouvel élément au début d’un tableau

* `concat()` : Fusionne plusieurs tableaux en un seul

* `join()` : Combine les éléments d’un tableau en une seule chaîne de caractères et renvoie la chaîne

* `slice()` : Copie une partie d’un tableau dans un nouveau tableau

* `splice()` : Est utilisé pour modifier le contenu d’un tableau en supprimant les éléments existants et/ou en ajoutant de nouveaux éléments.

* `valueOf()` : Retourne la valeur primitive de l’objet spécifié

* `indexOf()` : Retourne le premier index auquel l’élément donné peut être trouvé dans un 
*tableau, ou -1 s’il n’est pas présent dans un tableau.

* `lastIndexOf()` : Retourne le dernier index auquel l’élément donné peut être trouvé dans un tableau, ou -1 s’il n’est pas présent dans un tableau.
 
---

### Méthodes pour afficher la sortie des données

* `alert()` : Affiche la sortie sur une boîte de dialogue du navigateur

* `confirm()` : Ouvre une boîte de dialogue oui/non et renvoie true/false en fonction du clic de l’utilisateur

* `console.log()` : Affiche la sortie sur la console du navigateur, utile pour le débogage
document.write() : Écrit directement dans le document HTM

---

  * `concat()`  joindre plusieurs tableaux en un seul

  * `indexOf()`  Renvoie la première position à laquelle un élément donné apparaît dans un tableau

  * `join()`  Combiner les éléments d'un tableau en une seule chaîne et renvoyer la chaîne

  * `lastIdexOf()`  Donne la dernière position à laquelle un élément donné apparaît dans un tableau

  * `pop()`  Supprime le dernier élément d'un tableau

  * `push()`  Ajoute un nouvel élément à la fin

  * `shift()`  Supprime le dernier élément d'un tableau

  * `unshift()`  Ajoute un nouvel élément à la fin

  * `splice()`  Supprime le dernier élément d'un tableau

  * `sort()`  Ajoute un nouvel élément à la fin

  * `reverse()`  Ajoute un nouvel élément à la fin

Fonctions globales
* `isNaN()` : Détermine si une valeur est NaN((Not a Number) ou non
* `Number()`  : Convertit l’argument en nombre représentant la valeur de l’objet. Si la valeur ne peut pas être convertie en nombre, NaN est renvoyé.
* `eval()`  : Évalue le code JavaScript représenté sous forme de chaîne
* `encodeURI()`  : Encode un URI en UTF-8
* `decodeURI()`  : Décode un URI créé par encodeURI() ou d’autres fonctions
* `decodeURIComponent()`  : Décode un composant URI
* `parseInt()`  : convertit une chaîne de caractères en entier
* `parseFloat()`  : convertit une chaîne de caractères en nombre à virgule flottante
* `isFinite()`  : Détermine si la valeur transmise est un nombre fini
 

Méthodes de l’objet String

* `match()`  : Récupère les correspondances d’une chaîne par rapport à un motif de recherche

* `search()`  : Recherche dans une chaîne de caractères la valeur spécifiée et renvoie la 
position de la correspondance.

* `toLowerCase()`  : Convertit une chaîne de caractères en minuscules

* `toUpperCase()`  : Convertit une chaîne de caractères en majuscules

* `indexOf()`  : Fournit la position du première occurrence d’un texte spécifié dans une chaîne

* `charAt()` : Retourne le caractère à la position spécifiée dans la chaîne

* `concat()`  : Concatène deux ou plusieurs chaînes en une seule

* `charCodeAt()`  : Retourne la valeur unicode d’un caractère à la position spécifiée

* `indexOf()`  : Fournit la position du première occurrence d’un texte spécifié dans une chaîne

* `lastIndexOf()`  : Fournit la position du dernière occurrence d’un texte spécifié dans une chaîne

* `slice()`  : Extrait une partie d’une chaîne et la renvoie sous forme de nouvelle chaîne


* `split()`  : Découpe une chaîne de caractère en un tableau de sous-chaînes en fonction d’un séparateur

* `substr()` : Comme slice() mais extrait une sous-chaîne en fonction du nombre de caractères spécifié

* `substring()` : Comme slice() mais ne peut accepter les index négatifs

* `replace()` : Recherche et remplace un texte spécifique dans une chaîne

---
### LOOPS

#### for()

```
<div v-for="item in items" :key="item.id">
  <!-- contenu -->
</div>

```

#### while()


#### do while()

---
### FUNCTIONS
