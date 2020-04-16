# Coronavirus datasets

This is a mirror of the data presented on the [PHE Coronavirus Dashboard](https://coronavirus.data.gov.uk/).

The data behind the dashboard is not easy to query, although it is obtainable by looking at [the dashboard codebase](https://github.com/PublicHealthEngland/coronavirus-dashboard).

This repository holds the raw JSON data and versions of the CSV files that are downloadable via javascript from the dashboard app.

The files in the data directory are:

* `data.json` - latest data using the procedure defined by the PHE app
* `coronavirus-cases.csv` - cases data in the PHE format
* `coronavirus-deaths.csv` - deaths data in the PHE format
* `metadata.json` - metadata - currently only the timestamp the build was run

WARNING - the data from PHE is not clearly licensed. I assume that it is licensed under the [Open Government License](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)