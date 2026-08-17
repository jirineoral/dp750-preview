# DP-750 — Data engineering s Azure Databricks (zkrácená 3denní verze)

Interaktivní podkladové materiály ke kurzu DP-750. Otevřete `index.html` v prohlížeči —
každá kapitola je samostatný HTML soubor, obsah funguje offline i bez webového serveru.

- Kapitoly 01–13 odpovídají 1:1 modulům oficiálního MOC kurzu DP-750T00.
  Kapitoly 09 a 12 jsou označeny **Mimo osnovu · samostudium** — ve zkrácené verzi se neprobírají.
- Kapitoly 14–16 („pod čarou") jsou vlastní nadstavba mimo MOC: Microsoft Fabric,
  propojení s Power BI a migrace z Oracle.
- Praktická část = oficiální laby na
  [microsoftlearning.github.io/DP-750T00](https://microsoftlearning.github.io/DP-750T00-Implement-Data-Engineering-Solutions-using-Azure-Databricks/) (EN).

Zdrojové fragmenty a build nejsou součástí tohoto repozitáře; vygenerované HTML needitujte ručně.

## Rozsah publikace

Web je hostovaný na GitHub Pages z veřejného repozitáře — **je tedy dostupný komukoli, kdo zná
URL**. Indexaci vyhledávači potlačují `robots.txt` a `<meta name="robots" content="noindex">`,
což ale není řízení přístupu. Materiály jsou psané jako doprovod ke kurzu; nic v nich není
důvěrné ani vázané na konkrétního zákazníka.

Do repozitáře nepatří a nikdy se do něj nesmí dostat:

- oficiální MOC prezentace (`DP-750T00A-ENU-PowerPoint_*.pptx`) — licence Microsoft Courseware
  jejich veřejnou redistribuci zakazuje,
- lektorské materiály určené jen pro lektora.

Obojí hlídá `.gitignore`. Git si historii pamatuje navždy — jediné omylem provedené
`git add .` s těmito soubory znamená přepis historie, ne pouhé smazání.

## Autorství a zdroje

Text, diagramy a příklady © Jiří Neoral — [neoral.cz](https://neoral.cz). Všechna práva vyhrazena.

Materiál je vlastní zpracování témat kurzu DP-750, ne kopie oficiálního courseware. Krátké
citace z dokumentace Microsoft Learn jsou uvedeny v uvozovkách s odkazem na zdroj. Microsoft,
Azure, Power BI a Microsoft Fabric jsou ochranné známky Microsoft Corporation; Databricks,
Unity Catalog, Delta Lake a Lakeflow jsou ochranné známky Databricks, Inc. Autor není
s Microsoftem ani Databricks nijak spojen a materiál není těmito společnostmi schválen.

Stránky nenačítají žádný externí obsah — žádné CDN, fonty, analytiku ani cookies.
