# Spiekbrief Git en GitHub

## 1. Clone, commit, push en pull

Met clone download je eigenlijk gewoon een project van GitHub naar je laptop zodat je er lokaal aan kunt werken. Als je wat veranderingen hebt gemaakt sla je dat op met een commit zodat je weet wat je hebt gedaan. Via push stuur je al je wijzigingen weer terug naar GitHub zodat de online versie ook up to date is. En met pull haal je juist de nieuwste wijzigingen van GitHub binnen op je eigen computer als iemand anders iets heeft aangepast.

## 2. Een goed commitbericht

Slecht voorbeeld: iets aangepast of fix
Waarom is dit slecht?: je hebt geen idee wat er eigenlijk is veranderd en als er straks iets fout gaat kun je niet meer terugvinden door welke aanpassing dat kwam

Goed voorbeeld: login knop werkt weer of navigatiebar toegevoegd aan index.html
Waarom is dit goed?: Je ziet meteen wat je hebt gemaakt of gefixet, veel overzichtelijker

## 3. Gitignore

In een .gitignore bestand zet je alle bestanden en mappen die Git moet negeren zodat die niet per ongeluk mee worden geupload naar GitHub (zoals wachtwoorden of tijdelijke bestanden)

## 4. Pull

Toen ik op pull klikte werd de zin die ik online op GitHub in de README had gezet meteen gedownload naar mijn eigen laptop. Daarom moet je aan het begin van elke les eerst pullen zodat je zeker weet dat je met de nieuwste versie werkt en geen conflicts krijgt

## 5. Terugdraaien

De foute commit verdwijnt niet uit de geschiedenis omdat Git alles onthoudt wat je ooit hebt gedaan en als je een fout terugdraait met Revert, maakt Git eigenlijk gewoon een nieuwe commit aan die precies het tegenovergestelde doet zodat je altijd nog kunt terugzien wat er eerder is gebeurd

## 6. Branches en pull requests
Een branch is een soort aparte tak van je project waarin je veilig kunt werken zonder dat je meteen de hoofdversie stukmaakt en  hierdoor blijft main altijd de werkende versie van je code. Een pull request is een aanvraag om jouw wijzigingen uit die aparte branch weer samen te voegen met de main branch

## 7. Mijn conflict

Er ontstond een conflict omdat ik zowel online op GitHub als lokaal op mijn laptop dezelfde titel op regel 1 had aangepast en ik heb dit opgelost door de dubbele regels en de conflict tekens weg te halen en er 1 nette titel van te maken dus weet Git weer precies welke versie de juiste is