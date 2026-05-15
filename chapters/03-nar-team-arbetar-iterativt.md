# Kapitel 3: Vad som förändras när team arbetar iterativt

## Varför detta kapitel finns

I det tidigare samarbetet kunde juristen ofta möta ett mer samlat underlag. Arkitekt, kravfångare och verksamhetsspecialist hade hunnit beskriva processen, lösningen, informationsflödena och de viktigaste frågorna. Juristen kunde analysera ett tydligare **analysobjekt**.

När team arbetar iterativt förändras rytmen.

Lösningen växer fram i mindre steg. Krav delas upp. Användarresor justeras. Tekniska vägval prövas. Nya undantag upptäcks. Det betyder att juridiskt relevanta frågor inte alltid kommer som en färdig fråga till juristen. De uppstår ofta som små signaler i teamets löpande arbete.

Det här kapitlet handlar om den förändringen.

Poängen är inte att juristen ska vara med i varje detalj. Poängen är att organisationen behöver förstå var juridiken börjar synas när arbetet inte längre väntar på ett färdigt underlag.

## Lärandemål

Efter kapitlet ska läsaren kunna:

- förklara hur iterativt arbete förändrar när och hur juridiska frågor uppstår,
- beskriva vad en backlogg är i detta sammanhang och varför den kan innehålla juridiskt relevanta signaler,
- känna igen juridiska signaler i användarbehov, dataflöden, prioriteringar och tekniska vägval,
- se varför begränsad juristtid kräver tidig upptäckt snarare än ständig juristnärvaro.

## Innan vi börjar

I kapitel 2 såg vi att det tidigare arbetssättet ofta hade fungerande beredande roller. Arkitekt, kravfångare och verksamhetsspecialist hjälpte juristen genom att samla och strukturera underlaget.

Det behöver fortfarande ske.

Skillnaden är att underlaget inte alltid finns i en färdig form när frågorna börjar bli viktiga. I ett iterativt arbetssätt kan en liten ändring i en användarberättelse påverka ansvar, sekretess, personuppgifter eller dokumentation. Ett tekniskt test kan visa att data behöver hämtas från en annan källa än teamet först tänkt. En prioritering kan göra att en manuell kontroll skjuts upp till senare.

Varje sådan förändring kan verka liten. Tillsammans kan de flytta den juridiska bedömningen.

Därför behöver vi ett nytt begrepp: **juridisk signal**.

## Huvudförklaring

### Iteration: när arbetet rör sig i kortare steg

En **iteration** är en avgränsad arbetscykel där teamet planerar, bygger, testar, lär och justerar. I praktiken kan det handla om en sprint, ett kortare leveranssteg eller en återkommande arbetsperiod.

Det viktiga är inte exakt vilken agil metod organisationen använder. Det viktiga är att arbetet inte sker som en enda lång kedja från krav till analys till lösning till granskning. I stället sker arbetet i återkommande steg där teamet lär sig mer efter hand.

Det får flera konsekvenser för juridiken.

För det första blir underlaget mer rörligt. Det som verkar vara lösningen i vecka ett kan vara omformulerat i vecka tre.

För det andra uppstår frågor tidigare. Teamet behöver inte ha byggt hela tjänsten för att en juridisk risk ska börja synas.

För det tredje blir frågorna ofta mindre. I stället för en stor fråga som “är tjänsten rättsligt möjlig?” kan teamet ställa flera mindre frågor:

- Får vi använda denna uppgift i just detta steg?
- Behöver användaren informeras här?
- Vem ansvarar för detta beslut?
- Är detta ett beslut, ett stöd eller bara en presentation av information?
- Vilken dokumentation måste finnas om teamet väljer alternativ A i stället för B?

Dessa frågor är ofta mer användbara än en sen helhetsfråga. De gör det möjligt att påverka lösningen innan den har låst sig.

Men de skapar också ett kapacitetsproblem. Om varje liten fråga går direkt till juristen blir juristen snabbt en flaskhals. Om ingen fråga går till juristen förrän slutet riskerar teamet att bygga på fel antaganden.

Skalbar juridik behöver därför hitta mellanläget.

### Backloggen som plats där juridiken börjar synas

I många agila arbetssätt finns en **backlogg**. Med backlogg menar vi här en prioriterad lista över behov, förändringar, uppgifter, risker, förbättringar och frågor som teamet kan behöva arbeta med.

Backloggen är inte bara en teknisk arbetslista. Den visar ofta hur organisationen tänker om användare, information, beslut och nytta. Därför kan den också innehålla juridiska signaler.

En backloggpost kan till exempel säga:

> Som handläggare vill jag se tidigare ärenden för en person så att jag snabbare kan bedöma nästa steg.

