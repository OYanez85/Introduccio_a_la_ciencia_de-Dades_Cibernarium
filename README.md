# Introducció a la ciència de dades

## Programació

Hola!

En aquest curs farem una introducció a la ciència de dades, un dels camps professionals amb més sortides laborals de l’actualitat.

Descobrirem els fonaments de la  ciència de dades i aprendrem a treballar amb l’entorn de programació Jupyter Notebook. Veurem com explorar les dades i aplicarem diversos models de predicció. El següent pas serà treballar amb gràfics per mostrar, d’una manera visual, què diuen les dades. Per últim, aprendrem a analitzar una base de dades fent ús de diverses funcions i operacions.  

Tot això, amb l’objectiu d’obtenir els coneixements bàsics per extreure informació d’una base de dades i saber ensenyar els resultats extrets d’una manera visual i atractiva.

Si vols, podem començar amb la ciència de dades ara mateix.  Un món ple d’oportunitats t’espera!

# Presentació

En aquesta Presentació trobaràs les dades bàsiques per navegar per la nostra plataforma de formació online, així com l’estructura dels continguts del curs.

## Com navegar

El menú de navegació està ubicat a la part superior, just sota el títol del curs. Trobaràs les següents opcions:

Inici: Conté la llista de mòduls del curs.
Lliçons: Permet accedir directament a les lliçons del curs. Mostra si una lliçó ja ha estat superada, marcant-la amb un check. Els mòduls assenyalats amb un cadenat estan pendents i cal haver revisat algun altre element anterior per desbloquejar-los i accedir-hi.
Resultats: Mostra amb una marca verda quines de les lliçons has anat resolent. Recorda que cal superar-les totes per poder obtenir el certificat.
 

## Estructura del curs

El contingut es presenta en diferents mòduls. En la lliçó següent d’aquesta Presentació, Guia del curs, trobaràs els objectius, el temari i el sistema d’avaluació.

Els materials audiovisuals del curs es poden seguir amb subtítols en català i castellà, i al final de la formació està disponible una versió castellana dels continguts.

# Guia del curs
Benvinguts i benvingudes al curs “Introducció a la ciència de dades”!

Al final d’aquest curs podrem:

Processar una col·lecció de dades recollides en una o diverses taules.
Generar visualitzacions que mostrin la informació de manera gràfica.
Dissenyar models per predir resultats.
 

Trobarem vídeos i articles per treballar cadascun dels punts. Combinarem la teoria amb exemples i activitats que portin a la reflexió i a la posada en pràctica dels conceptes apresos.

Al final del darrer mòdul trobarem una prova d’autoavaluació tipus test, per poder repassar i consolidar els continguts. També podrem descarregar-nos els continguts del curs.

El curs es divideix en quatre mòduls:

1. Introducció a la ciència de dades i a l’entorn de treball Jupyter Notebook

Què és la ciència de dades i quines aplicacions té?
Conceptes bàsics de la ciència de dades
Treballar amb Jupyter Notebook
Aprofundir en Jupyter Notebook
Idees clau: Introducció a la ciència de dades i a l’entorn de treball Jupyter Notebook
 

2. Exploració inicial a les dades

Exploració bàsica de dades
Videotutorial (I): exemple d’exploració de dades
Introducció als models predictius
Models de regressió
Videotutorial (II): exemple d’un model de regressió
Models de classificació
Exemple d’un model de classificació. Vídeo tutorial (screencast)
Idees clau: Exploració inicial a les dades
 

3. Visualització de dades amb Matplotlib

Gràfiques lineals i de barres
Scatter plots
Videotutorial (III): exemple per generar els gràfics apresos
Ara et toca a tu! Representació gràfica de les dades
Representació gràfica de les dades: solució
Idees clau: Visualització de dades amb Matplotlib
 

4. Anàlisis de dades amb Panda

