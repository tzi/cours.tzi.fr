# Fond

## Image de fond

```css
.image {
	background-image: url('photo.jpg');
}
```

La fonction `url()` permet d'indiquer l'url d'une image pour l'utiliser comme fond d'un élément.

## Taille d'une image

```css
.image {
	background-image: url('photo.jpg');
	background-size: cover;
}
```

La propriété `background-size` permet de définir la taille de l'image de fond. Cette image peut être plus petite ou plus grande que notre élément. Si on veut que l'image s'adapte à la taille de notre élément, il existe 2 mots clés.

![background-size: cover](https://ibin.co/4zZ9Ce0ncTwQ.png)
La déclaration `background-size: cover` permet de recouvrir notre élément avec l'image de fond, quitte à ce que certaines parties de l'image ne soient pas visibles.

![background-size: contain](https://ibin.co/4zZ9OCEwnpko.png)
La déclaration `background-size: contain` permet de contenir une image de fond à l'intérieur de notre élément, quitte à ce que certaines parties de notre élément ne dispose pas d'image de fond.

## Gradients

```css
.boite {
	background-image: linear-gradient(to right, blue, red);
}
```

À l'aide de la fonction `linear-gradient()` on peut générer une image qui représentera un gradient. Cette fonction prend comme premier paramètre la direction, puis les autres paramètres sont des étapes de couleurs.

![Exemple de gradient](https://mdn.mozillademos.org/files/3537/linear-gradient.png)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExNjI0MTE2OSwtMTQ3MDkyMjA0Nyw0MD
Q5NDkwOTZdfQ==
-->