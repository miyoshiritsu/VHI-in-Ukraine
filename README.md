# What is VHI-in-Ukraine?

For this code to work you will need to install [pandas library](https://github.com/pandas-dev/pandas) first.

This code takes raw data from [NOAA STAR site](https://www.star.nesdis.noaa.gov) about VHI values in Ukraine and creates a pandas DataFrame from it.

When you run this code, you can choose the index of the region (the indexes are in alphabetical order) and the year to find VHI values for this specific region during this specific year. It then prints VHI values for this region during the year the user provided according to the week (some weeks can be missing as the site didn't provide full information). The code also prints max and min VHI values for this region and years during which there was severe drought (VHI<=15%) and then during which there was moderate drought (35%<=VHI>=15%).

# UPDATE

The code VHI-in-Ukraine-app creates a web app that makes it easier to choose specific region and time series (VCI, TCI or VHI), This app also visualizes information by plotting the data.

For this code to work you will also need to install [dataspyre library](https://github.com/adamhajari/spyre).
