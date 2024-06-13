![image](https://github.com/Trlton/Noter/assets/124626087/905cd305-ed5a-47d9-b692-2ed94ebc2833)# Begrebsliste

Syntaks
Dette er en form for grammatik i kodesprog. Dette indeholder bade indents, placering af paranteser () og kolon : og mange andre ting.
  
Dette er et eksempel fra player. Her er den øverste linje korrekt, men nederste er fon xcgdsfdr55rkert syntaks. 
+= er det samme som at skrive x = x+y   #Dette er korrekt syntaks
x=+y, hvilket gør at x = y.       #Dette er ukkorekt I forhold til formodet formål
Et andet eksempel er:
Hej = ”hej”
Def hejsa (hej):
	Print(hej)
Dette får outputted hej i konsol
Hej = ”hej”
Def hejsa (hej):
Print(hej)
![image](https://github.com/Trlton/Noter/assets/124626087/6c74ad71-8c93-42c9-bb0d-38447be6dfca)

I det ene tilfælde bliver hej printet når man kører funktionen hejsa. I den anden printes det ude af funktionen, og funktionen har altså ingen funktion. Derudover siger den også fejl, da der ikke er indsat noget i funktionen.


2. Increase/Decrease indent
- Indents fucking matter (i python)
 De benyttes særligt i kategorisering af kode, særligt bruger classes og funktioner det. 

 En indent er at koden er rykket mod højre

Eksempel:
 
I grupperingen class har alt det i den gruppering en indent til højre.
Inde i den gruppering er der endnu en gruppering. Dette er en __init__ funktion. Den funktion er en form for gruppering, hvor det i funktion er indented.
Hvis man bagefter skriver print(”hej”) ude af grupperingerne vil den blive kørt. Men hvis man gør det inde i fx classen, så ville den kun blive kørt hvis classen bliver kørt. Det samme med funktionen.

3. Placering af parenteser
Når man skriver kode er det vigtigt at placere paranteser korrekt. Paranteser bliver brugt til et par ting.
	Til matematik (som i matematik) i forhold til rækkefølge
 
	At lave funktioner
 
Her er det der skrives inde i funktionens paranteser de lokale variabler der benyttes. Senere kan man så vælge hvad i dette tilfælde blocks er.

	lave instances, fx kalde et objekt eller til datatyper. 
Man kan kalde et objekt, og i paranteserne give de værdier objektet skal have.
 
 Derudover kan man fx lave str(x) som giver ”x”
 
Hvor at det indeni omdannes til en integer






4.Kode kommentar
For at gøre sin kode mere forståelig benytter man kommentarer. I python er syntaksen ”#”. Dette benyttes til at lave notes rundt omkring, som ikke bliver kørt.
 



5.Variable
      En variabel er ligsom i matematik et navn som har et eller andet i sig. Det kan være alt fra at x = 1, til at x har en eller anden funktion.
Variabel med funktion: 
 
Det er en måde at komprimere mængden af kode, samt også at kunne påvirke variabler senere.
Fx hvis man har en funktion for playerens liv. Så vil man måske gerne have man har et antal hp, i stedet for at man bare er død ved 1 skade. Her kan man oprette en hp variabel:
 
Som man så senere kan ændre på ved at benytte playerHealth: playerHealth -= 1. Dette vil gøre at playerHealth er 1 mindre, og i dette tilfælde 9.
Man kan også ændre variabler undervejs. X kan fx være = 1 til at starte med. Senere kan den være lige med print(”Hello world”


6.Datatyper
Data typer er forskellige typer data kan værre. Fx om 9 er et tal eller bogstav/tegn. Dette er relevant når man i visse funktioner eller handlinger har brug for at dataer er samme type, at de gør noget og returner en specefik type, eller at man skal konvertere en data til en anden type. Fx fra intigeren 9 til string(tekst) ”9” .

7.Float
     Denne datatype er alle reelle tal. Altså positive og negative  tal med decimaltal
8.Int
    Denne datatype er alle hele tal. Altså tal uden decimaltal, som er -8, 6, 10,        
    -6940 osv. 

9.Char
    Ved brug af chr() konverterer man en intiger om til et tegn. Dette tegn kan bruges til at komme tilbage til det originale tal med ord()
Fx:
Kode:
 
Output
 

10.Boolean
       En Boolean er en datatype, som enten kan være TRUE eller FALSE, som er det samme som 1 og 0. Det er fx noget der kinda benyttes i if-statements.
Fx:

 if x = 1   #Hvis x er 1 er dette true, så funktionen executer det den har i sig
             Do shit
Det basically et ja/nej svar 

11. String
       Denne datatype indeholder tekst. Det er fx ”hello world” eller ”9” som  er ikke tallet men teksten 9. Man kan omdanne noget til en string ved hjælp af str(), hvor det indeni omdannes.

12.If sætning
	Denne tjekker om et statement er true eller false. Hvis statement er 
	True excecuter den koden i if-statement. Hvis ikke skipper den det.
	Eks: 

Hvis self.acc.x er mindre end 0, så vil koden under i indented køres. Altså så vil dataen i self.rect.right nu være lig med dataen block.rect.left



13. While
          Denne gør, at så længde et statement enten er true eller false, så kører 
          koden inde i dens gruppering(indent).  
Så længde der ikke er noget inde i while loopet vil dette kode køre igen og igen, indtil noget i koden gør at det statement i starten ikke længere er rigtigt. Så stopper den loopet ved næste omgang.

14.For loop 
Et for loop er en form for kontrolstruktor, som tillader gentagelser af noget kode. Det bruges ofte til at iterere over elementer i en sekvens, fx i en tuple eller dictionary / andre itererbare objekter. I hver gennemgang får det loop en værdi fra et bestemt nr i den dict/tuple, og koden udføres med den kode. Derefter når det gentages går den videre til næste, indtil der ikke er flere der bliver kaldt på.
 
I denne er det hver gang der er en event i en liste af events i pygame.event.get, hvor hvis man fx har trykket WASD, så får den 4 events, og for hver af dem tjekkes der om der bliver trykket ESC knappen.




15.Pseudo kode

Pseudo kode er en slags skitsering af et program. Man benytter det til at gøre programmet / en algoritme / funktion / whatever mere forståeligt for mennesker. Det bruges også til bedre at få en forståelse af hvad man vil have til at ske i et program hvornår:
Eksempel: (stjålet fra https://cdn-dk-fk.clio.me/pseudokode.jpg)
 
16.Flow chart
Et flowchart er en grafisk repræsentation af noget kode. Det viser hvordan programmet fungerer, hvad den gør og i hvilken rækkefølge. 
Her til højre er et eksempel på et meget simpelt flowchart.
Den viser rækkefølgen af hvad den gør. Det er med til at skabe en bedre og nemmere forståelse af kode, både for dem der skal forstå en andens, og for at kortlægge hvordan programmet skal fungere.

Spørgsmål:
I hvilke stadier af programmeringen af et program bør man lave et flowcharts af et program?
17. Import af libraries
	Et library er en række functions som hvis man importer kan benytte. Måderne man kan import et library er adskillige.
1: Import x (Importer alt)
2: from x import all (Dette importer alt) 
3: from x import y, a, b, c  (Dette importer bestemte dele af et library)
Derudover kan man import noget men selv give det et andet navn:
import x as z
Eksempel på import:
 
Her er 3 af de fire metoder.

18. Framework (fx pygame)
	Et framework er noget som giver et standard grundlag for udvikling. Dette er fx pygame, fullstack, Et framework er et ”stort sæt værktøj” som kan bruges til at lave et fuldt program fra start til slut. Adskillelsen fra libraries er, at libraries er mere limeted, og giver mere værktøjer til specifikke ting med specifikke funktioner.
19.Function
      Functions er en række kode som bliver kørt når man skriver en bestemt variabel. Dette kunne fx være 
def x (y, a)
        print(str(y)+str(a))
Nu kan man så skrive x og give den to argumenter for de lokale variabler y og a.
Dette kunne fx være x(6,9). Det der ville blive printet er 69 som string.
Eksempel fra git:
 
Når draw function bliver kørt, giver man to argumenter, som er screen og camera. Så altså draw(ens screen, ens camera). Det udfører så koden i dens indent. Her er screen og camera lokale variabler, hvis data bliver givet til den.

20.Input parameter
Input parametrer er de argumenter som funktioner tager imod i paranteserner. 
 
Her er der eskemplet at funktionen tager imod 3 input parametrer, hvor man i main koden skriver funktionsnavnet, og giver den de tre værdier som er input parameterne.

21.Output(return) parameter
Dette er en made hvorpå man kan, i funktioner, få en værdi ud af funktionen, altså en bestemt af dem. Hvis man har 3 variabler i en funktion, og gerne vil have værdien i en og bruge den ude af den funktion, så kan man return den ene variabel som set herunder:
 
I eksemplet er der brugt en return output dims, hvor der er skrevet return total_price. Så kan man tage resultatet og bruge den andre steder. 

22.Global variable
- Globale variabler er variabler som alle ting i hele ens venv har adgang til. De er definerede uden for klasser og funktioner. Disse kan tilgås og ændres af alt i koden, herunder også inden i funktioner.
23.Lokal variable
- lokale variabler er variabler defineret inden for klasser eller funktioner. Disse kan kun tilgås inden i den funktion/class. Efter det har kørt slettes de lokale variabler. De bruges altså til midlertidige opgavaer. Her får funktioner og klasser ofte værdier udefra som arguments. Altså i fx funktion(argument1, argument2, .. , .. , osv)



24. Debugging
Debugging er hvor man prøver at udbedre bugs i programmet. Til dette kan man bruge debugging tool i pycharm, hvor man kan se alle variablers værdier undervejs hvor man vælger. Derudover kan man også benytte sig af print funktioner til samme formål.

25. Versionsstyring (git)’
Man kan benytte versionsstyring, gennem git, til at backup sin kode, og have flere versioner undervejs. Kinda ligesom quiksaves man kan gå tilbage i. Dette er en måde at sikre sig, at man ikke kommer til at fucke det helt op. Derudover skriver man kommentarer til hver version, som betyder man får et bedre overblik over hvad er ændret + hvad kunne have gået galt.

26.OOP(Objekt Orienteret Programmering)
Denne type programering handler om at lave klasser, hvor andre klasser nedavre de klassers stuff. Derefter kan man give argumenter til den klasse der har nedarvet, og lave objekter / instances inde i spillet. Dette kan man gøre igen og igen, da man bare genbruger det.
 
På den måde følger man også D.R.Y.
Man kan fx så have 40 objekter af en peter hvis man har lyst, uden at skrive ret meget mere kode end til en.
Eksempel fra projekt:
 
Her er klassen player som har nedarvet stuff fra GameObject. 
 
Derefter er playerclass blevet brugt til at skabe et objekt.
 
↑↑↑OBJEC↑↑↑



27.Class(Klasse)
       En klasse er en form for grupering af kode, som bruges til at skabe objects oftest. Det er en gruppering af funktioner/metoder og variabler som netop klassens senere constructed object har af egenskaber.

28.Object
Dette er en instance af en klasse. Der er altså blevet brugt en constructor til at lave et object ud fra en klasse. Selve objected er mere specifik en klassen, da man giver arguments som klassen bruger til netop dette objekt. Det kan fx være man har en person klasse, og i den klasse har den attributes alder og køn.
Derefter kan man lave en instance af objektet, hvor man giver den alderen 27 og kønnet mand.
Et andet eksempel er fra projektet:
 
Her er der lavet et playerobject ud fra playerclass. Playerobjected giver data til class functions, så den fx spawner I midten af banen, samt har en bestemt hitbox. Man kunne lave endnu et player_object, men her hvor den spawnede langt derfra og havde en helt anden hitbox. Helt uden at ændre på class.

29.Constructor
Constuctoren er __init__ som star for initialize. Denne bliver altid kaldt automatisk, når der bliver lavet en instance af en class. 
Dette kan man fx se her: 
 
Det gør så man kan give nødvendige atributes og hvilken som helst nødvendig setup eller startup tasks.
