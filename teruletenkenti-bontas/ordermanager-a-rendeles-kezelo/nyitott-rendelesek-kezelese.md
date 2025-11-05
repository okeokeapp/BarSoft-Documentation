# 📂 Nyitott rendelések kezelése

## Nyitott rendelések menüpont

Nyitott rendeléseket az OrderManagerben a gyors nyugtás értékesítés során alkalmazzuk.

A nyitott rendelések nézetet az OrderManager felületén a jobb felső sarokban található <mark style="color:blue;">"Nyitott rendelések"</mark> menüpontban érheted el.

Mikor használjam ezt a nézetet?

Akkor érdemes használni, ha nem asztaloztok, viszont fontos az, hogy a konyha visszajelezze, hogy mikor lett kész az adott rendelés.

Általában ilyen esetben vagy vendéghívóval pick up pontra hívják a vendéget, vagy runner segítségével kiviszik a rendelést.

A rendelés felvétel ebben az esetben a pultnál történik.

## Rendelések kezelése

### Rendelések felvétele

A rendelések kezelése igen egyszerű a felületen.

Értékesítés során az OrderManager-be automatikusan bekerülnek a tételek fizetés után (gyors nyugtás rendelés felvétel esetén).

<figure><img src="../../.gitbook/assets/quicksell-om.gif" alt=""><figcaption></figcaption></figure>

### Rendelések opciói

A státuszok mellet további lehetőségek is adottak a rendelések kapcsán.

#### **Fejléc adatok:**

1. Mikor lett felütve a rendelés
2. Ki ütötte fel (milyen POS felhasználóval) / Ha regisztráltunk azonosítót a rendelés leadásakor, az itt jelenik meg, vagy ha BrandApp-ról érkezik a rendelés, akkor a felhasználó neve
3. Milyen eszközön történt a felütés (POS, BrandApp, KIOSK)
4. Fizetve van-e a rendelés avagy nincs
5. Gyorsnyugta vagy asztalos rendelés (asztal esetében kiírjuk melyik asztal)

#### **Rendelés opciók:**

Ha a kártyára kattintunk a rendelésnél, akkor a rendeléssel kapcsolatos opciókat találjuk.

* Státuszok
* Fizetés és Bontott fizetés (ha nincs fizetve)
* Megszakítás (sztornó)
* Konyha nyomtatás (arra az esetre, ha a konyhai rendelés blokk nem nyomtatódott volna ki)
* Áthelyezés asztalra / Másik asztalra

Amennyiben a rendelésen belüli tételre kattintunk, úgy a tételekkel kapcsolatos státuszokat tudjuk kezelni.

{% hint style="info" %}
**TIPP**

Ha bekapcsolod a "Fogadva" státuszt, akkor a konyhára csak akkor küldjük be a rendelést, amennyiben ezt a státuszt kiválasztottad.
{% endhint %}

