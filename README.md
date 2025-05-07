# milestone2-implementation
This is my final project in my intro to programming course. In this project, I explore COVID-19 Case Surveillance Public Use Data where the raw data has 100M+ rows. So I add filter cdc_report_dt <= '2020-04-30T00:00:00.000' and current_status IN ('Laboratory-confirmed case'). Then I filter columns age_group, race_ethnicity_combined, death_yn for effective data. After all these filters, the data turns to 0.014M data.
There are 2 visualization to show the bar chart of different age group death rate and different race_ethnicity gourp death group.
