# Dr Death

## Microsoft Power BI Desktop

**Qu'est-ce que Power BI ?**</br>
C'est un logiciel de visualisation de données regroupant plusieurs fonctionnalités tel que
la création de visuels (tableaux de bords, graphiques, cartes) qui s'alimentent à partir de plusieurs sources de données.</br>
Elle permet de collecter, traiter, analyser et visualiser les données de manière efficace et dynamique.</br>

Sortie en été 2015, cet outil est récent, régulièrement mis à jour ce qui lui permet de rester **leader** sur le marché de l'analyse
et la visualisation de données pour but stratégique.


## Contexte des données et la problématique étudiée

Harold Shipman était un médecin en apparence respecté exerçant à Hyde,
dans le Grand Manchester. Derrière cette façade de médecin doux et
compétent, se cachait en fait une vérité sinistre. Entre 1975 et 1998, il a injecté
au moins 215 doses de ses patients, pour la plupart âgés, à une surdose
massive d'opiacés.

Nos données fournies se concentrent dans 2 fichiers CSV ("shipman-confirmed-victims.csv" & "shipman-times-comparison.csv").

Dans **shipman-confirmed-victims.csv** :
> - DateofDeath,
> - Name,
> - Age,
> - PlaceofDeath,
> - Decision,
> - yearOfDeath,
> - gender,
> - fractionalDeathYear,
> - ageBracket,
> - gender2

Dans **shipman-times-comparison.csv** :
> - Hour,
> - Shipman,
> - Comparison

---

A partir de ces données, la problématique étudiée est : </br>
**Quels types de personnes Harold Shipman a-t-il assassinées, et quand sont-elles mortes ?**

---

Grâce aux graphiques produits avec Power BI, on peut remarquer que la majorité des victimes de Shipman :
- est âgé entre 75 et 84 ans (45%)
- est une femme (83%)
- est décédé chez soi et entre 1995 et 1997 (204 victimes et environ 30 par année)
- 15 victimes sur 215 ont été officiellement déclaré

On remarque également que les déclarations de Shipman sont bien moins éparpillés que les déclarations de décès des autres medecins.
Lui a tendance à déclarer en majorité vers 15h/16h l'heure de décès, ce qui amène un doute.

De plus, les valeurs retenues dans la heatmap du notebook Jupyter sont : l'âge et l'heure et la date du décès.

---

**Conclusion**
Harold Shipman assassine un certain type de personne en majorité. Ce sont les dâmes âgées entre 75 et 84 ans (qui font partie des 15 victimes officielles).
Mais également des hommes de tout les âges (supérieur à 45 ans), qui sont au nombre de 37, tous faisant partie des victimes illégales non officielles car
incinérées. Ses victimes les plus jeunes ont au minimum 40 ans. 

Il a commencé sa série de meurtre en 1975. Et a continué jusqu'à 1998. Les années où il a été le plus actif dans sa série de meurtres ont été 1995, 1996 et 1997 avec 30 à 37 meurtres par an.