Crear, llegir i escriure una taula de dades
Indexar, seleccionar i filtrar
Ordenar, agrupar i dades no disponibles (missing values)
Videotutorial (IV): repàs del temari amb un exercici pràctic
Ara et toca a tu! Saber gestionar i processar les dades
Saber gestionar i processar les dades: solució
Idees clau: Anàlisis de dades amb Panda
 

Atenció: és molt recomanable tenir un nivell mínim de programació amb Python. Si aquest llenguatge t'és familiar, et serà més fàcil seguir el curs, sobretot en els mòduls 3 i 4.

## 1. Introducció a la ciència de dades i a l'entorn de treball Jupyter Notebook

En aquest primer mòdul ens aproparem a què és la ciència de dades, els seus fonaments, les eines de treball més habituals, quines aplicacions té i quins camps professionals i de recerca la fan servir. També abordarem quin paper hi juga el llenguatge de programació Python.

Posteriorment, veurem què és i com funciona l’entorn de programació Jupyter Notebook i per treballar, primer, amb les funcions més senzilles;  posteriorment, farem un pas endavant amb altres recursos més avançats. A partir d’aquí, ja podrem desenvolupar i escriure codi amb Python i disposar d’una orientació clara a la ciència de dades.

És important parar molta atenció  durant aquest primer mòdul, ja que assolirem les habilitats bàsiques per fer front a tot el curs i seguir aprenent. Tot el contingut és important, des de l’inici fins al final. La ciència de dades ens espera.

# Idees clau: Introducció a la ciència de dades i a l'entorn de treball Jupyter Notebook


En aquest primer mòdul, hem après els conceptes bàsics de la ciència de dades i les seves aplicacions més rellevants. Ara sabem que la informació codificada en forma de dades es pot depurar i netejar, i podem trobar patrons per tal de generar coneixement aplicat. Els camps on més es fa servir la ciència de dades són el món empresarial i la recerca en general.

L’aprenentatge automàtic és la capacitat d’una màquina de millorar els seus pronòstics, localitzant patrons amb un major grau de certesa, a mesura que aquesta màquina va gestionant més dades. Hi ha dos tipus de models:

Model de regressió. Serveix per calcular un valor determinat, és a dir, un número.
Model de classificació. Serveix per respondre a un qüestió en només dues opcions (binomi) o amb més de dues opcions (multinominal).
 

Jupyter Notebook és una plataforma gratuïta i de font oberta molt popular per desenvolupar projectes de ciència de dades. Aquesta aplicació té tres seccions: la barra de menú, la barra d’eines i la secció de les cel·les. Pel que fa a les cel·les, podem diferenciar-ne, principalment, dos tipus: un correspon al codi i l’altre al text. Quan necessitem picar codi, escollirem el primer i, quan necessitem escriure text, farem servir el segon. Això ens permet escriure codi i afegir  explicacions escrites i rellevants sobre aquest, i presentar-ho tot en el mateix document.

Jupyter Notebook permet afegir i eliminar cel·les fàcilment. Les cel·les noves es poden col·locar allà on més ens convingui. L’aplicació també ens permet visualitzar la nostra feina mitjançant una previsualització i, fins i tot, exportar el fitxer a HTML, per tal que es pugui penjar en un web.

## 2. Exploració inicial a les dades

Després d’una introducció al món de la ciència de dades, és hora de començar a treballar-hi. El primer que farem serà estudiar les dades. Normalment, les dades ens arriben en forma de taula, amb files i columnes. Veurem  com importar o carregar una taula i com extreure ràpidament la informació general que conté. Per fer-ho, necessitarem aplicar unes funcions senzilles amb Python. Tota aquesta feina serà executada en el nostre nou entorn de programació Jupyter Notebook. Aquest primer pas és molt important i sempre l’haurem d’executar en qualsevol dels nostres projectes, independentment de la complexitat de les dades que fem servir en cada moment.

