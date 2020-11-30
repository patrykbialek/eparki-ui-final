# Nowa odsłona serwisu e-Parki

## Projekt UI

```
Aktualizacja: 30/11/2020 22:00<br>
Autor: Patryk Białek (patryk.b@me.com)
```

---
### Spis treści
1. [Wprowadzenie](#wprowadzenie)
1. [Czcionki (fonts)](#czcionki)
1. [Widoki (html)](#widoki)
1. [Style (styles)](#style)
1. [Obrazy i ikony (images)](#obrazy)
1. [Demo linki](#demo-linki)
1. [Bootstrap](Bootstrap)

---
&nbsp;

## Wprowadzenie
&nbsp;

**Co tutaj mamy:**
- Wizualizację wyprodukowaną z html + css + obrazy
- Statyczny kontent - nie ma tutaj pełnego flow (flow prezetowany jest na mokapach/prototypach)
- Wsparcie dużego ekranu desktop oraz mobilnego
Wsparcie przeglądarek Chrome, FireFox, MS Edge, MS InternetExplorer 11


***Czego tutaj nie ma:***

- Nie został ostylowany komponent Kalendarza. Aby to zrobić muszę mieć informację od developera jaka biblioteka do kalendarza będzie finalnie wykorzystana
- Opcja widoku mapy zawiera jedynie ostylowane PINy Parku (do nałożenia póżniej podczas implementacji biblioteki mapy)

&nbsp;

## Czcionki

1. Do treści została użyta czcionka `Lato` z biblioteki Google 
1. Wszystkie ikony zastosowane w UI zostały przekonwertowane do postaci `czcionki` z obrazu `svg` (folder `fonts` oraz plik `icon-fonts.css`)

&nbsp;

## Widoki

W katalogu `html` znajdują się wszystkie widoki w formacie `html`.

&nbsp;

## Style

W katalogu `styles` znajdują się pliki stylów:
- css oraz min.css - skompilowany plik `css`
- scss - nieskompilowane pliki developerskie

&nbsp;

## Obrazy

W katalogu `images` znajdują się obrazy wykorzystane w projekcie:
- icons - ikony, oraz przykładowa demo strona wyświetlająca kodowanie czcionek ikon
- logo - obrazki logo parków
- narwianski - zestaw faviconów
- reszta obrazów

&nbsp;

## Demo linki
### #1 Strona główna e-Parki

- widok listy
- widok mapy
- filtry atrakcje
- filtry rejon Polski
- menu 'Wybór języka' 

https://patrykbialek.github.io/eparki-ui-glowna/

```
Ważne: jak wspominałem wcześniej, mapa Polski jest poglądowa, docelowo nasza rekomendacja jest taka aby zastosować mapę jak na głównej stronie PN (https://zpppn.pl/parki-narodowe)
```

&nbsp;

### #2 Strona Parku - turysta

- widok listy biletów
- widok listy filtrów (wraz z ukrywaniem/odkrywaniem)
- pozycje nagłówka

https://patrykbialek.github.io/eparki-ui-turysta

&nbsp;

### #3 Strona Parku - kasjer

- widok listy biletów
- widok podglądu koszyka (prawy kontent)

https://patrykbialek.github.io/eparki-ui-kasjer

&nbsp;

### #4 Okienka modalne (dialogowe)

- wszystkie okienka modalne zebrane w jednym miejscu

https://patrykbialek.github.io/eparki-ui-modal/

&nbsp;

## Bootstrap

W projekcie została wykorzystana biblioteka `Bootstrap` w zakresie:
 - layoutu (grid)
 - menu (nav)
 - przyciski (button)
 - listy
 - modal (okienka dialogowe)
