# Koenigsberger Strasse 10, Welzheim, Wohnung Nr. 20 (Fassung Anna Dogic)

Stand: 07.10.2026, Fassung per Du, Kaufpreis 140.000 EUR inkl. Tiefgaragenstellplatz

## Was in diesem Ordner liegt

    index.html          das Expose, alle Fotos sind darin enthalten
    unterlagen/         20 Dokumente, ueber die Downloadkarten verlinkt

Die Fotos stecken direkt in der index.html. Die Datei funktioniert allein,
auch per Doppelklick von der Festplatte und auch, wenn du sie per Mail oder
WhatsApp weitergibst. Ein Bilderordner ist deshalb nicht noetig.

Der Ordner "unterlagen" muss neben der index.html liegen, sonst laden die
Dokumente nicht.

## Hochladen

Ein eigenes Repository fuer diese Wohnung anlegen. Dann "Add file",
danach "Upload files", und beides zusammen hineinziehen:

    index.html
    unterlagen        (der ganze Ordner)

Den Ordner "Welzheim-Whg-20" selbst nicht hochladen, nur seinen Inhalt.
Die index.html muss im Repository ganz oben liegen.

## Pages einschalten

Settings, dann Pages. Bei Source "Deploy from a branch" waehlen,
Branch `main`, Ordner `/ (root)`. Speichern. Der erste Aufbau dauert
ein bis zwei Minuten.

## Danach: Link im Finanzierungsbutton eintragen

In der index.html steht im Abschnitt Finanzierung diese Zeile:

    var EXPOSE_URL = "";

Dort die fertige Adresse eintragen, zum Beispiel

    var EXPOSE_URL = "https://wuerttembergerwohnkonzepte.github.io/Welzheim-Wohnung_20/";

Bleibt das Feld leer, steht im Mailtext an die Moeglichmacher ein
Platzhalter statt des Links. Alles andere funktioniert trotzdem.

## Diese Dokumente sind bewusst NICHT dabei

    Grundbuchauszug Wohnung
    Grundbuchauszug Tiefgarage
    Reservierungsvereinbarung
    Modernisierungsaufstellung

Die beiden Grundbuchauszuege enthalten personenbezogene Daten. Auf
GitHub Pages ist jede Datei im Repository oeffentlich abrufbar, auch
wenn sie auf der Seite nicht verlinkt ist. Im Expose steht, dass
Grundbuchauszuege, Restnutzungsdauergutachten und Mietvertrag bei
ernsthaftem Kaufinteresse nachgereicht werden. Die
Reservierungsvereinbarung ist ein internes Dokument, die
Modernisierungsaufstellung hast du selbst herausgenommen.

Lade diese vier Dateien also bitte nicht mit hoch.

## Rechenstand, nachgeprueft (07.10.2026)

    Kaufpreis inkl. TG-Stellplatz      140.000 EUR
    davon Wohnung                      128.000 EUR
    davon TG-Stellplatz                 12.000 EUR
    Erwerbsnebenkosten 7 %               9.800 EUR
      (1,5 % Notar, 0,5 % Grundbuch, 5 % Grunderwerbsteuer)
    Gesamtinvestition                  149.800 EUR
    Gebaeudeanteil 83,6 %, Boden 16,4 %
    Abschreibungsbasis                 125.233 EUR
    Abschreibung pro Jahr, 35 J.         3.578,08 EUR  (2,86 %)

    Kaltmiete Wohnung                      552,00 EUR
    Miete TG-Stellplatz                     55,00 EUR
    Kaltmiete zusammen                     607,00 EUR
    Miete je Quadratmeter                   12,93 EUR
    Kaufpreis je Quadratmeter            2.998 EUR  (ohne Stellplatz)

    Bruttomietrendite Wohnung                5,18 %
    Bruttomietrendite gesamt                 5,20 %
    Bruttomietrendite Stellplatz             5,50 %
    Kaufpreisfaktor gesamt                  19,2

    Monatsrechnung, Startwerte im Rechner:
    9.800 EUR Eigenkapital (deckt die Nebenkosten), Darlehen 140.000 EUR,
    Sollzins 5,20 %, Tilgung 1,00 %, Steuersatz 42 %

    Kaltmiete inkl. Stellplatz            607,00
    Hausgeld nicht umlegbar               -40,37
    Erhaltungsruecklage                   -58,54
    Zinsen                               -606,67
    Tilgung                              -116,67
    Cashflow vor Steuern                 -215,24
    Steuererstattung                     +142,05
    Cashflow nach Steuern                 -73,20

    Ergebnis nach zehn Jahren, Startwerte, Wertsteigerung 2,3 %:
    Ergebnis gesamt                      34.822 EUR
    davon Gewinn bei Verkauf             44.257 EUR
    davon Cashflow nach Steuern          -9.435 EUR
    Steuerersparnis zehn Jahre           13.651 EUR
    Eigenkapitalrendite pro Jahr             35,5 %
    Cashflow pro Monat, erstes Jahr         -74 EUR

