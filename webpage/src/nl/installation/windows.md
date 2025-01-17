# Installatie op Microsoft Windows™

Download the latest **Windows archive** from [QOwnNotes Releases on GitHub](https://github.com/pbek/QOwnNotes/releases) (look for a file called `QOwnNotes.zip`) and unzip it to anywhere you like. Er is geen installatie nodig!

::: warning
Als u de **automatic updater** wilt gebruiken, zorg er dan voor dat u deze uitpakt op een plaats waar uw gebruikersaccount schrijftoegang tot heeft. By default, your user account most likely **doesn't have write access** to places like `C:\Program Files (x86)` or `C:\Program Files`.
:::

U kunt dan direct `QOwnNotes.exe` starten vanuit uw `QOwnNotes` -map, er is geen installatie vereist.

### Portable mode

Gebruik `QOwnNotesPortable.bat` om QOwnNotes in **draagbare modus** uit te voeren, waar alles (inclusief uw notities) alleen wordt opgeslagen in uw map `QOwnNotes`.

::: tip
U hebt het draagbare modus niet nodig als u gewoon geen beheerdersrechten voor uw computer hebt. QOwnNotes hoeft niet te worden geïnstalleerd!
:::

## Windows XP

Qt heeft de ondersteuning voor Windows XP met versie 5.8 laten vallen, maar QOwnNotes is nu ook gebouwd met Qt 5.7 zodat Windows XP-gebruikers het nog steeds kunnen gebruiken.

Je moet het ZIP-bestand zelf downloaden van [AppVeyor](https://ci.appveyor.com/project/pbek/qownnotes/build/artifacts) en het uitpakken in een map naar keuze.

U kunt dan direct `QOwnNotes.exe` uitvoeren vanuit die map, er is geen installatie vereist.

::: tip
Info
Het automatische updatemechanisme werkt niet met de AppVeyor-build voor Windows XP!
U zult zelf nieuwe releases moeten downloaden.
:::

## Chocolatey

Er is een door de gemeenschap onderhouden pakket van QOwnNotes op [Chocolatey](https://chocolatey.org/packages/qownnotes/).

U kunt het installeren met:

```shell
choco install qownnotes
```

## Scoop

Er is een [door de gemeenschap onderhouden pakket van QOwnNotes](https://github.com/ScoopInstaller/Extras/blob/master/bucket/qownnotes.json) bij [Scoop](https://scoop.sh/). Als u de Extras-bucket toevoegt, kunt u deze gebruiken om QOwnNotes in draagbare modus te installeren.

```shell
scoop bucket add extras
scoop update
scoop install qownnotes
```
