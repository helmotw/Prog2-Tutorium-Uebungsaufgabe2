# Übung 2: Einblick in die OOP

In dieser Übung wollen wir die 2. Aufgabe des Uebungsblatt 4 erweitern.

Unser Kunde moechte eine Verwaltungsapplikation für CSV-Dateien, also so zu sagen was wir in der 2. Aufgabe implemetiert haben.
Da aber nicht jeder aus der Buchhaltung Java-Code lesen kann, müssen wir unser Programm in Geschaeftslogik und Benutzerschnittstelle unterteilen.
Zusaetztlich moechte unser Kunde weitere Praemienaufschlaege bei gewissen bedingungen fordern(siehe Javadoc in Jahreseinnahmenrechner).
Heute wollen wir uns aber erst das Herzstueck, die GL anschauen.

Unsere GL besteht aus diesen Akteuren:
* ```Kunde```: Klasse fuer einen Kundendatensatz.
* ```KundenDB```: Klasse fuer die Speicherung unserer Datensaetze.
* ```CSVReader```: Klasse um CSV-Zeilen in Datensaetze zu uebersaetzen.
* ```JahresEinnahmenrechner```: Klasse fuer die Berechnung der Jahrespraemie.

Euch ist bestimmt aufgefallen, dass diesmal keine Main-Methode gefordert ist. Das liegt daran, dass wir nur einen Teil des fertigen Programmes entwickeln.
Stattdessen koennen wir unseren Code ueber JUnit-Tests kontrollieren.
