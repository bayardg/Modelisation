Première étape : Executer " cmake . " dans le répertoire source

Deuxième étape :

"make doc" : génération de la documentation dans le dossier doc
"make check" : compilation et exécution de tous les tests unitaires placés dans le dossier tests

APRES avoir fait "make check", faire :
"./tests/test_simple", "./tests/test_operator" ou "./tests/test_creator" pour lancer les tests individuellement
