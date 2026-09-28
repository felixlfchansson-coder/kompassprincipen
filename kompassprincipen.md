---
affiliation: Institutionen för narrativ gränssnittspsykologi och digital
  maritim kognition
author: Professor Dr. Felix J.A. Hansson
date: September 2026
lang: sv
report_number: Forskningsrapport 02/2026
status: Konceptuellt forskningsmanuskript
subtitle: Riktning som sekundärt narrativt orienteringssystem
title: Kompassprincipen
version: 2.0
---

```{=html}
<!--
KOMPASSPRINCIPEN · MASTERFIL · VERSION 2.0

SIDA 1–47 och page-break-divarna är avsiktliga ankare för den framtida
47-sidiga PDF-utgåvan. Markdownfilen är masterkällan.
-->
```
```{=html}
<!-- SIDA 1 -->
```
# Kompassprincipen

## Riktning som sekundärt narrativt orienteringssystem

**Professor Dr. Felix J.A. Hansson**\
*Institutionen för narrativ gränssnittspsykologi och digital maritim
kognition*\
**Forskningsrapport 02/2026 · Version 2.0 · September 2026**

> *Farkosten förklarar varför resan finns. Kompassen förklarar hur resan
> får riktning.*

### Författarens anmärkning

Detta manuskript presenterar **Kompassprincipen**, en konceptuell modell
för hur riktning uppstår och kommuniceras i digitala och narrativa
miljöer. Principen utvecklades som en följd av en offentlig invändning
mot Farkostprincipen.

Kompassprincipen ska inte förstås som ett påstående om att webbplatser
behöver bokstavliga kompasser.

Detta anges på första sidan av skäl som senare kommer att framgå.

### Forskningsstatus

Kompassprincipen presenteras här som en **konceptuell och prövbar
modell**. De termer som introduceras i rapporten är författarens
analytiska begrepp och ska inte förväxlas med etablerad terminologi inom
människa--datorinteraktion, informationsarkitektur eller psykologi.
Modellens fortsatta värde är beroende av empirisk prövning.

### Nyckelord

*narrativ orientering · digital navigation · riktning ·
informationsarkitektur · farkostprincipen · kompassfunktion ·
riktningsosäkerhet · användarupplevelse*

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 2 -->
```
# Sammanfattning

**Abstract**

Farkostprincipen formulerades för att beskriva relationen mellan en
digital plats, dess identitet och den resa som denna identitet erbjuder
användaren. Modellen innehöll emellertid en lucka. En individ kan förstå
både platsen och resans existens utan att därför förstå **vilken
riktning som är meningsfull**.

Kompassprincipen föreslår att digitala miljöer med flera möjliga vägar
skapar ett sekundärt orienteringsproblem. Problemet uppstår inte därför
att användaren saknar rörelseförmåga, utan därför att rörelsen kan ske i
flera riktningar. Ett **kompasselement** är varje signal som hjälper
användaren att relatera sin nuvarande position till en möjlig
destination.

Principens grundformulering är:

> **När en individ befinner sig i ett narrativt eller digitalt system
> med flera möjliga riktningar uppstår ett sekundärt orienteringsbehov.
> Ett riktningsgivande element reducerar denna osäkerhet genom att
> etablera en begriplig relation mellan nuvarande position, möjlig
> handling och föreställd destination.**

Manuskriptet skiljer mellan fysisk riktning, funktionell riktning och
narrativ riktning; introducerar begreppen **kompasslös drift**, **falsk
nord**, **kompassavvikelse** och **riktningskonflikt**; samt integrerar
Farkostprincipen och Kompassprincipen i **det Hanssonska
orienteringssystemet**.

Modellen presenteras som en konceptuell syntes och som en uppsättning
empiriskt prövbara hypoteser. Den gör inte anspråk på att
Kompassprincipen redan är empiriskt bevisad. Tvärtom argumenteras för
att dess värde beror på om de prediktioner som här formuleras kan
överleva experimentell prövning.

### Rapportens struktur

1.  Inledning och problemformulering\
2.  Kompassprincipens teoretiska modell\
3.  Riktningsmekanismer och orientering\
4.  Tillämpningsområden och konsekvenser\
5.  Empirisk prövning och falsifierbarhet\
6.  Begränsningar\
7.  Vanliga invändningar och avgränsningar\
8.  Begrepp och formalisering\
9.  Diskussion\
10. Slutsats

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 3 -->
```
# 1. Inledning och problemformulering

## 1.1 Problemet som Farkostprincipen lämnade efter sig

Farkostprincipen började med en enkel distinktion: en digital miljö kan
vara mer än en samling funktioner. Den kan också presentera en
identitet, ett ursprung och en föreställd destination. Farkosten blev
metaforen för förbindelsen mellan dessa delar.

Den modellen besvarade emellertid huvudsakligen frågan **varför resan
finns**.

Den besvarade inte tillräckligt tydligt frågan **hur en resenär väljer
riktning**.

Det är möjligt att befinna sig på en fullt fungerande farkost, förstå
varför den existerar och ändå inte veta åt vilket håll man bör färdas.
Detta är inte en semantisk detalj. Det är skillnaden mellan
**mobilitet** och **orientering**.

En meny gör det möjligt att klicka. Det betyder inte att användaren vet
vilket alternativ som är relevant. En lista med berättelser gör det
möjligt att välja. Det betyder inte att läsaren förstår var det är
meningsfullt att börja. En sökruta gör hela databasen tekniskt åtkomlig.
Den talar fortfarande inte om vad som är värt att söka efter.

Farkostprincipens första version behandlade ofta sådana funktioner som
delar av samma övergripande resa. Det var för grovt.

Resans existens och resans riktning måste skiljas åt.

Det är ur denna separation Kompassprincipen uppstår.

Den nya principen ersätter därför inte Farkostprincipen. Den begränsar
den. Där Farkostprincipen tidigare riskerade att förklara för mycket,
tilldelas den nu en snävare uppgift: att beskriva hur en miljö kan
etablera ett begripligt samband mellan plats och resa.

Kompassen tar därefter vid.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 4 -->
```
## 1.2 Den von Gustafssonska interventionen

Kompassprincipens omedelbara ursprung kan dateras till ett offentligt
samtal där kritikern **Joel von Gustafsson** ifrågasatte
Farkostprincipens terminologi.

von Gustafsson frågade:

> *"Varför inte kalla det Kompassprincipen?"*

Frågan var avsedd som kritik. Den byggde dessutom på en delvis felaktig
förståelse av Farkostprincipen, eftersom farkosten och kompassen inte
fyller samma funktion.

Dess konsekvenser gjorde det inte.

Frågan isolerade, sannolikt oavsiktligt, ett problem som den
ursprungliga modellen hade behandlat som en del av någonting annat. Om
farkosten representerar förmågan att förstå resans sammanhang, vad
representerar då förmågan att avgöra riktning inom detta sammanhang?

Svaret kunde inte rimligen vara farkosten själv.

En båt kan transportera en människa österut, västerut eller i cirklar.
Transportmedlet innehåller ingen nödvändig uppgift om den riktning som
bör väljas. På motsvarande sätt kan en webbplats erbjuda länkar utan att
länkarna skapar begriplig orientering.

von Gustafsson hade därmed separerat **transportfunktionen** från
**riktningsfunktionen**.

Vetenskapshistorien innehåller exempel på frågor vars betydelse blivit
större än frågeställaren ursprungligen avsett. Till denna kategori måste
vi nu, något motvilligt, lägga Joel von Gustafsson.

Detta innebär inte att hans kritik av Farkostprincipen därmed var
korrekt i sin helhet.

Det innebär att en av hans frågor var bättre än hans svar.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 5 -->
```
## 1.3 Vad menas med riktning?

Ordet *riktning* verkar självklart tills man försöker definiera det.

I fysisk navigation beskriver riktning en relation mellan positioner i
rum. Norr, syd, öster och väster är klassiska exempel. I digitala
miljöer är riktningen sällan geografisk. När en användare väljer
"Bibliotek", "Om", "Nästa kapitel" eller "Fortsätt läsa" sker ingen
nödvändig fysisk förflyttning.

