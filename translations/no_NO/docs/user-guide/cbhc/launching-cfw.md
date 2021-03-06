# CBHC

## Bruke CFW {docsify-ignore}

Nå som du har en NAND backup i tilfelle noe går galt senere, kan du kjøre CFW på systemet ditt.

I motsetning til systemer som DSi, Wii eller 3DS, er Wii U CFW midlertidig. Dette betyr at så snart systemet starter på nytt, vil du miste CFW og må følge disse instruksjonene igjen. Det trenger du ikke ved å installere CBHC på en Haxchi CFW installasjon.

!> Installere CBHC feil kan "bricke" Wii U konsollen din. Sørg for å følge "CBHC reglene" når man installerer CBHC: <br>- DS spillet må være legitimt installert fra eShop <br>- Ikke formater systemet mens CBHC er installert <br>- Ikke slett brukerkontoen som kjøpte DS VC spillet <br>- Ikke re-installer det samme spillet med WUP Installer eller eShop <br>- Ikke installer Haxchi over CBHC <br>- Ikke slett DS Virtual Console spillet uten å [avinstallere CBHC first](../uninstall-cbhc) <br>- Ikke flytt DS Virtual Console spillet til en USB-enhet

!> Hvis du bryter en av reglene ovenfor, vil du "bricke" konsollen.

### Instruksjoner

1. Ta SD-kortet ut av PCen og sett det inn i Wii U konsollen.
1. Hvis du ikke har gjort det enda, last ned DS VC spillet du valgte fra eShop.
1. Start Homebrew Launcher på Wii U konsollen din som [forklart tidligere](browser-exploit).
1. Kjør Haxchi appen.
1. Bruk D-padden til å navigere markøren til spillet du ønsker å installere Haxchi over og trykk på A knappen for å installere den.
1. Når installasjonen er ferdig, vil konsollen gå tilbake til Wii U menyen. Der vil du se spillet ditt erstattet med et Haxchi ikon.
1. Kjør Haxchi. Dette vil starte konsollen på nytt og aktivere CFW.
1. Kjør Haxchi igjen og hold A knappen mens den starter. Dette vil sende deg til Homebrew Launcher.
1. I Homebrew Launcher, kjør CBHC appen.
1. Bruk D-padden for å flytte markøren til spillet du installerte Haxchi over og trykk på A knappen for å installere CBHC.
1. Når installasjonen er ferdig, vil konsollen gå tilbake til Wii U menyen.
1. Start konsollen på nytt. Hvis CBHC er installert riktig, bør du se en ny oppstartsmeny.
1. Bruk D-padden for å flytte til `Autoboot: Disabled` og trykk på A knappen helt til det står `Autoboot: System Menu`.
1. Bruk D-padden for å flytte til `Boot system menu` og trykk på A-knappen. Dette vil åpne Wii U menyen med CFW aktivert.
1. Konsollen din kommer nå til å automatisk være i CFW etter oppstart.
1. Du kan nå koble til eventuelle USB-enheter du hadde tilkoblet, før du startet guiden.