# Allocation Algorithm

Dieses Projekt behandelt einen konzipierten und umgesetzten Zuordnungsalgorithmus für das Projektstudium der Fakultät Digitale Medien. In der Vergangenheit war es so, dass die Semestersprecher der einzelnen Studiengänge die Projektwünsche ihrer Kommilitonen und Kommilitoninnen gesammelt und sie später den einzelnen Projekten zugeordnet haben.
Dabei konnten nicht immer alle Wünsche der Studierenden erfüllt werden, wodurch oft Studierende Projekten zugeordnet wurden, zu denen ihnen die passenden Fähigkeiten oder das Interesse fehlten. Um hierbei eine bessere Zuordnung gewährleisten zu können, wurde ein Algorithmus entwickelt, der auf Basis der eigenen Job-Wünschen innerhalb des Projekts, sowie dem Studiengang und der Priorität des Studierenden die richtige Zuordnung treffen soll.

Der Algorithmus entstand dabei als Abgabe für die Wahlpflicht Veranstaltung des Fachdidaktischen Praktikums für Mathe 2.


## Konzeption

<img src="./Konzept des Algorithmus.PNG"/>

## Vorbereitung

Bevor der Algorithmus gestartet werden kann, muss sowohl in der ```InitStudents()```, ```InitInitiators()``` und ```InitProjects()``` die jeweiligen Studierenden, Projektinitiatoren und Projekte konfiguriert werden.

Im Anschluss kann der Algorithmus gestartet werden.

## Algorithmus starten

Über den Befehl ```dotnet run``` kann nun der Algorithmus gestartet werden. Im Anschluss gibt er aus, in welchem Projekt die jeweiligen Studierenden gelandet sind und wie zufrieden sie mit der Zuordnung des Projekts sein können.

## Ausblick

Es ist geplant, diesen Algorithmus über eine Webseite zu initierien und zu starten.

