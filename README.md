# Prometne nesreče na slovenskih cestah

Avtorji: Aljaž Podkrižnik (63170238), Klemen Vogler (63170305) in Nace Selišnik (63170260)

Za projekt smo si izbrali analizo podatkov povezanih s prometnimi nesrečami na slovenskih cestah do leta 2014. 

Našli smo podatke o nesrečah glede na mesec in uro v dnevu, nesreče povezane z alkoholom ter vrste cest, kjer se zgodi največ prometnih nesreč. Našli smo tudi podatke o tem, kako so se prometne nesreče končale.

Naši cilji so:
  - Ugotoviti najpogostejše vzroke za prometno nesrečo
  - Ob katerem času se zgodi največ nesreč (v katerh mesecih v letu in ob katerih urah v posameznem dnevu)
  - Ugotoviti na katerih vrstah cest so nesreče najbolj pogoste
  - Ugotoviti najpogostejši izid nesreč
  - Primerjati vse zgornje ugotovitve in posikati povezavo med njimi

Izdelali smo vizualizacije podatkov oziroma grafe, ki na zanimiv, razločen in lahko berljiv način predstavijo naše ugotovitve. Poleg tega pa smo ugotovitve tudi analizirali.


Povezave do podatkov:

- https://podatki.gov.si/dataset/surs2222005s (Nesreče po urah dneva)

- https://podatki.gov.si/dataset/surs2222003s (Nesreče po mesecih v letu)

- https://podatki.gov.si/dataset/surs2222001s (Nesreče po vrstah ceste)

- https://podatki.gov.si/dataset/surs2222007s (Nesreče pod vplivom alkohola)

Za vmesno poročilo smo uporabili 3 tabele podatkov, in sicer podatke o nesrečah po mesecih v letu, po vrstah cest in nesreče pod vplivom alkohola.

### Analiza podatkov

**Analiza nesreč in lažje poškodovanih udeležencev za vsako leto**

Za prvo analizo smo iz podatkov o nesrečah po mesecih primerjali število nesreč po posameznih letih in število lažje poškodovanih udeležencev v teh nesrečah. Podatke smo sešteli skupaj po letih, tako za nesreče kot tudi za lažje poškodovane udeležence. Spodaj je graf naših ugotovitev.

![Nesreče in udeleženci po mesecih](./vmesno/slike/nesrece_udelezenci_po_letih.png?raw=true "Nesreče in udeleženci po mesecih")

Ugotovili smo:
 - da se je število nesreč vsako leto zmanjšalo,
 - da je bilo leta 2004 največ prometnih nesreč, prav tako pa tudi največ lažje poškodovanih udeležencev,
 - da je med leti 2010 in 2013 število nesreč nekoliko narastlo, število lažje poškodovanih udeležencev pa se je zmanjšalo,
 - sklepamo, da se je varnost na naših cestah zelo izboljšala v zadnjih letih.

**Analiza nesreč v vsakem mesecu za leti 2004 in 2014**

Pri drugi analizi smo iz podatkov o nesrečah po mesecih primerjali število nesreč za leti 2004 in 2014 po posameznem mesecu. 

![Nesreče po mesecih za leti 2004 in 2014](./vmesno/slike/nesrece_po_mesecih_2004_2014.png?raw=true "Nesreče po mesecih za leti 2004 in 2014")

Ugotovili smo:
- da je bilo leta 2004 v povprečju za več kot 1-krat več nesreč kot v letu 2014,
- da je bilo največ nesreč v jesenskih mesecih pri obeh letih,
- leta 2004 je bilo marca najmanj nesreč, največ pa oktobra,
- leta 2014 je bilo najmanj nesreč februarja, največ pa septembra,
- Očitno se je varnost na cestah v desetih letih močno zvišala, saj je nesreč veliko manj.

**Analiza nesreč na avtocestah in lokalnih cestah za posamezno leto**

Tretjo analizo smo izdelali nad podatki o nesrečah iz različnih vrst cest v Sloveniji. Primerjali smo število nesreč na avtocestah in lokalnih cestah skozi leta od leta 2003 do 2014.

Na spodnjem grafu se lepo vidi razlika med številom nesreč na avtocesti ter na lokalnih cestah.

![Nesreče na avtocestah in lokalnih cestah od leta 2003 do 2014](./vmesno/slike/nesrece_avtoceste_lokalne_ceste.png?raw=true "Nesreče na avtocestah in lokalnih cesta od leta 2003 do 2014")

Ugotovitve:
 - v letu 2003 je bilo na lokalnih cestah več nesreč kot na avtocestah. Sklepamo, da je razlog to, da v Sloveniji nismo imeli veliko kilomentrov avtocest, ali pa so jih ljudje uporabljali manj,
 - od leta 2004 do 2014 pa nesreče na avtocestah prevladujejo,
 - število nesreč je do leta 2009 padalo, nato pa spet skokovito naraslo. Sklepamo da je razlog v obsežni uporabi avtocest v zadnjih letih, prav tako temu botruje tovorni promet, ki poteka skozi Slovenijo,
 - nesreče na lokalnih cestah so vsako leto nižje. Razlogi so verjetno v varnejših avtomobilih, varnejših voznikih in prometni signalizaciji,
 - sklepamo, da povečana varnost v prometu ter ozaveščanje voznikov zelo pripomore k manjšanju števila prometnih nesreč na naših cestah.

**Analiza vinjenosti voznikov in voznic v prometu**

Za zadnjo analizo pa smo uporabili podatke o nesrečah z vinjenimi vozniki. Primerjali smo voznike in voznice, razdelili pa smo jih v tri kategorije, in sicer od 0.5 do 0.8 promila v krvi, od 0.8 do 1.5 promila v krvi in od 1.5 promila v krvi naprej. Podatki so zbrani od leta 2007 do 2014.

Naše ugotovitve se vidijo na spodnjem grafu.

![Vozniki in voznice po količini alkohola v krvi](./vmesno/slike/nesrece_pod_vplivom_alkohola.png?raw=true "Nesreče na avtocestah in lokalnih cesta od leta 2003 do 2014")

Ugotovitve:
 - Število moških v posamezni kategoriji je veliko več kot žensk (tudi do 10-krat več). Glavni razlog po naše tiči v tem, da je na cesti veliko več voznikov kot voznic, vemo pa tudi, da se v večini moški zadržujejo v gostilnah, ki se najverjetneje potem pijani peljejo proti domu.
 - Število vinjenih se z višjim nivojem alkohola v krvi povečuje, čeprav smo mislili, da temu ne bo tako.
 
 ### Zaključek
 
Pri izvedenih analizah smo ugotovili, da se je število nesreč vsako leto zmanjšalo, s tem pa se je povečala tudi varnost na naših cestah. K tem po našem mnenju pripomoglo ozaveščanje voznikov, poostreni nadzori voznikov (k tem sodi varnostni pas, uporaba telefona, nižja toleranca alkohola, itd.). Najbolj nevarne so avtoceste, zaradi večjih hitrosti in drastičnega povečanja prometa v zadnjih letih (tudi povečanje tranzita preko Slovenije). Presenetilo nas je razmerje voznikov pod vplivom alkohola in tudi razmerje med spoloma. Nismo pričakovali, da bo moških, ki so bili udeleženi v nesreči pod vplivom alkohola več kot 10-krat več kot žensk, prav tako pa, da bo število voznikov z več kot 1.5 promila toliko več, kot je voznikov, ki so imeli med 0.5 in 0.8 promila v krvi.
