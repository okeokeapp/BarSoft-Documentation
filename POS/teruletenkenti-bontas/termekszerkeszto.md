# 🖋️ Termékszerkesztő

A BarSoft rendszerében a Katalógus (menü) Termék kategóriákból, Termékekből és Módosítókból épül fel.

A POS felületén nem lehet szerkeszteni ezeket, csak a termékek és a módosítók láthatóságát. Ez a láthatóság befolyásolni fogja mely termékek és módosítók fognak megjelenni a BrandApp-on és a KIOSK-on.

{% hint style="info" %}
Amennyiben az üzletben már nem elérhető egy termék ideiglenesen, itt tudjuk szabályozni, hogy a vendégek mit tudnak rendelni.

Például: Elfogyott a forrócsoki, ezért a láthatóságot kikapcsoljuk a POS-on, így azok a vendégek, akik ezután lépnek a KIOSK-hoz, vagy nyitják meg a BrandApp-ot, már nem fogják látni a forrócsoki terméket.
{% endhint %}

{% hint style="warning" %}
**FIGYELEM!**

Ahhoz, hogy POS-on is lehessen szerkeszteni a menüt, megfelelő jogosultsággal kell rendelkezned!
{% endhint %}

A POS -on a bal oldali menüsoron a "Menü szerkesztő" ceruza gombra kattintva tudjuk előhozni a menüpontot.

## A menüpont felépítése

Bal oldalon találhatjuk a Váltás módosítókra gombot, a kategóriáinkat, középen a termékeket, jobb oldalon pedig egy linket, ami elvisz minket az iPanel V2 termék szerkesztő menüpontjába.

## Láthatóságok szerkesztése

Csak válasszuk ki a terméket, amelyiknek a láthatóságát szabályozni szeretnénk, majd a megfelelő termék melletti szem ikon kiválasztásával tudjuk eltüntetni, illetve megjeleníteni az adott méretet a termékhez.

Amennyiben rendelkezünk Fruitsys integrációval, viszont az adott termék nincs összekötve, tehát nincs megadva ExtID, ezt itt jelezzük.

A Váltás módosítókra gomb megnyomásával eljutunk a módosító láthatóság szerkesztéséhez, itt elég egy szimpla kattintással kiválasztani azt a módosítót, amelyiket szeretnénk eltüntetni vagy megjeleníteni.

Ahogy a termékeknél is, úgy a módosítóknál is szem ikonnal mutatjuk a láthatóságot. Nyitott szem jelzi a látható elemeket, csukott szem pedig a rejtetteket.

A termékekre vonatkozó többi szerkesztési opciót az iPanel felületen találod, természetesen erről is készítettünk leírást, amit [itt ](https://barsoft.gitbook.io/ipanel/ipanel-menuepontok/katalogus)érhetsz el
