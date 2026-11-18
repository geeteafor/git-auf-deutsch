# Git auf Deutsch

Das täjliche Sabbeln in Berliner Kellerkind-Buden, die `git`
(übersetzt: `Schwachkopp`) nutzen tun, ist so’n Denglish meiste Zeet.
_"Kannst du bitte pullen"_ oder _"Hast du gepusht"_ hören sich ei’fach net jut an.

Git auf Berlinernisch machet jut!

## Vorschläge

Hier kommen nu zwo Tabellen mit’n paar Vorschläjen für jeden Tach.

| Verb        | Aktueller Jebrauch | Uff Berlinerisch      |
|-------------|--------------------|-----------------------|
| init        | initten            | uffmachen             |
| add         | adden              | dazupacken            |
| blame       | blamen             | verpfeifen            |
| pull        | pullen             | rannholen             |
| push        | pushen             | rueberjeben           |
| clone       | clonen             | nachaeffen            |
| fetch       | fetchen            | anschaffen            |
| branch      | branchen           | abzweijen             |
| commit      | commiten           | festkloppen           |
| rebase      | rebasen            | (neu) uffsetzen       |
| diff        | diffen             | abjleichen            |
| merge       | mergen             | zusammenschustern     |
| fork        | forken             | jabeln                |
| stash       | stashen            | wechpacken            |
| tag         | taggen             | feddisch (machen)     |
| cherry-pick | cherry-picken      | Rosinen russpicken    |
| checkout    | auschecken         | rüberjehen            |
| squash      | squashen           | zusammenmatschen      |

Hier komm' noch'n paar Dinger (nich allet janz ernst jemeent, wa!).

| Substantiv    | Aktueller Jebrauch | Uff Berlinerisch           |
|---------------|--------------------|----------------------------|
| git           | git                | Schwachkopp                |
| github        | github             | Schwachkopphausen          |
| gitlab        | gitlab             | Schwachkoppbude            |
| gitea         | gitea              | Schwachkopptee             |
| blame         | blame              | Anschiss                   |
| bitbucket     | bitbucket          | Kaukübel                   |
| repository    | repo               | Kackfass                   |
| branch        | branch             | Zweij                      |
| commit        | commit             | Festjeklopptet             |
| log           | log                | Kladde                     |
| pull request  | pull request       | Wunsch uff n’ Zuch         |
| merge request | merge request      | Wunsch uff nh Schusterung  |
| stash         | stash              | Messiebude                 |
| status        | status             | Sachstand                  |
| tag           | tag                | Schildchen                 |
| origin        | origin             | Herkunft                   |
| master        | master             | Obermacker                 |
| main          | main               | Hauptdingens               |

## Beispiele

    - Kannst du den Zweig, den ich gerade umgeschrieben hab, ziehen und zum Deppenzentrum drücken?

    - Dafür habe ich ein neues Depot eröffnet, mach sie nach und nimm dir den Entwicklungszweig.

    - Nein, drücke das gleich zum Meister im Ursprung!
    
    - Du kannst in der Deppenbeschuldigung sehen, wer das geändert hat.

    - Ich hab gerade abgezweigt und die Änderungen aus meinem Versteck übergeben.

    - Mach ein Ziehbegehren, wenn du mit der Vereinigung fertig bist!

    - Am besten wir picken uns die Rosinen aus dem Hauptzweig heraus.

    - Gabeln Sie im Deppenzentrum!
    
    - Wenn du fertig bist, dann kannst du das Ziehbegehren sofort quetschen und zusammenführen.
    
    - Im Deppentagebuch kannst du nachlesen, wer zuletzt eine gequetschte Einbuchung zusammengeführt hat.

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
