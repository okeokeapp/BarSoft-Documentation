---
description: A nyomtatók beállítása távolról
---

# 🖨️ Nyomtatók

Van lehetőség arra, hogy távolról is beállítsd a nyomtatókat abban az esetben, ha hálózatos nyomtatókról beszélünk.

## **Nyomtatók típusai:**

{% tabs %}
{% tab title="Hálózatos nyomtatók" %}
A hálózatos nyomtatók a belső hálózaton keresztül kommunikálnak a POS eszközzel.

Ebben az esetben a hálózat routerén fixálni kell a nyomtató IP címét (amit általában kikapcsolt állapotban, bekapcsolás során a feed gomb hosszan megnyomásával tudsz megtudni).
{% endtab %}

{% tab title="USB / COM nyomtatók" %}
USB kábeles vagy COM portos nyomtatók esetében direkt összekötésről beszélünk, és csak az adott eszköz fér hozzá.
{% endtab %}
{% endtabs %}

## Nyomtató konfigurálása

Nyomtató létrehozásához kattints az **Új létrehozása** gombra.

{% hint style="danger" %}
FONTOS!

CSAK IP-S NYOMTATÓT ÁLLÍTS BE IPANELEN, a többi mód előre beállítása nem ajánlott, hiszen eszközspecifikusak.
{% endhint %}

A felugró menüben az alábbiakat tudod beállítani:

* Engedélyezés
* Rendelés nyomtatása
* Név, lokáció
* Nyomtató PROTOKOLL típusa
* Max karakter egy sorban (nyomtató papír szélességtől függően)
* Kommunikáció típusa (ez eszköztől függő)
* Port: 9100 (általában ez az érték, de nyomtató típusa válogatja)
* Kommunikációs útvonal (a nyomtató IP címe)
* Pultok

A <mark style="color:blue;">**Létrehozás**</mark> gombra kattintva meg fog jelenni a nyomtató a POS nyomtató beállítások "Megosztott nyomtatók" menüpontjában.

