
## P1: Investigate A Dataset (Gapminder World Dataset)

### Prerequisites

Additional installations: 

* [Missingno](https://github.com/ResidentMario/missingno)
* [pycountry](https://bitbucket.org/flyingcircus/pycountry)
* [pycountry-convert](https://pycountry-convert.readthedocs.io/en/latest/)

## Project Overview

### Data Sources

**Name: Population total**

- Definition: Total population
- Source: http://gapm.io/dpop
- Version: 5

**Name: Life expectancy (years)**

- Definition: The average number of years a newborn child would live if current mortality patterns were to stay the same.
- Source: http://gapm.io/ilex
- Version: 9

**Name: Income per person (GPD/Capita, PPP$ inflation-adjusted)**

- Definition: Gross domestic product per person adjusted for differences in purchasing power (in international dollars, fixed 2011 prices, PPP based on 2011 ICP).
- Source: http://gapm.io/dgdppc
- Version: 25

### Wrangling

For the analysis, following countries were dropped out of the dataframe due to too much missing data:

- Andorra, Dominica, Holy See, Liechtenstein, Marshall Islands, Monaco, Nauru, Palau, San Marino, St. Kitts and Nevis, Tuvalu

### Summary

- We can observe an overall and ongoing uptrend for the world population, the income per person and the life expectation

- especially between 1950 and 1975 was a starting point for a strong increase in all three metrics

- the world population is increasing strongly and one observable reason for that is the increase in the overall life expectancy

- we also found out that there is a relationship between the income per person and the life expectancy. An increasing income is no guarantee for an also increasing life expectancy, but it is correlated

### Authors

* Christoph Lindstädt
* Udacity

## License

* <a rel="license" href="https://creativecommons.org/licenses/by-nc-nd/4.0/"> Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>

<a rel="license" href="https://creativecommons.org/licenses/by-nc-nd/4.0/">
	<img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" />
</a>
