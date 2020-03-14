# British Columbia COVID-19 Case Data

This repository holds data on the patients in British Columbia found to have  COVID-19.

The data comes principally from
[press releases](http://www.bccdc.ca/about/news-stories/stories/2020/information-on-novel-coronavirus) issued by the
[BC Centre for Disease Control](http://www.bccdc.ca/).

Some gaps were filled in from a
[CTV article](https://bc.ctvnews.ca/timeline-every-case-of-covid-19-identified-in-british-columbia-1.4845820)
with details of every case up to #53.

There are two CSV files,
[one for the individual cases](cases.csv)
(including the date of diagnosis),
and
[one for the number of cumulative cases by day](cumulativeCases.csv).

I suspect that as the case count grows, we will stop getting individualized information
about each of the cases.

NOTE: On 13 March 2020, BC CDC started releasing *aggregated* information about
the patients, but not about the individuals.  
We do not know case number, age, gender, or health region after case #53.
