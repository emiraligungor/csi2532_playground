# csi2532_playground
# Laboratoire 4
##Systèmes univeritaire
Une base de données universitaire contient
des informations sur les professeurs
(identifié par le numéro de sécurité sociale
ou SSN) et les cours (identifié par courseid).
Les professeurs donnent des cours; chacun
de les situations suivantes concernent
l'ensemble de relation teaches.
S
| Nom              | Numéro d'étudiant | Email               |
| ---------------- | ----------------- | ------------------- |
| Emirali Gungor  | 300157209       | egung014@uottawa.ca |

### ER 1
Les professeurs peuvent enseigner le
même cours sur plusieurs semestres et seule
la plus récente doit être enregistrée.
![ERDiagram](lab04/er01.png)

### ER 3
Chaque professeur enseigne exactement
un cours (ni plus, ni moins).
![ERDiagram](lab04/er03.png)

### ER 5
Les professeurs peuvent enseigner le
même cours sur plusieurs semestres et
chaque doit être enregistrée.
![ERDiagram](lab04/er05.png)

### ER 6
Supposons maintenant que certains cours
puissent être enseignés conjointement par
une équipe de professeurs, mais il est
possible qu'aucun professeur dans une
équipe ne puisse enseigner le cours.
Modélisez cette situation en introduisant des
ensembles d'entités et des ensembles de
relations supplémentaires si nécessaire.
![ERDiagram](lab04/er06.png)


# Diagramme Relationnel

#### Diagramme 1
![ERDiagram](lab04/diagram01.png)

#### Diagramme 3
![ERDiagram](lab04/diagram03.png)

#### Diagramme 5
![ERDiagram](lab04/diagram05.png)

#### Diagramme 6
![ERDiagram](lab04/diagram06.png)

# Schéma Relationnel (SQL)


#### Schema 1
![ERDiagram](lab04/schema01.sql)

#### Schema 3
![ERDiagram](lab04/schema03.sql)

#### Schema 5
![ERDiagram](lab04/schema05.sql)

#### Schema 6
![ERDiagram](lab04/schema06.sql)
