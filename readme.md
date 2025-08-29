# Lernperiode 11

22.8 bis 26.9.2024

## Grob-Planung

1. Erklären Sie Ihre Projekt-Idee in einem Satz, als müssen Sie einen Investor davon überzeugen.
Ich will meine bestehendes [WPF-Projekt](https://github.com/seakyy/CasinoWPF) in eine Mobile Applikation umwandeln.

2. Erklären Sie, welche technischen Herausforderungen Sie in Ihrem Projekt erwarten.
Ich denke mal die MVVM-Struktur, in die passende Mobile Architektur umzuwandeln.

3. Beschreiben Sie, welche nicht-technischen Aspekte Sie in diesem Projekt besonders üben möchten.
Schritt für Schritt Dokumentation, falls später andere Devs es verbessern möchen.

4. Wie unterscheidet sich dieses Projekt von Ihrem Projekt in 335; und wo ergänzen sich diese Projekte?
Beide werden hoffentlich als Appliaktionen im PLay Store o.ä. auffindbar sein und ohne verheerende Bugs funktionieren. Die Funktionalität der Appliaktionen sollte sich nicht veränder.
Die Unterschiede der Applikationen liegen im Thema der App. Bei der Mobilen Version meiner CasinoWPF werde ich lernen, wie man eine MVVM strukturierte Applikation in eine mobile Appliaktion umwandelt. Da es sich um ein längeres bstehendes Projekt handelt, kann ich das gleiche schlecht zwei mal machen.


### Gedankengang, vor dem Start des Projekts
Da meine [CasinoWPF-App](https://github.com/seakyy/CasinoWPF) das [.NET Framework](https://learn.microsoft.com/en-us/dotnet/framework/) nutzt, kann ich es nicht umwandeln zu einer mobilen App. Mein erster Gedanke wäre, mein ganzes Projekt auf ein [.NET MAUI - Framework](https://learn.microsoft.com/en-us/dotnet/maui/?view=net-maui-9.0) umzustellen. Somit spare ich mir viel Ziet, da ich einen grossen Teil meines Codes wiederverwenden kann und nicht zu viel Zeit verschwende die gleichen Funktionen ein zweites mal neu zu programmieren. 

Ich muss unbedingt auf ein Responsive UI achten, da es verschiedene Bildschirm-Grössen gibt, sei es Smartphone oder Tablets. Ich muss auch im Hinterkopf behalten, dass wir (* Im Sinne von; Wir Handy- und Tablet-User) keinen Cursor haben, sonern alles mit dem Finger/Stift steuern.

Die Hardware-Zugriffe muss ich auch berücksichtigen, da diese das User-Experience deutlich verbessern könnten (Z.B.: Durch Vibrationen bei Gewinn).

## 22.8

- [ ] Überblick verschaffen und [Issue 1](https://github.com/seakyy/Mobile-Casino/issues/1) und [Issue 2](https://github.com/seakyy/Mobile-Casino/issues/2) erstellen.
- [ ] Setup für .NET MAUI Framework einrichten.

✍️ Heute habe ich... (50-100 Wörter)

Heute habe ich meine zwei ersten Arbeitspackete bzw Issues verfasst. Damit ich das nächste mal direkt mit dem Implementieren des alten Codes anfangen kann, musste ich zuerst meine Entwicklungsumgebung ändern. Um die passende Entwicklungsumgebung zu haben musste ich zuerst den Visual Studio Installer öffnen und das Packet installieren was mir die Mobile Entwicklung mittels .NET MAUI ermöglicht. Während sich das Packet installierte habe ich angefangen mir Gedanken zu den Anforderungen zu machen. Da responsive User-Interface ein (sehr) wichtiger Punkt ist bei mobile Apps habe ich mir überlegt was für Prototypen ich brauche (Siehe Arbeitspackete **29.8**). Als nächstes mache ich die Analyse meines vorherigen Code und sortiere es in [drei Kategorien](https://github.com/seakyy/Mobile-Casino/issues/1#issuecomment-3214607371) ein, somit weiss ich wo ich am meisten Zeit einplanen muss.     

Für Herr Colic: Sparen Sie sich Zeit, schauen Sie sich einfach die Analyse an: [Link zum Kommentar](https://github.com/seakyy/Mobile-Casino/issues/1#issuecomment-3214607371)

## 29.8

- [ ] Designing Prototype 1 - smartphone vertical layout
- [ ] Designing Prototype 2 - smartphone horizontal layout
- [ ] Designing Prototype 3 - tablet vertical layout 
- [ ] Designing Prototype 4 - tablet horizontal layout

✍️ Heute habe ich... (50-100 Wörter)
Heute habe ich die vorgesehene Arbeitspackete für diesen Tag nicht geschafft, da ich zuerst sicherstellen musste, dass ich mein [Ursprungsprojekt](https://github.com/seakyy/CasinoWPF) fertig bringe, damit ich viel Code übertragen kann (XAML-Dateien). Ich habe die [Version 1.3](https://github.com/seakyy/CasinoWPF/releases/tag/release) released, die jetzt neu viele funktionale Issues gepatched hat und neue Statistiken mit sich bringt. Deshalb veschiebe ich jetzt die alten vorgesehene Arbeitspackete auf nächste Woche, aber diesmal verfasse ich sie in User-Stories.


## 5.9
- [ ] Als Smartphone-User möchte ich das Mobile-Casino im Hochformat spielen, damit ich es bequem bedienen kann.
- [ ] Als Smartphone-User möchte ich das Mobile-Casino im Querformat spielen, damit ich eine breitere Spielübersicht habe.
- [ ] Als Tablet-User möchte ich das Mobile-Casino im Hochformat spielen, damit die Bedienung auf einem grossen Bildschirm angenehm ist.
- [ ] Als Tablet-User möchte ich das Mobile-Casino im Querformat spielen, um den grossen Bildschirm optimal zu nutzen.


