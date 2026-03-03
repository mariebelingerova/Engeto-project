Nejprve jsem si dle zadání zjistila společné roky pro tabulky czechia_price a czechia_payroll. Společné roky jsou od 2006 do 2018, pro další úpravu tabulek tedy budu používat toto období.

Jako dalším úkol jsem vytvořila primární a sekundární tabulky, kde budou obsaženy data mezd a cen potravin pro ČR a dodatečná data o dalších evropských státech. Tabulky jsem nazvala  **t_marie_belingerova_project_SQL_primary_final** a **t_marie_belingerova_project_SQL_secondary_final**.

Celý kód je obsažen v souboru "primary_final and secondary_final.sql"

**1. Rostou v průběhu let mzdy ve všech odvětvích, nebo v některých klesají?**
Ve většině sledovaných odvětví mzdy obecně rostou po většinu analyzovaného období. V několika odvětvích se však vyskytují jednotlivé roky, kdy mzdy klesaly. Tyto poklesy jsou spíše krátkodobé a nevytvářejí trvalý sestupný trend. Nejčastěji se poklesy mezd objevují v letech 2010–2013. Některá odvětví vykazují víceleté období stabilního růstu mezd bez významnějších poklesů (např. Doprava a skladování, Ostatní činnosti, Zdravotní a sociální péče, Zpracovatelský průmysl).

**2. Kolik je možné si koupit litrů mléka a kilogramů chleba za první a poslední srovnatelné období v dostupných datech cen a mezd?**
V roce 2006 bylo možné si za průměrnou měsíční mzdu koupit 1 287 kg chleba. V roce 2018 to bylo 1 342 kg.
V roce 2006 bylo možné si za průměrnou měsíční mzdu koupit 1 437 litrů mléka. V roce 2018 to bylo 1 642 litrů.

**3. Která kategorie potravin zdražuje nejpomaleji (je u ní nejnižší percentuální meziroční nárůst)?**
Nejpomalejší růst zaznamenaly potraviny cukr a rajská jablka, jejichž ceny meziročně dokonce mírně klesaly. 1% růst nepřekročily dále banány a vepřová pečeně s kostí.

**4. Existuje rok, ve kterém byl meziroční nárůst cen potravin výrazně vyšší než růst mezd (větší než 10 %)?**
V žádném roce meziroční růst cen potravin a mezd nepřekročil 10 %. Nejvyšší růst cen potravin byl v roce 2017 s hodnotou 9,63 %. Růst mezd byl v tomto roce nižší (6,28 %), ale rozdíl nebyl větší než 10 %. Nejvyšší růst mezd byl v roce 2008 (7,87 %), ale 10% hranici nedosáhl.

**5. Má výška HDP vliv na změny ve mzdách a cenách potravin? Neboli, pokud HDP vzroste výrazněji v jednom roce, projeví se to na cenách potravin či mzdách ve stejném nebo následujícím roce výraznějším růstem?**
V letech, kdy HDP roste výrazně (například 2007 – 5,57 %, 2015 – 5,39 %, 2017 – 5,17 %, 2018 – 3,2 %), mzdy přeročily 7 - 8% procentní hranici dvakrát, a to v roce 2008 a 2018. 10% hranice nebyla přeročena u žádného růstu cen. Nejvíce se k tomu přiblížil rok 2017 (9,63 %). V roce 2012, kdy HDP dokonce klesalo (-0,79 %) růst cen byl 6,72 %. HDP tedy vliv na růst cen nemá, na růst mezd mít může, ale potřebovali bychom sledovat delší časové období pro jasné určení.




