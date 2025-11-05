# 📋 VIP igénylés menete

## Licensz igénylése

A VIP modulunk használatához szükséged lesz a VIP licensz megigényelésére első körben.&#x20;

A modult [ezen az oldalon](https://barsoft.hu/billing/brand/license/brand) lehet megigényelni, enélkül nem fogja engedni a rendszer a további lépéseket.

{% hint style="info" %}
Abban az esetben ha a bevezetéssel kapcsolatban kérdéseid lennének, nem tudod merre indulj és szükséged van segítségre, keress minket bizalommal!
{% endhint %}

## Termékek VIP beállítása

### Termékek szinkronizálása

A termékeket átszinkronizáljuk neked az iPanel felületről ahol már létrehoztad a kategóriákat és termékeket amiket a POS-on értékesítesz a VIP részlegre, így azzal nem kell időt töltened, hogy újra létrehozd őket.

### Termékek kategorizálása a Loyalty rendszerben

A termékek átszinkronizálása után tetszőlegesen kategorizálhatod a termékeket, és nem feltétlenül kell ugyanannak a kategória struktúrának lennie, mint ami a POS felületen látható.

{% hint style="success" %}
**Mi a lényege ennek?**

A Loyalty rendszerben a termék kategóriák nem az ügyfelek felé fognak látszódni, hanem a te munkádat fogja megkönnyíteni ha létrehozol egy kupont például, mert sokkal egyszerűbbé teheted a termékek hozzáadását egy-egy kuponhoz.
{% endhint %}

**Reprezentatív példa**

Abban az esetben, ha szeretnél egy olyan kupont létrehozni, ami a reggelihez egy ingyen kávé, viszont a POS rendszerben az átláthatóság miatt külön kategóriában vannak a Pékáruk, a Toastok, a Kávék, a Tojásos ételek, akkor a Loyaltyban lehetőséged van arra, hogy csinálj egy Reggeli kategóriát, és minden olyan terméket belerakj ebbe a kategóriába, ami az ajándék kávéhoz szükséges, így pár kattintással létre tudod majd hozni a kuponodat.

## Kedvezmények beállítása

A termékekre kedvezményeket akár kuponnal, vagy kártyakedvezménnyel tudtok adni. Ez a kettő kombinálható.

Ha kártya kedvezménnyel adjátok, akkor be lehet állítani, hogy pl Személyzeti kártya, amit kifejezetten csak az személyzetnek állítotok be, így ők fix kedvezményt kapnak.

Ha kupon kedvezményt szeretnétek, az megoldható specifikus termékekre, vagy teljes kosár értékre is, illetve a kuponokkal oldható meg az is, ha ingyen terméket szeretnétek adni.

Kuponkódokkal lehetséges adott személyek számára kiadni a kupont, akik akár többször is beválthatják az adott kupont a megadott érvényességi időn belül. Ez szintúgy állítható, hogy hányszor használhatják fel személyenként, vagy globálisan.

## Vendégfelület kiválasztása

A VIP-hez jár egy, a vendégek számára publikus felület is, amin a kuponokat tudnak kiválasztani, nézegetni, a pontgyűjtés állapotát tudják megnézni, hogy éppen hol tartanak, illetve ezen a felületen mutatjuk a VIP felhasználók QR kódját is, amit be tudtok olvasni ahhoz, hogy a vásárló kedvezményei és kuponjai automatikusan aktiválódjanak a POS-on.&#x20;

Ez a felület lehet egy QR kódon vagy webcímen keresztül elérhető webalkalmazás, vagy egy (Android vagy IOS) áruházból letöltött app.&#x20;

Amint a felhasználók is belépnek az alkalmazáson keresztül, már meg is fognak jelenni a vásárlók menüpontban.

## Vendégfelület testreszabása

A vendégfelület megjelenítését az AppEditor modulunkban tudod módosítani, testreszabni.

* Lehetőséged van színeket állítani, hogy tükrözzék a Brand-ed színvilágát
* Ki tudod választani a képeket, amik az oldalon megjelennek (pl.: Logó, alapértelmezett VIP kártya kép, alapértelmezett termékkép, térkép jelölő)
* Tudod módosítani az elrendezést (pl.: főoldali elemek, alsó felső sáv elemek)
* Szabályozhatod a lekerekítés mértékét.

Vannak funkciók, amiket csak a VIP modulon belül tudsz módosítani, mint például:

* Kártyaszintenként különböző képek megadása
* Kuponok és azok képei
