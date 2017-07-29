---
permalink: /resources/
author_profile: true
redirect_from:
  - /research
---

{% include base_path %}

## Geography Tools

**1950 State Economic Areas (SEAs) to 1990 Commuting Zones (CZs) crosswal.** Stata file available [here](/files/cz_sea_cw_ekr.dta). 
- This crosswalk is designed to match the State Economic Area codes available in IPUMs census extracts for 1940 and 1950. It was constructed in the same way as crosswalks between other geographic concepts and 1990 commuting zones available from David Dorn's website.
- Each SEA's constituent counties were matched to their 1990 CZs. When an SEA contains counties that match to multiple CZs, the SEA is assigned to both commuting zones with weights proportional to its population overlap with each CZ. For example, if an SEA contains two counties with equal populations, each of which map into different CZs, the SEA will match to both CZs with weights equal to 0.5.
- A SEA to CZ crosswalk is also available from Dorn's website. It does not appear to match the current SEA codes available in IPUMS extracts (as of July 2016). The Los Angeles area (SEA 42), for example, is not included.

**1960 Public Use Microdata Areas (PUMAs) to 1990 Commuting Zones (CZs) crosswalk.** Stata file available [here](/files/cz_puma1960_cw_direct.dta).
- This crosswalk is designed to match the PUMAs constructed for the 1960 5% sample available from IPUMs.
- The 1960 PUMAs comprise counties and 1960 census tracts. They were constructed to align as closely as possible to the 2000 PUMAs. Each 2000 PUMA maps into a single 1960 PUMA. While many 1960 PUMAs consist of a single 2000 PUMA, some consists of two or more. More information is available here.
- To construct this crosswalk, the relationships between 1960 PUMAs and their county / census tracts components was combined with information on the counties included in each CZ. Each 1960 PUMA's constituent counties or census tracts were matched to their 1990 CZs. As above, when a 1960 PUMA contains counties or census tracts that map to multiple CZs, the 1960 PUMA is assigned to all matching CZs with weights proportional to its population overlap in each.
- Population counts for 1960 counties and census tracts are preliminary and may be subject to minor revisions as IPUMS / NHGIS update the data.


## Miscellanea
- [What's the best way to sort exams and problem sets?](https://stackoverflow.com/questions/9741231/best-algorithm-to-sort-exams/35517412#35517412?newreg=3872a97fce9f4b90aaa7896bd0d670ab)
- [When should I go to the gym?](/files/when_should_I_go_to_the_gym.pdf)
