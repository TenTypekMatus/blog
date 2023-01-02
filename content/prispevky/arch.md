---
title: "Arch Linux - distro review"
date: 2022-12-28T19:12:11+01:00
draft: false
author: "Matúš Maštena"
---

Ako asi (ne) viete, ja mám veľmi rád distrohopovanie. Je to aktivita, keď striedam viacero distribúcií, často aj v jeden deň. A vždy sa snažím túto aktivitu zastaviť. Prečo? Lebo je to prosté zlé. Je to to isté, ako keby ste húlili, len pri tom navyše strácate svoje dáta. Ale rozhodol som sa s tým skončiť. A to tak, že mojou ****„poslednou“**** distribúciou bude Arch Linux.

# Inštalácia

Arch sa v novších verziách inštaluje pomerne jednoducho. Nové snapshoty ISO „Archu“ majú inštalačný program, ktorý sa volá Archinstall. Keď sa nabootujete do Arch Linuxu, tak sa Vám zobrazí prostý príkazový riadok, čo je inak ``zsh``. Potom sa treba pripojiť k internetu, ale to bude trápiť len tých, ktorí ho chcú nainštalovať na notebooku/majú Wi-Fi kartu. A to sa dá urobiť následovné:

1. Napíšte ``iwctl``.
2. Potom napíšte ``station device list``.
3. Potom napíšte ``station <zariadenie, ktoré sa zobrazí, keď napíšete predchádzajúci príkaz> get-networks``. 
4. Potom napíšte ``station <zariadenie, ktoré sa zobrazí, keď napíšete predchádzajúci príkaz> connect <názov Wi-Fi, ku ktorej sa chcete pripojiť>``.
    - Ak tá Wi-Fi má heslo, tak sa Vám zobrazí pole, kde sa Vám síce nebudú zobrazovať hviezdičky, ale tam budete musieť zadať to heslo.

No a teraz môžete napísať príkaz ``archinstall``, potom chvíľku počkať a voilá, môžeme ísť inštalovať
## Jazyk
Po tom, čo sa vám načíta inštalátor, sa ocitnete v prehľadnom prostredií, kde si môžete nakonfigurovať jazyk, disky a zopár ďaľších vecí. My sa ale v tomto odseku povenujeme tomu, ako si zvoliť jazyk. Takže, poďme na to. 

1. Prejdite šípkami na možnosť ``Locale``, čo znamená jazyk. 
2. Keď stlačíte Enter, tak sa vám otvorí obrovský zoznam tzv. unixových jazykových kódov.
    - Sú to kódy pre jazyky, ktoré používa logicky každý unixový/„Unix-like“
3. Stlačte lomítko, ktoré je na klávesnici pri ľavom Shifte, pričom kód pre slovenčinu je ``sk_SK``. Napíšte tam napr. kód pre slovenčinu, pričom kódy pre ostatné jazyky som uviedol dole.
    > Pre iné jazyky je ten kód odlišný. Napríklad Česi majú kód ``cz_CS``, pričom to ``CS`` je vlastne jazyková mutácia. Alebo ``en_US``, čo je vlastne americká angličtina, ktorá sa líši od tej britskej, ktorá má kód ``en_GB``.
4. Keď prejdete na požadovaný jazyk tak stlačte Enter.
Hotovo, máte zvolený jazyk
## Disky
Keď si zvolíte jazyk, tak si musíte zvoliť disk(y), na ktoré chcete nainštalovať Arch. Urobíte to tak, že pôjdete šípkami na možnosť ``Drive(s)`` a stlačíte Enter. 