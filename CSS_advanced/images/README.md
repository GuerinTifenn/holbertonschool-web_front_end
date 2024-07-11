### PLD Questions - HTML Avancé

1. **Que signifie HTML ?**
   HTML signifie **HyperText Markup Language**.

2. **Quel est le but de HTML ?**
   Le but de HTML est de structurer et de présenter le contenu sur le web. Il permet de créer des pages web avec des éléments tels que du texte, des images, des liens, etc.

3. **Sous quel élément (balise) HTML écrivons-nous ce qui sera visible uniquement sur la PAGE du navigateur ?**
   Le contenu visible sur la page du navigateur est écrit sous l'élément `<body>`.

4. **Comment créer un titre en HTML ?**
   Vous pouvez créer un titre en HTML en utilisant les balises de titre, de `<h1>` à `<h6>`, par exemple `<h1>Titre principal</h1>`.

5. **Quelle est la différence entre les éléments inline et block en HTML ?**
   Les éléments *inline* ne commencent pas sur une nouvelle ligne et prennent seulement la largeur nécessaire, tandis que les éléments *block* commencent sur une nouvelle ligne et occupent toute la largeur disponible.

6. **Comment créer un lien hypertexte en HTML ?**
   Vous pouvez créer un lien hypertexte en utilisant la balise `<a>`, par exemple : `<a href="https://www.example.com">Cliquez ici</a>`.

7. **Quel est le but de l'attribut alt dans une balise `<img>` ?**
   L'attribut `alt` fournit une description textuelle de l'image, utile lorsque l'image ne peut pas être affichée ou pour les technologies d'assistance.

8. **Comment créer une liste non ordonnée en HTML ?**
   Vous pouvez créer une liste non ordonnée en utilisant la balise `<ul>` pour la liste et `<li>` pour les éléments, par exemple :
   ```html
   <ul>
     <li>Élément 1</li>
     <li>Élément 2</li>
   </ul>
   ```

9. **Que fait la balise `<br>` ?**
   La balise `<br>` insère un saut de ligne.

10. **Quel est le but de la balise `<meta>` en HTML ?**
    La balise `<meta>` fournit des métadonnées sur le document HTML, telles que les informations de caractère, l'auteur, et les mots-clés pour les moteurs de recherche.

11. **Comment ajouter un commentaire en HTML ?**
    Vous pouvez ajouter un commentaire en HTML en utilisant `<!-- Commentaire -->`.

12. **Quelle est la différence entre la balise `<header>` et les titres en HTML ? Sont-ils la même chose ou non ? Expliquez !**
    La balise `<header>` est utilisée pour contenir le contenu d'en-tête d'une page ou d'une section, comme les titres, les logos, ou les barres de navigation. Les titres (de `<h1>` à `<h6>`) sont des éléments de texte qui définissent les titres de sections spécifiques. Ils ne sont pas la même chose, mais `<header>` peut contenir des titres.

13. **Quelle est la structure de base d'une page HTML ? Pouvez-vous fournir un exemple de code simple ?**
    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <title>Page Titre</title>
    </head>
    <body>
        <h1>Mon premier titre</h1>
        <p>Voici un paragraphe.</p>
    </body>
    </html>
    ```

### PLD Questions - CSS Avancé

1. **Que signifie CSS ?**
   CSS signifie **Cascading Style Sheets** (Feuilles de Style en Cascade).

2. **Quel est le but de CSS ?**
   Le but de CSS est de styliser et de mettre en forme les éléments HTML d'une page web.

3. **Comment appliquez-vous des styles CSS à un élément HTML ?**
   Vous pouvez appliquer des styles CSS en utilisant des sélecteurs et des règles CSS dans une balise `<style>` dans le `<head>`, directement dans un élément avec l'attribut `style`, ou via un fichier CSS externe.

4. **Qu'est-ce qu'un sélecteur en CSS ?**
   Un sélecteur en CSS est un modèle utilisé pour sélectionner les éléments HTML que vous souhaitez styliser.

5. **Comment sélectionnez-vous des éléments par leur classe en CSS ?**
   Vous sélectionnez des éléments par leur classe en utilisant un point suivi du nom de la classe, par exemple `.maClasse`.

6. **Quelle est la différence entre les sélecteurs de classe et d'ID en CSS ?**
   Les sélecteurs de classe sont précédés d'un point (`.`) et peuvent être appliqués à plusieurs éléments, tandis que les sélecteurs d'ID sont précédés d'un dièse (`#`) et ne doivent être appliqués qu'à un seul élément unique.

