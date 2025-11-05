# 🎨 Testreszabás

Ezen az oldalon a "Testreszabás" menüpont elmein megyünk végig sorban, itt az eszközünk megjelenését és működését tudjuk testre szabni a saját működési elvünk szerint

## Működési beállítások

### Orientáció beállítás

Itt tudjuk beállítani, milyen orientációban szeretnénk megjeleníteni a BarSoftot a készülékünkön.\
Állítva vagy fektetve, illetve fordítva (fejjel lefelé).

### Asztal mód

Amennyiben a készüléket mobil eszközként ismeri fel a program, az elemek megjelenítése máshogy történik, viszont, ha a készülékünk eléggé nagy és magas felbontású, érdemes számításba venni az asztal mód használatát, ahol egyszerre több elem jelenik meg a képernyőn.

### Erőforrás kímélő beállítások

#### Termék hozzáadás

Itt két opció közül választhatunk: Hozzáadás egyesével vagy Halmozott hozzáadás. Amennyiben gyengébb gépünk van illetve lassabb internetünk érdemes a halmozott hozzáadást használni, ebben az esetben ameddig folyamatosan ütünk fel egymás után termékeket egy adott rövid időn belül a gép nem kezd el kommunikálni a szerverrel csak abban az esetben ha egy kis időre ez a termék felütés befejeződik így a sok üzenet küldés helyett egy tömbözött üzenetet küld el.

#### Termék kosárba animáció

Itt tudjuk beállítani, hogy a termék felütést követően a kosárba való bekerülés egyből történjen meg vagy egy szép becsúszós animáció keretein belül.

### Lezárt rendelések állapota

#### Sikeresen lezárt rendelések

* Automatikus eltüntetés: lezárást követően rövid idővel automatikusan eltűnik
* Kézi eltüntetés: Kiütést követően egy újabb gomb megnyomása szükséges az eltüntetéshez

#### Sikertelenül lezárt rendelések

* Automatikus eltüntetés: lezárást követően rövid idővel automatikusan eltűnik
* Kézi eltüntetés: Kiütést követően egy újabb gomb megnyomása szükséges az eltüntetéshez

### Kereső mező működés

Kereső mező törlése ekkor

{% tabs %}
{% tab title="Soha" %}
A kereső mezőbe beírt értéket kézzel kell törölni
{% endtab %}

{% tab title="Kategória váltáskor" %}
A kereső mezőbe beírt érték törlődik, ha kategóriát váltunk
{% endtab %}

{% tab title="Termék felütés után" %}
A kereső mezőbe beírt érték törlődik, ha felütöttünk egy terméket
{% endtab %}
{% endtabs %}

### Egyéb

#### Termék ablak nyitása több méret esetén

Ha ez az opció be van kapcsolva és egy terméknek több mérete van, a termék részletező ablak automatikusan megnyílik a termék felütésekor, hogy tudjunk választani.

#### Termékkép kikapcsolás

Amennyiben ez aktív abban az esetben a feltöltött képeket nem jeleníti meg a termékeknél

#### Kategóriák ABC sorrendben

A kategóriákat ABC sorrendbe rendezi

#### Termékek ABC sorrendben

A termékeket ABC sorrendbe rendezi

#### Paginálás ki

Eladás oldalon a lent található _(1) Termék neve_ rész nem jelenik meg így kikapcsolva a gyors ugrás lehetőségét sok termék esetén. Ezt abban az esetben javasolt kikapcsolni amennyiben nincs annyi termékünk, hogy egy teljes oldalt befedjen.

#### Pénzösszeg ki

A fizető ablakban a készpénzes fizetési mód kártya jobb szélén levő pénzösszeg gomb eltüntetése

#### Körök

Több körös rendelés felvételekor érdemes bekapcsolni, hogy megjelöljük a konyha számára, hogy melyik ételek, melyik körben mennek ki a vendég számára, hogyan készüljenek sorrendben.

#### Üres asztal elől

Az asztal listán a már foglalt asztalokat a sor végére helyezi, így például a bejáratnál lévő hostess/fogadós tudja, hova lehet ültetni az érkező vendégeket.

#### Előnyugta

Amennyiben ez be van kapcsolva, a fizetési ablaknál megjelenik az Előnyugta gomb. Ha van blokk nyomtató, és ki is van választva blokkok nyomtatására, akkor az Előnyugta gomb megnyomásával egy az összesítőhöz hasonló előnyugtát tudunk nyomtatni. Ezen természetesen feltüntetjük, hogy ez csak előnyugta, illetve azt is, hogy még nincs fizetve a rendelés. Ez akkor lehet hasznos, ha jelezni akarjuk egy vendég felé, hogy mennyit kell fizetnie, illetve milyen tételekért fog fizetni.

#### Fizettetés után gyűjtő összesítő

Ha bekapcsoljuk ezt a gombot, a rendelés fizettetése után kapunk egy ablakot amiben látható, hogy milyen áfacsoportba hány Ft-ot kell beütni a pénztárgépbe (ha esetleg nem lenne integrálva).

#### Hangok

Bekapcsolt állapotban a készülék hangjelzést ad a rendelések beérkezésekor és a státuszok módosításakor.

