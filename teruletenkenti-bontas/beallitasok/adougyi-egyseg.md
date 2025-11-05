---
description: Adóügyi nyomtató / Online pénztrágép csatlakoztatása
---

# 📠 Adóügyi egység

{% hint style="danger" %}
**FIGYELEM!**

Ezekhez a beállításokhoz érdemes pénztárgép forgalmazódat megkérni, hogy segítsen, melyik protokollt kell használnod a működéshez!
{% endhint %}

A menüpontot a beállítások -> <mark style="color:blue;">Adóügyi egység</mark> gombra kattintva éred el.

Itt tudod kiválasztani, milyen szoftver verziószámú pénztárgéped van, illetve hogy soros (serial), QR kódos, vagy bluetooth-os csatlakozásod van.

Fiscat adóügyi nyomtató vagy Bee esetében, a protokoll kiválasztása után párosításkor tudjuk kiválasztani a csatlakozás típusát.

Miután kiválasztottuk az adóügyi egységet, ellenőrizzük le a gyűjtő beállításokat.

<figure><img src="../../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
**Fontos!**

Az itt beállított gyűjtőkre küldi a BarSoft az adóügyi felé az adatot, tehát ha ide olyan gyűjtő számát írjuk be, ami nincs beprogramozva a pénztárgépen, akkor "Gyűjtő nincs beprogramozva" hibaüzenetet kapunk vissza.
{% endhint %}

Miután a párosítást sikerült elvégeznünk fontos, hogy a további beállítások között írjuk be az adóügyi egység AP számát, majd mentsük el. Így amikor sztornóra kerül a sor, nem lesz szükséges beírni ismét ezt az adatot.

<figure><img src="../../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

A "További beállítások" között megtalálható még néhány funkció, ami az adóügyi nyomtatáshoz kapcsolódik.

<figure><img src="../../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>

<details>

<summary>Utalásos fizetésnél ne nyomtasson</summary>

Amennyiben a fizettető ablakban átutalás típusú fizetési módot választunk ki, az adóügyi egységre nem küldjük ki a nyugtát, így a vendég akkor tud nyugtát kapni (manuálisan), amikor megtörténik az átutalás.

</details>

<details>

<summary>ÁFÁ-s számla nyomtatás kikapcsolása</summary>

Amennyiben adóügyi nyomtatót és online számlázó szolgáltatást is használunk, viszont azt szeretnénk hogy az ÁFÁ-s számla e-mailben küldődjön ki a papír formátum helyett, ez a funkció lesz segítségünkre.

</details>

<details>

<summary>Gyűjtőt nyomtasson termék helyett</summary>

Ha rövidíteni szeretnénk az adóügyi nyugtánkon, ezzel a megoldással könnyű dolgunk lesz, ugyanis így nem fogjuk kiírni a hosszú termékneveket, csak azt, melyik gyűjtőre mennyi pénz ment át.

</details>
