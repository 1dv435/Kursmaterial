## Inledning
Vi har hittills koncentrerat oss på att strukturera upp vår information på ett så semantiskt sätt som möjligt. Nu är det dags att ge ögat något vackert att vila på. Vi ska alltså se till att med stilmallar ge vår sajt ett enhetligt och trevligt uttryck.

## Mål
Css ligger i fokus för laborationen och målet med laborationen är att din sajt ska kännas i det närmaste färdig utseendemässigt. Efter laborationen ska du ha övat dina färdigheter inom:
- Layout med css
- Typografi
- Färgsättning
- CSS-egenskaper som float, margin, padding, width, height etc.

## Förberedelse
Innan du kommer till laborationstillfället bör du vara så förberedd att du känner att du hinner genomföra och redovisa laborationen under det handledda tillfället. Du får givetvis göra laborationen helt klar i förväg och du har då möjlighet att utnyttja handledningstillfället för frågor och redovisning. 

Läs igenom **hela** laborationshandledningen innan du påbörjar laborationen.

## Genomförande
Utför laborationens uppgifter och moment samt dokumentera vad du kommer fram till på de olika delarna. Vid redovisning av laborationen ska du kunna besvara frågor om hur du har löst de olika delarna och varför de är lösta på det sätt du löst dem på.
När du anser dig vara klar med laborationen kontrollerar du att din källkod uppfyller laborationens samtliga krav.

Efter **minst** varje uppgift i denna handledning ska du göra en commit till ditt GIT-repositorie. 

## Plagiat
Laborationen ska genomföras enskilt. Du får givetvis fråga klasskamrater om hjälp men du ska skriva din egen kod och kunna svara för varför du skrivit din kod på det sätt du gjort. Vid fuskmisstanke lämnas misstankar samt berörda dokument över till universitetets disciplinnämnd.

