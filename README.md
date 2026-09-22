# cwdemo

Dit is een morsedecoder, speciaal bedoeld voor demonstraties aan kinderen.
De app is nog in ontwikkeling.

## Support

Dit is een hobbyproject dat zonder ondersteuning wordt aangeboden. Er wordt geen individuele gebruikerssupport geleverd.

## Disclaimer

Gebruik van de app en wat daarbij komt kijken is op eigen verantwoording.

## Muis als interface

Seinen kan met een seinsleutel (straight key) die aangesloten is op de contacten van de linkermuisknop van een USB-muis.

## Installatie

Deze app is gemaakt voor Windows 11.

### Windows-beveiligingsupdates

Zorg er eerst voor dat de pc de nieuwste Windows-beveiligingsupdates heeft. Dit is straks ook nodig voor de SAC-stap.

### App en SHA-256 downloaden

[**Download de nieuwste versie van cwdemo**](https://github.com/sdr21c/cwdemo/releases/latest)

Download onder **Assets**:
- `cwdemo.exe`
- `cwdemo.exe.sha256`

Bekijk de changelog om te zien wat er in de verschillende versies is gewijzigd.

### Authenticiteit en veiligheid

Download cwdemo.exe uitsluitend via de officiële releases van deze repository.

Bij iedere officiële release wordt de SHA-256-controlesom van cwdemo.exe gepubliceerd. Controleer het gedownloade bestand in PowerShell met:

Get-FileHash .\cwdemo.exe -Algorithm SHA256

Vergelijk de weergegeven SHA-256 uitsluitend met de waarde die bij de overeenkomstige officiële release op bovenstaande GitHub-repository staat.
Komt de SHA-256 niet exact overeen, gebruik het bestand dan niet. Het bestand is dan niet identiek aan de officiële versie van cwdemo.
Een SHA-256-bestand dat samen met cwdemo.exe van een andere bron is verkregen, is op zichzelf geen bewijs dat het bestand een officiële versie is.

### App uitvoeren

Start de app. De app werkt op volledig scherm.

De app is niet ondertekend met een certificaat. Daarom kun je beveiligingswaarschuwingen krijgen, of een melding dat de app wordt geblokkeerd. Zie hieronder.

### App stoppen

De app kan gestopt worden met de Esc-toets.

#### SmartScreen-melding

Bij deze melding kun je ervoor kiezen de app toch uit te voeren.

#### Smart App Control (SAC)-melding

Het kan zijn dat de app wordt geblokkeerd met een SAC-melding. Dit kan worden opgelost door SAC, al dan niet tijdelijk, uit te schakelen. Dit gaat als volgt:

* Open Start en zoek naar **Windows-beveiliging**.
* Kies **App- en browserbeheer**.
* Klik op **Instellingen voor Smart App Control**.
* Selecteer **Uit**.

### Download en verspreiding

Het opnieuw aanbieden, uploaden of verspreiden van cwdemo.exe via andere websites, repositories of andere kanalen is niet toegestaan. Verwijzen of linken naar deze GitHub-repository is uiteraard wel toegestaan.


## Gebruik
- De bedoeling is dat kinderen hun naam seinen. De app begint met in het scherm 'Sein je naam!'.
- De app laat bij Morsealfabet alleen de letters zien, maar herkent ook cijfers en leestekens.
- Als er niet meer geseind wordt gaat de app na 5 seconden naar een nieuwe regel voor een volgende naam, of een herkansing als men fouten gemaakt had. Na 2 minuten gaat het scherm weer terug naar de begintoestand.
- Rechtsonderaan staat het versienummer van de app. Zie de CHANGELOG.md voor de doorgevoerde wijzigingen.