## Sondereigentumsverwaltung (optional, im Rechner zubuchbar)

    Pauschale                            45,00 EUR im Monat, nicht mietabhaengig
    Cashflow vor Steuern mit SEV       -260,24 EUR  (statt -215,24)
    Steuererstattung mit SEV           +160,95 EUR  (statt +142,05)
    Cashflow nach Steuern mit SEV       -99,30 EUR  (statt -73,20)

Die Pauschale ist als Werbungskosten angesetzt und bleibt ueber die zehn
Jahre unveraendert, sie waechst nicht mit der Miete.

Hinweis: Der Wert "Cashflow pro Monat, erstes Jahr" (-74 EUR) ist der
Durchschnitt ueber zwoelf Monate. Die Monatsrechnung (-73,20 EUR) zeigt
den ersten Monat. Der kleine Unterschied entsteht, weil der Zinsanteil
mit jeder Rate sinkt und die Steuererstattung entsprechend mit.

## Aufbau des Exposes

    01 Lage
    02 Wohnung und Renovierung (inkl. Bilder und Grundriss)
    03 Das Haus
    04 Verwaltung
    05 Deine Zahlen (Rechner)
    06 Die Rechnung (Monatsrechnung und Cashflow ueber zehn Jahre)
    07 Unterlagen
    08 Finanzierung
    09 Die naechsten Schritte
    10 Kontakt

## Aenderungen in dieser Fassung (07.10.2026)

- Abschnitte "Die Wohnung" und "Renovierung" zu Abschnitt 02
  "Wohnung und Renovierung" zusammengefasst. Jede Angabe steht nur noch
  einmal, das doppelte Badfoto ist entfallen
- Rechner "Ihre Zahlen": links die Eingaben, darunter der Button
  "Ergebnis anzeigen". Erst nach dem Klick erscheinen rechts Ergebnis
  nach zehn Jahren, Gewinn, Cashflow, Diagramm, Fun Fact, Cashflow pro
  Monat, Steuerersparnis und Eigenkapitalrendite. Jede Aenderung an den
  Eingaben blendet das Ergebnis wieder aus, bis erneut geklickt wird
- Balkendiagramm unter "Cashflow ueber zehn Jahre" entfernt, die Tabelle
  bleibt
- "Prozent" und "Euro" im Expose durchgehend als Zeichen
- Woerter aus "laufen" ersetzt, Navigation heisst "Schritte"
- Gegenueberstellungen nach dem Muster "nicht X, sondern Y" umformuliert
- Startwerte der Monatsrechnung im HTML auf den aktuellen Rechenstand
  gebracht (-215,24 / +142,05 / -73,20). Der Rechner hat diese Werte
  beim Laden ohnehin neu berechnet, die alten Zahlen standen nur noch
  als Platzhalter im Quelltext
- LIESMICH auf Kaufpreis 140.000 EUR aktualisiert, veraltete Rechenstaende
  mit 155.000 EUR entfernt

## Aenderungen in der Du-Fassung (07.10.2026)

- Das gesamte Expose spricht den Leser per Du an, auch Rechner,
  Hinweisfelder und Rechtstexte. Die vorbereiteten Mails an die
  Moeglichmacher und an Dorothee Hahn bleiben beim Sie, weil der
  Kaufinteressent sie selbst verschickt
- Besichtigung: "Einen Besichtigungstermin stimmen wir gern mit dir ab.
  Ruf einfach an." Der doppelte Hinweis im Abschnitt Schritte ist entfallen
- Bilder der Wohnung: der Flur steht jetzt an erster Stelle
- "Was noch offen ist" in kleinerer Schrift, ergaenzt um den
  Kostenanteil: 13,8/1.000 Miteigentumsanteile, also 1,38 %, je
  10.000 EUR Gesamtkosten 138 EUR
- Kontakt: "Ueber 83 Wohnungen habe ich dabei selbst gekauft"
  (vorher 79 Einheiten)
- Darstellung auf schmalen Handys (ab 320 px Breite) korrigiert: die
  Seite liess sich bisher seitlich verschieben, weil lange Woerter im
  Kasten "Konditionen" der Verwaltung nicht umbrachen. Die Korrektur
  greift nur auf schmalen Bildschirmen, damit die Kontaktkarte auf dem
  Desktop (900 bis 1200 px) ihre volle Breite behaelt

## Fassung mit Anna als Ansprechpartnerin (07.10.2026)

- Kontaktkarte, WhatsApp, E-Mail, Telefon und Fusszeile mit den Daten von
  Anna Dogic: 0152 0849 8879, a.dogic@wuerttemberger-wohnkonzepte.de
- WhatsApp geht an dieselbe Nummer wie das Telefon
- Die Kopie der Finanzierungsanfrage an die Moeglichmacher geht an Anna
- Hintergrund-Absatz von Anna, Foto aus dem Screenshot uebernommen
  (geringe Aufloesung, bei Gelegenheit durch das Originalfoto ersetzen)
- Im Impressum bleiben Marco Hans und Dorothee Hahn als Geschaeftsfuehrer
- Fuer GitHub ein eigenes Repository anlegen, zum Beispiel
  "Welzheim-Wohnung_20_Anna", und EXPOSE_URL entsprechend eintragen
