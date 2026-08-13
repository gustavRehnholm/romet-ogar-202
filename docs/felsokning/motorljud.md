# Onormala motorljud

Här samlas information för felsökning av nytillkomna eller onormala mekaniska ljud från motorn.

Sidan behandlar för närvarande främst kamkedja och kamkedjespännare.

## Kamkedja

Kamkedjan synkroniserar vevaxeln med kamaxeln och därmed motorns ventiltider.

Romet Ogar 202 FI Euro 5 använder en motor ur **139FMB-familjen**. Dokumentation för FY139FMB beskriver en självverkande kamkedjespännare med fjäder och tryckstång. Kamkedjespelet ska därför normalt inte kräva regelbunden manuell justering.

### Symptom

Problem med kamkedja eller kamkedjespännare kan bland annat ge:

* rasslande eller skramlande ljud från motorn
* ljud som förändras tydligt med motorvarvet
* nytillkomna mekaniska ljud från motorns övre del

Ett tickande ljud behöver inte bero på kamkedjan. Felaktigt ventilspel kan ge liknande symptom.

## Kamkedjespännare

Verkstadsdata för FY139FMB beskriver en spännare med fjäder och tryckstång. Tryckstången innehåller även en ventilfunktion och systemet använder motorolja för sin funktion.

Möjliga orsaker till för stort kamkedjespel anges bland annat vara:

* sliten eller skadad spännarfjäder
* sliten eller kärvande tryckstång
* igensatta ventilhål i tryckstången
* luft i spännarkammaren
* skadade delar i spännaren

### Inspektion av spännaren

Följande procedur kommer från verkstadsdata för FY139FMB och är ännu inte verifierad specifikt för Romet Ogar 202 FI Euro 5.

1. Lossa spännarens tätningsbult/plugg.
2. Ta ut spännarfjädern.
3. Mät fjäderns fria längd.
4. Kontrollera tätningsbrickans skick.
5. Ta ut tryckstången och kontrollera den efter repor och slitage.
6. Kontrollera att ventilhålen i tryckstången inte är igensatta.
7. Mät tryckstångens ytterdiameter.
8. Montera tillbaka delarna i omvänd ordning.

#### Referensvärden för FY139FMB

| Del                       |         Standard | Slitgräns |
| ------------------------- | ---------------: | --------: |
| Spännarfjäder, fri längd  |         111,0 mm |  106,0 mm |
| Tryckstång, ytterdiameter | 11,985–12,000 mm |  11,94 mm |

Tätningsbulten anges till **25 Nm** i FY139FMB-verkstadshandboken.

!!! warning "Inte verifierat för Ogar 202 Euro 5"
Konstruktionen överensstämmer med dokumentation för FY139FMB-motorfamiljen, men mått och åtdragningsmoment ovan har ännu inte verifierats mot Ogar-specifik verkstadsdata.

```
Om konstruktionen eller dimensionerna avviker vid inspektion ska referensvärdena inte användas.
```

## Kamkedja och guider

Om spännaren fungerar men kamkedjan fortfarande misstänks ha för stort spel behöver även själva kedjan och dess guider kontrolleras.

Vid större ingrepp bör även kamtimingen verifieras innan motorn körs.

TODO:

* fotografera spännarens placering på Ogar 202
* verifiera att spännaren överensstämmer med FY139FMB-konstruktionen
* verifiera fjäderns och tryckstångens dimensioner
* dokumentera åtkomsten till spännaren