Ändå förändras användarens position i systemet.

Kompassprincipen använder därför en bredare definition:

> **Riktning är en begriplig relation mellan ett aktuellt tillstånd och
> ett möjligt efterföljande tillstånd.**

Tre former skiljs åt.

**Spatial riktning** avser rörelse genom ett rum eller en representation
av rum.

**Funktionell riktning** avser rörelse mot en uppgift: logga in, hitta
en text, genomföra ett köp, ändra en inställning.

**Narrativ riktning** avser rörelse mot ökad förståelse, fördjupning,
progression eller meningsfull fortsättning.

Samma gränssnitt kan innehålla alla tre samtidigt.

En länk märkt "Nästa" har funktionell riktning eftersom den erbjuder en
handling. Om den står längst ned i ett kapitel har den även narrativ
riktning. Om kapitlen representeras som platser på en karta får länken
dessutom spatial karaktär.

Kompassprincipen handlar inte om att reducera dessa till en enda
kategori.

Den handlar om vad de delar: de hjälper användaren att svara på frågan
**"Vad betyder det att gå vidare härifrån?"**

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 6 -->
```
## 1.4 Primär och sekundär orientering

För att undvika att Farkostprincipen och Kompassprincipen kollapsar in i
varandra krävs en tydlig distinktion mellan två orienteringsnivåer.

**Primär orientering** handlar om situationen som helhet. Användaren
behöver förstå ungefär var hon befinner sig, vad miljön är och vilket
slags aktivitet den möjliggör.

**Sekundär orientering** uppstår när den primära situationen redan är
tillräckligt begriplig men flera fortsättningar är möjliga.

En läsare kan exempelvis förstå att hon befinner sig i ett digitalt
bibliotek. Den primära orienteringen är då relativt stabil. Men
biblioteket kan innehålla hundratals texter, kategorier och ingångar.
Frågan blir inte längre *"Vad är detta?"* utan *"Vad gör jag nu?"*

Kompassprincipen behandlar huvudsakligen denna andra fråga.

Skillnaden är viktig eftersom en miljö kan lyckas på den ena nivån och
misslyckas på den andra. En visuellt tydlig webbplats kan vara
fullständigt begriplig som produkt men samtidigt erbjuda en
ogenomtränglig navigationsstruktur. Omvänt kan en tekniskt effektiv meny
låta användaren röra sig snabbt genom ett system vars övergripande syfte
förblir oklart.

Det första är ett kompassproblem.

Det andra är närmare ett farkostproblem.

En mogen modell för digital orientering behöver kunna beskriva båda utan
att använda samma förklaring för allt.

Detta är den första större revisionen av det Hanssonska ramverket.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 7 -->
```
# 2. Kompassprincipens teoretiska modell

## 2.1 Kompassprincipens grundformulering

Kompassprincipen kan nu formuleras i sin starkare form:

> **När en individ befinner sig i ett system där flera efterföljande
> tillstånd är möjliga och där dessa tillstånd inte är likvärdiga i
> förhållande till individens mål, uppstår riktningsosäkerhet. Signaler
> som gör relationen mellan nuvarande position, möjlig handling och
> relevant destination begriplig fungerar som kompasser.**

Formuleringen innehåller fyra nödvändiga komponenter.

För det första måste det finnas ett **aktuellt tillstånd**. Användaren
befinner sig någonstans i systemet.

För det andra måste det finnas **alternativ**. Om endast en handling är
möjlig finns inget meningsfullt riktningsval.

För det tredje måste alternativen vara **asymmetriska**. De leder till
olika konsekvenser, innehåll eller grad av måluppfyllelse.

För det fjärde måste individen ha någon form av **mål**, även om målet
är vagt. "Jag vill hitta något intressant att läsa" är tillräckligt.

Kompassfunktionen består då inte nödvändigtvis i att välja åt
användaren. Den kan i stället göra skillnaderna mellan vägarna
begripliga.

Detta är centralt.

En kompass säger inte: *gå norrut*.

Den säger: *detta är norr*.

Skillnaden mellan vägledning och tvång kommer att återkomma genom hela
manuskriptet.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 8 -->
```
## 2.2 Kompassen som funktion, inte föremål

Tidigare diskussioner kring Farkostprincipen visade hur snabbt en
metafor kan misstolkas som en bokstavlig designföreskrift. Därför krävs
här en ovanligt explicit avgränsning.

**En webbplats behöver inte en bokstavlig kompass.**

Kompassprincipen beskriver en funktion.

Ett sökfält kan fungera som kompass när användaren redan vet vad hon
söker. En kategorimeny kan fungera som kompass genom att dela upp ett
stort informationsrum i begripliga riktningar. En rekommendation kan
fungera som kompass genom att signalera ett sannolikt relevant nästa
steg. En progressionsindikator kan fungera som kompass genom att visa
relationen mellan nuvarande och framtida position.

Även språk kan vara en kompass.

"Läs nästa del" uttrycker en tydlig riktning. "Utforska liknande
berättelser" uttrycker en annan. "Tillbaka till biblioteket" etablerar
en relation mellan den lokala positionen och en högre nivå.

Det avgörande är inte elementets form utan dess **orienterande verkan**.

Detta innebär också att samma element kan fungera som kompass för en
användare men inte för en annan. En avancerad kategorisering hjälper
bara den som förstår kategorierna. Ett välbekant ikonmönster kan
orientera en erfaren användare och förvirra en ny.

Kompassfunktionen är därför relationell.

Den finns inte enbart i gränssnittet.

Den uppstår mellan signalen och den som försöker tolka den.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 9 -->
```
## 2.3 Den Hanssonska fyrfältsmodellen

Den ursprungliga Farkostprincipen kunde förenklas till:

**Plats → Farkost → Destination**

Kompassprincipen visar att denna sekvens saknade en explicit
riktningsmekanism.

Den reviderade modellen är:

**Plats → Farkost → Kompass → Destination**

De fyra fälten motsvarar fyra frågor.

  Fält          Orienteringsfråga
  ------------- --------------------------------------------
  Plats         Var är jag?
  Farkost       Varför finns resan?
  Kompass       Åt vilket håll kan eller bör jag röra mig?
  Destination   Vart kan rörelsen leda?

Modellen ska inte förstås som en obligatorisk kronologisk sekvens. I
praktiska gränssnitt kan komponenterna visas samtidigt, överlappa eller
återkomma.

Dess analytiska värde ligger i separationen.

En startsida kan etablera plats. En presentation kan etablera resans
identitet. Navigation och rekommendationer kan etablera riktning. Ett
mål kan representeras av en berättelse, en slutförd uppgift eller en
djupare förståelse av materialet.

Om en användare går vilse kan modellen användas diagnostiskt.

Vet hon inte **var** hon är? Platsproblem.

Vet hon inte **varför** miljön finns? Farkostproblem.

Vet hon inte **vilken väg** som är relevant? Kompassproblem.

Vet hon inte **vad vägen leder till**? Destinationsproblem.

Att fyra frågor kan formuleras betyder inte att fyra separata
komponenter alltid måste byggas.

Det betyder att fyra olika typer av misslyckande kan förekomma.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 10 -->
```
# 3. Riktningsmekanismer och orientering

## 3.1 Riktningsosäkerhet

Kompassprincipens centrala problemvariabel är **riktningsosäkerhet**.

Riktningsosäkerhet uppstår när användaren uppfattar flera möjliga
handlingar men saknar tillräcklig information för att bedöma deras
relation till sitt mål.

Det är inte samma sak som total förvirring.

En användare kan mycket väl förstå varje enskild knapp och ändå vara
osäker på vilken knapp som är relevant. Hon kan känna igen samtliga
kategorier och ändå sakna grund för att välja mellan dem.

Riktningsosäkerhet kan därför existera i ett tekniskt fungerande och
visuellt tydligt system.

Den kan beskrivas konceptuellt som:

**R = f(A, D, M, S)**

där:

-   **R** = riktningsosäkerhet,
-   **A** = antal upplevda alternativ,
-   **D** = upplevd skillnad mellan alternativen,
-   **M** = målets tydlighet,
-   **S** = signalernas begriplighet.

Formeln är inte en validerad matematisk modell. Den fungerar här som ett
sätt att tydliggöra relationer som senare kan operationaliseras.

Fler alternativ behöver inte alltid öka osäkerheten. Om alternativen är
tydligt kategoriserade kan tio val vara lättare än tre dåligt namngivna
val.

Kompassprincipen förutsäger därför inte att enkelhet alltid är bättre.

Den förutsäger att **begriplig riktning** är bättre än obegriplig
riktning.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 11 -->
```
## 3.2 Kompasslös drift

