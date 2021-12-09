# pdv-nm

Our final election results validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2020-california-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed.

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions, or if you would like to request a full validation report.

## Raw from source

### Accessible files:

- File: CA VEST File, 2020
   - Date accessed: 11/07/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=5206371&version=28.0
- File: VEST Documentation File, 2020
   - Date accessed: 11/07/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=5431956&version=27.0
- File:CA Precinct-Level Election Results, 2020
  - Date accessed: 12/01/2021
  - Link: https://statewidedatabase.org/d10/g20.html
  - Note: srprec.zip
  - Shape Boundaries, 2020
- Accessed: 11/28/2020, Source: CA Statewide Database
  - https://statewidedatabase.org/d10/g20_geo_conv.html
  - Note: These shapes are not what VEST used
- Alameda County Shapefile
  - Accessed 12/5/2020, Source: Alameda County
  - https://data.acgov.org/datasets/364c65861fc044ddb1d250867c9d7e30_0/explore
  - Note: Used to spot check VEST’s shapefile validation work
- Glenn County SOV Consolidated Precincts
  - Accessed 11/07/2021, Source: Glenn County 
  - https://www.countyofglenn.net/government/resources/elections-voter-information/historical-statement-vote
  - Note: Used to deconsolidate precincts
- El Dorado County SOV Consolidated Precincts
  - Accessed 11/07/2021, Source: El Dorado County
  - https://edcgov.us/Government/Elections/Documents/20201103-sov-pct.pdf
  - Note: Converted to CSV format to deconsolidate precincts
- Imperial County SOV Consolidated Precincts
  - Accessed 11/07/2021, Source: Imperial County
  - https://elections.imperialcounty.org/election-data/
  - Note: Both A and B excel forms were consolidated to get the total vote amounts
- Inyo County SOV Consolidated Precincts
  - Accessed 11/07/2021, Source: Inyo County
  - https://elections.inyocounty.us/results/
- Madera County SOV Consolidated Precincts
  - Accessed 11/07/2021, Source: Madera County
  - https://votemadera.com/november-3-2020-presidential-general-election/
  - Note: Converted to CSV format to deconsolidate precincts
- Mendocino County SOV Consolidated Precincts
  - Accessed 11/07/2021, Source: Mendocino County
  - https://www.mendocinocounty.org/home/showpublisheddocument/39378/637425187809500000
- San Joaquin County SOV Consolidated Precincts
  - Accessed 11/07/2021, Source: San Joaquin County
  - https://www.sjgov.org/department/rov/results/election-results
- San Luis Obispo County SOV Consolidated Precincts
  - Accessed 11/07/2021, Source: San Luis Obispo
  - https://www.sjgov.org/department/rov/results/election-results
- Shasta County SOV Consolidated Precincts
  - Accessed 11/07/2021, Source: Shasta County
  - https://www.elections.co.shasta.ca.us/election-results/election-results/past-election-results/#Election
- Sierra County SOV Consolidated Precincts
  - Accessed 11/07/2021, Source: Sierra County
  - https://www.sierracounty.ca.gov/218/Election-Results
- Siskiyou County SOV Consolidated Precincts
  - Accessed 11/07/2021, Source: Siskiyou County
  - https://www.co.siskiyou.ca.us/sites/default/files/fileattachments/elections/page/6981/ele_20201103_certifiedelectionresults_20201130.pdf
- Sutter County SOV Consolidated precincts
  - Accessed 11/07/2021, Source: Sutter County
  - https://www.suttercounty.org/government/county-departments/clerk-recorder/elections/past-election-results/-folder-327

## File processing:

`vest-ca-2020-validation.ipynb` is the script that is the basis of the validation report
