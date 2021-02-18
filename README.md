# D3Times

![Newsroom](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

This project uses D3.js to visualize some state-level data about population health based on 2014 U.S. Census data.  It similates an on-line newpaper article with an interactive visualization.  Three risk factors (obesity, smoking, and uninsurance rates) are plotted against three perhaps underlying factors (income, poverty rate, and age).

The data set included with the assignment is based on 2014 ACS 1-year estimates from the [US Census Bureau](https://data.census.gov/cedsci/). The data set used, includes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."

![4-scatter](Images/4-scatter.jpg)

Scatter plot between two of the data variables such as `Healthcare vs. Poverty` or `Smokers vs. Age`.

### File Structure
- The base webpage template is index.html.
- The assets folder contains everything else of relevance
- assets/css holds two styling files, styles.css and d3style.css
- assets/data holds the data set in data.csv
- assets/js holds .eslintrc.json and app.js, the latter of which runs the javascript code that contains the visualization

### Running
Due to loading in a csv file, many browsers will fail to load this unless run on an http server.  This project was developed with the `python -m http.server` method.

### [Navi Sohi](https://github.com/PlainJane20) | Data Analytics & Visualization
