**1. Beskriv skillnaden mellan vattenfallsmodellen och agil metodik.**  
När bör man använda vilken, och varför?  

Att bygga med Vattenfall innebär att jag bygger färdigt hela produkten innan jag lanserar den då varje  
fas måste vara utfört innan man kan gå vidare till nästa fas men om jag bygger med Agile innebär det  
att jag bygger appen i flera steg och lanserar den redan vid första steget. 

Med vattenfall planerar man och bestämmer allt innan man börjar koda, Behovsanalys,  
Kravspecifikation och design, Programmering och utveckling, Kvalitet och tester. Till sist leverans och  
sedan underhåll av appen så länge den är i bruk. Här kan man inte gå tillbaka och utföra ändringar.

Med Agil är det samma process som vattenfall dock med ett steg i taget. 
Här planerar man och bestämmer under arbetets gång hur man vill bygga appen. Om jag ska börja  
med steg 1 som till exempel är inloggning till appen, behöver jag köra analys och datainsamling,  
kravspecifikation och design, programmering och utveckling, kvalitet och tester och sedan lansera.  
Fördelen med Agile är att kunden kan vara med och testa efter lanseringen och vara med och påverka om man vill göra ändringar.

Vattenfall hade gått snabbare, men för mig som nybörjare hade jag valt agile i utbildningssyfte då jag  
får vattenfall på köpet och där kunden är med och bestämmer och har möjlighet till ändringar under processens gång.



**2. Vad är ett Git-commit och varför är det viktigt?**  
Beskriv ett verkligt scenario där Git hjälper dig undvika problem.  

Git-commit är en snapshot av ett projekts samtliga filer, den sparar alla ändringar som har gjorts där  
man kan se vem som gjort ändringen, när och vad som är ändrad. När man gör en commit får  
commiten en specifik id och som skapar en historik där man kan gå tillbaka och se alla ändringar som  
har gjorts och som man kan återanvända om man gör något fel, så kan man alltid via commit id:en gå  
tillbaka till en äldre version istället för att börja om från början vilket är viktigt speciellt i ett större  
projekt. Ett scenario är där ett team jobbar på ett projekt, en i teamet råkar förstöra en kod, eller  
råkar ta bort en fil, då kan man bara gå tillbaka till en commit innan och fixa till koden eller återställa filen enkelt.




**3. Vad innebär samarbete med GitHub? Vad är pull requests, branches och merge?**  

Samarbete med github innebär att jobba i team på ett projekt, där man delar upp arbetet och skapar  
egna branches som man jobbar med och sedan skickar en pull request som sedan granskas och  
mergears. T.ex. bankappen där en ansvarar för inloggning via fingeravtryck, en annan via faceid,  
någon via lösenord osv. som man sedan slår samman.


**Pull request**  
En pull request (PR) är en begäran som skapas när man commitar och pushar en ändring i en branch.  
Och den skapas för att man ska kunna granska och godkänna ändringen innan den slås samman med huvudbranchen main/development.  

**Branches**  
En branch är som en mapp där man har ett projekts alla filer i, där main eller development är huvudversionen.  
Det är OK att jobba med en branch om man är själv, men bättre med branches. Men om man är flera behöver man  
skapa nya branches baserad på main/development, vilket är en kopia där man gör ändringarna först för att sedan  
commita, pusha, PR skapas, granskas och sedan slås samman med main/development. Det är branches som gör det möjligt  
att jobba med en kopia som låter dig testa så att allt fungerar utan att påverka eller förstöra huvudversionen.


**Merge**  
Merge är att slå samman, och det gör man från en branch till main/development branchen,  
så att ändringar man gjort i branches blir en del av huvudbranchen.