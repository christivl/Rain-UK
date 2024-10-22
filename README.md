## Interactive Jupyter Notebooks

It is possible to view the interactive Jupyter notebooks and run them on Google Colab using the following links:

1. Curve Fitting - London Rain: 
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)][https://colab.research.google.com/github/](https://colab.research.google.com/github/christivl/Rain-UK/blob/main/Curve_Fitting_London_Rain.ipynb)

2. Automation
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)][https://colab.research.google.com/github/](https://colab.research.google.com/github/christivl/Rain-UK/blob/main/Automation.ipynb)


3. Colourmaps and animated plots:
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)][https://colab.research.google.com/github/](https://colab.research.google.com/github/christivl/Rain-UK/blob/main/Colourmaps_and_animated_plots.ipynb)


## List of files:

### Jupyter Notebooks

1. Curve_Fitting_London_Rain.ipynb
2. Automation.ipynb
3. Colourmaps_and_animated_plots.ipynb

### Additional files

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

4. yearly_rain

An animated plot (gif), of the UK map, indicating the cities, for which we calculated the number of rainy days per year. Each snapshot corresponds to one year, from 2001 up to 2023. The colour of the scatter points corresponds to the amount of rainy days for that year. This plot is generated by the 3rd Notebook (Colourmaps and animated plots).
