## 1. Distribution des naissances des juges dans le temps

L’analyse de la distribution des années de naissance des juges permet de visualiser la dynamique de recrutement et les évolutions démographiques de la profession sur deux siècles. Les données issues de Wikidata montrent une croissance régulière du nombre de juges nés chaque année à partir du XIXe siècle, avec un pic marqué au XXe siècle, notamment entre 1900 et 1950. Cette augmentation traduit à la fois l’expansion des systèmes judiciaires nationaux et la meilleure documentation des parcours individuels dans les bases de données contemporaines.

**Graphique 1 : Nombre de juges nés par décennie (1800–2000)**

![Distribution des naissances par décennie](https://github.com/TanguyGodat/Judges/blob/main/images/naissances_distribution_10ans_genre.jpg)

On observe :
- Une faible proportion de juges nés avant 1900, puis une croissance rapide jusqu’à la première moitié du XXe siècle.
- Un ralentissement après 1975, lié à la fois à la temporalité des carrières (les juges nommés récemment sont rarement nés après 1975) et à la couverture des données disponibles.

La répartition par genre montre également une évolution significative :
- Jusqu’à 1950, la quasi-totalité des juges sont des hommes.
- À partir de la seconde moitié du XXe siècle, la part des femmes augmente, atteignant près de 40% des naissances de juges dans les années 1970–2000.

**Graphique 2 : Évolution du genre des juges par période**

| Période      | Hommes | Femmes |
|--------------|--------|--------|
| 1876-1900    | 3873   | 57     |
| 1901-1925    | 5029   | 223    |
| 1926-1950    | 7398   | 1113   |
| 1951-1975    | 5097   | 2285   |
| 1976-2000    | 323    | 238    |

Cette féminisation progressive reflète les transformations sociales et l’ouverture des professions juridiques aux femmes dans la plupart des pays.

---

## 2. Répartition des juges par continent

L’étude de la répartition géographique montre une forte concentration des juges en Europe et en Amérique du Nord :  
- **Europe** : 45,7% des juges recensés
- **Amérique du Nord** : 37,4%
- **Asie** : 9,3%
- **Amérique du Sud** : 3,2%
- **Afrique** : 2,3%
- **Océanie** : 2,0%

**Graphique 3 : Répartition des juges par continent**

| Continent      | Effectif | Fréquence (%)|
|----------------|----------|--------------|
| Europe         | 13 260   | 45,7         |
| Amérique Nord  | 10 853   | 37,4         |
| Asie           | 2 706    | 9,3          |
| Amérique Sud   | 927      | 3,2          |
| Afrique        | 667      | 2,3          |
| Océanie        | 597      | 2,0          |

Cette surreprésentation de l’Europe et de l’Amérique du Nord s’explique par la densité des systèmes judiciaires, la taille des bases de données nationales et la disponibilité des informations biographiques dans Wikidata.

L’évolution dans le temps montre que la proportion de juges d’Asie et d’Afrique augmente lentement au XXe siècle, mais reste minoritaire.

---

## 3. Analyse bivariée : genre et continent

Pour mieux comprendre les dynamiques de diversité, une analyse croisée du genre et du continent a été réalisée.  
Les résultats montrent que la féminisation de la magistrature est un phénomène global, mais avec des rythmes très différents selon les continents.

**Graphique 4 : Nombre de juges par genre et continent (toutes périodes confondues)**

| Continent      | Hommes | Femmes | % Femmes |
|----------------|--------|--------|----------|
| Europe         | 11 967 | 1 320  | 9,9      |
| Amérique Nord  | 9 581  | 1 189  | 11,0     |
| Asie           | 2 431  | 274    | 10,1     |
| Afrique        | 486    | 184    | 27,5     |
| Océanie        | 481    | 84     | 14,9     |
| Amérique Sud   | 841    | 85     | 9,2      |
| Eurasie        | 80     | 3      | 3,6      |

Le test du Chi-2 confirme que la répartition du genre diffère significativement selon le continent (p-value < 0,001).  
On note :
- Une féminisation plus marquée en Afrique (27,5%), mais sur des effectifs plus faibles.
- En Europe et Amérique du Nord, la part des femmes progresse fortement à partir de 1950, mais reste minoritaire sur l’ensemble de la période.
- En Asie, Océanie et Amérique du Sud, la progression est plus lente.

**Graphique 4 : Nombre de juges par genre, continent et période(XXe siècle)**

![Proportion de juges par genre, continent et période](https://github.com/TanguyGodat/Judges/blob/main/images/gen_continent_bivariee.jpg)

---

## 4. Analyse de réseaux : affiliations institutionnelles

L’analyse des réseaux d’affiliation des juges met en évidence le rôle central des institutions universitaires et des grandes écoles de droit dans la structuration de la profession.

**Principaux résultats :**
- Les universités (Harvard, Michigan, Yale, etc.) et les écoles de droit sont les principaux nœuds du réseau, avec plusieurs centaines de juges affiliés.
- Les relations les plus fréquentes sont l’éducation (formation initiale), l’emploi (carrière académique ou judiciaire) et l’appartenance à des sociétés savantes ou organisations internationales.
- Les graphes de co-affiliation révèlent des clusters nationaux (ex : réseau nord-américain très dense autour de Harvard Law School et University of Michigan Law School) et des liaisons transnationales plus rares, souvent via des organisations internationales ou des universités européennes de renom.

**Graphique 6 : Exemple de réseau d’affiliations (extrait)**

![Réseau d’affiliations des juges](https://github.com/TanguyGodat/Judges/blob/main/images/biggest_bipartite_component_test.svg)

**Classement des organisations par nombre de juges affiliés :**

| Organisation                         | Type                   | Nombre de juges affiliés |
|--------------------------------------|------------------------|--------------------------|
| Harvard Law School                   | École de droit         | 667                      |
| Federal Court of Justice of Germany  | Cour suprême           | 599                      |
| University of Michigan               | Université             | 281                      |
| Yale Law School                      | École de droit         | 266                      |
| Harvard University                   | Université             | 246                      |

L’analyse des indicateurs de centralité (degree, eigenvector) confirme le rôle pivot de ces institutions dans la structuration des élites judiciaires, notamment en Amérique du Nord et en Europe.

---

## Conclusion

Ce travail met en évidence la forte structuration géographique et institutionnelle de la profession de juge à l’échelle mondiale, ainsi que les évolutions majeures du XXe siècle : féminisation progressive, diversification géographique, et centralité persistante des grandes universités. L’approche par les données ouvertes et les graphes relationnels permet de visualiser ces dynamiques sur le temps.

