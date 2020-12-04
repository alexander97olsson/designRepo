Utvärdering av webbplatsers laddningstid och användbarhet
=======================

Rapporten handlar om att genom ett specifikt och genomtänkt urval välja tre stycken olika webbplatser och analysera deras prestanda. Det som kommer tas upp i rapporten är laddningstid och användbarhet för varje hemsida. Hemsidorna kommer sedan analyseras för att ta fram ett resultat kring prestanda, laddningstid och användbarhet. 

1. Urval
-----------------------

Undersökningen kommer fokusera på tre olika webbplatser som är specifikt valde utifrån perspektivet av att sidorna har många besökare. Anledning till det är för att det känns mer relevant att undersöka hemsidor som riktar sig mot samma målgrupp. Temat jag valt är nyhetshemsidor eftersom det är något som människor runt om i världen använder dagligen. Med många besökare blir det viktigt att webbplatserna har en bra prestanda för att förenkla användningen. Lena K Samuelsson på Aftonbladet skriver att under sommaren 2019 hade Aftonbladet en rekordsiffra på 3,7 miljoner läsare på en dag vilket motsvarar en stor del av Sveriges befolkning (aftonbladet). Det finns alltså ett stort intresse av att optimera hemsidan eftersom webbplatserna dagligen används av miljoner.

