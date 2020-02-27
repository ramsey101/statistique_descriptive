### DÉCOUVREZ LA STATISTIQUE DESCRIPTIVE 



#### NAN DATA ANALYST



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


******Symbole Signification*******

```js
[ ] La partie entière.

Card(Ω) Le cardinal : nombre d’éléments de l’ensembleΩ.

:= Est défini comme étant (symbole d’affectation). 

N Ensemble des nombres entiers naturels.

Z Ensemble des nombres entiers relatifs.

R Ensemble des nombres réels.

R^2 Ensemble des couples de nombres réels.

n
∑ = La somme pourivariant de 1 àn.
i 

V.S La variable statistique

Me La médiane.

Me+ Me par valeur supérieure.

Me− Me par valeur inférieure.

M 0 Le mode.

x La moyenne d’une série statistiqueX.

σ X L’écart-type deX.

Var(X) La variance deX.

Cov(X,Y) La covariance entre les variablesXetY.

ρXY Le coefficient de corrélation entre les variablesXetY.

F(x) La fonction s’appelle la fonction de répartition du caractèreX
```




## Chapitre 1

# Généralités sur la statistique

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

- Recueillir des données.
- Présenter et résumer ces données.
- Tirer des conclusions sur la population étudiée et d’aider à la prise de décision.
- En présence de données dépendant du temps, nous essayons de faire de la prévision.

### 1.1 Vocabulaire

Les statistiques consistent en diverses méthodes de classement des données tels que les
tableaux, les histogrammes et les graphiques, permettant d’organiser un grand nombre de
données. Les statistiques se sont développées dans la deuxième moitié du XIXe siècle dans
le domaine des sciences humaines (sociologie, économie, anthropologie, ...). Elles se sont
dotées d’un vocabulaire particulier.



#### 1.1.1 Épreuve statistique

Les statistiques descriptives visent à étudier les caractéristiques d’un ensemble d’ob-
servations comme les mesures obtenues lors d’une expérience. L’expérience est l’étape pré-
liminaire à toute étude statistique. Il s’agit de prendre "contact" avec les observations. De
manière générale, la méthode statistique est basée sur le concept suivant.

```
Définition 1
L’épreuve statistique est une expérience que l’on provoque.
```
```
Exemple 1 (La durée de vie des lampes)

Imaginons le cas suivant : un fabricant d’ampoules électriques ayant le choix entre
4 types de filaments se propose d’étudier l’influence de la nature du filament sur la
durée de vie des ampoules fabriquées. Pour ce faire, il va faire fabriquer 4 échantillons
d’ampoules identiques, sauf en ce qui concerne le filament, faire brûler les ampoules
jusqu’à extinction, puis comparer les résultats obtenus.
```
#### 1.1.2 Population

En statistique, on travaille sur des populations. Ce terme vient du fait que la démo-
graphie, étude des populations humaines, a occupé une place centrale aux débuts de la
statistique, notamment au travers des recensements de population. Mais, en statistique,
le terme de population s’applique à tout objet statistique étudié, qu’il s’agisse d’étudiants
(d’une université ou d’un pays), de ménages ou de n’importe quel autre ensemble sur lequel
on fait des observations statistiques. Nous définissons la notion de population.


##### 1.1. VOCABULAIRE 

```
Définition 2
On appelle population l’ensemble sur lequel porte notre étude statistique. Cet ensemble
est noté Ω.
```
```
Exemple 2
```
_- On considère l’ensemble des étudiants de la section A. On s’intéresse aux_
    _nombre de frères et sœurs de chaque étudiant. Dans ce cas_

```
Ω = ensemble desétudiants.
```
_- Si l’on s’intéresse maintenant a la circulation automobile dans une ville, la po-_
    _pulation est alors constituée de l’ensemble des véhicules susceptibles de circuler_
    _dans cette ville à une date donnée. Dans ce cas_

```
Ω = ensemble des véhicules.
```
#### 1.1.3 Individu (unité statistique)

Une population est composée d’individus. Les individus qui composent une population
statistique sont appelés unités statistiques.

