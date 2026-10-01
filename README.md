# UCLL Copilot Day

Standalone vragenlijst vooraf: **https://jochemclaes.github.io/ucll-copilot-day/**

Open `index.html` rechtstreeks in een browser of gebruik de website. Geen build,
externe scripts, lettertypen, trackers of backend nodig. De 27 vragen staan in
vier delen (A-D). Antwoorden worden alleen lokaal in de browser bewaard; de
deelnemer downloadt een Word-bestand (`.doc`) en bezorgt dat zelf aan de
contactpersoon bij Microsoft. De pagina verstuurt geen antwoorden.

Beide knoppen **Alles wissen** vragen bevestiging voor onomkeerbaar wissen.
De opslag gebruikt `ucll-copilot-day-vragenlijst-v1`, build `2026.10.01.1`.
Een andere build opent opnieuw leeg. Dit is een afzonderlijke repository en
Pages-website met een eigen opslagsleutel, geen beveiligingsisolatie: andere
projectsites op `jochemclaes.github.io` delen dezelfde browserorigin.

Het vereenvoudigde agendaoverzicht en vraag 10 gebruiken dezelfde drie
sessieblokken: Gezamenlijke sessies, Onderwijssessies en ICT-sessies, zonder
tijden of specifieke sessietitels. Bij deze wijziging blijft de buildstempel
gelijk: alleen een eerder opgeslagen antwoord op vraag 10 wordt verwijderd,
met een melding om opnieuw te kiezen. Alle andere antwoorden blijven bewaard.
De opslagmarkering `q10Versie: 1` zorgt dat nieuwe keuzes normaal terugkomen.

## UCLL-afstemming

Kleuren zijn ontleend aan de publieke UCLL-website: rood `#E30046`, dieprood
`#B40A4D`, marineblauw `#003469`, lichtblauw `#F2FAFE` en wit. Knoppen volgen
het rood-dieprode verloop. De vragenlijst blijft licht, ook bij een donkere
systeemvoorkeur. Een lokale lettertypenreeks vervangt Readex Pro zodat geen
externe fontdownload nodig is. Er worden geen logo- of fotoassets overgenomen.

Vraag 1 gebruikt de vijf brede interessegebieden van UCLL: **Lerarenopleiding,
Management, Technologie, Gezondheid en Welzijn**. Onderzoek, expertise,
dienstverlening en ondersteuning zijn generieke antwoordcategorieen, geen
claim over officiele departementsnamen. Ook de rol-, opvolgings- en
beleidsvragen zijn op UCLL afgestemd.

Publieke bronnen:

- [UCLL-homepage en Moving Minds-positionering](https://www.ucll.be/nl)
- [Publieke UCLL-stylesheet](https://www.ucll.be/themes/custom/calibr8_easytheme/css/styles.css?tm7pc4)
- [Over UCLL: vijf brede interessegebieden](https://www.ucll.be/nl/over-ucll)

Dit is geen formele huisstijlgoedkeuring; de afgeschermde huisstijlgids is niet
geraadpleegd. Het Engelse privacybericht verwijst rechtstreeks naar
[Microsoft Privacy Statement](https://aka.ms/privacy).

Publicatie via GitHub Pages: branch `main`, repositoryroot, HTTPS, geen eigen
domein. `.nojekyll` houdt de pagina statisch; `.gitattributes` bewaart de
HTML-bestandsbytes ongewijzigd.
