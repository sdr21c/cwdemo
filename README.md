# cwdemo
Dit is een morsedecoder, speciaal bedoeld voor demonstraties aan kinderen.

Deze app is gemaakt voor Windows 11. De app is gratis.

De app wordt binnenkort in de praktijk getest op Makers Days in Eindhoven.
Zie https://makerdays.nl/maker/hamradiolab-eindhoven-de-makers-van-de-ether/

## Support
Op de app wordt geen support gegeven.

## Disclaimer
Gebruik van de app is op eigen verantwoording.

## Muis als interface
Seinen kan met de linkermuis-button van een USB muis. Hierbij kan op de contacten van de button een seinsleutel (straight key) aangesloten worden. 

## Installatie

### Windows beveiligingsupdates
Zorg eerst dat de PC de nieuwste Windows beveiligingsupdates heeft. Dit is straks ook nodig voor de SAC stap.

### App en sha-256 downloaden
De nieuwste versie van de app is te vinden onder **Releases**.
Download daar:
- cwdemo.exe
- cwdemo.exe.sha256

### SHA-256 controleren
Deze stap is niet vereist maar het is vestandig om deze uit te voeren:
- Open PowerShell in de map waarin het bestand staat en voer uit:
Get-FileHash .\cwdemo.exe -Algorithm SHA256
- Vergelijk de weergegeven SHA-256 met de checksum die bij de release staat.

### App uitvoeren
Start de app. De app werkt full-screen, met Esc kun je het sluiten.
De app is niet ondertekend met een certificaat, daarom kun je beveiligingswaarschuwingen krijgen of een melding dat de app geblokkeerd wordt. Zie hieronder.

#### Smart Screen melding
Bij deze melding kun je kiezen dat de app toch uitgevoerd mag worden.

#### Smart Screen Control (SCA) melding.
Het kan zijn dat de app geblokkeerd wordt met een SCA melding. Dit kan opgelost worden door SCA, al of niet tijdelijk, uit te schakelen, als volgt (alles op eigen verantwoording, en dus nadat de nieuwste Windows updates zijn binnengehaald):
- Open Start en zoek naar Windows-beveiliging.
- Kies App- en browserbeheer.
- Klik op Instellingen voor Smart App Control.
- Selecteer Uit