```
Définition 3
On appelle individu tout élément de la population Ω , il est noté ω ( ω dans Ω ).
```
```
Remarque 1
L’ensemble Ω peut être un ensemble de personnes, de choses ou d’animaux...
L’unité statistique est un objet pour lequel nous sommes intéressés à recueillir de l’in-
formation.
```
```
Exemple 3
```
_- Dans l’exemple indiqué ci-dessus, un individu est tout étudiant de la section.
- Si on étudie la production annuelle d’une usine de boîtes de boisson en métal_
    _(canettes). La population est l’ensemble des boîtes produites durant l’année et_


##### 4 1.1. VOCABULAIRE

```
une boîte constitue un individu.
```
#### 1.1.4 Caractère (variable statistique)

La statistique « descriptive », comme son nom l’indique cherche à décrire une po-
pulation donnée. Nous nous intéressons au caractéristique des unités qui peuvent prendre
différentes valeurs.

```
Définition 4
On appelle caractère (ou variable statistique, dénotée V.S) toute application
```
```
X: Ω→C.
```
```
L’ensemble C est dit : ensemble des valeurs du caractère X (c’est ce qui est mesuré ou
observé sur les individus)
```
```
Exemple 4
Taille, température, nationalité, couleur des yeux, catégorie socioprofessionnelle ...
```
```
Remarque 2
Soit Ω un ensemble. On appelle et on note Card (Ω) , le nombre d’éléments de Ω.
```
```
Card (Ω) := nombre d’éléments de Ω =N.
```
#### 1.1.5 Modalités

Les modalités d’une variable statistique sont les différentes valeurs que peut prendre
celle-ci.

```
Exemple 5
```
_- Variable est " situation familiale "_
    _Modalités sont " célibataire, marié, divorcé "_


##### 1.2. TYPES DES CARACTÈRES 

_- Variable est" statut d’interrupteur "_
    _Modalités sont " 0 et 1 ".
- Variable est " catégories socio-professionnelles "_
    _Modalités sont " Employés, ouvriers, retraités,... "_

Les modalités sont les différentes situations dans lesquelles les individus peuvent se
trouver à l’égard du caractère considéré.

### 1.2 Types des caractères

Nous distinguons deux catégories de caractères : les caractères qualitatifs et les carac-
tères quantitatifs.

# iamge1. 2

#### 1.2.1 Caractère qualitatif

Les caractères qualitatifs sont ceux dont les modalités ne peuvent pas être ordonnées,
c’est-à-dire que si l’on considère deux caractères pris au hasard, on ne peut pas dire de l’un
des caractères qu’il est inférieur ou égal à l’autre. Plus précisément, nous avons la définition
suivante.

```
Définition 5
Les éléments de C sont représentés par autre chose que des chiffres.
```
```
Exemple 6
L’état d’une maison : on peut considérer les modalités suivantes
```

_ Ancienne.
_ Dégradée.
_ Nouvelle.
_ Rénovée.





#### 1.2.2 Caractère quantitatif

Les caractères quantitatifs sont des caractères dont les modalités peuvent être ordon-
nées. Ainsi, l’âge, la taille de vie ou le salaire d’un individu sont des caractères quantitatifs.
Donc, nous avons la définition suivante.

```
Définition 6
L’ensemble des valeurs est représenté par des chiffres. De même, il est partagé en deux
sortes de caractères, discret et continu (voir l’exemple).
```
```
Exemple 7
```
_- Le salaire d’employés d’une usine._
    _Modalités :_ 10000 _da ,_ 20000 _da..._
    _Type : Discret.
- La rigidité des ressorts._
    _Modalités :_ [10,20] _N/m_
    _Type : continu._

En général, la variable quantitative discrète est une variable ne prenant que des valeurs
entières (plus rarement décimales). Le nombre de valeurs distinctes d’une telle variable
est habituellement assez faible. Citons, par exemple, le nombre de maisons par quartier
d’une ville. Une variable quantitative est dite continue lorsque les observations qui lui sont
associées ne sont pas des valeurs précises, mais des intervalles. C’est le cas lorsque nous
avons un grand nombre d’observations distinctes.

