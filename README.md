# Vaja2-ADC-continuos-conversion-STM32F0
Neprekrinjeno ADC pretvorba z izbranem potenciometrom na pinu PC0 s hitrostjo 16MHz in 8-bitno ločljivostjo

b) Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter potenciometri, izberite ustrezni
analogni vhod. Kateri pin je to? PC0 .

e) Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni
kanal/pin. Na zaslonu se vam mora usterzno pobarvati izbrani pin v
zeleno barvo. Kaj se izpiše poleg pina? ADC_IN10 .

f) V Clock Configuration spremenimo APB1 peripheral clock (MHz) na 16
MHz. Kaj opazite? Vse vrednosti se spremenijo na 16 MHz.

h) Clock Prescaler nastavimo z deliteljem 4. Kolikšna je sedaj preskalirana frekvenca takta f preskalirana ?
4 MHz.

j) Sampling time (čas vzorčenja t vz_ciklih ) spremenite na 239.5 cikov. Pravi čas vzorčenja se nato poveča še za
12 ciklov. Koliko znaša pravi čas vzorčenja t vz v mikro sekundah?
(enačba: t vz =t vz_ciklih /f preskalriana )? 59,875 µs.


Program pretvarja analogno vrednost v digitalno desetiško vrednost. Ta vrednost je 8-bitna kar pomeni da imamo vrednosti od 0-255. Pretvornik deluje s 4 MHz. S spreminjanjem potenciometra se spreminja vrednost (kot je prikazano v videju). V navodilih je napaka pri nalogi 4 b) saj je najprej potrebno odpreti Debug in šele potem lahko z desnim klikom dodamo okno v Watch1
