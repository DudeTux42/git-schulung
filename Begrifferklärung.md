## Git 
Git ist ein Open-Source-Tool welches für die Versionskontrolle von Software verwendet wird. Es wurde 2005 von Linus Torvalds ins Leben gerufen wurde. Das Wort “Git” kommt aus der britischen Umgangssprache und bedeutet übersetzt soviel wie “Blödmann”. Linus Torvalds begründete seine Namenswahl für Git zum einen damit, dass das Wort praktisch und in der Softwarewelt noch unbenutzt war und zum anderen, dass er alle seine Produkte nach sich benennt.

Git erlaubt mehreren Entwicklern an einem Projekt zu arbeiten, indem sie eine lokale Arbeitskopie des kompletten **Repositories** (und somit der Projektdaten) auf ihrem Rechner haben. Git macht es für die Entwickler möglich Änderungen des Codes zu verfolgen, sie rückgängig zu machen, sie anderen zur Verfügung zu stellen und über Git auch Änderungen von anderen einzuholen. Neben den lokalen Arbeitskopien der Entwickler existieren noch remote Repositories. Die Änderungen aus dem eigenen Repository können per Git öffentlich gemacht werden indem sie in ein Remote-Repository "gepusht" werden. Weil jeder Entwickler eine Kopie der vollständigen Projektdaten hat, ist Git ein **verteiltes Versionskontrollsystem.**

### Was sind die Vorteile von GIT?
- **Daten-Sicherheit**: Da jeder Entwickler via Git eine Kopie aller Projektdaten besitzt, ist die Wahrscheinlichkeit, Daten durch einen Serverausfall zu verlieren, minimal.
- **Flexibilität:** Mehrere Entwickler können dank Git zeitgleich an einem Projekt arbeiten.
- **Versionsspeicherung:** Da jede Code-Änderung per Git verfolgt und gespeichert wird, kann man im Notfall an einem späteren Zeitpunkt auf ältere Stände des Projekts zugreifen. Somit wird verhindert, dass getätigte Arbeiten überschrieben werden oder verloren gehen. Hier spielt auch der Befehl “git commit” eine Rolle (siehe unten).


## Versionskontrollsystem
Ein Versionskontrollsystem wie Git wird in der Softwareentwicklung verwendet, um Änderungen des Quellcodes zu speichern und zu verwalten. Hier gibt es drei Arten von Versionskontrollsystemen: die lokale Versionsverwaltung,  die zentrale Versionsverwaltung und die verteilte Versionsverwaltung. Bei der **lokalen Versionsverwaltung** werden Dateien lokal einfach nur in ein separates Verzeichnis kopiert. Bei der **zentralen Versionsverwaltung** gibt es einen einen zentralen Server, der alle versionierten Dateien verwaltet und es Personen ermöglicht, Dateien von diesem zentralen Repository (Aufbewahrungsort) abzuholen und auf ihren PC zu übertragen. Bei der **verteilten Versionsverwaltung** gibt es zwar ein zentrales Repository, aber jede Person  hat eine Kopie des Repositories und somit die vollständigen Projektdaten. Steuern lässt sich die Versionsverwaltung mit Befehlen wie “git commit” (siehe unten).


## GitHub
Neben Git, dem Versionskontrollsystem welches mithilfe der Kommandozeile benutzt wird, gibt es noch GitHub. Im Gegensatz zu Git ist GitHub kein Versionskontrollsystem sondern **eine Hosting-Plattform** die Versionskontrolle und das Zusammenarbeiten an Projekten ermöglicht. GitHub zeichnet sich durch seine Benutzerfreundlichkeit aus, da durch die Benutzeroberfläche die Verwaltung von Git-Repositories vereinfacht wird. GitHub ist vor allem für das Teilen von Open Source Software beliebt, da öffentliche Repositories auf GitHub verwendet werden können.


## GIT Begriffe
- **Repository**: Ein Git-Repository (Aufbewahrungsort) ist eine Arbeitskopie der Entwickler das den vollständigen Verlauf aller Änderungen enthält. Zusätzlich gibt es noch ein remote Repository in dem alle lokalen Änderungen zusammenkommen.
- **Branch:** Entwicklungsstände (z.B. neue Features) können dank Git in sogenannte branches (separate Arbeitszweige) aufgeteilt werden. Sie dienen dazu, verschiedene Funktionen getrennt voneinander zu entwickeln.
- **Commit:** Der Befehl “git commit” wird verwendet um den Status eines Projekts zu erfassen. Das bedeutet, dass der gegenwärtige Status eines Projekts als eine Version in Git gespeichert wird. “Git commit” ist somit eine besonders relevante Funktion.
- **Merge:** Der Befehl “git merge” wird verwendet um Änderungen aus verschiedenen  branches zusammenzuführen.
- **Push:** Der Befehl “git push” wird verwendet um lokale Änderungen an ein entferntes (remote) Repository zu senden.
- **Remote:** Als Remote wird ein entferntes Repository bezeichnet wie z.B GitHub oder GitLab.
- **Local:** Dein lokales Repository  bzw.  das wo das gespeichert wird was du in deinem lokalen Projekt comittest.






