# population-segmentation

In this notebook, I'll employ two, unsupervised learning algorithms to do population segmentation.\

Population segmentation aims to find natural groupings in population data that reveal some feature-level similarities between different regions in the US.

Using principal component analysis (PCA) we will reduce the dimensionality of the original census data. Then, we'll use k-means clustering to assign each US county to a particular cluster based on where a county lies in component space. How each cluster is arranged in component space can tell us which US counties are most similar and what demographic traits define that similarity; this information is most often used to inform targeted, marketing campaigns that want to appeal to a specific group of people. This cluster information is also useful for learning more about a population by revealing patterns between regions that we may not have noticed.
