# Projet Domotique
## Presentation
### Definition
Ensemble des technologies de l'électronique de l'information et des télécommunications utilisées dans les domiciles. Elles visent à assurer des fonctions de sécurité, de confort, de gestion d'énergie et de communication qu'on peut retrouver dans une maison.

Câblée ou fonctionnant par ondes radio, la domotique investit notre univers quotidien pour nous faciliter la vie. Souvent on la pratique sans y penser, en actionnant par exemple la télécommande du téléviseur ou en réglant le programmateur du lave-linge. Dans ses applications les plus évoluées, la domotique met en réseau et coordonne le fonctionnement de différents types d’équipements ménagers, de travail, de loisir… Les services offerts couvrent trois domaines principaux : confort domestique, économies d’énergie, protection.

![Def](/images/page1.jpg)

### Confort doméstique
Votre maison s'adapte à votre rythme de vie et à vos habitudes. Elle satisfait vos besoins et vos envies de confort, et prend en compte des situations de la vie quotidienne en effet un seul bouton suffit pour tamiser l'éclairage, déclencher la musique, diffuser de l'air parfumé, allumer la cheminée fermer son domicile, créer une ambiance de lecture, déclencher les stores, préparer le café avant tout le monde.... C’est un réel gain de temps.

### Economie d'énergie
Le but est d’éviter le gaspillage en supprimant les dépenses inutiles. Les systèmes de régulation permettent de maîtriser la consommation d’électricité, de gérer le chauffage et la production d’eau chaude sanitaire avec un niveau de confort optimal. Un détecteur de présence placé dans chaque pièce commande instantanément l’allumage ou l’extinction des éclairages, la mise en route ou l’arrêt de la climatisation... Au jardin, l’arrosage s’automatise, tandis qu’un détecteur crépusculaire se charge d’allumer et d’éteindre les lumières dès la tombée du jour.
### Protection
En liaison avec des prestataires extérieurs, la domotique permet le suivi des personnes fragiles, âgées ou handicapées (télésanté). Grâce à la technologie satellitaire, elle favorise également le désenclavement sanitaire. En matière de sécurité domestique, rien n’est laissé au hasard. Alarmes, détecteurs de mouvement ou d’intrusion, interphones et portiers vidéo, simulateurs de présence… se combinent pour dissuader les visiteurs indésirables ou malintentionnés.

D’autres systèmes de détection sont prévus pour surveiller les enfants, prévenir les risques d’accident (incendie, fuite de gaz…), signaler des pannes (inondation, coupure de courant…).

## Principe de fonctionnement 
La domotique est une intelligence centralisée. L'intérêt d'un tel système est de pouvoir faire communiquer entre elles les diverses fonctions des matériels, pour créer des scénarios et répondre aux styles de vie de chacun. Cette communication se fait via une interface de contrôle entre l'utilisateur et le système et, entre les équipements, par un mode de communication particulier.

Il est ainsi possible de programmer soi-même sa maison grâce à une interface, (généralement informatique), reliant les appareils connectés. Ce peut être un ordinateur, un Smartphone, une télécommande, une interface sur télévision…
### Sans fil
Actuellement, le sans-fil est surtout intéressant dans le cadre d’une rénovation ou d’un complément d’installation lorsque l’on souhaite minimiser les travaux. Les équipements radiocommandés fonctionnent sur des fréquences en mégahertz (MHz). Dans cette catégorie, on trouve des appareils mixtes capables de piloter indifféremment des équipements infrarouges ou radio. Ou encore, des modules télécommandables à monter dans les coffres des volets roulants ou à associer aux luminaires.

À l’usage, cette technologie présente des inconvénients non négligeables. La multiplicité des solutions proposées peut poser des problèmes d’interférences. Les ondes radios sont sensibles aux rayonnements électromagnétiques (éléments métalliques…) et la portée des infrarouges est limitée à quelques mètres. Par ailleurs, les fréquences utilisées sont loin d’être standardisées. Les protocoles « propriétaires » compliquent singulièrement la centralisation des matériels de marques différentes, quand ils ne l’interdisent pas tout bonnement.

