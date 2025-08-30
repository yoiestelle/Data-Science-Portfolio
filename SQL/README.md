# 🚀 SpaceX Falcon 9 Launch Analysis with SQL

## Project Overview

SpaceX has gained worldwide attention for a series of historic milestones. It is the only private company to return a spacecraft from low-Earth orbit, first accomplished in December 2010. Falcon 9 launches are advertised at $62M per launch compared to $165M+ from competitors, with much of the cost savings attributed to the reusability of the first stage.
Predicting whether the first stage will land successfully is critical, since successful landings lower costs and improve competitiveness. These insights are valuable for competitors, investors, and policymakers who want to evaluate SpaceX’s market position or bid for launch contracts.
This dataset contains detailed records of Falcon 9 missions, including launch sites, payloads, customers, booster versions, and mission outcomes. Using SQL queries, I analyze the dataset to answer key business questions about payload distribution, customer demand, launch success rates, and booster performance.

## Dataset Description
This dataset is provided as part of the IBM Data Science Capstone project. It is compiled from publicly available launch records (SpaceX, NASA, Wikipedia) and contains detailed information on Falcon 9 launches. Each record corresponds to a Falcon 9 mission and includes fields such as launch date, booster version, payload mass, launch site, customer, orbit type, mission outcome, and landing outcome.

While this dataset is curated for educational purposes, it is based on real mission data and provides a reliable representation of SpaceX’s launch history up to the point of compilation.

## Key Findings
- Launch Sites: Falcon 9 missions launched mainly from Cape Canaveral (CCAFS LC-40, SLC-40), Kennedy Space Center (LC-39A), and Vandenberg (SLC-4E).
- Customers: NASA CRS contributed significant payload mass, showing SpaceX’s deep partnership with NASA.
- Payload Mass: The average payload mass for F9 v1.1 boosters was ~2,928 kg.
- Reusability Milestone: The first successful ground pad landing occurred on 2015-12-22.
- Drone Ship Success: Boosters such as F9 FT B1022 and B1026 succeeded with medium payloads.
- Mission Outcomes: Out of 101 missions, 99 succeeded, with only 1 in-flight failure and 1 unclear payload status. This indicates a 97%+ success rate in payload delivery.
- Landing success improved markedly over time: overall success rate rose from 0% (2010–2014) to ~78% in 2017, ~91% in 2019, and ~88% in 2020. When excluding “No attempt”/“Precluded” launches, the success rate on attempted recoveries is even higher — highlighting SpaceX’s rapid iteration on reusability.
- SpaceX itself is the largest customer, with ~185,000 kg of payload delivered — highlighting how Falcon 9 has been used extensively for internal projects.
Iridium Communications (67,200 kg) and NASA CRS (~45,600 kg) are also major customers, showing SpaceX’s strong role in both commercial satellite deployment and government partnerships.
Other contributors include Planet Labs and SES, pointing to SpaceX’s diverse customer base across communications, Earth observation, and broadcasting.
These results underscore that while SpaceX relies heavily on its own launches, it has also become a critical provider for government missions and private industry.
