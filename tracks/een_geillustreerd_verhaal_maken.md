## Track 1: Maak een geïllustreerde video met muziek en stem

Het doel van deze track is om een geïllustreerd verhaal te maken met geanimeerde beelden, muziek en een stemverteller. De deelnemer ontdekt verschillende technologieën waaronder: diffusiemodellen (dall-e, stablediffusion, midjourney,...), tekst-naar-spraaksynthese en tekst-naar-muzieksynthese.

1. Stap 1: Genereer een pitch voor het verhaal 

Je kunt de prompt in [chatgpt] (https://chat.openai.com) gebruiken om een pitch voor je verhaal te genereren: 

    Genereer een script voor een video van 1 minuut over ONTDEK UW VERHAAL. De video moet een geïllustreerd verhaal zijn waarin een verteller de actie van elke scène beschrijft. Geef een beschrijving van de illustratie en de tekst van de verteller voor elke scène. De beschrijving van de afbeelding moet coherent zijn tussen de scènes en herhaal altijd de personage-namen en beschrijving voor elke illustratiebeschrijving.


2. Stap 2: Genereer een stijl voor je geïllustreerde verhaal.

Je kunt deze prompt gebruiken in [chatgpt] (https://chat.openai.com) :

    Kun je een korte stijlvoorspelling maken voor een afbeeldingengenerator. Het moet alleen de stijl van de afbeelding beschrijven en niet de compositie. Ik wil graag een BESCHRIJVING VAN DE STIJL die U WILT ?
    voorbeeld : Render in een levendige anime stijl, met vloeiende verlopen, expressieve ogen en zachte schaduw. Emuleer de nauwgezette details die typerend zijn voor Japanse animatie van hoge kwaliteit, zorg voor strakke lijnen en een balans tussen realisme en stilering.

3. Stap 3: Genereer elk frame met [bing image creator] (https://www.bing.com/create) met de illustratiebeschrijving als prompt. Voeg de stijlprompt toe aan elke illustratiebeschrijving (je moet misschien ook wat details toevoegen aan de prompt om de scène verder te beschrijven om het consistent te houden met het script).

4. Stap 4: Geef elk frame door aan [gen-2](https://research.runwayml.com/gen2) op runwayml om de afbeeldingen te animeren.

5. Stap 5 : Groepeer de verteller lijn in chatgpt met behulp van deze prompt : 

    Kun je alle vertellerregels groeperen in een enkele paragraaf?

5. Stap 5 : Genereer de stem van de verteller met [elevenlabs](https://elevenlabs.io/). Kopieer gewoon de narrotor paragraaf, kies je stem en genereer.

6. Stap 6 : [optioneel] Genereer achtergrondmuziek met een tekst-naar-muziek app. Je kunt ook omgevingsgeluiden genereren.

7. Stap 7 : Zet alles in elkaar in een [capcut](https://www.capcut.com) online video editor (voorbeeld: capcut)