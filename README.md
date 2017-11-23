# chono-SWLH
**Modifier la durée :**

la variable `temps` permet de définir la durée du chronomètre.

Par exemple pour 2 min :
```javascript
var temps = 2;
```
ou pour 1min 30 :
```javascript
var temps = 1.50;
```
**Les sponsors**

le carrousel de bootstrap est utilisé : https://v4-alpha.getbootstrap.com/components/carousel/

dans la 
```html
<div class="carousel-inner" role="listbox">
```
il suffit de rajouter pour chaque sponsor

```html
<div class="carousel-item">
    <img class="d-block logo" src="logo/SWLH_Partner_CONTAINER.png" alt="Second slide">
</div>
```

pour changer la vitesse, il faut changer la valeur de l'interval: 
```javascript 
$('.carousel').carousel({
    interval: 2000
})
```
**la musique de fin**

pour définir la musique , il faut changer l'attribut `src` dans 
```html
<audio id="arret" src="Je_vous_demande_de_vous_arreter.mp3"></audio>
```