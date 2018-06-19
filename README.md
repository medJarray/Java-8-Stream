"Java-8-Preview" 

*******************************
******** Les Streams **********
** Opérations Intermédiaires **
***** Opérations Terminal *****
*******************************

Cet exemple montre divers extraits de code pour illustrer les opérations Intermédiaires et Terminale sur les Stream.

* Les opérations Intermédiaires :
Les opérations intermédiaires renvoient un autre stream qui vous permet d'appeler plusieurs opérations (intermédiaires ou terminal) sous la forme d'une requête.

Exemple de quelques opérations :
	
	- Filter()
	- Map()
	- Peek()
	- Distinct()
	- Sorted()
	- Limit()

	
* Les opérations Terminales :
Les opérations terminales produisent un résultat non-stream, tel qu'une valeur primitive, une collection ou aucune valeur.
Les opérations de terminal sont généralement précédées d'opérations intermédiaires qui renvoient un autre flux qui permet aux opérations d'être connectées sous la forme d'une requête.

Exemple de quelques opérations :

	- forEach()
	- toArray()
	- reduce()
	- collect()
	- min()
	- max()
	- count()
	- anymatch()
	- allMatch()
	- noneMatch()
	- findFirst()
	- findAny()
	
