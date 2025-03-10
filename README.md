# OS2KLE

OS2KLE is developed by Taxon ApS (https://taxon.dk) for OS2 - Offentligt digitaliseringsfællesskab (https://os2.eu).

Copyright (c) 2013-2025, OS2 - Offentligt digitaliseringsfællesskab.

OS2KLE is a free and open dataset; you may use, study, modify and distribute it under the terms of version 2.0 of the Mozilla Public License. See the LICENSE file for details. If a copy of the MPL was not distributed with this file, You can obtain one at http://mozilla.org/MPL/2.0/.

All source code in this and the underlying directories is subject to the terms of the Mozilla Public License, v. 2.0.

## Beskrivelse

OS2KLE er et maskinlæsbar KLE-datasæt, som sammen med en motor gør, at dokumenter automatisk kan opmærkes efter KLE. Motoren, som skal anvendes sammen med datasættet, kan være Taxon Classifier eller f.eks. en egenudviklet motor. 

## Anvendelse
OS2KLE kan f.eks. bruges til: 

    Automatisk KLE-opmærkning af digitale dokumenter, sager og data,
    Automatisk postfordeling efter KLE,
    Søgeoptimering, præjournalisering eller adgangsstyring,
    Strukturering af hjemmesider, hvor emnet er opdelt efter KLE.

OS2KLE består af en Master, som er bygget over KLE og de fælles forhold i kommunerne. Den kan downloades fra GitHub. OS2KLE opdateres to gange årligt, så den følger udviklingen af KLE. 
OS2KLE Master kan bruges, som den er, men det giver et langt bedre opmærkningsresultat og en højere præcision, hvis den redigeres og tilpasses i forhold til den specifikke opgave hos den enkelte kommune.
Afhængig af hvilke data, der opmærkes, kan en tilpasset OS2kle opnå en opmærkningspræcision på op til mellem 85-100%.

Læs mere på https://os2.eu/produkt/os2kle.


## Filer

### OS2KLE.json

Indeholder selve OS2KLE i JSON format.

### change.json

Indeholder en oversigt over ændringerne i forhold til forrige version. Filen er i JSON.

### view_changes.html

Er en stand-alone HTML-side, som kan vise change.json på en pæn og letlæselig måde i en browser.

change.json skal ligge i samme folder som view_changes.html.

