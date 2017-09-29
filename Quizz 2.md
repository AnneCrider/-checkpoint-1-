## Qu'est ce qu’un navigateur ?

```
Un navigateur permet à un utilisateur de consulter une page web. 
Il est l'interface entre l'ordinateur de l'utilisateur et un serveur qui va gérer la requête et renvoyer l'information sur l'ordinateur de l'utilisateur.



```

________________________________________________________________________________________

## Définissez l’ensemble HTML/CSS/JavaScript et leur utilités.


```
Ce sont des langages informatiques qui permettent la création de sites web dynamiques.
HTML permet d'écrire le squelette du site.
CSS permet la mise en forme des différents éléments.
JS permet de faire des animations dynamiques.

```
________________________________________________________________________________________


## Qu’est-ce qu’un élément HTML ? Un attribut ?

```
Un élément HTML permet d'écrire du contenu dans une page web, il est inscrit dans des balises.
Un attribut est une balise qui donne un comportement donné à un élément. (par exemple la balise <form>)



```
________________________________________________________________________________________


## Dans quels cas utilisez-vous des id au lieu des classes (et vice-versa) ?


```
Une id permet de sélectionner un élément de façon unique alors que les classes permettent une sélection générale.



```
________________________________________________________________________________________


## Qu’est-ce que EcmaScript ?

```
Langage de script de JS



```

________________________________________________________________________________________

## Pourquoi est-il important de bien indenter vos fichiers ?

```

C'est important pour la lecture et la bonne compréhension du code.


```
________________________________________________________________________________________


## Quelle est la différence entre margin et padding ? 

```

Le padding est à l'intérieur de l'élément alors que le margin est autour.


```

________________________________________________________________________________________


## Citez au moins 3 types de positionnement en CSS et expliquer leurs rôles.

```
'in-line' = les éléments sont alignés
'float'= les éléments se positionnent librement les uns par rapport aux autres
'relative'= les éléments se positionnent par rapport à un élément 'absolute'
'text-align' permet de mettre en forme le texte


```
________________________________________________________________________________________

## Qu’est-ce qu’une variable ?

```
une variable est un élément auquel on peut donner différentes valeurs



```
________________________________________________________________________________________


## Citez le plus de types JavaScript possible et définissez les rapidement.


```
''= chaine de caractères
var= variable
cont=constante
function()=fonction
[]=tableau



```
________________________________________________________________________________________


##  À quoi sert le mot-clef “if” ?

```
"if" permet de poser des conditions de réalisations d'une fonction



```

________________________________________________________________________________________

##  Définissez l’objet XHR en JavaScript, son abréviation. À quoi sert-il ?


```




```

________________________________________________________________________________________

## Qu’est-ce qu’une requête HTTP ? 

```
c'est un protocole de demande au serveur



```
________________________________________________________________________________________


## Quelle sont les deux types de requêtes permettant de récupérer et d’envoyer de la donnée sur un serveur HTTP ?

```
GET
POST


```

________________________________________________________________________________________

## À quoi sert le Header d’une requête ? Le “Content-Type” ?

```
le 'header' est l'en-tête de la demande et va envoyer le type de requête
le 'content-type' contient la requête en elle-même



```
________________________________________________________________________________________


## Donnez au moins 3 codes de réponse HTTP et définissez les.


```
300 redirection
404 erreur sur la page
504 erreur de serveur

```
________________________________________________________________________________________


## Définissez les rôles de Scrum Master et Product Owner.


```
Le Scrum Master est le garant des bonnes pratiques de Scrum et vérifie que le Product Owner les applique

Le Product Owner est à l'origine des différents sprints,  va regrouper les user stories sur le backlog product, les assigner en différentes taches et faire le lien avec le client. 

```
________________________________________________________________________________________


## Citer 4 commandes utilisées avec GIT et expliquer leurs rôles.
```
'git clone' permet de cloner un repository sur Github
'git add.' permet d'ajouter un fichier sur git
'git branch' crée une branche 
'git remote -v' crée un commit 



```
________________________________________________________________________________________


## Expliquer le code suivant et indiquer le résultat retourné par la fonction.

```
function counter(){
        const sentence = "Validation de la première phase";
        const words = sentence.split(' ');
        let count = 0;


        for (let i = 0; i < words.length; i++) {
            var mot = words[i];
            count += mot.length;
        }
        return count;
}
```
```On a une fonction 'compteur'
On assigne une constante 'sentence' qui est une chaine de caractères.
On assigne une constante 'words' qui est une fonction 'split' qui permet de découper une chaine de caractères et de la mettre en tableau.
On démarre le compteur à 0 et on l'incrémente de 1 jusqu'au nombre de mots dans la chaine de caractères.
On assigne une variable 'word' qui est le tableau donné par la fonction.

On affiche le nombre de fois que le compteur a tourné.




```
________________________________________________________________________________________


## Algo 

Ecrire l’algorithme d’une fonction prenant en paramètre 2 arguments : le premier est une chaîne de caractère et le second correspondant au caractère recherché. Cette fonction retourne le nombre de fois que le caractère recherché est rencontré dans la chaîne de caractères.
Ex. 
   * chaîne : ‘examen’, caractère : ‘x’ => 1
   * chaîne : ‘wild code school’, caractère : ‘w’ => 1



```
function search(){
    const sentence = 'une chaine de caractères';
    const word = 'x';
    let count = 0;

    for (let i=0; i<=sentence.length; i++){
        
        count += 

    }
    return count;
}



```


