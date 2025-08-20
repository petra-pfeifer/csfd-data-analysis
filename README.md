# Analýza nejlépe hodnocených filmů na ČSFD

Tento projekt je výsledkem workshopu z kurzu Python Data Analysis od Coders Lab. Je zde ukázán celý proces datové analýzy – od sběru dat (web scraping) přes jejich analýzu a vizualizaci až po vyhotovení PDF reportu.

Zdrojová data pocházejí z webu ČSFD, kde jsem analyzovala 1000 nejlépe hodnocených filmů.

## Klíčové úkoly a cíle projektu:

- **Web Scraping:** Použití knihoven **Selenium** a **BeautifulSoup** k automatizovanému stažení dat o top 1000 filmů z webu ČSFD.
- **Analýza dat:** Zpracování a čištění dat pomocí knihovny **Pandas**.
- **Vizualizace dat:** Vytvoření grafů v knihovně **Matplotlib**, které vizualizují klíčové poznatky.
- **Generování reportu:** Sestavení komplexního PDF reportu pomocí knihovny **ReportLab**, který obsahuje vizualizace a tabulku TOP 10 filmů.

## Dosažené výsledky a poznatky

1.  [cite_start]**Vývoj filmové produkce v čase:** Graf "Nejlepších 1000 filmů podle roku" ukazuje distribuci těchto filmů v průběhu let[cite: 13].
2.  [cite_start]**Distribuce hodnocení:** Histogram "Histogram hodnocení filmů" znázorňuje, jak se hodnocení rozprostírá mezi jednotlivými filmy[cite: 47].
3.  [cite_start]**Závislost hodnocení a počtu hodnocení:** Bodový graf "Závislost: Hodnocení vs. Počet hodnocení" vizualizuje vztah mezi hodnocením filmu a počtem hlasů[cite: 63].
4.  [cite_start]**Tabulka TOP 10 filmů:** Prezentace tabulky s TOP 10 filmy, včetně jejich hodnocení a počtu hlasů[cite: 81].

## Použité nástroje

- **Python**
- **Selenium** (web scraping)
- **BeautifulSoup** (parsování HTML)
- **Pandas** (analýza dat)
- **Matplotlib** (vizualizace dat)
- **ReportLab** (generování PDF)
- **Jupyter Notebook** (vývojové prostředí)