La statistique descriptive a pour objectif de synthétiser l’information contenue dans
les jeux de données au moyen de tableaux, figures ou résumés numériques. Les variables
statistiques sont analysées différemment selon leur nature (quantitative, qualitative).


## Chapitre 2

# Étude d’une variable statistique discrète



Le caractère statistique peut prendre un nombre fini raisonnable de valeurs (note,
nombre d’enfants, nombre de pièces, ...). Dans ce cas, le caractère statistique étudié est
alors appelé un caractère discret.

```
Dans toute la suite du chapitre, nous considérons la situation suivante :
```
```
X: Ω→{x 1 ,x 2 ,...,x n },
```
avec Card(Ω) :=Nest le nombre d’individus dans notre étude.

Nous allons utiliser souvent l’exemple ci-dessous pour illustrer les énoncés de ce cha-
pitre.

```
Exemple 8
Une enquête réalisée dans un village porte sur le nombre d’enfants à charge par famille.
On note X le nombre d’enfants, les résultats sont données par ce tableau :
```

| xi | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 
|----|---|---|---|---|---|---|---|
| ni(Effectif) | 18 | 32 | 66 | 41 | 32 | 9 | 2 |



_-_ Ω _ensemble des familles.
-_ ω _une famille.
-_ X _nombre d’enfants par famille_

```
                    X:ω→X(ω).
```

##### 12 2.1. EFFECTIF PARTIEL - EFFECTIF CUMULÉ

```
On lit, à la famille ω , on associe X(ω) = le nombre d’enfants de cette famille.
```
### 2.1 Effectif partiel - effectif cumulé

On étudie ici un caractère statistique numérique représenté par une suitex _i_ décrivant
la valeur du caractère avecivarie de 1 àk.

#### 2.1.1 Effectif partiel (fréquence absolue)

```
Définition 
Pour chaque valeur x i, on pose par définition
                 n i = Card {ω∈Ω : X(ω) =x i }.
                 
n i: le nombre d’individus qui ont le même x i, ça s’appelle effectif partiel de x i.
```
# image 2.1.1
```
Figure2.1:Le nombre d’individus qui prennent la valeurx i.
```
```
Exemple 9
Dans l’exemple précédent, 66 est le nombre de familles qui ont 2 enfants.
```

| xi |··· | 2 | ··· |
|----|----|---|-----|
| n i(Effectif)| ··· | 66 | ··· |


##### 2.2. FRÉQUENCE PARTIELLE - FRÉQUENCE CUMULÉE 

#### 2.1.2 Effectif cumulé

```
Définition 8
Pour chaque valeur x i, on pose par définition

               N i =n 1 +n 2 +...+ni
L’effectif cumulé N id’une valeur est la somme de l’effectif de cette valeur et de tous
les effectifs des valeurs qui précèdent.
```
```
Exemple 10
Dans l’exemple précédent : 50 est le nombre de familles qui ont un nombre d’enfant
inférieur à 1. Nous le regardons dans le tableau suivant :
```

| xi | 0 | 1 | 2 | 3 | 4 | 5 | 6 |
|----|---|---|---|---|---|---|---|
|Ni | 18 | 50 | 116 | 157 | 189 | 198 | 200 |
```
**Interprétation** :
N _i_ est le nombre d’individus dont la valeur du caractère est inférieur
ou égale àx _i_. De ce fait, l’effectif total est donné par

                              n
                   N=card{Ω) =∑ ni
                             i=1
```
Dans notre exemple précédent, nous avonsN= 200.

### 2.2 Fréquence partielle - Fréquence cumulée

Typiquement les effectifsn _i_ sont grands et il est intéressant de calculer des grandeurs
permettant de résumer la série.

#### 2.2.1 Fréquence partielle (fréquence relative)

```
Définition 9
Pour chaque valeur x i, on pose par définition

                   f i :=n i/N

```


