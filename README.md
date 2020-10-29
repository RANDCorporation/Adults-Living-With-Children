# RAND Commentary – Sitting It Out? Or Pushed Out? Women Are Leaving the Labor Force in Record Numbers
ED & Labor Unit

This GitHub repository supports a RAND Commentary written by Kathryn Edwards published on October 23, 2020 and can be found at the following URL: https://www.rand.org/blog/2020/10/sitting-it-out-or-pushed-out-women-are-leaving-the.html.

#### -- Project Status: Completed.

## Project description
This code supports a commentary that measures the labor force status of men and women age 18-55 since January 2020 based on whether the person has a child (defined as individual under 18 years old) in the household. We further divide individuals by how many children they live with (0, 1, 2, 3+, or 1+) and the age of the oldest child (0-1, 2-6, 7-12, 13-17). For each gender and children group, we count the number of individuals who are employed, unemployed, and not in the labor force. We then calculate the labor force participation rate, which is the number employed and unemployed over the total population.

### Methods used
* Descriptive statistics

### Technologies
* Stata

## Getting started

1. Download the two Do files in this repository.

2. Download data from the cps.ipums.org (see “Analysis” do file for list of variables).
    
3. Run “Analysis – Adults Living With Children.do” to generate the statistics referenced in the commentary.

### Other notes

The data for figure 1 (Men and Women’s Labor Force Participation Rate, Age 16 and Older, 1948-2019) comes from the Bureau of Labor Statistics Employment Situation Summary. Specifically, the data are from Historical A Tables, Table A1. To access this data, please perform the following steps:

1. Go to: https://www.bls.gov/cps/cpsatabs.htm
2. Select “Table A-1. Employment status of the civilian population by sex and age”
3. Select the not seasonally adjusted, participation rate options for “Men, 16 years and over” and “Women, 16 years and over”. “Participation rate” can be found under “Civilian labor force”.
4. Click retrieve data
5. Go to “more formatting options” and select “All years”, “Annual Data”, and the “Multi-series table” options. Then click retrieve data.

LNU01300001 - Men, 16 years and over
LNU01300002 - Women. 16 years and over

Data extract from the CPS downloaded on September 22, 2020 by Daniel Schwam.

Reference(s): 

1. Sarah Flood, Miriam King, Renae Rodgers, Steven Ruggles and J. Robert Warren. Integrated Public Use Microdata Series, Current Population Survey: Version 7.0 [dataset]. Minneapolis, MN: IPUMS, 2020. https://doi.org/10.18128/D030.V7.0

2. Bureau of Labor Statistics, Employment Situation Summary.

## Project members:

Kathryn Edwards (kathryne@rand.org) and Daniel Schwam (dschwam@rand.org)
* Feel free to contact team leads with any questions or if you are interested in contributing!

## Suggested citation for this repository:

Schwam, Daniel, and Kathryn Edwards, “Adults Living with Children” GitHub, RAND Corporation Repository, last updated 29 September 2020. As of September 29, 2020: URL
