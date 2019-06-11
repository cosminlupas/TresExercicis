1 – Centre Hospitalari.

En un centre hospitalari es desitja informatitzar part de la gestió relativa a pacients.
Després de l’anàlisi realitzat, s’estableixen els següents requeriments:

• Les dades d’interès que es desitgen emmagatzemar del pacient són el número de
Seguretat Social, DNI, nom, cognoms i data de naixement.


![](https://github.com/cosminlupas/TresExercicis/blob/master/1.PNG)


• Un pacient estarà assignat a un llit determinat d’una planta de l’hospital, podent
estar durant el temps d’ingrés a diferents llits i plantes, sent significativa la data
d’assignació de llit i el número del llit. Haurà de tenir en compte que els llits es
numeren correlativament per cada planta, es a dir, existirà el llit número 12 de la
tercera planta i també el número 12 de la setena planta. Les plantes de l’hospital
estaran identificades per número de planta, el seu nom i el nombre de llits de que
disposa.


![](https://github.com/cosminlupas/TresExercicis/blob/master/2.PNG)


• Per cada pacient es donaran com a màxim 4 targes de visita. Aquestes targes de
visita seran vàlides per visitar a un únic pacient. La tarja de visita es definirà pel
número de targeta de visita i l’hora de començament i de final en que es pot visitar
al malalt.


![](https://github.com/cosminlupas/TresExercicis/blob/master/3.PNG)


• A un pacient el poden atendre diferents metges, sent important per cada visita la
data i hora d’aquesta. I un pacient pot tenir diferents diagnòstics de malaltia, sent important la data del diagnòstic. Per una altra banda, un metge pot tractar diferents
tipus de diagnòstics i al revés.


![](https://github.com/cosminlupas/TresExercicis/blob/master/4.PNG)


• Les dades d’interès dels metges seran: codi del metge, nom i cognoms. Les dades
d’interès dels diagnòstics seran: codi de diagnòstic i descripció.


![](https://github.com/cosminlupas/TresExercicis/blob/master/5.PNG)

2 – Companyia d’assegurances.
Una companyia d’assegurances desitja que es faci un disseny d’una base de dades
per gestionar tota la informació referent a les assegurances que ofereixen, els clients als que
atenen i els agents d’assegurances que treballen per la companyia. Aquesta companyia
ofereix tres tipus d’assegurances:

• Assegurances de la llar: les assegurances d’aquest tipus oferts per la companyia
estan oferts de forma fixa (es a dir, s’han fet estudis previs), segons el valor del
continent (la casa), el contingut (mobles, electrodomèstics, joies, ...) i riscos
auxiliars (responsabilitat civil, assalt i altres). Per cada oferta hi ha una prima
assignada.

![](https://github.com/cosminlupas/TresExercicis/blob/master/11.PNG)

• Assegurances de vida: igual que de la llar, existeixen vàries ofertes fixes segons
l’edat i professió del client, i la cobertura econòmica de l’assegurança. De la mateixa
manera a les assegurances de la llar, existeix una prim a fixa per cada oferta.

![](https://github.com/cosminlupas/TresExercicis/blob/master/12.PNG)

• Assegurances de l’automòbil: també existeixen ofertes fixes, segons la categoria
del cotxe (utilitari, gamma mitjana, gamma alta, gran turisme, luxe, ...), anys del
vehicle, edat del conductor i cobertura (tot risc, franquícia, tercers, ...). A cada una
d’aquestes ofertes li correspon una prima.

![](https://github.com/cosminlupas/TresExercicis/blob/master/13.PNG)

• Per portar un control de les comissions que es porten els agents i de les seves
carteres corresponents, la companyia necessita tenir guardades les dades dels
agents, considerant-se d’interès el nom, DNI, adreça i telèfon. Pel pagament de
comissions i carteres (s’entén per cartera la comissió anual de l’agent mentre
l’assegurança estigui vigent), serà necessari saber quin agent ha realitzat
l’assegurança i en quina data. 

![](https://github.com/cosminlupas/TresExercicis/blob/master/14.PNG)

• La companyia considera com dades d’interès referents al client (sigui la que sigui
l’assegurança que contracti) el nom, l’adreça, el telèfon i el DNI.

![](https://github.com/cosminlupas/TresExercicis/blob/master/15.PNG)

Altres consideracions sobre la contractació d’assegurances per part del client són:

• Assegurances de la llar: data del contracte de l’assegurança i adreça de l’immoble
assegurat.

• Assegurances de vida: data de contractació, professió, cobertura econòmica i
beneficiaris.

• Assegurances de l’automòbil: data de contractació, matrícula del vehicle, recàrrecs
i descomptes.

• Altres consideracions: un client pot contractar més d’una assegurança de cada
tipus. A més aquests contractes poden realitzar-se mitjançant diferents agents. Els
beneficiaris d’assegurances de vida poden ser-ho de vàries assegurances, i de
varis clients diferents. A més un client pot anomenar a més d’un beneficiari en una
mateixa assegurança de vida. 

![](https://github.com/cosminlupas/TresExercicis/blob/master/16.PNG)


3 – CANTI-QUI-PUGUI.

L’empresa CANTI-QUI-PUGUI ens ha contractat per dissenyar una BD que mantingui
informació referent al món musical. Els interessa emmagatzemar informació dels diferents
grups de música que existeixen. Volen desar el nom del grup, el seu codi identificador, el seu
estil musical (només un), l’any què es va crear i quina és la formació del grup (és a dir, els
músics que toquen en el grup). Com és sabut, la formació del grup pot anar variant al llarg del
temps. Es pot donar el cas que una persona toqui en diferents grups alhora, i que fins i tot
torni a tocar en un grup al cap de cert temps d’haver marxat. Es vol mantenir l’historia l de la
formació dels grups musicals i els motius pels quals els músics deixen els grups. Hi ha alguns
grups que són semblants entre ells i es vol saber quin és el grau de semblança que hi ha. A
més a més, els interessa distingir entre els grups de música professionals i els grups
afeccionats. Dels grups de música professionals volen saber qui és el seu manager i l’adreça
de la pàgina web oficial del grup. Dels grups de música afeccionats volen conèixer l’adreça
de correu electrònica de contacte. Els grups professionals tenen un contracte amb una
companyia discogràfica. De la companyia discogràfica els interessa desar el NIF, el nom de
la companyia i l’adreça de correu electrònica. Es vol tenir constància de les companyies discogràfiques per les quals el grup ha passat al llarg del temps, així com el pressupost que
la companyia destina al grup. Lògicament, en un moment donat, el grup només té contracte
amb una única companyia. Cal esmentar que un grup mai tornarà a ser contractat per una
discogràfica si ja ho havia estat abans. Els grups professionals editen discos. Es vol conèixer
l’any en què es va enregistrar el disc, la persona que el va produir, i les cançons de què consta
el disc (considerem que una cançó només apareix en un únic disc). De les cançons volen
desar el nom, el codi identificador per cada cançó, la duració i els músics que l’han escrit.
També es vol conèixer quin va ser el primer single del disc (el qual consta d’una única cançó
del disc). Es pot donar el cas que diferents grups editin un disc amb el mateix nom, ara bé un
mateix grup mai editarà més d’un disc amb el mateix nom. De totes les persones es vol
conèixer el seu nom i cognoms, el seu codi identificador, la data de naixement i l’adreça de
correu electrònica personal.
Cal destacar que tant els productors com els managers poden haver estat (o són)
músics, i un músic pot fer de productor del grup o fins i tot de manager. Finalment el productor
pot ser, alhora, el manager del grup. Addicionalment, dels managers ens interessa saber el
seu número de telèfon mòbil.


![](https://github.com/cosminlupas/TresExercicis/blob/master/21.PNG)



![](https://github.com/cosminlupas/TresExercicis/blob/master/22.PNG)



![](https://github.com/cosminlupas/TresExercicis/blob/master/23.PNG)



![](https://github.com/cosminlupas/TresExercicis/blob/master/24.PNG)


![](https://github.com/cosminlupas/TresExercicis/blob/master/25.PNG)



![](https://github.com/cosminlupas/TresExercicis/blob/master/26.PNG)