Det kan låta som ett enkelt effektiviseringsbehov. Men ur juridiskt perspektiv kan flera frågor finnas under ytan:

- Vilka tidigare ärenden ska visas?
- Är alla ärenden relevanta för den nya bedömningen?
- Finns uppgifter som omfattas av särskilda begränsningar?
- Vem får se informationen?
- Behöver åtkomst loggas?
- Finns risk att handläggaren påverkas av uppgifter som inte bör användas?

Teamet behöver inte svara på allt direkt. Men det behöver känna igen att backloggposten bär juridiska signaler.

En annan backloggpost kan säga:

> Som användare vill jag få en preliminär rekommendation innan jag skickar in min ansökan.

Här kan signalerna vara andra:

- Är rekommendationen bara vägledning eller påverkar den användarens beslut?
- Kan användaren tro att rekommendationen är ett myndighetsbeslut?
- Vilka uppgifter används för att skapa rekommendationen?
- Vad händer om rekommendationen blir fel?
- Behöver text, ansvar och dokumentation utformas på ett särskilt sätt?

Det är här juristen riskerar att kopplas in för sent. Om teamet först bygger funktionen och sedan frågar “är detta okej?” kan svaret kräva större omtag. Om teamet däremot känner igen signalen tidigt kan frågan formuleras smalare och mer användbart.

### Juridisk signal: något som bör uppmärksammas

En **juridisk signal** är en händelse, formulering, förändring eller observation som tyder på att ett juridiskt perspektiv kan behövas.

En signal är inte samma sak som ett juridiskt problem.

Det är viktigt.

Om varje signal behandlas som ett problem blir arbetet tungt och defensivt. Om signaler ignoreras blir arbetet riskfyllt. En signal betyder bara: “Här kan det finnas något som behöver sorteras.”

Juridiska signaler kan uppstå i flera delar av arbetet.

I användarbehov kan signalen vara att lösningen påverkar en persons rättigheter, skyldigheter eller praktiska handlingsutrymme.

I informationsflöden kan signalen vara att uppgifter samlas in, kombineras, delas, visas, lagras eller återanvänds på ett nytt sätt.

I tekniska vägval kan signalen vara att systemet automatiserar något, skapar beroenden till en extern part eller gör det svårare att förklara hur ett resultat uppstår.

I prioriteringar kan signalen vara att teamet skjuter upp kontroller, dokumentation eller användarinformation för att leverera snabbare.

I verksamhetsregler kan signalen vara att ett undantag hanteras manuellt, informellt eller bara av vissa personer.

Juridiska signaler är ofta små. Därför upptäcks de bäst av personer som redan är nära arbetet: arkitekten, kravfångaren, verksamhetsspecialisten, produktägaren och teamet. Juristen behöver hjälpa dessa roller att förstå vilka signaler som är viktiga, men juristen kan inte vara den enda som ser dem.

### Fyra platser där juridiska signaler ofta uppstår

För att göra begreppet mer praktiskt kan vi dela in juridiska signaler i fyra platser.

#### 1. I användarresan

Användarresan visar vad en person, handläggare, medarbetare eller extern aktör gör i tjänsten. När den förändras kan juridiken påverkas.

Exempel:

Teamet lägger till ett steg där användaren kan se en sammanfattning av uppgifter som myndigheten redan har. Det kan förbättra service och minska fel. Men det väcker också frågor om vilka uppgifter som får visas, hur användaren förstår dem och vad som händer om något är fel.

Här behöver teamet inte direkt skriva en lång juridisk analys. Men någon behöver markera signalen:

> Ny visning av tidigare uppgifter. Kontrollera ändamål, behörighet, information till användaren och konsekvens om uppgifterna är fel.

Det är en användbar signal eftersom den kan prioriteras och föras vidare.

#### 2. I informationsflödet

Informationsflödet visar vilka uppgifter som hämtas, skapas, ändras, delas och lagras. För juristen är detta ofta en central källa till frågor.

Exempel:

Amin, arkitekten, upptäcker att teamet vill hämta uppgifter från ett annat system än det som först var tänkt. Tekniskt är det enklare. Men det förändrar också källan, kvaliteten, åtkomsten och kanske syftet med användningen.

Det kan vara en juridisk signal även om ingen ny funktion syns för användaren.

En enkel formulering kan vara:

> Ny datakälla föreslagen. Juridisk kontroll behövs innan lösningsval låses.

Det räcker inte som juridisk bedömning. Men det gör att frågan inte försvinner.

#### 3. I beslutslogiken

Beslutslogik handlar om hur systemet eller processen leder fram till ett beslut, en rekommendation, en prioritering eller ett urval.

