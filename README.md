# RSI_IoT
V priečinku BLE sú dva súbory:
Súbor Com-bluetooth-mwoolley-microbitbledemo.7.apk je aplikácia, ktorú je nutné nainštalovať do telefónu.
Súbor BLE_alphabot2.hex je nutné nahrať do microbitu


Po úspešnom spárovaní s aplikáciou sa na microbite má objaviť "C"
V aplikácií je ikona ovládača DPad, na ktorú je potrebné kliknúť
Šípkami ovládame pohyb robota a horným tlačidlom na pravej strane súšťame klaksón
Robot má zvukom upozorní:
    ak je vzdialenosť k prekážke menšia ako 15cm pomalým pípaním
    ak je vzdialenosť k prekážke menšia ako 10cm zrýchleným pípaním
    ak je vzdialenosť k prekážke menšia ako 5cm stálym tónom

-----------------------------------dodatočné súbory-----------------------------------

V priečinku Radio sú súbory, ktoré je nutné nahrať do microbitov príslušne podľa názvu ovládač a auto.
Microbit s kódom pre ovládač bude riadiť auto tak, že bude odosielať údaje o svojom naklonení, ktoré auto následne prevedie na pohyb motorov.
Žiadné iné senzory tam nie sú.

---POZOR!---
Odosielanie veľkého množstva údajov o Y a X náklone vedie k rýchlemu vybitiu batérií alphabot2 (2x3,6V (typ batérie 14500))!
Je preto nutné používať dobíjateľné batérie alebo porozmýšľať nad nejakou power bankou, ktorá bude mať požadované napätie na výstupe.