També aprofundirem en els dos tipus de models predictius bàsics: el de regressió i el de classificació. Començarem, primer, des d’un punt de vista teòric o descriptiu i, després, agafarem experiència amb exercicis pràctics. Tot ho farem pas a pas.

# Idees clau: Exploració inicial a les dades

El més important abans de començar a fer servir cap model és entendre les dades que tractem, detectar els errors més comuns, identificar les cel·les sense dades i els valors allunyats. És una feina essencial trobar-los i netejar-los. Altrament, aquests afectarien negativament la qualitat dels models. Per tal de fer una exploració inicial de les dades, hem après a fer ús de funcions bàsiques com ara són head() i describe()

Tenim dos tipus bàsics de model predictiu: el de regressió i el de classificació. El primer recull aquells models que procuren predir valors numèrics quantitatius, mentre que els models que formen part del segon tipus es fan servir quan el resultat és un valor qualitatiu.

Tots els models necessiten que una part de la taula es faci servir per a l’entrenament. L’altra part restant es pot fer servir per mesurar si les prediccions dels models són prou bones o no. En els models de regressió lineal, el paràmetre de qualitat és el coeficient de regressió, mentre que, per a un model de classificació, és l’accuracy.

## 3.Visualització de dades amb Matplotlib

Per visualitzar les dades que tractem és útil aprendre a generar gràfics. Els gràfics són l’eina més poderosa per transmetre al públic no tècnic la nostra feina d’anàlisi de les dades: mostren visualment molta informació que d’altra manera podria passar desapercebuda.

En aquest mòdul, aprendrem a construir gràfics lineals, de barra i de dispersió. Depenent del tipus de dades amb les qual estem treballant i les qüestions que volguem resoldre, en farem servir un o un altre. L’instrument que emprarem serà Matplotlib.

## Ara et toca a tu! Representació gràfica de les dades

Tenint en compte la taula de dades que et pots descarregar en format CSV a través del següent enllaç, respon a les qüestions següents:

Nota: per tal de resoldre les qüestions, has d’importar els mòduls de Pandas, Matplotlib.pyplot i Seaborn.

Quina regió té l’observació 4? Quin valor bmi mostra l’observació 2? L’observació 3 té sexe femení o masculí? Quin cost (charge) té l’observació 1?
Quantes observacions (count) hi ha a la taula? Quina és la desviació std de la columna bmi? Quin és el cost (charges) mínim que té la taula? Quin és el nombre màxim de fills o filles que pot tenir una observació concreta?
Genera un histograma per a la variable edats (age) i la variable cost (charge).
Fes un gràfic de dispersió del cost (charges) davant de bmi i diferencia els punts obtinguts, depenent, primer, de si la persona és fumadora o no i, després, de si és de sexe masculí o femení.
Crea un gràfic de dispersió dels valors bmi en relació, primer, amb el nombre de fills o filles (children) i, després, amb el sexe i, finalment, amb si fuma o no. Tingues present que hi ha una funció específica per crear gràfics de dispersió en els quals una variable és categòrica. El nombre de fills o filles, el sexe i si fuma o no ho són.
 

Si veus que no pots resoldre tots els exercicis, la propera lliçó mostrarà com fer-ho.

## Idees clau: Visualització de dades amb Marplotlib

En aquest apartat, hem après a extreure informació de les dades mitjançant representacions gràfiques, les quals ens ajuden a visualitzar tendències i patrons amb només un cop d’ull.

Concretament, hem treballat amb gràfics de línia, de barra i de dispersió.

Els gràfics de línia mostren una línia continua que enllaça tots els punts que relacionen els valors de l’eix x i el valor de l’eix y corresponents.

Els gràfics de barres són aquells que utilitzen barres, les quals representen l’altura que té un punt respecte l’eix x.

Els gràfics de dispersió mostren els punts i les coordenades formades pel valor en l’eix x i el valor en l’eix y corresponent.

