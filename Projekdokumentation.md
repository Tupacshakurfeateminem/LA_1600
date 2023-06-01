# LA_1600
# Projekt-Dokumentation

Cranberry: Broder, Hassani, Dakaj
| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|  11.5     | 0.0.1   | Use-Case Diagramm & Mockup, User Stories, 1.1 Prjkdoku, Arbeitspakete gemacht |
|      |    |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

In unserem Projekt müssen wir eine Webseite mit Thema/Inhalt unserer Wahl mit der Programmiersprache CSS programmieren. 



Unsere Themenwahl ist eine Informative Seite zu den Sporten Fussball, Basketball und Tennis, welche Inhalte wie das Spielkonzept, die Spielregeln, Stadien zu den Sporten, und berühmte Spieler. Zum Stadion und dem Spieler sind jeweils Bilder erhältlich. Man kann auf der Seite auch die Sprache ändern. Mit diesem Projekt wollen wir eine Sicherheit in unseren CSS-Kenntnissen und unserer praktischen Erfahrung erlangen. 


### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1  | Muss  |  Funktional| Als User möchte ich eine Webseite zu den Sportarten Fussball, Basketball, Tennis, deren Spielregeln, berühmte Spielhallen/Stadien zu dem Sport, ein paar erfolgreiche/bekannte Spieler, anschauen können. |
|2|Muss/Kann|Rand| Als User möchte ich, dass wenn ich auf das Bild der Sportart gedrückt habe, nur noch diese auf meinem Bildschirm ist, und die anderen zwei ausgeblendet werden und von der Startseite aus erreichbar sind.|
|3|Kann|Rand|Als User möchte ich, dass die Bilder zu den Sporten sich von selbst ändern, bzw. verschieden Bilder einblendet. |
|4|Kann| Rand|Als User möchte ich, dass wenn ich auf die Sportart drücke, zuerst ein Ball des Sportes dort runterfällt, wo dann der Inhalt, also Infos zu den die Spielregeln, berühmten Spielhallen/Stadien zum Sport, ein paar erfolgreiche/bekannte Spieler, eingeblendet wird.|
|5|Kann|Qualität|Als User möchte ich, dass das Spielkonzept zuerst einfach erklärt wird und ich für eine erweiterte Erklärung ein Pfeilchen drücken kann, welches den Rest nachlädt.|
|6|Kann |Rand|Als User möchte ich ein Bild von dem jeweiligen Stadion auf/nachklappbar ist.|
|7|Kann|Rand|Als User möchte ich, dass eine Animation zum Spieler vom Spieler in Aktion angezeigt wird.|
|8 | Kann| Rand| Als User möchte ich die Seite, bzw. das Geschriebene, auf englisch übersetzen können, damit nicht deutschsprechende Personen die Seite auch verstehen können. |
|9| Kann | Rand | Als User möchte ich, dass die Seite jeweils auch auf meinem Smartphone angenehm anzuschauen und mitzuinteragieren, ist.|


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 2.A/4.5  |   Seite geladen           |  Auf das Bild zum Sport drücken   |   Ball des Sports fällt und Seite lädt                |
| 3.A |  Geladene Seite zum gewählten Sport   |  Nichts        |    Bilder bewegen sich kontinoierlich         |
| 5.A| Seite zum Sport geladen |Erweiterung zum Text über Spielkonzept drücken |Ganzer Text wird angezeigt|
|6.A| geladene Seite mit änderndem Bild und aufklappbarem Text|Bild zum Stadion aufklappen | Bild wird ersichtlich |
|7.A|Geladene Seite vom Sport, stille Animation |Hover über Animation |Animation vom bekanntesten Spieler in Aktion geht los|
|8.A |Geladenen Seite | Auf Sprachenwechsel oben Links drücken| Sämtlicher Text wechselt die Sprache von Deutsch zu Englisch |


### 1.4 Diagramme

![image](https://github.com/Tupacshakurfeateminem/LA_1600/assets/111044137/1884d71e-55f7-470c-a6c7-73212dfdaae0)
![WhatsApp Bild 2023-05-11 um 10 08 09](https://github.com/Tupacshakurfeateminem/LA_1600/assets/89085609/b1a452e2-9391-48f9-8dcc-fbc77e4b4f77)


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |  11.5  |  Dakaj&Broder | Gerüst der Seite mit HTML erstellen | 45 min   |
|1.B| 11.5 |Dakaj |erste Grafik/visueller Aufbau der Seite erstellen| 45 min | 
|2.A | 25.5| Ava| Bild zum Sport anklicken, auf einzelne Seite landen| 50 min |
| 3.A  | 25.5 | Broder   |  Bild, dass von selbst wechselt   |   60 min    |
|4.A | 25.5|Dakaj | Ball welcher fällt| 50 min |
| 5.A|1.6| Ava|Erweiterung des Textes | 20 min|
|6.A |1.6 |Dakaj&Broder |"nachklappbares" Bild| 30 min|
|7.A |1.6 | Broder| Spieler-Animation| 40 min |
|8.A |7.6| Dakaj|Übersetzung auf Englisch | 45 min |
|9.A|7.6 |Ava |Smartphone freundlich| 45 min |

Total: 
10

## 3 Entscheiden



## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |   11.5    |  Dakaj&Broder         |   45 min            |    55 min               |
| 1.B |  11.5     |   Dakaj        |    45 min           |     55 min              |
| 2.A  |1.6     |  Ava         |    50 min           |                |
| 3.A  |    1.6   |  Broder        |   60 min            |                |
| 4.A | 1.6     |  Dakaj        |    50 min           |                 |
| ...  |       |           |               |                   |


## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
