---
# Post Title
# String | *REQUIRED*
# Ex: Top 4 React UI Libraries for 2023
title: GoLang - eine Reise von GoLand bis Writerside
 
# Post Slug
# What is slug? https://www.semrush.com/blog/what-is-a-url-slug
# String | *REQUIRED*
# Ex: top-4-react-ui-libraries-for-2023
# - This is the URL of the post. It should be unique and should not be used by any other post.
# - If you use the same slug of an existing post, the existing post will be updated.
# - In order to let users update the post SLUG, we depend on the post slug as well
# as it's path in the repo.
# - If you change both path and slug of the post, the post will be treated as a new post and
# will be published with a new slug.
# - If you change only the slug of the post, the post will be updated with the new slug.
# - If you change only the path of the post, the post will be will be updated with new path
# and any other changes along with it if any.
slug: Go
 
# Tags
# String (comma-separated tag slugs) | *REQUIRED*
# Ex: reactjs, css, python, nodejs
# Upto 5 tag slugs
# - You can find tags information from here https://github.com/Hashnode/support/blob/main/misc/tags.json
# You can also update a post to edit this later.
tags: go
 
# Publication Domain (hashnode.dev subdomain or your custom domain)
# String | *REQUIRED*
# Ex: townhall.hashnode.com
# - This can also be a hashnode.dev subdomain as well.
# - The publication domain name that you want to publish the post to.
# This should be a valid domain name only.
# - You should be an ADMIN of the publication to publish.
domain: de.blog.postrausch.tech
 
# Subtitle of the post
# String | Optional
# Ex: A curated list of the best React UI libraries for 2023
subtitle: GoLang - eine Reise von GoLand bis Writerside
 
# Cover Image URL of the post
# String | Optional
# Note: You must upload the image to Hashnode's CDN, before you can use it here.
# Ex: https://cdn.hashnode.com/res/hashnode/image/upload/v1681132538878/itnaYF1h-.png
# - To upload, Login to Hashnode and go to https://hashnode.com/uploader
# Use the URL that is generated after the upload.
cover:
 
# Should the post be ignored? When true it will not be picked up by Hashnode.
# Boolean | Optional
# Default value: false
# Ex: true
# - It's useful when you want to keep the post in your repo but don't
# want it to be picked up by Hashnode.
ignorePost: False
 
# Publish on behalf of a team publication member
# String | Optional | *WORKS WITH TEAM PUBLICATION ONLY*
# Ex: sandeep
# - Does not have any effect in drafts. It will be ignored in drafts.
# But once you convert the draft to post, it will be respected
# - This resembles the Change of author from article settings of a
# team publication in Hashnode editor.
# - Fails if the user is not a member of the team publication or
# if the publication is not a team publication
publishAs:
 
# Canonical URL of the post
# String | Optional
# What is a canonical URL? https://moz.com/learn/seo/canonicalization
# Ex: https://www.hashnode.com/post/top-4-react-ui-libraries-for-2023
# - This is equivalent to original URL option present in draft settings
# of a post in Hashnode editor.
# - This is useful when you want to publish a post that is already
# published on another platform.
canonical:
 
 
# Hide from Hashnode Community
# Boolean | Optional
# Default value: false // by default the post will be visible in the Hashnode's public feed.
# Ex: true
# - This is equivalent to "HIDE ARTICLE FROM HASHNODE FEED" option
# present in draft settings of a post in Hashnode editor.
# - This is useful when you want to publish a post to your publication
# only but hide it from the Hashnode's public feed.
# - You can also update a post to enable/disable this later.
hideFromHashnodeCommunity: True
 
# SEO Title
# String | Optional
# Ex: Top 4 React UI Libraries for 2023
# - This is equivalent to SEO TITLE option present in draft settings
# of a post in Hashnode editor.
# - You can also update a post to update this later.
seoTitle: GoLang - eine Reise von GoLand bis Writerside
 
# SEO Description
# String | Optional
# Ex: A curated list of the best React UI libraries for 2023
# - This is equivalent to SEO DESCRIPTION option present in
# draft settings of a post in Hashnode editor.
# - You can also update a post to update this later.
seoDescription:
 
