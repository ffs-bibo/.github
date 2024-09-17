# FFS-Bibo

Dies ist der Ort wo ich (@assarbad) einstweilen alles unterbringe was zur Digitalisierung der Schulbücherei an der Friedrich-Fröbel-Schule in Frankfurt-Niederrad dienen kann, bis auf Daten die personenbezogen sind oder für die ich keine Freigabe vom Urheber habe.

Das Ziel in der Ferne ist ein Rust-basierter Dienst der eine Datenbank vorhält und per WASM eine browserbasierte Oberfläche bietet. In Sachen Datenbank ist derzeit eine rein lokale Variante angedacht, wobei ich versuchen werde eine mögliche Anbindung an eine zentrale Datenbank und eine entsprechende Abstrahierung im Hinterkopf zu behalten. In dem kleinen Rahmen wie wir die Bücherei betreiben, ist allerdings vermutlich ein Rechner mehr als ausreichend und daher eine Anbindung an eine zentrale Datenbank -- mit den entsprechenden datenschutzrechtlichen Implikationen -- vermutlich nicht notwendig.

## Webseiten

* [Schule](https://www.ffsfrankfurt.de)
* [Förderverein](https://www.fv-ffs.de/)
* [SBA-Katalogsuche](https://sbakatalog.stadtbuecherei.frankfurt.de/A-F/Friedrich-Fr%C3%B6bel-Schule)

# Weiterführende Links

* Deutsche Nationalbibliothek
  * [deutsche-nationalbibliothek](https://github.com/deutsche-nationalbibliothek)-Github-Org
    * [deutsche-nationalbibliothek/dnblab](https://github.com/deutsche-nationalbibliothek/dnblab)
  * dnblab:
    * https://www.dnb.de/dnblabtutorials
    * https://www.dnb.de/sru (Search & Retrieve via URL) via CQL (Contextual Query Language)
      * bspw. https://services.dnb.de/sru/dnb?version=1.1&operation=searchRetrieve&query=num=9783954702039&recordSchema=oai_dc
    * https://www.dnb.de/metadatenbezugswege
  * https://portal.dnb.de/ (Datenshop usw.)
  * https://sta.dnb.de/wiki/Hauptseite (Wiki, aber nur bedingt für unseren Anwendungsfall geeignet)
* https://github.com/mloesch/sickle