```
f is’appelle la fréquence partielle de x i. La fréquence d’une valeur est le rapport de
l’effectif de cette valeur par l’effectif total.
```
```
Remarque 3
On peut remplacer f ipar f i × 100 qui représente alors un pourcentage.
```

**Interprétation**: f i = est le pourcentage desωtel queX(ω) =x i.*

```
Exemple 11
Dans l’exemple précédent, 0 ,33 := il y a 33 % de familles dont le nombre d’enfants égale
à 2. Ce pourcentage est calculé de la façon suivante ( N= 200 ) :
```


| xi | ··· | 2 | ··· |
|----| --- |---| --- |
| ni(Effectif)| ··· | 66 |···|
| Ni(Effectif)| ··· | 200/66 = 0. 33 | ··· |


Nous pouvons conclure la propriété suivante.

```
Proposition 1
Soit f idéfini comme précédemment. Alors,

                   n
                   ∑ fi = 1
                   i =1


```


#### 2.2.2 Fréquence cumulée

```
Définition 10
Pour chaque valeur x i, on pose par définition

                    F i =f 1 +f 2 +...+f i. 
La quantité F is’appelle la fréquence cumulée de x i.
```

**Interprétation** : F _i_ =est le pourcentage desωtel que la valeurX(ω)est inférieure
ou égale àx _i_.

```
Exemple 12
```
_- Dans l’exemple précédent,_ 0. 785 _représente_ 78 .5% _de familles dont le nombre d’en-
fants est inférieur ou égale à_ 3_.




### 2.3 Représentation graphique des séries statistiques

On distingue les méthodes de représentation d’une variable statistique en fonction de
la nature de cette variable (qualitative ou quantitative). Les représentations recommandées
et les plus fréquentes sont les tableaux et les diagrammes (graphe).

```
Le graphique est un support visuel qui permet :
```
**La synthèse** : visualiser d’un seul coup d’œil les principales caractéristiques (mais on
perd une quantité d’informations), voir Figure 2.2.
# image figure 2.2
```
Figure2.2:Quelques caractéristiques du graphique

```
**La découverte** : met en évidence les tendances.
**Le contrôle** : on aperçoit mieux les anomalies sur un graphique que dans un tableau.
**La recherche des régularités** : régularité dans le mouvement, répétition du phéno-
mène.

#### 2.3.1 Distribution à caractère qualitatif

A partir de l’observation d’une variable qualitative, deux diagrammes permettent de
représenter cette variable : le diagramme en bandes (dit tuyaux d’orgue) et le diagramme
à secteurs angulaires (dit camembert).



**Tuyaux d’orgues**

Nous portons en abscisses les modalités, de façon arbitraire. Nous portons en ordonnées
des rectangles dont la longueur est proportionnelle aux effectifs, ou aux fréquences, de chaque
modalité (voir Figure 2.3).
# image figure 2.3

```
Figure2.3:Tuyaux d’orgues
```
**Diagramme par secteur (diagramme circulaire)**

Les diagrammes circulaires, ou semi-circulaires, consistent à partager un disque ou un
demi-disque, en tranches, ou secteurs, correspondant aux modalités observées et dont la
surface est proportionnelle à l’effectif, ou à la fréquence, de la modalité (voir Figure 2.4).
# image figure 2.4
```
Figure2.4:Diagramme par secteur
```
Le degré d’un secteur est déterminé à l’aide de la règle de trois de la manière suivante :

```
                N−→ 360 ◦ 
                n i −→ d i (degréde la modalitéi).
                Donc, d i = (n i * 360)/N 
```



#### 2.3.2 Distribution à caractère quantitatif discret

A partir de l’observation d’une variable quantitative discrète, deux diagrammes per-
mettent de représenter cette variable : le diagramme en bâtons et le diagramme cumulatif
(voir ci-dessous).

Pour l’illustration, nous prenons l’exemple précédent de départ (nombre d’enfants par
famille). Nous rappelons le tableau statistique associe.



| x i | 0 | 1 | 2 | 3 | 4 | 5 | 6 |
|-----|---|---|---|---|---|---|---|
| n i | 18 | 32 | 66 | 41 | 32 | 9 | 2 |


