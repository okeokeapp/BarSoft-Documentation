---
description: A BarSoft POS eszközökkel kapcsolatos beállítási lehetőségek
---

# 💻 POS eszközök

Navigálj az iPanel / eszközök / POS eszközök menüpontra.

Itt látod a már meglévő POS eszközöket.



{% hint style="info" %}
INFÓ

A brand regisztrációval automatikusan létrehozunk 1 POS eszközt, amit azonnal tudsz használni.
{% endhint %}

## Új eszköz létrehozása

Kattints az <mark style="color:blue;">**Új létrehozása**</mark> gombra.

Add meg az eszköz nevét és azt, hogy melyik lokációra szeretnéd azt aktiválni.

{% hint style="info" %}
TIPP

Ha csak kipróbálni szeretnél bizonyos beállításokat, érdemes egy teszt készüléket létrehozni.&#x20;

Ez a készülék ingyenes, sem heti, sem havidíjat nem számolunk fel érte.

A teszt készüléken leadott rendelések nem keverednek az éles készülék rendeléseivel, nem kerülnek beküldésre NTAK vagy NAV felé, tehát nem küldi ki az adatokat adóügyi nyomtatóra sem.&#x20;

A rendelés blokkokat kinyomtatja a hozzá kapcsolt blokknyomtató, viszont ezeken az első sorban fel is tüntetjük, hogy teszt rendelés került kinyomtatásra.

Egy teszt készülék nem lehet éles készülék.&#x20;

Ha egy éles készüléket szeretnénk teszt környezetben kipróbálni, a beállítások, Eszköz műveletek, Sandbox mód-dal tudjuk bekapcsolni, ez ki is kapcsolható.
{% endhint %}

{% hint style="warning" %}
FONTOS

HA több lokációval rendelkezel, akkor nagyon fontos odafigyelni arra, hogy melyik lokációra aktiválod a POS eszközt, ugyanis az adott lokáció beállításait fogja automatikusan használni a POS.
{% endhint %}

Az adatok megadása után kattints a <mark style="color:green;">**Létrehozás**</mark> gombra.

Az eszközöket ugyanitt tudod <mark style="color:red;">törölni</mark> is

<figure><img src="../../.gitbook/assets/pos eszk.gif" alt=""><figcaption></figcaption></figure>

## Aktiválás



{% embed url="https://www.youtube.com/watch?v=oNj0gKYoqp8" %}

Miután letöltötted a BarSoft applikációt Windowsra, vagy Androidra, az alábbi képernyő fog fogadni az applikáció megnyitása után.

<figure><img src="../../.gitbook/assets/Képernyőkép 2024-04-03 102013.png" alt=""><figcaption></figcaption></figure>

Az <mark style="color:blue;">**"Igen, aktiválom (123456)"**</mark>  gombon látszik az a 6 számjegyű kód, amit iPanelen az adott POS eszköz profil kártyáján az <mark style="color:blue;">**Aktiválás**</mark> gombra kattintva be kell írni.

Ha a gombra rányomnál, ott is írjuk a folyamat menetét.

<figure><img src="../../.gitbook/assets/Képernyőkép 2024-04-03 102028.png" alt=""><figcaption></figcaption></figure>

<div data-full-width="false"><figure><img src="../../.gitbook/assets/activ.gif" alt=""><figcaption></figcaption></figure></div>

Az aktiválás után már használatra is kész a szoftver!

{% hint style="warning" %}
INFO

Természetesen vannak olyan beállítások amiket el kell végezni a POS-on, (a felületen) amik eszköz specifikusak mint például: betűméret, színek stb...)
{% endhint %}

{% hint style="info" %}
TIPP

Az aktiválást és a beállításokat iPanelen akár TELEFONRÓL is tudod intézni!
{% endhint %}

## Fizetési módok hozzáadása

Ahhoz hogy el tudjuk kezdeni használni a beaktivált POS eszközünket, néhány beállítást még el kell / lehet végezni.

Az egyik ilyen kötelező az a fizetési módok hozzáadása.

### Mit jelent a fizetési módok hozzáadása?

A branden belül több fizetési módot is kezelhetsz, és POS eszközönként megadhatod, hogy azokon az eszközökön milyen fizetési módokat szeretnél használni.

### **Példa a fizetési módokra**

Az egyik gép össze van kötve a TEYA terminállal, a másikon nincs, vagy az egyikhez van SZÉP kártya terminál a másikhoz nincs.

Így külön be tudod állítani az eszközökhöz a fizetési módokat.

### A fizetési módok hozzáadása

Kattints a POS profil kártyán a "**Fizetési Beállítások**" gombra.&#x20;

<figure><img src="../../.gitbook/assets/image (89).png" alt=""><figcaption></figcaption></figure>

A "**Szerkesztés"** gombra kattintva a felugró ablakban hozzá tudod adni azokat a fizetési módokat, amiket előzőleg létrehoztál.

<figure><img src="../../.gitbook/assets/image (90).png" alt="" width="213"><figcaption></figcaption></figure>

{% content-ref url="../fizetesi-modok/" %}
[fizetesi-modok](../fizetesi-modok/)
{% endcontent-ref %}

{% hint style="warning" %}
FONTOS!

A fizetési módok változtatása során a POS appot újra kell indítani a változtatások véglegesítéséhez!
{% endhint %}

<figure><img src="../../.gitbook/assets/fizmodok.gif" alt=""><figcaption></figcaption></figure>

## Egyéb beállítások

Az egyéb beállásokban találhatod meg a POS pulthoz rendelését, valamint az automatikusan beléptetett felhasználó opcióját.

Mi mit jelent?

### Pulthoz rendelés

Ha pultokat is kezelsz (kávés, konyhai, halas, burgeres, lángosos stb...) akkor egy - egy POS eszközt hozzá tudsz rendelni a már létrehozott pultokhoz.

Ez azt jelenti, hogy az adott POS eszközön csak az adott pult termékei fognak megjelenni.

{% hint style="danger" %}
FONTOS!

Azok a termékek, amiket nem rendelsz hozzá pultokhoz, MINDEN POS eszközön meg fog jelenni! További információt a pultok-nál találsz.
{% endhint %}

### Automatikusan beléptetett felhasználó

Amennyiben szeretnéd, hogy az adott POS-on egy felhasználó automatikusan bejelentkezzen indításkor, úgy a felhasználó listából ezt ki tudod választani.

Ilyenkor az indítás után se pin kódot, se start gombot nem kell megnyomni, automatikusan bejelentkeztetjük a kiválasztott felhasználót.

<figure><img src="../../.gitbook/assets/pos-counter-user-login.gif" alt=""><figcaption></figcaption></figure>

### Kijelentkeztetés / adatok módosítása / törlés

Abban az esetben, ha mondjuk a hardver eszközöd tönkre ment, vagy másik hardver eszközt szeretnél használni, nincs szükség új profil létrehozására.

Jelentkeztesd ki az eszközt, majd az adatok (pl név) opcionális átírásával és egy újra aktiválással könnyedén meg tudod ezt tenni.