7. **Comment changez-vous la couleur de fond d'un élément en CSS ?**
   Vous pouvez changer la couleur de fond avec la propriété `background-color`, par exemple `background-color: blue;`.

8. **Comment changez-vous la taille de la police en CSS ?**
   Vous pouvez changer la taille de la police avec la propriété `font-size`, par exemple `font-size: 16px;`.

9. **Comment centrez-vous un élément horizontalement en CSS ?**
   Pour centrer un élément horizontalement, vous pouvez utiliser `margin: 0 auto;` sur un élément avec une largeur définie.

10. **Comment ajoutez-vous une bordure à un élément en CSS ?**
    Vous pouvez ajouter une bordure avec la propriété `border`, par exemple `border: 1px solid black;`.

11. **Qu'est-ce que le modèle de boîte CSS (CSS box model) ?**
    Le modèle de boîte CSS est un concept qui définit la structure d'un élément HTML avec des marges (`margin`), des bordures (`border`), des espaces intérieurs (`padding`), et le contenu (`content`).

12. **Comment changez-vous la couleur du texte d'un élément en CSS ?**
    Vous pouvez changer la couleur du texte avec la propriété `color`, par exemple `color: red;`.

13. **Comment créez-vous un commentaire en CSS ?**
    Vous pouvez créer un commentaire en CSS avec `/* Commentaire */`.

14. **Comment liez-vous un fichier CSS externe à un document HTML ?**
    Vous pouvez lier un fichier CSS externe avec la balise `<link>` dans le `<head>` de votre document HTML, par exemple :
    ```html
    <link rel="stylesheet" type="text/css" href="styles.css">
    ```

15. **Qu'est-ce que le "cascading" dans les feuilles de style en cascade (CSS) ?**
    Le "cascading" se réfère à la manière dont les styles sont appliqués en fonction de leur spécificité et de leur ordre dans le code. Les styles plus spécifiques et plus récents ont la priorité.

16. **Qu'est-ce que le padding ?**
    Le padding est l'espace entre le contenu d'un élément et sa bordure.

17. **Qu'est-ce que la marge ?**
    La marge est l'espace autour de l'extérieur de la bordure d'un élément.

18. **Quelle est la différence entre `padding: 25px;`, `padding: 25px 15px;` et `padding: 5px 15px 8px;` ? Expliquez comment les valeurs de padding sont appliquées à un élément sur tous les côtés (haut, bas, gauche et droite).**
    - `padding: 25px;` applique 25 pixels de padding sur tous les côtés.
    - `padding: 25px 15px;` applique 25 pixels de padding en haut et en bas, et 15 pixels à gauche et à droite.
    - `padding: 5px 15px 8px;` applique 5 pixels en haut, 15 pixels à gauche et à droite, et 8 pixels en bas.

19. **Quelles valeurs seront appliquées à quels côtés pour cette règle CSS `margin: 4px 8px 6px 5px;` ?**
    - 4px en haut
    - 8px à droite
    - 6px en bas
    - 5px à gauche

20. **Explication de l'ordre de priorité en CSS.**
    L'ordre de priorité en CSS est déterminé par la spécificité et la source des styles. Les règles les plus spécifiques et les plus récentes l'emportent. La spécificité est calculée en fonction du type de sélecteur utilisé (inline styles, IDs, classes, éléments). Les styles en ligne ont la priorité maximale, suivis par les IDs, puis les classes, et enfin les éléments. En cas de conflit, la dernière règle définie dans le code a la priorité.