## Föreslå ändringar
Denna handledning ligger på [GitHub](https://github.com/1dv435/Kursmaterial/blob/master/Laborationer/Laboration%202.md) om du vill föreslå ändringar eller hålla koll på vad de senaste uppdateringarna innebar.

## Eget arbete
Du ska i denna laboration med hjälp av css göra din sida mer funktionell och förhoppningsvis även se till att den blir en fröjd för ögat.

Du kan i denna laboration välja lite hur du vill lägga upp ditt arbete. Har du tidigare arbetat mycket med css tidigare kan du vara ganska fri i din process att "stila" upp sidan. Är du nybörjare så rekommenderas det att du följer arbetsgången i dokumentet. 

För dig som väljer att göra laborationen utan att följa laborationshandledningen finns dock några krav:

- Ingen stilmallskod får finnas i html-dokumenten
- Din layout ska ha minst två kolumner. 
- Layouten ska vara centrerad på sidan.
- Du ska kunna redogöra för layouten i uppgift 3.2
- Du ska ha en genomtänkt färgsättning och typografi
- Kraven för menyn i uppgift 3.4 ska vara uppfyllda.
- Minst två bakgrundsbilder ska länkas in via css
- Blogginlägg ska vara tydligt markerade och innehålla bilder som kan vänster eller högerställas. (Uppgift 3.7)

Läs igenom hela handledningen även om du inte kommer att följa den.

## Uppgift 2.1 – Använda stilmallar
För att få ett enhetligt uttryck på vår sida bör vi skapa en css-fil som länkas in på alla sidor på siten. Det gör inget att denna stilmall kommer att innehålla kod som inte används på samtliga sidor. 

![Filstruktur][filetree-css]

Du bör nu skapa en länkstruktur enligt ovan. Då hittar du allt som har med stilmallar att göra i katalogen ”css”. I katalogen ”css/pics” kan du lägga bilder som länkas in från css-filen.

På denna laboration får du mer än gärna använda en ”nollställnings-css” som exempelvis Eric Meyers CSS Reset ([http://meyerweb.com/eric/tools/css/reset/](http://meyerweb.com/eric/tools/css/reset/)). Du får dock inte använda någon form av CSS-ramverk.


**Git-commit**

## Uppgift 2.2 – Layout
När det nu är dags att pynta vår sida med css är det första vi bör göra att titta på den övervägande layouten av sidan. Hur ska de stora byggblocken på sidan förhålla sig till varandra. Ska vi arbeta med kolumner? Ska sidan vara centrerad? Och så vidare. 

Eftersom vi i föregående laborationer inte har funderat alls över vår layout så kommer du nu troligtvis att behöva strukturera din HTML-kod något för att ha en rimlig möjlighet att sedan förändra den på lämpligt sätt med css.

Vi kommer att föreslå att du använder en layout av sidan enligt följande:

![Layoutförslag][css-layout]

Du är fri att använda en annorlunda layout om du önskar, men du får inte göra det enklare för dig och ett grundkrav är att du ska använda dig av minst två kolumner. Vid redovisning ska du också kunna redogöra för hur layouten ovan skulle kunna skapas.

Det första du bör göra nu är att peta in div-taggar i din kod för att få en struktur lik den ovan (Det är ok att använda nya strukturelement i HTML5 men du måste kunna förklara användningen. Detta kommer senare i kursen). Sätt även id:n med lämpliga värden så att du enkelt kan komma åt sidans olika delar från css-koden. Titta gärna även i föreläsningsmaterialet/demos för ett exempel på hur detta skulle kunna se ut.

Observera att detta är en layout som har en **fast bredd** (960-1200px kan vara lämpligt för containern) och att layouten är **centrerad** på sidan, den gråa ytan på bilden ovan motsvarar alltså body-taggen.

Du kan börja med att göra om en sida, exempelvis index.html eller presentation.html. När du sedan är nöjd med resultatet av layouten så länkar du in din css-fil i de övriga filerna samt modifierar dessa så att de har samma html-struktur som den första filen du gjorde. Glöm inte bort att layouten ska vara centrerad!

För att underlätta kan du sätta en ram runt alla övergripande element så blir det lättare att se var dess gränser är. Tänk dock på att ramens bredd är utöver elementets width-attribut.

![Layoutförslag][css-htmllayout]

I detta skede behöver du inte fokusera på typsnitts-storlekar, färger etc. då detta är enkelt att ändra i css-filen i efterhand. Det viktiga är att du får en struktur på html-koden som du känner att du är nöjd med.

**Git-commit**

## Uppgift 2.3 – Färgsättning
När du känner dig nöjd med layouten kan vi nu gå över till att färgsätta sajten. Här bör du försöka hitta en färgsättning med färger som fungerar bra tillsammans. Ett par primärfärger och någon/några komplementfärger kan vara lämpligt. 

![.][css-colorex]

Om du inte har ett bra öga för färger så kan man få mycket inspiration genom att titta på andra webbsajter eller använda ett verktyg som [http://colorschemedesigner.com/](http://colorschemedesigner.com/) eller [http://kuler.adobe.com/](http://kuler.adobe.com/)

Notera gärna dina färger som kommentarer i din css-fil så hittar du enkelt dina färger när du behöver dem.

![.][css-colorcomment]

Se nu till att sätta genomtänkta färger på bakgrunder, texter, ramar etc.  

**Git-commit**

## Uppgift 2.4 – Menyn
Hittills har vi inte lagt så mycket energi på menyn men det ska vi göra någonting åt nu.

![.][css-menu]

Du får i denna uppgift välja om du vill ha en vertikal eller horisontell meny. Tänk dock på att om du väljer en horisontell meny så behöver du fylla din kolumn med något annat då du fortfarande ska ha två kolumner i layouten. 

Grundkraven som ska uppfyllas:

- När användarens muspekare rörs över ett menyalternativ så ska detta markeras på något sätt. (färg, fetstil, understrykning etc.) 
- Hela den yta som markerar menyalternativet ska vara klickbar. Inte bara texten.
- Prickarna som markerar ett listelement ska inte vara synliga.
- Det menyalternativ som är aktivt just för tillfället (motsvarar den sida som användaren besöker) ska markeras på något sätt. 

För att få tag i aktivt menyalternativ är det smidigast om du tilldelar den a-tagg som detta gäller en speciell klass, exempelvis 'active'.

`<li><a href="index.html" class="active">Start</a></li>`

Se nu till att menyn ser likadan ut på samtliga sidor och att den fungerar för alla sidor.

**Git-commit**

## Uppgift 2.5 – Typografi
Dags nu att se över sidans typografi, alltså hur typsnitt och läsbarheten kan förbättras på din sida.

Tänk igenom typsnittsstorlekar, vilka typsnitt som ska användas, radavstånd etc. och implementera detta i din stilmall. Du ska i detta steg även se till att dina länkar (exklusive menyn) har ett enhetligt utseende och är lätta att urskilja från vanlig text. 

![.][css-typografi]

**Git-commit**

## Uppgift 2.6 – Övrigt
Nu kan vi börja med ”finliret”, rätta till marginaler och stoppningar (padding). Dessutom ska du i denna uppgift se till att använda från css-filen inlänkade bakgrundsbilder på minst två ställen i koden. T.ex. kan du se till att lägga din logotyp som en bakgrundsbild och även infoga en liten ikon framför dina blogginlägg på startsidan. 

![.][css-bgimage1] ![.][css-bgimage2]

Givetvis kan du även behöva gå tillbaka och rätta till vissa delar i tidigare skriven kod, som du nu ser inte riktigt passar som du hade tänkt dig. I denna uppgift kommer du att behöva göra flera commits till git. Gör en commit per avgränsad ändring som du gör i koden. Alltså, en commit för att lägga till bakgrundsbilder, en commit om du ändrar något i strukturen, en kommit om du ändrar färgsättning etc.

Du bör nu även kontrollera att allt ser bra ut på samtliga sidor som du skapat. Var inte rädd för att lägga in några extra klasser i fin html-kod även om dessa bara används på någon enstaka sida. 

Har du inte kommenterat din css-kod under tiden du skrivit? Kanske dags att se över detta nu i så fall. Tid kanske även finns för att gå igenom koden en extra gång.


**Git-commit, commit, commit, commit…..**

## Uppgift 2.7 – Ny bloggpost
För att få laborera lite med bilder på våra sidor ska du nu skapa en ny bloggpost innehållandes ett flertal stycken med text samt även en bild (som nu länkas in med &lt;img&gt;-taggen då den hör till blogginläggets innehåll). 
Texten kan vara av typen ”Lorem ipsum” men givetvis är det roliga om du kan skriva ett blogginlägg. Uppgiften blir att genom att sätta en klass på bilden ska man kunna bestämma hur bilden ska ligga i förhållande till texten.
Klasserna är:
- **"left"**:  Bilden fälls in till vänster i inlägget
- **"right"**: Bilden fälls in till höger i inlägget. (se exempel nedan)

![.][css-post]

Vill du kan nu även ge en ram till bilden. 

**Git-commit**

## Uppgift 2.8 – Laborationssidan
Stila nu på eget bevåg till laborationssidan så att exempelvis tabellen följer din sidas design och att den blir tydlig. 
Kontaktformuläret lämnar vi till nästa laboration, men om du vill får du gärna redan nu ge dig på att snygga till det.

**Git-commit**

**Git-push**

## Postludium
Du har nu genomfört laboration 2 och du ska nu skapa en release för detta på GitHub

1. Logga in på GitHub och gå till repositoriet för laborationen.
2. Kontrollera att dina senaste ändringar finns tillgängliga på GitHub.
3. Klicka på "releases" ovanför fillistningen.
4. Välj att skapa en ny release.
5. Se till att "Tag version" blir `l02` (Ludvig, nolla, tvåa).
Välj en lämplig titel.
6. Publicera releasen

Var så god att påbörja arbetet med laboration 3!


[filetree-css]: https://github.com/1dv435/Kursmaterial/raw/master/Laborationer/pics/filetree-css.png

[css-layout]: https://github.com/1dv435/Kursmaterial/raw/master/Laborationer/pics/css-layout.png

[css-htmllayout]: https://github.com/1dv435/Kursmaterial/raw/master/Laborationer/pics/css-htmllayout.png

[css-colorex]: https://github.com/1dv435/Kursmaterial/raw/master/Laborationer/pics/css-colorex.png

[css-colorcomment]: https://github.com/1dv435/Kursmaterial/raw/master/Laborationer/pics/css-colorcomment.png

[css-menu]: https://github.com/1dv435/Kursmaterial/raw/master/Laborationer/pics/css-menu.png

[css-typografi]: https://github.com/1dv435/Kursmaterial/raw/master/Laborationer/pics/css-typografi.png

[css-bgimage1]: https://github.com/1dv435/Kursmaterial/raw/master/Laborationer/pics/css-bgimage1.png

[css-bgimage2]: https://github.com/1dv435/Kursmaterial/raw/master/Laborationer/pics/css-bgimage2.png

[css-post]: https://github.com/1dv435/Kursmaterial/raw/master/Laborationer/pics/css-post.png
