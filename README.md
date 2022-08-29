# ER-REL-Trainer

## Beschreibung
Mit dem ER-REL-Trainer wird die Überführung einer Beziehung zwischen zwei Entitäten eines ER-Diagramms in ein logisches relationales Schema trainiert. Es gilt die nötigen Tabellen anzulegen, die erforderlichen Schlüsselattribute zu ergänzen und die Richtung festzulegen, in der die Tabellen miteinander in Beziehung stehen.

## Systemanforderungen
Voraussetzung ist ein aktueller Webbrowser mit aktiviertem JavaScript.

## Installation
Die Webanwendung kann über GitHub Pages ohne Installation über die folgende Web-URL genutzt werden: https://eild-nrw.github.io/er_rel_trainer/.

Alternativ kann das Repository als ZIP-Datei heruntergeladen, an beliebiger Stelle entpackt und durch den Aufruf der enthaltenen `index.html` gestartet werden.

Über die Web-URL ist die Webanwendung immer auf dem neusten Stand und muss nicht von Hand aktualisiert werden. Dafür hat man bei der ZIP-Variante den Vorteil einer von GitHub unabhängigen Version mit weitreichender individueller Anpassbarkeit.

## Anpassbarkeit
Durch das Editieren der im Repository enthaltenen `configs.js` können weitreichende individuelle Anpassungen vorgenommen werden.

## Datenverarbeitung
In der unveränderten Basiskonfiguration werden an keiner Stelle Benutzer-spezifische Daten verarbeitet. Es handelt sich um reine Selbsttests mit direktem Feedback, was richtig/falsch beantwortet wurde. Es existieren keine Abhängigkeiten zu externen Servern und es findet entsprechend kein Datenaustausch mit anderen Servern statt.
<br><br>
Der Fortschritt kann, wenn gewünscht, offline-fähig lokal gespeichert werden, sodass man dort weitermachen kann, wo man das letzte Mal aufgehört hat. Dies kann bei Bedarf in der `configs.js` aktiviert werden.

## Hintergrundinformationen
Der ER-REL-Trainer wurde an der Hochschule Bonn-Rhein-Sieg im Rahmen des EILD-Projekts von André Kless entwickelt.

## Code-Dokumentation
Eine aus den Dokumentationskommentaren generierte Code-Dokumentation für Entwickler findet sich unter https://eild-nrw.github.io/er_rel_trainer/docs/.
<br><br>
Der `libs`-Ordner enthält wiederverwendete Webkomponenten, Bibliotheken und Frameworks.
<br>
Der `versions`-Ordner enthält alles was nötig ist, um auch ältere Versionen weiter lauffähig zu halten und um die Anwendung auch in anderen Webseiten (mit absoluten Pfaden) flexibel einsetzen zu können.

## Kontakt
Wir freuen uns über jedes Feedback und beantworten gern Ihre Fragen. Hierfür können Sie sich jederzeit (auch nach dem Ende des EILD-Projekts) an den Entwickler André Kless wenden.

Email: andre.kless@h-brs.de | Web: https://www.h-brs.de/de/inf/andre-kless
