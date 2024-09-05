# CNN Háziállat Képek Klasszifikálására
Ez a projekt egy mély konvolúciós neurális háló (CNN) alkalmazását foglalja magában háziállatfajták képeinek osztályozására.
A modell alapja egy előre betanított MobileNet v2 háló, amely az ImageNet adatbázison lett tanítva.
A háló architektúráját módosítottuk a specifikus feladathoz, majd finomhangolással optimalizáltuk a teljesítményt.

Mivel kevés címkézett kép áll rendelkezésre, adat-augmentációs technikák kerültek alkalmazásra a tanítás során.
A képeket előfeldolgozásnak vetjük alá, és szegmentációs címkéket használunk a fontos objektumok (például háziállatok) azonosítására és kivágására.
