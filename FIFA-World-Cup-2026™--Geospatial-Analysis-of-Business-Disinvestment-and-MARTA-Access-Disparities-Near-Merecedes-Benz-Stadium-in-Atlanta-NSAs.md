FIFA World Cup 2026™: Geospatial Analysis of Business Disinvestment and
MARTA Access Disparities Near Merecedes-Benz Stadium in Atlanta NSAs
================
Savannnah Drake

Brief Introduction: Disinvestment and unequal access to transportation
infrastructure shape economic opportunities across Atlanta. In this
project, I use spatial analysis to examine:

- Where disinvested businesses are concentrated

- How these patterns align with Neighborhood Statistical Areas (NSAs)

- How closely MARTA transit access aligns with areas of high need

- How distance to major landmarks, specifically Mercedes-Benz Stadium,
  relate to disinvestment patterns

This report was developed for the AI.Data Lab and demonstrates my skills
in spatial data processing, geospatial joins, visualization, and
exploratory data analytics.

Methods:

Data Sources

- Atlanta Neighborhood Statistical Areas (shapefile)

- Business license data (CSV) with latitude/longitude and disinvestment
  flags

- MARTA stop shapefile

- Mercedes-Benz Stadium coordinates

Analytical Workflow

- Load and clean spatial datasets

- Convert business license coordinates into spatial points

- Join businesses to NSAs via geometric intersection

- Summarize disinvestment counts per NSA

- Identify NSAs with high levels of disinvestment

- Analyze MARTA access within NSAs

- Measure distance from NSA centroids to the stadium

- Visualize spatial disparities across Atlanta

Map 1: Distribution of Disinvested Businesses(points)

![](FIFA-World-Cup-2026™--Geospatial-Analysis-of-Business-Disinvestment-and-MARTA-Access-Disparities-Near-Merecedes-Benz-Stadium-in-Atlanta-NSAs_files/figure-gfm/disinvested%20businesses%20distribution-1.png)<!-- -->

Figure note: Points show individual business locations and whether they
are flagged as “disinvested” in the license data.

Map 2: NSA Chloropleth: Disinvested Business Counts
![](FIFA-World-Cup-2026™--Geospatial-Analysis-of-Business-Disinvestment-and-MARTA-Access-Disparities-Near-Merecedes-Benz-Stadium-in-Atlanta-NSAs_files/figure-gfm/NSA%20chloropleth-1.png)<!-- -->

Map 3: Disinvested Businesses, MARTA Stops, and Stadium
![](FIFA-World-Cup-2026™--Geospatial-Analysis-of-Business-Disinvestment-and-MARTA-Access-Disparities-Near-Merecedes-Benz-Stadium-in-Atlanta-NSAs_files/figure-gfm/MARTA%20stops-1.png)<!-- -->

Table 1: Top NSAs by Disinvested Businesses, MARTA Access, Distance to
Stadium

| NSA | Disinvested Businesses(\>=50) | MARTA stops | Distance to stadium(km) |
|:----|------------------------------:|------------:|------------------------:|
| L01 |                            51 |          30 |               0.9592807 |
| K02 |                            81 |          35 |               2.4316666 |
| V03 |                            62 |          34 |               3.3929628 |
| S01 |                            74 |          39 |               4.0714353 |
| X01 |                            62 |          17 |               4.2866111 |

Plot 4: High-Disinvestment NSAs : MARTA stop counts(ranked)
![](FIFA-World-Cup-2026™--Geospatial-Analysis-of-Business-Disinvestment-and-MARTA-Access-Disparities-Near-Merecedes-Benz-Stadium-in-Atlanta-NSAs_files/figure-gfm/plot4-1.png)<!-- -->

Plot 5: Priority Plot: Disinvestment, MARTA, & Stadium Proximity
![](FIFA-World-Cup-2026™--Geospatial-Analysis-of-Business-Disinvestment-and-MARTA-Access-Disparities-Near-Merecedes-Benz-Stadium-in-Atlanta-NSAs_files/figure-gfm/plot5-1.png)<!-- -->

Discussion:

This analysis reveals several major findings:

- Disinvestment is heavily concentrated in select NSAs, many of which
  show limited MARTA accessibility.

- Several high-disinvestment NSAs are close to economic hubs, suggesting
  potential for targeted investment.

- NSAs far from the stadium are disproportionately disinvested and
  underserved by MARTA.

- Visual analysis supports the idea that transit inequality mirrors
  economic inequality.

This framework can support equitable policy decisions around
infrastructure, business support, and mobility planning.

Conclusion:

This project combines spatial data processing, geospatial statistical
joins, and layered visualization to reveal structural inequities across
Atlanta. The workflow demonstrates technical skills in:

- R, R Markdown

- GIS and spatial joins

- Exploratory spatial analysis

- Data storytelling and visualization
