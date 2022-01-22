
Remove German Gender Language (RGGL)
------------------------------------

v5.5 (22.01.2022)

Autor: Motsi Weech (motsi.weech ät protonmail.com)

Kleines Add-On für den Firefox.
Lizenz: GNU GENERAL PUBLIC LICENSE Version 3

Das Add-On entfernt folgendes:
* Gender-Sternchen (Anwender*innen)
* Gender-Doppelpunkt (Anwender:innen)
* Binnenmajuskel (AnwenderInnen)
* Gendergap (Anwender_innen)
* Schrägstrichlösung (Anwender/-innen)
* Klammerlösung (Anwender(innen))

Viele Spezialfälle werden berücksichtigt. Dadurch werden deutschsprachige Webseiten besser lesbar dargestellt. 

Bedienung:
In der Symbolleiste des Firefox erscheint ein neuer "Gender"-Knopf. Er wechselt die Farbe beim Klicken.
- schwarz: Gender-Konstruktionen werden gefiltert
- rot: Gender-Konstruktionmen werden gefiltert und die Änderungen farbig markiert
- x: Deaktiviert
- Der Knopf zeigt die Zahl der geänderten Elemente auf der aktuellen Webseite.
- In der Konsole (F12) lassen sich alle Änderungen im Detail nachvollziehen (Tipp: Filtern nach rggl).


Installation:
https://addons.mozilla.org/de/firefox/addon/remove-german-gender-language/


Warum dieses Add-On?

Einige deutschsprachige Medien haben sich für die Freigabe des sogenannten 'Genderns' unter ihren Autoren und Redakteuren entschieden. So haben Leser, die sich ein möglichst umfassendes Meinungsbild der Medienlandschaft verschaffen möchten, keine Chance mehr dem zu entgehen, es sei denn man beschränkt sich auf konservative und Boulevard-Zeitungen. Die Intensität des Genderns ist überall autorenabhängig.

Wenn Sie wertvolle Informationen und Meinungen nicht ignorieren wollen, gleichzeitig aber das sog. 'Gendern' als grobe Verunglimpfung der deutschen Sprache empfinden, dann verwenden Sie  dieses Add-On. Artikel werden lesbarer und inhaltlich deutlicher. Mehr als 95% der Korrekturen erfolgen grammatikalisch korrekt. In den übrigen Fällen sind die Änderungen weniger obtrusiv als die vormalige 'Gender'-Konstruktion (meist erfolgt eine irrtümliche Verschiebung vom Dativ zum Akkusativ).


Funktionsweise

Folgende 20 Regeln werden in diesem Add-On abgearbeitet:
1. Ersatz von Dem/der, er:sie, man*frau usw. durch das generische Maskulinum.
2. Singular: Lautverschiebung bei bestimmten Nomen (Bäuer*in => Bauer, Schwäger*in => Schwager).
3. Korrektur Nomen auf -erin/-erer (Veräußer*in => Veräußerer)
4. Korrektur Artikel und Fürwörter (ein*e => ein, jede*r => jeder)
5. Plural mit Binnen-'innen' (Freund*innenkreise => Freundeskreise)
6. Gruppen-N im Nominativ mit einigen Nomen (die Beamt*innen => die Beamten)
7. Anglizismen (Chef*innen => Chefs)
8. Dativ auf 'en' bei Wörtern, die nicht auf 'r' enden (den Therapeut*innen => den Therapeuten)
9. Dativ Spezialfälle auf 'en' bei Wörtern, die auf 'r' enden (den Autor*innen => den Autoren)
10. Akkusativ mit 'auf' bei Nomen, die auf 'r' enden (Angriffe auf Arbeiter*innen => Angriffe auf Arbeiter)
10. Dativ auf 'n' bei den übrigen Wörtern, die auf 'r' enden (den Arbeiter*innen => den Arbeitern)
11. Genitiv plural auf 'e' bei Nomen, die auf -eur,-pst,-bst,-pitän usw. enden (der Päpst*innen => der Päpste)
12. Genitiv plural auf 'en' bei übrigen Nomen (der Finn*innen => der Finnen)
13. Nominativ/Akkusativ plural auf 'e' bei Nomen auf -eur,-wält usw. (die Anwält*innen => die Anwälte)
14. Nominativ/Akkusativ plural auf 'en' bei Nomen auf -nom,-ürk usw. (die Türk*innen => die Türken)
15. Dativ/Akkusativ singular auf 'en' bei Nomen auf -log,-pert usw. (dem*der Astrolog*in => dem Astrologen)
16. Einzahl auf 'e' bei Nomen auf -gog,-log,-oss usw. (Genoss*in => Genosse)
17. Einzahl auf 'er' bei Nomen auf -amt,-ndt (Beamt*in => Beamter)
18. Einzahl auf 'r' bei Nomen auf -dnete,-wachsene (Erwachsene*r => Erwachsener)
19. Alle verbleibenden *innen und *in entfernen.
20. Korrekturen für unregelmäßige Formen (Israel*innen => Israelis, Juden/Jüdinnen => Juden)



Version History

5.5
- Das Add-On wird nur noch auf deutschsprachigen Webseiten aktiv.

5.4
- Ergänzt: Akkusative mit auf (Druck auf Politiker*innen, Wirkung auf Schüler*innen)
- Modus "Änderungen hervorheben": Viele farbige Leerzeichen beseitigt

