---
layout: page
title: Ausrichten
---

<style>
  h2 {
  margin-top: 1.5rem;
  font-size: 1.5rem;
  border-top: 2px dotted #8f8f8f;
  padding-top: 0.5rem;
}
</style>

Ihr wollt also eine TaCoS ausrichten? Großartig! Diese Seite listet in keiner bestimmten Reihenfolge auf, um welche Dinge ihr euch vielleicht kümmern wollt.

Die Time-Badges (z.B. <span class="time-badge">August</span>) geben an, in welchem Monat ihr euch um dieses Thema kümmern könntet.

## Termin <span class="time-badge">Juli</span>

Seit einigen Jahren findet die TaCoS meistens in einer der späten Maiwochen statt, und zwar von Donnerstag bis Samstag (jeweils einschließlich). Am Sonntag gibt es einen inoffiziellen Brunch.

## Logo und „Corporate Identity“ <span class="time-badge">Juli</span>

Um ein Logo solltet ihr euch auch bemühen. Inspiration:

* Stadtwappen (siehe Bochum 2025, Buch)
* Abbildungen aus Papers (siehe Saarbrücken 2024, gehalten im Stil _der_ Standard-Transformer-Illustration)
* Literal Tacos (siehe [Düsseldorf 2023](https://github.com/tacosConference/.github/blob/7ed464865d018c0fce5a72772df00c15c50ad0f2/assets/wugos.png), die haben das aber auch noch mit einem Wug kombiniert)
* Logo der Universität

Wenn ihr dabei seid (das klappt auch noch viel später, aber vielleicht wollt ihr euch ja jetzt schon drum kümmern), könnt ihr euch auch noch um die folgenden anderen Dinge kümmern:

* Namensschilder für die Teilnehmer, mit groß gedruckten
  * Vor- und Nachname
  * Universität
  * Pronomen
  * Sprachen, die man spricht
* A4- und A3-Druckvorlage mit Logo, bisschen Design, und großem Platz für Freitext

Die A4- und A3-Druckvorlage kann man sich, wenn die Zeit gekommen ist, vielfach ausdrucken und dann mit einem Edding ausfüllen (schaut besser aus als ein hingepappter Karozettel), oder man druckt sich gleich auch noch ein paar Texte mit dazu:

* Raumnamen
* Pfeile in alle Richtungen und diagonal
* Name der Konferenz
* „Registration Desk“
* Nachnamensranges für den Registration Desk (also sowas wie „A-H“, „H–M“, „M-Z“)
* Verbleibende Vortragszeiten (10 min, 5 min, 2 min, 1 min o.Ä.)

## Technik <span class="time-badge">August</span>

### linguistik.computer

Schreibt an <vorstand@junge-sprachwissenschaft.de> und bittet um Zugriff auf die Website [linguistik.computer](https://linguistik.computer) (dies beinhaltet Zugriff auf [Seafile](https://seafile.junge-sprachwissenschaft.de/library/cccede54-df97-4507-bf6b-1ca13f608999/jekyll_tacos/) und die Website `tacos` im [Website-Dashboard](https://website-dashboard.junge-sprachwissenschaft.de/)).

Um eure TaCoS einzufügen, müsst ihr die Datei `_data/conferences.yml` bearbeiten, und ganz oben einen neuen Block im folgenden Format einfügen.

```yaml
- name: TaCoS 2025
  edition: 34
  location: Bochum
  date: 22. – 24. Mai 2025
  Tagungsort: Ruhr-Universität Bochum
  logo: https://tacosconference.github.io/34.tacosConference/css/2024_style/img/tacos_2025_logo_circle.png
  url: https://tacosconference.github.io/34.tacosConference
  image: bochum-1.jpg
```

Außerdem müsst ihr unter `assets/img/` ein Bild hochladen (im Beispiel: `bochum-1.jpg`). Bitte tragt auf jeden Fall `name`, `edition`, `location` und `date` ein; und sofern möglich `url` und `image`.

Nach dem Regenerieren erscheint eure TaCoS dann automatisch auf der [Startseite](/), im [Archiv](/pages/archive.md) in der Liste und der Statistik, und es wird ein hübscher Kurzlink der Form https://linguistik.computer/2025 angelegt.

### newsletter.fachschaft.cl.uni-heidelberg.de

Die Fachschaft Computerlinguistik in Heidelberg hat zur Unterstützung des TaCoS-Orga-Teams ein Newsletter-Tool eingerichtet. Es bietet ein Formular an, mit dem sich Leute für den Newsletter anmelden können, an die man dann Rundmails verschicken kann. Kontaktiert <fs-coli@cl.uni-heidelberg.de>, um wahlweise Tipps zu bekommen, wie ihr so etwas auch hosten könnt, oder vielleicht sogar Zugriff zu bekommen.

### stage.tacos.cl.uni-heidelberg.de

Die Fachschaft Computerlinguistik in Heidelberg betreibt außerdem die TaCoStage (Eigenentwicklung), um Beiträge entgegenzunehmen. Kontaktiert <fs-coli@cl.uni-heidelberg.de>, um Tipps zum Selbsthosting oder ggfs. Zugriff zu bekommen.

Alternativ könnt ihr auch talks.stuts.de verwenden.

### talks.stuts.de

Schreibt an <vorstand@junge-sprachwissenschaft.de> und gebt an, dass ihr gerne Zugriff aufs [talks.stuts.de](https://talks.stuts.de) (auch genannt „frab“) hättet. Mit diesem Tool könnt ihr Einsendungen zu sammeln, Vorträge und Redner verwalten und ein Programm erstellen.

### tacosconference.github.io

Schreibt an <anna.stein@hhu.de> und bittet um Zugriff auf [github.com/tacosConference](https://github.com/tacosConference). Damit kontrolliert ihr dann automatisch auch [tacosconference.github.io](https://tacosconference.github.io/).

## Tagungsort <span class="time-badge">September</span>

Als Tagungsort bieten sich Räume der Uni an. Mit Glück könnt ihr entweder direkt, oder über ein Institut oder eine Fakultät kostenlos Räume reservieren. Denkt daran, früh anzufragen, da Unis oft sehr früh mit der Planung für das kommende Semester beginnen (fragt da gegebenenfalls mal beim Sekretariat an, bis wann die Rückmeldung brauchen).

Heidelberg hatte 2026 in der Planung initial mit 60 Teilnehmern gerechnet, es wurden dann aber doch eher 120 Anmeldungen. Am ersten Tag waren dann so ca. 85 Leute da. Also die 60-Raum-Planung war vielleicht okay.

Die folgende Raumkonfiguration könnte man für eine Konferenz mit 60 Teilnehmern einplanen (am besten natürlich alles in einem Gebäude, um Laufwege zu minimieren und zu verhindern, dass jemand verloren geht):

- 2 Seminarräume, Kapazität: 40–45 Personen
  * Auf die Weise kann man parallele Tracks machen, und hat etwas Puffer, falls mal doch ein Vortrag ausfallen sollte oder ein Vortrag wesentlich beliebter ist etc.
- 1 Hörsaal, Kapazität: >60 Personen
  * Für Eröffnung, Abschluss, Keynotes etc.
- 1 Pausenraum
  * Für Snacks und Getränke, und als Rückzugsort
- 1 Tagungsbüro
  * Also halt ein normaler Seminarraum, aber es ist erfahrungsgemäß immens nützlich, wenn man einen Raum hat für das Team (für einen Late Registration Desk, Storage, Abhängen in Pausen etc.)
- 1 Foyer
  * Falls euer Gebäude einen Eingangsbereich hat, könnte man da zum Beispiel ein paar Tische für die Anmeldung aufbauen.

Plant auf jeden Fall, Wegweiser zu basteln. Eine Schablone und Sprühkreide können helfen, um Pfeile auf den Boden zu malen.

## Save-The-Date <span class="time-badge">Oktober</span>

Per Mail an:

* Eure Fachschaft
* Andere Coli-Fachschaften (Heidelberg hat eine Liste)

Falls ihr auf sozialen Medien aktiv seid, wäre ein Post dort sicher auch sehr angebracht. In dieser Mail könntet ihr, sofern ihr es eingerichtet habt, auch Werbung für euren Newsletter machen.

## Finanzen <span class="time-badge">Oktober</span>

Größenordnungsmäßig kostet eine TaCoS 10.000 € (± 5.000 €).

### Konto

Um das Sponsorengeld irgendwo aufzubewahren, braucht ihr ein Konto. Wir können euch hier keine rechtlich geprüften Tipps geben, aber es soll schon TaCoS-Tagungen gegeben haben, die sich dafür einfach ein privates Girokonto bei einer Bank eröffnet haben (und die TaCoS dementsprechend einfach „privat“ organisiert haben). Am besten, ihr fragt da mal bei den Vorjahresorganisatoren nach.

Die Junge Sprachwissenschaft e. V. unterstützt aber, wenn ihr sie lieb fragt, vielleicht auch mit ihrem Konto.

### Budgetplan

Ihr braucht einen Budgetplan. Selbst, wenn ihr selbst keinen wollt, will früher oder später ein Sponsor einen sehen. Dinge, die man normalerweise bezahlen muss, sind:

* Essen
  * Mensa (Donnerstag und Freitag)
  * Caterer (Samstag, da haben Mensen ja oft zu)
  * Getränke und Snacks für die Kaffeepause
* Unterkünfte (Zuschuss für die Teilnehmer)
* Werbung
  * Merchandise-Artikel (Tassen, Flaschenöffner, Taschen, Notizbücher, Sticks, ...)
  * Aufsteller, Banner, Poster
* Aufmerksamkeitsgeschenke für Keynote-Speaker (Schokolade, Blumen, ...)

Dinge, die man vielleicht gratis bekommt, sind hingegen:

* Tagungsort
  * Räume an der Uni kann man als studentisches Projekt zumeist einfach reservieren.

### Sponsoren

Eine großzügige Organisation unterstützt vielleicht so mit 1.000 €. Von Firmen haben wir oft Spenden in Höhe von 500 € gesehen. Ein kleiner Sponsoringbetrag wären 100 €.

### Rechnungen

Eigentlich alle Organisationen wollen für ihr Sponsoring eine Rechnung bekommen, ihr müsst also Rechnungen ausstellen. Wenn ihr die TaCoS privat organisiert (also nicht unter der Schirmherrschaft eines Vereins oder einer Körperschaft oder eines sonstigen Gewerbes), stellt ihr [Privatrechnungen](https://de.wikipedia.org/w/index.php?title=Rechnung&oldid=258701942#Zivilrecht:~:text=durch%20Privatpersonen%20(-,Privatrechnung,-)%20nicht%20gesetzlich%20geregelt) aus. Das Gute: Für Privatrechnungen gibt es offenbar keine gesetzlichen Regelungen. Eine solche Rechnung auszustellen ist also weniger gruselig, als es klingt.

Die folgenden Infos könntet ihr draufschreiben:

* Voller Name und Adresse eines Verantwortlichen
* Adresse des Sponsors
* Rechnungsdatum
* Rechnungsnummer (denkt ihr euch aus)
* Überschrift „Rechnung“
* Referenz (ein String, den der Sponsor potenziell bei der Überweisung angeben wird)
* Tabellarische Aufstellung der Rechnungsposten (vermutlich nur eine Zeile)
  * Postennummer (z. B. 1)
  * Bezeichnung (z. B. „Sponsoring der TaCoS 2026“)
  * Einzelpreis in € (z. B. 100,00)
  * Gesamtpreis in € (z. B. 100,00)
* Zahlbar an
  * Name
  * IBAN

Manche Organisationen hätten gerne eine Angabe der enthaltenen Umsatzsteuer. Bei einem Privatgeschäft seid ihr von der Umsatzsteuer befreit, gebt also da 0 % bzw. 0 € an, optional vielleicht noch einen Vermerk, dass es sich um ein Privatgeschäft handelt.

* [Anleitung zum Schreiben einer Privatrechnung · rechnung.de](https://www.rechnung.de/ratgeber/rechnung-erstellen/privatrechnung/)

Wir haben für euch auch eine Beispielrechnung vorbereitet. Diese ist verschlüsselt, wir schicken euch das Passwort aber gerne zu, wenn ihr uns eine Mail an „tacos@cl.uni-heidelberg.de“ mit dem Betreff „Passwort“ schreibt. Mit dem verlinkten Tool könnt ihr das Passwort an eurer Kopie dann auch gerne wieder entfernen.

* [Beispielrechnung (PDF, verschlüsselt)](/assets/pdf/encrypted-Rechnung_Muster.pdf)
* [Mail an tacos@cl.uni-heidelberg.de für Passwort](mailto:tacos@cl.uni-heidelberg.de?subject=Passwort)
* [Tool, um das PDF zu entschlüsseln](pdf.fachschaft.cl.uni-heidelberg.de)

Wenn ihr eine Rechnung braucht, die von einer echten juristischen Person ausgestellt wird, fragt mal lieb die Junge Sprachwissenschaft e.V., die kann euch eventuell helfen.

### Teilnahmebeitrag

Setzt einen Teilnahmebeitrag fast. Mindestens mal eine kleine Gebühr (sowas wie 10 €) bietet sich an, um eine gewisse Verbindlichkeit sicherzustellen (wer schon bezahlt hat, wird vermutlich auch kommen).

## Essen und Trinken <span class="time-badge">Dezember</span>

Fragt das lokale Studierendenwerk für die Mensa an. Normalerweise werden die dafür irgendein erprobtes Verfahren haben (meistens über Coupons, die man einlösen muss). In Heidelberg kostete 2026 ein Essen ca. 8 € pro Person und Tag.

Für den Sonntagsbrunch solltet ihr Plätze in einem Café reservieren. Das könnt ihr sinnvoll allerdings vermutlich erst nach beendeter Anmeldefrist machen.

## Keynotes <span class="time-badge">Dezember</span>

Fragt lokale Professoren, Postdocs oder sonstige Leute, die interessante Dinge zu erzählen haben, an, ob sie Lust haben, eine Keynote für die TaCoS zu geben. Eine Keynote ist auch einfach nur ein Vortrag, aber meistens ohne zeitgleich Vorträge, und mit besonderer Hervorhebung.

Wann genau welche Keynote stattfindet, könnt ihr zusammen mit der Programmplanung machen (etwas später), aber es rentiert sich sicherlich, schon mal vorab anzufragen.

## Unterkünfte <span class="time-badge">Januar</span>

Günstig zu organisieren ist Couchsurfing: Fragt Leute aus eurer Fachschaft, ob sie bereit wären, andere Studis für die Tage unterzubringen.

Man könnte versuchen, Hotelkontigente zu bekommen, das scheint aber eher teuer und aufwändig zu sein.

## Anmeldung <span class="time-badge">Januar</span>

Für die Anmeldung bietet sich ein Online-Formular an. Die Junge Sprachwissenschaft betreibt das Anmeldetool [FISH](https://anmeldung.stuts.de/), ihr könnt aber auch ein Formular auf eurer eigenen Website implementieren (sofern ihr ein Backend dafür betreibt).

* [Anmeldung zur 35. TaCoS 2026 (eigene Website)](https://linguistik.computer/2026/participate/)
* [Anmeldung zur 33. TaCoS 2024 (via FISH)](https://anmeldung.stuts.de/tacos2024)

Falls ihr euch das Formular selbst zusammenklicken wollt, bietet sich [CryptPad Forms](https://cryptpad.fr/form/) an. Das ist so ähnlich wie die Formulartools der Technik-Giganten, aber etwas respektvoller gegenüber der Privatsphäre der Teilnehmer.

### Inhalt

Die folgenden Formularfelder könnte eure Anmeldung enthalten:

1. Vorname
2. Nachname
3. Pronomen (optional)
4. E-Mail-Adresse
5. Universität
6. Studiengang (optional)
7. Sprachen, die ich spreche
8. Checkbox: Ich war schon einmal auf einer TaCoS
9. Unterkunft: Habe eine / brauche eine und Couchsurfing ist okay / brauche eine, aber bitte kein Courchsurfing
10. Bedürfnisse zur Barrierfreiheit (optional)
11. Anmerkungen (optional)
12. Checkbox: Ich akzeptiere den Code of Conduct

Guter Stil wäre es, zu jedem Feld anzugeben, warum ihr es erhebt (also z.B. für Statistiken, oder um den Austragungsort der nächsten TaCoS zu bestimmen, oder um bestimmtes Essen einzukaufen).

Außerdem sollte direkt auf der Anmeldung stehen, wie hoch der Teilnehmerbetrag ist, und an welchen Kontoinhaber mit welcher IBAN und welchem Verwendungszweck er zu überweisen ist. Der Verwendungszweck sollte den Namen der Person enthalten (mit JavaScript könntet ihr den sogar direkt aus dem Namensfeld der Anmeldung kopieren, dann braucht ihr keinen Platzhalter der Form `<Dein Name>` in der Verwendungszwecks-Angabe). Für noch erhöhten Komfort könnt ihr euch [einen EPC-QR-Code generieren lassen](https://github.com/tacosConference/35.tacosConference/blob/ed021d72ea6385d474b4d34d2668dc8569dd5d03/src/lib/components/SignupForm.svelte#L18-L35), den können die meisten Banking-Apps scannen, dann spart man sich das Abtippen von IBANs.

Als Anmeldedeadline könntet ihr z. B. Mitte März nehmen. Setzt diese nicht zu spät, da sich so oder so nach der Deadline noch Leute bei euch melden werden, die die Anmeldung leider verpasst haben, aber sehr gerne doch noch teilnehmen wollen etc. Diese Anfragen lassen zwar mit der Zeit nach, tröpfeln aber offenbar bis zu Beginn der Konferenz noch ein. Stellt daher sicher, dass eure Lösung zur Anmeldung flexibel ist — es wäre schade, wenn ihr eine Person später noch aufnehmen wollt, die Kapazitäten dafür auch noch da wären, aber euer Anmeldeformular keine weiteren Anmeldungen mehr zulässt und ihr diese dann separat tracken müsst. 2026 in Heidelberg gab es einen nur auf Anfrage herausgegebenen Link, der das Anmeldeformular wieder aktivierte, am Ende liefen alle Anmeldungen im selben System zusammen.

### Ankündigung

Kündigt die Öffnung der Anmeldung (aka. die offizielle Einladung an), und zwar idealerweise:

* Per Mail an alle Coli-Fachschaften
* Per Mail an alle Newsletter-Abonnenten
* Prominent auf eurer Website
* Über soziale Medien

Ihr könnt die Anmeldung zeitgleich mit dem Call for Participation freischalten.

### Reaktion

Sobald jemand das Formular ausgefüllt hat, solltet ihr eine Bestätigungs-E-Mail verschicken. Erfahrungsgemäß freuen sich Leute ab dann auch über gelegentliche Aktualisierungen zum Planungsfortschritt, um zu wissen, dass die TaCoS tatsächlich so passiert und um Rückfragen zu vermeiden.

## Call for Participation <span class="time-badge">Januar</span>

Überlegt euch, welche Beitragsformate ihr akzeptieren wollt, z.B.:

* Lightning Talk: 5-10 min, nur Vortrag, keine Fragen
* Normaler Talk: 20 min Vortrag + 10 min Fragen
* Workshops: 30 oder 60 min, zum Mitmachen

Um einen Beitrag einzureichen, wird oft ein Titel und ein Abstract (70–200 Wörter) verlangt. Zur Einreichung könnt ihr wahlweise ein Formular erstellen (z.B. mit [CryptPad Forms](https://cryptpad.fr/form/)), oder talks.stuts.de oder vielleicht die TaCoStage benutzen.

Als Einreichungsdeadline könntet ihr z. B. Ende März nehmen.

Zeitnah nach Ende der Einreichungsdeadline solltet ihr durch die Einreichungen durchgehen und sie (im Normalfall) annehmen. **Denkt daran, danach eine Mail an alle Personen zu verschicken**, um sie über die Annahme zu informieren (denn für viele ist das der Startschuss für die Vortragsvorbereitung).

## Merchandise <span class="time-badge">März</span>

Beliebt sind:

* Tassen (TaCoS 2026: 125 Tassen, 550 €, geht billiger, waren aber auch coole Tasse)
* Sticker (TaCoS 2026: 400 Stück, rund, Outdoor, 55 € & 1500 Stück, quadratisch, Outdoor, 50 €)
  * Outdoor-Sticker sind robuster und reiben sich nicht so ab (was nützlich ist, wenn sie sich jemand auf eine Handy-Hülle klebt, die oft aus Hosentaschen gezogen und wieder hineingesteckt wird).
  * Rechteckige Sticker sind billiger als runde.
* Taschen

## Programm <span class="time-badge">April</span>

<!-- TODO -->

## Vorbereiten <span class="time-badge">1 Tag vorher</span>

- Schilder für Wegweiser aufhängen
- Registration Desk aufbauen
- Einkaufen (Snacks, Getränke, ...)
- Räume mal auf Sicht kontrollieren (die Schlüssel habt ihr hoffentlich schon vorher abgeholt)

### Getränke bestellen

Zum Beispiel bei Flaschenpost. 2026 hat Heidelberg mit der folgenden Bestelliste gute Erfahrungen gemacht:

* 2 Kästen, je 24× 0,33L (Glas) Rothaus Pils Tannenzäpfle
* 2 Kästen, je 20× 0,5L (Glas) Paulaner Spezi
* 2 Kästen, je 20× 0,5L (Glas) Paulaner Spezi Zero
* 2 Kästen, je 20× 0,5L (Glas) Club-Mate Original
* 2 Kästen, je 20× 0,5L (Glas) Chiemseer Hell
* 2 Kästen, je 24× 0,33L (Glas) Proviant Bio Orangenlimo
* 2 Kästen, je 24× 0,33L (Glas) fritz-kola
* 1 Kasten, je 24× 0,33L (Glas) fritz-kola ohne zucker
* 1 Kasten, je 24× 0,33L (Glas) Proviant Bio Rhabarberlimo
* 1 Kasten, je 24× 0,33L (Glas) Fanta Exotic
* 1 Kasten, je 20× 0,5L (Glas) Franziskaner Hefe-Weissbier Naturtrüb
* 1 Kasten, je 20× 0,5L (Glas) Augustiner Lagerbier Hell
* 1 Kasten, je 20× 0,5L (Glas) Oettinger Eistee Zitrone
* 1 Kasten, je 6× 1L (Glas) Mixkiste De Buur Mix - klarer Apfelsaft, Multivitaminnektar, Orangensaft
* 4× 0,25L (Dose) Red Bull Energy Drink Green Edition
* 4× 0,5L (Dose) Monster Energy Ultra White
* 4× 0,5L (Dose) Monster Energy Mango Loco
* 4× 0,25L (Dose) Red Bull Energy Drink Sea Blue Edition
* 1× 0,75L (Glas) Fassreiter Riesling feinherb halbtrocken

Kosten (inklusive Pfand) knapp 600 €.

## Durchführen <span class="time-badge">Währenddessen</span>

### Folien einsammeln 

Generell finden es viele Teilnehmende gut, die Slides aus den Talks am Ende zu bekommen. Dazu solltet ihr *am besten schon während der Konferenz* euch einen Kanal überlegen, über den ihr die Folien verteilt, und dann spätestens direkt nach der Konferenz die Speaker darum bitten, euch die Folien zur Verfügung zu stellen.

Sobald alle Folien da sind, freuen sich die Teilnehmenden sicher noch mal über eine Mail.

### Abschließen

