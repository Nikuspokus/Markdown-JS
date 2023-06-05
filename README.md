![Logo, Javascript](/assets/images/JS-Logo-1.png) # Markdown-JS
------------------------------------------

![Basics, Javascript](/assets/images/JS-Basics.png)

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

![Variables, Javascript](/assets/images/JS-Variables.png)

### VARIABLES

var = peut être réaffecté mais accessible uniquement dans une fonction

const = Ne peuvent pas être réaffectés et ne sont pas accessibles avant qu'ils n'apparaissent dans le code

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
![Operators, Javascript](/assets/images/JS-Operators.png)

### OPERATORS

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
![Arrays, Javascript](/assets/images/JS-Arrays.png)

### ARRAYS

`var fruit=["Banana", "Apple", "Pear"];`

* `['1','2'].concat(['3'])` : '1','2',3

* `['1','2'].join(['*'])` : 1*2

* `['1','2','3'].slice(2)` : 3

* `['1','2','3'].indexOf('2')` : 1

* `['1','2','3','4'].slice(0,2)` : 1,2

* `['1','2','3'].sort()` : 1,2,3

* `['1','2','3','4'].pop()` : 1,2,3

* `['1','2','3','4,].push('5')` : 1,2,3,4,5

* `['1','2','3'].length` : 3

* `['1','2','3'].reverse()` : 3,2,1

---

![Methods, Javascript](/assets/images/JS-Methods.png)
### Méthodes

#### Méthodes de gestion des tableaux – Array

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
 
#### Méthodes pour afficher la sortie des données

* `alert()` : Affiche la sortie sur une boîte de dialogue du navigateur

* `confirm()` : Ouvre une boîte de dialogue oui/non et renvoie true/false en fonction du clic de l’utilisateur

* `console.log()` : Affiche la sortie sur la console du navigateur, utile pour le débogage
document.write() : Écrit directement dans le document HTM

#### Fonctions globales

