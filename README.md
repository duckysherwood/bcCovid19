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

# Notes
On 13 March 2020, BC CDC started releasing *aggregated* information about
the patients, but not about the individuals.  
We do not know case number, age, gender, or health region after case #53.

Cases #48 and #49 were originally said to be staff at both Hollyburn and Lynn
Valley; on 14 March, Dr. Henry corrected that to say that only one was at Hollyburn,
and the other was only Lynn Valley.  However, she did not clarify if it was case #48
or case #49.  I have arbitrarily chosen to say that case #48 was Lynn Valley only.

Also on 14 March, Dr. Henry reclassified two of the Vancouver Health patients
as Northern Health patients.  They work in the Coastal Health region but live in 
Northern Health region.

On 16 March, there were 30 cases announced, but there was no press conference yesterday,
so it LOOKS like there were no cases on Sunday and a bunch on Monday.  I thought about
putting half of the cases on Sunday and half on Monday, but that doesn't seem honest
either.

On 16 March, Dr. Henry mentioned that there are a number of residents at the Lynn Valley
Care Home who have tested positive, and that four Lynn Valley residents have died.
I only see four Lynn Valley residents total who tested positive, so I don't know if
those other residents tested positive over the weekend or if there were some which 
were not correctly categorized.

Starting on 16 March, they are not giving breakouts on individual cases, so I will not
continue to update cases.csv.

On 17 March, I renamed 'deaths' and 'recovered' to 'new deaths' and 'newly recovered'
to make it more clear.

On 17 March, I dropped the columns for where the new cases were because everybody's 
got it.
