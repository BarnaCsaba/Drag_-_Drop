# Metamorfózis

## Történet

Van egy remek ötletünk: a programozás nagyon szórakoztató, de békákat és pillangókat tenyészteni talán még jobb! :)

A döntés megszületett: egy új üzleti vonalat indítunk, tele menő békákkal és gyönyörű pillangókkal. Viszont nem vagyunk biztosak a folyamat lépéseiben, ezért **szükségünk van a segítségedre**. Készítenél egy kis játékot, amellyel gyakorolhatjuk ezeknek az állatoknak a helyes átalakulási sorrendjét?

Van néhány kártyánk, mindegyik a metamorfózis egy-egy állomását mutatja. Drag and drop játékot szeretnénk belőlük építeni, hogy begyakoroljuk a helyes sorrendet.


## Feladatok

1. **Minden kártya elemet lehessen egérrel húzni.**
    - Az összes `.card` elem felvehető és mozgatható.
    - Húzás közben az eredeti helyén maradó elem vizuálisan különbözzön.

2. **A felvett kártyákat le lehessen dobni a metamorfózis lépésekre.**
    - A kártyák dobhatók a `.metamorphosis-slots` elemen belüli helyekre.
    - Minden `.card-slot` aktív és vizuálisan kiemelt, amikor kártyát fogsz.
    - Amikor egy drop zóna fölé viszed a kártyát, a kiemelés jelezze, hová fog érkezni.

3. **A kártyákat vissza is kell tudni dobni a `.mixed-cards` konténerbe.**
    - Bármelyik kártya visszatehető a `.mixed-cards` területre.
    - A konténer húzás közben aktív és kiemelt.
    - A konténer fölött tartva változzon a kiemelés, hogy hol fog landolni a kártya.

4. **Csak a megfelelő helyekre lehessen lerakni a kártyákat.**
    - A béka/pillangó konténerek csak a saját kártyáikat fogadják.
    - A `.mixed-cards` konténer bármilyen kártyát visszavesz.
    - A drop zónák vizuálisan jelezzék, ha egy kártya lerakható oda.
    - Egy `.card-slot` csak egy kártyát tartalmazhat.
    - Csak `.card` elemek váltsák ki a drop zónákat (pl. ha egy fájlt húzol a böngésző fölé, ne történjen semmi).

5. **Nyerni kell, ha minden kártya a helyes sorrendben van.**
    - Amikor az utolsó darab is a helyére kerül, és minden sorrend stimmel, kapjunk visszajelzést a győzelemről.
    - Mutass be valami látványos CSS-trükköt! :)

6. **[OPCIONÁLIS]** Az alapverzióban kilenc drop zóna van. Oldd meg a feladatot külön `.card-slot` elemek nélkül, hogy a kártyák közvetlenül a `.metamorphosis-slots` területre kerüljenek és ott rendezhetők legyenek.
    - Csak három drop zóna van (béka, pillangó, pakli).
    - A kártyák rendezhetők a metamorfózis zónákon belül.


## Háttéranyagok

- <i class="far fa-exclamation"></i> [MDN HTML Drag&Drop API](https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API) – külön oldalai vannak az eseményeknek és az event handler-eknek
- <i class="far fa-exclamation"></i> [MDN Drag műveletek](https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API/Drag_operations)
- <i class="far fa-exclamation"></i> [Hogyan futtass helyi HTTP szervert](project/curriculum/materials/pages/tools/serve-files.md)
- <i class="far fa-exclamation"></i> [Alapos vanilla JS Drag&Drop példa](https://codepen.io/szrudi/pen/gOpLyKd)
- [Vanilla JS Drag&Drop tutorial](https://code-boxx.com/javascript-drag-and-drop/)
- [Dragula JS Drag&Drop library](https://bevacqua.github.io/dragula)
- [Interact.js Drag&Drop library](https://interactjs.io/)
- <i class="far fa-book-open"></i> [CSS Flexbox összefoglaló](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

