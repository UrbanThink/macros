# macros
Répertoire contenant toutes les macros de nos activités avec Warp10


**============== FRENCH =================**

Ce répertoire peut contenir des sous-dossiers avec des macros. 
Une macro est un code Warp10 nous permettant d'exclure une fonctionnalités dans un autre fichier. 
De la même façon qu'une fonction / méthode appelé dans un fichier extérieur et que nous appelons avec un include. 

Si vous souhaitez créer une macro nommée 'test', **vous devez créer un sous-répertoire avant permettant de stocker celle-ci**
Par exemple, ..../macros/myrepo

Ensuite, ajoutez votre macro à l'interieur de ce dossier. Le fichier doit forcément être préfixé de l'extension '.mc2'
Le résultat final sera quelque chose du genre : .../macros/myrepo/test.mc2


Pour appeler la macro dans warpscript, utilisez @myrepo/test



**============== ENGLISH =================**

This directory contains subdirectories with macros.

If you want to create one macro named 'test', **you have to create one subdirectory before to store your macro.**
For example, ..../macros/myrepo

Then, put your macro file into this directory. This file must be suffixed by '.mc2'
At the end, you should have something like that: ..../macros/myrepo/test.mc2

And to reference your macro in WarpScript, use @myrepo/test
