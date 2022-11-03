# Git uf Thurgauerisch

S tägliche Gelaber i Programmierer-Teams, wo `git` (übersetzt: `Depp` oder `Totsch`) bruuched, isch s feinste Denglisch.
_"Chasch du rasch pulle"_ oder _"Hesch du scho pusht"_ sind nur zwei vo de Konstruktione wo so komisch töned.

Git uf Thurgauerisch hilft da!

## Vorschläg

Da gsehsch zwei Tabelle mit Vorschläg wo im alltäglich helfe cha.

| Verb        | Jetzige Uusdruck | Vorschlag       |
| ----------- | ---------------- | --------------- |
| init        | initten          | ahfange         |
| add         | adden            | dezuetue        |
| blame       | blamen           | beschuldige     |
| pull        | pullen           | züche           |
| push        | pushen           | drucke          |
| clone       | clonen           | nahmache        |
| fetch       | fetchen          | hole            |
| branch      | branchen         | abbüge          |
| commit      | commiten         | iihbueche       |
| rebase      | rebasen          | uf Wiifelde gah |
| diff        | diffen           | vergliiche      |
| merge       | mergen           | zemmetue        |
| fork        | forken           | abbüge          |
| stash       | stashen          | versorge        |
| tag         | taggen           | markiere        |
| cherry-pick | cherry-picken    | Öpfel pflücke   |
| checkout    | checkouten       | usbueche        |
| squash      | squashen         | quätsche        |

Da no es paar wiiteri (üsserst ernsti):

| Substantiv    | Jetzige Uusdruck | Vorschlag           |
| ------------- | ---------------- | ------------------- |
| git           | git              | Totsch              |
| github        | github           | Totschzentrum       |
| gitlab        | gitlab           | Totschlabor         |
| gitea         | gitea            | Totschtee           |
| blame         | blame            | Beschuldigung       |
| bitbucket     | bitbucket        | Gebiss-Chübel       |
| repository    | repo             | Schopf              |
| branch        | branch           | Zwiigli             |
| commit        | commit           | Iihbuechig          |
| log           | log              | Tagebuech           |
| pull request  | pull request     | Ziehbegehre         |
| merge request | merge request    | Ahtrag zum zemmetue |
| stash         | stash            | Versteck            |
| status        | status           | Zuestand            |
| tag           | tag              | Markierig           |
| origin        | origin           | Ursprung            |
| master        | master           | Meister             |
| main          | main             | Haupt               |

## Biispiel

    - Chach du s Zwiigli, wo ich grad gmacht ha, züche und zum Totschzentrum drucke?

    - Für das han ich en neue Schopf gmacht, tue's nahmache und nimm dir s Entwickler-Zwiigli.

    - Nei, druck das grad zum Meister im Ursprung!

    - Du chasch i de Deppe-Beschuldigung gseh, wer das gmacht het.

    - Ich ha grad abboge und d Änderige us mim Versteck übergeh.

    - Mach es Ziehbegehre, wenn du mitem Zemmetue fertig bisch!

    - Am beste pflücked mir d Öpfel usem Hauptzwiigli use.

    - Büüged Sie's ab im Totschzentrum!

    - Wenn'd fertig bisch, chasch's Ziehbegehre sofort quätsche und zemmetue.

    - Im Totsch-Tagebuech chasch nahlese, wer zletzt e quätschti Übergab zemme tue het.

## Totsch uf Thurgauerisch bruuche

Die wo de nächst Schritt mache wönd, chöned die Ahleitig bruche, wo de Totsch uf Thurgauerisch i ihri Konsole bringt. Will de Totsch kei Umluut zuelaht, müend mir i de einzelne Befehl leider druf verzichte. Mach die Änderige i dis `~/.gitconfig` ine:

    git config --global alias.ahfange init
    git config --global alias.machnah clone
    git config --global alias.zieh pull
    git config --global alias.tuedezue add
    git config --global alias.druck push
    git config --global alias.pfudle 'push --force'
    git config --global alias.zwiigli branch
    git config --global alias.zwiigab branch
    git config --global alias.buechiih commit
    git config --global alias.gahufwiifelde rebase
    git config --global alias.unterscheide diff
    git config --global alias.tuezemme merge
    git config --global alias.versorg stash
    git config --global alias.markier tag
    git config --global alias.buechuus checkout
    git config --global alias.tagebuech log
    git config --global alias.zuestand status
    git config --global alias.beschuldige blame

Und wenn's die Ziile no i dis `~/.bashrc` (oder wie die Datei au immer heisst uf dim Betriebssystem) tuesch:

    alias totsch='git'
https://github.com/danielauener/git-auf-deutsch.git
