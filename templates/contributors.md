<!-- Diese Datei wird automatisch überschrieben, bitte contributors.csv anpassen -->

## Beteiligte Autor*innen

$for(contributor)$
* $it.name$$if(it.orcid)$ <https://orcid.org/$it.orcid$>$endif$$if(it.email)$, [$it.email$](mailto:$it.email$)$endif$$if(it.position)$\
$it.position$$endif$
$endfor$
