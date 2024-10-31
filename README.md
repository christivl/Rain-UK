## This Project
This is a personal project, displaying my current skills in data science. It consists of three mini-projects, each in the form of a Jupyter Notebook, focussing on working with databases and analysing and visualising data.

1. Curve Fitting:

This notebook retrieves the historical rainfall data for London from 1980 from a publicly available API (OpenMeteo). It then calculates the number of rainy days per year and plots the yearly rain count. Finally, a third-order Fourier series is fitted to the data.

2. Automation:

It finds the geographical coordinates (Latitude, Longitude) of all the UK cities from a public database (GeoNames) and retrieves the 

3. Colourmaps & Animated Plots




## Why the weather
The most popular small talk topic in the UK is the weather! "Is it going to rain today?" or "Will we have a sunny weekend?" and similar questions are part of a conversation, almost every day!

The common interest in the weather motivated me to start this personal project, along with the fact that there are plenty 
of weather databases and many of them are free-access.




## Usage
All the Jupyter notebooks can be viewed as "static" files on GitHub. However, there is also the possibility of viewing each of them interactively and running them locally on Google Colab, using the following links:

1. Curve Fitting - London Rain: 
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)][https://colab.research.google.com/github/](https://colab.research.google.com/github/christivl/Rain-UK/blob/main/1_Curve_Fitting_London_Rain.ipynb)

2. Automation
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)][https://colab.research.google.com/github/](https://colab.research.google.com/github/christivl/Rain-UK/blob/main/2_Automation.ipynb)

3. Colourmaps and animated plots:
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)][https://colab.research.google.com/github/](https://colab.research.google.com/github/christivl/Rain-UK/blob/main/3_Colourmaps_and_animated_plots.ipynb)

The text files and the plots produced by the three scripts can also be found in this branch.

## List of files:

### Jupyter Notebooks

1. Curve_Fitting_London_Rain.ipynb
2. Automation.ipynb
3. Colourmaps_and_animated_plots.ipynb

### Text files

1. rain_AVG_city.txt:

Text file containing the data needed for the 3rd Notebook (Colourmaps and animated plots).
It contains the number of rainy days for each year, from 2000 to 2023, for 270 UK cities.
Its format is the following:

CITY | 2001 | 2002 | ... | 2023 |
--- | --- | --- | --- | ---
City 0 | x rainy days | y rainy days | ... | z rainy days |
City 1 | x rainy days | y rainy days | ... | z rainy days |
... | ... | ... | ... | ...
City 270 | x rainy days | y rainy days | ... | z rainy days |

2. rain_40_cities.txt

A text file in the same format as "rain_AVG_city.txt", produced by the second Jupyter Notebook (Automation), containing the rain information for the first 40 cities (out of the 270).


3. City_coords.txt

A text file, containing the Latitude and Longitude of every city, in decimals. This file is generated by the 2nd Notebook (Automation) and it is of the format:

Link | Latitude | Longitude |
---  | --- | ---
City 0 | 51.5083 | -0.1256|
City 1 | x Latitude | y Longitude |
... | ... | ...
City 300 | x Latitude | y Longitude |

### Interactive geospatial plot

"yearly_rain"

An animated plot (gif), of the UK map, indicating the cities, for which we calculated the number of rainy days per year. Each snapshot corresponds to one year, from 2001 up to 2023. The colour of the scatter points corresponds to the amount of rainy days for that year. This plot is generated by the 3rd Notebook (Colourmaps and animated plots).


## Future Work


## Sources

