# ParseMetarTaf
This is a repo to show the progress of producing some code that is able to parse METAR's and TAF.

# File types and conventions 

## Conventions
As this is a project that will likely be forked from users new to the world of handling meteorological data and handling TAF's there will be extensive commenting done by both the authors and AI assistants (to fill in comments for if an author/commit doesn't include comments). Not adding comments is also a good way to not allow a push to go through as we want to be able to see the thought process unfold.

## CSV Files
These will be typically processed and downloaded from [Iowa State Mesonet](https://mesonet.agron.iastate.edu/request/daily.phtml) which allows people to download observation data as they see fit. 

## HTML Files
These are the downloaded files from [OGIMET](https://www.ogimet.com/) which allows people to download both the METAR's and the TAF's. However, we will do post-processing on it by just copying the TAF data as that is what would be desired. The reason for this is because we get the nicely formatted CSV files from IEM so lets just go with the TAF's for this data. 

## .PY and .IPYNB 
These are where the testing (typically .ipynb) will be done and then a final script (probably .py) will be made to run everything all at once, or seperate depending on what the user wants. 
