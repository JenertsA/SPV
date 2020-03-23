 [![ForTheBadge powered-by-electricity](http://ForTheBadge.com/images/badges/powered-by-electricity.svg)](https://github.com/JenertsA/SPV/blob/master/spiestas_plates/pirma_PCB/README.md)
 # Uzdevums   

Lai atvieglotu pirmās spiestās plates izstrādi Tev jau ir dota strādājoša shēma, kurā
izmantotas zināmi un pārbaudīti komponenšu *footprint*. Iekārta ir pavisam vienārš divu tranzistoru __multivibrators__.

Tev jāizgatavo spiestā plate cilvēkeim, kas __grib iemācīties lodēt__, tāpēc uz plates tiek lietotas lielas, *THD* detaļas.
Izvietotjot kompoenetes ņem vērā to, ka tās lodēs pilnīgi dažadi cilvēki,
dažādos vecumos un ar dažādām prasmēm. Lai salodētā iekārta nebūtu vienkārši izmetama, __izdomā tai interesantu formu__, 
ievieto atbilstoša izmēra urbumu un paredzi komonenšu izvietojumu tā, lai t __varētu lietot kā atslēgas piekariņu__.

## nosacījumi
- plate ir divu slāņu (1p.)
- platei ir neregulāra forma, kas iekļaujas izmēros (3p.)
- ir izpldīts uzdevums, kas atrodams .sch failā kā teksts (3p.)
- ir lietots jēgpilns celiņu platums, kura izmērs ir metrisks (2p.)
- *silkscreen* norādi gadu, kad izstrādāta plate(1p.)
- *silkscreen* atrodams autora vārds vai izdomāts logo (2p.)
- uzaksti, kas atrodas uz *silkscreen* ir izkārtoti un tādā izmērā, kas palīdz cilvēkam ievietot pareizi detaļas (3p.)
- platē tiek lietoti *poligoni*, kas savieno detaļas(2p.)
- celiņi uz plates vilki sistemātiski, lietojot 45° leņķi (3p.)

### papildus uzdevumi
Starp Eagle un Fusion 360 pastāv iesēja savienot projektus. </br>
Ievieto jaunizveidoto plati Fusion360 un uztaisīt detalizētu modeli
kā piekariņš izskatīsies realitātē 

Izveido pirmās reizes pamācību cilvēkam, kas mēģināt lodēt Tavu piekariņu, kas kur jāsprauž un kā kas jādara. 

### paturi prātā
- platei jābūt nelielai, bet ne tika mazai, lai to ir grūti lodēt (iekļaujies 30x30 mm, bet ne lielāku kā 60x30 mm)
- attālumam starp komponentēm jābūt tik lielam, lai, lodējot tās, samazinātu risku izveidot *solder bridge*


### *lietotie termini*

*__footprint__* - urbumi vai laukumu izmērs un novietojums konkrētajai detaļa, lai tā varētu tikt montēta platē.

*__THD__* - no angļu valodas *Through-hole technology/devices* detaļas, kas tiek montētas urbumos. 

*__silkscreen__* - uzraksti, kas, parasti baltā krāsā, uzdrukāti uz plates. Tie tiek lietoti, lai marķētu detļau novietojumu, nosaukumu,
retāk detaļu vērtībām. Silkscreens tiek lietotas arī, lai piešķirtu platēm unikālāku izskatu. 

*__poligoni__* - vara pildījumi platē, ar kuru palīdzibu tiek aizstāta viena vai vairāku celiņu vilkšana. Tipiski ir visu plates varu izmantot kā lielu zemes poligonu - *ground plane*


*__solder bridge__* - lodējot divus blakus esošus kontaktus, alva starp lodējumiem saplūst un veido nevēlamu īssavienojumu. 


