---
title: "Ako som bol na pár dní na Windowse"
date: 2022-12-13T18:06:57+01:00
draft: false
author: "Matúš Maštena"
showToc: true
---

Windows - nočná mora pre tých, ktorí majú radi súkromie. Ale zároveň je naň kopa super softvéru, len ten paradox je, že väčšina tohto softvéru je proprietárna. Ale zas dnes je všetko napísané alebo sa píše pre Windows. Dnes Vám poviem, ako som prežil tri dni bez toho, aby som bol na nejakej linuxovej distribúcií.
# Inštálácia
## Je to ťažké z prostredia linuxových distribúcií
Toto bol trochu problém, lebo Rufus nie je na linuxových distribúciách, no tak som vyskúšal [Ventoy](https://ventoy.net). Keď som si naformátoval USBčko Ventoyom a nahral som naň ISO súbor Windowsu, tak som reštartoval laptop a nabootoval som do Ventoyu a zvolil som ISO Windowsu a dal som možnosť ```Boot in normal mode```. Počkal som chvíľku, ale nič sa nedialo. Reštartoval som počítač a zase som spravil to isté, čo som urobil predtým, ale tentokrát som zvolil možnosť ```Boot in wimboot mode```. Konečne sa začalo niečo diať. Prešiel som nastavením jazyka a klávesnice a potom to preskočilo krok s aktiváciou a inštalátor išiel priamo na výber ovládača pre disk. Bolo to divné, lebo ten notebook mal v sebe SSD a naposledy, keď som inštaloval Windows, tak sa mi tam ten disk zjavil. No tak som reštartoval počítač, nainštaloval som [WoeUSB](https://github.com/WoeUSB/WoeUSB), prečítal som si ich manuálovú stránku a nahral som ISO Windowsu na USB kľúč, reštartoval som počítač, ale tentokrát to už bolo lepšie.
## Teraz naozaj - inštalácia Windows
Windows sa inštaluje pomerne jednoducho, ba dokonca nemusíte zadávať ani Product Key, i keď je pravda, že ja som si ho aktivoval neskôr pomocou tohoto skriptu, [ktorý nájdete tu](https://github.com/massgravel/Microsoft-Activation-Scripts). Ale poďme 