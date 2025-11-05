# ⚖️ Mérleg használat

### Integráció

Jelenleg a CAS PR-2 típusú mérleg integrációját tudjuk használni a programmal.\
Amennyiben az eszközön nem található COM port, úgy szükségünk lesz egy RS232 USB átalakító kábelre.\
Miután összecsatlakoztatjuk a két eszközt, el kell fogadnunk a felugró ablakban, hogy a Barsoft kezelhesse az USB-s eszközt.

<figure><img src="../../.gitbook/assets/Screenshot_20231102-134836.png" alt=""><figcaption></figcaption></figure>

Első lépésként a beállításokban a mérleg integráció alatt a megfelelő usb portot válasszuk ki.

### Mérendő termék

Ahhoz, hogy egy termék beütésekor számításba vegyük a mért értéket, be kell állítani a termék méreténél iPanel V2-n a "Mérendő" kapcsolót.

<figure><img src="../../.gitbook/assets/scale1.gif" alt=""><figcaption><p>Fontos, hogy a mérendő termék mérete elérhető legyen az adott lokáción</p></figcaption></figure>

Amennyiben egy termék méretének az NTAK egység típusa kilógramm és a mérendő kapcsoló aktiválva van, a mérés eredménye befolyásolni fogja a termék értékét.

<figure><img src="../../.gitbook/assets/scale2.gif" alt=""><figcaption></figcaption></figure>

### Láthatóság

BrandApp vagy Kiosk használata esetén a méret láthatóságának levétele (azért, hogy ne lehessen mérendő terméket rendelni appból, vagy kioskról)

### Mérés

Amennyiben a mérleget sikeresen integráltuk, már egyből láthatjuk a mérleg aktuálisan mért értékét a kijelzőn.

<figure><img src="../../.gitbook/assets/Képernyőkép 2023-11-02 142321.png" alt=""><figcaption><p>Helyesen integrált mérlegnél már itt is látható a mérleg értéke</p></figcaption></figure>

Eladáskor elég kiválasztani a mérendő terméket, ezután a mérlegre helyezzük a terméket, és amint stabil értéket mutat a mérleg (ezt a mért érték körülötti zöld keret jelzi), már hozzá is adhatjuk a kosárhoz.

<figure><img src="../../.gitbook/assets/scale3.gif" alt=""><figcaption><p>Miután felraktuk a mérlegre a mérendő terméket, várjuk meg a zöld (stabil érték) jelzést</p></figcaption></figure>

Amennyiben nem integrálható mérleget szeretnénk használni, a mért értéket kézzel kell majd beírnunk "Mennyiség állítás"-kor.

<figure><img src="../../.gitbook/assets/Screenshot_20231102-143002.png" alt="" width="358"><figcaption><p>Integráció nélküli mérendő termék</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Screenshot_20231102-143014.png" alt="" width="346"><figcaption><p>Kilógrammban meg tudjuk adni a súlyt, amit egy másik mérlegen lemértünk</p></figcaption></figure>

### Csomagolás súlyának levonása

Ha beállítunk egy olyan csomagolást a termékünkhöz, aminek súlya van, a mérendő terméknél bekapcsolhatjuk a "Csomagolás súlyának levonása" opciót. Ezzel a mért értékből a rendszer automatikusan levonja a csomagolás súlyát, így nem kell tárázni a csomagoló mérlegre helyezése előtt.

<figure><img src="../../.gitbook/assets/Képernyőkép 2024-03-20 163836.png" alt=""><figcaption></figcaption></figure>

