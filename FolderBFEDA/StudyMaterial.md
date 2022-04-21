
GitHub
Git Rebase and Git Squash 


Realizar un rebase a una rama (branch) en Git es una forma de mover la totalidad de una rama a otro punto del árbol

Para realizar rebase, asegúrate de tener todos los commits que quieras en el rebase en tu rama master. Revisar la rama en la que quieres hacer el rebase y escribe git rebase master (donde master es la rama en la que quieres hacer el rebase).

La reorganización es el proceso de mover o combinar una secuencia de confirmaciones en una nueva confirmación base. La reorganización es muy útil y se visualiza fácilmente en el contexto de un flujo de trabajo de ramas de funciones. El proceso general se puede visualizar de la siguiente manera:


https://wac-cdn.atlassian.com/dam/jcr:4e576671-1b7f-43db-afb5-cf8db8df8e4a/01%20What%20is%20git%20rebase.svg?cdnVersion=309

El motivo principal por el que llevar a cabo una fusión mediante cambio de base es para mantener un historial del proyecto lineal. Por ejemplo, piensa en una situación en la que la rama principal haya progresado desde que empezaste a trabajar en una rama de función. Quieres incorporar las últimas actualizaciones de la rama principal a tu rama de función, pero quieres mantener el historial de la rama limpio para que parezca que has estado trabajando a partir de la rama principal más reciente. Esto proporciona el beneficio posterior de una fusión limpia de la rama de función de nuevo a la rama principal. ¿Por qué queremos mantener un "historial limpio"? Los beneficios de tener un historial limpio se vuelven evidentes cuando se realizan operaciones de Git para investigar la introducción de una regresión.

Se identifica un error en la rama principal. Una función que funcionaba perfectamente ahora falla.
Un desarrollador examina el historial de la rama principal usando git log. Dado que el historial está "limpio", el desarrollador puede deducir rápidamente qué ha ocurrido en el historial del proyecto.
El desarrollador no puede identificar mediante git log cuándo se introdujo el error, por lo que ejecuta un comando git bisect.
Dado que el historial de Git está limpio, git bisect tiene un conjunto perfeccionado de confirmaciones para comparar cuando se busca la regresión. El desarrollador encuentra rápidamente la confirmación que introdujo el error y puede actuar en consecuencia.

Hacer squash en Git, (“aplastar”), hace que nuestra rama a mergear (a la que haremos un pull request) se componga de un solo commit de esta manera mergearemos un solo paquete de código a nuestra rama de desarrollo que contendrá una funcionalidad completa. A posteriori será más fácil retirar o sustituir funcionalidades problemáticas o desechadas.


https://www.atlassian.com/es/git/tutorials/rewriting-history/git-rebase

https://git-scm.com/docs/git-rebase

https://www.freecodecamp.org/espanol/news/la-guia-definitiva-para-git-merge-y-git-rebase/

https://scrumguides.org/scrum-guide.html	


https://www.atlassian.com/es/agile/scrum/sprints	


https://www.atlassian.com/es/agile


https://www.agilealliance.org/agile101/12-principles-behind-the-agile-manifesto/


https://www.alpharithms.com/how-to-create-a-folder-in-github-repos-463022/


https://education.github.com/git-cheat-sheet-education.pdf


https://www.w3schools.com/html/default.asp

https://geeks.ms/windowsplatform/2015/11/05/squasing-en-git/

https://onthedock.github.io/post/210121-combinar-commits/


https://scrumguides.org/scrum-guide.html

https://www.atlassian.com/es/agile/scrum/sprints

https://www.atlassian.com/es/agile

https://www.agilealliance.org/agile101/12-principles-behind-the-agile-manifesto/

https://www.alpharithms.com/how-to-create-a-folder-in-github-repos-463022/

https://education.github.com/git-cheat-sheet-education.pdf

https://www.w3schools.com/html/default.asp
