Pourquoi les tests mettent autant de temps ?

Parce ce que le tableau que nous somme en train de trier contiend une grande quantité de valeur, d'ou le long temps d'execution du test "isWellSortedLargeArrays".

A. S'assurer que le code de l'application ne comporte pas d'erreurs

2-Qu'avez-vous remarqué ? 
Après l'implémentation de la méthode reverseSort ligne 20, l'execution du test ne fonctionne plus.
message d'erreur : 20:12 java: class, interface, or enum expected
Le test ne s'execute pas car la méthode a été ajouté en dehors de la classe "SortAlgorithms".