# Disable comments for a post
# Boolean | Optional
# Default value: false // by default the comments will be enabled for the post.
# Ex: true
# - This is equivalent to "DISABLE COMMENTS" option present in
# draft settings of a post in Hashnode editor.
# - You can also update a post to enable/disable this later.
disableComments: True
 
# Slug of the series that you want your post to be a part of
# String | Optional
# Ex: react-series
# - This is equivalent to "ADD TO A SERIES" option present in
# draft settings of a post in Hashnode editor.
# - If invalid series is given, the post will not be added to any series.
# - You can update the post again to correct it later.
# - You can find series information from the series section in your publication dashboard.
# You can also edit the series information from there.
seriesSlug:
 
# Table of contents
# Boolean | Optional
# Default value: false // by default the table of contents will not be added to the post.
# Ex: true
# - This is equivalent to "GENERATE TABLE OF CONTENTS" option
# present in draft settings of a post in Hashnode editor.
# - If true, the table of contents will be added to the post.
# - You can also update a post to enable/disable this later.
enableToc: True
 
# Save post as draft
# Boolean | Optional
# Default value: false // by default the post will be published.
# Ex: true
# - If true, the post will be saved as a draft.
# - You can also update a draft with all the above attributes.
# - This draft will be available under Drafts section of the
# left sidebar in your publication dashboard.
# - Note: Once you remove this attribute, the post will be
# published and removed from drafts automatically.
# - This follows the same rules as a post create and update
# flow as well as the slug rules mentioned since
# beginning of this manual.
saveAsDraft: True
 
 
# Note:
# Newsletter and Post scheduling is NOT supported as of now.
 
---

## Go und GoLand - ein Dreamteam?

Dieser Beitrag soll meine Reise durch das `GoLand` beschreiben. Was habe ich gelernt und wieso bin ich so begeistert von `Go`?

### Go - eine kurze Einführung

