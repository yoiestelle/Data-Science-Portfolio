# 🚀 SpaceX Falcon 9 Launch Analysis with SQL

## Project Overview

SpaceX has gained worldwide attention for a series of historic milestones. It is the only private company to return a spacecraft from low-Earth orbit, first accomplished in December 2010. Falcon 9 launches are advertised at $62M per launch compared to $165M+ from competitors, with much of the cost savings attributed to the reusability of the first stage.
Predicting whether the first stage will land successfully is critical, since successful landings lower costs and improve competitiveness. These insights are valuable for competitors, investors, and policymakers who want to evaluate SpaceX’s market position or bid for launch contracts.
This dataset contains detailed records of Falcon 9 missions, including launch sites, payloads, customers, booster versions, and mission outcomes. Using SQL queries, I analyze the dataset to answer key business questions about payload distribution, customer demand, launch success rates, and booster performance.

## Key Findings
- Launch Sites: Falcon 9 missions launched mainly from Cape Canaveral (CCAFS LC-40, SLC-40), Kennedy Space Center (LC-39A), and Vandenberg (SLC-4E).
- Customers: NASA CRS contributed significant payload mass, showing SpaceX’s deep partnership with NASA.
- Payload Mass: The average payload mass for F9 v1.1 boosters was ~2,928 kg.
- Reusability Milestone: The first successful ground pad landing occurred on 2015-12-22.
- Drone Ship Success: Boosters such as F9 FT B1022 and B1026 succeeded with medium payloads.
- Mission Outcomes: Out of 100+ missions, 98 were successful, with very few failures.
