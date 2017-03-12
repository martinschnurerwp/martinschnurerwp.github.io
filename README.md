# Zadanie 1

## Plugin

Webové sídlo obsahuje plugin pre predpoveď času potrebného na prečítanie daného článku. Tento plugin funguje len na lokálnej verzii.

## Lokálna inštalácia
- sudo gem install liquid_reading_time
- bundle install
- sudo jekyll serve

## Požiadavky:
 - aspoň 5 premenných, rôzne premenné sú použité v "config.yml" a taktiež, premenné sú použité v postoch
 - kolekcie alebo dátové - použité na školy v živote + kategórie vo filtry
 - aspoň 5 filtrov alebo tagov:
    - T : FOR použité v passion na generovanie obrázkov z priečinka
    - T : IF použité pri "contain" path pri generovani obrazkov passion z priečinka
    - T : použitie načitania obrazkov cez []() na mnohych miestach
    - F : použité v postoch na parsnutie času vytvorenia članku
    - F : použité spolu s pluginom POST layoute pre vypisovanie, kolko bude trvať čitanie članku
  - použitý plugin: reading_time na predikciu času potrebného na prečitanie článku v blogu (layout post)