* `isNaN()` : Détermine si une valeur est NaN((Not a Number) ou non

* `Number()`  : Convertit l’argument en nombre représentant la valeur de l’objet. Si la valeur ne peut pas être convertie en nombre, NaN est renvoyé.

* `eval()`  : Évalue le code JavaScript représenté sous forme de chaîne

* `encodeURI()`  : Encode un URI en UTF-8

* `decodeURI()`  : Décode un URI créé par encodeURI() ou d’autres fonctions

* `decodeURIComponent()`  : Décode un composant URI

* `parseInt()`  : convertit une chaîne de caractères en entier

* `parseFloat()`  : convertit une chaîne de caractères en nombre à virgule flottante

* `isFinite()`  : Détermine si la valeur transmise est un nombre fini

#### Méthodes de l’objet String

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

#### Méthodes mathématiques

* `random()` : Retourne un nombre aléatoire compris entre 0 et 1

* `round(x)` : Arrondie la valeur de x à son entier le plus proche

* `pow(x, y)` : X à la puissance de y

* `exp(x)` : Exponentielle de x

* `log(x)` : Le logarithme naturel (base E) de x

* `max(x, y, z, …, n)` : Retourne le maximum

* `min(x, y, z, …, n)` : Retourne le minimum

* `abs(x)` : Retourne la valeur absolue de x

* `sqrt(x)` : La racine carrée de x

* `cos(x)` : Le cosinus de x

* `sin(x)` : Le sinus de x

* `tan(x)` : La tangente de x

* `ceil(x)` : Arrondie la valeur de x à l’entier le plus proche

#### Méthodes pour la manipulation des dates/heures en Javascript

* `getDate()` : Récupère le jour du mois sous forme de nombre (1-31)

* `getDay()` : Le jour de la semaine sous forme de nombre (0-6)

* `getFullYear()` : Année sous la forme d’un nombre à quatre chiffres (aaaa)

* `getHours()` : Retourne l’heure (0-23)

* `getMilliseconds()` : Retourne les millisecondes (0-999)

* `getMinutes()` : Retourne les minutes (0-59)

* `getMonth()` : Retourne le mois sous forme de nombre (0-11)

* `getSeconds()` : Récupère les secondes (0-59)

* `getTime()` : Récupère les millisecondes depuis le 1er janvier 1970

* `getUTCDate()` : Le jour du mois à la date spécifiée selon l’heure universelle.

* `setDate()` – Définit le jour en tant que nombre (1-31)

* `setFullYear()` – Définit l’année

* `setHours()` – Définit l’heure (0-23)

* `setMilliseconds()` – Définit les millisecondes (0 à 999)

* `setMinutes()` – Définit les minutes (0-59)

* `setMonth()` – Définit le mois (0-11)

* `setSeconds()` – Définit les secondes (0-59)

* `setTime()` – Fixe l’heure (en millisecondes depuis le 1er janvier 1970)

* `setUTCDate()` – Définit le jour du mois pour une date spécifiée en fonction du temps universel

#### Méthodes de nœud

* `appendChild()` : Ajoute un nouveau noeud en tant que dernier enfant d’un noeud parent.

* `removeChild()` : Supprime un nœud enfant

* `replaceChild()` : Remplace un nœud enfant

* `cloneNode()` : Clone un élément HTML

* `isEqualNode()` : Vérifie si deux noeuds sont égaux

* `isSameNode()` : Vérifie si deux noeuds sont identiques

* `getAttribute()` : Retourne la valeur d’attribut spécifiée dans un noeud

* `hasAttribute()` : Retourne true si l’élément a des attributs, sinon false

* `removeAttribute()` : Supprime l’attribut de l’élément spécifié

* `setAttribute()` : Définit ou modifie la valeur de l’attribut spécifié

* `getElementsByTagName()` : retourne une collection des éléments portant le nom de la balise spécifié.

---

![Loops, Javascript](/assets/images/JS-Loops.png)

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

![Json, Javascript](/assets/images/JS-Json.png)

### JSON

---

#### Types de données JSON

JSON définit 6 types de données :
 
1. String

```
{
  "name": "Alex"
}
``` 

4. Nombre

```
{
  "age": 24
}
``` 

2. Object

```
{
  "person": {
    "name": "Alex"
  }
}
```

3. Tableau

```
{
  "tab": [1, 2, 3, 4, 5, 6]
}
```
 

Boolean

```
{
  "open": true,
  "close": false
}
```
 

5. Date

```
{
  "DateNaissance": "1996-01-25 20:00:00 +0100"
}
```

### Comment lire les différents types de structure JSON

#### 1. Objets JSON
```
var person = {
   "name" : "Alex",
   "age" :  "25",
   "address" : "Paris"
};
```
Nous pouvons accéder aux informations comme ceci:
```
document.writeln("Le nom est:  " +person.name);
```

```
document.writeln("L'age est: " + person.age);
```

```
document.writeln("L'adresse est: "+ person.address);
``` 

#### 2. Objets JSON dans un tableau

Dans l’exemple ci-dessus, nous avons stocké les informations d’une seule personne dans un objet JSON. Supposons que nous souhaitons stocker les informations de plusieurs personnes. dans ce cas, nous pouvons avoir un tableau d’objets.

```
var persons = [{
   "name" : "Alex",
   "age" :  "25",
   "address" : "Paris"
},
{
   "name" : "Emily",
   "age" : "22",
   "address" : "Toulouse"
}];
```

Nous pouvons accéder aux informations comme ceci:
```
document.writeln("Le nom du 1er personne est:  " +person[0].name);   //Alex
```

```
document.writeln("Le nom du 2éme personne est: " + person[1].name);   //Emily
```

#### 3. Imbrication d’objets JSON:

Une autre façon de faire la même chose que nous avons fait dans l’exemple ci-dessus.

```
var persons = {
  "p1" : {
    "name" : "Alex",
    "age" :  "25",
    "address" : "Paris" 
  },
  "p2" : {
    "name" : "Emily",
    "age" : "22",
    "address" : "Toulouse"
  }
}
```

Nous pouvons accéder aux informations comme ceci:

```
document.writeln("Le nom du 1er personne est:  " +persons.p1.name);   //Alex
```

```
document.writeln("Le nom du 2éme personne est: " + persons.p2.name);   //Emily
``` 

![Json, Javascript](/assets/images/JS-Json.png)

### ARRAY METHODS
// Array iteration: 8 methods
```
// forEach
[1, 2, 3].forEach(function (item, index) {
  console.log(item, index);
});
```

```
// map
const three = [1, 2, 3];
const doubled = three.map(function (item) {
  return item * 2;
});
console.log(doubled);
```

```
// filter
const ints = [1, 2, 3];
const evens = ints.filter(function (item) {
  return item % 2 === 0;
});
console.log(evens);
```

```
// reduce
const sum = [1, 2, 3].reduce(function (result, item) {
  return result + item;
}, 0);
console.log(sum)
```

```
// some
const hasNegativeNumbers = [1, 2, 3, -1, 4].some(function (item) {
  return item < 0;
});
console.log(hasNegativeNumbers);
```

```
// every
const allPositiveNumbers = [1, 2, -3].every(function (item) {
  return item > 0;
});
console.log(allPositiveNumbers);
```

```
// find
const objects = [{ id: 'a' }, { id: 'b' }, { id: 'c' }];
const found = objects.find(function (item) {
  return item.id === 'b';
});
console.log(found);
```

```
// find index
const objects2 = [{ id: 'a' }, { id: 'b' }, { id: 'c' }];
const foundIndex = objects2.findIndex(function (item) {
  return item.id === 'b';
});
console.log(foundIndex)
```

![Json, Javascript](/assets/images/JS-Json.png)
```
// switch case
const expr = 'Papayas';
switch (expr) {
  case 'Oranges':
    console.log('Oranges are $0.59 a pound.');
    break;
  case 'Mangoes':
  case 'Papayas':
    console.log('Mangoes and papayas are $2.79 a pound.');
    // Expected output: "Mangoes and papayas are $2.79 a pound."
    break;
  default:
    console.log(`Sorry, we are out of ${expr}.`);
}
```
