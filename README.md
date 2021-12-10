# :star2:Ames Housing Prices : Data Visualization Hands-on:star2:

This work is data visualization hands-on of Ames Housing Prices dataset, downloaded from Kaggle. Even though it looks simple, all plot were created attractively using a few of libraries and methods you may have never heard of before (includes Geospatial Visualization). This work was done in R (Rstudio) and tidyverse environment. Reviewed by my mentor at dibimbing.id wtih score 100/100 as he said, "*The visualization results are already on par with what is expected in the industry*" 👍.

![ide](https://img.shields.io/badge/RStudio-75AADB?style=for-the-badge&logo=RStudio&logoColor=white)
![kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)

## Objectives
Data used in this work is House Sale Prices in Ames, Iowa, USA from 2006-2010, downloaded from [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). Overall, this work visualized :

- Univariate analysis of certain categorical variable
- Univariate analysis of certain numerical variable
- Bivariate analysis between categorical and numerical variable
- Bivariate analysis between numerical and numerical variable
- Geospatial visualization of houses within the dataset

In addition to the plot, the insights obtained from each visualization will also be explained clearly and concisely.

## Libraries
As explained before, this work mainly done using tidyverse environment. However, i also used another libraries to make plots looks more attractive such as :

- [tidyverse](https://www.tidyverse.org/)
- [gghighlight](https://cran.r-project.org/web/packages/gghighlight/vignettes/gghighlight.html)
- [patchwork](https://patchwork.data-imaginist.com/)
- [ggridges](https://cran.r-project.org/web/packages/ggridges/vignettes/introduction.html#:~:text=The%20ggridges%20package%20provides%20two,then%20draws%20those%20using%20ridgelines.)
- [reshape2](https://seananderson.ca/2013/10/19/reshape/)
- [AmesHousing](https://cran.r-project.org/web/packages/AmesHousing/index.html) (extract longitude and latitude informations)
- [jpeg](https://cran.r-project.org/web/packages/jpeg/index.html)
- [grid](https://stat.ethz.ch/R-manual/R-devel/library/grid/html/00Index.html)

## Result preview
#### Map of Neighborhoods in Ames, Iowa
![image](https://user-images.githubusercontent.com/92590596/145498164-fc217959-8f89-4589-b025-ecd048ba0f5a.png)
This is one of geospatial visualization contained in this work.  This map located every neighborhood in Ames, Iowa back at the time.

## References
Credit to these works/videos, that help me by giving insights about this data and visualization method, especially the procedures to create geospatial visualization :

- https://rstudio-pubs-static.s3.amazonaws.com/337439_24918eaefe724411be93e41ede48b256.html

- https://rpubs.com/sknapp/667278

- https://medium.com/upasana-mahanta/exploratory-data-analysis-19feb90ab9e7

- https://www.youtube.com/watch?v=2k8O-Y_uiRU
