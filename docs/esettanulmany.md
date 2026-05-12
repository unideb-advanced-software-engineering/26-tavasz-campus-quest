# Esettanulmány: Campus Quest

## Háttér

Egy modern egyetemi campuson rengeteg olyan értékes hallgatói aktivitás történik, amely nem feltétlenül jelenik meg a hivatalos tanulmányi rendszerekben. Ezek az aktivitások sokszor fontosak az egyetemi élet szempontjából, de nehezen láthatók, nehezen mérhetők, és ritkán kapnak visszajelzést. Az egyetem ezért szeretne létrehozni egy játékosított közösségi platformot, a **Campus Questet**, amelyben a hallgatók különböző campushoz kapcsolódó küldetéseket teljesíthetnek.

## Általános követelmények

- A rendszer kísérleti jellegű, ezért az első verzió legyen egyszerű, gyorsan kipróbálható és könnyen módosítható.
- A játékosítás nem válhat öncélúvá: a pontok, jelvények és ranglisták célja a részvétel ösztönzése és a visszajelzés, nem pedig a hallgatók túlzott versenyeztetése.
- A hallgatói aktivitási adatok érzékenyek lehetnek, ezért fontos az adatvédelem, a láthatóság szabályozása és az auditálhatóság.
- A küldetések, pontozási szabályok és jelvényfeltételek idővel változhatnak, ezért a rendszer tervezésénél számolni kell a későbbi módosításokkal.

## Leírás

A Campus Quest egy olyan platform, ahol a hallgatók különböző **küldetéseket** teljesíthetnek. Egy küldetés valamilyen egyetemi, közösségi, szakmai vagy önkéntes aktivitáshoz kapcsolódik.

Példák küldetésekre:

- „Vegyél részt egy kari nyílt napon önkéntesként.”
- „Látogass el egy vendégelőadásra.”
- „Vegyél részt egy hallgatói klub eseményén.”
- „Segíts egy elsőéves hallgatónak eligazodni a campuson.”

A küldetések teljesítéséért pontok járhatnak. Bizonyos feltételek teljesülése esetén a hallgatók jelvényeket is szerezhetnek, például közösségi segítségért, önkéntes munkáért, rendszeres részvételért vagy több különböző campusprogram kipróbálásáért.

A rendszer ranglistát is vezethet, de ennek láthatóságát körültekintően kell megtervezni. Nem biztos, hogy minden hallgató szeretné nyilvánosan látni a saját pontszámát, és az sem biztos, hogy a túlzott verseny minden közösségi célt támogat.

## Felhasználók

- A hallgatók, akik küldetéseket böngésznek, teljesítéseket küldenek be, pontokat és jelvényeket gyűjtenek.
- Az eseményszervezők, akik küldetéseket hozhatnak létre.
- A jóváhagyók, akik bizonyos teljesítéseket elfogadhatnak vagy elutasíthatnak.
- Az adminisztrátorok, akik kezelik a rendszer beállításait és a láthatósági szabályokat.

## Követelmények

- Lehessen küldetéseket létrehozni névvel, leírással, kategóriával, pontértékkel és érvényességi időszakkal.
- A hallgatók küldetésteljesítéseket küldhessenek be rövid indoklással vagy igazoló hivatkozással.
- A teljesítések állapota legyen beküldve, elfogadva, elutasítva vagy visszavonva.
- Csak az elfogadott teljesítések után járjon pont.
- A rendszer automatikusan oszthasson ki egyszerű jelvényeket, például az első teljesítésért vagy adott számú küldetés után.
- A hallgatók megtekinthetik saját pontjaikat, teljesítéseiket és jelvényeiket.
- Készüljön egyszerű ranglista, amely kikapcsolható vagy anonimizálható.
- A jóváhagyói döntésekről készüljön naplóbejegyzés.
- A rendszer első verziója webes felületen legyen használható.

## Kiegészítések

- Nem szükséges valódi egyetemi rendszerhez, beléptetőrendszerhez vagy eseménynaptárhoz integrálódni.
- Távlati cél lehet fejlettebb jelvényszabályok, külső integrációk és több féléven átívelő hallgatói profilok kezelése.
