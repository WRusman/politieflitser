# politieflitser
Printontwerp voor een driedubbele astabiele multivibrator die knippert zoals zwaailichten van de politie

Wat heb je nodig :

- de printplaat
- 6x weerstand 33 Kilo Ohm (oranje - oranje - oranje) 
- 6x weerstand 4,7 Kilo Ohm (geel - violet - rood)
- 2x weerstand 470 Ohm (geel - violet - bruin)
- 4x weerstand 1 Kilo Ohm (bruin - zwart - rood)
- 2 Electolytische Condensatoren van 100 MicroFarad (µF)
- 4 Electolytische Condensatoren van 10 MicroFarad (µF)
- 2x transistor BC327 (ook te herkennen aan gouden bovenkant)
- 2x transistor BC337 (ook te herkennen aan zilveren bovenkant)
- 6x transistor BC547
- 2 grote blauwe leds


Op de printplaat zie je diverse teksten staan bij de onderdelen:

R1 t/m R18; dit zijn de weerstanden. Het maakt niet uit hoe je deze monteert, ze hebben geen + of – polen. Al ziet het er natuurlijk wel mooi uit als alle kleuren aan dezelfde kant zitten.

C1 t/m C6; dit zijn de electrolytische condensatoren (elco). Monteer deze zo dat het witte vlak op de printplaat overeen komt met de minpool van de condensator; dat is de witte streep op de elco. 

Q1 t/m Q10; dit zijn de transistoren. Monteer deze zo dat de platte kant van de transistor overeenkomt met de platte kant van de contour op de printplaat. Het middelste pootje komt in het gaatje tegenover de platte kant, de twee buitenste pootjes komen in de gaatjes aan de zijkant van de contour.

D1 en D2; dit zijn de Light Emitting Diodes (LED’s). Monteer deze zo dat de platte kant van de LED overeenkomt met de platte kant van de contour op de printplaat, een tweede aanwijzing is de K bij de contour van de LED, die komt overeen met de Kathode, wat toevallig ook het Kortste pootje is 

De onderdelen moeten op de kant komen waar de teksten staan, dus niet aan de kant met de koper sporen. Het opbouwen begint meestal met de laagste componenten, zodat je niet tussen hoge dingen in hoeft te werken. In dit geval zijn de weerstanden het laagst dus daar beginnen we mee. 

Buig de draden van de weerstand na het dikke deel strak in een hoek van 90 graden, buig ze niet te vaak heen en weer want dan kunnen ze afbreken! Steek de draden door de gaatje en buig de draden aan de kant van de koper sporen op de print een klein beetje naar buiten, zo vallen ze er minder makkelijk uit. Soldeer de weerstand vast, hou de soldeerbout niet te lang op de printplaat want anders kunnen de koperen sporen los laten van de printplaat.

- Begin met de 6 weerstanden R3, R4, R8, R9, R13 en R14 deze hebben een waarde
  van 33k (or-or-or)

- Daarna de 6 weerstanden R2, R5, R7, R10, R12 en R15, deze hebben een waarde
  van 4,7k (ge-vi-ro)

- Daarna de 4 weerstanden R1, R6, R11 en R16, deze hebben een waarde
  van 1k (br-zw-ro)

- Als laatste de 2 weerstanden R17 en R18, deze hebben een waarde
  van 470 Ohm (ge-vi-br)


Als tweede stap gaan we de transistoren plaatsen.

- Begin met Q3 en Q4, dat zijn de BC327 transistoren, in dit pakketje ook te herkennen aan de
  goudkleurige bovenkant.

- Daarna Q1 en Q2, dat zijn de BC337 transistoren, in dit pakketje ook te herkennen aan de
  zilverkleurige bovenkant.

- Als laatste Q5 t/m Q10, dat zijn de BC547 transitoren met een zwarte bovenkant.


Als derde stap gaan we de elco’s plaatsen.
- Begin met de 100 µF elco’s C3 en C4, deze hebben de meest lastige plek. Zorg dat de witte streep
  op de elco (minpool) aan de kant van het witte vlak zit.

- Daarna de 10 µF elco’s C1, C2, C5 en C6. Zorg ook hier dat de witte streep
  op de elco (minpool) aan de kant van het witte vlak zit.

Als laatste stap kunnen we de LED’s plaatsen, zorg dat de vlakke kant van de LED op de vlakke kant van de countour zit, of op korte poot bij de K en dus naar de buitenkant van de print gericht.

Nu nog de draden van de batterijclip met de rode draad aan de + aansluiting en met de zwarte draad aan de – aansluiting, en dan zou alles moeten werken.
