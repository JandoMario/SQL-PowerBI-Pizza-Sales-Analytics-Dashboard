# SQL-PowerBI-Pizza-Sales-Analytics-Dashboard
Interactive Business Intelligence project focusing on sales data analysis, demonstrating ETL processes, and dashboard visualization utilising SQL and PowerBI.
SQL querries available in text document, PBI reports available in .pbix file or with png screenshots.

EN: The project was implemented with the aim of analyzing historical pizza sales data and providing management with key information about financial performance and operational peaks.

The project began by querying a database to filter, aggregate, and structure raw data into five specific tables. The following SQL queries were performed:

1.Most Popular Pizza and Size: Aggregated the sum of quantity by both name and size to identify specific high-volume product combinations.

2.Size Popularity and Average Price: Analyzed the relationship between pizza sizes, total quantity ordered, and the average unit price.

3.Total Revenue by Pizza Name: Calculated the total revenue and quantity sold for every individual pizza variety.

4.Total Revenue by Pizza Category: Grouped sales by categories to determine which drive the highest revenue.

5.Amount of Orders by Part of Day: Utilized a CASE statement to bin order times into "morning" "noon" "afternoon" and "evening" counting distinct order IDs to identify peak traffic.

Once the five SQL result sets were imported, the data underwent minor cleaning through Power Query.
The finalized analysis was presented through two distinct dashboards. The Financial Dashboard displays KPI cards for total revenue and total quantity sold, alongside a pie chart for category distribution and a bar chart highlighting the top revenue-generating pizzas. The Popularity Dashboard features a treemap for item popularity, a donut chart for size distribution, and a line chart that visualized the daily order distribution to determine peak periods.


SK: Projekt bol implementovaný s cieľom analyzovať historické údaje o predaji pizze a poskytnúť manažmentu kľúčové informácie o finančnej výkonnosti a prevádzkových špičkách.

Projekt sa začal dotazovaním databázy na filtrovanie, agregáciu a štruktúrovanie nespracovaných údajov do piatich špecifických tabuliek.
Boli vykonané nasledujúce SQL dotazy:

1.Najobľúbenejšia pizza a veľkosť: Agregácia súčtu množstva podľa názvu aj veľkosti s cieľom identifikovať konkrétne kombinácie produktov s vysokým objemom.

2.Obľúbenosť veľkosti a priemerná cena: Analýza vzťahu medzi veľkosťami pizze, celkovým objednaným množstvom a priemernou jednotkovou cenou.

3.Celkové tržby podľa názvu pizze: Vypočítali sa celkové tržby a predané množstvo pre každý jednotlivý druh pizze.

4. Celkové tržby podľa kategórie pizze: Zoskupenie predajov podľa kategórií s cieľom určiť, ktoré prinášajú najvyššie tržby.

5.Množstvo objednávok podľa časti dňa: Použitý bol príkaz CASE na rozdelenie časov objednávok do kategórií "morning" "noon" "afternoon" a "evening" pričom sa počítali odlišné ID objednávok na identifikáciu špičky prevádzky.

Po importovaní SQL dotazov boli údaje mierne čistené pomocou Power Query. Analýza bola prezentovaná prostredníctvom dvoch odlišných dashboardov. Finančný dashboard zobrazuje karty KPI pre celkové príjmy a celkové predané množstvo, spolu s koláčovým grafom pre rozdelenie podľa kategórií a stĺpcovým grafom zvýrazňujúcim pizze s najvyšším generovaním príjmov. Dashboard popularity obsahuje stromovú mapu pre popularitu položiek, prstencový graf pre rozdelenie veľkosti a čiarový graf, ktorý vizualizuje denné rozdelenie objednávok na určenie období špičky.
