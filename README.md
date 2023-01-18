# RSI_IoT
---Ovládanie microbitu pomocou mobilnej aplikácie---
V priečinku BLE sú dva súbory:
1.Súbor Com-bluetooth-mwoolley-microbitbledemo.7.apk je aplikácia, ktorú je nutné nainštalovať do telefónu.
2.Súbor BLE_alphabot2.hex je nutné nahrať do microbitu.


Po úspešnom spárovaní s aplikáciou sa na microbite má objaviť "C" (Connected).
V aplikácií je ikona ovládača DPad, na ktorú je potrebné kliknúť.
Šípkami ovládame pohyb robota a horným tlačidlom na pravej strane súšťame klaksón.
V priečinku je aj snímka kódu, pre rýchly nahľad princípu fungovania.

-----------------------------------dodatočné súbory-----------------------------------
---Ovládanie microbitu druhým microbitom---
V priečinku Radio sú súbory, ktoré je nutné nahrať do microbitov príslušne podľa názvu ovládač a auto.
Microbit s kódom pre ovládač bude riadiť auto tak, že bude odosielať údaje o svojom naklonení, ktoré auto následne prevedie na pohyb motorov.
Žiadné iné senzory tam nie sú.
V priečinku sú aj snímky kódov pre rýchly nahľad princípu fungovania.

---POZOR!---
Odosielanie veľkého množstva údajov o Y a X náklone vedie k rýchlemu vybitiu batérií alphabot2 (2x3,6V (typ batérie 14500))!
Je preto nutné používať dobíjateľné batérie alebo porozmýšľať nad nejakou power bankou, ktorá bude mať požadované napätie na výstupe.
