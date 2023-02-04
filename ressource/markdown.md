# markdown

[doc ici](https://www.ionos.fr/digitalguide/sites-internet/developpement-web/markdown/)

[site officel](https://www.markdownguide.org/)

[cheat-sheet](https://www.markdownguide.org/cheat-sheet/)


## sommaire 


[caractère](#caractère-↑)<br>
[titre](#titre-1)<br>
[liste numéroté](#liste-↑)<br>
[Les citations](#citation-↑)<br>
[code suivant la langue de programation](#code-suivant-le-langage-de-programmation-↑)
[les listes](#hyperliens-↑)<br>
[case à cocher](#case-à-cocher-↑)<br>
[caractères spéciaux](#caractères-spéciaux-↑)<br>
[image](#images-↑)<br>
[tableau](#les-tableaux-↑)<br>
[note de bas de page](#les-notes-de-bas-de-page-↑)<br>







<hr>

# caractère [&uarr;](#sommaire)


*italique* :  `*italique*`  ou `_italique_`

**gras** : `**gras**`  ou `__gras__`

~~barré~~ : `~~barré~~`

<ins>_souligné</ins> : ``<ins>_souligné</ins> ``

exposant 2<sup>2</sup> : ``2<sup>2</sup> ``

indice  h<sub>2</sub>o : ``h<sub>2</sub>o``

<hr>

## titre [&uarr;](#sommaire)
[sommaire](#sommaire)
#  Titre 1 
## Titre 2
###  Titre 3
#### Titre 4
#####  Titre 5
###### Titre 6

```
#  Titre 1
## Titre 2
###  Titre 3
#### Titre 4
#####  Titre 5
###### Titre 6
```

<hr>


<hr>

## liste  [&uarr;](#sommaire)


- Liste tiret 1
- Liste tiret 2
- Liste tiret 3

+ Liste plus 1
+ Liste plus 2
+ Liste plus 3

* Liste asterisque 1
* Liste asterisque 2
* Liste asterisque 3



 ```
- Liste tiret 1
- Liste tiret 2
- Liste tiret 3

+ Liste plus 1
+ Liste plus 2
+ Liste plus 3

* Liste asterisque 1
* Liste asterisque 2
* Liste asterisque 3

 ```
{#liste numéroté}
{#listeNumerote}
 
 
 
1. Liste 1
2. Liste 2
3. Liste 3


 ```
1. Liste 1
2. Liste 2
3. Liste 3

 ```
<hr>

## case à cocher   [&uarr;](#sommaire)


[ ] A

[x] B

[ ] C

```
[ ] A

[x] B

[ ] C

```

## citation [&uarr;](#sommaire)



>Ceci est une **zone en retrait**.<br>
>La zone continue ici

```
>Ceci est une **zone en retrait**.<br>
>La zone continue ici
```


>Ceci est une **zone en retrait**. <br>
>La zone continue ici

>Ceci est une autre **zone de retrait**.<br>
Cette zone continue également dans la ligne suivante.<br>
Cependant, cette ligne n’est plus en retrait

```
>Ceci est une **zone en retrait**.<br>
>La zone continue ici<br>

>Ceci est une autre **zone de retrait**.<br>
Cette zone continue également dans la ligne suivante.<br>
Cependant, cette ligne n’est plus en retrait<br>
```


Code

C’est le `code`.

```
C’est le `code`.
```


c'est le code ``backtique ` ``

```
c'est le code ``backtique ` ``
```


Si votre codage renferme déjà l’apostrophe inversée, vous devez précéder la zone de code de deux fois ce caractère. Dans ce cas, Markdown n’interprétera pas l’apostrophe inversée comme une balise.





### code suivant le langage de programmation  [&uarr;](#sommaire)

exemple html 

```html
<div>
    tiitit
</div>

```


## hyperliens  [&uarr;](#sommaire)

Ici ce qui suit [Lien](https://example.com/ "titre de lien optionnel").

```
Ici ce qui suit [Lien](https://example.com/ "titre de lien optionnel").

```
<https://example.com> lien automatique  par`<>`

`https://example.com` pas de lien par backtique

```
<https://example.com> lien automatique  par`<>`

`https://example.com` pas de lien par backtique

```


## Images  [&uarr;](#sommaire)
![Ceci est un exemple d’image](./image/markdown_logo.jpeg)


```
![Ceci est un exemple d’image](./image/markdown_logo.jpeg)

```

image + lien 




[![Ceci est un exemple d’image](./markdown.md)](https://www.markdownguide.org/)



## Les tableaux  [&uarr;](#sommaire)
|cellule 1|cellule 2|
|--------|--------|
|    A    |    B    |
|    C    |    D    |


```
|cellule 1|cellule 2|
|--------|--------|
|    A    |    B    |
|    C    |    D    |


```

<hr>

## Les notes de bas de page  [&uarr;](#sommaire)


Dans le texte ordinaire [^1] vous pouvez facilement placer des notes de bas de page [^2]

[^1]: Vous trouverez ici le texte de la note de bas de page.

[^2]: **Note de page de page** peut aussi être *formatée*.
Et celles-ci comprennent même plusieurs lignes

L’endroit où vous l’implantez dans le texte n’a pas d’importance. Markdown le placera dans tous les cas à la fin du document. Pour clore l’annotation et poursuivre la rédaction du corps de texte, ajoutez tout simplement une ligne vierge.


<hr>

## caractères spéciaux  [&uarr;](#sommaire)


A & B
&alpha;
1 < 2

```
A & B
&alpha;
1 < 2

```

```html 
<p>
```

>Astérisque : *
>Trait d’union : -
>Souligné : _
>Parenthèses : ()
>Crochets : []
    Accolades : {}
    Point : .
    Point d’exclamation : !
    Dièse : #
    Accent grave : `
    Barre oblique inversée : \


utiliser Backslash pour annuler le caractère

