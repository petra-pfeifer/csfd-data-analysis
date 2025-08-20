# Analýza nejlépe hodnocených filmů na ČSFD

Tento projekt je výsledkem workshopu z kurzu Python Data Analysis od Coders Lab. Je zde ukázán celý proces datové analýzy – od sběru dat (web scraping) přes jejich analýzu a vizualizaci až po vyhotovení PDF reportu.

Zdrojová data pocházejí z webu ČSFD, kde jsem analyzovala 1000 nejlépe hodnocených filmů.

## Klíčové úkoly a cíle projektu:

- **Web Scraping:** Použití knihoven **Selenium** a **BeautifulSoup** k automatizovanému stažení dat o top 1000 filmů z webu ČSFD.
- **Analýza dat:** Zpracování a čištění dat pomocí knihovny **Pandas**.
- **Vizualizace dat:** Vytvoření grafů v knihovně **Matplotlib**, které vizualizují klíčové poznatky.
- **Generování reportu:** Sestavení komplexního PDF reportu pomocí knihovny **ReportLab**, který obsahuje vizualizace a tabulku TOP 10 filmů.

## Dosažené výsledky a poznatky

**1. Vývoj filmové produkce v čase:** Graf "Nejlepších 1000 filmů podle roku" ukazuje distribuci těchto filmů v průběhu let.
**2. Distribuce hodnocení:** Histogram "Histogram hodnocení filmů" znázorňuje, jak se hodnocení rozprostírá mezi jednotlivými filmy.
**3.  Závislost hodnocení a počtu hodnocení:** Bodový graf "Závislost: Hodnocení vs. Počet hodnocení" vizualizuje vztah mezi hodnocením filmu a počtem hlasů.
**4.  Tabulka TOP 10 filmů:** Prezentace tabulky s TOP 10 filmy, včetně jejich hodnocení a počtu hlasů.

## Použité nástroje

- **Python**
- **Selenium** (web scraping)
- **BeautifulSoup** (parsování HTML)
- **Pandas** (analýza dat)
- **Matplotlib** (vizualizace dat)
- **ReportLab** (generování PDF)
- **Jupyter Notebook** (vývojové prostředí)