---
description: Branded összes boltja egy helyen
---

# 🏘️ Lokációk

Ezen az oldalon tudod kezelni boltjaidat, melyek ugyanabból az adatbázisból dolgoznak, és egy helyen látod az összes adatot, ami megjelenik az iPanelen.

{% hint style="danger" %}
FIGYELEM

A multi lokáció kezeléshez szükség lesz a Franchise modulra, melyet a Billing felületen tudsz megvásárolni!
{% endhint %}

## Új lokáció létrehozása

## A lokációk beállításai

<table data-view="cards"><thead><tr><th></th><th></th><th></th><th data-hidden data-card-target data-type="content-ref"></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td></td><td>Alapadatok</td><td></td><td><a href="lokaciok.md#alapadatok">#alapadatok</a></td><td><a href="../.gitbook/assets/basic-info.png">basic-info.png</a></td></tr><tr><td></td><td>Szervízdíj, borravaló, szállítás</td><td></td><td><a href="lokaciok.md#szervizdij-borravalo-szallitas">#szervizdij-borravalo-szallitas</a></td><td><a href="../.gitbook/assets/szervizdij.png">szervizdij.png</a></td></tr><tr><td></td><td>Cím</td><td></td><td><a href="lokaciok.md#cim">#cim</a></td><td><a href="../.gitbook/assets/cim.png">cim.png</a></td></tr><tr><td></td><td>Integrációk</td><td></td><td><a href="lokaciok.md#integraciok-fruitsys-meg-fog-szunni">#integraciok-fruitsys-meg-fog-szunni</a></td><td><a href="../.gitbook/assets/integrációk.png">integrációk.png</a></td></tr><tr><td></td><td>Online</td><td></td><td><a href="lokaciok.md#online">#online</a></td><td><a href="../.gitbook/assets/online.png">online.png</a></td></tr><tr><td></td><td>Értesítések</td><td></td><td><a href="lokaciok.md#ertesitesek">#ertesitesek</a></td><td><a href="../.gitbook/assets/értesítések.png">értesítések.png</a></td></tr><tr><td></td><td>Státuszok</td><td></td><td><a href="lokaciok.md#statuszok">#statuszok</a></td><td><a href="../.gitbook/assets/statuszok.png">statuszok.png</a></td></tr></tbody></table>

Lokációk menü ponton belül találhatóak a létrehozott lokációk. Kattints jobb oldalt a sor végén lévő ceruzára, ha az adatait szeretnéd állítani.

<figure><img src="../.gitbook/assets/Képernyőkép 2024-11-26 141715.png" alt=""><figcaption></figcaption></figure>

## Alapadatok

Az alapadatok menüponton belül tudod engedélyezni a lokációt, tudod módosítani a nevét, leírását, valamint az adott üzlet NTAK szolgáltatóját.

{% hint style="info" %}
INFO

A leírás csak akkor fontos, ha online is szeretnél értékesíteni, hiszen az appon belül mutatjuk meg ezeket az értékeket.
{% endhint %}

