# Vaccine-Immunizations-Analysis
This project explores 2017 data on immunizations from the CDC, USA.
You can find the raw data file in [NISPUF17.csv](NISPUF17.csv).
The data users guide to map the variables is available at [NIS-PUF17-DUG.pdf](NIS-PUF17-DUG.pdf).

The project looked into 4 questions as in the following:
## Proportion of Education
This first section is a function which returns the proportion of children in the dataset who had a mother with the education levels equal to less than high school (<12), high school (12), more than high school but not a college graduate (>12) and college degree.

## Breastmilk fed and seasonal influenza vaccine injection
This function looks into the relationship between being fed breastmilk as a child and getting a seasonal influenza vaccine from a healthcare provider, and returns a tuple of the average number of influenza vaccines for those children we know received breastmilk as a child and those who know did not.

## Link between vaccine effectiveness and sex of the child
It would be interesting to see if there is any evidence of a link between vaccine effectiveness and sex of the child. This function calculates the ratio of the number of children who contracted chickenpox but were vaccinated against it (at least one varicella dose) versus those who were vaccinated but did not contract chicken pox. Return results by sex.

## Correlation between having had the chicken pox and the number of chickenpox vaccine doses given (varicella).
This function is to see if there is a correlation between having had the chicken pox and the number of chickenpox vaccine doses given (varicella).

This isn’t really the full picture, since we are not looking at when the dose was given. It’s possible that children had chickenpox and then their parents went to get them the vaccine.