5.3
- Korrektur: Ärzt*innen, Prinzess*innen, Närr*innen, ChefIn
- Ergänzt: Analphabet*innen

5.2
- Ergänzt: Tatar*innen, Athlet*innen, Vietnames*innen, Veteran*innen

5.1
- Ergänzt: seinem*ihrem
- Ungenutzte Berechtigungsanforderungen entfernt

5.0
- Ergänzt: Katholik*innen
- Trennzeichen · (Mittel-/Hochpunkt) ergänzt

4.9
- Ergänzt: Erb:innen
- Ergänzt: Beauftragte*r
- Ergänzt: Akkusativ LandrätInnen


4.8
- Ergänzt: Konfirmand*innen

4.7
- Bugfix: Nomen auf -erer im Genitiv Plural
- Ergänzt: -sophen (Philosophen, Antroposophen usw.)

4.6
- Bugfix: Nomen auf -erer im Modus 'Änderungen hervorheben'

4.5
- Ergänzt: Fütter*in => Fütterer

4.4
- Dokumentation / Readme überarbeitet

4.3
- Bugfix 'für'+Dativ

4.2
- Ergänzt: Kund*innen

4.1
- Ergänzt Sonderfall: "Angriffe auf Arbeiter*innen" (Nomen auf -r)
- Ergänzt Sonderfall: "Übergriffe auf Verteidiger*innen" (Nomen auf -r)

4.0
- Ergänzt: Erwachsene*r

3.9
- Ergänzt: Russ*innen
- Ergänzt: Köch*innen
- 

3.8
- Bugfix "machen Schülern"
- Ergänzt: Abgeordnete*r

3.7
- Dativ und Akkusativ singular ergänzt
- diverse Korrekturen

3.6
- Bugfix: Dativ Plural mit r am Ende und -en (Autor*innen => Autoren)

3.5
- Ergänzt: Geodäte, Architekten, Asiaten
- Bugfix: Dativkonstrukte mit pitän|tär|när|wält|dät
- Bugfix: den Muslime
- massiver Code cleanup

3.4
- Ergänzt: FreundinnenkreiseE

3.3
- Ergänzt: Schweden
- Ergänzt: ihre*n
- Bugfix: Gynäkolog

3.2
- Ergänzt: Anwälte, Funktionäre, Visionäre, Sekretäre
- Bugfix: Kosovaren

3.1
- Ergänzt: Chef*innen => Chefs
- Ergänzt: Kapitän*innen => Kapitäne

3.0
- Ergänzt: Kommilitonen, Zeugen, Kosovare
- Bugfix: Satzzeichen '?' verhinderte Korrektur
- Bugfix: erzählen Berufsanfänger
- Bugfix: Juden:Jüdinnen wurde zu Jüdinnen - versehentlich generisches Femininum benutzt ;)

2.9
- Ergänzt: Jüd*innen, Griech*innen
- Bugfix: Satzzeichen 'Doppelpunkt' verhinderte Korrektur
- Kompatibilität maximiert / weniger obtrusiv (Text-Nodes anstatt innerHTML)

2.8
- Ergänzt: Nomaden
- Bugfix: Franzosee
- Bugfix: LinkedIn

2.7
- Muslime, Kurden, Wölfinnen, Türken, Gefährten, Freund*innenkreis, 
- Irinnen, Afghaninnen, Ungarinnen, Kasachinnen, Kongolesinnen, Rumänen
- Sonderbehandlung taz: Vokale + Trema werden zu Umlauten konvertiert

2.6
- Performance verbessert
- Bugfix

2.5
- Sonderfälle ergänzt 
  (Wilderer, Zauberer, Plünderer, Bewunderer, Herausforderer, Hinderer, Plauderer, Meuterer, Veräußerer)
- Verbesserung bei weichen Trennstrichen (taz)
- farbliche Hervorhebung verbessert
- schönere Icons

2.4
- erste öffentliche Version

2.3
- Code aufgeräumt

2.2
- Kleinere Korrekturen

2.1
- Bessere Farben für Hervorhebung von Änderungen

2.0
- Button zeigt jetzt die Zahl der Änderungen mittels Badge
- Button schaltet zwischen drei Modi:
  - Filterung aktiv (Standard) => Symbol schwarz
  - Änderungen farbig hervorheben => Symbol rot
  - Deaktiviert => Symbol "ausge-X-t"

1.9
- Zahlwörter hinzughefügt (Mit 30.000 Einwohner*innen... => Mit 30.000 Einwohnern)

1.8
- Beamt*innen hinzugefügt
- Sonderfälle mit Umlaute in den weiblichen Formen
- Nachbarn hinzugefügt

1.7
- Vorfahr*innen/Nachfahr*innen hinzugefügt
- man/frau und frau:man
- Dativ + 'zufolge' hinzugefügt

1.6:
- weiche/bedingte Trennstriche verbessert
- Analyst*innen hinzugefügt

1.5:
- Zeitmessung hinzugefügt
- Konsolenausgabe farbig und auf das Wesentliche reduziert
- weiche/bedingte Trennstriche werden unterstützt

1.4:
- kleinere Fehler beseitigt
- Bäuer*innen werden unterstützt

1.3:
- Knopf hinzugefügt (tut aber noch nichts)
- diverse sprachliche Korrekturen