Az NTAK szolgáltatással kapcsolatos beállításokat az [<mark style="color:blue;">**NTAK Portálon**</mark>](https://info.ntakportal.hu/) tudod megtenni, majd a létrehozott szolgáltatót tudod itt beállítani.

{% hint style="danger" %}
NAGYON FONTOS!

Ahhoz, hogy az NTAK adatbeküldés rendben működjön, a szolgáltatót muszáj hozzárendelni egy-egy lokációhoz.
{% endhint %}

## Szervízdíj, Borravaló, Szállítás

Ezen az oldalon tudod beállítani a szervízdíjat, borravalót és a szállítást.

<figure><img src="../.gitbook/assets/Képernyőkép 2024-11-26 142024.png" alt=""><figcaption></figcaption></figure>

### Szervízdíj

{% embed url="https://www.youtube.com/watch?v=okELGp6cCfY" %}

A BarSoft tud hozzáadott és fordított szervízdíjat is kezelni.

{% hint style="info" %}
Mit jelent a Fordított szervízdíj?

A fordított szervízdíj a termék árába van beépítve, így nem plusz százalékos mértékben jelenik meg a nyugtán.\
Ettől függetlenül a szervízdíj mennyiséget továbbra is kedvezményesen lehet elszámolni.
{% endhint %}

iPanelen több szervízdíj opciót is létre lehet hozni, és kosaranként lehet változtatni a POS-on az értékét.

Minden Platformunkra külön lehet állítani a szervízdíj mértékét.

{% hint style="warning" %}
JÓ TUDNI!

A többféle szervizdíj opció közül csak a POS felületén lehet rendelésenként választani, miután azokat az iPanelen előzetesen beállították! \
A KIOSK-on és a BrandAppon csupán 1 opció (ami fentebb meg lett határozva) lesz érvényes.

<img src="../.gitbook/assets/image (39).png" alt="" data-size="original">
{% endhint %}

### Szállítás

A szállítás opció alatt meg lehet határozni a szállítási díj mértékét, a számlán szereplő nevet ( tetszőleges) valamint a szállítással kapcsolatos NTAK kategóriát.

### Borravaló típusa

{% embed url="https://www.youtube.com/watch?v=okELGp6cCfY" %}

A borravaló elszámolásának típusát lehet itt beállítani.

Ezzel abban az esetben kell foglalkozni, ha szeretnéd a borravalót elszámolni és vezetni a BarSoft rendszerében.

Ha nem szeretnél ezzel foglalkozni akkor válaszd a <mark style="color:blue;">"Nincs elszámolás"</mark> opciót.

{% hint style="warning" %}
JÓ TUDNI!

Ha nem állítod ezt a beállítást, abban az esetben a <mark style="color:blue;">"Nincs elszámolás"</mark> beállítás lesz érvényben, ha ütöd a borravalót.
{% endhint %}

#### Nincs elszámolás

A nincs elszámolás azt jelenti, hogy a borravaló mértékével és összegével nem foglalkozik a rendszer, tehát sem a kimutatásokban, se máshol nem fogjuk mutatni, valamint az NTAK rendszerébe se küldjük be.

#### Termék 0% ÁFA

Ebben az esetben termékként küldjük be a borravaló mennyiségét 0%-os ÁFA tartalommal, valamint bekerül az NTAK rendszerébe is statisztikai adatként.

#### Pénz BE

Ha a pénz be funkciót választod, ebben az esetben a borravaló bekerül az online pénztárgépbe, valamint az adóügyi nyomtató rendszerébe is. Így a NAV látni fogja az adatokat mint borravaló és ennek megfelelő módon kell majd adózni utána.&#x20;

## Cím

Ebben a menüpontban meg tudod adni a boltod címét.&#x20;

Ez akkor fontos, ha BrandApp-al is rendelkezel, hiszen opcionálisan meg tudjuk mutatni a vendégnek, hogy hol található üzleted.

## Integrációk - Fruitsys (Külön modulba költözik)

Az integrációk menüpontban a Fruitsys rendszerrel kapcsolatos menüpontot találod, ha alapesetben Fruit ügyfél vagy. Itt technikai beállításokat hajtunk végre, amivel nem kell foglalkoznod.

Amennyiben nem az vagy, ezt a menüpontot nem fogod látni.&#x20;

## BrandApp, Számlázás

Ebben a menüpontban a BrandApp-al, számlázással kapcsolatos beállításokat tudod elvégezni.

<figure><img src="../.gitbook/assets/Képernyőkép 2024-11-26 142208.png" alt=""><figcaption></figcaption></figure>

Be tudod állítani az alábbiakat:

* <mark style="color:blue;">**Rendelhetek innen:**</mark> ha be van kapcsolva, online elérhető lesz a rendelés az appról azokkal a termékekkel, amelyek ezen a lokáción láthatóvá vannak téve
* <mark style="color:blue;">**Alapértelmezett lokáció:**</mark> ha ez be van kapcsolva, akkor ez lesz az alapértelmezett lokációd (KI FOGJUK VEZETNI)
* <mark style="color:blue;">**Alapértelmezett elkészítési idő:**</mark> Az appon ezt az értéket fogjuk mutatni, rendelés leadástól a kézhez vételig. Ez egy becsült érték lesz, amit meg is írunk az ügyfélnek: Körülbelül ennyi idő múlva lesz kész.
* <mark style="color:blue;">**Számlázási profil:**</mark> Itt tudod hozzárendelni a fizetési módok menüpont / számlázás részénél létrehozott számlázási profilodat a lokációhoz.
* <mark style="color:blue;">**Fizetési módok:**</mark> Itt tudsz hozzáadni fizetési módokat az online értékesítéshez. Az online fizetési módokat az online fizetésnél tudod előre beállítani.
* <mark style="color:blue;">**Lokáció képe:**</mark> Amennyiben több lokációd van, és feltöltesz képet hozzájuk, a terheltség jelző oldalon mutatjuk ezeket.
* <mark style="color:blue;">**Terheltség:**</mark> Ez alapján tudod jelezni a vendégek felé, hogy éppen milyen terheltséggel fut az adott lokáció.
* <mark style="color:blue;">**Nyitvatartás:**</mark> Ezt beállítva a terhelség jelző oldalon a vendégek látni fogják a lokációk nyitvatartását.

## Értesítések

Több fajta értesítést is be lehet állítani a rendelésekkel kapcsolatban.

1. Dolgozói értesítések
2. Vendég értesítések

<figure><img src="../.gitbook/assets/Képernyőkép 2024-11-26 1457181.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
TIPP

A vendég értesítéseket akkor kell használni, ha BrandApp-ot is használsz, hiszen a rendelés státuszokat fogjuk küldeni a vendégnek.
{% endhint %}

{% hint style="warning" %}
FONTOS

Az értesítések kiküldéséhez kötelező rendelés státuszokat használni, különben nem tudjuk mi alapján kiküldeni a rendelés állapotát.
{% endhint %}

### Dolgozói értesítések

Dolgozói értesítésekhez a felhasználó melletti checkboxokat kipipálva E-mail / Push notificationt lehet küldeni.

{% hint style="warning" %}
FONTOS

Push notification csak akkor fog működni a rendelésekkel kapcsolatban a dolgozó / tulajdonos számára, ha le van töltve az iPanel applikáció, vagy desktopon engedélyezve vannak az értesítések.
{% endhint %}

4 fajta értesítést lehet beállítani:

* Beérkezett rendelés
* Sikeresen lezárt (fizetett) rendelés
* Sikertelenül lezárt (sztornózott) rendelés
* Műszak zárás

#### Beérkezett rendelés

Abban az esetben, ha beérkezik egy rendelés, tudunk róla értesítést küldeni. Ez csak a beküldést jelenti, vagy éppen az asztalra felütést.

#### Sikeresen lezárt rendelés

Abban az esetben, ha gyorsnyugtás nézetben / bontott fizetéssel asztalon / online applikáción keresztül a fizetés megtörtént és KIADVA státuszt kapott a rendelés, úgy értesítést küldünk róla.

{% hint style="danger" %}
FIGYELEM!

Csak azokat a rendeléseket küldjük ki ebben az esetben értesítésként, amik fizetés után megkapják a KIADVA státuszt!

Abban az esetben ha ki van fizetve, de nincs beállítva a kiadva státusz, úgy nem fogunk értesítést küldeni!
{% endhint %}

#### Sikertelenül lezárt rendelés

Abban az esetben, ha a rendelés meghiúsul valamilyen oknál fogva (pl.: online nem fejezték be és nem fizették ki 5 percen belül) vagy sztornózzák a rendelést, úgy értesítést küldünk róla.

#### Műszak zárás

Push értesítés esetén kiküldjük a műszak zárásakor a nyitástól számított termék eladások összegét, illetve a tényt, hogy műszakzárás történt.\
E-mail értesítés esetén egy rövid e-mail-t küldünk, az összegről, hogy hol történt a zárás, ki és mikor nyitotta/zárta a műszakot. Ez tartalmaz még egy Műszak részletei gombot, ami elnavigál az adott műszakhoz az iPanel-en.

### Vendég értesítések

A vendégek számára BrandApp-on keresztül többfajta értesítést is tudunk küldeni.

Webes applikáció esetén webes üzeneteket (ha a weboldalon engedélyeztük azt), letöltős app esetében pedig Push üzeneteket.



#### Beérkezett:

Abban az esetben, ha beérkezik sikeresen a rendelés, úgy üzenetet tudunk küldeni a felhasználónak



#### Látták

Ha be van állítva ez a státusz, akkor ha "láttamozzuk" a rendelést, úgy értesítést küldünk a felhasználónak, hogy lássa, hogy elkezdtünk a rendeléssel foglalkozni.



#### Fizetési emlékeztető

Abban az esetben, ha megszakítja az online fizetést tudunk neki emlékeztetőt küldeni, hogy nem ment be a rendelése, mert nem fizette még ki a tételeket.



#### Megerősítve

Abban az esetben, ha megerősítették a rendelést, tehát a fizetés beérkezett és megkapta a konyha küldünk értesítést (és láttamoztuk ha be van kapcsolva)

#### Várható idő

POS-on tudunk állítani idő intervallumot, hogy mennyi idő alatt készül el a rendelés. Erről tudunk értesítést küldeni a vendég számára.



#### Kész

Amennyiben elkészült a rendelés és KÉSZ státuszra rakjuk, küldünk róla értesítést a vendégnek

#### Sikeresen lezárva

Abban az esetben, ha a rendelés KIADVA státuszt kapott, azaz elkészült és a futárnak vagy személyesen átadtuk a vendégnek "Jó étvágyat kívánunk" üzenetet küldünk.

#### Lezárva fizetés nélkül

Amennyiben nem került fizetésre a rendelés és túlléptük a 10 perces időablakot, úgy Lezárva fizetés nélkül értesítést küldünk, azaz töröljük a függőben lévő rendelését.

## Státuszok

<figure><img src="../.gitbook/assets/Képernyőkép 2024-11-26 151823.png" alt=""><figcaption></figcaption></figure>

A státuszok menüpontban be lehet állítani, hogy a POS-on milyen státuszokat szeretnénk kezelni a rendeléseknek.

{% hint style="info" %}
INFÓ

Mindig az a státusz lesz a legkorábbi státusz, ami legelsőnek be van kapcsolva! Tehát ha a RENDELÉS ELKÉSZÜLT és KIADVA státuszok vannak csak bekapcsolva, úgy a rendelés beérkezte után az első státusz amit lehet kezelni a KÉSZ státusz!
{% endhint %}

### Fizetés szükséges

Abban az esetben ha mindenképpen szükséges fizetés a rendelés beküldéshez az appon, vagy POS-on keresztül ezt a státuszt be kell kapcsolni.

{% hint style="warning" %}
FONTOS

Ebben az esetben a konyhai nyomtatóra csak fizetés után küldjük be a rendelést.
{% endhint %}

### Fogadva

Fogadva státusz a "Láttam"-al megfelelő, tehát beérkezik a rendelés és szükséges egy láttam státuszt állítani, hogy fogadtuk a rendelést és foglalkozunk vele.

### Várható elkészülési idő

A várható elkészülési idő státusz bekapcsolása után a POS-on 5-10-15-30-45 percek közül tudunk választani.

### Rendelés elkészült

A KÉSZ státusz azt jelzi, hogy elkészült a rendelés

### Kiadva

A KIADVA státusz azt jelzi, hogy a rendelést átvették, ezzel együtt lezáródik a rendelés.
