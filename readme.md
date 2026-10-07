# Laboration 2

## Webbplatsen _Stephenie Knutsson_

Webbplatsen är resultatet av laboration 1 och 2 i delkursen _Introdkution till webbutveckling med HTML, CSS och JavScript_ som ingår i **Mittuniversitetets* 2-åriga program [_Webbutveckling_](https://www.miun.se/utbildning/program/webbutveckling/). 

Webbplatsen består av tre sidor där jag erbjuder dels en kort presentation av mig själv, samt en av mina stora passioner, följt av ett kontaktformulär. Syftet med uppgiften har varit att skapa förståelse för en webbplats grundläggande HTML-struktur med fungerade navigering, korrekt användning av semantiska element samt tillämpning av tillgänglighet. 

### Tekniker

Jag har använt mig utav HTML-kod och en liten touch av CSS för att testa funktionen av <rel link> på ett redan befintigt projekt. 

[Kolla in min webbplats på Netlify]()
[Kolla in min webbplats på xxx]()

_Följande stycke är en del av uppgiftens examinering där jag besvarar ett gäng frågor rörande versionshantering i Git och GitHub._ 

#### Vad är skillnaden mellan git add och git commit?
Med **git _add_** lägger man till ändrade filer och kod till det som kallas _staging area_, vilket gör att Git kommer "spåra" de exakta ändringar som gjorts. **Git _commit_** är snarare ett sorts "spara"-kommando genom vilken man sparar sitt befintliga arbete (eller filer) utifrån det stadie det befinner sig i just nu. Om man bara använder sig av **git _commit_** utan att först genoföra **git _add_** sparas endast enskilda ögonblicksbilder av projeketet utan att egentligen spåra de ändringar som genomförts under arbetets gång. 

#### Varför använder man branches istället för att jobba direkt i main?
Det möjliggör tester och experimentering av kod och olika element utan att påverka själva grundkoden. Det tillåter även att man - i ett projektarbete bestående av flera aktörer - kan arbeta med olika delar av kod, i olika språk, med olika verktyg utan att man trampar varandra på tårna eller riskerar att förstöra/störa varandras arbete. Det är även tacksamt när man underhåller och felsöker en webbplats på så sätt att man lätt kan se vart i koden en viss bug uppstått och därmed enklare åtgärda problemet och mer tidseffektivt kan publicera nya versioner av webbplatsen. 

#### Vad händer rent praktiskt när man gör en merge?
Genom att sammanföra en _developer_ branch med _main_ branch **sammanför** man de ändringar och commits som genomförts i de båda förgreningar till en och samma branch - ofta till _main_.

#### Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex. Netlify?
Att _pusha_ sitt repository till Gitub (från Git) handlar om att man "sparar" repot till ett molnbaserat lagringsutrymme. Det är ingen riktig webbplats och kan väljas att göras privat eller publikt. Publicering direkt på en plattform (såsom Netlify) innebär istället att man faktiskt publicerar repot som en webbplats vilken vem som helst har åtkomst till. 

#### Om du vill exkludera någon fil i projektet från versionshanteringen, hur gör du då?
Jag döper helt enkelt om filen och ger den filändelsen .gitignore vilket gör att Git då automatiskt ignorerar denna. 