När en individ kan röra sig men saknar en begriplig riktning uppstår det
tillstånd jag benämner **kompasslös drift**.

Drift är inte samma sak som stillastående.

Tvärtom kan användaren vara mycket aktiv. Hon klickar, öppnar, går
tillbaka, provar en annan kategori, läser några rader, byter sida och
fortsätter.

Problemet är att handlingarna inte längre upplevs som delar av en
sammanhängande rörelse.

Kompasslös drift kan därför maskeras av aktivitet.

Detta är särskilt relevant i digitala miljöer där varje klick lätt kan
registreras som engagemang. En hög mängd interaktioner behöver inte
betyda att användaren är väl orienterad. Den kan lika gärna betyda att
hon letar efter riktningen.

Tre kännetecken föreslås:

1.  **Repetitiv återgång** -- användaren återvänder ofta till samma nod.
2.  **Låg konsekvens mellan val** -- efterföljande handlingar saknar
    tydlig relation.
3.  **Svag målförklaring** -- användaren har svårt att beskriva varför
    hon valde nästa steg.

Begreppet är avsiktligt neutralt. Drift kan ibland vara önskvärd. Ett
bibliotek, museum eller berättelsearkiv kan vara byggt för serendipitet.

Skillnaden mellan **utforskning** och **drift** är därför inte mängden
planering utan graden av upplevd kontroll.

Den som vandrar frivilligt är inte nödvändigtvis vilse.

Den som inte längre vet varför hon vandrar kan vara det.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 12 -->
```
## 3.3 Utforskning är inte orienteringsfel

En möjlig invändning mot Kompassprincipen är att den övervärderar
målmedveten navigation. Många digitala upplevelser är uttryckligen
byggda för upptäckt, lek och oplanerad rörelse.

Invändningen är viktig.

Kompassprincipen bör inte användas för att göra varje miljö till en
korridor.

Orientering innebär inte att användaren alltid måste känna till
slutdestinationen. Det kan räcka att hon förstår **vilken sorts
riktning** ett val representerar.

En läsare kan exempelvis välja kategorin "mörk fantasy" utan att veta
vilken berättelse hon kommer att läsa. Hon är fortfarande orienterad
eftersom valet uttrycker en meningsfull preferens.

På samma sätt kan en knapp märkt "Överraska mig" vara en legitim
kompass. Den riktar användaren mot slumpmässighet på ett kontrollerat
sätt.

Detta kan verka motsägelsefullt men är inte det.

Att välja slump är fortfarande ett val.

Kompasslös drift uppstår först när systemets fortsättningar blir svåra
att tolka i relation till användarens avsikt.

Kompassprincipen försvarar alltså inte maximal förutsägbarhet.

Den försvarar **begriplig valfrihet**.

Ett system kan vara mystiskt utan att vara desorienterande. Det kan
dölja destinationen men ändå tydliggöra vilken sorts resa användaren
accepterar när hon går vidare.

Den distinktionen är avgörande för narrativa miljöer.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 13 -->
```
## 3.4 Informationsdoft och den digitala kompassen

Inom forskning om informationssökning har begreppet *information scent*
använts för att beskriva de signaler människor använder för att bedöma
om en informationsväg sannolikt leder mot ett mål. Kompassprincipen
ligger nära denna idé men försöker beskriva ett bredare fenomen.

En länktext som "Biografi" har starkare riktningsinformation än "Klicka
här". Den första antyder destinationens innehåll. Den andra beskriver
endast handlingen.

Ur Kompassprincipens perspektiv fungerar informationsdoft som en lokal
kompassignal.

Men den fullständiga kompassen kan även innehålla relationer mellan
flera signaler: hierarki, placering, tidigare val, progression och
förväntningar på vad systemet försöker hjälpa användaren att göra.

Detta är en viktig begränsning av teorins originalitet.

Kompassprincipen uppfinner inte observationen att människor använder
ledtrådar för att navigera information. Sådana observationer är sedan
länge etablerade inom forskning om informationssökning, wayfinding och
människa--datorinteraktion.

Principens anspråk är i stället syntetiskt.

Den föreslår att dessa signaler kan förstås som delar av ett gemensamt
**riktningssystem**, och att detta riktningssystem bör analyseras
separat från systemets identitet och dess övergripande narrativa ram.

Om den separationen inte ger bättre förklaringar eller prediktioner än
befintliga modeller har Kompassprincipen inget vetenskapligt
existensberättigande.

En teori bör inte överleva enbart därför att dess metafor är
tilltalande.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 14 -->
```
## 3.5 Lokal och global kompass

Alla riktningssignaler verkar inte på samma skala.

En **lokal kompass** hjälper användaren att avgöra nästa steg. "Nästa
kapitel", en markerad flik eller en brödsmula är typiska exempel.

En **global kompass** hjälper användaren att förstå systemets större
riktningar. Huvudnavigation, innehållskategorier och övergripande
progression fungerar ofta på denna nivå.

Problemet uppstår när de två motsäger varandra.

En webbplats kan exempelvis ha en tydlig global struktur men enskilda
sidor vars lokala fortsättning är oklar. Användaren vet ungefär var hon
befinner sig i systemet men inte vad hon ska göra på den aktuella sidan.

Det motsatta kan också inträffa. Varje sida erbjuder ett uppenbart nästa
steg, men efter flera steg vet användaren inte längre var kedjan
befinner sig i helheten.

Kompassprincipen förutsäger att robust orientering gynnas när lokal och
global riktning är **kompatibla**.

Det betyder inte att båda alltid måste visas.

I en linjär berättelse kan den globala kompassen medvetet vara svag för
att bevara upptäckten, medan den lokala riktningen är enkel: fortsätt
läsa.

I ett stort arkiv är den globala kompassen däremot viktigare eftersom
användaren behöver förstå innehållsrummet innan ett lokalt val kan
göras.

Rätt kompass beror alltså på vilken sorts resa systemet erbjuder.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 15 -->
```
## 3.6 Falsk nord

En kompass kan vara tydlig och ändå leda fel.

Detta tillstånd benämns **falsk nord**.

Falsk nord uppstår när ett system presenterar en stark riktningssignal
som inte motsvarar användarens sannolika mål eller som medvetet maskerar
destinationens verkliga konsekvens.

Ett enkelt exempel är en knapp vars text antyder att användaren
fortsätter gratis men vars destination inleder ett betalflöde. Ett annat
är en navigationsetikett som använder ett välbekant ord för en ovanlig
funktion.

Problemet är inte brist på signal.

Problemet är signalens tillförlitlighet.

Falsk nord är därför viktig eftersom den visar att Kompassprincipen inte
kan reduceras till "mer vägledning är bättre".

En stark men felaktig kompass kan vara värre än en svag kompass.

Detta ger två kvalitetsdimensioner:

**Kompassstyrka** -- hur tydligt riktningen kommuniceras.

**Kompassvaliditet** -- hur väl signalen motsvarar destinationen och
användarens rimliga förväntningar.

Ett välorienterat system behöver båda.

Denna distinktion öppnar också för etiska frågor. Manipulativa
gränssnitt kan vara mycket skickliga på orientering, men orienteringen
sker mot systemägarens mål snarare än användarens.

En kompass är inte god därför att den pekar tydligt.

