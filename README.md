# Spieler_Manager

## Motivation: 
Die Idee für unser Projekt entstand aus unserer gemeinsamen Begeisterung für Fußball – insbesondere im Kontext der Champions League, die während des Projektzeitraums stattfand. Uns war es wichtig, ein praxisnahes Thema zu wählen, mit dem wir uns identifizieren können und das gleichzeitig Spaß bei der Umsetzung bringt.







## Beschreibung unseres Projektes:
Unsere Anwendung „Champions League Spieler-Manager“ ist ein Java-basiertes Desktop-Programm mit grafischer Benutzeroberfläche, das Fußballfans die Möglichkeit bietet, ihre Lieblingsspieler zu verwalten und auszuwerten. Die Anwendung wurde nach dem **Model-View-Controller** (MVC)-Prinzip aufgebaut, um eine klare Trennung von Daten, Darstellung und Logik zu gewährleisten.
Im **Model** befindet sich die Klasse Spieler, welche die Datenstruktur für jeden einzelnen Spieler definiert. Sie speichert Attribute wie Name, Position, Tore, Marktwert und ob der Spieler Stammspieler ist. Zudem beinhaltet das Modell auch die Berechnung des durchschnittlichen Marktwerts für eine Liste von Spielern. Dadurch ist die Geschäftslogik klar vom Rest der Anwendung getrennt.
Die **View** wird durch die grafische Benutzeroberfläche (SpielerManagerGUI) repräsentiert. Sie besteht aus Eingabefeldern, Auswahlmenüs, einer Checkbox zur Filterung und einer scrollbaren Liste zur Anzeige aller Spieler. Außerdem gibt es Schaltflächen zum Speichern, Löschen und Auswerten, die durch klare Layouts logisch angeordnet sind. Die Benutzeroberfläche ist intuitiv gestaltet, sodass Nutzer einfach mit dem Programm interagieren können.
Der **Controller** ist ebenfalls innerhalb der SpielerManagerGUI-Klasse angesiedelt und verbindet Eingaben der Nutzer mit der Logik des Programms. Er sorgt z. B. dafür, dass eingegebene Daten validiert und korrekt gespeichert oder gelöscht werden, oder dass die Liste der Spieler basierend auf Filterkriterien aktualisiert wird. Auch die Ereignisbehandlung (z. B. bei Button-Klicks) wird hier gesteuert.
Funktional können Nutzer neue Spieler anlegen, indem sie grundlegende Informationen wie Name, Position, Tore, Marktwert sowie den Stammspieler-Status eingeben. Alle Eingaben werden dabei auf ihre Gültigkeit geprüft – etwa dürfen Namen nur Buchstaben enthalten und Marktwerte müssen positiv sein. Gespeicherte Spieler erscheinen in einer Liste, die sich dynamisch filtern lässt – etwa nach Position oder Stammspielerstatus. Eine besondere Funktion ist die Berechnung des durchschnittlichen Marktwerts für die aktuell angezeigte (gefilterte) Spielerliste. Außerdem können Spieler per Auswahl und Klick gelöscht werden.








## Unser Video:
https://www.dropbox.com/scl/fi/93b3j8ayg66eam3p9sw9d/Protech-Abgabe-Video-Derman-u-Emre.mov?rlkey=zengfv0osefnsojpwhdfadzth&e=1&st=5fi2h5f1&dl=0