Per tal de construir els diferents tipus de gràfics, hem treballat amb funcions dels mòduls Matplotlip.pyplot i Seaborn.

El mòdul Pyplot proporciona funcions molt útils per generar els diferents gràfics. Per treballar amb gràfics de línia, farem servir plot(), de barra bar() i de dispersió scatter(). Aquestes funcions incorporen diferents paràmetres per configurar els gràfics. Per exemple, xlabel() dona nom a l’eix x, ylabel() a l’eix y, title() serveix per posar un títol, color() proporciona el color, linewidth() l’amplada de la línia, etc.

# 4. Anàlisis de dades amb Panda

Cada projecte, sigui gran o petit, incorporarà una base de dades amb la qual haurem de treballar. Independentment del volum, aquesta base de dades, probablement, requerirà una sèrie d’accions per tal de descobrir la informació rellevant i útil que conté.

En aquest mòdul aprendrem a treballar i processar bases de dades. Sabrem com crear-ne una des de zero i, després, llegir-ne el contingut i escriure-hi de nou. Tot seguit, farem front al primer bloc d’operacions bàsiques de processament de base de dades, que estarà format per les accions de seleccionar, filtrar i indexar. A continuació, aprendrem a ordenar i agrupar dades i a gestionar dades no disponibles.

Finalment, posarem a prova els nous coneixements amb un exercici pràctic. Certament, l’habilitat en saber gestionar bases de dades s’adquireix, primer, amb una bona base teòrica i, després, necessàriament, amb exercicis pràctics. Comencem!

## Ara et toca a tu! Saber gestionar i processar les dades

A continuació, es mostren diferent qüestions que cal resoldre de la taula “Insurance.csv”, que et pots descarregar en aquest enllaç.

Nota: ja has treballat amb aquesta base de dades anteriorment.

Imprimeix la taula que genera la funció describe() només des de la fila 45 fins a la 68. Calcula la suma dels valors bmi d’aquest interval i la mitjana dels charges.
Del mateix interval de files del punt anterior, mostra només els primers 12 registres de manera ordenada en sentit descendent, segons els valors de bmi. Aplica, després, un segon nivell amb els valors de charges, mantenint, per a aquest, el sentit predeterminat i canviant el sentit del primer nivell per ordre ascendent.
Torna a la base de dades principal i digues quantes persones fumadores hi ha a la zona northwest. Sabries dir la mitjana del nombre de fills o filles que hi ha a cada regió? Pots visualitzar les dades amb un gràfic?
Torna a la base de dades principal i crea’n una de nova només amb aquelles files que tinguin un bmi superior a 35 i que no siguin persones fumadores. Com ho faries, si només es necessita complir una de les dues condicions? I, què passa, si afegim que l’edat ha de ser, obligatòriament, superior a 25 per ser una fila seleccionada, però mantenim que una de les dues primeres no és obligatòria?

# Idees clau: Anàlisis de dades amb Panda
En aquest mòdul hem après a treballar amb bases de dades i hem vist com poden ser de potents, si sabem com aplicar-hi diverses accions destinades a l’anàlisi de dades.

Hem començat a construir-ne una des de zero, fent ús de la classe DataFrame. Després, hem vist com llegir i modificar bases de dades, tot accedint a les seves posicions.

Aplicant els operadors iloc[] i loc[], podem crear bases de dades més petites, partint d’una base de dades principal.

També hem après a seleccionar files, depenent d’una determinada condició, o més d’una, fet que ens permet filtrar la base de dades en relació amb els diferents valors que poden tenir els atributs o variables.

Podem agrupar bases de dades entorn als valors d’una o més variables. Una vegada hem agrupat aquests valors, és possible aplicar diferents funcions com, per exemple, la mitjana, el nombre de casos o les desviacions d’aquestes agrupacions.

Si vols descarregar-te el contingut del curs en català, fes clic aquí.

Si quieres descargarte el contenido del curso en castellano, haz clic aquí.