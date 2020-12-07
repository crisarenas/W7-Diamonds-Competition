# Kaggle Competition
The aim of this project is to make the best prediction od diamond prices in a kaggle competition.
The kaggle competition can be found [here.](https://www.kaggle.com/c/diamonds-datamad1020/submissions)

## Diamond Features:

- **Price**: price in US dollars (\$326--\$18,823)
- **Parat**: weight of the diamond (0.2--5.01)
- **Cut**: quality of the cut (Fair, Good, Very Good, Premium, Ideal)
- **Color**: diamond colour, from J (worst) to D (best)
- **Clarity**: a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
- **x**: length in mm (0--10.74)
- **y**: width in mm (0--58.9)
- **z**: depth in mm (0--31.8)
- **Depth**: total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)
- **Table**: width of top of diamond relative to widest point (43--95)

## Strategy:
The first task that we need to do is the cleaning.
Find correlations, categorical features, standadize data...All of this can be found in the cleaninf notebook.

After cleaning tha data, we tried to find the best prediction. There are some of them that are very good at first, but they can be overfitted since we don't know our y_test.