Man måste också fråga **vems nord den pekar mot**.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 16 -->
```
## 3.7 Kompassavvikelse

I fysisk navigation beskriver avvikelse en skillnad mellan förväntad och
faktisk riktning. I Kompassprincipen används **kompassavvikelse** för
att beskriva skillnaden mellan användarens uppfattning om en handlings
destination och den destination som faktiskt uppstår.

Om användaren tror att "Spara" avslutar ett formulär men knappen endast
sparar ett utkast finns en avvikelse. Om "Tillbaka" förväntas återgå
till föregående sammanhang men i stället för användaren till startsidan
finns en annan.

Små avvikelser behöver inte vara katastrofala.

Men upprepade avvikelser kan försvaga förtroendet för hela
riktningssystemet.

Användaren börjar då inte bara tveka på enskilda signaler. Hon börjar
tveka på om signalerna över huvud taget går att använda för att
förutsäga systemet.

Kompassavvikelse bör därför kunna mätas genom att jämföra **förväntad
destination** med **faktisk destination**.

Ett enkelt experiment kan låta deltagare se en navigationssignal och
beskriva vad de förväntar sig ska hända innan de aktiverar den.
Skillnaden mellan förväntning och resultat kan därefter
operationaliseras.

Detta är ett exempel på hur Kompassprincipens metafor kan översättas
till en prövbar fråga.

Om den inte kan översättas bör metaforen överges.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 17 -->
```
## 3.8 Riktningskonflikt

Digitala miljöer innehåller ofta flera kompasser samtidigt.

En huvudmeny pekar mot systemets kategorier. En rekommendationsmotor
pekar mot innehåll som algoritmen bedömer relevant. En kampanjbanner
pekar mot ett kommersiellt mål. En notifikation pekar mot någonting
nytt. Användarens egen avsikt pekar kanske åt ett femte håll.

När dessa signaler konkurrerar uppstår **riktningskonflikt**.

Konflikten behöver inte bero på dålig design. Den kan vara en naturlig
följd av att systemet tjänar flera syften.

Men ju fler starka riktningar som presenteras samtidigt, desto större
blir kravet på prioritering.

Kompassprincipen föreslår därför att gränssnitt inte enbart bör
analyseras utifrån vilka val som finns utan utifrån **vilka val som
framställs som riktningar**.

Storlek, kontrast, placering, språk och timing kan alla ge ett
alternativ riktningsmässig tyngd.

Detta innebär att visuell hierarki är mer än estetik.

Den kan fungera som en kompasshierarki.

När den visuellt starkaste signalen motsvarar användarens mest sannolika
mål kan orienteringen underlättas. När den motsvarar ett perifert eller
kommersiellt mål kan användaren tvingas navigera mot systemets signaler
i stället för med dem.

Kompassens problem blir då politiskt i den lilla betydelsen: vem får
bestämma vad som räknas som framåt?

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 18 -->
```
## 3.9 Den interna kompassen

Hittills har kompassen huvudsakligen beskrivits som en egenskap hos
miljön. Det är otillräckligt.

Användaren anländer med en **intern kompass**: mål, erfarenheter,
förväntningar, vanor och mentala modeller.

En erfaren användare kan navigera ett svagt designat system eftersom hon
redan vet var funktionerna brukar finnas. En ny användare kan behöva
betydligt starkare externa signaler.

Det innebär att orientering alltid är resultatet av en relation mellan
intern och extern kompass.

När de överensstämmer känns navigation ofta självklar. När de skiljer
sig åt måste användaren antingen revidera sin mentala modell eller kämpa
mot systemets struktur.

Den interna kompassen förklarar också varför samma design kan få olika
utfall för olika grupper.

Det som för en expert är elegant minimalism kan för en nybörjare vara
frånvaro av riktning.

Det som för en nybörjare är hjälpsam vägledning kan för experten
upplevas som hinder.

Kompassprincipen bör därför aldrig användas för att påstå att en viss
navigationssignal är universellt optimal.

Frågan är i stället:

**Vilken extern information behöver denna användare för att kalibrera
sin interna kompass i denna miljö?**

Det är en betydligt mindre poetisk fråga.

Den är också mer användbar.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 19 -->
```
## 3.10 Kalibrering

När användaren lär sig hur ett system fungerar sker en form av
**kompasskalibrering**.

Tidiga interaktioner är särskilt viktiga. Om de första länkarna beter
sig som förväntat stärks tilliten till senare signaler. Om de första
handlingarna ger oväntade resultat måste användaren investera mer
kognitivt arbete i varje nytt val.

Kalibrering innebär att användaren bygger en modell av systemets
riktningslogik.

Efter tillräcklig erfarenhet kan explicit vägledning minska i betydelse.
Användaren har då internaliserat delar av kompassen.

Detta skapar en designmässig paradox.

Ett gränssnitt som är optimalt för första besöket kan bli övertydligt
för den återkommande användaren. Ett system som är effektivt för
experter kan vara ogenomträngligt för nya.

Kompassprincipen förutsäger därför att adaptiv eller progressiv
vägledning ibland kan vara bättre än permanent maximal vägledning.

Detta behöver testas.

Det är också möjligt att stabilitet är viktigare än anpassning, eftersom
en kompass som flyttar sig riskerar att förstöra den mentala karta
användaren just har byggt.

Teorin ger här ingen automatisk lösning.

Den identifierar en konflikt mellan **lärbarhet** och **stabilitet**.

En användbar teori bör ibland göra problemen tydligare utan att låtsas
att alla problem har ett enkelt svar.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 20 -->
```
## 3.11 Destinationens roll

En kompass är meningslös utan någon form av destination.

Destinationen behöver dock inte vara en exakt slutpunkt.

Den kan vara kategorisk: "något humoristiskt att läsa". Den kan vara
processuell: "förstå ämnet bättre". Den kan vara temporär: "hitta nästa
rimliga steg".

Detta betyder att Kompassprincipen inte kräver att användaren kan
formulera ett slutmål innan navigationen börjar.

Däremot krävs någon dimension längs vilken alternativ kan uppfattas som
mer eller mindre relevanta.

Destinationen fungerar därmed som kompassens referensram.

Om användarens mål förändras kan samma riktningssignal få en annan
betydelse. En knapp som tidigare var irrelevant kan plötsligt bli den
naturliga vägen framåt.

Detta gör destinationen dynamisk.

I narrativa miljöer är detta särskilt tydligt. En läsare kan börja med
målet att förstå världen, senare vilja följa en specifik karaktär och
därefter söka efter bakgrundsmaterial. Systemets kompass måste antingen
stödja dessa skiften eller acceptera att användaren själv tar över
navigeringen.

Det är därför missvisande att tala om "den korrekta vägen" i alla
digitala miljöer.

Ofta finns flera legitima destinationer.

Kompassens uppgift är inte att utplåna dem.

Den är att göra dem urskiljbara.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 21 -->
```
## 3.12 Farkost--kompass-interaktionen

Farkostprincipen och Kompassprincipen kan nu relateras mer precist.

Farkosten svarar på den övergripande frågan om **resans meningsram**.

Kompassen svarar på den lokala och globala frågan om **riktning inom
denna ram**.

En stark farkost utan kompass kan skapa fascination men svag
handlingsförmåga. Användaren förstår miljöns identitet men vet inte hur
hon ska fortsätta.

En stark kompass utan farkost kan skapa effektivitet men svag mening.
Användaren kan utföra uppgifter utan att förstå sammanhanget.

Det första kan beskrivas som **meningsfull desorientering**.

Det andra som **effektiv meningslöshet**.

Båda formuleringarna är avsiktligt spetsiga. De ska inte behandlas som
kliniska kategorier.

I praktiken kan en produkt mycket väl behöva mer av det ena än det
andra. En internetbank behöver sannolikt inte ett rikt narrativt ramverk
för varje överföring. Ett litterärt projekt kan däremot vinna på en
tydligare identitet.

Det Hanssonska orienteringssystemet är därför inte en checklista.

Det är en modell för att ställa separata frågor.

