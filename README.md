# algdat-2022-oblig-2-master
Obligen er utført alene av student Nabila s364588 
Steg for steg

Oppgave 1 
•	å få klassen til å inneholder en returmetode for tallforekomstvariabelen. 
•	lagre en tom metode ved å bruke forekomstvariabelen.
•	 Deretter oppretter klassen DoubleLinkedList(T)-metoden ved å bruke forekomstvariabelen for å teste om tabellen er null før en for-løkke implementeres. Denne sløyfen sjekker hver tabelloppføring for å se om den er null, noe som forhindrer at oppføringen legges til den koblede listen.
•	 I stedet legger denne løkken til verdier fra hode til hale i rekkefølge.

Oppgave 2
•	Tomte Listen før jeg startet på strengbyggeroppgave 2. 
•	Deretter setter den en start-hakeparentes i strengen. 
•	Etterpå spør den om listen er tom. Det siste trinnet bestemmes av om metoden har noen data.
•	brukte looperne for hvilke verdier som er i Listbox-byggeren til reverseString() bestemmer hvordan StringBuilders innhold fylles fra slutt til begynnelse. Denne metoden ble bygget på en lignende måte som reverseString(), bare med en omvendt streng som input i stedet for en StringBuilder.

Oppgave 3
•	Startet  ved å finne ut vor noden var.
•	skjekker om indeksen er gyldig . 
•	 Etter å ha sjekket om indeksen er gyldig, sjekker hent først haledelen av kjeden for en frontløkke. 
•	Når den blir funnet, returneres noden foran i kjeden. opptatter indeksen finner først noden hvis verdi den trenger å vedlikeholde ved å bruke findNode. 
•	Deretter får den tilgang til denne verdien gjennom T. A for loop navigerer gjennom listen fra startindeksen til sluttindeksen. 
•	Etter å ha satt den innsatte verdien i listen til ønsket verdi, returnerer løkken til slutt T mid, som er verdien den erstattet. 
•	Listens nye datastruktur lages ved å ta et segment fra mellom til. Etterpå utfører listen en sjekk fra til og plasserer eventuelle verdier som finnes mellom disse to indeksene i den nye strukturen.

oppgave 4
•	Metoden starter med å sette r = -1, som indikerer at den ikke skal inneholde noen null-verdier.

•	 Etter å ha behandlet hode til hale i en løkke, returnerer den hvis det ikke er relevante verdier. Når den finner et likt beløp, returneres dette. 

•	Antallet øker med én med hver i plassert foran likhetstegnet.

Oppgave 5 
•	metoden først sjekker at indeksen er gyldig før du sjekker om verdien er gyldig.
•	Etter å ha krysset den dobbeltlenkede listen, posisjonerer den seg på den aktuelle indeksen. Alle verdier med en indeks som er større enn dette vil bli flyttet én posisjon fremover.

oppgave 6
•	boolean fjern()sjekker halen eller hodet på en liste for å finne ut om en verdi er på slutten eller begynnelsen. 
•	Hvis det er på slutten, blir påfølgende verdier halen, og tidligere verdier blir hodet. 
•	Denne metoden fjerner en indeks hvis den er fraværende. 
•	Den sjekker indeksens gyldighet og filtrerer ut alle verdier knyttet til den ved å bruke findNode().
Oppgave 8
•	sjekker om den har flere elementer, kaster den en NoSuchElementException hvis den har det. 
•	Deretter setter den fjernOk til true og går videre til neste noden. 
•	Når først opprettet, setter DoublyLinkedListIterator pekeren. 
•	Den kaller findNode for å returnere en forekomst av iteratorklassen. 
•	Etter det kaller den iterator med en bestemt indeks.
•	 Hvis indeksen er gyldig, returnerer iterator en forekomst av iteratorklassen.
