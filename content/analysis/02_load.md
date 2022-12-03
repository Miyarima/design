---
Title: Load
Description: A raport about loading times and utility.
Template: reports
---

Load
=======================

<p class="first-row">
En undersökning av tre webbplatsers laddningstid och användbarhet, görs för att se hur snabbat dem är
och om de kan förbättra sin laddningstid.
</p>

<div class="second-row">
<h2>Urval</h2>

<p>
Tre bland de 100 mest besökta webbplatser i Sverige enligt [1] i olika kategorier. En bank, Swedbank.se, en e-shop
Netonet.se och en tidning, expressen.se.
</p>
</div>
<div class="third-row">
<h2>Metod</h2>

<p>
Googles PageSpeed Insights används för att undersöka webbsidornas laddningstids betyg för mobil och desktop. Nätverksfilken
i valfri webbläsare används för att se hur snabbt sidan laddas. Detta görs tre gånger för att få ut ett snitt på laddningstiden.
Nätverksfliken används också för att se hur många resurser som laddas och skickas.
</p>
</div>

<div class="fourth-row">
<h2>Resultat</h2>
<div class="embed-container">
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRVcsCxKzVkRBqGb40xZULPHUPZO_OlH_0rZnUdcX44-HVgeWfeF0lhceRVYpyhqnCe3RhRH7g5jaqs/pubhtml?widget=true&amp;headers=false"></iframe>
</div>
</div>

<div class="fifth-row">
<strong>Swedbank.se</strong>
<img class="img" src="%base_url%/image/swedbank.png" alt="en bild på swedbanks sida.">
<p>
SwedBank fick i betyg 90 på desktop och 61 på mobile. Efter tre omladdningar blev sidans snitt laddningstid 504 millisekunder. 
SwedBank hade 2.1 MB i resurser, var av dessa 1.3 MB blev överförda till klienten. Enligt PageSpeed var SwedBanks största problem,
mycket oanvänd CSS, bilder är inte ooptimerade, above the fold tog väldigt lång tid att ladda, samt fanns det assets som kan bli
chachade.
</p>
</div>

<div class="sixth-row">
<strong>Netonnet.se</strong>
<img class="img" src="%base_url%/image/netonnet.png" alt="en bild på netonnet sida.">
<p>
NetonNet fick i betyg 96 på desktop och 44 på mobile. Efter tre omladdningar blev sidans snitt laddningstid 570 millisekunder. 
NetonNet hade 3.0 MB i resurser, var av dessa 1.2 MB blev överförda till klienten. Enligt PageSpeed var NetonNet största problem,
mycket oanvänd JavaScript och CSS, ooptimerade bilder, above the fold tog väldigt lång tid att ladda, fanns det assets som kan bli
chachade och ner slöning av tredje part kod.
</p>
</div>

<div class="seventh-row">
<strong>Expressen.se</strong>
<img class="img" src="%base_url%/image/expressen.png" alt="en bild på expressens sida.">
<p>
Expressen fick i betyg 53 på desktop och 56 på mobile. Efter tre omladdningar blev sidans snitt laddningstid 658 millisekunder. 
Expressen hade 3.1 MB i resurser, var av dessa 864 kB blev överförda till klienten. Enligt PageSpeed var SwedBanks största problem,
mycket oanvänd JavaScript, ner slöning av tredje part kod, ooptimerade bilder och gammal JavaScript som exekveras långsamt.
</p>
</div>

<div class="eigth-row">
<h2>Analys</h2>
<p>
De vanligaste förbättringsåtgärderna från dessa tre sidor är, antingen mycket CSS eller JavaScript som inte används och kan
där med tas bort. Bilder på alla tre sidor kan bli optimerade och kan där med dra ner laddningstiden. Två av tre sidor hade
onödigt tredje parts kod som slöade ner sidorna. Om alla dessa förbättringsåtgärderna utfördes skulle laddningstiden minskas
markant.
</p>
<p>
Vinnaren av dessa tre sidor blir SwedBank, de har högst sammanlagda betyg, kortas laddnings tid och minst antal resurser.
</p>
<p>
Om jag skulle sätta ett gränsvärde på snabb laddningstid ligger detta kring 500 ms. I mitt urval av webbplatser passerar bara
Swedbank detta. Men jag upplever både SwedBank och Expressen som väldigt snabbt laddade sidor, medan NetonNet känns slö då man kan
se innehåll ladda in på sidan efter hand.
</p>
</div>

<div class="ninth-row">
<h2>Referenser</h2>
<p>1. <a href="https://computersweden.idg.se/2.2683/1.738698/sverige-mest-trafik-google">
        computersweden.idg.se/2.2683/1.738698/sverige-mest-trafik-google
    </a> (besökt 2022-12-01)</p>
<p>2. <a href="https://www.swedbank.se/">www.swedbank.se/</a> (besökt 2022-12-01)</p>
<p>3. <a href="https://www.netonnet.se/">www.netonnet.se/</a> (besökt 2022-12-01)</p>
<p>4. <a href="https://www.expressen.se/">www.expressen.se/</a> (besökt 2022-12-01)</p>
</div>

<div class="tenth-row">
<h2>Övrigt</h2>
<p>Jonathan Göransson.</p>
</div>
