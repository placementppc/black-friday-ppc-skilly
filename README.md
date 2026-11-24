# Black Friday PPC skilly

Dva skilly, se kterými AI připraví Black Friday kampaně za vás. Hlavní je Sklik, druhý je Meta Ads. Použijete je i na jiné časově omezené akce.

AI připraví návrh. V účtu se nic nezmění, dokud to neschválíte.

Demand Gen v Google Ads je ve Sklik skillu jen jako možnost.

## Co skilly umí

- Zeptají se na nabídku, termíny, rozpočet, měření a podklady. Ve třech kolech, ne po jedné otázce.
- Rozplánují akci do fází s daty: teaser, Black Week, Black Friday, víkend, Cyber Monday, poslední šance, konec.
- Pohlídají, aby akční banner po konci akce neběžel.
- Rozdělí publika do oken: košík 1-7 a 7-14 dní, prohlížení 1-7, 7-14 a 14-30 dní, nakoupili 30-365 dní. Nakupující za dobu akce vyloučí.
- Ve Skliku postaví mobil a desktop jako dvě kampaně s vlastním rozpočtem.
- Připraví zadání bannerů pro všechny rozměry Skliku a texty kombinované reklamy s počtem znaků.
- Navrhnou sdělení pro každé publikum zvlášť.
- V Metě zkontrolují Advantage+ publikum u košíku, plán reklam, akční ceny v katalogu a vylepšení kreativy, která by mohla změnit text slevy.
- Připraví vyloučení webů, frekvenci, UTM a pojmenování.
- Dají vám checklist před spuštěním, plán hlídání během akce a tabulku, jak všechny změny po akci vrátit.
- Umí i dávku klientů najednou. Stačí vyplnit tabulku `vstup-klienti.csv`.
- Hlídají, aby sleva odpovídala pravidlům ČOI (nejnižší cena za 30 dní).

## Stažení

Celá složka jako ZIP:

https://github.com/placementppc/black-friday-ppc-skilly/archive/refs/heads/main.zip

Na stránce repozitáře to samé uděláte přes Code a pak Download ZIP.

V ZIPu najdete:

- `BF-skill-Sklik.md`, skill na Sklik
- `BF-skill-Meta.md`, skill na Meta Ads
- `vstup-klienti.csv`, tabulka pro dávku klientů (oddělovač středník, otevřete v Excelu nebo Google Tabulkách)

## Jak skilly použít

Skilly jsou delší texty. Proto je nahrajte jako soubor, ne do krátkého pole pro instrukce.

1. Claude: v nastavení skillů přidejte skill jako ZIP. Vytvořte složku `black-friday-sklik`, dejte do ní soubor `BF-skill-Sklik.md` přejmenovaný na `SKILL.md` a složku zabalte do ZIPu. Stejně pro `black-friday-meta`. Nebo soubor nahrajte do projektu.
2. ChatGPT: nahrajte soubor do projektu. Do instrukcí projektu napište: Řiď se souborem BF-skill-Sklik.md.
3. Gemini: nahrajte soubor jako znalost do Gemu, nebo do chatu.
4. Grok: nahrajte soubor do projektu, nebo do chatu.

Pak napište: Nachystej mi Black Friday kampaně podle skillu.

Pro víc klientů napište: Nachystej Black Friday kampaně pro klienty z přiložené tabulky. A přiložte vyplněný `vstup-klienti.csv`.

## Než začnete

- Čísla si skill nevymýšlí. Rozpočet, slevu a termíny musíte dodat vy.
- Pravidla Skliku a Mety se mění. Skill má u každého pravidla odkaz na zdroj a datum ověření.
- Právní pravidla slev jsou ve skillu jako kontrola, ne jako právní rada.

## Webinář a klub

Když budete chtít vidět, jak s AI tvoříme kampaně od začátku, tady je záznam webináře Tvořte PPC kampaně pomocí AI:

https://vzdelavani.placement.cz/webinare/ppc-fachman

Pokud chcete daleko víc než jeden skill, můžete vstoupit do klubu Nefér výhoda:

https://vzdelavani.placement.cz/klub

## Autor

Jakub Herrmann, PLACEMENT.cz

https://www.linkedin.com/in/jakubherrmann/

Licence MIT. Verze 3, 24. 11. 2026.
