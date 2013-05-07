
Watson
================================================================================

stellt eine globale Suche bereit an der sich andere AddOns andocken können.

Zum Bspl. dockt sich das **[watson_core](https://github.com/tbaddade/redaxo_watson/blob/master/README.md#watson_core)** Plugin mit einer Artikel-, Modul- und Templatesuche an.



Voraussetzungen
--------------------------------------------------------------------------------

* **REDAXO** 4.5
* **PHP:** 5.3



Installation
--------------------------------------------------------------------------------

* Ordner **redaxo_watson** in **watson** umbennen
* AddOn installieren und aktivieren
* Plugins installieren und aktivieren




Hotkeys
--------------------------------------------------------------------------------


### Watson öffnen:

* **ctrl + space** (um im Firefox das Contextmenü zu vermeiden, **ctrl + alt + space** drücken)
* **ctrl + alt + space**
* **ctrl + cmd + space**


### Quick look:

* **rechter Cursor**



Keywords
--------------------------------------------------------------------------------

Sind Keywords registriert, wird die Suche entsprechend eingegrenzt.

Gibt man ein Keyword und nachfolgend ein **+** ein, gelangt man in den Add-Modus der angegebenen Url.



Plugins
--------------------------------------------------------------------------------

### watson_core

#### Suchen

* Artikel (Keywords: a, c); um eine(n) Kategorie/Arikel anzulegen, muss man sich in der Struktur befinden
* Module (Keyword: m)
* Templates (Keyword: t)
* Benutzer (Keyword: u)


#### Kommandos

* start :: zur Startseite im Backend
* home :: zur Startseite im Frontend
* logout :: REDAXO logout



### watson_calculator

Ein einfacher Rechner (Keyword: =)

#### Konstanten

* Pi (Kreiszahl π), 3.141592653589793
* G (Gravitationskonstante), 6.67384E-11

#### Beispiele

| Eingabe                   | Ergebnis      |
|:--------------------------|--------------:|
| 2+4                       | 6             |
| 2+4*6                     | 26            |
| 2+4*6/8                   | 5             |
| 19% von 238               | 38            |
| Pi*2                      | 6,28318530718 |
| G*5.9736E+24/6.371E+6^2   | 9,82192737896 |


Screenshots
--------------------------------------------------------------------------------

### Watson
![Watson](http://blumbeet.com/screens/github/watson/2013-04-22-14-01-49.png)

### Quick look
![Watson](http://blumbeet.com/screens/github/watson/2013-04-22-14-03-23.png)
