# Git uff Hessisch

Die tägliche Kommunikation in de deutsche Endwicklerteams, die `git`
(üwwersetzt: `Depp`) verwende, ist meist des feinste Denglish.
_"Kannst du bitte pullen"_ oder _"Hast du gepusht"_ sei nur zwo
der seltsamme Konstruktione.

Git uff Hessisch hilft dir gern aus!

## Vorschläche

Es folche zwo Tabelle mit Vorschläche für de tägliche Gebrauch.

| Verb        | Aktueller Gebrauch | Vorschlag             |
|-------------|--------------------|-----------------------|
| init        | initten            | uffmache              |
| add         | adden              | hinzudou              |
| blame       | blamen             | beschuldiche          |
| pull        | pullen             | zeihe                 |
| push        | pushen             | schiewe               |
| clone       | clonen             | nochmache             |
| fetch       | fetchen            | hölln                 |
| branch      | branchen           | abzweiche             |
| commit      | commiten           | abuche                |
| rebase      | rebasen            | (neu) erden           |
| diff        | diffen             | unnerscheide          |
| merge       | mergen             | zusammeschmeiße       |
| fork        | forken             | abzweiche             |
| stash       | stashen            | verstaue              |
| tag         | taggen             | markiern              |
| cherry-pick | cherry-picken      | Rosine nauspicke      |
| checkout    | checkouten         | ausbuche              |
| squash      | squashen           | quetsche              |

Hier noch einige (zum Teil nicht ganz ernste)

| Substantiv    | Aktueller Gebrauch | Vorschlag                  |
|---------------|--------------------|----------------------------|
| git           | git                | Depp                       |
| github        | github             | Deppendrehkreuz            |
| gitlab        | gitlab             | Deppenlabor                |
| gitea         | gitea              | Deppentee                  |
| blame         | blame              | Beschuldichung             |
| bitbucket     | bitbucket          | Gebissaamer                |
| repository    | repo               | Schuppen                   |
| branch        | branch             | Zweich                     |
| commit        | commit             | Aabuchung                  |
| log           | log                | Tagebuch                   |
| pull request  | pull request       | Ziehbegehren               |
| merge request | merge request      | Antrag auf Zusammenführung |
| stash         | stash              | Verstegg                   |
| status        | status             | Zustand                    |
| tag           | tag                | Markierung                 |
| origin        | origin             | Ursprung                   |
| master        | master             | Meister                    |
| main          | main               | Haupt                      |

## Beispiele

    - Kannst du den Zweig, den ich gerade umgeschrieben hab, ziehen und zum Deppendrehkreuz drücken?

    - Dafür habe ich ein neues Depot eröffnet, mach sie nach und nimm dir den Entwicklungszweig.

    - Nein, drücke das gleich zum Meister im Ursprung!
    
    - Du kannst in der Deppenbeschuldigung sehen, wer das geändert hat.

    - Ich hab gerade abgezweigt und die Änderungen aus meinem Versteck übergeben.

    - Mach ein Ziehbegehren, wenn du mit der Vereinigung fertig bist!

    - Am besten wir picken uns die Rosinen aus dem Hauptzweig heraus.

    - Gabeln Sie auf Deppendrehkreuz!
    
    - Wenn du fertig bist, dann kannst du das Ziehbegehren sofort quetschen und zusammenführen.

## Depp auf Deutsch anwenden

Wer den nächsten Schritt machen will, hier eine Anleitung, die Depp auf Deutsch in Deine Konsole bringt. Da Depp keine Umlaute zulässt, müssen wir in den Befehlen leider darauf verzichten. Nimm folgende Änderungen in deiner `~/.gitconfig` vor:

    git config --global alias.eroeffne init
    git config --global alias.machnach clone
    git config --global alias.zieh pull
    git config --global alias.fueghinzu add
    git config --global alias.drueck push
    git config --global alias.pfusch 'push --force'
    git config --global alias.zweig branch
    git config --global alias.verzweige branch
    git config --global alias.buche-ein commit
    git config --global alias.erde rebase
    git config --global alias.unterscheide diff
    git config --global alias.vereinige merge
    git config --global alias.bunkere stash
    git config --global alias.markiere tag
    git config --global alias.buche-aus checkout
    git config --global alias.tagebuch log
    git config --global alias.zustand status
    git config --global alias.beschuldige blame

Und füge die folgende Zeile zu deiner `~/.bashrc` (oder das Äquivalent auf deinem Betriebssystem) hinzu:

    alias depp=git
https://github.com/danielauener/git-auf-deutsch.git
