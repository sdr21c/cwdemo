# cwdemo

Dit is een morsedecoder, speciaal bedoeld voor demonstraties aan kinderen.

De app is nog in ontwikkeling. Binnenkort wordt deze in de praktijk getest op de Makers Days in Eindhoven. Zie https://makerdays.nl/maker/hamradiolab-eindhoven-de-makers-van-de-ether/

## Support

Op de app wordt geen support gegeven.

## Disclaimer

Gebruik van de app is op eigen verantwoording.

## Muis als interface

Seinen kan met een seinsleutel (straight key) die aangesloten is op de contacten van de linkermuisknop van een USB-muis.

## Installatie

Deze app is gemaakt voor Windows 11.

### Windows-beveiligingsupdates

Zorg er eerst voor dat de pc de nieuwste Windows-beveiligingsupdates heeft. Dit is straks ook nodig voor de SAC-stap.

### App en SHA-256 downloaden

De nieuwste versie van de app kan worden gedownload via GitHub Releases.
Download daar:
- cwdemo.exe
- cwdemo.exe.sha256

Bekijk de changelog om te zien wat er in de verschillende versies is gewijzigd.

### SHA-256 controleren

Deze stap is niet vereist, maar het is verstandig om deze uit te voeren:

- Download cwdemo.exe en cwdemo.exe.sha256.
- Open PowerShell in de map waarin de bestanden staan.
- Voer uit: Get-FileHash .\cwdemo.exe -Algorithm SHA256
- Vergelijk de weergegeven SHA-256 met de waarde in cwdemo.exe.sha256.

### App uitvoeren

Start de app. De app werkt op volledig scherm. Met Esc kun je de app sluiten.

De app is niet ondertekend met een certificaat. Daarom kun je beveiligingswaarschuwingen krijgen of een melding dat de app wordt geblokkeerd. Zie hieronder.

#### SmartScreen-melding

Bij deze melding kun je ervoor kiezen de app toch uit te voeren.

#### Smart App Control (SAC)-melding

Het kan zijn dat de app wordt geblokkeerd met een SAC-melding. Dit kan worden opgelost door SAC, al dan niet tijdelijk, uit te schakelen. Dit gaat als volgt (alles op eigen verantwoording en dus nadat de nieuwste Windows-updates zijn binnengehaald):

* Open Start en zoek naar **Windows-beveiliging**.
* Kies **App- en browserbeheer**.
* Klik op **Instellingen voor Smart App Control**.
* Selecteer **Uit**.

## Gebruik
- De bedoeling is dat kinderen hun naam seinen. De app begint met in het scherm 'Sein je naam!'.
- De app laat bij Morsealfabet alleen de letters zien, maar herkent ook cijfers en leestekens.
- Als er niet meer geseind wordt gaat de app na 10 seconden naar een nieuwe regel voor een volgende naam. Na 2 minuten gaat het scherm weer terug naar de begintoestand.
- Rechtsonderaan staat het versienummer van de app. Zie de CHANGELOG.md voor de doorgevoerde wijzigingen.