Det vore ett missbruk av teorin att lägga till metaforiska element
enbart för att fylla modellens rutor.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 22 -->
```
## 3.13 Det Hanssonska orienteringssystemet

När Farkostprincipen och Kompassprincipen kombineras uppstår ett större
ramverk: **det Hanssonska orienteringssystemet**.

Systemet består i sin nuvarande form av fyra analytiska funktioner:

1.  **Platsfunktionen** -- etablerar det aktuella sammanhanget.
2.  **Farkostfunktionen** -- etablerar resans identitet eller mening.
3.  **Kompassfunktionen** -- etablerar möjliga riktningar.
4.  **Destinationsfunktionen** -- etablerar tänkbara framtida tillstånd.

Modellen kan uttryckas:

**O = P + F + K + D**

där **O** står för orienteringsstruktur.

Plustecknen betyder inte att variablerna kan summeras numeriskt.
Notationen är konceptuell.

En mer realistisk formulering är att orientering uppstår genom
interaktion mellan funktionerna.

Om platsen är oklar kan kompassen peka tydligt men sakna referenspunkt.
Om destinationen är oklar kan riktningen vara tekniskt begriplig men
motivet för valet svagt. Om farkosten är oklar kan användaren navigera
utan att förstå varför miljön organiserats på detta sätt.

Ramverket gör inga anspråk på fullständighet.

Det är möjligt att andra funktioner behöver separeras i framtiden.

Denna möjlighet ska inte tolkas som en inbjudan att omedelbart namnge
fler nautiska principer.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 23 -->
```
# 4. Tillämpningsområden och konsekvenser

## 4.1 Narrativ riktning

Narrativ riktning skiljer sig från vanlig navigation genom att nästa
steg inte enbart förändrar position utan även förståelse.

I en berättelse kan ordningen mellan delar vara avgörande. Kapitel två
efter kapitel ett är inte bara en ny plats i dokumentet. Det är ett nytt
tillstånd i läsarens kunskap.

Detta gör narrativ navigation tidsberoende.

En länk till slutet av berättelsen kan vara tekniskt korrekt men
narrativt destruktiv.

Kompassprincipen föreslår därför att riktningskvalitet ibland måste
bedömas i relation till **informationsordning**.

Detta gäller även utanför fiktion. En teknisk guide kan kräva att
grundläggande begrepp förstås innan avancerade moment blir meningsfulla.
Ett utbildningssystem kan erbjuda fri navigation men samtidigt signalera
rekommenderad progression.

Narrativ riktning är alltså inte samma sak som linjäritet.

Ett system kan ha många vägar men ändå hjälpa användaren att förstå
deras konsekvenser.

Det centrala är återigen inte att bestämma åt användaren.

Det är att göra riktningens betydelse synlig.

En kompass som säger "norr" hindrar ingen från att gå söderut.

Den gör bara valet medvetet.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 24 -->
```
## 4.2 Kompasser i informationsarkitektur

Informationsarkitektur organiserar innehåll så att människor kan hitta,
förstå och använda det. Kompassprincipen bör därför inte presenteras som
en ersättning för informationsarkitektur.

Snarare kan den fungera som ett analytiskt språk inom den.

Menyer, etiketter, hierarkier, sökfunktioner och korslänkar kan alla
undersökas utifrån vilken riktningsinformation de ger.

En hierarki svarar exempelvis inte bara på frågan "var finns detta?"
utan också "vilka andra vägar ligger nära denna?". En brödsmula visar
inte bara historik utan relation mellan nivåer. En rekommendationslista
skapar inte bara exponering utan pekar ut möjliga fortsättningar.

Kompassperspektivet kan därför vara användbart när en struktur tekniskt
sett är komplett men fortfarande känns svår att navigera.

Frågan blir då inte endast om informationen finns.

Frågan blir om användaren kan **läsa riktningen**.

Detta kan förklara varför två informationsarkitekturer med samma
innehåll och samma antal länkar kan upplevas mycket olika.

Skillnaden kan ligga i hur tydligt relationerna mellan länkarna
kommuniceras.

Återigen måste detta prövas empiriskt.

En metafor får inte användas som ersättning för användartestning.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 25 -->
```
## 4.3 Rekommendationssystem som kompasser

Rekommendationssystem är särskilt tydliga exempel på externa kompasser.

De reducerar ett stort valrum genom att framhäva ett mindre antal
möjliga riktningar.

Men rekommendationer introducerar ett problem: kompassen bygger inte
enbart på användarens uttalade mål. Den bygger på en modell av
användaren.

Det innebär att riktningen kan bli effektiv utan att vara transparent.

En rekommendation kan kännas relevant samtidigt som användaren saknar
förståelse för varför den visas. Detta kan vara praktiskt men skapar en
asymmetri mellan systemets kunskap och användarens.

Kompassprincipen skiljer därför mellan **förklarad riktning** och
**oförklarad riktning**.

Båda kan fungera.

Men de har olika konsekvenser för användarens möjlighet att kalibrera
sin interna kompass.

Om systemet alltid väljer åt användaren kan hon nå relevanta
destinationer utan att lära sig informationslandskapet. Om
rekommendationerna försvinner står hon då utan orientering.

Detta liknar skillnaden mellan att följa en GPS och att förstå en karta.

Analogin ska inte överdrivas.

Men den illustrerar att effektiv navigation och utvecklad
orienteringsförmåga inte alltid är samma sak.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 26 -->
```
## 4.4 Sökrutan och den förutsatta kompassen

Sökfunktioner betraktas ofta som universella navigationsverktyg.

Men sökning kräver att användaren kan formulera en riktning i ord.

Sökrutan är därför en märklig kompass: den är kraftfull först när
användaren redan bär en relativt tydlig intern kompass.

Den som vet att hon söker "gotisk fantasy" kan använda sökningen
effektivt. Den som endast vet att hon vill "hitta något" behöver andra
signaler.

Detta innebär att sökning och bläddring stöder olika
orienteringstillstånd.

Sökning lämpar sig för relativt tydliga destinationer.

Bläddring och rekommendationer kan hjälpa när destinationen ännu formas.

Ett system som endast erbjuder sökning kan därför vara funktionellt
komplett men orienteringsmässigt tunt.

Detta är inte ett argument för att varje webbplats måste ha omfattande
kategorier.

Det är ett argument för att fråga vilken grad av intern riktning
användaren rimligen kan förväntas ha vid ankomst.

Kompassdesign börjar inte med komponenten.

Den börjar med tillståndet hos den som ska använda den.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 27 -->
```
## 4.5 När kompassen bör försvinna

En god kompass behöver inte alltid vara synlig.

I vissa upplevelser kan konstant vägledning störa koncentration,
immersion eller känslan av självständig upptäckt.

Kompassprincipen innehåller därför ett till synes paradoxalt påstående:

**Ibland är den bästa kompassfunktionen att veta när kompassen inte
behövs.**

Om användaren befinner sig i en linjär text och endast behöver scrolla
kan ytterligare navigation skapa brus. Om en berättelse avsiktligt ska
kännas osäker kan fullständig orientering motverka det konstnärliga
målet.

Det avgörande är om desorienteringen är **avsiktlig och begriplig**
eller **oavsiktlig och hindrande**.

Ett skräckspel kan vilja att spelaren känner sig vilse.

Det betyder inte att menyerna för ljudinställningar också bör vara
obegripliga.

Kompassprincipen måste därför tillämpas på rätt nivå.

Att en upplevelse använder osäkerhet estetiskt innebär inte att alla
delar av systemet gynnas av samma osäkerhet.

Design är inte konsekvent därför att samma regel används överallt.

Den är konsekvent när varje regel används där den fyller sitt syfte.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 28 -->
```
## 4.6 Kompassöverbelastning

Om för lite riktning skapar drift kan för mycket riktning skapa
**kompassöverbelastning**.

Detta inträffar när användaren möter så många vägledande signaler att
själva prioriteringen blir ett nytt orienteringsproblem.

Pilar, rekommendationer, guider, popuprutor, notifikationer,
progressionsfält och markerade knappar kan var för sig vara tydliga.
Tillsammans kan de konkurrera.

Det är alltså möjligt att maximera varje enskild kompassignal och
samtidigt försämra den övergripande kompassen.

Detta är ytterligare ett skäl att skilja signalstyrka från
systemkvalitet.

Kompassprincipen förutsäger en icke-linjär relation mellan vägledning
och orientering: för lite vägledning kan vara dåligt, men mer är inte
obegränsat bättre.

Den exakta relationen beror sannolikt på uppgift, erfarenhet och
informationsmängd.

Detta ger en tydlig experimentell möjlighet.

Deltagare kan exponeras för samma uppgift med olika antal samtidiga
riktningssignaler. Om Kompassprincipen har rätt bör det finnas nivåer
där ytterligare signaler inte längre förbättrar och möjligen försämrar
prestation eller upplevd kontroll.

Detta är en faktisk prediktion.

Den kan vara fel.

Det är meningen.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 29 -->
```
## 4.7 Trovärdighet och kompassförtroende

