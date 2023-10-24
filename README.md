# Birth_Rate_Analysis
An exploratory analysis of birth data

INTRODUCTION

The data used in this project is a record of births in the United States between 1969 and 1988. The data was provided by the Centers for Disease Control. The goal of this project was to explore the data for birth trends.

EXPLORATORY ANALYSIS

The data was mostly explored by visualization. Since the main attributes in the dataset are number of births and dates, the data was visualized to observe the birth trends by year, month, and day. Some errors with data entry were found during the analysis, and they were resolved.

RESULTS

There were more male than female births by year, month, and day. Fewer births were recorded on weekends than on weekdays. There was a sharp decline in birth rate from 1970 to 1973. The birth rate stabilized at this low level till 1976. Thereafter, it began to increase steadily.

LIMITATIONS

In the lineplot used to visualize birth by year, the years were not represented distinctly on the x-axis. Sns generated intervals instead. Even when year was converted from integer to category, intervals were still displayed. This will be resolved in a future commit.
