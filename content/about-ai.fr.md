---
title: "En savoir plus - Intelligence artificelle"
ShowToc: true
---

## L'IA au service de la météorologie et de l'adaptation au changement climatique

### Qu'est-ce que l'IA ?

L'intelligence artificielle (IA) permet à une machine d'effectuer des
tâches intelligentes telles que la planification, le raisonnement, la
prédiction et la classification. *Machine Learning* (apprentissage
automatique) est une branche de l'IA dans laquelle un programme
informatique apprend à partir de données existantes pour effectuer des
prédictions ou des tâches. Par exemple, un programme d'apprentissage
automatique peut reconnaître des animaux sur des photos en apprenant à
partir d'images existantes. Depuis 2012, l'IA a fait un énorme bond en
avant grâce aux développements du *deep learning* (réseaux neuronaux
artificiels à très nombreuses couches), ainsi qu'à une augmentation de
la puissance de calcul des ordinateurs. Grâce au deep learning, les
technologies telles que les voitures autonomes, les assistants virtuels
(Siri, Google Assistant, Alexa,\...) et les services basés sur de grands
modèles de langage, comme chatGPT, s'améliorent de plus en plus. L'IA a
de plus en plus d'applications pratiques, y compris dans le domaine
scientifique.

![AlphaGo, une IA développée par DeepMind, bat Lee Sedol, le champion du monde de go. (AlphaGo - the Movie)](/assets/images/about/alphago.jpeg)

### L'IA pour la météorologie

Prévoir le temps est un défi car de nombreuses échelles temporelles et
spatiales sont impliquées. Les modèles météorologiques numériques
résolvent les équations physiques de l'atmosphère pour produire une
prévision. Ils nécessitent une grande puissance de calcul et deviennent
moins fiables lorsque les prévisions sont éloignées dans le temps. Plus
les modèles sont fins, plus les prévisions sont précises au niveau
local, comme le montre la figure suivante. Malheureusement, cela
nécessite également beaucoup plus de puissance de calcul. Une autre
solution consiste à augmenter la résolution des modèles à l'aide de
l'IA. 

![L’effet de la résolution : afﬁner une prévision de
température d’une résolution plus faible à une
résolution plus élevée. Dans la ﬁgure de droite, vous
pouvez voir beaucoup plus clairement l’impact local
sur la température. (Downscaling weather data via
VineForecast)](/assets/images/about/Knipsel.PNG)

Calcul du climat urbain Les villes ont un climat unique en raison du
grand nombre de bâtiments et de rues qui les composent. Pendant la
journée, ils stockent la lumière du soleil sous forme d'énergie, qui est
émise sous forme de chaleur pendant la nuit. Cet effet d'îlot de chaleur
urbain fait que les villes sont plus chaudes la nuit que les zones
rurales environnantes. En outre, l'activité humaine produit localement
de la chaleur supplémentaire (chauffage, voitures, etc.). 
La prévision du climat urbain est complexe car les modèles
météorologiques traditionnels ont tendance à fonctionner à grande
échelle. La finesse du paysage urbain crée des microclimats qui peuvent
varier considérablement au sein d'une même ville, en raison d'effets
locaux tels que la pollution de l'air et les différences entre les zones
bâties. Cela rend les prévisions urbaines difficiles et souvent
divergentes par rapport aux modèles climatiques régionaux.

Pour cartographier correctement le climat urbain, les interactions entre
l'urbanisme, les activités humaines et le climat local doivent être
transformées en équations mathématiques, puis calculées. Les modèles qui
tiennent compte de ces effets peuvent fournir une meilleure image du
climat d'une ville. Cela permet d'obtenir de meilleures informations
pour la planification urbaine et les décisions politiques, en soulignant
la nécessité de disposer d'espaces verts, de matériaux réfléchissants et
d'une architecture appropriée pour contrer l'augmentation des
températures dans les zones urbaines.

![Un modèle climatique urbain, tel que le TEB (Town Energy Balance), est très complexe. (CNRM, MétéoFrance)](/assets/images/about/TEB.png)

### L'IA au service du climat urbain

L'IA ouvre la voie à des prévisions climatiques urbaines poussées. En
utilisant des données climatiques historiques et des informations sur
l'urbanisme, les modèles d'IA peuvent faire des prédictions plus
détaillées. Par exemple, ils peuvent simuler l'effet sur la température
de la présence d'un plus grand nombre d'arbres dans la ville ou de
bâtiments dotés de surfaces réfléchissantes. Ces connaissances peuvent
contribuer à un aménagement urbain durable et à des stratégies de
régulation de la température.

### Notre projet de recherche

Les chercheurs de l'ETRO (Electronics and
Informatics) et de la VUB (Vrije Universiteit Brussel) travaillent sur
un modèle de climat urbain alimenté par l'IA. Pour ce faire, ils
collaborent avec l'RMI et l'UGent, en utilisant les mesures de
température fournies par les citoyens. Les modèles d'intelligence
artificielle sont entraînés à partir de ces mesures, ce qui offre un
moyen innovant de mieux calculer le climat de la ville.

En collectant des données à partir de différentes sources de mesures
réparties dans la ville, telles que des capteurs dans les smartphones,
des stations météorologiques et d'autres ressources déployées par les
citoyens, nous obtenons un réseau de mesures à relativement haute
résolution. Dans le cadre de ce projet, nous avons utilisé les données
du réseau VLINDER, qui est un réseau de stations météorologiques de
qualité placées dans des zones rurales, urbaines et dans quelques autres
endroits particuliers. Ces stations ont été placées ici spécifiquement
pour étudier l'effet de l'environnement local sur le climat local.

Sur cet ensemble de données, une IA a été entraînée à partir de
prévisions météorologiques à plus faible résolution et de la couverture
végétale locale, et les a utilisées pour calculer les corrections
nécessaires à l'obtention de la température locale (urbaine). De cette
manière, la combinaison de l'IA et des observations des citoyens peut
contribuer à des prévisions météorologiques urbaines plus précises et
plus pertinentes. Vous pouvez en voir un exemple ci-dessous, où le
modèle d'IA a été utilisé pour calculer l'effet d'îlot de chaleur urbain
pour une nuit d'été pendant une canicule. Ce modèle d'IA basé sur le
réseau VLINDER est également utilisé comme modèle climatique urbain pour
l'atelier d'aujourd'hui.

![A gauche : la carte de la couverture du sol de Gand
(https://www.geopunt.be/). A droite : l’effet
d’îlot de chaleur pour Gand pour une nuit d’été
pendant une vague de chaleur prédite par notre IA.](/assets/images/about/picture3.PNG)

### Remerciements

Ce projet a été financé par Innoviris et réalisé en
partenariat entre la VUB, l'IRM et l'UGent.

Envie d'en savoir plus ? Découvrez le [Master in Applied Computer Science](https://www.vub.be/en/studying-vub/all-study-programmes-vub/bachelors-and-masters-programmes-vub/applied-sciences-and-engineering-applied-computer-science/program/master/master-applied-computer-science) à la [VUB](https://www.vub.be)
