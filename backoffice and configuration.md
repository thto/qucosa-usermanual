* ##### [Login und Zugang zum Backoffice](#login-und-zugang-zum-backoffice)

  * ##### [Start Backoffice TYPO3](#start-backoffice-typo3)
* ##### [Die Bedeutung der Schaltflächen](/backoffice and configuration.md)
* ##### Veröffentlichen von Dokumenten
* ##### Bearbeiten von bereits veröffentlichten Dokumenten
* ##### [Felder und Eingaberegeln](#felder-und-eingaberegeln)

## [Login und Zugang zum Backoffice](#login-und-zugang-zum-backoffice)

Das Backoffice ist im neuen System in die Contentmanagementsoftware TYPO3 integriert.  
Dieses ist über folgenden Link:  
[https://web-redaktion.slub-dresden.de/typo3/](https://web-redaktion.slub-dresden.de/typo3/ "Qucosa- Administrationsbereich")

oder über die Qucosa-Webseite zu erreichen:

#### Start Backoffice TYPO3

* linke Menüleiste - Qucosa - Manager anklicken
* mittlere Menüleiste - gewünschten Mandantenbereich anklicken
* richtig angemeldet ist man, wenn im rechten Anzeigefeld die Meldung

  ![](file:///C:/Users/hoericht/AppData/Local/Temp/msohtmlclip1/01/clip_image001.png "\(Warnung\)") **Es wurde kein gültiger Mandantenordner ausgewählt! **

nicht mehr angezeigt wird.

* um möglichst viel Platz im rechten Anzeigefeld zu haben, kann man die beiden Menüleisten links zusammenschieben, die mittlere kann auch ausgeblendet werden

## [Die Bedeutung der Schaltflächen](#die-bedeutung-der-schaltflächen)

## 

**Generell gilt:** Etwas heller eingefärbte Schaltflächen sind für den konkreten Anwendungsfall nicht relevant und können deshalb nicht bedient werden.

| **Symbol/Button** | **Wo?** | **Aktion** |  |
| :---: | :---: | :---: | :---: |
| Neu |  | Anzeige aller neu angemeldeten Dokumte |  |
| In Bearbeitung |  | Anzeige aller Dokumente, welche sich gerade im Arbeitsbereich befinden |  |
| ![](file:///C:/Users/hoericht/AppData/Local/Temp/msohtmlclip1/01/clip_image001.png) Previewanzeige |  |  |  |
| ![](file:///C:/Users/hoericht/AppData/Local/Temp/msohtmlclip1/01/clip_image002.png) Duplizieren des Dokumentes |  |  |  |
| ![](file:///C:/Users/hoericht/AppData/Local/Temp/msohtmlclip1/01/clip_image003.png)Aktivieren des Dokumentes |  | Einblenden eines bereits veröffentlichten Dokumentes | ein zuvor inaktiv gesetztes Dokument soll wieder in die Suche integriert werden |
| ![](file:///C:/Users/hoericht/AppData/Local/Temp/msohtmlclip1/01/clip_image004.png)inactive document |  | Ausblenden eines bereits veröffentlichten Dokumentes | Dokument kann in der Suche nicht mehr gefunden werden, es erscheint nicht in der Landing-Page Dokument ist im Frontend nicht mehr sichtbarInaktiv gesetzte Dokumente können im Arbeitsbereich gelöscht werden, es wird innerhalb des Repositories ein Schalter umgelegt. Dadurch hat man die Möglichkeit den Arbeitsbereich für bestimmte Dokumente zu leeren. |
| ![](file:///C:/Users/hoericht/AppData/Local/Temp/msohtmlclip1/01/clip_image005.png) | DokumentenlisteDatensatz im Editiermodus | Entfernen eines Datensatzes aus dem lokalen Arbeitsbereich | Möglichkeit, einen Datensatz vor der Veröffentlichung zu löschenMöglichkeit, die Kopie eines Datensatzes, die zur Aktualisierung in den lokalen Arbeitsbereich geholt wurde, zu löschen |
| ![](file:///C:/Users/hoericht/AppData/Local/Temp/msohtmlclip1/01/clip_image006.png)![](file:///C:/Users/hoericht/AppData/Local/Temp/msohtmlclip1/01/clip_image007.png) | Dokumentenliste | Veröffentlichen des Datensatzes | Metadaten und Datei\(en\) werden ins Repository übertragen. Präsentation über die Recherche erfolgtDokument wird nicht mehr im lokalen Arbeitsbereich gelistet |
| ![](file:///C:/Users/hoericht/AppData/Local/Temp/msohtmlclip1/01/clip_image008.png)![](file:///C:/Users/hoericht/AppData/Local/Temp/msohtmlclip1/01/clip_image009.png) | Dokumentenliste | Abschließen der Korrektur eines bereits veröffentlichten Datensatzes | Kopie des Datensatzes wurde im lokalen Arbeitsbereich bearbeitet-                         Korrekturen werden ins Repository übertragen.Dokument wird nicht mehr im lokalen Arbeitsbereich gelistet |
| ![](file:///C:/Users/hoericht/AppData/Local/Temp/msohtmlclip1/01/clip_image010.png)![](file:///C:/Users/hoericht/AppData/Local/Temp/msohtmlclip1/01/clip_image011.png) | Datensatz im Editiermodus | Markieren eines Datensatzes als "Im Repository Löschen" | Schaltfläche steht nur für Datensätze zur Verfügung, die bereits freigeschaltet wurden, sich im Repository befinden und für die eine Kopie zur Aktualisierung in den lokalen Arbeitsbereich geholt wurde |



## [Felder und Eingaberegeln](/backoffice and configuration.md)



| **Dokumentenarten** | **Seite** | **Feldgruppe / Felder** | **Beschreibung** |
| :--- | :--- | :--- | :--- |
|  | Dokument | Jahr der Erstveröffentlichung | Jahr der Erstveröffentlichung eines Artikels in einem Journal, einer Printausgabe u.ä.relevant für die Formalerschließungnicht Jahr der Veröffentlichung auf Qucosa |
|  | Dokument | URN Qucosa | die Qucosa URN wird automatisch mit der Veröffentlichung \(Freischlatung\) des Dokuments vergebenbei Bedarf kann sie vorab durch Bedienung der Schaltfläche rechts im Feld erzeugt werden |
|  | Dokument | Identifier  Checkbox "Invalid" |  |
|  | Dokument | Bandnummer Schriftenreihe / mehrbändiges Werkmit den Feldern Sortierschlüssel und Bandnummer | Bandzählung innerhalb einer Schriftenreihe oder eines mehrbändigen Werkesnumerischer Sortierschlüssel, um die Sortierung in der Liste der mit einer Überordnung in Qucosa verknüpften Bände zu bestimmenes ist auch möglich, nur eine Sortierzählung anzugeben, wenn die Bände keine Zählung haben |
|  |  |  |  |
|  | Personen | Namenszusätze | Feld noch nicht belegen |
|  |  |  |  |
|  | Quellenangaben | URN | in dieses Feld darf keine Qucosa-URN eingetragen werden |
|  | Quellenangaben | Quellenangaben - Quelle \(Display Name: Quelle\) | in dieses Feld darf nichts eingetragen werden; es dient lediglich der Migration der Altdaten |





