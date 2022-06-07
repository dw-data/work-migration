# Work Migration

_Idea:_  [Michel Penke](https://michelpenke.de)\
_Research, data analysis and data visualization:_ [Michel Penke](https://michelpenke.de)\
_Writing:_  Faisal Ahmed, [Michel Penke](https://michelpenke.de)

**Read the full articles on DW.com:**
- [Please, go home: How COVID-19 halted labor migration](https://www.dw.com/en/please-go-home-how-covid-19-halted-labor-migration/a-61839447)

Over the course of the coronavirus pandemic, just about every country in the world imposed travel restrictions to stop the spread of the virus. Especially hard hit by the restrictions are migrant workers, who have lost their jobs in many places due to lockdowns and have lost the ability to travel between their home and work countries due to travel bans. The analysis is devoted to the economic consequences of the pandemic for migrant workers. 

The following text will explain the process behind this story: Which data sources were used, how the analysis was conducted and how the data was visualized.

# Source data



| **Data** | **Source** | **Link** |
| --- | --- | --- |
| CoronaNet data collection | CoronaNet Project| [Data](https://www.coronanet-project.org)  |
| Personal remittances, recieved | World Bank | [Data](https://data.worldbank.org/indicator/BX.TRF.PWKR.CD.DT) |
| Personal remittances, paid | World Bank | [Data](https://data.worldbank.org/indicator/BM.TRF.PWKR.CD.DT) |
| Immigrants’ labour market outcomes  | OECD Libary | [Data](https://www.oecd-ilibrary.org/sites/29f23e9d-en/1/3/1/index.html?itemId=/content/publication/29f23e9d-en&_csp_=a9da7d4f182770aaa63ad86232529333&itemIGO=oecd&itemContentType=book#section-d1e10989) |
| ILO Global Estimates onInternational Migrant Workers |ILO | [Report](https://www.ilo.org/wcmsp5/groups/public/---dgreports/---dcomm/---publ/documents/publication/wcms_652001.pdf)
| Personal remittances, received (% of GDP) | World Bank | [Data](https://data.worldbank.org/indicator/BX.TRF.PWKR.DT.GD.ZS?name_desc=false)
|COVID-19 Crisis: Through a Migration Lens | KNOMAD | [Report](https://www.knomad.org/sites/default/files/2020-06/R8_Migration%26Remittances_brief32.pdf)
| Migration data relevant for the COVID-19 pandemic | Migration Data Portal | [Report](https://www.migrationdataportal.org/themes/migration-data-relevant-covid-19-pandemic) 
| Remittance Flows Register Robust 7.3 Percent Growth in 2021 | World Bank | [Report](https://www.worldbank.org/en/news/press-release/2021/11/17/remittance-flows-register-robust-7-3-percent-growth-in-2021)
| Locked down and in limbo: The global impact of COVID-19on migrant worker rightsand recruitment | ILO | [Report](https://www.ilo.org/wcmsp5/groups/public/---ed_protect/---protrav/---migrant/documents/publication/wcms_821985.pdf)
| Total number repatriated to India during Covid-19 under Vande Bharat Mission as on 30 April 2021 | MEA | [Report](https://mea.gov.in/vande-bharat-mission-list-of-flights.htm)
| The Impact of the Saudization Policy on Recruitment and Retention: A Case Study of the Banking Sector in Saudi Arabia | Researchgate | [Study](https://www.researchgate.net/publication/316022174_The_Impact_of_the_Saudization_Policy_on_Recruitment_and_Retention_A_Case_Study_of_the_Banking_Sector_in_Saudi_Arabia)
| Migration and the COVID-19 Pandemic in the Gulf | KAS | [Report](https://www.kas.de/documents/286298/8668222/Policy+Report+No+15+Migration+and+The+COVID-19+Pandemic+in+the+Gulf.pdf/87dd88bd-ed47-41c7-be23-48c5a5eb8d7c?version=1.0&t=1603448109241)
| The plight of migrants during COVID-19 and the impact of circular migration in India: a systematic review | Nature Magazin | [Study](https://www.nature.com/articles/s41599-021-00915-6)
| Covid-19 lockdown and migrant workers: Survey of vocational trainees from Bihar and Jharkhand | IdeasPande and coauthors: New data on India's migrant workers and Covid-19 for India | [Study](https://www.ideasforindia.in/topics/macroeconomics/covid-19-lockdown-and-migrant-workers-survey-of-vocational-trainees-from-bihar-and-jharkhand.html)
| Pande and coauthors: New data on India's migrant workers and Covid-19https://egc.yale.edu/data-migrant-covid19 | Yale Economic Growth Center | [Report](https://egc.yale.edu/data-migrant-covid19)
| Quarterly Report on Remittance Inflows in Bangladesh | Bangladesh Bank | [Report](https://www.bb.org.bd/pub/quaterly/remittance_earnings/oct-dec2021.pdf)


# Analysis
### Remittances flow

To show the geographically varying importance of labor migration and remittances, the ratio of payments paid and received per country was put into perspective and the results divided into quantiles to visualize their scatter. Since the values were more scattered in the area of received payments, the color scaling was increased by one unit. 

![](graphics/362_en_work-migration_global-flow.png)

### Remittances
For the graph of remittances, World Bank figures were accessed and the shares of the world regions were calculated.

![](graphics/365_en_work-migration_remittances.png)

_Caveats: The World Bank's figures for remittances received and paid are not entirely congruent. The difference is explained by the imprecision of the collection method, which requires the World Bank to draw on data from a large number of banks and central banks with varying methodological standards and varying degrees of measurement accuracy. For presentation purposes, this imprecision has been ignored and the sum of funds received and transferred has been equated at 100 percent. Therefore the sum of remittances received and paid are normalized but not equal in size._

### Unemployment
For the visualization of the "employment gap", the unemployment data of the native population and those of labor migrants were put into relation. This made it possible to compare data from countries with very different unemployment rates, since the "employment gap" is a relative ratio independent of the absolute rate. 

Seasonal fluctuations were not removed from the unemployment figures. However, the historical presentation should make the viewer aware of this and counteract any distortion. 

![](graphics/364_en_work-migration_unemployment.png)

### Restrictions
The chart of global travel restrictions is based on data from the CoronaNet Project, which compiles the number and types of anti-covid measures. The analysis filtered out measures that had nothing to do with restricting mobility as well as those that reduced mobility restrictions. The remainder were presented on a day-by-day basis. 

![](graphics/363_en_work-migration_restrictions.png)

_Caveats: It should be noted here that there was no qualitative assessment of the constraints. A nationwide "hard" lockdown with the threat of punishment was evaluated in exactly the same way as a partial and "soft" one that, for example, only froze certain regions of a country and imposed, but did not enforce, a quarantine._


_Caveats: It should be noted here that there was no qualitative assessment of the constraints. A nationwide "hard" lockdown with the threat of punishment was evaluated in exactly the same way as a partial and "soft" one that, for example, only froze certain regions of a country and imposed, but did not enforce, a quarantine._
