---
Title: Load
Description: This is my analysis page.
Template: analysis
---

Kmom05 Rapport
=======================

Kursmoment 5 i Design-kursen.

Urval
-----------------------

Jag valde att fortsätta med samma sidor som i föregående moment:

- **Apple**
- **Svenska Dagbladet**
- **Stockholms Stad**

Min tanke var att välja sidor med olika syften för att se om hur de skiljer sig åt. Min egen uppfattning om sidornas syfte är att:  

Apple vill sälja sina produkter och samtidigt bygga och stärka sitt varumärke. Webbplatsen har många bilder och är grafiskt intensiv.  

Svenska Dagbladet vill ha fokus på läsbarhet och samtidigt sälja annonser. Även här är bilder en viktig del av webbplatsen.  

Stokholms stads sida fokuserar på tydlighet och användbarhet. Bilder är inte lika vanligt som för de övriga sidorna.  


Metod
-----------------------

Jag utförde uppgiften enligt instruktion, dvs:

Mätte sidans prestanda i Google Pagespeed, både för mobil och desktop.

Kontrollerade laddtid, resurser och storlek på nedladdat material i webbläsarens inspektör. Jag laddade om tre gånger utan cache och tog snittet av laddningarna.

Resultatet dokumenterade jag i Google Kalkylark.

Resultat
-----------------------

##Apple  

Sämst resultat generellt. Sista plats men klart snyggast sida!

![Image Title](../assets/img/apple.png)  

##Svenska Dagbladet  

Bäst reultat generellt. Testvinnare!

![Image Title](../assets/img/svd.png)  

##Stockholms stad  

Snabbast enligt devtools network i webbläsaren, men mittenplacering enligt Pagespeed. Mellanplats.

![Image Title](../assets/img/sthlm.png)  

Analys
-----------------------

Innan jag genomförde testerna trodde jag nog att Stockholm skulle vara bäst eftersom det är en sida som inte är särskilt grafiktung. Jag hade nog förväntat mig att Apple och SvD skulle vara ungeför likvärdiga. Detta för att Apple är grafiskt tung och SvD generellt känns som en omfattande sida med mycket information och många bilder. 
Det visade sig att Stockolm inte var i topp på något enligt Pagespeed, trots att sidan laddade minst antal resurser och minst antal MB. Enligt webbläsarens inspektör laddade dock Stockholm snabbast av sidorna. 
Om jag bara går på känsla så upplever jag samtliga sidor som snabba. Jag känner inte att jag behöver vänta på någon av dem, vilket är min egen definition av en tillräckligt snabb webbsida. Eftersom jag använder bredband med bra hastighet så spelar det kanske inte så påverkas just dessa sidor kanske inte så mycket av att de ändå har mycket innehåll. Skulle man ladda sidorna på en långsam 3G mobil skulle man säkert uppleva det annorlunda. 

Tittar man på möjliga förbättringar kan man se följande i Pagespeed:

Apple - För Apple är det olika element, bilder och animeringar, som drar ned hastigeten, tillsammans med stora CSS och Javascriptfiler. Sidan är som sagt grafiskt intensiv och det lär vara ett medvetet val att prioritera utseende framför högsta möjliga prestanda.

SvD - För SvD verkar den största tidsbesparingen finnas i om det är möjligt att minska antalet Javascript som laddas in, samt en stor CSS-fil.

Stockholm - Den bild som laddas är stor och tar lång tid. Bilden skulle eventuellt kunna komprimeras, visas i mindre storlek eller ändrat till ett modernare format, som WebP.  

Alla webbplateser kan förbättra sig genom att minska på det grafiska innehåller, men som sagt, jag upplever inte någon som långsam, varken via mobil eller desktop, så då är det svårt att komma med förbättringsförslag.

<div class="google_sheets">
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRF0NVC1RZF7OobkqdNMAH6cWB54lI5p8NvNJ-DXgGxVT1LWX4rd7WX8fwQ1ASo-LrWY96Tp40wlD0O/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
</div>

[Länk till Google-dokumentet](https://docs.google.com/spreadsheets/d/1Xgaa01XWFOXkIJwQW4CumCTm88m9bCOQNJzgkqqTUUs/edit?usp=sharing) 

Referenser
-----------------------

Alla sidor hämtade 2024-12-08. Bilderna återanvända från förra KMOM.

[Apple](https://www.apple.com/se/)  
[Svenska Dagbladet](https://www.svd.se)  
[Stockholm Stad](https://start.stockholm)  
[Google Pagespeed](https://pagespeed.web.dev/)  

Övrigt
-----------------------

Jag genomförde uppgiften ensam.
/David
