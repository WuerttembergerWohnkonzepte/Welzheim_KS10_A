# Koenigsberger Strasse 10, Welzheim, Wohnung Nr. 20

## Was in diesem Ordner liegt

    index.html          das Expose, alle Fotos sind darin enthalten
    unterlagen/         16 Dokumente, ueber die Downloadkarten verlinkt

Die Fotos stecken diesmal direkt in der index.html. Die Datei laeuft
allein, auch per Doppelklick von der Festplatte und auch, wenn du sie
per Mail oder WhatsApp weitergibst. Ein Bilderordner ist nicht mehr
noetig, deshalb koennen die Fotos auch nicht mehr schwarz bleiben.

Der Ordner "unterlagen" muss dagegen weiter danebenliegen, sonst
laden die Dokumente nicht.

## Hochladen

Ein eigenes Repository fuer diese Wohnung anlegen. Dann "Add file",
danach "Upload files", und beides zusammen hineinziehen:

    index.html
    unterlagen        (der ganze Ordner)

Nicht den Ordner "Welzheim-Whg-20" hochladen, sondern seinen Inhalt.
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

## Was in dieser Fassung geaendert wurde

- Fotos eingebettet, neues Garderobenbild mit den richtigen Fenstern
- Ueberschrift "Renoviert und in Vermietung, inklusive Einbaukueche",
  darunter Einzimmerwohnung mit Balkon und Tiefgaragenstellplatz
- Miete nicht mehr als Kalkulation, sondern als angesetzte Miete in
  der eingeleiteten Neuvermietung, mit den ueber 25 Anfragen
- Lage um Entfernungen, S-Bahn und Arbeitgeber der Region erweitert
- Renovierung deutlich gekuerzt, ohne Kostenaufstellung, mit dem
  Hinweis auf jederzeit moegliche Besichtigung
- "Das Haus" gekuerzt, Schimmelthema entfernt, Tiefgarage sachlich
  eingeordnet, keine Wiederholung der Daten aus Abschnitt 02
- Sondereigentumsverwaltung komplett entfernt, auch aus Rechner,
  Monatsrechnung und Rechtstexten
- Modernisierungsaufstellung aus den Unterlagen entfernt
- Rechner mit Indexmiete: Anpassung alle drei Jahre

## Rechenstand, nachgeprueft

    Erwerbsnebenkosten 6,5 %        10.075 EUR
    Gesamtinvestition              165.075 EUR
    Abschreibungsbasis bei 84 %    138.663 EUR
    Abschreibung pro Jahr, 35 J.     3.961,80 EUR  (2,86 %)
    Rendite Wohnung                      4,84 %
    Rendite gesamt                       4,70 %
    Rendite Stellplatz                   3,67 %
    Kaufpreisfaktor                     21,3
    Miete je Quadratmeter               12,93 EUR
    Kaufpreis je Quadratmeter        3.208 EUR

    Monatsrechnung bei 10.075 EUR Eigenkapital, 4,70 %, 1,00 %, 42 %
    Zinsen 607,08  Tilgung 129,17  Abschreibung 330,15
    Cashflow vor Steuern  -211,10
    Steuererstattung      +154,24
    Cashflow nach Steuern  -56,86

## Aenderungen in dieser Fassung (02.09.)

- Abschnitt 02: Raeume, Kueche, Bad, Balkon, Abstellraum, Mietanpassung,
  beide Bruttomietrenditen, Kaufpreisfaktor und "Uebergang moeglich" aus
  der Faktenliste entfernt, Baujahr weiter nach oben
- Alle Textbausteine im Blocksatz, mit Silbentrennung, und ueber die
  volle Spaltenbreite. Die Fussnote unter dem Rechner ist nicht mehr
  zweispaltig
- Bildhinweis "Alle Bilder sind Fotografien des Objekts ..." steht jetzt
  direkt unter den Wohnungsbildern, einzeilig
- Grundriss-Ueberschrift: "Optimal geschnittener Grundriss fuer eine
  hohe Mietnachfrage"
- Abschnitt 04: aktuell stehen keine Sanierungen an, Hinweis auf die
  Protokolle 2023 bis 2025 im Downloadbereich
- Diagramme: linke Achse verbreitert, "Euro" ueberdeckt die Zahlen nicht mehr
- Cashflow-Aufstellung steht jetzt unter der Monatsrechnung in
  Abschnitt 07, nicht mehr in Abschnitt 06
- Ablauf: Schritt 04 mit Hinweis auf das eigene Nachrechnen im Rechner,
  Schritt 05 heisst "Reservierungsvereinbarung"
- Neuer Abschnitt 05 Verwaltung: Sondereigentumsverwaltung als Pauschale
  von 45 EUR im Monat, zubuchbar im Rechner. Dadurch verschieben sich die
  Abschnittsnummern 05 bis 10 auf 06 bis 11
- Semikolons aus den Exposetexten entfernt

## Rechenstand Sondereigentumsverwaltung

    Pauschale                        45,00 EUR im Monat, nicht mietabhaengig
    Cashflow vor Steuern mit SEV   -256,10 EUR  (statt -211,10)
    Cashflow nach Steuern mit SEV   -82,96 EUR  (statt -56,86)

    Die Pauschale ist als Werbungskosten angesetzt und bleibt ueber die
    zehn Jahre unveraendert, sie waechst nicht mit der Miete.
