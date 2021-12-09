Zoom 25%

```html
<html>
<head>
</head>
<body>
    <header>
        <nav>
        </nav>
    </header>

    <main>
        <section class="search"></section>
        <section class="result"></section>
        <section class="popular"></section>
        <section class="activities"></section>
        <footer></footer>
    </main>
</body>
</html>
```

Zoom 75%

```html
<html>
    <head>
    </head>

<body>
    <header>
        <nav>
        </nav>
    </header>

    <main>
        <section class="search"></section>
        <section class="result"></section>
        <section class="popular"></section>
        <section class="activities"></section>
        <footer></footer>
    </main>
</body>
</html>
```

Zoom 90%

```html
<html>
    <head>
    </head>

<body>
    <header>
        <nav>
            <img class="logo">
            <div class="nav-links">
                <ul>
                    <li></li>
                    <li></li>
                </ul>
            </div>
        </nav>
    </header>

    <main>
        <section class="search">
            <h1></h1>
            <h3></h3>
            <div class="search-input">
                <input>
                <button></button>
                <button></button>
            </div>
            <div class="filters">
                <span></span>
                <div class="filter">
                    <i></i>
                    <span></span>
                </div>
                <div class="filter">
                    <i></i>
                    <span></span>
                </div>
                <div class="filter">
                    <i></i>
                    <span></span>
                </div>
                <div class="filter">
                    <i></i>
                    <span></span>
                </div>
            </div>
        </section>
        <div class="infos">
            <i></i>
            <span></span>
        </div>
        <section class="result-city">
            <h2>

            <!-- 6 articles -->
            <article class="city-card">
                <a>
                    <img>
                    <div class="city-card-details">
                        <div class="rating"></div>
                    </div>
                </a>
            </article>

        </section>
        
        <section class="result-popular">

            <!-- 3 articles -->
            <article class="popular-card">
                <a>
                    <img>
                    <div class="popular-card-details">
                        <div class="rating">
                        </div>
                    </div>
                </a>
            </article>
        </section>

        <section class="activities">
            <h2>
            <!-- 6 articles -->
            <article class="activities-card">
                <a>
                    <img>
                    <h3>
                </a>
            </article>
            <article class="activities-card">
                <a>
                    <img>
                    <h3>
                </a>
            </article>
            <article class="activities-card">
                <a>
                    <img>
                    <h3>
                </a>
            </article>
            <article class="activities-card">
                <a>
                    <img>
                    <h3>
                </a>
            </article>
            <article class="activities-card">
                <a>
                    <img>
                    <h3>
                </a>
            </article>
            <article class="activities-card">
                <a>
                    <img>
                    <h3>
                </a>
            </article>
        </section>
        <footer>
            <div class="about">
                <h6></h6>
                <ul>
                    <li>
                        <a></a>
                    </li>
                </ul>
            </div>
            <div class="our-accomodations">
                <h6></h6>
                <ul>
                    <li>
                        <a></a>
                    </li>
                </ul>
            </div>
            <div class="help">
                <h6></h6>
                <ul>
                    <li>
                        <a></a>
                    </li>
                </ul>
            </div>
        </footer>
    </main>
</body>
</html>
```

CMD + K relacher et V  

<pre>
    align-items
    y
    |
    |
    |
    |
    |
_____logo____________________div_ x justify-content
    |
    |
    |
    |
    |
    
</pre>
``
/* .menu-link:visited {
    
} */

/* 

Unités
px : fixes
% : relatif au parent
vh, vw : unités relatives à la taille du viewport (zone d'affichage de la page)
em, rem, ch : unités relatives à la taille de la police / des caractères




Les propriétés d'alignement ont commencé sous forme de liste dans Flexbox, mais elles ont maintenant leur propre spécification et s'appliquent à d'autres contextes de layout. Quelques points-clés vous aideront à vous rappeler comment les utiliser dans Flexbox:

justify- l'axe principal et align- l'axe transversal;
Pour utiliser align-content et justify-content, vous avez besoin d'espace disponible.
Les propriétés align-content et justify-content traitent les éléments en tant que groupe, en partageant de l'espace. Par conséquent, vous ne pouvez pas cibler un élément individuel et il n’existe donc pas d’alignement de type -self pour ces propriétés;
Si vous souhaitez aligner un élément ou diviser un groupe sur l'axe principal, utilisez les marges automatiques pour le faire.
La propriété align-items définit toutes les valeurs align-self en tant que groupe. Utilisez align-self sur le flex enfant pour définir la valeur d'un élément individuel.
*/

 <!-- kebab-case css
        snake_case
        camelCase js -->


/* gap: valeur1 valeur2;
flex: grow shrink basis;
object-fit: cover;
 */

 <!-- Article card example
<div class='flex-row'>
    <!-- Card -->
    <div class='flex-column'>
        <img style='height: 150px; width: 100%'/>
        <!-- Description (title, price...) -->
        <div style='padding: 3px 6px;'>
            <p>Nom de l'hôtel</p>
            <p>prix</p>   
            <p>étoiles</p>   
        </div> 
    </div>
</div>
</html> -->

CMD shift L pour selectionner et effacer en meme temps

<!-- CMD+Shift+P go to maching pair -->
        <!---------------------------- ACTIVITÉS  ------------------------>

            <!-- <section class="activity-section">
                <h2></h2>
                <div class="activity-container">
                    <div class="activity-column">
                        <article class="activity-card">
                            <img>
                            <h3></h3>
                        </article>
                    </div>
                    <div class="activity-column">
                        <article class="activity-card">
                            <img>
                            <h3></h3>
                        </article>
                        <article class="activity-card"></article>
                        
                    </div>
                    <div class="activity-column">
                        <article class="activity-card"></article>
                    </div>
                    <div class="activity-column">
                        <article class="activity-card"></article>
                        <article class="activity-card"></article>
                    </div>
                </div>
            </section> -->

            /*
Section container : 600px
    Colonne : height : 100%
        Lien : height : 100%
            Article : height: 100%

Section container : 600px
    Colonne : height : 100%
        Lien 1 : height : 55%
            Article 1: height: 100% - 1000px
                Image article 1 90% - 900px
                h3 Article 1    10% - 100px - font : 20px

            Article 1: height: 100% - 300px
                Image article 1 90% - 270px
                h3 Article 1    10% - 30px - font-size : 40px


        [Reste : 10% d'espace entre Lien 1 et Lien 2]
        Lien 2 : height : 35%
            Article 2: height: 100%


        Dans ma carte, je veux que le h3 ait toujours la place de s'afficher.
        Pour ça je peux définir une hauteur en pixels qui soit plus grande que la taille du texte.
        Si mon h3 a une font-size de 30px, il faut que la height fasse minimum 30px.
        Le problème est que si je mets 10% de height au h3, parfois ça peut descendre en dessous de 30px (si ma carte est très petite)
        
*/