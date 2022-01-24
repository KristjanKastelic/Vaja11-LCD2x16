# Vaja11-LCD2x16

Za RS in E priključka na LCD zaslonu izberite in aktivirajte ustrezna pina _PB0_ in _PB2_ kot GPIO_Output. (Uporabil sem tudi RW na pinu PB1).

Tudi za priključke D4 do D7 na LCD zaslonu aktivirajte 4
ustrezne pine _PB12_, _PB13_, _PB14_ in _PB15_ kot GPIO_Output.

V Clock Configuration spremenite frekvenco na vrednost, da bo polovica najvišje možne: Nova frekvenca 
bo _40_ MHz.
V zavihku Pinout & Configuration pod rubriku System Core kliknite gumb GPIO. Kakšna je nastavljena 
hitrost podatkov na vodilih (max. output speed) ? _Low_.

Kakšne so min ter max vrednosti za x in y za vaš LCD zaslon? :
 x   y
207 144
316 146
255 154
242 155
234 157

Kaj počne funkcija itoa? _itoa spremeni int v string_.
Zakaj jo moramo uporabiti? _Moramo jo uporabiti ker lahko sprejme DECIMALNE, HEX ali DECIMALNI._.

KOMENTAR: nekatere stvarisem moral spremeniti saj sem nalogo delal na nucleu. Spremenil sem pine RW, RS in E in pine od D4 do D7. Kodo sem sicer napisal ampak je nisem moral previriti saj nisem sploh mogel kliknit na gumbza preverjanje. Naloga mi ani delovala.
