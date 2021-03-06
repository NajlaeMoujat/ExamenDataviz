# Le Cinéma et les français, une longue histoire d'amour.

La France peut, à juste titre, prétendre avoir inventé le concept même du cinéma. Les historiens du cinéma considèrent "L'arrivée d'un train en gare de La Ciotat", le film de 50 secondes des frères Lumière projeté pour la première fois en 1895, comme l'évènement marquant la naissance du cinéma. La France est l'industrie cinématographique la plus performante d'Europe en termes de nombre de films produits par an, avec un record de plus de 300 longs métrages produits en 2015.

# Sommaire 

1. [Paris, capitale du Cinéma à travers le monde](#T1)
2. [Le festival : un vecteur important de l'image animée](#T2)
3. [Les meilleures audiences en salles depuis 1945](#T3)
4. [Les genres les plus appréciés par les français depuis 1945](#T4)
5. [Requêtes Wikidata](#T5)
6. [Affinage et nettoyage des dataset](#T6)
7. [Conclusion](#T7)


## 1. Paris, capitale du Cinéma à travers le monde. <a id="T1"></a>


Paris possède la plus forte densité de cinémas au monde, avec près de 420 écrans de cinéma, la capitale s'est imposée comme une ville dont le cinéma est profondément ancré dans sa culture. 

C'est d'ailleurs à Paris qu'a eu lieu la toute première projection de film au monde en 1895. Depuis, Paris n'a cessé de prospérer en tant que visage mondial du cinéma, avec ses 364 salles présentant non seulement des productions françaises indépendantes et grand public, mais aussi les meilleures œuvres cinématographiques du monde entier.


### A - Les Cinémas en France 


Jeu de données des cinémas actifs en France :
<iframe src="https://data.culture.gouv.fr/explore/embed/dataset/etablissements-cinematographiques/table/?location=5,46.53754,2.40395&dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQ09VTlQiLCJzY2llbnRpZmljRGlzcGxheSI6dHJ1ZSwiY29sb3IiOiIjOGRhMGNiIn1dLCJ4QXhpcyI6InJlZ2lvbl9hZG1pbmlzdHJhdGl2ZSIsIm1heHBvaW50cyI6NTAsInNvcnQiOiIiLCJjb25maWciOnsiZGF0YXNldCI6ImV0YWJsaXNzZW1lbnRzLWNpbmVtYXRvZ3JhcGhpcXVlcyIsIm9wdGlvbnMiOnt9fX1dLCJ0aW1lc2NhbGUiOiIiLCJkaXNwbGF5TGVnZW5kIjp0cnVlLCJhbGlnbk1vbnRoIjp0cnVlfQ%3D%3D&static=false&datasetcard=false" width="800" height="300" frameborder="0"></iframe>


Pour commencer mon étude, j'ai utilisé ce premier jeu de données qui représente à l'état brut les données des cinémas actifs en France. Puis par la suite j'ai affiné le jeu de données sur OpenRefine afin de ne garder que les éléments les plus pertinents et prépondérants dans mon analyse du cinéma.

Ce jeu de données révèle que la France dispose d'un très large pannel de cinémas au sein de son territoire, non seulement les films exposés sont considérablement variés mais l'audience française encourage l'augmentation de séances de cinémas qui sont déjà nombreuses afin de satisfaire son public très demandeur.



Classement des établissements cinématographiques par département en 2018 :

<iframe frameborder="0" width="800" height="600" src="https://data.opendatasoft.com/map/embed/frequentationcine/?&static=false&scrollWheelZoom=false"></iframe>

Comme nous le savons, le cinéma occupe une grande place dans la culture française. Ainsi le classement des établissements cinématographiques par département démontre l'ascendence du cinéma sur l'ensemble des régions françaises. Les taux de concentration des départements les plus forts sont dispersés un peu partout en France, du nord (59, 75, 77, 78, 91, 92, 94) au sud (83), de l'ouest (44, 35, 33) à l'est (38, 73). Néanmoins, on note une très forte concentration des salles de cinémas en Ile-de-France notamment à Paris avec près de 405 écrans et 84 établissements comme énoncés plus haut. 
Ces fortes concentrations s'expliquent en partie par la présence de nombreux évènements tels que le festival de Cannes, César, Reims Polar ...
En effet, la France est bien connue pour ces nombreux festivals de films, qui dépassent largement ceux des autres pays européens.



## 2. Le festival, un acteur important de l'image animée en France. <a id="T2"></a>


<iframe frameborder="0" width="800" height="600" src="https://data.opendatasoft.com/map/embed/geolocalisation_des_cines_actifs/?&static=false&scrollWheelZoom=false"></iframe>

Paris compte 88 cinémas au total et un écran de cinéma pour 6 000 habitants, alors que la France entière compte un écran pour 11 000 habitants.
Si la France est incontestablement l'une des capitales mondiales du cinéma, cette statistique montre que Paris apprécie particulièrement l'art et le divertissement du cinéma. Pour mettre le reste du monde en perspective, les États-Unis comptent un écran pour 7 400 personnes, et le Royaume-Uni et l'Allemagne un écran pour 17 000 personnes. 

De nombreuses manifestations cinématographiques très suivies ont lieu chaque année à Paris et mettent en lumière les productions locales. Parmi ces événements figurent les Paris Art and Movie Awards, le Festival du film indépendant de Paris et le Festival européen du film indépendant. Ces événements sont importants car ils permettent de faire connaître le cinéma produit en France et à Paris en particulier, en soulignant les réalisations nationales et en attirant un public plus large au cinéma.


## 3. Les meilleures audiences en salles depuis 1945. <a id="T3"></a>


Fréquentation des cinémas :

<iframe title="Fréquentation des salles de cinéma en France " aria-label="Interactive line chart" id="datawrapper-chart-5rT3e" src="https://datawrapper.dwcdn.net/5rT3e/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(e){if(void 0!==e.data["datawrapper-height"]){var t=document.querySelectorAll("iframe");for(var a in e.data["datawrapper-height"])for(var r=0;r<t.length;r++){if(t[r].contentWindow===e.source)t[r].style.height=e.data["datawrapper-height"][a]+"px"}}}))}();
</script>
 

Jeu de données des cinémas :
  
<iframe title="Jeu de données recensant la fréquentation des salles de cinéma" aria-label="Tableau" id="datawrapper-chart-giWSt" src="https://datawrapper.dwcdn.net/giWSt/3/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="783"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(e){if(void 0!==e.data["datawrapper-height"]){var t=document.querySelectorAll("iframe");for(var a in e.data["datawrapper-height"])for(var r=0;r<t.length;r++){if(t[r].contentWindow===e.source)t[r].style.height=e.data["datawrapper-height"][a]+"px"}}}))}();
</script>
  
  Ce tableau nous permet de voir l'évolution des places d'entrées au cinéma en France. De 1938 à 1958, la fréquentation des salles de cinéma en France était à son apogée ( sauf pendant la période de la seconde guerre mondiale ). Durant cette période, les cinémas représentaient la nouveauté et la modernité, d'où la forte influence. Puis les années qui suivirent il y eut un déclin dû à l'apparition de la télévision ( nouveau concept ) qui s'est imposé et a mis à l'écart le cinéma.

  
## 4. Les genres les plus appréciés par les français depuis 1945. <a id="T4"></a>
 
Dans cette étude du cinéma et des français, il est intéréssant d'observer quels sont les genres cinématographiques les plus populaires auprès des spectateurs français. Ainsi, la réalisation d'un classement de ces genres est très pertinente dans la mesure où elle met en lumière les goûts cinématographiques du peuple français depuis 1945 mais aussi d'en savoir plus sur les films les plus appréciés de ces derniers.

<iframe src='https://flo.uri.sh/visualisation/8647073/embed' title='Interactive or visual content' class='flourish-embed-iframe' frameborder='0' scrolling='no' style='width:100%;height:600px;' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/8647073/?utm_source=embed&utm_campaign=visualisation/8647073' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

<iframe src='https://flo.uri.sh/visualisation/8647794/embed' title='Interactive or visual content' class='flourish-embed-iframe' frameborder='0' scrolling='no' style='width:100%;height:600px;' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/8647794/?utm_source=embed&utm_campaign=visualisation/8647794' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

 
 L'évolution des différents types de genres cinématographiques au fil des années :
 
<iframe style="width: 80vw; height: 50vh; border: none;" src="https://query.wikidata.org/embed.html#SELECT%20%3Fannee%20%28COUNT%28%3F_genre%29%20AS%20%3FNombredeFilm%20%29%28SAMPLE%28%3F_genreLabel%29%20AS%20%3Fgenre%20%29%0AWHERE%20%7B%0A%3Fitem%20wdt%3AP31%20wd%3AQ11424.%20%20%0A%3Fitem%20wdt%3AP577%20%3Fdate_publication.%0A%3Fitem%20wdt%3AP136%20%3F_genre.%20%0A%3F_genre%20rdfs%3Alabel%20%3F_genreLabel.%0ABIND%28str%28YEAR%28%3Fdate_publication%29%29%20AS%20%3Fannee%29%0AFILTER%28%28LANG%28%3F_genreLabel%29%29%20%3D%20%22fr%22%29%20%0A%0AFILTER%20%28%28%3Fdate_publication%20%3E%3D%20%221945-01-01T00%3A00%3A00Z%22%5E%5Exsd%3AdateTime%29%20%26%26%20%28%3Fdate_publication%20%3C%3D%20%221990-12-31T00%3A00%3A00Z%22%5E%5Exsd%3AdateTime%29%29%0A%7D%0AGROUP%20BY%20%3F_genreLabel%20%3Fannee%0AORDER%20BY%20%3Fannee" referrerpolicy="origin" sandbox="allow-scripts allow-same-origin allow-popups" ></iframe>
 
Les films dramatiques occupent la première place, suivient des films de comédie. Ces deux genres sont les plus appréciés par l'audience française de 1945 à 1990 ( une période limitée car la requête Wikidata ne peut supporter une très longue période).

Avec cette datavisualisation, j’ai rassemblé par genre et titre les plus gros succès au box-office. Les meilleures audiences sont les comédies ensuite vient l’animation, le drame puis la fiction, plus loin derrière on note des genres plus variés comme la comédie musicale, drame/ comédie.
 
## 5. Requêtes Wikidata <a id="T5"></a>

 
  Requête :
  
````sparql

#defaultView:Map
SELECT ?film ?filmLabel ?lieu_histoire ?lieu_histoireLabel ?coordonees 
WHERE 
{
?film wdt:P31 wd:Q11424 . 
?film wdt:P840 ?lieu_histoire .
?lieu_histoire wdt:P625 ?coordonees . 
  
SERVICE wikibase:label { bd:serviceParam wikibase:language "[AUTO_LANGUAGE],fr". }
}
````
 
Cette première requête permet de représenter les films positionnés en fonction des lieux de leur histoire sur une carte géographique mondiale.
 
  Résultat :
  
<iframe style="width: 80vw; height: 50vh; border: none;" src="https://query.wikidata.org/embed.html#%23Les%20films%20positionn%C3%A9s%20sur%20une%20carte%20en%20fonction%20des%20lieux%20de%20leur%20histoire%0A%23defaultView%3AMap%0ASELECT%20%3Ffilm%20%3FfilmLabel%20%3Flieu_histoire%20%3Flieu_histoireLabel%20%3Fcoordonees%20WHERE%20%7B%0A%3Ffilm%20wdt%3AP840%20%3Flieu_histoire%20%3B%0Awdt%3AP31%20wd%3AQ11424%20.%0A%3Flieu_histoire%20wdt%3AP625%20%3Fcoordonees%20.%0ASERVICE%20wikibase%3Alabel%20%7B%20bd%3AserviceParam%20wikibase%3Alanguage%20%22%5BAUTO_LANGUAGE%5D%2Cfr%22.%20%7D%0A%7D" referrerpolicy="origin" sandbox="allow-scripts allow-same-origin allow-popups" ></iframe>
  
Ainsi nous pouvons constater grâce à cette carte que les lieux d'histoire des films se déroulent principalement en Europe et se concentrent bien dans les alentours du territoire français.
  
  Requête :
  
````sparql
SELECT ?annee (COUNT(?_genre) AS ?NombredeFilm )(SAMPLE(?_genreLabel) AS ?genre )
WHERE 
{
?item wdt:P31 wd:Q11424.  
?item wdt:P577 ?date_publication.
?item wdt:P136 ?_genre. 
?_genre rdfs:label ?_genreLabel.
BIND(str(YEAR(?date_publication)) AS ?annee)
FILTER((LANG(?_genreLabel)) = "fr") 

FILTER ((?date_publication >= "1945-01-01T00:00:00Z"^^xsd:dateTime) && (?date_publication <= "1990-12-31T00:00:00Z"^^xsd:dateTime))
}
GROUP BY ?_genreLabel ?annee
ORDER BY ?annee
````
 Cette deuxième requête établit un classement du nombre de films par genre et par année de 1945 à 1990. Il fut nécessaire d'établir une période exacte et relativement courte afin que la requête puisse aboutir.
                                                                                                            
  Résultat :
                                                                                                            
<iframe style="width: 80vw; height: 50vh; border: none;" src="https://query.wikidata.org/embed.html#SELECT%20%3Fannee%20%28COUNT%28%3F_genre%29%20AS%20%3FNombredeFilm%20%29%28SAMPLE%28%3F_genreLabel%29%20AS%20%3Fgenre%20%29%0AWHERE%20%7B%0A%3Fitem%20wdt%3AP31%20wd%3AQ11424.%20%20%0A%3Fitem%20wdt%3AP577%20%3Fdate_publication.%0A%3Fitem%20wdt%3AP136%20%3F_genre.%20%0A%3F_genre%20rdfs%3Alabel%20%3F_genreLabel.%0ABIND%28str%28YEAR%28%3Fdate_publication%29%29%20AS%20%3Fannee%29%0AFILTER%28%28LANG%28%3F_genreLabel%29%29%20%3D%20%22fr%22%29%20%0A%0AFILTER%20%28%28%3Fdate_publication%20%3E%3D%20%221945-01-01T00%3A00%3A00Z%22%5E%5Exsd%3AdateTime%29%20%26%26%20%28%3Fdate_publication%20%3C%3D%20%221990-12-31T00%3A00%3A00Z%22%5E%5Exsd%3AdateTime%29%29%0A%7D%0AGROUP%20BY%20%3F_genreLabel%20%3Fannee%0AORDER%20BY%20%3Fannee" referrerpolicy="origin" sandbox="allow-scripts allow-same-origin allow-popups" ></iframe>
  
## 6. Affinage et nettoyage des dataset <a id="T6"></a>
  
L'utilisation d'OpenRefine a été bénéfique puisqu'il m'a permis de filtrer, organiser et uniformiser mon jeu de données afin de l'exploiter plus facilement. 
OpenRefine m'a permis d'organiser la mise en forme de mon jeu de données comme par exemple la nomenclature non uniforme que j'ai constaté au niveau des pays. Ainsi, j’ai uniformisé le tout par le biais de la fonction « grouper et éditer » et « remplacer ».
J’ai fait le choix stratégique de ne retenir que les entrées les plus pertinentes et d'éliminer les autres afin de ne pas allourdir mon jeu de données. 
J’ai choisi une période charnière de mon étude, j’ai retiré les autres données car elles demeuraient inexploitées; pour se faire j’ai choisi de masquer certaines colonnes notamment celles relatives au volet financier (recette en million d'euros des films) 

Effectivement, dans le cadre de mon étude je ne me suis pas intéressée aux bénéfices financiers mais plutôt à l’aspect culturel du cinéma. Par ailleurs, il y a certes des données dont je disposais mais que j’ai choisi d’occulter, toutefois il y a des aspects que j’aurais apprécié mettre en évidence mais qui n’étaient pas forcément présents, je pense notamment à la présence des années 2021 et 2022 mettant en avant le déclin des entrées au cinéma dans le cadre dela situation sanitaire mondiale ( fermeture des lieux culturels, confinement, couvre-feu ... ). Malgré mes recherches de dataset français, anglais, hispanique, je n’ai rien trouvé de similaire pour mon étude, c'est d'ailleurs ce qui m'a poussé à alimenter moi-même mon jeu de données par le biais de l'ajout de la colonne "genre" qui semblait selon moi intéressante à approfondir, dans le but de savoir quels sont les genres les plus appréciés des français. J’ai pris l’initiative d’ajouter 200 entrées au jeu de données « les meilleurs succès du cinéma depuis 1945 » manuellement, ce qui a supposé préalablement un effort de documentation pour trouver le meilleur site habilité à qualifier le genre du fim en question. Après cette action, j’ai dû faire un travail d'affinage et nettoyage sur OpenRefine pour que tous ces genres ajoutés soient uniformes de sorte à être exploité par la suite dans le cadre d’une datavisualisation.

Avec OpenRefine, je me suis assurée de n’avoir aucun doublon car mon jeu de données était assez conséquent.
 
 Ci-dessous vous pourrez observer l'un des fichiers OpenRefine que j'ai utilisé.


```sparql
  [
  {
    "op": "core/column-rename",
    "oldColumnName": "entrées (millions)2",
    "newColumnName": "entrées (en millions)",
    "description": "Rename column entrées (millions)2 to entrées (en millions)"
  },
  {
    "op": "core/column-rename",
    "oldColumnName": "nationalité1",
    "newColumnName": "nationalité",
    "description": "Rename column nationalité1 to nationalité"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "nationalité",
    "expression": "value",
    "edits": [
      {
        "from": [
          "FR / BE"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "FR/BE"
      }
    ],
    "description": "Mass edit cells in column nationalité"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "nationalité",
    "expression": "value",
    "edits": [
      {
        "from": [
          "IT/FR"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "FR/IT"
      }
    ],
    "description": "Mass edit cells in column nationalité"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "nationalité",
    "expression": "value",
    "edits": [
      {
        "from": [
          "AT"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "AT"
      }
    ],
    "description": "Mass edit cells in column nationalité"
  },
  {
    "op": "core/column-addition",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "baseColumnName": "titre",
    "expression": "cell.recon.match.id",
    "onError": "set-to-blank",
    "newColumnName": "Genre",
    "columnInsertIndex": 2,
    "description": "Create column Genre at index 2 based on column titre using expression cell.recon.match.id"
  },
  {
    "op": "core/row-removal",
    "engineConfig": {
      "facets": [
        {
          "type": "list",
          "name": "Lignes étoilées",
          "expression": "row.starred",
          "columnName": "",
          "invert": false,
          "omitBlank": false,
          "omitError": false,
          "selection": [
            {
              "v": {
                "v": true,
                "l": "true"
              }
            }
          ],
          "selectBlank": false,
          "selectError": false
        }
      ],
      "mode": "row-based"
    },
    "description": "Remove rows"
  }
]
```
  
## 7. Conclusion <a id="T7"></a>
  
Pour la plupart des cinéphiles anglophones, une grande partie du cinéma français pourrait être considérée comme du cinéma d'art et d'essai.
Cela s'explique par le fait que la France ne produit pas seulement des films pour faire du profit au box-office comme le font de nombreux autres marchés cinématographiques.
  
Les Français utilisent l'expression "cinéma d'art et d'essai" pour décrire les films qui ont de l'ambition, mais dont le but artistique et expressif l'emporte sur la rentabilité.
Paris accueille ces films spéciaux grâce à sa forte culture cinématographique et au grand nombre de cinémas indépendants qui sont des lieux parfaits pour les projections.

Contrairement à France, les autres pays ont tendance à séparer les films d'art et d'essai des superproductions en les projetant dans des cinémas différents, mais les cinémas parisiens indépendants comblent le fossé et donnent aux cinéphiles l'occasion unique de voir tout l'éventail de ce qui est proposé. Cela souligne l'attitude ouverte de la France à l'égard des films et l'appréciation de la population française pour toutes les formes de grand écran.
 
 
J’ai pris plaisir à faire cette étude car je suis une véritable cinéphile, j’en ai appris davantage sur le sujet, en découvrant l’importance que le cinéma occupe au sein du patrimoine culturel français. C’est une expérience nouvelle car je n’ai jamais manipulé de jeux de données aussi importants auparavant. L’air de rien des outils tels que OpenRefine sont d’une grande aide. J’ai apprécié le travail qu’il est possible de faire via la datavisualisation en terme de représentation. La donnée a un véritable poids,un graphisme bien pensé est bien plus évocateur qu'une quantité de données : Flourish et Datawrapper  m'ont permis d'opter pour des datavisualisations relativement claires et attrayantes en terme de mise en forme.
 
Néanmoins, j’ai toutefois été confronté à certaines limites d'ordre technique mais également en termes de ressources car les jeux de données propre au cinéma français demeurent peu nombreux, mis à part ceux mis à disposition par le Centre National de Cinéma et de l’Image Animée et quelques jeux de données mis à disposition via data.gouv.fr. Ces derniers ne sont pas monnaie courrante dans le domaine du cinéma. 
Dans les jeux de donées qu'il m'a été donné d'observer, il manquait des paramètres tel que le genre qui me semblait relativement pertinent dans le cadre d'une datavisulation afin de mettre en lumière les genres les plus appréciés par les français depuis 1945 par exemple.
 
Malgré avoir utilisé OpenRefine et avoir uniformisé les jeux de données parfois il y a des données qui apparaissaient en doublon ou en diverses catégories distinctes alors qu’il s’agissait de la même nomenclature pour laquelle j'avais apporté une attention toute particulière à la casse. Ces valeurs apparaissant plusieurs fois lors de la réalisation de datavisulations, elles constituaient des biais évidents, ce qui m’a conduit à ne pas les représenter.

  
