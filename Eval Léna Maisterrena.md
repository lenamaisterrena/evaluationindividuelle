Évaluation individuelle

## Programmation - Coaching

```
Nom : Maisterrena
Prénom : Léna
URL de votre compte Github : https://github.com/lenamaisterrena
```

## Déroulé et fonctionnement. 

L'évaluation est à faire sur [Typora](https://typora.io/). Les réponses sont à écrire dans les blocks de code. 
Pour la partie Ruby, testez votre code sur [repl.it](https://repl.it/) et copiez le dans les blocks de code prévu à cet effet. 
Une fois fini, pushez votre feuille sur Github, dans un nouveau repository que vous appelerez "evaluation-inseec".
L'évaluation est individuelle et durera 1h30. Elle intègre des notions d'HTML, CSS, Ruby et computer science. 

![alt](https://media.giphy.com/media/26xBBfd0ii1khakpy/giphy.gif)

## Quelques mises en garde.

Je connais très bien ce merveilleux site qu'est Wikipédia. Je vous saurais gré de ne pas me remplir certaines questions avec les définitions de Wikipédia. Accessoirement, je sais aussi faire une recherche Google. Si j'ai un doute, je n'hésiterais pas rechercher "Qu'est-ce qu'une API" et comparer les définitions en tête de recherche avec les votre. Si je trouve une similarité trop grande et que je doute de votre bonne foi, je n'hésiterais pas à mettre 0 à la question. 
Pareil pour la copie sur les voisins. Si c'est trop gros et que j'ai un doute trop prononcé... 🔫

![alt](https://media.giphy.com/media/BtedgmzGNCiuk/giphy.gif)



------

### 1. Avec vos mots, expliquez l'interaction client-serveur

```t
C'est le circuit numérique entre un ordinateur (client) qui demande un accès et le serveur hébergeant qui répond en fournissant l'accès au client.
```



 ### 2. HTML est un langage côté... 	

```
client
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne --> 
<html>
    <head>
        <meta charset="utf-8" />
        <title>titredusite</title>
    </head>

    <body>
    <h3>
        Ceci est un site de chaussures 
        </h3> 
    </body>
</html>
```



### 4. Changez la couleur du texte "J'adore la programmation" en vert en utilisant du CSS.

```html
<div>
   <p>J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
p
{
    color: #32CD32;
}

OU

p
{
    color: green;
}
```



### 5. Qu'est-ce que Bootstrap ?

```
Une bibliothèque de codes en accès libre pour le design des sites internet.
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <title>titredusite</title>
       <!-- Bootstrap CSS -->
  <link href="document/bootstrap/css/bootstrap.min.css" rel="stylesheet">
    </head>

    <body>
    <h3>
        Ceci est un site de chaussures 
        </h3> 
    </body>
</html>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
<div class="container">
  <div class="row">
    <div class="col-sm-4">
      Google
    </div>
    <div class="col-sm-4">
      Microsoft
    </div>
    <div class="col-sm-4">
       Apple
    </div>
  </div>
</div>
```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div class="container">
  <div class="row">
    <div class="col-sm-4">
      <img src= "document/logogoogle.jpg">
    </div>
    <div class="col-sm-4">
     <img src= "document/logomicrosoft.jpg">
    </div>
    <div class="col-sm-4">
        <img src= "document/logoapple.jpg">
    </div>
  </div>
</div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<div class="container">
  <div class="row">
    <div class="col-sm-4">
      <a href="https://www.google.com/search?q=logo+google&rlz=1C5CHFA_enFR817FR821&source=lnms&tbm=isch&sa=X&ved=0ahUKEwitvqjlh9TfAhWizIUKHTSjBz0Q_AUIDigB&biw=1129&bih=561#imgrc=qjMmE0-CwMcCZM:">
    <img src= "bureau/logogoogle.jpg">
       </a>
    </div>
      
    <div class="col-sm-4">
       <a href="https://www.google.com/search?q=logo+microsoft&rlz=1C5CHFA_enFR817FR821&source=lnms&tbm=isch&sa=X&ved=0ahUKEwjj2OHah9TfAhVSKBoKHTMgAGgQ_AUIDigB&biw=1129&bih=561#imgrc=hiC9djRMjPuC4M:">
       <img src= "bureau/logomicrosoft.jpg">
       </a>
    </div>
      
    <div class="col-sm-4">
            <a href="https://www.google.com/search?rlz=1C5CHFA_enFR817FR821&biw=1129&bih=561&tbm=isch&sa=1&ei=6kUvXL3qMayKlwSK9Y7ACg&q=logo+apple+jpg&oq=logo+apple+jpg&gs_l=img.3..0j0i8i30l2.22289.24469..24717...0.0..0.199.1976.1j13......1....1..gws-wiz-img.......0i8i7i30j0i7i30.jqcyU5_hVK0#imgrc=InpoHbAht1lMHM:">
       <img src= "bureau/logoapple.jpg">
       </a>
    </div>
  </div>
</div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
serveur
```



### 11. Listez-moi tous les types de données que vous connaissez en donnant le nom et la syntaxe.

```
 # Ceci est un 
```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby

```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby
a=674
b=311
# Le résultat attendu est 52. 
```



### 14. Qu'est-ce qu'une gem ? 

```texte
C'est un fichier contenant un programme et son code fournit par Ruby
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
Une interface de programmation, on y accède sur le web.
```



### 16. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur

hour = 15

# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom

# sinon
	# j'écris mon code permettant de dire Bonsoir prénom

```



### 17. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]


```



### 18. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

