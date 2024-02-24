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

# Introducció a la ciència de dades i a l'entorn de treball Jupyter Notebook

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

# Exploració inicial a les dades

Després d’una introducció al món de la ciència de dades, és hora de començar a treballar-hi. El primer que farem serà estudiar les dades. Normalment, les dades ens arriben en forma de taula, amb files i columnes. Veurem  com importar o carregar una taula i com extreure ràpidament la informació general que conté. Per fer-ho, necessitarem aplicar unes funcions senzilles amb Python. Tota aquesta feina serà executada en el nostre nou entorn de programació Jupyter Notebook. Aquest primer pas és molt important i sempre l’haurem d’executar en qualsevol dels nostres projectes, independentment de la complexitat de les dades que fem servir en cada moment.

També aprofundirem en els dos tipus de models predictius bàsics: el de regressió i el de classificació. Començarem, primer, des d’un punt de vista teòric o descriptiu i, després, agafarem experiència amb exercicis pràctics. Tot ho farem pas a pas