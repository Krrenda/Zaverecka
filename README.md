# Scraping výsledků voleb 2017

## Popis projektu
Tento projekt scrapuje výsledky voleb 2017 pro konkrétní územní celek z webu volby.cz a ukládá je do výsledného souboru CSV.

## Instalace
1. Vytvořte virtuální prostředí pomocí Windows CMD:

    python -m venv venv
    source venv/bin/activate  # Pro Windows použijte `venv\Scripts\activate`


2. Nainstalujte potřebné knihovny:

    pip install -r requirements.txt


## Použití
Spusťte skript s následujícími argumenty:

python volby17.py "<URL>" "<vystupni_soubor.csv>"