Navigation bygger på förtroende.

Om användaren upprepade gånger upptäcker att länkar, etiketter eller
rekommendationer inte leder dit hon förväntat sig minskar viljan att
använda dem som framtida riktningssignaler.

Detta kan beskrivas som **kompassförtroende**.

Kompassförtroende är inte samma sak som allmän trovärdighet. En
användare kan betrakta en organisation som seriös men ändå uppleva dess
webbplats som navigationsmässigt opålitlig.

På motsvarande sätt kan en mindre trovärdig källa ha en tekniskt mycket
förutsägbar navigationsstruktur.

Begreppen bör hållas isär.

Hypotesen är att konsekventa relationer mellan signal och destination
bygger kompassförtroende över tid.

Detta förtroende minskar behovet av aktiv kontroll. Användaren behöver
inte längre analysera varje länk lika noggrant eftersom systemets
mönster blivit förutsägbart.

När förtroendet bryts ökar däremot kontrollbehovet.

Användaren börjar läsa mer noggrant, öppna länkar i nya flikar, använda
tillbaka-knappen eller söka alternativa vägar.

Kompassförtroende skulle därför kunna studeras både genom självrapport
och beteende.

Det är ett område där teorin bör möta data snarare än fler metaforer.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 30 -->
```
## 4.8 Tillgänglighet och olika kompasser

En kompassignal är endast en kompass om den kan uppfattas och tolkas.

Detta gör tillgänglighet central.

Om riktning kommuniceras enbart genom färg kan signalen försvinna för
vissa användare. Om hierarki endast uttrycks visuellt kan den bli svag
för den som använder skärmläsare. Om navigationsetiketter bygger på
kulturella metaforer kan de vara mindre begripliga för personer som inte
delar samma referenser.

Kompassprincipen leder därför till en enkel men viktig fråga:

**Är riktningen tillgänglig genom den kanal användaren faktiskt
använder?**

Redundans kan här vara en styrka.

Text, struktur, position och semantik kan tillsammans kommunicera samma
riktning utan att skapa överbelastning, eftersom signalerna förstärker
varandra snarare än konkurrerar.

Detta visar också varför en metaforbaserad design måste hanteras
försiktigt.

En båt kan vara charmig.

En kompass kan vara charmig.

Men om användaren måste förstå skämtet för att navigera systemet har
metaforen gått från identitet till hinder.

Kompassprincipen får aldrig användas som ursäkt för att göra gränssnitt
mer kryptiska i teorins namn.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 31 -->
```
## 4.9 Mobil navigation

På små skärmar blir kompassproblemet konkret.

Mindre yta innebär att färre riktningssignaler kan visas samtidigt.
Global navigation göms ofta bakom menyer. Kontext försvinner när
användaren scrollar. Flera alternativ måste sekvenseras i stället för
att presenteras parallellt.

Detta kan öka beroendet av lokala kompasser.

En tydlig rubrik, markerad flik eller konsekvent tillbaka-funktion får
större betydelse när resten av strukturen inte är synlig.

Samtidigt har mobila användare ofta starka inlärda konventioner. Gester,
bottennavigation och standardiserade ikoner kan fungera som delar av den
interna kompassen.

Kompassprincipen förutsäger därför inte att mobil design kräver mer
textuell vägledning.

Den förutsäger att **förlust av synlig struktur måste kompenseras av
andra begripliga riktningssignaler**.

Hur denna kompensation bäst sker är en empirisk fråga.

Det viktiga är att inte anta att mindre skärm endast är ett
layoutproblem.

Det är också ett orienteringsproblem.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 32 -->
```
## 4.10 Temporal riktning

Riktning behöver inte vara spatial eller strukturell.

Den kan också vara temporal.

"Fortsätt", "senare", "tidigare", "nästa vecka" och "steg 3 av 5"
placerar användaren i ett tids- eller progressionsförlopp.

Detta är särskilt tydligt i flerstegsprocesser.

En progressionsindikator fungerar som kompass genom att visa både
aktuell position och återstående väg.

Temporal riktning kan också vara narrativ. En tidslinje hjälper läsaren
att förstå relationen mellan händelser. En historikfunktion visar hur
det aktuella tillståndet uppstod.

Kompassprincipen bör därför inte bindas till menyer.

Varje struktur som gör relationen mellan **nu** och **sedan** begriplig
kan fylla en kompassfunktion.

Detta breddar teorin men skapar också en risk.

Om nästan allt kan kallas kompass förlorar begreppet precision.

Därför krävs ett kriterium: elementet måste minska osäkerhet om
relationen mellan ett aktuellt tillstånd och minst ett möjligt eller
tidigare tillstånd.

Dekoration räcker inte.

När metaforen slutar skilja mellan fenomen har den slutat vara
användbar.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 33 -->
```
## 4.11 Social riktning

Människor orienterar sig inte endast genom systemets egna signaler.

De orienterar sig genom andra människor.

Betyg, kommentarer, läslistor, popularitet och sociala rekommendationer
kan fungera som **sociala kompasser**.

Dessa signaler svarar inte nödvändigtvis på frågan "vart leder länken?"
utan "vilken väg har andra bedömt som värdefull?"

Social riktning är kraftfull eftersom den reducerar osäkerhet genom
kollektiv information.

Men den kan också skapa flockeffekter.

Om det mest populära innehållet alltid exponeras mest kan kompassen
förstärka den riktning den själv har skapat.

Kompassprincipen behöver därför skilja mellan **deskriptiv social
riktning** och **normativ social riktning**.

"Många har läst detta" är deskriptivt.

"Du bör läsa detta" är normativt.

Gränsen är dock inte alltid tydlig. En topplista kan uppfattas som
rekommendation även om den endast rapporterar statistik.

Detta visar att kompasser inte bara består av information.

De består också av tolkningen av vad informationen betyder för nästa
val.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 34 -->
```
## 4.12 Etik: vems destination?

Kompassprincipen blir etiskt relevant när systemets mål och användarens
mål skiljer sig åt.

En plattform kan vilja maximera tid i tjänsten. Användaren kan vilja
hitta en specifik uppgift och lämna.

Båda kan använda samma gränssnitt.

Om systemets starkaste riktningssignaler konsekvent leder mot fortsatt
engagemang snarare än användarens uttalade mål uppstår en konflikt
mellan två destinationer.

Det vore naivt att kalla detta enbart ett navigationsproblem.

Kompasser kan användas för att styra.

Det betyder inte att all styrning är manipulation. En säkerhetsvarning
bör vara stark. Ett formulär bör kunna markera nästa nödvändiga steg.

Den etiska frågan är snarare om riktningen är förenlig med användarens
informerade intention.

Kompassprincipen kan därför inte nöja sig med att mäta hur effektivt
människor rör sig.

Den måste också fråga **mot vad** de rör sig och **vem som valde
målet**.

En perfekt kompass mot fel destination är inte ett framgångsrikt
orienteringssystem ur användarens perspektiv.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 35 -->
```
# 5. Empirisk prövning och falsifierbarhet

## 5.1 Falsifierbarhet

En återkommande kritik mot konceptuella modeller är att de kan omtolka
varje resultat som stöd.

Kompassprincipen måste undvika detta.

Följande observationer skulle tala emot starka versioner av teorin:

1.  Om ökade och validerade riktningssignaler konsekvent inte påverkar
    förståelse, navigationsprestation eller upplevd kontroll i
    situationer med tydlig riktningsosäkerhet.
2.  Om användare navigerar lika väl när signal--destination-relationer
    är slumpmässiga som när de är konsekventa.
