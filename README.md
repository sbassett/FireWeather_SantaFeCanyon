# FireWeather_SantaFeCanyon



## Methods
Download FireFamilyPlus v5: https://www.firelab.org/document/firefamilyplus-software

Download station data in FW13 format from famweb: https://fam.nwcg.gov/fam-web/weatherfirecd/state_data.htm

Santa Fe Canyon station number is 290901

Open FFP and create a new DB (/FFPDB/SantaFeCanyonRAWS.mdb)

Import data (File -> Import)

Select the FW13 file.

Choose 290901 as the SIG/Station 

Change data years to be through 2020.

Set annual filter for fire season (roughly March 1 through July 31)

Save the DB (overwrite is OK)

Click on Weather -> Climatology

For 1-hour FM, 10-hr FM, 100 hr FM, Herb FM and Woody FM: set your critical points (CP #1 and CP #2) to the percentiles that you're planning to run though FlamMap. E.g. 10 is 90th percentile dryness, 3 is 97th percentile dryness.

Check the "Daily Freqs" box for the above variables.

Click Run.

See the "Variable: ..." section of the resulting files fro the "critical point" percentile values.

## Results

Santa Fe Canyon Results (daily values 2004-2020):

Variable | 90th Pctile | 97th Pctile
-- | -- | --
1hr FM | 1.96 | 1.39
10-hr FM | 2.85 | 2.14
100-hr | 5.38 | 4.34
Herb FM | 1.96 | 1.39
Woody FM | 60 | 60