De hemsidor jag valt att analysera är Aftonbladet (https://www.aftonbladet.se/), Expressen (https://www.expressen.se/) och Svenska Dagbladet (https://www.svd.se/). Alla tre hemsidor har gemensamt att de fokuserar på en stor målgrupp och försöker nå så många läsare som möjligt. Därför är det extra viktigt att första intrycket på hemsidan är bra och fungerar.

2. Metod
-----------------------

Rapportens metod består av två olika mätverktyg för att samla data kring varje hemsida. Det första heter PageSpeed insight (PageSpeed) som genom länk till en specifik hemsida kan kolla upp data kring vald webbplats. PageSpeed visar i procent hur bra hemsidan presterar på både mobil och dator.

Det andra verktyget är devtools flik networks som går att nå från de flesta moderna webbläsarna. Genom networks går det att analysera olika data från en webbplats. Det studien kommer fokusera genom användning av devtools-network är webbplatsernas laddningstid, resurser och storlek.

3. Resultat
-----------------------

<h1 class="watch-title">3.1 Aftonbladet</h1>
<div class="watch-image-div">
    <img class="watch-image" src="../assets/img/prestanda/aftonbladet.png" alt="Audemars Piguet">
</div>
<div class="watch-image-div">
    <img class="watch-image" src="../assets/img/prestanda/resultat_aftonbladet.png" alt="Audemars Piguet">
</div>
<a class="ref-link" href="https://www.aftonbladet.se/">Länk till webbplats</a>

I bilden ovan går det att se data som representerar och är insamlad via devtools flik networks. Informationen är laddningstid, storlek och resurser på webbplatsen. Storleken på webbplatsen ligger på 1,4 mb och antalet resurser är 76. Resultatet visar att det stora problemet med aftonbladet är deras laddningstid. Studien använder sig av tre olika försök på webbplatserna för att få fram ett medelvärde som ska representera webbplatsens laddningstid. Aftonbladet hade 2,79 sekunder, vilket motsvarar ganska mycket i sammanhanget.

Aftonbladet hade en procent på 18% och 52% enligt verktyget PageSpeed, 18% motsvarar besökare som använder sig av en mobil-enhet medan 52% motsvarar användning via datorer. Det går att göra en koppling mellan laddningstiden och webbplatsens procent. Låg procent i detta fallet resulterar i att laddningstiden ökar. Aftonbladet skulle behöva jobba genom sina bilder och applicera rätt storlekar där det passar bäst och även ta bort oanvänd CSS för att förbättra prestandan på webbplatsen.

<h1 class="watch-title">3.2 Expressen</h1>
<div class="watch-image-div">
    <img class="watch-image" src="../assets/img/prestanda/expressen.png" alt="Audemars Piguet">
</div>
<div class="watch-image-div">
    <img class="watch-image" src="../assets/img/prestanda/resultat_expressen.png" alt="Audemars Piguet">
</div>
<a class="ref-link" href="https://www.expressen.se/">Länk till webbplats</a>

Expressens resultat visar att antalet resurser är 55 och storleken är 5,3 mb, vilket går att observera på bilden ovan. Laddningstiden är betydligt bättre än vad det är för Aftonbladet och ligger på 0,83 sekunder. Även här togs det tre försök på vardera data för att få fram ett medelvärde som skulle representera resultatet.

Expressen fick en procent på 60% och 75% enligt PageSpeed. Där 60% motsvarar resultatet för en mobil-enhet och 75% för besökare som använder datorer. Även här går det att spegla resultatet från PageSpeed med antalet sekunder det tog att ladda hemsidan. Hög procent motsvarar i detta fallet även låg laddningstid.Det Expressen skulle behöver jobba med för att förbättra sin hemsida är att ta bort onödig JavaScript som inte används.


<h1 class="watch-title">3.3 Svenska Dagbladet</h1>
<div class="watch-image-div">
    <img class="watch-image" src="../assets/img/prestanda/svd.png" alt="Audemars Piguet">
</div>
<div class="watch-image-div">
    <img class="watch-image" src="../assets/img/prestanda/resultat_svd.png" alt="Audemars Piguet">
</div>
<a class="ref-link" href="https://www.svd.se/">Länk till webbplats</a>

Svenska Dagbladet hade ett medelvärde på 1,9 sekunder för webbplatsens laddningstid. Svenska Dagbladet var även den webbplats med flest resurser på 136 och högst storlek på hemsidan med 9,5 mb.

Svenska Dagbladet fick en procent på 35% och 87% från PageSpeed. Där 35% motsvarade resultatet från mobila-enheter och 87% för datorer.  Det är en stor skillnaden mellan datorer och mobiler på Svd vilket kan påverka besökare som väljer att använda sig av mobila-enheter. Det Svenska Dagbladet behöver jobba med för att göra sin hemsida få en bättre prestanda är att försöka skicka bilder i modernare bildformat och även läsa in viktiga resurser i förväg.


4. Analys
-----------------------

<div class="watch-image-div">
    <img class="watch-image" src="../assets/img/prestanda/resultat_total.png" alt="Audemars Piguet">
</div>

Resultatet och skillnande mellan de tre webbplatserna är stor även om de riktar sig till samma målgrupp och har samma huvudsyfte. Aftonbladet hade betydligt längre laddningstid än Expressen och Svd. Svd hamnar i mellan de två med 1,9 sekunder. Det är intressant att analysera PageSpeeds percent med resultatet från laddningstiderna. För att göra det enkelt att analysera har jag valt att ta fram medelvärdet för varje PageSpeed procent genom att ta procenten för mobila-enheter och addera det med procenten för datorer och dela på två. Aftonbladet fick en total procent på 35%, expressen fick 67,5% och Svenska Dagbladet fick 61%. Med det ser man att Expressen presterade bäst med 67,5%, därefter kommer Svenska Dagbladet med 61% och sist Aftonbladet med 35%. Resultatet speglar även sidans laddningstid, där ordningen för sidorna blir den samma.

Jag har valt att rangordna alla tre webbplats för att få fram vilken hemsida som presterar bäst enligt denna studie och analys. Ordningen på webbplatserna baserat på studiens mätvärden är: 

Expressen
Svenska Dagbladet
Aftonbladet

Anledningen till resultatet är för att jag anser att laddningstid är avgörande när det kommer till de flesta användarna och skulle det påverka besökaren för mycket kan det påverka antalet besökare, vilket för just nyhetshemsidor är viktigt eftersom de lever på att besökare läser deras nyheter.

De vanligaste förbättringarna är återkommande för alla de tre valda webbplatserna. Det är att försöka ta bort saker som inte används vid inladdning. Även att försöka använda bilder med rätt bildstorlek. 

Jag skulle säga att min gräns på absolut laddningstid är 1 sekund. Allt under 1 sekund är bra och gör att användaren snabbt kan fortsätta på hemsidan utan att tröttna och klicka ner webbplatsen. Allt över 2 sekunder är för långsamt och det kommer nog påverka antalet besökare som stannar på sidan. Aftonbladet tog 2,8 sekunder vilket går över 2 sekunder gränsen vilket jag anser är för högt. Expressen tog 1,9 sekunder vilket är gränsfall men det håller måttet och överstiger inte 2 sekunder. Svenska Dagbladet hade en laddningstid på bara 0,8 sekunder, vilket är väldigt bra och snabbt. När det kommer till storleken på sidorna och antalet resurser påverkar inte det laddningstiden.

5. Referenser
-----------------------

<a>Aftonbladet</a> <a class="ref-link" href="https://www.aftonbladet.se/nyheter/kolumnister/a/kJbggB/succesommar-for-aftonbladet">(www.aftonbladet.com(Lena K Samuelsson))</a><br>
<a>Aftonbladet</a> <a class="ref-link" href="https://www.aftonbladet.se/">(www.aftonbladet.com)</a><br>
<a>Expressen</a> <a class="ref-link" href="https://www.expressen.se/">(www.expressen.com)</a><br>
<a>Svenska Dagbladet</a> <a class="ref-link" href="https://www.svd.se/">(www.svd.se)</a><br>
<a>PageSpeed</a> <a class="ref-link" href="https://developers.google.com/speed/pagespeed/insights/?hl=sv">(www.developers.google.com.se)</a>

6. Övrigt
-----------------------

Rapporten utfördes av mig själv Alexander Olsson. Jag valde att arbeta ensam och utföra arbete själv eftersom jag tycker det är lättare att få en röd tråd om jag själv skriver varje del i rapporten. 