Exempel:

Teamet vill att systemet ska sortera ärenden efter sannolik komplexitet. Tanken är att handläggare ska få hjälp att prioritera. Men om sorteringen påverkar väntetid, uppmärksamhet eller faktisk behandling kan den få rättsliga och etiska konsekvenser.

Här kan den juridiska signalen vara:

> Funktionen påverkar prioritering av ärenden. Klargör om den är administrativt stöd, handläggarstöd eller del av beslutspåverkan.

Det här är en fråga där ordvalen spelar roll. Ett team kan säga “det är bara stöd”, men om stödet i praktiken styr arbetet kan det behöva analyseras mer noggrant.

#### 4. I bortprioriteringar

Juridiska frågor uppstår inte bara genom det teamet bygger. De uppstår också genom det teamet väljer att inte bygga ännu.

Exempel:

Teamet prioriterar bort tydlig loggvisning för intern åtkomst eftersom funktionen inte ger direkt användarnytta i första leveransen. Det kan vara begripligt ur leveransperspektiv, men det kan samtidigt påverka spårbarhet, kontroll och förtroende.

En bortprioritering kan därför behöva dokumenteras:

> Kontroll- och spårbarhetsfunktion skjuts upp. Bedöm risk och om tillfällig manuell kontroll krävs.

Det här är särskilt viktigt i organisationer där juristen har begränsad tid. Juristen kanske inte kan delta i varje prioriteringsmöte. Men om teamet markerar juridiskt relevanta bortprioriteringar kan juristen fokusera på de viktigaste.

## Exempel: Marias vecka förändras

På Myndigheten för samhällstjänster arbetar tre team med samma digitala tjänst.

Tidigare hade Maria ofta fått en samlad fråga från Amin och Sofia:

> Vi planerar denna lösning. Här är processen, informationsflödet och de viktigaste undantagen. Kan du bedöma om vi kan gå vidare?

Nu kommer frågorna på ett annat sätt.

På måndagen ser Sofia att en användarberättelse har ändrats. Användaren ska inte bara skicka in uppgifter, utan också få en preliminär rekommendation. Sofia markerar detta som en juridisk signal eftersom funktionen kan påverka hur användaren förstår sin situation.

På tisdagen ser Amin att teamet vill hämta uppgifter från ett annat system. Han markerar en signal om ny datakälla och ändrat informationsflöde.

På onsdagen berättar Lena att verksamheten hanterar ett undantag på olika sätt i olika regioner. Teamet hade trott att regeln var enhetlig. Nu blir det tydligt att lösningen kan behöva hantera flera praktiska varianter.

På torsdagen prioriterar Erik bort en kontrollfunktion till senare leverans. Han gör det för att teamet ska hinna testa huvudflödet. Lena påpekar att kontrollen kan vara viktig för spårbarheten.

Inget av detta är nödvändigtvis en akut juridisk kris. Men tillsammans visar det att lösningen rör sig. Om Maria bara får frågan i slutet kan hon behöva granska en lösning som redan bygger på flera rättsligt relevanta antaganden.

I ett skalbart arbetssätt behöver Maria inte vara med på alla möten. Men teamen behöver kunna samla signalerna så att hon kan använda sin tid rätt.

Ett praktiskt sätt är att teamet skapar en enkel juridisk signalrad i backloggen:

| Signal | Källa | Möjlig juridisk fråga | Föreslagen hantering |
|---|---|---|---|
| Preliminär rekommendation till användare | Användarberättelse | Kan uppfattas som myndighetsbeslut eller styrande besked | Kort juridisk avstämning innan design låses |
| Ny datakälla | Arkitekturval | Ändamål, åtkomst, kvalitet och ansvar | Ta upp på juridisk riskgenomgång |
| Regionala undantag | Verksamhetsregel | Likabehandling, dokumentation och beslutsstöd | Förtydliga verksamhetsregel innan utveckling |
| Kontrollfunktion skjuts upp | Prioritering | Spårbarhet och ansvar under övergångsperiod | Beslutsnotering och riskacceptans |

Tabellen är inte en juridisk analys. Den är ett sätt att göra signalerna synliga. Det gör det möjligt för Maria att avgöra vilka frågor som kräver hennes direkta tid.

## Vanliga misstag

### Misstag: Teamet väntar på en färdig juridisk fråga

**Varför det händer:**  
I tidigare arbetssätt var juristen ofta van att få ett sammanhållet underlag. Teamet kan därför tro att juridiken inte ska kopplas in förrän frågan är färdigformulerad.

**Hur man undviker det:**  
Inför ett enkelt sätt att markera juridiska signaler tidigt. Frågan behöver inte vara färdig. Det räcker att teamet kan beskriva vad som förändrats och varför det kan vara relevant.

