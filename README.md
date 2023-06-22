# grand_oral modeleur volumique parametrique

## questions

Comment la modélisation 3D révolutionne la construction mécanique, industrielle et civil ?


## modélisation 3D : SolidWorks, OnShape, matrices, STL

qu'est-ce qu'un fichier STL : https://www.sculpteo.com/fr/centre-apprentissage/creer-un-fichier-3d/quest-ce-quun-fichier-stl/

pourquoi et avantages de la modélisation 3D : https://www.autodesk.fr/solutions/3d-modeling-software#:~:text=La%20mod%C3%A9lisation%203D%20est%20le,%C3%A9galement%20appel%C3%A9%20%C2%AB%20mod%C3%A8le%203D%20%C2%BB.

ajouter la notion de rdm avec matrice etc .. dans les fonctions de la modélisation.
permet la réalisation technique des choses que l'on dne pouvait pas faire avant (imprimante 3D)

## intro
Durant notre année de terminal, en SI, nous avons à réaliser un projet. Le projet de notre groupe ( 6 ) était la construction d'un bras robot. Ainsi nous nous sommes rapidement rendus compte que les dessins techniques sont indispensables pour la communication, la visualisation, la fabrication, la construction, la conformité aux normes et la documentation. Ils permettent d'assurer la précision, la cohérence et la compréhension des projets et des produits tout au long de leur cycle de vie. Evidemment, pouvoir visualiser notre bras robot en 3 dimension nous était bien pratique. Et evidemment ce besoin est applicable à de nombreux domaines. Ce besoins ne date pas d'hier comme nous pouvons l'observer avec les divers croquis de Leonard de Vinci. Avec l'apparition de l'informatique, ces dessins technique ont ensuite été informatisé avec l'apparition d'un semblant de 3D mais qui n'est alors que de la perspective, les dessins ne sont définis que sur 2 axes; y et x. Jusque dans les années 1960-1970 ou les premières techniques de modélisation 3D apparaissent avec l'émergence de la conception assistée par ordinateur (CAO). J'ai alors trouvé interessant de me demander comment la modélisation 3D révolutionne la construction mécanique, industrielle et civil ?

## Qu'est-ce que la modélisation 3D ?
Commençons par une définition de modélisation 3D. La modélisation 3D est le processus de création de représentations tridimensionnelles d'un objet ou d'une surface. Les modèles 3D sont créés dans un logiciel de modélisation 3D informatisé, que nous explorerons un peu plus tard. 
Au cours du processus de modélisation 3D, vous pouvez déterminer la taille, la forme et la texture d'un objet. Le processus fonctionne avec des points, des lignes et des polygones pour créer les formes 3D dans le logiciel. Certains pourraient alors se demander ce qu'est la difference entre 2D et 3D puisqu'au final cela reste affiché sur un écran plat, donc théoriquement ça reste 2D. Et bien, comme je l'ai légèrement évoqué dans mon introduction, la 2D se défini par, 2 dimensions. Pour la 3d, on rajoute une autre dimension, la hauteur. Ainsi, même si votre objet et affiché à " plat " , lorsque vous enregistrer votre fichier, celui comporte bien 3 dimensions pour chaque point ou vecteurs.

## A quoi sert la modélisation 3D ? 
De nombreuses industries utilisent la modélisation 3D pour une gamme de projets ; il y a probablement beaucoup d'éléments modélisés en 3D que nous utilisons sans même nous rendre compte de leur implication. Avec la modélisation 3D, les possibilités sont infinies. C'est un support vraiment polyvalent qui peut être utilisé pour un éventail de domaines différents. avec notamment, le domaine des jeux vidéos, les modèles 3D sont utilisés pour créer des personnages, des  des décors, des accessoires et des mondes entiers afin que l'expèrience de jeu soit le plus immersive possible. La modélisation 3D est également utilisé dans le domaine médical pour fabriquer des prothèses et des implants sur mesure et pour créer des modèles anatomiquement corrects pour la planification chirurgicale. Evidemment, cela sert également dans l'architecture, l'animation, l'impression 3D evidemment et m^me la simple conception d'objet ... <br>
Ce qui nous interesse ici est la construction mécanique, industrielle et civil. Et bien dans un premier temps donc, la modélisation 3D sert à visualiser .....



~~La conception des produits
De nombreux produits que nous voyons autour de nous dans notre vie quotidienne auraient eu une certaine implication dans la modélisation 3D. En créant un modèle 3D virtuel de votre produit avant sa création physique, nous pouvons identifier les erreurs et ajuster le produit en conséquence. Même le fait de pouvoir voir la taille de l'objet par rapport à d'autres produits peut faire une énorme différence dans le processus de production.

