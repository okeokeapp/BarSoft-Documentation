# ➗ Kedvezmények

Itt lehet beállítani az összes kedvezménnyel kapcsolatos kérdést, mint például aktív kedvezmények, időszakok, kategóriák, automatikus kedvezmények, stb.

Kezdetnek létrehoztunk egy 10%-os kedvezményt, ami manuálisan adható a POS-on. Ezt lehet szerkeszteni, vagy újat hozzáadni, vagy akár törölni is.

### **Alap adatok**

**Név**\
Ez meg lesz jelenítve a nyugtán, illetve a POS-on is ez alapján tudjuk beazonosítani a kedvezményt.

**Kedvezmény százaléka**\
Amennyiben ez pozitív értékű, úgy levonjuk a kedvezmény százalékot az árból.\
Ha ez az érték negatív, akkor felárként lesz felszámolva ennyi százalék az árhoz.

**Összegszerű kedvezmény**\
A fizetőablakban, kiválasztáskor az itt beállított összeg kerül levonásra a végösszegből. Amennyiben az itt megadott érték 0 és a százalékos kedvezmény sem lett megadva létrehozáskor, úgy az összegszerű kedvezmény mértéke a POS-on szabályozható.

{% hint style="danger" %}
FONTOS: Az összegszerű kedvezmény csak a fizetőablakban adható, előbb nem!
{% endhint %}

**Érvényességi időszak**\
Itt tudjuk meghatározni, milyen időszakban lehessen ezt a kedvezményt adni.

Dátum törlése\
Amennyiben a dátumot töröltük, a kedvezmény folyamatosan elérhető lesz.

### Érvényesség

Itt tudjuk beállítani az érvényességgel kapcsolatos részletes információkat.

**Engedélyezve**\
**E**z a kapcsoló szabályozza, hogy az érvényességi időszaktól függetlenül egyáltalán engedélyezve van-e a kedvezmény. Ha nincs, hiába lesz az érvényességi időszakon belül, akkor sem adható, nem is mutatjuk a POS-on.

**Automatikusan hozzáadódik**\
Ezzel lehet beállítani olyan kedvezményt/felárt, amit a rendszer alapjáraton hozzáad a rendeléshez, törölni nem lehet a POS-ról.

**Módosítókra is érvényes**\
Ha ez be van kapcsolva, a kedvezmény mértéke kihat a módosítók árára is.

**Csomagolásra is érvényes**\
Ha ez be van kapcsolva, a kedvezmény mértéke kihat a csomagolások árára is.

**Csak admin adhatja**\
Ezzel a kapcsolóval lehet lekorlátozni, hogy csak manager jogosultsági szintű felhasználó tudja adni a kedvezményt.

**Érvényességi órák naponként**\
Itt található egy eszköz, aminek segítségével 15 perces bontásban napi szinten meg tudjuk határozni, mikor legyen elérhető és mikor legyen tiltott a kedvezmény adása.

### Termék, kategória érvényesség

Ezen az oldalon ha nincs megadva egy érték sem, az minden értéket jelent. \
Tehát ha 0 kategória/méret van kiválasztva az azt jelenti, hogy minden kategória minden méretére adható a kedvezmény.

**Ezekre a kategóriákra érvényes**\
Ezzel tudjuk lekorlátozni, ha csak bizonyos kategóriákra szeretnénk, hogy érvényes legyen a kedvezmény.

**Ezekre a kategóriákra nem lesz érvényes**\
Ha minden kategóriára érvényes a kedvezmény, kivéve néhányat, akkor azt itt érdemes beállítani. Amit ide beállítunk, arra nem lesz adható a kedvezmény

**Méretek amikre érvényes**\
Itt tudjuk megadni, ha csak bizonyos termékek méreteit szeretnénk, hogy megkapja a kedvezményt.

**Méretek amikre nem érvényes**\
Ha minden termékre szeretnénk, hogy érvényes legyen a kedvezmény, néhány kivétellel, akkor azokat a kivételeket itt kell megadni.

A mentés gomb megnyomásával már életbe is lépnek a módosítások a POS-on.
