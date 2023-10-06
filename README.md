# NYC Property Sales (2016-2017) Visualization
In this comprehensive explanation, we delve into the meticulous design choices that underpin our visualization, providing a clear rationale for their appropriateness in conveying both the data's essence and the intended message.

Our visualization explores four key variables: borough, tax class at present, sale price, and year built. Each variable has been thoughtfully encoded to enhance viewer comprehension:

Borough (Nominal Variable): The boroughs of New York City (Bronx, Brooklyn, Manhattan, Queens, and Staten Island) are depicted along the y-axis, organized in descending alphabetical order. This arrangement is chosen to provide a structured and easily navigable view of the different boroughs.

Tax Class at Present (Ordinal Variable): We employ a gradient of blue colors to depict the tax class at present, transitioning from lighter to darker shades for tax classes 1 through 4. This color scheme effectively communicates the ordinal nature of the variable, ensuring easy comparison between tax classes. The choice of blue, a color often associated with peace and calmness, is deliberate, aiming to provide viewers with a distraction-free and serene viewing experience.

Sale Price (Quantitative Ratio Variable): Sale prices are placed on the y-axis, but to avoid clutter and facilitate a clear view of the data, they are presented on a logarithmic scale. This transformation allows viewers to explore a wide range of sale prices without sacrificing clarity.

Year Built (Quantitative Ordinal Variable): The x-axis represents the year built, with data prior to 1900 filtered out as it constitutes less than 2% of the dataset, ensuring focus on the more relevant and densely populated information.

Regarding the aspects of the visualization:

Main Visualization: We chose a scatterplot to underscore the principle of importance ordering, with year built and sale price as the x and y-axes, respectively. This choice aligns with the quantitative nature of these pivotal features.

Downplayed Aspects: The choice to use a logarithmic scale for sale prices means that the precise values may be somewhat challenging to pinpoint visually. However, this trade-off was made to provide a more comprehensive overview of sale price trends.

Emphasized Aspects: The visualization effectively emphasizes the distribution of tax classes across boroughs through color saturation variations. For example, it highlights that Manhattan predominantly comprises tax class 2 properties, reflecting a prevalence of large residential units like apartments with more than three units. In contrast, Staten Island, primarily consisting of tax class 1, appears to have a higher concentration of one-to-three-unit residential properties. These observations align with the actual demographic distribution of New York boroughs. Additionally, the visualization vividly showcases the disparity in the number of property sales between boroughs, with Brooklyn exhibiting notably more sales than Staten Island.

Label: Labels for select data points provide contextual information about tax class, year built, and sale price. The text boxes are color-matched to the tax class, enhancing clarity.

Aggregations: Average sale prices are aggregated in the top left corner of each scatter plot, offering immediate insight into the price averages for each borough. Furthermore, the most prevalent tax class for each borough is aggregated in the bottom right corner, providing additional context without hindering the scatterplots' visual clarity.

This meticulous and thoughtful approach to data visualization ensures that our design choices align seamlessly with the data's characteristics and the visualization's intended purpose, resulting in a clear, informative, and visually engaging representation of the dataset.