### Misstag: Varje signal skickas direkt till juristen

**Varför det händer:**  
När organisationen blir mer uppmärksam på juridik kan den överkompensera. Allt som låter juridiskt skickas till juristen, vilket snabbt skapar köer.

**Hur man undviker det:**  
Skilj mellan signal, fråga och bedömning. Alla signaler ska synliggöras, men inte alla kräver omedelbar juristtid. Vissa kan samlas till en riskgenomgång eller hanteras med tidigare vägledning.

### Misstag: Backloggen behandlas som rent teknisk

**Varför det händer:**  
Backloggar används ofta för utvecklingsarbete. Då kan de uppfattas som teamets interna plan, inte som en plats där rättsligt relevanta antaganden formas.

**Hur man undviker det:**  
Lägg till enkla markörer för juridisk relevans, till exempel “påverkar uppgifter”, “påverkar beslut”, “påverkar åtkomst”, “påverkar dokumentation” eller “påverkar ansvar”.

### Misstag: Små ändringar dokumenteras inte

**Varför det händer:**  
Iterationer uppmuntrar snabba justeringar. Det kan göra att teamet ser förändringar som för små för att dokumentera.

**Hur man undviker det:**  
Dokumentera inte allt, men dokumentera förändringar som flyttar juridiska antaganden. Skriv kort: vad ändrades, varför, vilken risk eller fråga uppstod och vem behöver följa upp.

## Övningar

### Övning 1: Hitta juridiska signaler i en backlogg

Läs backloggposterna nedan. Markera vilka som kan innehålla juridiska signaler och skriv en kort signalformulering.

1. Som användare vill jag kunna se tidigare inskickade uppgifter.
2. Som handläggare vill jag få en varning om ärendet verkar avvika från normalfallet.
3. Som produktägare vill jag skjuta upp logggranskning till nästa leverans.
4. Som systemadministratör vill jag ge fler interna användare åtkomst till testmiljön.
5. Som användare vill jag få en preliminär bedömning innan jag skickar in ansökan.

Försök att inte lösa frågorna juridiskt. Målet är bara att upptäcka signalerna.

### Övning 2: Skillnad mellan signal och fråga

Välj en juridisk signal från din egen organisation eller från övning 1.

Skriv först signalen i en mening:

> Något har förändrats eller upptäckts som kan vara juridiskt relevant.

Skriv sedan en möjlig juridisk fråga:

> Vad behöver vi förstå, bedöma eller dokumentera?

Exempel:

- Signal: Teamet vill hämta uppgifter från en ny datakälla.
- Fråga: Behöver vi bedöma ändamål, åtkomst, kvalitet och ansvar innan lösningsvalet låses?

### Fördjupning: Skapa en signalrad

Skapa en enkel signalrad för ett pågående eller fiktivt initiativ:

| Signal | Var upptäcktes den? | Varför kan den vara juridiskt relevant? | Rekommenderad nästa hantering |
|---|---|---|---|
| | | | |

Diskutera särskilt om signalen kräver juristens tid direkt eller om den kan samlas till ett senare juridiskt forum.

## Snabb sammanfattning

- Iterativt arbete gör att juridiska frågor uppstår tidigare, oftare och i mindre delar.
- En backlogg kan innehålla juridiskt relevanta signaler även när den ser teknisk eller verksamhetsnära ut.
- En juridisk signal är inte samma sak som ett juridiskt problem; den är en markering om att något kan behöva sorteras.
- Juridiska signaler uppstår ofta i användarresor, informationsflöden, beslutslogik och bortprioriteringar.
- Begränsad juristtid gör det viktigt att teamet kan upptäcka och samla signaler innan juristen behöver ta ställning.

## Quiz/reflektionsfrågor

1. Varför blir juridiska frågor ofta mindre men fler i ett iterativt arbetssätt?
2. Vad är skillnaden mellan en juridisk signal och en juridisk bedömning?
3. Vilka roller i din organisation är bäst placerade för att upptäcka juridiska signaler tidigt?
4. Vilka backloggposter i din organisation skulle kunna innehålla dolda juridiska antaganden?
5. När bör en juridisk signal skickas direkt till juristen, och när kan den samlas till ett återkommande forum?

## Nästa steg

Nu har vi sett hur juridiska frågor förändras när arbetet blir mer iterativt. Nästa kapitel går vidare till den praktiska kapacitetsfrågan: juristen är ofta en begränsad resurs. Därför behöver organisationen inte bara upptäcka fler juridiska signaler, utan också avgöra hur juristens tid ska användas strategiskt.
