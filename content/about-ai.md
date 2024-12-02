---
title: "Meer weten - Artificiële intelligentie"
ShowToc: true
---

## AI voor weerkunde en klimaatadaptatie

### Wat is AI? 

Artificiële Intelligentie (AI) stelt een machine in staat om
intelligente taken uit te voeren, zoals plannen, redeneren, voorspellen
en classificeren.

*Machine learning* (machinaal leren) is een tak van de AI waarbij een
computerprogramma leert van bestaande gegevens om voorspellingen of
taken uit te voeren. Een ML programma kan bijvoorbeeld dieren in foto's
herkennen door te leren van bestaande afbeeldingen.

Sinds 2012 heeft AI een enorme sprong voorwaarts gemaakt dankzij
ontwikkelingen in *deep learning* (artificiële neurale netwerken met
zeer veel lagen), samen met krachtigere computers. Met de kracht van
deep learning worden technologieën zoals zelfrijdende auto's, virtuele
assistenten (Siri, Google Assistant, Alexa,...), en diensten gebaseerd
op grote taalmodellen, zoals chatGPT, steeds beter. AI heeft steeds meer
praktische toepassingen, ook in de wetenschap.

![AlphaGo, een AI ontwikkeld door
DeepMind, verslaat Lee Sedol, de
wereldkampioen Go](/assets/images/about/alphago.jpeg)

### AI voor weerkunde

Het weer voorspellen is uitdagend, omdat er veel verschillende tijds- en
ruimtelijke schalen een rol spelen. Numerieke weermodellen lossen de
fysische vergelijkingen van de atmosfeer op om zo een voorspelling te
maken. Ze vereisen veel computerkracht en worden minder betrouwbaar bij
voorspellingen ver in de toekomst.

Hoe fijnmaziger de modellen, hoe nauwkeuriger de voorspellingen lokaal
zijn, zoals getoond in de volgende figuur. Dit vereist helaas ook veel
meer rekenkracht. Een alternatief is om de modellen te verfijnen met AI.

![Het effect van resolutie: Het verﬁjnen van een
temperatuursvoorspelling van een lagere naar
hogere resolutie. In de rechterﬁguur zie je veel
duidelijker de lokale impact op de temperatuur.](/assets/images/about/Knipsel.PNG)

### Berekenen van het stadsklimaat

Steden hebben een uniek klimaat door de
vele gebouwen en straten. Overdag slaan ze zonlicht op als energie, die
's nachts als warmte wordt uitgestraald. Dit stedelijk hitte-eiland
effect zorgt ervoor dat steden 's nachts warmer zijn dan omliggende
landelijke gebieden. Daar bovenop wordt er door menselijke activiteit
lokaal extra warmte geproduceerd (bvb. verwarming, auto's,...). Het
voorspellen van het stadsklimaat is complex omdat traditionele
weermodellen meestal op grotere schalen werken. Het fijnmazige
stadslandschap zorgt voor microklimaten die sterk kunnen verschillen
binnen een stad, door lokale effecten zoals luchtvervuiling en
verschillen in bebouwing. Dit maakt stedelijke voorspellingen uitdagend
en vaak afwijkend van regionale klimaatpatronen.

Om het stadsklimaat juist in kaart te brengen, moet de wisselwerking
tussen stedelijk ontwerp, menselijke activiteiten en het lokale klimaat
in wiskundige vergelijkingen gegoten worden en vervolgens uitgerekend
worden. Modellen die deze effecten mee in rekening brengen kunnen een
beter beeld geven van het weer in een stad. Dit geeft betere informatie
voor stadsplanning en beleidsbeslissingen, waarbij de nadruk wordt
gelegd op de behoefte aan groene ruimten, reflecterende materialen en
aangepaste architectuur om de stijgende temperaturen in stedelijke
gebieden tegen te gaan.

![image](/assets/images/about/TEB.png)

### AI voor het stedelijk klimaat

AI opent de deur naar geavanceerde stadsklimaatberekeningen. Door
historische klimaatdata en stedelijke informatie te gebruiken, kunnen
AI-modellen gedetailleerdere voorspellingen maken. Zo kunnen ze
bijvoorbeeld het temperatuureffect simuleren van meer bomen in de stad,
of gebouwen met reflecterende oppervlakken. Deze inzichten kunnen
bijdragen aan duurzame stadsplanning en strategieën voor
temperatuurregulatie.

### Ons onderzoek 

De onderzoekers van [ETRO (Electronica en Informatica)](https://www.etrovub.be) -
VUB (Vrije Universiteit Brussel) werken aan een AI-aangedreven
stadsklimaatmodel. Ze werken hiervoor samen met het KMI en UGent, en
maken gebruik van zogenaamde crowsourced temperatuurmetingen. AI
modellen worden getraind met deze metingen, en bieden zo een innovatieve
manier om het stadsklimaat beter te berekenen.

Door gegevens te verzamelen van verschillende bronnen verspreid over de
stad, zoals sensoren in smartphones, weerstations in achtertuinen en
andere middelen ingezet door burgers, verkrijgen we een relatief
hoge-resolutie netwerk van metingen. In de context van dit project
hebben we de data van het VLINDER netwerk gebruikt, zijnde een netwerk
van kwaliteitsvolle stations geplaatst in landelijke, stedelijke en een
paar andere speciale locaties. Deze stations zijn hier specifiek
geplaatst om het effect van de lokale omgeving op het lokale klimaat te
bestuderen.

Op deze dataset werd een AI getraind die als input lagere resolutie
weersvoorspellingen en de lokale bodembedekking had en hiermee de nodige
correcties berekend om de lokale (stedelijke) temperatuur te verkrijgen.
Op deze manier kan de combinatie van AI en citizen science
(burgerwetenschap) bijdragen aan nauwkeurigere en relevantere stedelijke
weersvoorspellingen. Een voorbeeld hiervan zie je hieronder, waar het AI
model gebruikt werd om het stedelijk hitte-eiland effect te berekenen
voor een zomernacht tijdens een hittegolf. Dit AI-model op basis van het
VLINDER netwerk wordt vandaag ook gebruikt als stadsklimaatmodel voor
deze workshop.

![image](/assets/images/about/picture3.PNG)

Meer leren? Ontdek de [Master in Applied Computer Science](https://www.vub.be/en/studying-vub/all-study-programmes-vub/bachelors-and-masters-programmes-vub/applied-sciences-and-engineering-applied-computer-science/program/master/master-applied-computer-science) aan de [VUB](https://www.vub.be)