![Répartition des fréquences utilisées dans les 
applications domotiques](/images/tableau.png)

### Courant porteur
Compatible avec le pilotage sans fil (radio, infrarouge), le courant porteur en ligne (CPL) présente l’avantage d’utiliser les circuits électriques existants. Le CPL superpose au signal électrique du secteur de 50 Hz (phase et neutre) une fréquence plus élevée (1,6 à 30 MHz) et de moindre amplitude. Sur cette bande, chaque type d’équipement (domestique, informatique) utilise une fréquence différente afin de pouvoir cohabiter sans se parasiter. Propagé sur l’installation électrique du logement, le signal CPL est reçu et décodé à distance par les appareils dédiés branchés sur le réseau. Pour contourner les perturbations électriques « naturelles », ceux-ci intègrent divers outils de protection (coupleurs, filtres) et de correction d’erreurs. Il est facile de faire évoluer l’installation en déplaçant des prises, en ajoutant des adaptateurs ou en créant des extensions de ligne. le CPL n’est pas à l’abri d’un défaut ponctuel de l’installation électrique, d’un transformateur défectueux, d’une perturbation créée par un appareil électrique (aspirateur, outils de bricolage, radio/télé…).
![CPL](/images/CPL.jpg)

### Cable dédié
La technologie BUS/SCS offre les meilleures conditions de performance et de fiabilité en réduisant le nombre de voies nécessaires à la communication et en mutualisant les données. Elle utilise un câble composé de conducteurs torsadés par paires (deux au minimum) alimenté en très basse tension (courant faible) qui sert à la fois pour l'alimentation des interfaces de commandes (27 V non polarisé) et pour la transmission des ordres entre les points de commande et les contrôleurs installés dans le tableau électrique. L’entrelacement a pour but de contrer les interférences électriques qui pénalisent le CPL. Les contrôleurs sont raccordés d'une part au bus et d'autre part au réseau et aux charges à commander.

La configuration du système se fait par le positionnement de cavaliers directement sur les appareils et/ou bien grâce à un logiciel. Elle permet d'affecter les commandes aux contrôleurs indépendamment du câblage et de créer ainsi des commandes individuelles, des commandes par zone et des commandes générales.

Mais les qualités sont variables pour les bus comme pour tout autre produit. Les meilleurs câbles sont blindés ou écrantés, de type STP (Shielded Twisted Pair ) ou FTP (Foil screened Twisted Pair ). Quoique plus répandues, les versions non blindées, UTP (Unshielded Twisted Pair ), sont moins bien protégées et l’on doit veiller à la qualité de leur gainage.

Ces câbles se déclinent par catégories indiquant leurs capacités : les catégories 5, 5e et 6 sont recommandées. Pour réaliser un réseau de communication intégrant l’audiovisuel, on utilise des câbles VDI (Voies, Données, Images).

![Cables](/images/cable.png)

* Câble UTP cat. 5 à 2 paires grainées de polyéthylène haute densité. Gaine extérieur en PVC de diamétre 6 mm.
* STP cat. 6 à 4 paires isolées de polyoléfine à structure poreuse et blindé individuellement par une feuille de polyester / Aluminium. Gaine extérieure en PVC de diamétre 6 mm.
* FTP cat. 5e à 4 paires isolées de polyéthyléne haute densité et enrobé d'une feuille d'aluminium. Gaine extérieure en PVC de diamétre 5,5 mm.

### Différents protocoles
Un protocole est le moyen de communication utilisé entre les accessoires domotiques. Le choix engage la pérennité de l’installation car il existe plusieurs systèmes, qui constituent autant de langages différents.

Un protocole propriétaire est lié en général à une seule et même marque. La plupart du temps, il ne sait pas dialoguer avec les autres solutions du marché et l’on est tributaire du choix imposé par le fabricant.

Un protocole ouvert est au contraire adopté par différentes marques, dont les produits sont compatibles entre eux.