[Go](https://go.dev), auch bekannt als Golang, ist eine Open-Source-Programmiersprache, die von Robert Griesemer, Rob Pike und Ken Thompson entwickelt wurde.
Sie ist eine statisch typisierte, kompilierte Sprache, die die gleichzeitige Ausführung mehrerer Prozesse unterstützt.
Dies wird durch die Verwendung von Kanälen und Goroutinen erreicht. Go verfügt über eine Garbage Collection, die die Speicherverwaltung selbst übernimmt und die verzögerte Ausführung von Funktionen ermöglicht.

> Als wir drei [Ken Thompson, Rob Pike und Robert Griesemer] anfingen, war es reine Forschung.
> Wir drei kamen zusammen und beschlossen, dass wir C++ hassen.
> [Gelächter] ... [Um auf Go zurückzukommen]
> wir begannen mit der Idee, dass alle drei von uns in jedes Feature der Sprache eingeweiht werden mussten, damit kein überflüssiger Müll in die Sprache eingebaut wurde.
> **Ken Thompson über die Entwicklung von Go**

Zur Einführung soll uns ein sehr einfaches Go Programm reichen:

```go
package main

import (
"fmt"
)

func main() {
fmt.Println("Hallo Welt! Das ist ein sehr einfaches Beispiel für ein Go Programm.")
}
```

In diesem Code ist `package main` der Beginn jedes Go-Programms und `func main()` ist die Funktion, von der aus die Programmausführung beginnt.
Die Funktion `fmt.Println` wird verwendet, um Text auf dem Bildschirm auszugeben.
Go unterstützt die Wiederverwendbarkeit von Code durch die Verwendung von Paketen.
Ein ausführbares Go-Programm sollte ein Paket namens main enthalten und die Programmausführung beginnt mit der Funktion namens main

Es ist wichtig zu beachten, dass Go einige Konzepte hat, die für Anfänger verwirrend sein können.
Beispielsweise gibt es in Go keine Klassen und Objekte, wie in anderen Programmiersprachen.
Stattdessen verwendet Go Strukturen und Methoden.
Darüber hinaus hat Go auch keine Ausnahmen.
Fehler werden in Go explizit als Rückgabewerte von Funktionen behandelt.
Gleichzeitig sind das auch die größten Stärken von Go.

Solltest du Go lernen möchtest, kannst du im [Lernbereich](https://go.dev/learn/) des Go Projekts starten.

<details>
<summary>Go: Eine Einführung in 130 Minuten</summary>
{{< youtube eqSjKOPt7dg >}}
</details>

### Wieso habe ich mich für Go entschieden?

{{< rawhtml >}}
<div style="display: flex; justify-content: center;">
<div style="text-align: center;">
<img src="/Goland/18.svg" height="200" />
</div>
</div>
{{< /rawhtml >}}

Ich habe angefangen, mit Python und der Django Bibliothek Webanwendungen zu erstellen.
Allerdings störte mich dabei immer, dass Python keine echte Sicherheit bietet, speziell die Variablen nicht auf den Inhalt überprüft werden, das Fehlermanagement nicht präzise ist und Python relativ langsam ist.
Zudem muss der Code immer mit einer Python Laufzeitumgebung ausgeführt werden. Dies macht es nahezu unmöglich, Code über verschiedene System, ohne Installation von Abhängigkeiten auszuführen.

Nach einiger Recherche auf Youtube und den üblichen Webseiten stellten sich 3 alternativen dar:

- JavaScript (bzw. Node.js / TypeScript)
- Javascript benötigt ebenfalls immer eine Laufzeitumgebung, daher war die Sprache schnell aus dem Rennen, auch wenn Webanwendungen häufig nicht portabel sein müssen
- Rust
- ist eine recht neue Programmiersprache, die von Mozilla entwickelt wurde und inzwischen von der Rust Foundation verwaltet und weiterentwickelt werden soll
- wird als Binärdatei (unter Windows an der Dateiendung `.exe` zu erkennen) ausgeliefert, daher ist keine Laufzeitumgebung erforderlich
- viele Entwickler empfinden die Sprache als sehr präzise und nach einer Einarbeitung einfach in der Bedienung
- nach einigen Tests schied Rust schnell aus, da viele kleine einfache Programme sehr viel Entwicklungsaufwand benötigen und von der sehr schnellen Ausführungsgeschwindigkeit kaum profitieren
- Go
- wird, wie Rust, als Binärdatei ausgeliefert, daher ist es möglich einmal geschriebenen Code auf diversen Systemen auszuführen
- die Flexibilität von Go ermöglicht es, Desktop Anwendungen, Webanwendungen und Terminalanwendugen zu erstellen
- das statische Typsystem ermöglicht es Fehler zu finden bevor man das Programm übersetzt und ausliefert
- Go ist für mich eine perfekte Mischung aus Rust und Python, daher fiel die Wahl nicht schwer

Nach einigen Testprogrammen war ich sofort sehr angetan von der Sprache. Im Folgenden zeige ich einige Beispiele, mit denen ich am Anfang experimentiert habe.

Die "the native web GmbH" stellte sich vor einiger Zeit eine ähnliche Frage, der Kanal hat in einer halben Stunde den Prozess erklärt, der für sie ebenfalls zu Go führte.

<details>
<summary>Warum grade Go? Darum! - 30 Minuten Laufzeit</summary>
{{< youtube wc5adu6396A >}}
</details>

#### Go-Search

{{< rawhtml >}}
<div style="display: flex; justify-content: center;">
<div style="text-align: center;">
<img src="/Goland/go-search.png" alt="Hugo build" height="200" />
</div>
</div>
{{< /rawhtml >}}


Zum Experimentieren mit einer neuen Programmiersprache bietet es sich an, einige klassische Algorithmen zu programmieren. Ich fing daher mit einigen Suchalgorithmen an. Der Code ist auf [Github](https://github.com/HRA42/Go-Search) zu sehen.

Ich möchte nun einige Ausschnitte zeigen und erklären, was mich an Go begeistert:

**Lineare Suche**:

Als Beispiel fangen wir mit dem leichtesten und einfach zu verstehenden Suchalgorithmus an, der linearen Suche.
Der Name sagt bereits aus, was passiert. Wir gehen jedes Element in der Liste durch und vergleichen des Elements mit dem gesuchten Element.

```go
func Search(arr []int, target int) bool {
for _, v := range arr {
if v == target {
return true
}
}
return false
}
```

An dem Code fallen uns einige Besonderheiten auf:

1. Großgeschriebener Funktionsname `Search`

- in Go werden öffentliche Funktionen (Funktionen die von anderen Pakten sichtbar sind) großgeschrieben
- Soll die Funktion privat (also nicht sichtbar) sein, wird der Funktionsname kleingeschrieben

1. Schleifenkonstruktion

- Go bietet nur die `for-Schleife` an, andere bekannte Strukturen wie `do-while` gibt es nicht
- der `range` Operator erzeugt 2 Variablen, den Index und den Inhalt der Liste
- der `_` bedeutet, dass mich in diesem Fall der Index nicht verfügbar sein soll, daher weisen wir nur den Inhalt der Variable `v` zu

1. Variablen mit und ohne Typangaben

- Go bietet 3 Möglichkeiten, Variablen zu erstellen:
- `var Name Type`
- `Name := Inhalt`
- Wenn kein Typ angegeben ist, wird der Typ automatisch anhand des Inhalts vergeben, bspw. wird eine Zeichenkette als Typ `String` zugewiesen oder die Zahl 1 als Ganzzahl
- `var Name = Inhalt`
- Wenn eine Funktion mit einem Parameter arbeiten soll, dann muss sowohl ein Name als auch ein Typ übergeben werden, dies führt dazu das alle Funktionen und Eigenschaften des Objekts für den Übersetzer verfügbar sind
- der Typ des Rückgabewerts muss ebenfalls angegeben werden

**Binäre Suche**:

Die binäre Suche funktioniert sehr ähnlich zur linearen Suche, daher solltest du selbst überlegen, was dieser Code bedeutet.
Die Erklärung findest du unter diesem Code zum Ausklappen.

```go
func Search(index []int, target int) bool {
low := 0
high := len(index) - 1
for low <= high {
mid := (low + high) / 2
switch {
case index[mid] < target:
low = mid + 1
case index[mid] > target:
high = mid - 1
default:
return true
}
}
return false
}
```

<details>
<summary>Erklärung des Codes</summary>

1. Für die binäre Suche muss die Liste vorsortiert sein
- Das ist sicherzustellen, indem die Liste durch einen Sortieralgorithmus sortiert wird
- Anschließend wird die Liste in 2 Teile geteilt und geschaut, ob das gesuchte Element in dem linken oder rechten Teil ist
- Das wird, solange gemacht bis in beiden Teilen nur noch eine Zahl vorhanden ist
- Sollte das Ziel nicht vorhanden sein wird sowohl die Schleife als auch der Switch Block beendet und `Falsch` zurückgegeben
2. Switch Case:
- `switch` ohne zusätzliche Variable sorgt dafür, dass in dem anschließenden `case` ein Vergleich stattfindet
- `default` ist der Fall, wenn keine der Bedingungen erfüllt ist
- in diesem Fall ist das Ziel der Suche gefunden

</details>

### GoLand - die Spielwiese für alle Go Entwickler

Der folgende Teil ist ein klein bisschen Werbung für Jetbrains Goland.
Ich werde weder von Jetbrains bezahlt noch habe ich andere Vorteile von diesem Artikel.
Ich möchte nur meine Begeisterung und Überzeugung darstellen.

[GoLand](https://www.jetbrains.com/go/) ist eine integrierte Entwicklungsumgebung (IDE, von englisch `Integrated Development Environment`), welche speziell für die Programmiersprache Go, die von JetBrains entwickelt wurde.
JetBrains ist bekannt für die Entwicklung von hochwertigen IDEs für verschiedene Programmiersprachen, darunter PyCharm für Python und IntelliJ für Java.
Einige der Hauptmerkmale von GoLand sind:

- **Integriertes Terminal**:
- GoLand bietet ein eingebautes Terminalfenster, in dem du Go-Befehle ausführen kannst. Es setzt korrekt den Go-Pfad und den Systempfad, um das Go-Binary und alles aus dem Go-Pfad-Verzeichnis einzuschließen
- **Laufkonfigurationen**:
- Mit GoLand kannst du Laufkonfigurationen erstellen und anpassen, die Umgebungsvariablen, Flags für den Go-Compiler und Flags für deine Anwendung enthalten können. Du kannst sogar eine Go-Remote-Konfiguration erstellen,
um Anwendungen zu debuggen, die auf Remote-Hosts oder in Containern laufen
- **Unterstützung für Tests und Benchmarks**:
- GoLand unterstützt das Ausführen von Projekten, Tests und Benchmarks direkt aus der IDE heraus
- **intelligente Code-Vervollständigung**:
- Wie andere JetBrains-IDEs bietet auch GoLand intelligente Code-Vervollständigung, die das Schreiben von Code beschleunigt und Fehler reduziert
- **automatische Formatierung und Einfügen von Abhängigkeiten**:
- GoLand bietet Funktionen zur automatischen Formatierung und zum Einfügen von Abhängigkeiten.
- Du kannst die IDE so konfigurieren, dass sie den Code in geänderten Dateien automatisch formatiert, wenn deine Änderungen gespeichert werden.
- Darüber hinaus kannst du die Option "Optimize imports" aktivieren, die sich in den Git- oder Commit-Einstellungen befindet, um automatisch fehlende Importe hinzuzufügen und ungenutzte zu entfernen

#### Erklärung an einem Beispiel Projekt

1. Ein neues Projekt erstellen
Goland unterstützt das Erstellen neuer Projekte mit einer vielfältigen Auswahl an Templates.
Das Hinzufügen von Plugins ermöglicht es diese Auswahl zu erweitern und auf deine Bedürfnisse anzupassen.


1. Projektübersicht
Ein neues Projekt enthält zum Start die wichtige `go.mod` Datei.
In dieser Datei werden alle Abhängigkeiten gesammelt.
Dies ermöglicht es die Abhängigkeiten eines Projekts sehr schnell zu überblicken und diese über die `go mod` Befehle zu verwalten.
`go mod tidy` beseitigt zum Beispiel ungenutzte Abhängigkeiten, sodass nur notwendige Abhängigkeiten gesammelt werden.
Goland führt diesen Befehl automatisch bei allen Änderungen der Abhängigkeiten aus. Ebenfalls werden Abhängigkeiten automatisch hinzugefügt.

1. Entwicklung
Goland formatiert den Code automatisch mit dem Befehl `go fmt`, sodass Code immer identisch aussieht und so deutlich besser
zu lesen und nachvollziehbarER ist. Abhängigkeiten werden automatisch verwaltet. Sowohl neue Abhängigkeiten können automatisch
importiert und über den Befehl `go get ...` heruntergeladen werden. Solltest du eine Abhängigkeit nicht mehr benötigen,
musst du nur den Code entfernen, Goland kümmert sich um den Rest. Somit ist die Entwicklung ein Kinderspiel.
Das Userinterface ist für jeden Anwendungsfall frei konfigurierbar. Du möchtest eine bestimmte Funktion nicht sehen? Kein Problem.
Auf den Bildern siehst du bereits eine Anpassung, die ich vorgenommen habe, die Farbgestaltung.
Ausführen von Code ist eine besondere Stärke aller Jetbrains Produkte. Für die meisten Anwendungsfälle wird die Konfiguration automatisch erzeugt.
Du möchtest einen automatischen Test durchführen? Kein Problem einfach die Datei mit den Tests öffnen und ausführen drücken.
Aufwendige Konfigurationen sind nicht mehr notwendig. Das Beispiel unten zeigt das Kommando zum Erzeugen dieses Blogs.
Konfigurationen können als Datei abgelegt werden, sodass alle Beteiligten das gleiche Kommando verwenden.

1. Künstliche Intelligenz
[**Jetbrains AI Assistent**](https://plugins.jetbrains.com/plugin/22282-ai-assistant)
stellt ein Chatfenster wie ChatGPT innerhalb von Goland zur Verfügung, allerdings kann Code direkt referenziert werden.
Das bietet der AI immer den korrekten Kontext, indem die Frage gestellt wird, wodurch schneller die passende Antwort generiert wird.
Die Antwort kann per Mausklick an die passende Stelle kopiert werden.
Das für mich beste Feature an Jetbrains AI ist jedoch die Möglichkeit, Änderungen direkt zu dokumentieren, wodurch der Entwicklungsprozess
mit Git für außenstehende nachvollziehbar wird und bei Bedarf auf ältere Versionen zurückgegriffen werden kann.

1. Dokumentation und Rechtschreib- & Grammatikprüfung
Jetbrains bietet mit Grazie Pro bzw. Writerside Plugins für die Dokumentation von Code an.
[**Grazie Pro**](https://plugins.jetbrains.com/plugin/16136-grazie-pro)
bietet die automatische Korrektur der meisten Rechtschreib- und Grammatikfehler an.
Egal ob ein Komma fehlt, ein Wort falsch geschrieben ist oder der Text einfach zu Umständlich formuliert wurde.
Du kannst das Plugin ganz nach deinen Wünschen und Vorlieben konfigurieren.
Zum Beispiel kannst du eine Prüfung für wiederholte Satzanfänge aktivieren, oder deaktivieren.
[**Writerside**](https://www.jetbrains.com/help/writerside/writerside-as-a-plugin.html)
ist ein relativ neues Projekt von Jetbrains, das eine volle Umgebung für Dokumentationen bereitstellt.
Ein Beispiel findest du für mein neustes Projekt [Go-TextType](https://go-texttype.postrausch.tech/readme.html).
Mit GitHub Actions und GitHub Pages ist die bereitstellung für jedes Projekt ein Kinderspiel.
Jede Änderung wird somit automatisch erzeugt und bereitgestellt. Für öffentliche Projekte ist dieser Service kostenlos.
Der eigentliche Text kann mit XML oder Markdown erstellt und formatiert werden. Textblöcke sind über IDs wiederverwendbar.

### Zusammenfassung
Go ist eine Sprache, die einfache Dinge, einfach macht.
Das gilt natürlich für das Zusammenspiel mit einem Produkt das für die Entwicklung von Go Programmen gedacht und gebaut wurde.
Sinnvolle automatismen gestalten die Entwicklung angenehm und erlauben Entwicklern bessere Programme zu schreiben,
da der Fokus auf das, was wirklich zählt, gerichtet werden kann, dass lösen von Problemen.

Natürlich kannst du auch `Visual Studio Code` verwenden, ein kostenloser Editor von Microsoft.
Es gibt natürlich diverse Erweiterungen für Go, allerdings wird es nie eine Erfahrung, die von Grund auf für die speziellen Vorteile von Go gebaut wurde.

Allerdings muss man zum Schluss erwähnen, dass JetBrains einen stolzen Preis für dieses Paket aufruft.
99 € sind ein stolzer Preis für einen Text-Editor mit vielen Vorteilen, allerdings sollte man für diesen Preis sehr genau überlegen, ob man wirklich alle Funktionen benötigt.
Möchte man alle Produkte von JetBrains nutzen (etwa eine Funktion zum gemeinsamen Programmieren) steigt der Preis auf stolze 289 € pro Jahr.
Für Unternehmen beträgt der Preis von Goland 249 € pro Lizenz und für alle Produkte 779 €.
Goland bietet für alle Interessierten eine 30-tägige kostenlose Testversion, so kannst du feststellen, ob es das passende Produkt für dich ist.
Unternehmen erhalten eine 60-tägige kostenlose Testversion mit unlimitierten Lizenzen.

Weitere Informationen findest du auf der [Produkt Seite von Goland](https://www.jetbrains.com/go/).