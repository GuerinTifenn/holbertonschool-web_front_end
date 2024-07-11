### Réponses aux Questions du Quiz

#### Question #0
Quel est le texte final de couleur de `<h1>` dans ce code ?
```html
<html>
    <head>
        <style>
            h1 {
                color: #FF0000;
            }
        </style>
    </head>
    <body>
            <h1>Hello</h1>
    </body>
</html>
```
**Réponse :** `#FF0000`

#### Question #1
Quel est le texte final de couleur de `<h1>` dans ce code ?
```html
<html>
    <head>
        <style>
            h1, h2 {
                color: #FF0000;
            }
        </style>
    </head>
    <body>
            <h1>Hello</h1>
    </body>
</html>
```
**Réponse :** `#FF0000`

#### Question #2
Quel est le texte final de couleur de `<h1>` dans ce code ?
```html
<html>
    <head>
        <style>
            h1.title {
                color: #FF0000;
            }
        </style>
    </head>
    <body>
            <h1>Hello</h1>
    </body>
</html>
```
**Réponse :** `Black (default value)`

#### Question #3
Quel est le texte final de couleur de `<h1>` dans ce code ?
```html
<html>
    <head>
        <style>
            body {
                color: #00FF00;
            }
        </style>
    </head>
    <body>
            <h1>Hello</h1>
    </body>
</html>
```
**Réponse :** `#00FF00`

#### Question #4
Quel est le texte final de couleur de `<h1>` dans ce code ?
```html
<html>
    <head>
        <style>
            body {
                color: #00FF00;
            }
            h1 {
                color: #FF0000;
            }
        </style>
    </head>
    <body>
            <h1>Hello</h1>
    </body>
</html>
```
**Réponse :** `#FF0000`

#### Question #5
Quel est le texte final de couleur de `<h1>` dans ce code ?
```html
<html>
    <head>
        <style>
            h1 {
                color: #FF0000;
            }
            body h1 {
                color: #00FF00;
            }
        </style>
    </head>
    <body>
            <h1>Hello</h1>
    </body>
</html>
```
**Réponse :** `#00FF00`

#### Question #6
Quel est le texte final de couleur de `<h1>` dans ce code ?
```html
<html>
    <head>
        <style>
            h1 {
                color: #FF0000;
            }
            h1.title {
                color: #00FF00;
            }
            body h1 {
                color: #0000FF;
            }
        </style>
    </head>
    <body>
            <h1 class="title">Hello</h1>
    </body>
</html>
```
**Réponse :** `#0000FF`

#### Question #7
Quel est le texte final de couleur de `<h1>` dans ce code ?
```html
<html>
    <head>
        <style>
            body > h1.title {
                color: #FF0000;
            }
            h1.title {
                color: #00FF00;
            }
            body h1 {
                color: #0000FF;
            }
        </style>
    </head>
    <body>
            <h1 class="title">Hello</h1>
    </body>
</html>
```
**Réponse :** `#00FF00`

#### Question #8
Le padding ajoute de l'espace entre ?
**Réponse :** Entre le contenu intérieur et la bordure de l'élément

#### Question #9
La marge ajoute de l'espace entre ?
**Réponse :** Entre la bordure de l'élément et les éléments externes (éléments parents et frères)

#### Question #10
Quel est l'impact de `position: fixed` sur un élément ?
**Réponse :** L'élément sera positionné par rapport à la fenêtre d'affichage

#### Question #11
Quel est l'impact de `position: absolute` sur un élément ?
**Réponse :** L'élément sera positionné par rapport à l'ancêtre positionné le plus proche

#### Question #12
Qu'est-ce que le `z-index` ?
**Réponse :** Le `z-index` définit la position d'empilement d'un élément (de l'avant vers l'arrière)

#### Question #13
Quel est l'impact de `overflow-y: auto` sur un élément ?
**Réponse :** L'élément permet le défilement vertical si le contenu est trop long

#### Question #14
Quelle est la taille de la police en pixels d'un élément `p.my_class` ?
```css
p {
    font-size: 12px;
}
p.my_class {
    color: #FF0000;
}
```
**Réponse :** 12px

#### Question #15
Quelle est la taille de la police en pixels d'un élément `p.my_class` ?
```css
p {
    font-size: 12px;
}
p.my_class {
    font-size: 1em;
}
```
**Réponse :** 12px

#### Question #16
Quelle est la taille de la police en pixels d'un élément `p.my_class` ?
```css
p {
    font-size: 12px;
}
p.my_class {
    font-size: 1.5em;
}
```
**Réponse :** 18px

#### Question #17
Quelle est la taille de la police en pixels d'un élément `p.my_class` ?
```css
p {
    font-size: 12px;
}
p.my_class {
    font-size: 0.25em;
}
```
**Réponse :** 3px

#### Question #18
Quelle est la taille de la police en pixels d'un élément `p.my_class` si la taille par défaut de `p` est de 16px ?
```css
p {
    font-size: 12px;
}
p.my_class {
    font-size: 0.25rem;
}
```
**Réponse :** 4px

#### Question #19
Quelle est la taille de la police en pixels d'un élément `p.my_class` si la taille par défaut de `p` est de 16px ?
```css
p {
    font-size: 12px;
}
p.my_class {
    font-size: 2.25rem;
}
```
**Réponse :** 36px

#### Question #20
Quelle est la taille de la police en pixels d'un élément `p.my_class` si la taille par défaut de `p` est de 16px ?
```css
p {
    font-size: 75%;
}
p.my_class {
    font-size: 2.25em;
}
```
**Réponse :** 27px

Si vous avez des questions supplémentaires ou avez besoin de plus d'explications, n'hésitez pas à demander !
