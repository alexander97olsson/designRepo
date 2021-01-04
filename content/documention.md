---
Title: Dokumentation
Description: This is the dokumentation page.
hidden: true
Template: about
---

Dokumentation
==========================

Dokumentera färgpaletten och berätta hur du valde färgerna.
--------

Jag har valt att använda mig av en färgpalett som speglar loggan för advokatbyrån. Advokatbyrån skickade även en bild som de vill skulle representera hemsidans tema. Jag har valt att använda bilden som en header för webbplatsen och därefter också använda mig av samma toner av färger på resterande delar av webbplatsen. De primära färgerna jag jobbar med är, vitt, svart, orange och guld. Anledningen till valet av palett är som nämnt innan med att loggan speglar dessa färger men valet handlar även om att få en stilren och lyxig känsla. Orange och guld är snarlika i färgerna och går bra kombinera med varandra för att få en subtil stil på webbplatsen. Jag valde även att använda mig av ett färgschema. Jag valde komplementärt färgschema. Min primära färg är orange och därför valde jag att använda mig av blå som min komplementära färg. Detta för att förtyda knappen på min ”highlight-sida”. Orange och guld tar över mycket av färgerna på sidan blir blåa färgerna extra synlig. Det gör att besökaren lätt kan se knappen och fortsätta om de behöver hjälp.

<table class="color-palett" style="border-spacing: 4px; border-collapse: separate">
    <a>Color palette</a>
    <tr>
        <td style="height: 50px; width: 50px; background-color: rgb(168, 109, 50)">
        <td style="height: 50px; width: 50px; background-color: rgb(219, 181, 79)">
        <td style="height: 50px; width: 50px; background-color: rgb(0, 0, 0)">
        <td style="height: 50px; width: 50px; background-color: rgb(255, 255, 255)">
    </tr>
</table>

Beskriv typografin, designprinciper och designelement som du använt.
--------

Jag har valt att använda mig av enkel design för min typografi. Webbplatsen utstrålar stilrent och enkelhet, viket gör att en enkel design på min font känns relevant. Jag har valt att använda mig av "Roboto sans-serif” för den huvudsakliga delen av min webbplats. Den del som inte använder sig av sans-serif är header och footer. Där har jag valt att använda mig av ett typsnitt som heter ”crimson text serif”. Jag tycker det passar eftersom det påminner om sans-serif men har lite annan stil, tanken är att besökaren ska få öga för den texten först och sedan läsa den andra delen som det känns relevant. Storleken på texten varierar beroende på vad som ska synas mest och vad som ska dra läsaren till att fokusera på. Tillexempel är rubriker aningen större än under texten eftersom det gör att besökaren först läser rubriken för att förstå om hen vill fortsätta läsa.
De desingprinciper och designelement som återkommer på webbplatsen är färg, bilder och grid. Grid använder jag för att bygga upp ett rutnät för informationen på hemsidan. Det används på både förstasidan och ”medarbetar” sidan. Gridden som bygger upp medarbetar-sidan är bra för att placera ut alla medarbetare på ett snyggt och effektivt sätt. Det fungerar även bra när webbplatsen används i mobilt läge. Grid används även på förstasidan för att bygga upp information om webbplatsen och även för ”senaste nyheter”.

Jag använder mig av en bild som navbar och använder flikar för att navigera mellan de olika undersidorna. Min footer har användbar information kring företaget och deras kontaktmöjligheter. Loggan används på både header och footer för att förtydliga företagets synlighet.


Berätta vilken känsla som kunden vill uppnå med webbplatsen.
--------
Känslan hemsidan försöker uppnå är lyxig och välkommande. Känslan försöker uppnås via en stilrenhet och enkel design. Målet med den färgpalett som är skapad är få fram dessa känslor.

Beskriv hur du valt att dela upp din SASS-kod.
--------
Jag har valt att dela upp min SASS-kod i flera olika scss filer där alla ligger i mappen ”scss”. Jag har valt att skapa en scss-fil för varje enskild sida och även en för header och footer. Jag valde även att skapa en scss som heter common.scss som innehåller externa importerade delar. Det finns även en scss som heter varibles.scss som innehåller alla olika färger som används på sida i form av variabler. Anledning är för att enkelt kunna byta färg om behovet uppstår utan att behöva byta på alla olika ställen färgen används i koden. Totalt använder jag nio olika scss-filer i mitt projekt för att skapa webbplatsen.
Anledning till valen är för att enkelt ha koll på varje css separat från varandra. Det gör det enklare att uppdatera eller ändra något eftersom jag kan gå till den scss-fil det handlar om. Till exempel om jag behöver ändra något i min header vet jag att css för header ligger i filen ”header.scss”.
<div class="about-image-div">
    <img class="image-about" src="assets/img/scss-filer.png" alt="Picture of meeting">
</div>
