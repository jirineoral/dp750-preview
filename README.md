# DP-750 — Data engineering s Azure Databricks

Interaktivní podkladové materiály ke kurzu DP-750. Otevřete `index.html` v prohlížeči —
každá kapitola je samostatný HTML soubor, obsah funguje offline i bez webového serveru.

> **English:** these are course materials for DP-750 (Data Engineering with Azure Databricks),
> published in Czech and English. The language switch with the flags sits in the page header;
> the outline switch on the landing page toggles between the official 13-module MOC outline
> (default) and a shortened three-day variant. Every chapter is a standalone HTML file and works
> offline. See *Authorship and sources* at the bottom.

## Dvě osnovy, dva jazyky

- **Výchozí pohled je oficiální osnova DP-750T00** — 13 modulů, kapitoly 01–13 odpovídají
  1:1 modulům MOC kurzu.
- Přepínač na rozcestníku umí přepnout na **zkrácenou třídenní osnovu**. V ní jsou kapitoly
  09 a 12 označené **Mimo osnovu · samostudium** a přibývají kapitoly 14–16 („pod čarou") —
  vlastní nadstavba mimo MOC: Microsoft Fabric, propojení s Power BI a migrace z Oracle.
  Volba se pamatuje v prohlížeči.
- **Jazyk** přepíná vlaječka v hlavičce. Který jazyk je v kořeni a který v podadresáři,
  se liší podle nasazení — odkaz v hlavičce vede vždy na tutéž kapitolu v druhém jazyce.

Zdrojové fragmenty a build nejsou součástí tohoto repozitáře; vygenerované HTML needitujte ručně.

Praktická část = oficiální laby na
[microsoftlearning.github.io/DP-750T00](https://microsoftlearning.github.io/DP-750T00-Implement-Data-Engineering-Solutions-using-Azure-Databricks/) (EN).

## Rozsah publikace

Web je hostovaný na GitHub Pages z veřejného repozitáře — **je tedy dostupný komukoli, kdo zná
URL**. Indexaci potlačuje `<meta name="robots" content="noindex, nofollow">` na každé stránce.
Soubor `robots.txt` je v repozitáři pro úplnost, ale na *project* Pages je fakticky neúčinný:
roboti ho čtou jen z kořene domény (`jirineoral.github.io/robots.txt`), ne z podadresáře
projektu. Ochrana proti indexaci tedy stojí na tom meta tagu — nová stránka bez něj je
okamžitě indexovatelná. Ani jedno není řízení přístupu.

Materiály jsou psané jako doprovod ke kurzu; nic v nich není důvěrné ani vázané na konkrétního
zákazníka.

Do repozitáře nepatří a nikdy se do něj nesmí dostat:

- oficiální MOC prezentace (`DP-750T00A-ENU-PowerPoint_*.pptx`) — licence Microsoft Courseware
  jejich veřejnou redistribuci zakazuje,
- lektorské materiály určené jen pro lektora.

Hlídá to `.gitignore` a `pre-push` hook, který push s těmito typy souborů odmítne. Git si
historii pamatuje navždy — jediné omylem provedené `git add .` s těmito soubory znamená
přepis historie, ne pouhé smazání.

## Autorství a zdroje

Text, diagramy a příklady © Jiří Neoral — [neoral.cz](https://neoral.cz). Všechna práva vyhrazena.

Materiál je vlastní zpracování témat kurzu DP-750, ne kopie oficiálního courseware. Krátké
citace z dokumentace Microsoft Learn jsou uvedeny v uvozovkách s odkazem na zdroj. Microsoft,
Azure, Power BI a Microsoft Fabric jsou ochranné známky Microsoft Corporation; Databricks,
Unity Catalog, Delta Lake a Lakeflow jsou ochranné známky Databricks, Inc. Autor není
s Microsoftem ani Databricks nijak spojen a materiál není těmito společnostmi schválen.

Stránky nenačítají žádný externí obsah — žádné CDN, fonty, analytiku ani cookies.
