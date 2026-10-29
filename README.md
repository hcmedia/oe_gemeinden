# Liste österreichischer Gemeinden inkl. E-Mail & Website 🇦🇹

Die Tabelle enthält folgende Informationen:

* Gemeindekennziffer 
* Gemeindename 
* Postleitzahl
* Website der Gemeinde
* E-Mail-Adresse der Gemeinde
* Straße (Postadresse)
* Ort (Postadresse)
* BürgermeisterVorname
* BürgermeisterNachname
* BürgermeisterGeschlecht (`M` / `W`)

> Formate: .csv (UTF-8), .xlsx und .json

Adresse und Bürgermeister-Felder sind derzeit befüllt für:

* **Oberösterreich** — Quelle: [ooeGem.txt](https://www.land-oberoesterreich.gv.at/gemeinden/ooeGem.txt)
* **Steiermark** — Quelle: [BürgermeisterInnen / Gemeindedaten (XLSX)](https://www.verwaltung.steiermark.at/cms/dokumente/11683218_74836396/614adf1c/2026_BGM_GEM_StDat_20261020.xlsx)
* **Niederösterreich** — Quelle: Gemeindeseiten auf [noe.gv.at](https://www.noe.gv.at/noe/Zahlen-Fakten/Statistik-Gemeinden.html) (Straße/Ort/Name; `BürgermeisterGeschlecht` dort nicht ausgewiesen und daher leer)

Für andere Bundesländer sind diese Felder vorerst leer.

### Beispiel

| Gemeindekennziffer | Gemeindename | Postleitzahl | Website             | E-Mail              | Straße | Ort | BürgermeisterVorname | BürgermeisterNachname | BürgermeisterGeschlecht |
|--------------------|--------------|--------------|---------------------|---------------------|--------|-----|----------------------|-----------------------|-------------------------|
| 00001              | Gemeinde1    | 0001         | http://example.com  | example@example.com | Musterstraße 1 | Musterort | Max | Mustermann | M |
| 00002              | Gemeinde2    | 0002         | https://example2.at | example@example2.at | | | | | |

##### Was ist die Gemeindekennziffer?(GKZ)

Die Gemeinekennziffer wird von der Statistik Austria verwendet um die Gemeinden zu kategorisieren.
Die fünfstellige Zahl funktioniert so:
* 1\. Zahl: Bundesland (Alphabetische Reihenfolge, also alle 1xxxx sind Burgendland zB)
* 2\. und 3. Zahl: Geben an um welchen politischen Bezirk es sich handelt.
* 4\. und 5. Zahl: Gemeindezahl, eher unwichtig.

> Wer mehr über GKZ wissen möchte: [Wikipedia](https://de.wikipedia.org/wiki/Amtlicher_Gemeindeschl%C3%BCssel#%C3%96sterreich) & [Statistik Austria](https://www.statistik.at/web_de/klassifikationen/regionale_gliederungen/gemeinden/index.html)

> Quelle: [Statistik Austria](https://www.statistik.at/web_de/klassifikationen/regionale_gliederungen/gemeinden/index.html)

> Habe das alles mit einem Python-Scraper gemacht. Alle Angaben ohne Gewähr!