**Diagramme à bâtons**

On veut représenter cette répartition sous la forme d’un diagramme en bâtons. À
chaque marque correspond un bâton. Les hauteurs des bâtons sont proportionnelles aux
effectifs représentés (voir Figure 2.5).
# image figure 2.5
```
Figure2.5:Diagramme à bâtons
```
#### 2.3.3 Représentation sous forme de courbe et fonction de répartition

Nous avons déjà abordé les distributions cumulées d’une variable statistique. Nous
allons dans cette partie exploiter ses valeurs cumulées pour introduire la notion de la fonction
de répartition. Cette notion ne concerne que les variables quantitatives.



```console
Soit la fonctionF x :R→[0,1]définie par 
F x (x) :=pourcentage des individus dont la valeur du caractère est≤x. 
Cette fonction s’appelle la fonction de répartition du caractèreX.

```
Remarque 4
Pour tout i∈{ 1 ,...,n} , on a
F x (x i ) =F i.
La courbe de F xpasse par les points (x 1 ,F 1 ) , (x 2 ,F 2 ),... et (x n ,F n ).

```console
En se basant sur notre exemple, la courbe deF _x_ est représentée ci-dessous (Figure 2.6)
sur
               R=]−∞,0[∪[0,1[∪.... ∪ [6,+∞[.

Dans ce cas, nous avons
```
- Six < 0 , alorsF _x_ (x) = 0.
- Six∈[0,1[, alorsF _x_ (x) = 0. 09.
    ...
- Six≥ 6 , alorsF _x_ (x) = 1.

```
Cette courbe s’appelle "la courbe cumulative des fréquences". La courbe cumulative est une
courbe en escalier représentant les fréquences cumulées relatives.
```
# image figure 2.6
```
Figure2.6:Représentation d’une variable quantitative discrète par la courbe cumulative.
```



```
Proposition 2
La fonction de répartition satisfait, pour i∈{ 1 ,...,n} ,

l’égalité,F x (x i ) = F i,

l’expression, F x (x) =
                              0 , si x < x 1 ,
                              F 1 , si x 1 ≤x < x 2 ,
                              F i , si x i ≤x < x i +1,
                              1 , si x≥x n.

```

### 2.4 Paramètres de position (caractéristique de tendance centrale) 



Les indicateurs statistiques de tendance centrale (dits aussi de position) considérés
fréquemment sont la moyenne, la médiane et le mode.

**Le mode**

```
Le mode d’une V.S est la valeur qui a le plus grand effectif partiel (ou la plus grande
fréquence partielle) et il est dénoté parM 0.
```

```
Exemple 13
Dans l’exemple précédent, le mode est égal à 2 qui correspondant au plus grand effectif.
```
# image exemple 13

```
Remarque 5
On peut avoir plus d’un mode ou rien.
```
**La médiane**

```
On appelle médiane la valeur Me de la V.S X qui vérifie la relation suivante : 
                     F x (Me−)< 0. 5 ≤F x (Me+) =F x (Me).
La médiane partage la série statistique en deux groupes de même effectif.

```

***Exemple 14***
```
   Dans l’exemple précédent, la relation 
             F x (0) = 0< 0. 5 ≤F x (0+) = 0. 09
   n’est pas satisfaite. Donc, la médiane est différente de 0. Par contre, nous avons
             F x (2−) = 0. 25 < 0. 5 ≤F x (2+) =F(2) = 0. 58. 
   Donc, Me= 2.
```

**La moyenne**

```console
On appelle moyenne deX, la quantité

             _        n         n
             x= 1/N * ∑ nixi= ∑ fixi, 
                     i =1      i=1  

avecN=Card(Ω). On peut donc exprimer et calculer la moyenne dite "arithmétique" avec
des effectifs ou avec des fréquences.

```
**Exemple 15**
```console
   _
Si x= 2. 46 , alors nous avons au moyenne une famille de quartier a 2. 46 d’enfants.
```

La valeur de la moyenne est abstraite. Comme dans l’exemple précédent,x= 2. 46 est
un chiffre qui ne correspond pas à un fait concret.


```console
La moyenne arithmétique dont on vient d’indiquer la formule est dite moyenne pon-
dérée ; cela signifie que chaque valeur de la variable est multipliée (pondérée) par un coef-
ficient, ici par l’effectifn _i_ qui lui correspond. Dans ce cas, chaque valeurx _i_ de la variable
intervient dans le calcul de la moyenne autant de fois qu’elle a été observée. On parle de
moyenne arithmétique simple quand on n’effectue pas de pondération. Par exemple, si 5
étudiants ont pour âge respectif 18 , 19 , 20 , 21 et 22 ans, leur âge moyen est donné par
(18 + 19 + 20 + 21 + 22)/5 = 20ans.

```

**Remarque 6**

Nous mentionnons qu’il existe d’autres moyennes que la moyenne arithmétique

### 2.5 Paramètres de dispersion (variabilité)

Les indicateurs statistiques de dispersion usuels sont l’étendue, la variance et l’écart-
type.

**L’étendue**

La différence entre la plus grande valeur et la plus petite valeur du caractère, donnée
par la quantité
```console
                       e=xmax−xmin,
```                       

s’appelle l’étendue de la V.S X. Le calcul de l’étendue est très simple. Il donne une première
idée de la dispersion des observations. C’est un indicateur très rudimentaire et il existe des
indicateurs de dispersion plus élaborés (voir ci-dessous).

**La variance**

```console
On appelle variance de cette série statistiqueX, le nombre
          n      _
V ar(X) = ∑ f i (x − xi )^2 
         i=1
```
```
On dit que la variance est la moyenne des carrés des écarts à la moyennex. Les « écarts à
la moyenne » sont les(x(bar) − xi), les « carrés des écarts à la moyenne » sont donc les(x(bar) − xi )^2.
En faisant la moyenne de ces écarts, on trouve la variance.
```
Le théorème suivant (Théorème de König-Huygens) donne une identité remarquable reliant
la variance et la moyenne, parfois plus pratique dans le calcule de la variance.


**Théorème 1*, 
```js

Soit (x i ,n i ) une série statistique de moyenne x et de variance V ar(X). Alors,
 
                          n      _
                V ar(X) = ∑ f i (x − xi )^2 
                         i=1

```
**Remarque 7**

Dans l’utilisation de la formule du théorème précédent, il faut veiller à remplacer x par
sa valeur approchée la plus précise possible.




**L’écart type**

```console
La quantité:
          σ X = √V ar(x)
s’appelle l’écart type de la V.SX.
```

**Remarque 8**

Le paramètre σ xmesure la distance moyenne entre x et les valeurs de X (voir Figure
2.7). Il sert à mesurer la dispersion d’une série statistique autour de sa moyenne.

_- Plus il est petit, plus les caractères sont concentrés autour de la moyenne (on_
    _dit que la série est homogène).
- Plus il est grand, plus les caractères sont dispersés autour de la moyenne (on_
    _dit que la série est hétérogène)._
# image figure 2.7
```
Figure2.7:La dispersion d’une série statistique autour de sa moyenne
```

## Chapitre 3

### Étude d’une variable statistique continue 

 
Nous rappelons qu’une variable statistique (V.S) quantitative concerne une grandeur esurable.
Ses valeurs sont des nombres exprimant une quantité et sur lesquelles les opérations
arithmétiques (addition, multiplication, etc,...) ont un sens. Nous allons dans ce
chapitre se focaliser sur la V.S quantitative continue.

### 3.1 Caractère continu


Définition 11

```console
On appelle V.S continue (ou caractère continu) toute application de Ω et à valeurs
réelles et qui prend un nombre "important" de valeurs (Les caractères continus sont
ceux qui ont une infinité de modalités).
```

**Exemple 16**

```js
Soit Ω l’ensemble des nouveaux nés au C.H.U d’une ville pendant les 3 premiers mois
de 2017. Nous désignons par X le poids des nouveaux nés. On suppose que
           
             x min = 2. 701 et x max = 5. 001.
```

**Remarque 9**

```console
      Comment étudier ce caractère?
``` 

```console
Réponse : Partager les valeurs prises par X en classes de valeurs.
```

#### 3.1.1 Classe de valeurs

**Définition 12 **

```

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

# image class et valeur 

**Remarque 10**

```console
On supposera dans tous les cas étudiés que la distribution à l’intérieur des classes est
uniforme (voir Figure 3.1). Cette hypothèse permet de justifier le fait qu’on choisisse
le centre des classes comme représentant.
```

#### 3.1.2 Nombre de classes

En combien de classes partageons-nous les valeurs? la réponse n’est pas unique. SoitN
l’effectif total. Nous pouvons considérer dans ce cours trois réponses à titre d’exemple.


# image figure 3.1
```
Figure3.1:Une représentation de la distribution des valeurs à l’intérieur d’une classe.
```
1. Une réponse : √N,[√N](partie entière) ou[√N + 1] Donc, le nombre de classes k ~= √N.

**Exemple 17**

```
Considérons 30 valeurs entre 56. 5 cm et 97. 8 cm. Dans ce cas, k= √30 et on prend k= 6  
```

2. Une réponse : la formule de Sturge

```console
         k= 1 + 3.3 log 10 (N).
```
3. Une réponse : la formule de Yule

```console
k= 2. 54(racine quatrième√N)
```

**Remarque 11**

```
De ce fait, on peut avoir plusieurs tableaux statistiques selon le nombre de classes.
```

**Exemple 18**

```
Si on prend N= 30 , alors le nombre de classes est donné, par exemple, par
```

_- soit la formule de Sturge_ k= 1 + 3.3 log 10 (30) ~= 6 _,
_- soit la formule de Yule_ k= 2. 54(racine quatrième √30) ~= 6

Nous mentionnons que les deux formules sont presque pareils si N << 200.


Nous rappelons maintenant la définition de l’étendu. De plus, dans le cas continue
nous parlons aussi du pas ou de la longueur de la classe.


**Définition 13**

```console
Le nombre
                  e=x max −x min
s’appelle étendu de X. Dans ce cas, on peut définir le pas par

a i := étendu/nombre de classes  =x max −x min/k
```

#### 3.1.3 Effectif et fréquence d’une classe


**Définition 14**

```
La quantité
             n i := Card {w∈Ω : X(w)∈C i }
s’appelle effectif partiel de C i.

```
# image figure 3.2


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
On appelle l’effectif cumulé de C ila quantité
                        i
                 N i := ∑ nj. 
                       j=1
```

**Définition 17**

```js
On appelle la fréquence cumulée de C ila quantité

                        i
                 F i := ∑ fj
                       j =1
```

**Remarque 12**

```
Nous avons, comme dans le chapitre précédent, les interprétations suivantes :
```
_-_ n _i_ : _est le nombre d’individus dont les valeurs des caractères sont dans la classe_
    C _i,
-_ f _i_ : _est le pourcentage des_ w _tel que_ X(w)∈C _i,
-_ N _i_ : _est égale au Card_ {w: X(w)∈C 1 ∪C 2 ∪...∪C _i_ } _,
-_ F _i_ : _est le pourcentage des w tel que_

```js
                      X(w)∈C 1 ∪...∪C i.
```
### 3.2 Représentation graphique d’un caractère continu

#### 3.2.1 Histogramme des fréquences (ou effectifs)

Nous pouvons représenter le tableau statistique par un histogramme. Nous reportons
les classes sur l’axe des abscisses et, au-dessus de chacune d’elles, nous traçons un rectangle
dont l’aire est proportionnelle à la fréquencef _i_ (ou l’effectifn _i_ ) associée. Ce graphique est
appelé l’histogramme des fréquences (voir Figure 3.3).


# image figure 3.3
```
Figure3.3:Histogramme des fréquences ou des éffctifs.
```

**À suivre.......👩‍🎓👨‍🏫**

