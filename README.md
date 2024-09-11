# Researchuppgift Git Github och Terminalen

## Terminalen

**Kommandon från föreläsningarna**

- **pwd**: Print working directory. Kommando för att visar path till det directory man befinner sig i.
- **ls**: List directory content. Visar lista för innehållet i det directory man befinner sig i. 
- **cd**: Change directory. Ex:  *cd directoryName* för att gå till ett annat directory eller *cd ..* för att gå tillbaka till föregående plats.
- **mkdir**: Skapar nytt directory, ex: *mkdir ImportantStuff*.
- **mv**: Move. Används för att flytta något, ex: *mv fileName directoryName*. *mv oldName newName* används för att döpa om något. 
- **rm**: Remove: Raderar fil, ex: *rm fileName*.
- **echo**: Skriver ut sträng, ex: *echo "He's the leader of the bunch!"*.
- **>**: Skapa fil, ex: *> DonkeyKong.txt*. Kan användas tillsammans med echo för att skapa fil och skriva in text direkt, ex: *echo "He's the leader of the bunch!". > DonkeyKong.txt*.
- **>>**: Uppdatera fil. 
- **cat**: Visar innehållet i en fil, ex: *cat DonkeyKong.txt*.
- **help**: Visar kommandon i terminalen. 

**Några andra kommandon**

- **cp**: Copy. Kopierar en fil från ett directory till ett annat, ex: *cp DonkeyKong.txt ImportantStuff*.
- **rmdir**: Remove directory. Raderar ett directory, ex: *rmdir UnimportantStuff*
- **ps**: Processes. Visar vilka processer som körs. 
- **q (utan Enter)**: Quit. Avslutar nuvarande process i terminalen.

###### Källa: <https://medium.com/@prasku/basic-terminal-commands-ce5790c20107>

---

## Git

**Kommandon från föreläsningarna**

- **git init**: Skapar Git repository. 
- **git clone**: Hämtar repository från en host, ex: *git clone www.exampleurl.com*.
- **git add**: Lägger till fil till staged, ex: *git add .* för att lägga till alla filer eller *git add fileName* för att läga till en specifik fil. 
- **git commit -m**: Commitar stageade filer med ett tillhörande meddelande, ex: *git commit -m "Skrev in citat i DonkeyKong.txt"*.
- **git status**: Visar nuvarande status i git. 
- **git log**: Visar alla commits i nuvarande branch. 
- **git branch**: Visar alla branches. En * markerar nuvarande branch. 
- **git branch branchName**: Skapar ny branch. 
- **git switch**: Byter branch, ex: *git switch experimentBranch*.

**Några andra kommandon**
- **git reset**: Tar bort en fil från stage men behåller eventuella förändringar i working directory, ex: *git reset DonkeyKong.txt*.
- **git mv**: Byter en fils path och stagear bytet, ex: *git mv ImportantStuff UnimportantStuff*.
- **git rm**: Raderar en fil och stagear det, ex: *rm DonkeyKong.txt*.
---
## Github & Markdown

### Kort om Github & Markdown

**Github**

GitHub kan beskrivas som ett socialt nätverk för utvecklare där man istället för bild eller video delar kod. Detta innebär att man kan hämta andras kod och använda den. Det kan vara ett bra sätt att komma igång med ett eget projekt, att bara experimentera eller för att bidra till någon annans projekt. 

**Markdown**

Markdown är en lättläst och lättanvänt markeringsspråk (inte ett programmeringsspråk). Det innebär också att det enkelt kan konverteras om till andra format, bl.a. PDF, epub, HTML o.s.v. 

###### Källa: <https://kazemmdev.medium.com/the-ultimate-guide-to-github-everything-you-need-to-know-310b6173abb2>

**Bonus**:

![En bild på exemplet i den här texten!](<donkey kong.jpg>)