3.  Om skillnaden mellan lokal och global orientering inte kan
    observeras i beteende eller rapporterad förståelse.
4.  Om begrepp som kompassavvikelse inte kan operationaliseras på ett
    sätt som ger mer information än redan etablerade mått.
5.  Om modellen inte förklarar eller förutsäger någonting utöver
    befintliga teorier om wayfinding, informationssökning och
    informationsarkitektur.

Det sista kriteriet är särskilt viktigt.

Att ett nytt namn kan appliceras på ett gammalt fenomen är inte i sig
ett vetenskapligt bidrag.

Kompassprincipen förtjänar endast att överleva om kombinationen av
begrepp gör någonting användbart: organiserar problem tydligare,
genererar nya hypoteser eller förbättrar designanalys.

Annars bör den förbli vad den började som.

En bra formulering.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 36 -->
```
## 5.2 Hypotes 1: tydligare riktning

Den första empiriska hypotesen är avsiktligt enkel.

> **H1: I uppgifter där flera möjliga vägar finns kommer tydliga och
> validerade riktningssignaler att minska tiden till korrekt vägval
> jämfört med semantiskt svaga signaler.**

Ett experiment kan bygga två versioner av samma informationsmiljö.

I version A används etiketter som beskriver destinationernas innehåll.

I version B används generiska etiketter med samma visuella vikt och
samma tekniska funktion.

Deltagarna får samma mål.

Utfall kan inkludera tid till första relevanta val, antal felvägar,
återgångar och självrapporterad säkerhet.

Om skillnaden uteblir behöver hypotesen revideras.

Det vore inte ett misslyckande för vetenskapen.

Det vore ett misslyckande för en specifik förutsägelse.

Den distinktionen är värd att understryka eftersom teorier annars lätt
skyddas från den verklighet som skulle kunna göra dem bättre.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 37 -->
```
## 5.3 Hypotes 2: falsk nord

Den andra hypotesen behandlar missvisande signaler.

> **H2: En stark men missvisande riktningssignal kommer att skapa större
> initial felorientering än en svag eller neutral signal när användarens
> mål är tydligt.**

Experimentellt kan deltagare möta tre varianter:

-   tydlig och korrekt signal,
-   neutral signal,
-   tydlig men missvisande signal.

Om falsk nord är ett meningsfullt fenomen bör den tredje gruppen inte
bara göra fler fel än den första. Den kan även göra fler fel än gruppen
som fått mindre vägledning.

Det skulle stödja tesen att kompassvaliditet är en separat dimension
från kompassstyrka.

Efterföljande försök kan mäta hur snabbt användare återfår förtroende
efter att ha upptäckt avvikelsen.

Detta kopplar falsk nord till kompassförtroende.

Även här finns etablerad forskning om förtroende, förväntningar och
gränssnitt som teorin måste relateras till. Kompassprincipen får inte
behandla välkända effekter som om de upptäckts på nytt enbart därför att
de nu har nautiska namn.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 38 -->
```
## 5.4 Hypotes 3: lokal och global orientering

Den tredje hypotesen prövar separationen mellan lokal och global
kompass.

> **H3: Lokal vägledning kan förbättra nästa-steg-prestation utan att
> nödvändigtvis förbättra användarens förståelse av systemets
> övergripande struktur.**

Deltagare kan navigera en komplex informationsmiljö där varje sida
erbjuder en tydlig rekommenderad fortsättning.

En grupp får dessutom en stabil global struktur, exempelvis en karta
eller hierarkisk navigation.

Om båda grupperna genomför lokala uppgifter lika väl men gruppen med
global struktur bättre kan rekonstruera systemets organisation efteråt,
finns stöd för distinktionen.

Detta skulle vara viktigt eftersom traditionella prestationsmått annars
kan dölja svag global orientering.

En användare kan nå målet utan att förstå landskapet.

I vissa produkter är det fullt tillräckligt.

I andra är förståelsen av landskapet en del av målet.

Kompassprincipen bör därför inte föreskriva samma mätvärden för alla
miljöer.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 39 -->
```
## 5.5 Hypotes 4: kompassöverbelastning

Den fjärde hypotesen behandlar mängden vägledning.

> **H4: När flera riktningssignaler konkurrerar om samma beslut kommer
> orienteringsnyttan först att öka och därefter plana ut eller minska.**

Detta kan testas genom att successivt öka antalet visuellt framträdande
vägledningar i en uppgift.

Viktigt är att signalerna faktiskt konkurrerar. Flera redundanta
signaler som säger samma sak är ett annat fenomen.

Mätvärden kan vara beslutstid, felval, upplevd säkerhet och minne av
alternativen.

Om mer vägledning alltid förbättrar samtliga mått inom realistiska
nivåer är begreppet kompassöverbelastning svagare än föreslaget.

Om en tydlig vändpunkt kan observeras blir nästa fråga vilka faktorer
som flyttar den.

Expertis, skärmstorlek, uppgiftens komplexitet och stress är rimliga
kandidater.

Här kan teorin börja producera ett faktiskt forskningsprogram.

Det är betydligt mer intressant än att producera fler namn.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 40 -->
```
## 5.6 Föreslaget experiment: Inkstone-testet

Eftersom Kompassprincipen uppstod i anslutning till en litterär
webbmiljö är ett naturligt första test att använda samma typ av miljö.

Tre versioner kan byggas.

**Version A -- Minimal kompass:** innehållet är åtkomligt men
relationerna mellan möjliga vägar är svagt kommunicerade.

**Version B -- Funktionell kompass:** kategorier, rekommendationer och
progression gör riktningen tydlig utan maritim metafor.

**Version C -- Narrativ kompass:** samma funktioner integreras i
webbplatsens narrativa identitet.

Deltagare får både målinriktade och öppna uppgifter.

Målinriktade uppgifter kan vara att hitta en specifik typ av berättelse.

Öppna uppgifter kan vara att hitta "något du själv skulle vilja läsa".

Mätning bör inkludera effektivitet, minne av strukturen, upplevd
kontroll, förståelse av webbplatsens identitet och vilja att fortsätta
utforska.

Version B och C är särskilt viktiga.

Om C inte förbättrar relevanta utfall jämfört med B finns inget stöd för
att den narrativa kompassen tillför funktionell orientering.

Den kan fortfarande ha estetiskt värde.

Men estetik ska inte smugglas in som psykologi.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 41 -->
```
# 6. Begränsningar

Kompassprincipen har flera uppenbara begränsningar.

För det första är den ännu en konceptuell modell. De centrala begreppen
kräver empirisk operationalisering.

För det andra överlappar modellen etablerade områden som wayfinding,
informationsarkitektur, informationssökning, beslutsfattande och
människa--datorinteraktion.

För det tredje riskerar kompassmetaforen att bli för bred. Om varje
signal om ett möjligt nästa tillstånd kallas kompass kan begreppet
förlora diskriminerande värde.

För det fjärde är modellen huvudsakligen utvecklad med digitala miljöer
i åtanke. Överföring till andra domäner måste göras försiktigt.

För det femte kan teorins ursprung påverka dess formulering. Den
utvecklades som svar på en offentlig konflikt kring Farkostprincipen,
vilket skapar en uppenbar risk att vissa distinktioner har fått större
vikt därför att de var retoriskt användbara.

Detta är inte skäl att avfärda modellen.

Det är skäl att testa den hårdare.

En teori som endast fungerar när dess upphovsman får definiera alla
misslyckanden som nya principer är inte en teori.

Det är ett imperium.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 42 -->
```
# 7. Vanliga invändningar och avgränsningar

### Behöver webbplatser kompasser?

Nej, inte bokstavliga.

### Behöver alla webbplatser en tydlig narrativ riktning?

Nej.

### Är en meny alltid en kompass?

Nej. En meny kan presentera val utan att göra deras relation till
användarens mål begriplig.

### Är Kompassprincipen empiriskt bevisad?

Nej.

### Påstår modellen att människor har ett särskilt psykologiskt "kompassorgan"?

Nej.

### Är detta bara informationsarkitektur med ett nytt namn?

Det är en legitim invändning och en fråga som måste avgöras genom
modellens förklarings- och prediktionsvärde.

### Uppfann Joel von Gustafsson Kompassprincipen?

Han formulerade frågan som utlöste separationen mellan farkost- och
kompassfunktion.

Detta erkänns här uttryckligen.

### Var frågan avsedd att skapa en ny teori?

Nej.

### Är detta roligt för författaren?

Frågan ligger utanför manuskriptets vetenskapliga avgränsning.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 43 -->
```
# 8. Begrepp och formalisering

