# Gestion des tabs par JavaScript
> JS exercise given at HEPL

* * *

**js-tp-aria-tabs** is an educational project, which will be used for `JS` courses.

**Note:** the school where the course is given, the [HEPL](http://www.provincedeliege.be/hauteecole) from Liège, Belgium, is a french-speaking school. From this point, the instruction will be in french. Sorry.

* * *

> Lors de vos cours de *web*, vous allez découvrir le langage *JavaScript* et le mettre en pratique pour apprendre à rendre vos pages web interactives.  

* * *
Dans le cadre de cet exercice, nous vous demandons de contrôler l’affichage des tabs par JavaScript. 

Remarquez qu’il s’agit d’un exercice purement scolaire. La couche de JavaScript n'est **pas** nécessaire. Un tel comportement pourrait être pleinement assumé à l’aide de CSS uniquement. Notez que nous prendrons quand même soin de laisser le contenu de la page accessible si JavaScript  n'est pas disponible.



Énoncé

1. Ajoutez la classe `.js-enabled` à l’élément `html` afin de provoquer un rendu sous forme de tab. 

1. Au click sur un bouton de la navigation vous devez ajouter la classe `active` à l’article qui porte l’`id`
définit dans l’attribut `data-country` du bouton cliqué. 
Ex : Quand je clique sur le bouton 

```
<button class="tablinks" data-country="London">Londres</button>
```
l’article dont l’id est `London` reçoit la classe active.
```
<article id="London" class="tabcontent active"></article>
```
2. Ajouter au bouton cliqué également la classe `active`.



![Rendu](./readme.gif)
