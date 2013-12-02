## Inledning
Vi kommer på denna laboration fortsätta med CSS och nu finslipa vår sida. Du kommer även att få träna lite extra på CSS genom att göra en ny layout på en separat sida och så långt det går försöka efterlikna en redan färdig design. I och med detta kommer du också att få testa att "forka" ett befintligt projekt på GitHub.

## Mål
Vi fortsätter med css. Efter laborationen ska du:
- Kunna stila formulär
- Ordna utskriftsvänliga versioner
- Kunna använda css-sprites
- Ha en orientering om nya CSS3-tekniker.

## Förberedelse
Innan du kommer till laborationstillfället bör du vara så förberedd att du känner att du hinner genomföra och redovisa laborationen under det handledda tillfället. Du får givetvis göra laborationen helt klar i förväg och du har då möjlighet att utnyttja handledningstillfället för frågor och redovisning. 

Läs igenom **hela** laborationshandledningen innan du påbörjar laborationen.

## Genomförande
Utför laborationens uppgifter och moment samt dokumentera vad du kommer fram till på de olika delarna. I schemat finns handledningstid utlagd då du har möjlighet att ställa frågor kring uppgiften och få hjälp ifall du kört fast. Använd också kursens forum för att ställa frågor där. Posta dock inga lösningar av uppgifterna på forumet.

När du anser dig vara klar med laborationen kontrollerar du att din källkod uppfyller laborationens samtliga krav.
Efter (minst) varje uppgift i denna handledning ska du göra en commit till ditt GIT-repositorie. Du ska då också göra en "release" av din kod när du är klar med varje laboration.

## Plagiat
Laborationen ska genomföras enskilt. Du får givetvis fråga klasskamrater om hjälp men du ska skriva din egen kod och kunna svara för varför du skrivit din kod på det sätt du gjort. Vid fuskmisstanke lämnas misstankar samt berörda dokument över till universitetets disciplinnämnd.

## Föreslå ändringar
Denna handledning ligger på [GitHub](https://github.com/1ik415/Kursmaterial/blob/master/Laborationer/Laboration%203.md) om du vill föreslå ändringar eller hålla koll på vad de senaste uppdateringarna innebar.


## Uppgift 3.1 – Utskriftsvänlig version
För att det på ett snyggt sätt ska gå att skriva ut innehållet på din sida på en skrivare utan att få med en massa onödig information ska du nu skapa utskriftsvänliga stilmallar till din sajt. 

Arbeta gärna om typografin till något du tycker lämpar sig för utskrift och se till att ta bort onödiga delar så som exempelvis menyer. 

Länkar till externa webbplatser ska skrivas ut i sin helhet när man skriver ut sidan. 

PS. Du kan i alla webbläsare förhandsgranska hur din sida kommer att se ut vid utskrift så att du slipper ödsla träd på detta.

**Git-commit**

## Uppgift 3.2 - Copycat
Denna uppgift går ut på att du givet ett påbörjat html-projekt ska färdigställa det och efterlikna en prototyp så gott du kan. Projektet ligger på GitHub så din första uppgift blir att göra en "fork" av detta projekt så att du kan göra egna ändringar.

1. Logga först och främst in på GitHub och besök uppgiftens repro: [https://github.com/1ik415/Uppgift-3-3](https://github.com/1ik415/Uppgift-3-3)

2. För att göra en "fork" av reprot så klickar du på "Fork" i övre högra delen av webbsidan.

![Fork][github-fork]

3. Nu finns en kopia av ursprungsreprot på ditt GitHub-konto. Detta betyder att du också kan öppna detta i Cloud9.

4. Logga in på Cloud9 och skapa ett nytt, publikt workspace utifrån "uppgift3-3"

![Cloud9][c9-repro]

5. Du kan nu börja editera uppgiften. Observera att vi nu håller oss på "branchen" master. Vi kommer alltså inte att publicera resultatet via GitHub-pages.

Din uppgift blir att med hjälp av css skapa en sida som så nära du kan återskapar exemplet som du hittar i de skärmdumpar som finns i rootkatalogen ("IE7_hela.png" och "IE7_mouseover.png"). Till din hjälp har du fått html-filen till vilken du ska skriva css-filen "basic.css".
 **Du får INTE ändra i html-filen** utan du ska enbart editera den CSS-fil som finns. Sidan ska vara godtagbar i de senaste webbläsarna.

Layouten har en fast bredd och är centrerad i webbläsarfönstret.

I denna uppgift ska du **minst** göra en commit per isolerat delproblem. T.ex. en commit efter att du skapat den överliggande layouten, en när du fixat menyn, en när du fått in bakgrundsbilden etc.

De teckensnitt som använts är "Verdana" samt "Times New Roman". Hur du får fram vilka färger som använts kan du nog klura ut genom att använda ett lämpligt grafikverktyg.

När du är färdig så länkar du till uppgiften (en absolut länk till din Cloud9-preview) från din laborationsportal samt skriver ett kortare blogginlägg om uppgiften på startsidan på din blogg samt länkar till uppgiften.

**Git-commit**

**Git-push**

## Uppgift 3.3 – CSS Sprites
Växla nu tillbaka till arbetsytan för din laborationsportal.

För att få testa på att använda CSS-sprites så ska du nu lägga till lite enkla ikoner till din meny. 
[På denna länk hittar du en .zip-fil](https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/uppgift3.4.zip) som innehåller en sprite som du kan använda. Det går givetvis lika bra om du själv tar fram en sprite som du tycker passar bättre till din sidas layout. 

Verktyget [http://spritegen.website-performance.org/](http://spritegen.website-performance.org/) kan du då ha stor nytta av.

Om du använder den medföljande bildfilen så ser du att det finns två versioner av varje ikon. En svartvit och en färgad. Tanken är då att använda den svartvita på menyn och när muspekaren förs över ett menyalternativ så används den färgade ikonen. Bra att veta är att varje ikon i filen är 24\*24 pixlar stor och mellanrummet mellan ikonerna är 24\*24 pixlar.

**Git-commit**


## Postludium
Du har nu genomfört laboration 3 och du ska nu skapa en release för detta på GitHub

1. Logga in på GitHub och gå till repositoriet för laborationen.
2. Kontrollera att dina senaste ändringar finns tillgängliga på GitHub.
3. Klicka på "releases" ovanför fillistningen.
4. Välj att skapa en ny release.
5. Se till att "Tag version" blir `l03` (Ludvig, nolla, trea).
Välj en lämplig titel.
6. Publicera releasen

Var så god att påbörja arbetet med laboration 4!


[github-fork]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/github-fork.png

[c9-repro]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/c9-repro.png