## 8.1 Terminologi

För tydlighet sammanfattas manuskriptets centrala termer.

**Kompassfunktion**\
En signals eller strukturs förmåga att göra relationen mellan aktuell
position, möjlig handling och destination begriplig.

**Riktningsosäkerhet**\
Osäkerhet om vilket av flera möjliga efterföljande tillstånd som bäst
relaterar till ett mål.

**Kompasslös drift**\
Aktiv rörelse genom ett system utan stabil upplevelse av riktning.

**Falsk nord**\
En tydlig riktningssignal som skapar en missvisande uppfattning om
destination eller relevans.

**Kompassavvikelse**\
Skillnaden mellan förväntad och faktisk destination.

**Riktningskonflikt**\
Tillstånd där flera starka kompassignaler pekar mot konkurrerande mål.

**Intern kompass**\
Användarens mål, erfarenheter och mentala modeller som används för att
tolka externa signaler.

**Extern kompass**\
Riktningsinformation som uttrycks av systemet.

**Kompassförtroende**\
Grad av tillit till att systemets riktningssignaler förutsäger sina
destinationer.

**Kompassöverbelastning**\
Tillstånd där mängden konkurrerande vägledning själv skapar
orienteringsproblem.

**Farkostfunktion**\
Den funktion som etablerar resans övergripande identitet och meningsram.

Terminologin är provisorisk.

Särskilt de mer metaforiska termerna bör överges om de försvårar snarare
än förbättrar precisionen.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 44 -->
```
## 8.2 En formell skiss

Kompassprincipen kan uttryckas i en förenklad beslutsmodell.

Låt användaren befinna sig i tillstånd **s₀** med möjliga handlingar
**a₁ ... aₙ**.

Varje handling leder, med viss upplevd sannolikhet, till ett
efterföljande tillstånd **sᵢ**.

Användaren har ett mål **g**.

En riktningssignal **k** tillför information om relationen:

**aᵢ → sᵢ → g**

Kompassens funktion kan då beskrivas som en minskning av osäkerheten
kring vilken handling som bäst relaterar till målet.

I informations­teoretiska termer skulle framtida arbete kunna undersöka
om orienteringsnytta kan uttryckas som minskad entropi över möjliga
handlingar, förutsatt att detta görs utan att blanda samman subjektiv
osäkerhet med objektiv sannolikhet.

Denna sida gör inte anspråk på en färdig matematisk teori.

Syftet är att visa att begreppen åtminstone kan översättas till
variabler som potentiellt kan mätas.

Om en sådan översättning misslyckas återstår endast metaforen.

Det kan vara tillräckligt för litteratur.

Det är inte tillräckligt för vetenskap.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 45 -->
```
# 9. Diskussion

Kompassprincipen började som ett svar på en invändning.

Det är en ovanlig men inte nödvändigtvis dålig utgångspunkt.

Kritikens viktigaste funktion är inte att besegra en teori utan att visa
var teorin behöver bli mer exakt. von Gustafssons fråga lyckades med
detta trots att hans avsikt var en annan.

Den reviderade modellen är mindre grandios än den ursprungliga
Farkostprincipen.

Det är en förbättring.

Farkosten behöver inte längre förklara både mening, rörelse, navigation
och destination. Kompassen tar ansvar för en mer avgränsad uppgift:
relationen mellan möjliga fortsättningar och upplevd riktning.

Samtidigt blir det tydligare hur mycket av modellen som redan har nära
släktingar i etablerad forskning.

Detta är också en förbättring.

En ny teori behöver inte låtsas att tidigare arbete saknas. Tvärtom blir
dess värde beroende av om den kan integreras med, skiljas från och
prövas mot detta arbete.

Kompassprincipens framtid bör därför avgöras av tre frågor:

**Kan begreppen mätas?**

**Ger modellen prediktioner som kan misslyckas?**

**Förklarar separationen mellan farkost och kompass någonting som annars
blir mindre tydligt?**

Om svaret på dessa frågor blir nej bör principen överges.

Om svaret blir ja har en fråga ställd under en konflikt producerat
någonting mer användbart än konflikten själv.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 46 -->
```
# 10. Slutsats

En resa och en riktning är inte samma sak.

Det är Kompassprincipens enklaste påstående.

Farkostprincipen beskrev hur en digital miljö kan skapa en meningsram
kring förflyttning mellan plats och destination. Kompassprincipen lägger
till en separat mekanism: signalerna genom vilka individen tolkar
möjliga fortsättningar.

Den centrala tesen kan sammanfattas:

> **Orientering kräver inte bara möjligheten att röra sig. Den kräver
> möjligheten att förstå vad rörelserna betyder.**

Kompassen är namnet på den senare funktionen.

I digitala miljöer kan den bestå av navigation, språk, hierarki,
progression, rekommendationer, social information eller andra signaler.
Ingen av dessa är automatiskt en god kompass. Deras värde beror på
begriplighet, validitet, tillgänglighet och relation till användarens
mål.

Kompassprincipen är ännu inte ett empiriskt etablerat psykologiskt
faktum.

Den är en modell.

Dess fortsatta existens bör bero på vad som händer när modellen möter
data.

Det är en högre standard än den som ibland tillämpades under
Farkostprincipens tidiga formulering.

Det är avsiktligt.

En kompass som aldrig kan visa fel riktning kan heller aldrig visa att
den fungerar.

::: {style="page-break-after: always;"}
:::

```{=html}
<!-- SIDA 47 -->
```
# Referenser och avslutande anmärkning

## Referenser

Darken, R. P., & Sibert, J. L. (1996). Wayfinding strategies and
behaviors in large virtual worlds. *Proceedings of the SIGCHI Conference
on Human Factors in Computing Systems*, 142--149.
https://doi.org/10.1145/238386.238459

Green, M. C., & Brock, T. C. (2000). The role of transportation in the
persuasiveness of public narratives. *Journal of Personality and Social
Psychology, 79*(5), 701--721. https://doi.org/10.1037/0022-3514.79.5.701

McAdams, D. P., & McLean, K. C. (2013). Narrative identity. *Current
Directions in Psychological Science, 22*(3), 233--238.
https://doi.org/10.1177/0963721413475622

Norman, D. A. (2013). *The Design of Everyday Things: Revised and
Expanded Edition*. Basic Books.

Pirolli, P., & Card, S. (1999). Information foraging. *Psychological
Review, 106*(4), 643--675. https://doi.org/10.1037/0033-295X.106.4.643

### Referensanmärkning

Referenserna ovan används som teoretisk bakgrund till närliggande
fenomen. De utgör **inte** belägg för att Kompassprincipen som
självständig teori redan är etablerad. Begrepp som *falsk nord*,
*kompasslös drift* och *kompassöverbelastning* introduceras i denna
rapport.

## Erkännande

Författaren tackar Karin Lindholm för journalistisk dokumentation av den
diskussion ur vilken manuskriptet utvecklades.

Författaren tackar även Joel von Gustafsson för frågan:

> *"Varför inte kalla det Kompassprincipen?"*

Frågan var retorisk.

Svaret blev fyrtiosju sidor.

## Avslutande anmärkning om terminologi

Begreppet *kompass* avser genomgående ett funktionellt
orienteringssystem och inte ett magnetiskt navigationsinstrument.

## Slutord

Det finns i nuläget ingen anledning att anta att det Hanssonska
orienteringssystemet kräver ytterligare en princip.

Eventuella frågor om kartor undanbedes tills vidare.

**--- Professor Dr. Felix J.A. Hansson, 2026**

::: {style="page-break-after: always;"}
:::