Il est également utile pour présenter des idées de produits aux investisseurs, car les produits peuvent être présentés sous un angle de 360 ​​degrés, permettant aux parties prenantes d'envisager pleinement le résultat final. C'est aussi moins de gaspillage que de créer des échantillons et de fabriquer à plusieurs reprises des faux produits, et la conception de produits durables est un grand pas dans la bonne direction.~~

## Le principe de base du fonctionnement de la modélisation 3D repose sur la création d'un modèle mathématique d'un objet en trois dimensions. Voici les étapes générales impliquées dans ce processus :

Modélisation : 
par maillage : La modélisation par maillage, également connue sous le nom de modélisation polygonale, est l'une des techniques de modélisation 3D les plus couramment utilisées. Elle consiste à représenter des objets en utilisant un réseau de polygones interconnectés, appelé maillage. Ces polygones sont généralement des triangles, mais ils peuvent aussi être des quadrilatères ou d'autres formes. 
Création de primitives : Le processus commence souvent par la création de formes de base, telles que des cubes, des sphères, des cylindres, etc. Ces formes de base sont utilisées comme point de départ pour construire des objets plus complexes.
Édition et manipulation : Les polygones du maillage sont ensuite édités et manipulés pour former la géométrie souhaitée. Cela peut impliquer l'extrusion, la translation, la rotation, le redimensionnement, la subdivision, la suppression de polygones, etc. Ces opérations permettent de donner forme à l'objet et de créer des détails.
Raffinement et ajustements : Le maillage est affiné en ajustant les arêtes, les sommets et les faces pour obtenir une forme plus précise et régulière. Des outils de lissage, de fusion, de découpage, etc., sont utilisés pour améliorer la qualité de la géométrie.
La modélisation par géométries : Elle consiste à assembler des formes simples (cubes, cônes, cylindres, etc.) afin d'en créer des plus complexes.
La modélisation voxel (abréviation de "volume pixel") est une technique de modélisation 3D qui se base sur la représentation d'objets à l'aide d'une grille tridimensionnelle de voxels. Les voxels sont des éléments volumétriques analogues aux pixels en 2D, mais qui occupent un espace tridimensionnel. Chaque voxel représente un point dans l'espace 3D et possède des attributs tels que la position, la couleur, la transparence, la densité, etc.

- volumique paramétrique : bases = courbes 2D( + : possibilité d’éditer à tout moment les dimensions de l’objet qui va se répercuter sur toutes les autres étapes de manière à s’adapter ) ( - : ne se prête pas à toutes les géométries. Exemple de la souris où chaque surface a des courbures indépendantes et qui lui sont propres)
- Volumique surfacique : bases = courbes 3D ( + : exemple de la souris )
- Volumique polygonale : 
- Sculpture 



Texturage : Une fois que la géométrie de base est créée, des textures peuvent être appliquées à la surface de l'objet pour lui donner une apparence réaliste. Les textures sont des images qui sont "enveloppées" autour de la surface de l'objet pour ajouter des détails tels que la couleur, les motifs, les reflets, etc. Les artistes 3D peuvent créer leurs propres textures ou utiliser des bibliothèques de textures existantes.

Éclairage : L'éclairage est un aspect essentiel de la modélisation 3D. Il permet de simuler la façon dont la lumière interagit avec l'objet virtuel. Des sources de lumière peuvent être ajoutées à la scène virtuelle pour illuminer l'objet sous différents angles, créant ainsi des ombres, des reflets et des effets d'éclairage réalistes. Les logiciels de modélisation 3D offrent généralement des options pour ajuster les propriétés de l'éclairage, comme la couleur, l'intensité et la direction des sources lumineuses.

Animation : Si nécessaire, des objets 3D peuvent être animés en leur donnant des mouvements et des transformations au fil du temps. Par exemple, des personnages animés dans un film ou un jeu vidéo nécessitent des squelettes et des contrôles pour créer des mouvements réalistes. Les logiciels d'animation 3D permettent de définir des trajectoires de mouvement, des transitions entre les états et d'autres paramètres pour créer des animations fluides.

Rendu : La dernière étape consiste à effectuer le rendu final de la scène 3D. Cela implique le calcul de chaque pixel de l'image finale en fonction de la géométrie, des textures, de l'éclairage et des autres propriétés de la scène. Le rendu peut être effectué en temps réel, comme dans les jeux vidéo, ou en utilisant des logiciels de rendu plus complexes pour des résultats de haute qualité, comme dans l'industrie du cinéma.
