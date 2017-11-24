# prjava02
PREGUNTA 1-:
hem creat una nova branca amb "git branch" anomenada branca00, i després lhi hem 
fet un git checkout per canviar, de la branca master, a la nova que hem creat

PREGUNTA 5-:
S'ha de fer amb el comando de "git checkout" mes amb el nom de la branca que vols 
tornar, en aquest cas és la branca "master", doncs serà: git checkout master.
La diferencia principal és que a la branca branca00 hi han dos commits, en canvi en la branca "master" només hi ha un. 
Per verificar els commits que hi ha en la branca has de executar l'ordre "git log".

PREGUNTA 6-:
Hem obert el porojecte per verificar que en el geany no sortia la nova linia que abans hem afegit a la branca00

PREGUNTA 7-:
Si que es veu ja que hem tornat a la branca00 on ho hem guardat abans.

PREGUNTA 10-:
Si tornes a la branca "master" amb checkout master, trobaràs que amb el comando git log només hi ha un commit. 
Et demana que facis un RELOAD per que ha detectat que hi ha canvis en el fitxer i una vegada fet un RELOAD han 
passat tots els canvis que hem fet a la branca00 i ens ho ha passat a la branca "master"

PREGUNTA 12-:
Com que has fet un git push -u origin master s'ha pujat en el escriptori remot els canvis que tenias a la branca "master" 

PREGUNTA 14-:
per fer el push des de la branca01 has de posar la seguent ordre: git push -u origin branch01. Un cop s'hagi pujat 
has de anar al GITHUB i veuràs que s'haurà creat una nova branca amb el nom de branca01.
