# verispy_to_csv
Extends the Verispy project (https://github.com/RiskLens/verispy), producing a CSV file suitable for import into Onspring, Tableau, or any analysis platform. Note that you'll also need to clone the Versipy repo to make this work. 

Filters out non-US data and focuses on specific industry codes, which can/should be edited as needed.

The current version favors interpreting data columns over pivot tables due to the internal project specifications. This can be modified to produce values and levels of details suitable for your needs. 

Discards or interprets most columns; the initial 2408 dataframe columns are reduced to 13 columns required for internal reporting. Removed columns are grouped, so if your project needs different information, it should be possible to edit accordingly. 