# Projekt Stream deck - Jakub Kučera 
## Zadání projektu 
## Jelikož jsem si vybral úkol, který mi přišel složitý a raději jsem změnil téma. U předešlého nápadu jsem sprovoznil kód na animaci na displeji(soubor s kódem je zde uložen) a zybtek kódu, pomocí kterého se mělo komunikovat EPS32 přímo s PC. Jelikož jste chtěl nějaký projekt, který se dá dále používat, např doma, tak jsem si vybral barevné osvětlení pokoje pomocí LED pásku a ovládaní přes mobilní telefon přes WIFI. 
## Stav projektu 
#### Mám objednané další dva LED pásky a ESP32, které si dám pod postel a druhý pod stolek, jeden už mám nainstalovaný pod stolem. 
## Průběh práce na projektu 
#### Stáhl jsem si kód přes stránky WLED do esp32, poté ho připojil na WiFi, poté jsem si stáhl aplikaci WLED na mobil a na stejné síti jsem viděl IP adresu ESP32 a mohl si přes vybraný GUI měnit jas, barvu a módy. Momentálně to mám takto přilepené pod stolem.
![image](https://github.com/Vajco06/Ku-era-Projekt/assets/154622913/9e28c4d4-168f-4fd8-8d89-98db5d609905)
#### Dále si musím sehnat napájení na 5V (pravděpodobně přímo do zásuvky nějaké starší nabíječky) a přes mikro USB napájet ESP32 daných "okruhů". LED pásek který mám u pc je napájený přimo do PC. 
## Zapojení 
#### Pasék má tří pinovou koncovku - VCC (napájení na 5V), GND (ZEM) a datový pin (v tomto projektu pin 16)
