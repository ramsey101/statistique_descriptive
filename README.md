[DÉCOUVREZ LA STATISTIQUE DESCRIPTIVE](https://fr.wikipedia.org/wiki/Statistique_descriptive )
 ![Image](https://github.com/daniel497/statistique_descriptive/blob/master/head.jpg)



[NAN DATA ANALYST](https:nan.ci)



### Préambule

```js
Le cours a pour but d’initier les étudiants aux principes de base de la statistique.
Le cours vise principalement à introduire et faire méditer les concepts fondamentaux et
méthodes élémentaires de la statistique pour permettre un apprentissage autonome ultérieur
de méthodes complémentaires.

On veut développer le sens critique nécessaire lors de la mise en œuvre et de l’interpré-
tation d’un traitement statistique. Pour cela, on introduira et utilisera un cadre mathéma-
tique rigoureux. Nous fournirons autant d’exemples et de figures nécessaires afin d’obtenir
une meilleure compréhension du cours.

La statistique descriptive a pour but d’étudier un phénomène à partir de données. Cette
description se fait à travers la présentation des données (la plus synthétique possible), leur
représentation graphique et le calcul de résumés numériques.
```

```console
La place de ce cours dans le future métier des étudiants :
```
- Analyse des données (outils scientifiques permettant de résumer un ensemble de
    données afin de mettre en évidence l’information).
- Simulations (processus stochastique - variable temporelle)
- Prédiction et décisions (probabilités de risque ou d’occurrence)




**Symboles et Notations**


- Symbole Signification & signification

```js
[ ] La partie entière.

Card(Ω) Le cardinal : nombre d’éléments de l'ensemble Ω.

:= Est défini comme étant (symbole d’affectation). 

N Ensemble des nombres entiers naturels.

Z Ensemble des nombres entiers relatifs.

R Ensemble des nombres réels.

R^2 Ensemble des couples de nombres réels.

n
∑ = La somme pourivariant de 1 à n.
i 

V.S La variable statistique

Me La médiane.

Me+ Me par valeur supérieure.

Me− Me par valeur inférieure.

M 0 Le mode.

_
x La moyenne d’une série statistique X.

σ X L’écart-type de X.

Var(X) La variance de X.

Cov(X,Y) La covariance entre les variables X et Y.

ρXY Le coefficient de corrélation entre les variables X et Y.

F(x) La fonction s’appelle la fonction de répartition du caractère X

```




## Chapitre 1

# Généralités sur la statistique

```console
La statistique est l’étude de la collecte de données, leur analyse, leur traitement, l’in-
terprétation des résultats et leur présentation afin de rendre les données compréhensibles
par tous. C’est à la fois une science, une méthode et un ensemble de techniques.

L’analyse des données est utilisée pour d’écrire les phénomènes étudiés, faire des pré-
visions et prendre des décisions à leur sujet. En cela, la statistique est un outil essentiel
pour la compréhension et la gestion des phénomènes complexes.

Les données étudiées peuvent être de toute nature, ce qui rend la statistique utile
dans tous les champs disciplinaires et explique pourquoi elle est enseignée dans toutes les
filières universitaires, de l’économie à la biologie en passant par la psychologie et bien sûr
les sciences de l’ingénieur. La statistique consiste à :
```

- Recueillir des données.
- Présenter et résumer ces données.
- Tirer des conclusions sur la population étudiée et d’aider à la prise de décision.
- En présence de données dépendant du temps, nous essayons de faire de la prévision.

### 1.1 Vocabulaire

```console
Les statistiques consistent en diverses méthodes de classement des données tels que les
tableaux, les histogrammes et les graphiques, permettant d’organiser un grand nombre de
données. Les statistiques se sont développées dans la deuxième moitié du XIXe siècle dans
le domaine des sciences humaines (sociologie, économie, anthropologie, ...). Elles se sont
dotées d’un vocabulaire particulier.
```


#### 1.1.1 Épreuve statistique

```console
Les statistiques descriptives visent à étudier les caractéristiques d’un ensemble d’ob-
servations comme les mesures obtenues lors d’une expérience. L’expérience est l’étape pré-
liminaire à toute étude statistique. Il s’agit de prendre "contact" avec les observations. De
manière générale, la méthode statistique est basée sur le concept suivant.
```

**Définition 1**

```console
L’épreuve statistique est une expérience que l’on provoque.
```
- Exemple 1 (La durée de vie des lampes)
```js


Imaginons le cas suivant : un fabricant d’ampoules électriques ayant le choix entre
4 types de filaments se propose d’étudier l’influence de la nature du filament sur la
durée de vie des ampoules fabriquées. Pour ce faire, il va faire fabriquer 4 échantillons
d’ampoules identiques, sauf en ce qui concerne le filament, faire brûler les ampoules
jusqu’à extinction, puis comparer les résultats obtenus.
```
#### 1.1.2 Population

```console
En statistique, on travaille sur des populations. Ce terme vient du fait que la démo-
graphie, étude des populations humaines, a occupé une place centrale aux débuts de la
statistique, notamment au travers des recensements de population. Mais, en statistique,
le terme de population s’applique à tout objet statistique étudié, qu’il s’agisse d’étudiants
(d’une université ou d’un pays), de ménages ou de n’importe quel autre ensemble sur lequel
on fait des observations statistiques. Nous définissons la notion de population.
```

**Définition 2**

```console
On appelle population l’ensemble sur lequel porte notre étude statistique. Cet ensemble
est noté Ω.
```

- Exemple 2

```console
 On considère l’ensemble des étudiants de la section A. On s’intéresse aux_
 nombre de frères et sœurs de chaque étudiant. Dans ce cas : 
```

```js
            Ω = ensemble desétudiants.
```

```console
Si l’on s’intéresse maintenant a la circulation automobile dans une ville, la po-_
pulation est alors constituée de l’ensemble des véhicules susceptibles de circuler_
dans cette ville à une date donnée. Dans ce cas :
```

```js
            Ω = ensemble des véhicules.
```

#### 1.1.3 Individu (unité statistique)

```console
Une population est composée d’individus. Les individus qui composent une population
statistique sont appelés unités statistiques.

```
**Définition 3**

```console
On appelle individu tout élément de la population Ω , il est noté ω ( ω dans Ω ).
```

_Remarque 1_

```console
L’ensemble Ω peut être un ensemble de personnes, de choses ou d’animaux...
L’unité statistique est un objet pour lequel nous sommes intéressés à recueillir de l’in-
formation.
```

- Exemple 3

```js
Dans l’exemple indiqué ci-dessus, un individu est tout étudiant de la section.
Si on étudie la production annuelle d’une usine de boîtes de boisson en métal
(canettes). La population est l’ensemble des boîtes produites durant l’année et 
une boîte constitue un individu.
```

#### 1.1.4 Caractère (variable statistique)

```console
La statistique « descriptive », comme son nom l’indique cherche à décrire une po-
pulation donnée. Nous nous intéressons au caractéristique des unités qui peuvent prendre
différentes valeurs.

```

**Définition 4**

```console
On appelle caractère (ou variable statistique, dénotée V.S) toute application
``` 
```js
                         X: Ω→C.
```

```console
L’ensemble C est dit : ensemble des valeurs du caractère X (c’est ce qui est mesuré ou
observé sur les individus)
```


- Exemple 4

```js
Taille, température, nationalité, couleur des yeux, catégorie socioprofessionnelle ...
```

_Remarque 2_

```js
Soit Ω un ensemble. On appelle et on note Card (Ω) , le nombre d’éléments de Ω.
           Card (Ω) := nombre d’éléments de Ω =N. 
```

#### 1.1.5 Modalités

```console
Les modalités d’une variable statistique sont les différentes valeurs que peut prendre
celle-ci.

```
- Exemple 5

```js
Variable est " situation familiale "
Modalités sont " célibataire, marié, divorcé "

Variable est" statut d’interrupteur "
Modalités sont " 0 et 1 ".

Variable est " catégories socio-professionnelles "
Modalités sont " Employés, ouvriers, retraités,... "
```

```console
Les modalités sont les différentes situations dans lesquelles les individus peuvent se
trouver à l’égard du caractère considéré.
```

### 1.2 Types des caractères

```console
Nous distinguons deux catégories de caractères : les caractères qualitatifs et les carac-
tères quantitatifs.
```
![Image](https://github.com/daniel497/statistique_descriptive/blob/master/image1_2.jpg)

 

#### 1.2.1 Caractère qualitatif

```console
Les caractères qualitatifs sont ceux dont les modalités ne peuvent pas être ordonnées,
c’est-à-dire que si l’on considère deux caractères pris au hasard, on ne peut pas dire de l’un
des caractères qu’il est inférieur ou égal à l’autre. Plus précisément, nous avons la définition
suivante.
```

**Définition 5**

```console
Les éléments de C sont représentés par autre chose que des chiffres.
```

- Exemple 6

```js
L’état d’une maison : on peut considérer les modalités suivantes
- Ancienne.

- Dégradée.

- Nouvelle.

- Rénovée.
```

#### 1.2.2 Caractère quantitatif

```console
Les caractères quantitatifs sont des caractères dont les modalités peuvent être ordon-
nées. Ainsi, l’âge, la taille de vie ou le salaire d’un individu sont des caractères quantitatifs.
Donc, nous avons la définition suivante.

```
**Définition 6**

```console
L’ensemble des valeurs est représenté par des chiffres. De même, il est partagé en deux
sortes de caractères, discret et continu (voir l’exemple).
```

- Exemple 7

```js
Le salaire d’employés d’une usine.
    Modalités :10000 da ,20000 da
    Type : Discret.
La rigidité des ressorts.
    Modalités :[10,20] N/m
    Type : continu.
```

```console
En général, la variable quantitative discrète est une variable ne prenant que des valeurs
entières (plus rarement décimales). Le nombre de valeurs distinctes d’une telle variable
est habituellement assez faible. Citons, par exemple, le nombre de maisons par quartier
d’une ville. Une variable quantitative est dite continue lorsque les observations qui lui sont
associées ne sont pas des valeurs précises, mais des intervalles. C’est le cas lorsque nous
avons un grand nombre d’observations distinctes.

La statistique descriptive a pour objectif de synthétiser l’information contenue dans
les jeux de données au moyen de tableaux, figures ou résumés numériques. Les variables
statistiques sont analysées différemment selon leur nature (quantitative, qualitative).
```

## Chapitre 2

# Étude d’une variable statistique discrète


```console
Le caractère statistique peut prendre un nombre fini raisonnable de valeurs (note,
nombre d’enfants, nombre de pièces, ...). Dans ce cas, le caractère statistique étudié est
alors appelé un caractère discret.
```

```console
Dans toute la suite du chapitre, nous considérons la situation suivante :
```

```js
                X: Ω→{x 1 ,x 2 ,...,x n },
```

```console
avec Card(Ω) :=Nest le nombre d’individus dans notre étude.

Nous allons utiliser souvent l’exemple ci-dessous pour illustrer les énoncés de ce cha-
pitre.

```

- Exemple 8

```console
Une enquête réalisée dans un village porte sur le nombre d’enfants à charge par famille.
On note X le nombre d’enfants, les résultats sont données par ce tableau :
```

| xi | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 
|----|---|---|---|---|---|---|---|
| ni(Effectif) | 18 | 32 | 66 | 41 | 32 | 9 | 2 |


```console
- Ω ensemble des familles.
- ω une famille.
- X nombre d’enfants par famille
```

```js
                    X:ω→X(ω).
```


```console
On lit, à la famille ω , on associe X(ω) = le nombre d’enfants de cette famille.
```

### 2.1 Effectif partiel - effectif cumulé

```console
On étudie ici un caractère statistique numérique représenté par une suitex _i_ décrivant
la valeur du caractère avecivarie de 1 àk.
```

#### 2.1.1 Effectif partiel (fréquence absolue)


**Définition 7**

```js
Pour chaque valeur x i, on pose par définition
                 n i = Card {ω∈Ω : X(ω) =x i }.
                 
n i: le nombre d’individus qui ont le même x i, ça s’appelle effectif partiel de x i.
```

![Image](https://github.com/daniel497/statistique_descriptive/blob/master/image2_1.jpg)


```
Figure2.1:Le nombre d’individus qui prennent la valeurx i.
```

- Exemple 9

```js
Dans l’exemple précédent, 66 est le nombre de familles qui ont 2 enfants.
```

| xi |··· | 2 | ··· |
|----|----|---|-----|
| n i(Effectif)| ··· | 66 | ··· |


#### 2.1.2 Effectif cumulé


**Définition 8**

```console
Pour chaque valeur x i, on pose par définition
```
```js
               N i = n1 + n2 + ... + ni
```
```console
L’effectif cumulé N id’une valeur est la somme de l’effectif de cette valeur et de tous
les effectifs des valeurs qui précèdent.
```

- Exemple 10

```console
Dans l’exemple précédent : 50 est le nombre de familles qui ont un nombre d’enfant
inférieur à 1. Nous le regardons dans le tableau suivant :
```

| xi | 0 | 1 | 2 | 3 | 4 | 5 | 6 |
|----|---|---|---|---|---|---|---|
|Ni | 18 | 50 | 116 | 157 | 189 | 198 | 200 |


**Interprétation** :

```console
N i est le nombre d’individus dont la valeur du caractère est inférieur
ou égale à x i. De ce fait, l’effectif total est donné par
```
```js
                              n
                   N=card{Ω) =∑ ni
                             i=1
```
```console
Dans notre exemple précédent, nous avonsN= 200.
```

### 2.2 Fréquence partielle - Fréquence cumulée

```console
Typiquement les effectifsn i sont grands et il est intéressant de calculer des 
grandeurs permettant de résumer la série. 

```

#### 2.2.1 Fréquence partielle (fréquence relative)


**Définition 9**

```console
Pour chaque valeur x i, on pose par définition
```
```js
                   f i :=n i/N

```


```console
f is’appelle la fréquence partielle de x i. La fréquence d’une valeur est le rapport de
l’effectif de cette valeur par l’effectif total.
```

_Remarque 3_

```console
On peut remplacer f ipar f i × 100 qui représente alors un pourcentage.
```

**Interprétation**:
```js
f i = est le pourcentage des ω tel queX(ω) =x i.

```
- Exemple 11

```js
Dans l’exemple précédent, 0 ,33 := il y a 33 % de familles dont le nombre d’enfants égale
à 2. Ce pourcentage est calculé de la façon suivante ( N= 200 ) :
```


| xi | ··· | 2 | ··· |
|----| --- |---| --- |
| ni(Effectif)| ··· | 66 |···|
| Ni(Effectif)| ··· | 200/66 = 0. 33 | ··· |

```console
Nous pouvons conclure la propriété suivante.

```
- Proposition 1
  - Soit f idéfini comme précédemment. Alors,
```js
                   n
                   ∑ fi = 1
                   i =1


```


#### 2.2.2 Fréquence cumulée


**Définition 10**

```console
Pour chaque valeur x i, on pose par définition
```
```js
                    F i = f 1 + f2 +...+ fi. 
```
```console
La quantité F is’appelle la fréquence cumulée de x i.
```

**Interprétation** :

```js
F i =est le pourcentage desωtel que la valeur X(ω)est inférieure
ou égale àx i.

```
- Exemple 12

```js
Dans l’exemple précédent, 0. 785 représente 78 .5% de familles dont le nombre d’enfants
est inférieur ou égale à 3.
```



### 2.3 Représentation graphique des séries statistiques

```console
On distingue les méthodes de représentation d’une variable statistique en fonction de
la nature de cette variable (qualitative ou quantitative). Les représentations recommandées
et les plus fréquentes sont les tableaux et les diagrammes (graphe).


Le graphique est un support visuel qui permet :
```
**La synthèse** : 
```console
visualiser d’un seul coup d’œil les principales caractéristiques (mais on
perd une quantité d’informations), voir Figure 2.2.
```
![Image](https://github.com/daniel497/statistique_descriptive/blob/master/image2_2.jpg)

```
Figure2.2:Quelques caractéristiques du graphique

```
**La découverte** : 
```console
met en évidence les tendances.
```
**Le contrôle** :
```console 
on aperçoit mieux les anomalies sur un graphique que dans un tableau.
```
**La recherche des régularités** : 
```console 
régularité dans le mouvement, répétition du phénomène. 

```

#### 2.3.1 Distribution à caractère qualitatif

```console
A partir de l’observation d’une variable qualitative, deux diagrammes permettent de
représenter cette variable : le diagramme en bandes (dit tuyaux d’orgue) et le diagramme
à secteurs angulaires (dit camembert).
```


**Tuyaux d’orgues**

```console
Nous portons en abscisses les modalités, de façon arbitraire. Nous portons en ordonnées
des rectangles dont la longueur est proportionnelle aux effectifs, ou aux fréquences, de chaque
modalité (voir Figure 2.3).
```
![Image](https://github.com/daniel497/statistique_descriptive/blob/master/image2_3.jpg)


```
Figure2.3:Tuyaux d’orgues
```
**Diagramme par secteur (diagramme circulaire)**

```console
Les diagrammes circulaires, ou semi-circulaires, consistent à partager un disque ou un
demi-disque, en tranches, ou secteurs, correspondant aux modalités observées et dont la
surface est proportionnelle à l’effectif, ou à la fréquence, de la modalité (voir Figure 2.4).
```
![Image](https://github.com/daniel497/statistique_descriptive/blob/master/image2_4.jpg)

```
Figure2.4:Diagramme par secteur
```

```console
Le degré d’un secteur est déterminé à l’aide de la règle de trois de la manière suivante :

```
```js
                N → 360 ◦ 
                n i → d i (degréde la modalitéi).
                Donc, d i = (n i * 360)/N 
```



#### 2.3.2 Distribution à caractère quantitatif discret

```console
A partir de l’observation d’une variable quantitative discrète, deux diagrammes per-
mettent de représenter cette variable : le diagramme en bâtons et le diagramme cumulatif
(voir ci-dessous).

Pour l’illustration, nous prenons l’exemple précédent de départ (nombre d’enfants par
famille). Nous rappelons le tableau statistique associe.
```


| x i | 0 | 1 | 2 | 3 | 4 | 5 | 6 |
|-----|---|---|---|---|---|---|---|
| n i | 18 | 32 | 66 | 41 | 32 | 9 | 2 |


**Diagramme à bâtons**

```console
On veut représenter cette répartition sous la forme d’un diagramme en bâtons. À
chaque marque correspond un bâton. Les hauteurs des bâtons sont proportionnelles aux
effectifs représentés (voir Figure 2.5).
```
![Image](https://github.com/daniel497/statistique_descriptive/blob/master/image2_5.jpg)


```
Figure2.5:Diagramme à bâtons
```

#### 2.3.3 Représentation sous forme de courbe et fonction de répartition

```console
Nous avons déjà abordé les distributions cumulées d’une variable statistique. Nous
allons dans cette partie exploiter ses valeurs cumulées pour introduire la notion de la fonction
de répartition. Cette notion ne concerne que les variables quantitatives.
```


```js
Soit la fonctionF x :R→[0,1]définie par 
             F x (x) :=pourcentage des individus dont la valeur du caractère est≤x. 
Cette fonction s’appelle la fonction de répartition du caractèreX.

```
_Remarque 4_

```js
Pour tout i∈{ 1 ,...,n} , on a
F x (x i ) =F i.
La courbe de F xpasse par les points (x 1 ,F 1 ) , (x 2 ,F 2 ),... et (x n ,F n ).
```

```console
En se basant sur notre exemple, la courbe deF _x_ est représentée ci-dessous (Figure 2.6)
sur
```
```js
               R=]−∞,0[∪[0,1[∪.... ∪ [6,+∞[.
```
```js
Dans ce cas, nous avons:

- Six < 0 , alorsF _x_ (x) = 0.
- Six∈[0,1[, alorsF _x_ (x) = 0. 09.
    ...
- Six≥ 6 , alorsF _x_ (x) = 1.

```

```console
Cette courbe s’appelle "la courbe cumulative des fréquences". La courbe cumulative est une
courbe en escalier représentant les fréquences cumulées relatives.
```
![Image](https://github.com/daniel497/statistique_descriptive/blob/master/image2_6.jpg)

```
Figure2.6:Représentation d’une variable quantitative discrète par la courbe cumulative.
```




- Proposition 2

```console
La fonction de répartition satisfait, pour i∈{ 1 ,...,n} ,
```
```js
l’égalité,F x (x i ) = F i,

l’expression, F x (x) =
                              0 , si x < x1 ,
                              F1 , si x1 ≤x < x2 ,
                              Fi , si x i ≤x < xi +1,
                              1 , si x ≥ xn.

```

### 2.4 Paramètres de position (caractéristique de tendance centrale) 


```console
Les indicateurs statistiques de tendance centrale (dits aussi de position) considérés
fréquemment sont la moyenne, la médiane et le mode.
```

**Le mode**

```console
Le mode d’une V.S est la valeur qui a le plus grand effectif partiel (ou la plus grande
fréquence partielle) et il est dénoté parM 0.
```


- Exemple 13

```js
Dans l’exemple précédent, le mode est égal à 2 qui correspondant au plus grand effectif.
```
![Image](https://github.com/daniel497/statistique_descriptive/blob/master/image2_5.jpg)



_Remarque 5_

```console
On peut avoir plus d’un mode ou rien.
```

**La médiane**

```console
On appelle médiane la valeur Me de la V.S X qui vérifie la relation suivante : 
```
```js
              F x (Me−)< 0. 5 ≤F x (Me+) =F x (Me).
```
```console
La médiane partage la série statistique en deux groupes de même effectif.

```

- Exemple 14

```js
   Dans l’exemple précédent, la relation 
             F x (0) = 0< 0. 5 ≤F x (0+) = 0. 09
   n’est pas satisfaite. Donc, la médiane est différente de 0. Par contre, nous avons
             F x (2−) = 0. 25 < 0. 5 ≤F x (2+) =F(2) = 0. 58. 
   Donc, Me= 2.
```

**La moyenne**

```console
On appelle moyenne deX, la quantité
```

```js
             _        n         n
             x= 1/N * ∑ nixi= ∑ fixi, 
                     i =1      i=1  
```
```console
avecN=Card(Ω). On peut donc exprimer et calculer la moyenne dite "arithmétique" avec
des effectifs ou avec des fréquences.

```

- Exemple 15

```js
   _
Si x= 2. 46 , alors nous avons au moyenne une famille de quartier a 2. 46 d’enfants.
```
```console
La valeur de la moyenne est abstraite. Comme dans l’exemple précédent,x= 2. 46 est
un chiffre qui ne correspond pas à un fait concret.
```

```js
La moyenne arithmétique dont on vient d’indiquer la formule est dite moyenne pondérée;
cela signifie que chaque valeur de la variable est multipliée (pondérée) par un 
coefficient, ici par l’effectifn i qui lui correspond. Dans ce cas, chaque valeurx i de la
intervient dans le calcul de la moyenne autant de fois qu’elle a été observée. On parle de
variable moyenne arithmétique simple quand on n’effectue pas de pondération. Par exemple, si 5
étudiants ont pour âge respectif 18 , 19 , 20 , 21 et 22 ans, leur âge moyen est donné par
(18 + 19 + 20 + 21 + 22)/5 = 20ans.

```

_Remarque 6_

```console
Nous mentionnons qu’il existe d’autres moyennes que la moyenne arithmétique
```

### 2.5 Paramètres de dispersion (variabilité)

```console
Les indicateurs statistiques de dispersion usuels sont l’étendue, la variance et l’écart-
type.
```

**L’étendue**

```console
La différence entre la plus grande valeur et la plus petite valeur du caractère, donnée
par la quantité
```
```js
                       e=xmax−xmin,
```                       
```console
s’appelle l’étendue de la V.S X. Le calcul de l’étendue est très simple. Il donne une première
idée de la dispersion des observations. C’est un indicateur très rudimentaire et il existe des
indicateurs de dispersion plus élaborés (voir ci-dessous).
```

**La variance**

```console
On appelle variance de cette série statistiqueX, le nombre
```
```js
                n      _
      V ar(X) = ∑ f i (x − xi )^2 
               i=1
```
```console
On dit que la variance est la moyenne des carrés des écarts à la moyennex. Les « écarts à
la moyenne » sont les(x(bar) − xi), les « carrés des écarts à la moyenne » sont donc les(x(bar) − xi )^2.
En faisant la moyenne de ces écarts, on trouve la variance.

Le théorème suivant (Théorème de König-Huygens) donne une identité remarquable reliant
la variance et la moyenne, parfois plus pratique dans le calcule de la variance.
```

**Théorème 1**

```console

Soit (x i ,n i ) une série statistique de moyenne x et de variance V ar(X). Alors,
```
```js
                          n      _
                V ar(X) = ∑ f i (x − xi )^2 
                         i=1

```
_Remarque 7_

```condole
Dans l’utilisation de la formule du théorème précédent, il faut veiller à remplacer x par
sa valeur approchée la plus précise possible.
```



**L’écart type**

```js
La quantité:
          σ X = √V ar(x)
s’appelle l’écart type de la V.SX.
```

_Remarque 8_

```console
Le paramètre σ xmesure la distance moyenne entre x et les valeurs de X (voir Figure
2.7). Il sert à mesurer la dispersion d’une série statistique autour de sa moyenne.

- Plus il est petit, plus les caractères sont concentrés autour de la moyenne (on_
    dit que la série est homogène).
- Plus il est grand, plus les caractères sont dispersés autour de la moyenne (on_
    _dit que la série est hétérogène).
```

![Image](https://github.com/daniel497/statistique_descriptive/blob/master/image2_7.jpg)


```
Figure2.7:La dispersion d’une série statistique autour de sa moyenne
```

## Chapitre 3

### Étude d’une variable statistique continue 

```console
Nous rappelons qu’une variable statistique (V.S) quantitative concerne une grandeur esurable.
Ses valeurs sont des nombres exprimant une quantité et sur lesquelles les opérations
arithmétiques (addition, multiplication, etc,...) ont un sens. Nous allons dans ce
chapitre se focaliser sur la V.S quantitative continue.
```

### 3.1 Caractère continu


**Définition 11**

```console
On appelle V.S continue (ou caractère continu) toute application de Ω et à valeurs
réelles et qui prend un nombre "important" de valeurs (Les caractères continus sont
ceux qui ont une infinité de modalités).
```

- Exemple 16

```console
Soit Ω l’ensemble des nouveaux nés au C.H.U d’une ville pendant les 3 premiers mois
de 2017. Nous désignons par X le poids des nouveaux nés. On suppose que
```
```js
             x min = 2. 701 et x max = 5. 001.
```

_Remarque 9_

```console
      Comment étudier ce caractère?
``` 

```js
Réponse : Partager les valeurs prises par X en classes de valeurs.
```

#### 3.1.1 Classe de valeurs

**Définition 12 **

```console

On appelle classe de valeurs de X un intervalle de type [a,b[ tel que X∈[a,b[ si et
seulement si a≤X(w)< b , c’est à dire, que les valeurs du caractère sont dans la classe
[a,b[.
```


Dès qu’un caractère est identifié en tant que continu, ces modalitésC _k_ = [L _k_ ,L _k_ +1[
sont des intervalles avec

- L _k_ : borne inférieure.
- L _k_ +1: borne supérieure.
- a _k_ =L _k_ +1−L _k_ : son amplitude, son pas ou sa longueur.
- C _k_ =x _k_ = (L _k_ +1+L _k_ )/ 2 : son centre.

![Image](https://github.com/daniel497/statistique_descriptive/blob/master/class2.jpg)


_Remarque 10_

```console
On supposera dans tous les cas étudiés que la distribution à l’intérieur des classes est
uniforme (voir Figure 3.1). Cette hypothèse permet de justifier le fait qu’on choisisse
le centre des classes comme représentant.
```

#### 3.1.2 Nombre de classes

```console
En combien de classes partageons-nous les valeurs? la réponse n’est pas unique. SoitN
l’effectif total. Nous pouvons considérer dans ce cours trois réponses à titre d’exemple.
```

![Image](https://github.com/daniel497/statistique_descriptive/blob/master/class.jpg)


```console

Figure3.1:Une représentation de la distribution des valeurs à l’intérieur d’une classe.
```

```js
1. Une réponse : √ N,[√ N](partie entière) ou[√ N + 1] Donc, le nombre de classes k ~= √ N.
```
- Exemple 17

```console
Considérons 30 valeurs entre 56. 5 cm et 97. 8 cm. Dans ce cas, k= √30 et on prend k= 6  
```

```console
2. Une réponse : la formule de Sturge
```
```js
         k= 1 + 3.3 log 10 (N).
```
```console
3. Une réponse : la formule de Yule
```
```js
k= 2. 54(racine quatrième√ N)
```

_Remarque 11_

```console
De ce fait, on peut avoir plusieurs tableaux statistiques selon le nombre de classes.
```

- Exemple 18

```console
Si on prend N= 30 , alors le nombre de classes est donné, par exemple, par
 soit la formule de Sturge_ k= 1 + 3.3 log 10 (30) ~= 6 _,
 soit la formule de Yule_ k= 2. 54(racine quatrième √30) ~= 6

Nous mentionnons que les deux formules sont presque pareils si N << 200.
```
```console

Nous rappelons maintenant la définition de l’étendu. De plus, dans le cas continue
nous parlons aussi du pas ou de la longueur de la classe.
```

**Définition 13**

```js
Le nombre
                  e=x max −x min
s’appelle étendu de X. Dans ce cas, on peut définir le pas par

a i := étendu/nombre de classes  =x max −x min/k
```

#### 3.1.3 Effectif et fréquence d’une classe


**Définition 14**

```js
La quantité
             n i := Card {w∈Ω : X(w)∈C i }
s’appelle effectif partiel de C i.

```
![Image](https://github.com/daniel497/statistique_descriptive/blob/master/p.jpg)



```
Figure3.2:Le nombre d’individus qui prennent des valeursx i dansC i.
``` 

**Définition 15**

```js
Le nombre
              fi :=ni/N

est appelé la fréquence partielle de C i.
```

**Définition 16**

```js
On appelle l’effectif cumulé de C i la quantité
                        i
                 N i := ∑ nj. 
                       j=1
```

**Définition 17**

```js
On appelle la fréquence cumulée de C i la quantité

                        i
                 F i := ∑ fj
                       j =1
```

_Remarque 12_

```console
Nous avons, comme dans le chapitre précédent, les interprétations suivantes :
```
- n _i_ : _est le nombre d’individus dont les valeurs des caractères sont dans la classe_
    C _i,
- f _i_ : _est le pourcentage des_ w _tel que_ X(w)∈C _i,
- N _i_ : _est égale au Card_ {w: X(w)∈C 1 ∪C 2 ∪...∪C _i_ } _,
- F _i_ : _est le pourcentage des w tel que_

```js
                      X(w)∈ C1 ∪...∪ Ci.
```
### 3.2 Représentation graphique d’un caractère continu

#### 3.2.1 Histogramme des fréquences (ou effectifs)

```console
Nous pouvons représenter le tableau statistique par un histogramme. Nous reportons
les classes sur l’axe des abscisses et, au-dessus de chacune d’elles, nous traçons un rectangle
dont l’aire est proportionnelle à la fréquencef _i_ (ou l’effectifn _i_ ) associée. Ce graphique est
appelé l’histogramme des fréquences (voir Figure 3.3).

```
![Image](https://github.com/daniel497/statistique_descriptive/blob/master/image3_3.jpg)


```
Figure3.3:Histogramme des fréquences ou des éffctifs.
```



#### 3.2.2 Fonction de répartition


**Notation** : 

```console
Nous allons noter par

```js
C i = [xmin=a 0 ,xmin+1=a 1 [.
```

**Définition 18**

```console

La fonction F x :R→[0,1] définie par F x (x) représente le pourcentage des individus
tel que la valeur de leur caractère est inférieure ou égale à x. Elle est donnée par

```

```js
Fx(x)= :

- 0 , si x < a 0 ,
- f1/h(x−a^0 ), si a^0 ≤x < a^1 ,
- F i + ((f i +1)/h)(x−a i ), si a i ≤x < a i +1,
- 1 , si x≥a n ,

et elle s’appelle la fonction de répartition de X.
```

```console
Nous expliquons cette formulation de la fonction de répartition dans cette remarque.
```

_Remarque 13_

```console
Nous calculons F x (x) par extrapolation (voir Figure 3.4). Nous avons déjà F(L i ) =F i.
De plus,
tan(α) = F(L i +1)−F(L i )/L i +1−L i= F(x)−F(L i )/x−L i
```



##### 3.3. PARAMÈTRES DE TENDANCE CENTRAL 39

```console
Ce qui implique la formule de la fonction de répartition
```
```js
F(x) = (f i +1/h)(x−L i ) +F i.
```

# image figure 3.4

```
Figure3.4:Le calcul deF x (x)par extrapolation.
```

```console
La courbe deF _x_ est nulle avanta 0 , constante égale à 1 aprèsa _n_ et joint les points(a 0 ,0),
(a 1 ,F 1 ),...,(a _n_ ,1)par des segments de droites (voir Figure 3.5).
```
# image 3.5

```
Figure3.5:La courbe des fréquences cumulées.
```
### 3.3 Paramètres de tendance central

```console
On note parC _i_ le centre de la classeC _i_ et nous considéronsf _i_ la fréquence partielle
deC _i_.
```
#image figure 3.6
```
Figure3.6:Le centre de la classe.
```
**La moyenne**


**Définition 19**

```console
            
La quantité:
               
                _   n
                x = ∑ fiCi
                   i=1

s’appelle la moyenne de X.
```

**Le mode**

```console

La définition suivante permet de comprendre la démarche à suivre pour calculer le mode
d’une manière exacte et qui se trouve dans une des classes appelée "classe modale".
```

**Définition 20**

```console
Nous définissions la classe modale comme étant la classe des valeurs de X qui a le plus
grand effectif partiel (ou la plus grande fréquence partielle). La quantité
```
```js

M 0 =L i + (∆1/(∆ 1 + ∆ 2))ai
s’appelle le mode avec (voir Figure 3.7)
_-_ L _i: la borne inférieure de la classe modale.
-_ a _i: le pas de la classe modale.
-_ ∆ 1 =n 0 −n 1 _,_ ∆ 2 =n 0 −n 2 _ou bien_ ∆ 1 =f 0 −f 1 _,_ ∆ 2 =f 0 −f 2_.
-_ n 0 _et_ f 0 _sont l’effectif et la fréquence associés à la classe modale.
-_ n 1 _et_ f 1 _sont l’effectif et la fréquence de la classe qui précède la classe modale.
-_ n 2 _et_ f 2 _sont l’effectif et la fréquence de la classe qui suit la classe modale._

```
# image 3.7
```
Figure3.7:Représentation ou détermination graphique du mode (cas continu).
```

_Remarque 14_

```console
L’expression du mode donnée ci-dessus est déterminée à partir de l’intersection des
deux segments représentés dans la Figure 3.7. Cette notion n’est pas unique.
```

**La médiane**

**Définition 21**

```console
C'’est la valeur Me telle que F(Me) = 0. 5. Cette valeur est unique.

```

```js
Nous pouvons la déterminer graphiquement ou par calcule.
```

**1. Première méthode** :
_Graphiquement à partir de la formule_

```js
tan(α) = F(L i +1)−F(L i )/L i +1−L i = 0. 5 −F(L i )/Me−L i.
```

```console
Plus précisément, dans la figure 3.8, nous mettonsF(x) = 0. 5 etx=Me.
```

**2. Deuxième méthode** : 
_En utilisant directement la fonction de répartition donnée par_

```js
F(x) = ((f i +1) /h)(x−L i ) +F i.
```
```console
Nous retrouvons donc
```
```js
0 .5 =((f i +1)/h) (Me−L i ) +F i.
```

# image 3.8

```
Figure3.8:Le calcul de la médiane par extrapolation.
```

### 3.4 Paramètres de dispersion

```
**Définition 22**

```console
La variance est la quantité
```
```js
                      n    _
            V ar(x) = ∑ fi (x - Ci)^2
                     i=1
```

_Remarque 15_

```console
Pour le calcul, on utilise (voir Chapitre 2, Théorème 1)
```

```js
                      n    _
            V ar(x) = ∑ fiCi^2 - x^2
                     i=1
```

**Définition 23**

```console
La quantité
```

```js
σX = √ V ar(x)
```

```console
s’appelle l’écart type de la V.S X.
```

```console
Nous généralisons la notion de la médiane dans la définition suivante.
```

**Définition 24**

```console
Pour i∈{ 1 , 2 , 3 } , la quantité Q itel que F(Q i ) = 4 i s’appelle le i emquartile.
```

- Exemple 19

```console
Pour i= 2 , Q 2 tel que F(Q 2 ) =2/4 = 0. 5. Donc, Q 2 =Me.
```

```console
La détermination ou le calcul deQ _i_ se fait exactement comme le calcul de la médiane
(graphiquement ou analytiquement).
```
**Interprétation** : 

```
Il y a 25 % d’individus dont la valeur du caractère est dans l’in-
tervalle[a 0 ,Q 1 ]. De même pour les autres quartiles. Ces intervalles s’appellent "intervalles
interquartiles".
```

```js
                Q1 →25%,

                Q2 →50%,

                Q3 →75%.
```

# image figure 3.9
```
Figure3.9:Les quartiles.
```




## Chapitre 4

# Étude d’une variable statistique à deux dimensions


```console
Dans les chapitres précédents, nous avons présenté les méthodes qui permettent de
résumer et représenter les informations relatives à une variable. Un même individu peut être
étudié à l’aide de plusieurs caractères (ou variables). Par exemple, les salaries en regardant
leur ancienneté et leur niveau d’étude, la croissance d’un enfant en regardant son poids et
sa taille. Dans la suite, nous introduisons l’étude globale des relations entre deux variables
(en nous limitant au cas de deux variables).
Donc, soit Ω une population et :
```
```js

             Z: Ω → R^2 ,
             w → Z(w) = (X(w),Z(w)),

ou directement

            (X,Y) : Ω → R^2 ,
             w → (X(w),Z(w)).
```

```console
Dans ce cas,Zest dite variable statistique à deux dimensions avec Card(Ω) =N, avecN
un entier fini. Le couple(X,Y)est appelé le couple de la variable statistique.
```


- Exemple 20

```console

- On observe simultanément sur un échantillon de 200 foyers, le nombre d’enfants
    X et le nombre de chambre Y. 
- On observe sur un échantillon de 20 foyers, le revenu mensuel X en Da et les
    dépenses mensuelles Y.
- Au près des étudiants pris au hasard parmi une section de L2 génie civil, on

 observe les notes de math3 X et de statistique Y.

- Une entreprise mène une étude sur la liaison entre les dépenses mensuelles en
    Publicité X et le volume des ventes Y qu’elle réalise.

### 4.1 Représentation des séries statistiques à deux variables

```console
Les séries statistiques à deux variables peuvent être présentées de deux façons.
```

**Présentation 1**

```console
A chaquew i , on associé(x i ,y i ), c’est à dire,
```
```js
                          w i →(x i ,y i ).
```
```console
On rassemblera les données comme dans le tableau suivant


| w i | w 1 | w 2 | ... | w N |
|-----|-----|-----|-----|-----|
| VariableX | X(w 1 ) | X(w 2 ) | ... | X(w N ) |
| VariableY | Y(w 1 ) | Y(w 2 ) | ... | Y(w N ) |


```console
Cette représentation on la notera "présentation 1 ". Nous allons utiliser toujours les notations
suivantes :```
```js

                 x i :=X(w i)

                 et y i :=Y(w i).

```

- Exemple 21

```console
Soit Ω l’ensemble de 8 étudiants. Nous avons le tableau suivant
```

| w i | w 1 | w 2 | w 3 | w 4 | w 5 | w 6 | w 7 | w 8 |
|-----|-----|-----|-----|-----|-----|-----|-----|-----|
|X(w) | 8 | 2 | 6 | 6 | 11 | 10 | 7 | 2 |
|Y(w) | 9 | 10 | 11 | 7 | 14 | 16 | 12 | 5 |



```console
avec X représente le nombre d’heures passées à préparer l’examen de statistique par
étudiant et Y représente la note sur 20 obtenue à l’examen par l’étudiant.
```

```console
Lors de cette représentation, nous pouvons traduire le tableau associe dans une figure
appelée "le nuage de points" ou "diagramme de dispersion" (voir Figure 4.1). Cette représen-
tation est obtenue en mettant dans un repère cartésien chaque couple d’observation(x _i_ ,y _j_ )
par un point.
```

# image figure 4.1

```
Figure4.1:Représentation sous forme de nuage de points.
```

**Présentation 2**

```console
Soit la variable statistiqueZdonnée par le couple(X,Y). Soientx 1 , ...,x _k_ ety 1 ,...,y _l_
les valeurs prises respectivement parXetY. Dans ce cas, nous définissons les valeurs deZ
comme suite, pouriallant de 1 àket pourjallant de 1 àl,
```
```js
                         z ij := (x i ,y j ).
```

```console
La variable statistiqueZprendk×lvaleurs. Lors de cette étude, nous avons le tableau à
double entrée (ou tableau de contingence) suivant (discrète ou continue)
```


| X \ Y | C′ 1 = [L′ 1 ,L′ 2 [ ou y1 | ... | C l ′= [L′ l ,L′ l +1[ ou y | l Marginale % à X |
|-------|----------------------------|-----|-----------------------------|-------------------|
| C 1 = [L 1 ,L 2 [ ou x 1 | n 11 ou f 11 | ... | n 1 l ou f 1 L | n 1 • ou f 1 • |
| C 2 = [L 2 ,L 3 [ ou x 2 | n 21 ou f 21 | ... | n 2 l ou f 2 l | n 2 • ou f 2 • |
| C 3 = [L 3 ,L 4 [ ou x 3 | n 31 ou f 31 | ... | n 3 l ou f 3 l | n 3 • ou f 3 • |
| ... | ... | ... | ... | ... |
| C k = [L k ,L k +1[ ou x K | n k 1 ou f k 1 | ... | n kl ou f kl | n k • ou f k • |
| Marginale % à Y |  n• 1 ouf• 1 |  ... | n• l ouf• L | N |


```console
Cette représentation on l’a notera "présentation 2 ". A chaque couple(x i ,y i ), on an ij est
l’effectif qui représente le nombre d’individus qui prennent en même temps la valeurx i et
y i , c’est à dire,
```
```js
                 n ij :=Card{w∈Ω :Z(w) =z ij }.
```

### image figure 4.2

```
Figure4.2:Le nombre d’individus qui prennent en même temps la valeurx i ety i.
```

```console
Nous notons parf ij la fréquence du coulpe(x i,y i). Cette fréquence est donnée par

```
                  f ij := n ij/N,
```console
avec
```
```js
N = Card(Ω),
    L   k 
  = ∑   ∑  n ij, 
   j=1 i=1

    L   k 
  = ∑   ∑  n ij, 
    i=1 j=1
```


_Remarque 16_

```console
Nous avons la propriété suivante,
```
```js
    L   k 
    ∑   ∑  f ij = 1
    i=1 j=1
```

**Lois marginales**

```console
Sur la marge du tableau de contingence, on peut extraire les données seulement par
rapport àXet seulement par rapport àY (voir le tableau de contingence établi aupara-
vant).
```

_1. Effectifs et fréquences marginale par rapport àY : nous avons, pourj= 1...l,_

```js
                     k
             n•j := ∑ n ij
                    i =1
```
```console
          et
```
```js 
                            k
            f•j :=n•j/N = ∑ f ij. 
                            i=1
```


_2. Effectifs et fréquences marginale par rapport àX: nous avons, pouri= 1...k,_

```js
                     k
             N i• := ∑ n ij
                    i =1
```
```console
          et
```
```js 
                            k
            f i• :=n i•/N = ∑ f ij. 
                            i=1
```


_Remarque 17_

```console
Nous avons les propriétés suivantes
```
 
```js
    k         k
    ∑ n i• =  ∑ n •j = N
   i =1      i =1
```

```console
                et
```
```js
    k         k
    ∑ f i• =  ∑ f •j = 1
   i =1      i =1
```
 

### 4.2 Description numérique

#### 4.2.1 Caractéristique des séries marginales

```console
Dans le cas d’une variable statistique à deux dimensionsXetY, les moyennes sont
données respectivement par

```
```js
                  _       k          k
                  x:= 1/N(∑ n i•xi = ∑ f i•xi ( moyenne de X) 
                          i =1       i=1
```
```console
                                      et 
```
```js
                 _       k          k
                 y:= 1/N(∑ n •jyj = ∑ f •jyj ( moyenne de Y) 
                          i =1       i=1

```
_Remarque 18_

```console
Dans le cas continu, x iet y jreprésentent respectivement le centre des classes de X et
Y , c’est à dire,
         x i =((L i +1 + L i)/2)
                et
         y j =((L j +1 + L j)/2).
```

- Exemple 22

```console
Nous calculons x et y pour l’exercice traité précédemment. Nous avons la moyenne
d’âge
```
```js
    
    _     1
    x =   _ (40 + 60 + 120 + 150) = 37 ans. 

         10

```

```console
et la moyenne du salaire
```
```js

    _     1
    y =   _ (6.5 + 15 + 25.5 + 28.5 + 10.5) x 100 =  8600 da. 

         10

```
```console
Nous définissions maintenant la variance deXet la variance deY comme suit,
```
```js
            ___   _      
V ar(X) : = x^2 −(x)^2 ,
                
     _           k                  k
avec x^2 : = 1/N ∑ n i • (x i)^2 =  ∑ f i • (x i)^2 
                i=1                i=1
```
```console
                          et
```
```js
            ___   _      
V ar(Y) : = y^2 −(y)^2 ,
                
     _           k                  k
avec x^2 : = 1/N ∑ n •j (y j)^2 =  ∑ f  •j(y i)^2 
                j=1                j=1
``` 

```console
Les écarts-type deXet deY sont donnés, respectivement, par
```

```js
σ X := √ (V ar(X)) et σ Y := √ (V ar(Y)) .
```


#### 4.2.2 Série conditionnelle

```consoleLa notion de série conditionnelle est essentielle pour comprendre l’analyse de la ré-
gression. Un tableau de contingence se compose en autant de séries conditionnelles suivant
chaque ligne et chaque colonnes.
```

**Série conditionnelle par rapport à X**

```console
Elle est notée parX/y j (ouX j ) et on dit que c’est la série conditionnelle deXsachant
queY =y j. Nous calculons dans ce cas la fréquence conditionnellef i/j (f i sachant j), pour
i= 1,...,k, par
```
```js
f i/j := n ij / n• j = f ij / f• j
```
```console
Nous avons aussi la moyenne conditionnellex j , c’est à dire la moyenne des valeurs de X
sous la conditiony j , elle est définie par

```
```js
_      k                     k
x j := ∑ f (i/j) x i =  1/n•j(∑ n ij x i. 
      i=1                   i=1
```
```console
Pour l’écart-type conditionnel, nous avons
```
```js
σ Xj := √ (V ar(X j )) 

```console
              avec
```
```js                      k             _         ___     _
             V ar(X j ) := ∑ f i/j (x i −x j )^2 = x^2 j −(x j )^2.
                          i=1
```

##### 60 4.2. DESCRIPTION NUMÉRIQUE

**Série conditionnelle par rapport à Y**

```console
Elle est notée parY/x j (ouY j ) et on dit que c’est la série conditionnelle deY sachant
queX=x i. Nous calculons aussi dans ce cas la fréquence conditionnellef j/i (f j sachant
i), pourj= 1,...,l, par
```
```js
f j/i := n ij / n i • = f ij / f i •
```
```console
Nous avons aussi la moyenne conditionnelley i , c’est à dire la moyenne des valeurs de Y
sous la conditionx i , elle est définie par
```
```js
_      k                     k
y i:= ∑ f (j/i) y j=  1/n i•(∑ n ij y j. 
      j=1                   j=1
```
```console
Pour l’écart-type conditionnel, nous avons
```
```js
σ Yi:= √ (V ar(Y i)) 

```console
              avec
```
```js                      l             _         ___     _
             V ar(Y i ) := ∑ f j/i (y i −y i)^2 = y^2 i −(y i )^2.
                          j=1
```
 
#### 4.2.3 Notion de covariance

```console
Nous notons parCov(X,Y)la covariance entre les variables X et Y. La covariance est
un paramètre qui donne la variabilité deXpar rapport à Y (voir Figure 4.3).
```

# image figure 4.3

```
Figure4.3:La covariance et la variabilité.
```
```console
La covariance se calcule par l’expression suivante
```
```js
                          __   _ _       k   l                _ _ 
                Cov(X,Y) =xy − x y= 1/N (∑   ∑  n ij x i y j −x y.
                                        i=1 j=1
```





**Définition 25**

```console
On dit que deux variables statistiques X et Y sont indépendantes si et seulement si,
pour tout i et j ,

                          f ij =f i • ×f• j.

Il suffit que cette égalité ne soit pas vérifiée dans une seule cellule pour que les deux
variables ne soient pas indépendantes.. De manière équivalente, pour tout i et j ,
                         
                          N×n ij =n i • ×n• j.

Dans ce cas, si X et Y sont indépendantes alors (réciproque est fausse) Cov(X,Y) = 0.
```

```console
Cette définition donne une interprétation intéressante de d’indépendance ; elle signifie que
dans ce cas, les effectifs des modalités conjointes peuvent se calculer uniquement à partir
des distributions marginales, supposées « identiques » aux distributions deXetY dans la
population ; en d’autres termes, siXetY sont indépendantes, les observations séparées de
Xet deY donnent la même information qu’une observation conjointe.
```

### 4.3 Ajustement linéaire

```console
Dans le cas où on peut mettre en évidence l’existence d’une relation linéaire significative
entre deux caractères quantitatifs continusXetY(la silhouette du nuage de points est étirée
dans une direction), on peut chercher à formaliser la relation moyenne qui unit ces deux
variables à l’aide d’une équation de droite qui résume cette relation. Nous appelons cette
démarche l’ajustement linéaire.
```

#### 4.3.1 Coefficient de corrélation

```console
Les coefficients de corrélation permettent de donner une mesure synthétique de l’inten-
sité de la relation entre deux caractères et de son sens lorsque cette relation est monotone.
Le coefficient de corrélation de Pearson permet d’analyser les relations linéaires (voir ci-
dessous). Il existe d’autres coefficients pour les relations non-linéaires et non-monotones,
mais ils ne seront pas étudiés dans le cadre de ce cours.
```

**Définition 26**

```console
La quantité
```js
     
      ρXY := Cov(X,Y) / σ X σ Y ,
```
```console
s’appelle le coefficient de corrélation.
```


**Proposition 3**


```js
Le coefficientρXY est compris entre [− 1 ,1] , ou encore| ρXY | ≤ 1.

Le coefficient ρXY mesure le degré de liaison linéaire entreXetY (voir Figure 4.4 et).

Nous avons les deux caractéristiques suivantes (voir Figures 4.5 et 4.6)^1 :
```

– Plus le module de ρXY est proche de 1 plusXetY sont liées linéairement.
– Plus le module de ρXY est proche de 0 plus il y a l’absence de liaison linéaire entre X et Y.

# image figure 4.4

```
Figure4.4:A gauche, le coefficient de corrélation est proche de 1. A droite, le coefficient de
corrélation est proche de 0.
```

# image figure 4.5
```
Figure4.5:Exemples de diagrammes de dispersion avec différentes valeurs de coefficient de cor-
rélation.
```


_Remarque 21_

```js
Par définition, siρXY = 0 , alors Cov(X,Y) = 0.
```

# image figure 4.6

```js
Figure4.6:La corrélation reflète la non-linéarité et la direction d’une relation linéaire mais pas
la pente de cette relation ni de nombreux aspects des relations non linéaires (en bas). La figure au
centre a une pente de 0 , mais dans ce cas, le coefficient de corrélation est indéfini car la variance de
Yest nulle..
```

#### 4.3.2 Droite de régression

```console 
L’idée est de transformer un nuage de point en une droite. Celle-ci doit être la plus
proche possible de chacun des points. On cherchera donc à minimiser les écarts entre les
points et la droite.
```

# image figure 4.7

```
Figure4.7:La droite la plus proche possible de chacun des points.
```

```console
Pour cela, on utilise la méthode des moindres carrées. Cette méthode vise à expliquer un
nuage de points par une droite qui lié Y à X, c’est à dire,

```js
                          Y =aX+b,
```
```console
telle que la distance entre le nuage de points et droite soit minimale. Cette distance matéria-
lise l’erreur, c’est à dire la différence entre le point réellement observé et le point prédit par
la droite. Si la droite passe au milieu des points, cette erreur sera alternativement positive
et négative, la somme des erreurs étant par définition nulle. Ainsi, la méthode des moindres
carrés consiste à chercher la valeur des paramètresaetbqui minimise la somme des erreurs
élevées au carré.
On pose
```
```js
           n
           ∑  e^2 i =U(a,b),
          i=1
```
```console
avece i est l’erreur commise sur chaque observation, c’est à dire,
```
```js
|e i |=|y i −y*i |=|y i −ax i −b|.
```
```console
La méthode des moindres carrées consiste donc à minimiser la fonctionU (la somme des
erreurs commises). Nous avons la condition de minimisation suivante,
```
```js

                 ∂U/∂a = ∂U/∂b = 0,
```
```console
avec
```
```js 
                    n
           U(a,b) = ∑ (y i −ax i −b)^2.
                   i=1
```
```console
L’équation ∂U/∂b = 0
donne
```
```js
               n
               ∑ −2(y i −ax i −b) = 0.
              i=1
```
```console
Ce qui implique que
```
```js
          n         n        n
          ∑ y i − a ∑ x i −b ∑ 1 = 0  × 1/N.
         i=1       i=1      i=1
```

```js
Par conséquent, nous obtenons
                     y−ax−b= 0,

c’est à dire,
                     b=y−ax.

De même, après calcule,∂U/∂a = 0implique que


                     a=Cov(X,Y)/Var(X).
```

```js
Donc, la droite de régression, qui rend la distance entre elle et les points minimale, est
donnée par
D(Y/X) : Y =aX+b,
avec

a= Cov(X,Y)/Var(X) et
  _     _
b=y − a x.

Ou bien
D(X/Y) : X=a′Y+b′,

avec

a′= Cov(X,Y)/Var(Y) et 
b′=x−a′y.

```

_Remarque 22_

```console
Le coefficient de corrélationρXY permet de justifier le fait de l’ajustement linéaire.
On adopte les critères numériques suivants (voir Figure 4.8),
```
– Si | ρXY |< 0. 7 , alors l’ajustement linéaire est refusé (droite refusée).

– Si | ρXY |≥ 0. 7 , alors l’ajustement linéaire est accepté (droite acceptée).

 


# image figure 4.8

```
Figure4.8:La zone d’acceptation ou de refus de l’ajustement linéaire.
```




#### Fin du cours.
#### Consulter la partie exercice pour vous entraîner. 0
