---
description: Online fizetési igények beállítása
---

# 🖱️ Online fizetési mód

{% hint style="info" %}
INFÓ

Ez a szekció akkor vonatkozik rád, ha BrandApp-ot szeretnél használni!
{% endhint %}

Az online profil létrehozásának lépései:

1. Online profil varázsló lépéseinek végrehajtása
2. VivaWallet beállítások
3. Lokációhoz rendelés

{% hint style="danger" %}
FIGYELEM!

Jelenleg, ha BrandApp-ot használsz, a javasolt online fizetési mód a VivaWallet. Éppen ezért ennek a beállításain fogunk végigmenni.\
\
A fiók, amin bemutatjuk, egy DEMO fiók, de ugyanazok a beállítások fognak kelleni, mint az éles fiókban.
{% endhint %}

## Viva Wallet és iPanel beállítások

{% hint style="info" %}
TIPP

Érdemes megnyitva tartani az iPanel felület és a Viva fiók oldalt, ugyanis egyszerre fogunk dolgozni a két felületen.
{% endhint %}

### Mire lesz szükséged?

#### Viva fiókból:

* Merchant ID (Kereskedő azonosító)
* API kulcs
* Source Code (app forráskódja)

iPanelen:

* Webhook link (ami a fenti adatok alapján épül össze)

## VivaWallet beállítások

Lépj be a VivaWallet fiókodba.

* Kattints a Beállítások menüpontra, majd az API hozzáférésre.
* Másold ki a Kereskedő azonosítót és az API kulcsot.

Lépj be az Értékesítés / Online fizetések / Weboldalak, Applikációk menüpontra.

Kattints a <mark style="color:green;">"</mark><mark style="color:green;">**Weboldal / applikáció hozzáadása"**</mark> gombra.&#x20;

A felugró ablakban írd be a következő adatokat:

* <mark style="background-color:blue;">**Másold ki a kódot - kelleni fog iPanelen**</mark>
* Adj meg egy nevet (Pl: BrandApp)
* Protokoll: https
* Domain név: okeoke.io
* Url: viva
* Minden checkbox-ot pipálj ki
* Kattints a **"**<mark style="color:green;">**Létrehoz**</mark>**"** gombra

## iPanel beállítások

Nyisd meg iPanel-en a Fizetési módok / Online profil varázslót

* Kattints az "**Új profil"** tabra
* Add meg a nevét és válaszd ki a "**Viva Smart Checkout"** típust
* Kapcsold be (Éles)
* Másold be a Merchant ID-t (Kereskedő azonosító)
* Másold be az API kulcsot
* Kattints a "**Létrehozás**" gombra
* Másold ki a linket

{% hint style="danger" %}
NAGYON FONTOS!

Minden esetben győződj meg arról, hogy a TELJES LINKET kimásoltad, különben a következő lépésben a VIVA felülete hibát fog mutatni!
{% endhint %}

<figure><img src="../../.gitbook/assets/online-payment-viva-setup1.gif" alt=""><figcaption></figcaption></figure>

## Webhookok létrehozása

Miután megvan a link, térj vissza a VivaWallet felületére, és kattints a Beállítások / API hozzáférés / Webhookok menüpontra.

Kattints a "**Webhook létrehozása"** linkre, és másold be a linket, amit iPanelen generáltunk.

Kattints az "**Aktív"** négyzetre, majd az Esemény típusnál válaszd ki: "**Tranzakció fizetés létrehozva**".

<figure><img src="../../.gitbook/assets/online-payment-viva-setup2.gif" alt=""><figcaption></figcaption></figure>

Végezd el újra a fentieket, azzal a különbséggel, hogy "**Tranzakció Befoglalása Létrehozva"** legyen kiválasztva Eseményként.

