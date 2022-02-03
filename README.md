# Data-Visualization-with-Seaborn

# Distribution Plots

To visualize the distribution of a data set:

distplot

jointplot

pairplot

rugplot

kdeplot


# Categorical Data Plots

To plot categorical data: 

factorplot

boxplot

violinplot

stripplot

swarmplot

barplot

countplot


# Matrix Plots

heatmap

clustermap


# Grids

pairplot

pairplot is a simpler version of PairGrid

Pairgrid is a subplot grid for plotting pairwise relationships in a dataset.

FacetGrid is the general way to create grids of plots based off of a feature: hist/scatter 

g = sns.FacetGrid(tips, col="time",  row="smoker",hue='sex')

Notice the TWO arguments come after plt.scatter call

g = g.map(plt.scatter, "total_bill", "tip").add_legend()

JointGrid is the general version for jointplot() type grids

