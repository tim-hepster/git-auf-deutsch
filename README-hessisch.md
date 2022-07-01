# Git uff Hessisch

Die tächliche Kommunikation in deutsche Endwicklerteams, die `git`
(üwwersetzt: `Depp`) verwende, ist meist des feinste Denglish.
_"Kannste bidde pullen"_ oder _"Haste gepusht"_ sei nur zwo
der seltsame Konstruktione.

Git uff Hessisch hilft dir gern aus!

## Empfehlunge

Es folche zwo Tabelle mit Vorschläche fürn tägliche Gebrauch.

| Verb        | Aktueller Gebrauch | Vorschlag             |
|-------------|--------------------|-----------------------|
| init        | initten            | uffmache              |
| add         | adden              | dazudou               |
| blame       | blamen             | beschuldiche          |
| pull        | pullen             | zeihe                 |
| push        | pushen             | schiewe               |
| clone       | clonen             | nochmache             |
| fetch       | fetchen            | hölln                 |
| branch      | branchen           | abzweiche             |
| commit      | commiten           | aabuche               |
| rebase      | rebasen            | (nau) erde            |
| diff        | diffen             | unnerscheide          |
| merge       | mergen             | zusammeschmeiße       |
| fork        | forken             | gawweln               |
| stash       | stashen            | verstaue              |
| tag         | taggen             | markiern              |
| cherry-pick | cherry-picken      | Rosine nauspicke      |
| checkout    | checkouten         | ausbuche              |
| squash      | squashen           | quetsche              |

Hier noch einige (zum Teil nicht ganz ernste)

| Substantiv    | Aktueller Gebrauch | Vorschlag                  |
|---------------|--------------------|----------------------------|
| git           | git                | Depp                       |
| github        | github             | Deppedrehkreuz             |
| gitlab        | gitlab             | Deppelabor                 |
| gitea         | gitea              | Deppetee                   |
| blame         | blame              | Beschuldichung             |
| bitbucket     | bitbucket          | Gebissaamer                |
| repository    | repo               | Schuppen                   |
| branch        | branch             | Zweich                     |
| commit        | commit             | Aabuchung                  |
| log           | log                | Tagebuch                   |
| pull request  | pull request       | Ziehbegehre                |
| merge request | merge request      | Antrach uff Zusammeführung |
| stash         | stash              | Verstegg                   |
| status        | status             | Zustand                    |
| tag           | tag                | Markierung                 |
| origin        | origin             | Ursprung                   |
| master        | master             | Maaster                    |
| main          | main               | Haupt                      |

## Beispiele

    - Kannste den Zweich, den ich grad umgeschriwwe hen, zeihe un zum Deppedrehkreuz schiewe?

    - Dafür hu ich n naue Schuppe uffgemacht, mach dir den amo nach und nimm dir n Entwicklungszweich.

    - Naa, schieb des gleich uffn Maaster im Ursprung!
    
    - Du kannst in de Deppenbeschuldichung sehe, wer da dro rumgepfuscht hat.

    - Ich hu grad abgezweicht un die Ännerunge aus meim Versteck üwwergewe.

    - Mach n Ziehbegehren, wenn du mim zusammeschmeiße fertig seist!

    - De beste wärsch wir picke uns die Rosine ausm Hauptzweich naus.

    - Mache se sich ne Gawwel uffm Deppendrehkreuz!
    
    - Wenn de fertich seist, dann kannste des Ziehbegehren direkt quetsche un zusammeschmeiße.

## Depp uff Hessisch anwende

Wer n nächste Schritt waage will, hier ne Anleidung, die Depp uff Hessisch in dei Konsole bringt. Weil Depp kaane Umlaute zulässt, müsse mir in de Befehle leider druf verzichte. Nimm folchende Ännerunge in daaner `~/.gitconfig` vor:

    git config --global alias.machuff init
    git config --global alias.machnach clone
    git config --global alias.zeih pull
    git config --global alias.dazudou add
    git config --global alias.schieb push
    git config --global alias.pfusch 'push --force'
    git config --global alias.zweich branch
    git config --global alias.verzweiche branch
    git config --global alias.aabuche commit
    git config --global alias.erde rebase
    git config --global alias.unnerscheide diff
    git config --global alias.schmeisszusamme merge
    git config --global alias.verstegge stash
    git config --global alias.markiere tag
    git config --global alias.buche-aus checkout
    git config --global alias.tagebuch log
    git config --global alias.zustand status
    git config --global alias.beschuldiche blame

Und füche de folchende Zeile zu daaner `~/.bashrc` (oder was aach immer uff deinem Rechner läuft) hinzu:

    alias depp=git
https://github.com/danielauener/git-auf-deutsch.git
