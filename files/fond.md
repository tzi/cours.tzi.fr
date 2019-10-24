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
La déclaration `background-size: cover` permet de recouvrir notre élément avec l'image de fond, quitte à ce que certaines parties de l'image ne soient pas visibles.
La déclaration `background-size: contain` permet de contenir une image à l'intérieurnotre élément avec l'image de fond, quitte à ce que certaines parties de l'image ne soient pas visibles.

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTM5MjgwMzc3Nyw0MDQ5NDkwOTZdfQ==
-->