#### Nyugta jóváhagyás fizettetés után

Ha nem adóügyi nyomtatót használunk, hanem pénztárgépet, érdemes ezt a lehetőséget bekapcsolni, így egy ablak a tranzakció után megkérdezi hogy sikerült-e a nyugta kinyomtatása. Amennyiben ezt használjuk, nap végén nem lesz kérdéses nyugta és jó eséllyel nem lesz eltérés a BarSoft és a pénztárgép között.

#### Mérés később

Ez a funkció lehetővé teszi hogy mérés nélkül küldjünk be termékeket a konyhára, hogy azokat utólag sütés után le tudják mérni és a megfelelő árral lehessen terhelni a vendéget. Ha ez be van kapcsolva, egy mérendő termék mért értékénél megtalálható lesz a "Mérés később" gomb, aminek kiválasztásával 0kg súlyú terméket küldünk a konyhára, ezt fizettetés előtt szükséges lemérni, hogy fizetni lehessen a rendelést.

#### KIOSK és BrandApp rendelések értesítő

Amennyiben nem csak POS-t használunk, hanem van KIOSK vagy BrandApp rendelési felülete a vendégnek, érdemes bekapcsolni ezt a funkciót, így ha nem a POS-on adják le a rendelést, akkor is látszik majd egy értesítés:

<figure><img src="../../.gitbook/assets/image (38).png" alt=""><figcaption></figcaption></figure>

#### Nem látható termékek elrejtése

Ha ez be van kapcsolva, azok a termékek, amik nem láthatóak a KIOSK-on vagy a BrandAppon, már a POS-on sem fognak megjelenni

#### Termék ajánlás

Ezzel a funkcióval az eladó felületen a fizetés gomb megnyomása után mutatjuk az upsell-ként beállított termékeket, ha a kosárban van hozzá tartozó termék

<figure><img src="../../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

#### Hosszú nyomás művelet

Itt kiválaszthatjuk, hogy mi történjen amennyiben egy termékre hosszan nyomunk (számítógépen jobb kattintás). \
**Számláló**: Termékmennyiség megadása \
**Részletek megjelenítése**: felugró ablak ami a termékhez rendelt méreteket és módosítókat és egyéb információkat mutatja számunkra

#### Alapértelmezett Elvitel/Helyben

Ezzel kiválaszthatod, hogy az alapértelmezett kosár az elviteles, vagy helyben fogyasztásos legyen.&#x20;

#### Eladási mód

{% tabs %}
{% tab title="Vendéglátás" %}
Alapbeállítás: a vendéglátással kapcsolatos termékek és kategóriák jelennek meg, az RMS NTAK szolgáltató által lesz az adat kiküldve
{% endtab %}

{% tab title="Jegyeladás" %}
A jegyeladással kapcsolatos termékek és kategóriák jelennek meg, a TSS NTAK szolgáltató által lesz az adat kiküldve
{% endtab %}

{% tab title="Választható" %}
A kategóriák felett megjelenik egy gomb, amivel változtathatunk a két mód között

<figure><img src="../../.gitbook/assets/szviccs.gif" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

## Elrendezés

### Felület elrendezése

Itt a következő opciókat adhatjuk meg:

* A kosár megjelenítése bal oldalon (bal kezes felhasználók számára ideális lehet)
* Kategóriák egymás mellett (ha be van kapcsolva a kategóriákat egymás mellett jeleníti meg, egyébként egymás alatt)
* Kategóriák termékek után (ha a kategóriák egymás mellett vannak és a termékek után, akkor a képernyő alján jeleníti meg, ha egymás alatt és a termékek után, akkor a jobb oldalon)

### Eladási felület

Az itt levő gombokkal tudunk elrejteni bizonyos elemeket az eladási felületről.\
Ezt érdemes beállítani, hogy csak azok a gombok jelenjenek meg, amiket szeretnénk, hogy az alkalmazottak tudjanak használni.

## Kinézet

### Termékek elrendezése

#### Termék oszlopok száma

Itt tudjuk beállítani, hogy az eladási felületen hány oszlop jelenjen meg ami a termékeket tárolja 1-8 értékig

#### Termék magasság

Itt tudjuk beállítani, hogy az eladási felületen milyen magas legyen egy termék doboza

#### Termék betűméret

Itt tudjuk beállítani, hogy az eladási felületen és az Order Manager-ben mekkora legyen a szöveg

#### Termék betű vastagság

Itt tudjuk beállítani, hogy milyen vastag legyen a termékek szövege

#### Betűtípus

Kiválaszthatjuk a számunkra legszimpatikusabb betűtípust, így a továbbiakban ezt fogja használni a POS rendszer.

### Gombszín

A rendszerben megjelenő színes gombok színét állíthatjuk.

### Szín mód

Itt a sötét és világos mód között váltogathatunk

Egyes számítógépek esetében amennyiben sötét módot használunk akkor is javíthatunk az eszköz gyorsaságán

### Kategória oszlop

&#x20;Amennyiben nem fentre vannak rendezve a kategóriák, be lehet állítani a kategória gombok szélességét.

